#### Test 81316179298ded4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-15 16:20:47.872  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:20:47.892  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-15 16:20:47.897  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-15 16:20:47.937  1502  3490 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-15 16:20:47.937  1502  3490 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-15 16:20:47.937  1502  3490 I GLSUser : [GLSUser] Extracting token using key: Auth
08-15 16:20:47.938  1502  3490 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-15 16:20:47.965  3543  3543 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-15 16:20:47.966  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-15 16:20:47.967  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-15 16:20:48.508  3793  3793 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-15 16:20:48.513  3793  3793 D AndroidRuntime: CheckJNI is OFF
08-15 16:20:48.555  3793  3793 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-15 16:20:48.604  3793  3793 I Radio-JNI: register_android_hardware_Radio DONE
08-15 16:20:48.627  3793  3793 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-15 16:20:48.633   871  2231 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-15 16:20:48.679  2009  2024 W SearchService: Abort, client detached.
08-15 16:20:48.681  3793  3793 D AndroidRuntime: Shutting down VM
08-15 16:20:48.690  2009  2302 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@965d455
08-15 16:20:48.690  2009  2009 I HotwordDetector: Closing mic
08-15 16:20:48.704   871  1478 I ActivityManager: Start proc 3802:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-15 16:20:48.755   375  2311 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-15 16:20:48.761   375  2311 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-15 16:20:48.767   375  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-15 16:20:48.769  2009  2305 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-15 16:20:48.772  2009  2307 I MicroRecognitionRnrImpl: Detection finished
08-15 16:20:48.787  3802  3802 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-15 16:20:48.816  3802  3802 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-15 16:20:48.823  3802  3802 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 48-51)
08-15 16:20:48.823  3802  3802 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 16:20:48.837  3802  3802 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34f1b29}
08-15 16:20:48.838  3802  3802 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 16:20:48.838  3802  3802 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-15 16:20:48.846  3802  3802 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-15 16:20:48.848  3802  3802 E SysUtils: ApplicationContext is null in ApplicationStatus
08-15 16:20:48.864  3802  3802 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-15 16:20:48.875  3802  3802 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-15 16:20:48.875  3802  3802 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-15 16:20:48.876  3802  3802 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-15 16:20:48.876  3802  3802 I Adreno  : Build Date                       : 10/20/15
08-15 16:20:48.876  3802  3802 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-15 16:20:48.876  3802  3802 I Adreno  : Local Branch                     : M14
08-15 16:20:48.876  3802  3802 I Adreno  : Remote Branch                    : 
08-15 16:20:48.876  3802  3802 I Adreno  : Remote Branch                    : 
08-15 16:20:48.876  3802  3802 I Adreno  : Reconstruct Branch               : 
,08-15 16:20:48.925   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23483bd:true
,08-15 16:20:48.977  3802  3802 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-15 16:20:48.991  3802  3802 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-15 16:20:49.044  3802  3840 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-15 16:20:49.052  3802  3827 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-15 16:20:49.085  3802  3840 I OpenGLRenderer: Initialized EGL, version 1.4
,08-15 16:20:49.154   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +473ms
,08-15 16:20:49.161  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-15 16:20:49.232  3802  3802 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3802
,08-15 16:20:49.384  3802  3802 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-15 16:20:49.515   871   882 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #17
08-15 16:20:49.515  3802  3842 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700333264
,08-15 16:20:49.523  3802  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-15 16:20:49.523  3802  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-15 16:20:49.523  3802  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-15 16:20:49.523  3802  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-15 16:20:49.523  3802  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-15 16:20:49.523  3802  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@908b95d added. We now have 1 listener(s)
,08-15 16:20:49.526  3802  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-15 16:20:49.527  3802  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:20:49.527  3802  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:20:49.527  3802  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-15 16:20:49.530  3802  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b882a0 added. We now have 1 listener(s)
,08-15 16:20:49.531  3802  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:20:49.535   871  1306 D WifiService: New client listening to asynchronous messages
,08-15 16:20:49.536  3802  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 16:20:49.536  3802  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-15 16:20:49.536  3802  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-15 16:20:49.536  3802  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-15 16:20:49.536  3802  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
,08-15 16:20:49.547   871   882 I ActivityManager: Killing 3134:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-15 16:20:49.592  3802  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:20:49.592  3802  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-15 16:20:49.609  3802  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:20:49.611  3802  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:20:49.611  3802  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-15 16:20:49.611  3802  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:20:49.612  3802  3842 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-15 16:20:49.626  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:20:49.629  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:20:49.649  3802  3802 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-15 16:20:50.373  3802  3852 W jxcore-log: Initializing JXcore engine
,08-15 16:20:50.373  3802  3852 W jxcore-log: JXcore engine is ready
,08-15 16:20:50.410  3852  3852 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-15 16:20:50.410  3852  3852 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10730]" dev="sockfs" ino=10730 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-15 16:20:50.410  3852  3852 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-15 16:20:50.410  3852  3852 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25884]" dev="sockfs" ino=25884 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-15 16:20:50.424  3802  3852 W jxcore-log: Starting JXcore engine
,08-15 16:20:50.502  3802  3852 W jxcore-log: Platform android
08-15 16:20:50.502  3802  3852 W jxcore-log: 
,08-15 16:20:50.502  3802  3852 W jxcore-log: Process ARCH arm
08-15 16:20:50.502  3802  3852 W jxcore-log: 
,08-15 16:20:50.667  3802  3852 I jxcore-log: JXcore Cordova bridge is ready!
08-15 16:20:50.667  3802  3852 I jxcore-log: 
,08-15 16:20:50.667  3802  3852 W jxcore-log: JXcore engine is started
,08-15 16:20:50.680  3802  3842 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-15 16:20:50.686  3802  3802 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-15 16:20:52.272   871  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-15 16:20:54.595   871  2079 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-15 16:20:55.033  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:20:55.037  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:20:55.074  1502  2265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-15 16:20:55.075  1502  2265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-15 16:20:55.075  1502  2265 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-15 16:20:55.075  1502  2265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-15 16:20:55.101  3002  3859 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-15 16:20:55.101  3002  3859 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jdm.a(PG:82)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jcs.o(PG:406)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jcn.a(PG:1379)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jcs.i(PG:143)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at blb.a(PG:3937)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at czp.a(PG:18188)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at czp.a(PG:9081)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at czq.run(PG:1686)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-15 16:20:55.101  3002  3859 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jdj.a(PG:4091)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jdj.a(PG:1125)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jdm.a(PG:77)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	... 12 more
08-15 16:20:55.101  3002  3859 E HttpOperation: Caused by: faj: BadAuthentication
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at fal.a(PG:38)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	at jdj.a(PG:4089)
08-15 16:20:55.101  3002  3859 E HttpOperation: 	... 14 more
,08-15 16:20:55.174  1502  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-15 16:20:55.174  1502  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-15 16:20:55.174  1502  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-15 16:20:55.174  1502  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-15 16:20:55.187  3002  3859 E HttpOperation: [getmobileexperiments] Unexpected exception
08-15 16:20:55.187  3002  3859 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jdm.a(PG:82)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jcs.o(PG:406)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jcn.a(PG:1379)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jcs.i(PG:143)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at hec.a(PG:42)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at hee.a(PG:102)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at czr.a(PG:65)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at kka.a(PG:108)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at czp.a(PG:19176)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at czp.a(PG:9081)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at czq.run(PG:1686)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-15 16:20:55.187  3002  3859 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jdj.a(PG:4091)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jdj.a(PG:1125)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jdm.a(PG:77)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	... 15 more
08-15 16:20:55.187  3002  3859 E HttpOperation: Caused by: faj: BadAuthentication
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at fal.a(PG:38)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	at jdj.a(PG:4089)
08-15 16:20:55.187  3002  3859 E HttpOperation: 	... 17 more
,08-15 16:20:55.187  3002  3859 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-15 16:20:55.187  3002  3859 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jdm.a(PG:82)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jcs.o(PG:406)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jcn.a(PG:1379)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jcs.i(PG:143)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at hec.a(PG:42)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at hee.a(PG:102)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at czr.a(PG:65)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at kka.a(PG:108)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at czp.a(PG:19176)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at czp.a(PG:9081)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at czq.run(PG:1686)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jdj.a(PG:4091)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jdj.a(PG:1125)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jdm.a(PG:77)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	... 15 more
08-15 16:20:55.187  3002  3859 E ExperimentLoader: Caused by: faj: BadAuthentication
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at fal.a(PG:38)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	at jdj.a(PG:4089)
08-15 16:20:55.187  3002  3859 E ExperimentLoader: 	... 17 more
,08-15 16:20:55.270   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125267, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-15 16:21:01.146  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-15 16:21:01.146  3802  3852 I jxcore-log: 
,08-15 16:21:01.148  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-15 16:21:01.148  3802  3852 I jxcore-log: 
,08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.159  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:01.165  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-15 16:21:01.167  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-15 16:21:01.167  3802  3852 I jxcore-log: 
,08-15 16:21:01.169  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-15 16:21:01.169  3802  3852 I jxcore-log: 
,08-15 16:21:01.494  3802  3852 D ExecuteNativeTests: Running unit tests
,08-15 16:21:01.553  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:21:01.554  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 added. We now have 2 listener(s)
,08-15 16:21:01.555  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:21:01.555  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-15 16:21:01.555  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:01.555  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:21:01.555  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 added. We now have 2 listener(s)
08-15 16:21:01.555  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:01.556  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 16:21:01.562  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.574  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:01.579  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.579  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:21:01.581  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 16:21:01.581  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:21:01.582  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:21:01.583  3802  3852 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-15 16:21:01.583  3802  3852 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-15 16:21:01.583  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-15 16:21:01.583  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-15 16:21:01.583  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-15 16:21:01.584  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:21:01.584  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:01.584  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.584  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.585  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.585  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-15 16:21:01.585  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-15 16:21:01.585  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 removed from the list
,08-15 16:21:01.585  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.585  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 removed from the list
,08-15 16:21:01.587  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:01.588  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:01.588  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.589  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.589  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.596  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 16:21:01.596  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.596  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.596  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.598  3802  3852 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-15 16:21:01.598  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-15 16:21:01.598  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.598  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.599  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:01.599  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.599  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.599  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.599  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.599  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.604  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:01.604  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.604  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.604  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.604  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.604  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.606  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.606  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.606  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.606  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.610  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-15 16:21:01.610  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-15 16:21:01.611  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-15 16:21:01.613  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-15 16:21:01.613  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-15 16:21:01.613  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingC,onnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-15 16:21:01.614  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-15 16:21:01.614  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.614  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.614  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.615  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.615  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.615  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.615  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.615  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.615  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.615  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.615  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.615  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.615  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.615  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.619  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.619  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.619  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.619  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.620  3802  3852 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 16:21:01.622  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.626  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:21:01.629  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.629  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:21:01.630  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:21:01.630  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:21:01.630  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:21:01.630  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.630  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:21:01.632  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:01.634  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-15 16:21:01.634  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 16:21:01.636  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:01.640  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:21:01.642  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-15 16:21:01.642  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 16:21:01.645  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-15 16:21:01.648  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-15 16:21:01.648  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-15 16:21:01.648  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-15 16:21:01.649  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-15 16:21:01.650  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:01.656  2645  2783 D BtGatt.GattService: registerClient() - UUID=0f5c148b-b0e6-4347-89cc-f3186641a71a
08-15 16:21:01.656  2645  2679 D BtGatt.GattService: onClientRegistered() - UUID=0f5c148b-b0e6-4347-89cc-f3186641a71a, clientIf=5
08-15 16:21:01.657  3802  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-15 16:21:01.658  2645  2659 D BtGatt.GattService: start scan with filters
,08-15 16:21:01.662  2645  2682 D BtGatt.ScanManager: handling starting scan
08-15 16:21:01.662  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-15 16:21:01.662  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-15 16:21:01.663  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-15 16:21:01.663  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-15 16:21:01.664  2645  2682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
08-15 16:21:01.665  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-15 16:21:01.666  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-15 16:21:01.667  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-15 16:21:01.668  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-15 16:21:01.671  2645  2679 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-15 16:21:01.671  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.671  3802  3852 I io.jxcore.node.ConnectionHelper: start: OK
08-15 16:21:01.671  2645  2682 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-15 16:21:01.674  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.674  3802  3852 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-15 16:21:01.674  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.674  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-15 16:21:01.674  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.674  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-15 16:21:01.674  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-15 16:21:01.675  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 16:21:01.675  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 16:21:01.675  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:01.676  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-15 16:21:01.676  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-15 16:21:01.677  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:01.677  2645  2783 D BtGatt.GattService: stopScan() - queue size =1
08-15 16:21:01.678  2645  2659 D BtGatt.GattService: unregisterClient() - clientIf=5
08-15 16:21:01.678  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:21:01.678  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-15 16:21:01.678  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-15 16:21:01.678  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-15 16:21:01.678  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-15 16:21:01.679  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:01.680  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-15 16:21:01.680  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 16:21:01.680  2645  2679 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-15 16:21:01.680  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.680  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:21:01.680  2645  2682 D BtGatt.ScanManager: Starting BLE batch scan
08-15 16:21:01.680  2645  2682 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-15 16:21:01.681  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:01.681  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:01.681  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:01.682  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:01.682  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.682  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.682  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:01.682  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.682  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.682  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.682  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.682  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.683  3802  3852 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 16:21:01.684  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.690  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:21:01.692  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.692  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:21:01.694  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:21:01.694  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:21:01.694  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:21:01.694  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.694  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 16:21:01.694  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:01.696  2645  2679 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-15 16:21:01.696  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.697  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:01.699  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-15 16:21:01.699  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-15 16:21:01.703  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:21:01.704  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-15 16:21:01.704  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 16:21:01.706  2645  2679 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-15 16:21:01.706  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.709  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-15 16:21:01.709  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-15 16:21:01.709  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-15 16:21:01.710  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:01.713  2645  2659 D BtGatt.GattService: registerClient() - UUID=ce7dcaa0-5c39-44a3-aa90-c0f21615d4f7
08-15 16:21:01.713  2645  2679 D BtGatt.GattService: onClientRegistered() - UUID=ce7dcaa0-5c39-44a3-aa90-c0f21615d4f7, clientIf=5
08-15 16:21:01.714  3802  3813 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-15 16:21:01.714  2645  2783 D BtGatt.GattService: start scan with filters
08-15 16:21:01.715  2645  2679 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-15 16:21:01.715  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.715  2645  2682 D BtGatt.ScanManager: stopping BLe Batch
08-15 16:21:01.719  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-15 16:21:01.720  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-15 16:21:01.720  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-15 16:21:01.720  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-15 16:21:01.722  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-15 16:21:01.723  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-15 16:21:01.723  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-15 16:21:01.724  2645  2679 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-15 16:21:01.724  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.725  2645  2682 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-15 16:21:01.725  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-15 16:21:01.728  3802  3852 I io.jxcore.node.ConnectionHelper: start: OK
08-15 16:21:01.732  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.732  3802  3852 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-15 16:21:01.732  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.732  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-15 16:21:01.732  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.732  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-15 16:21:01.732  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-15 16:21:01.732  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 16:21:01.732  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 16:21:01.733  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:01.733  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-15 16:21:01.733  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-15 16:21:01.733  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:01.734  2645  2679 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-15 16:21:01.734  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.734  2645  2783 D BtGatt.GattService: stopScan() - queue size =0
,08-15 16:21:01.735  2645  2657 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-15 16:21:01.736  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:21:01.736  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-15 16:21:01.736  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-15 16:21:01.736  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-15 16:21:01.736  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-15 16:21:01.736  2645  2682 D BtGatt.ScanManager: handling starting scan
,08-15 16:21:01.738  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-15 16:21:01.738  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-15 16:21:01.738  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-15 16:21:01.738  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-15 16:21:01.739  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-15 16:21:01.740  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-15 16:21:01.740  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-15 16:21:01.740  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-15 16:21:01.740  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.740  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.740  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:01.740  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.740  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.741  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.741  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.741  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.741  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.742  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.743  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.743  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.743  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.743  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.744  3802  3852 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 16:21:01.746  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.746  2645  2679 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-15 16:21:01.746  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.747  2645  2682 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.751  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:21:01.754  2645  2679 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-15 16:21:01.754  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.754  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:01.754  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:21:01.754  2645  2682 D BtGatt.ScanManager: Starting BLE batch scan
,08-15 16:21:01.755  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-15 16:21:01.755  2645  2682 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-15 16:21:01.755  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-15 16:21:01.755  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-15 16:21:01.755  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.755  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-15 16:21:01.757  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.759  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-15 16:21:01.759  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-15 16:21:01.760  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.764  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-15 16:21:01.765  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-15 16:21:01.765  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 16:21:01.767  2645  2679 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-15 16:21:01.767  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.770  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-15 16:21:01.770  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-15 16:21:01.770  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-15 16:21:01.771  3802  3852 D BluetoothAdapter: STATE_ON
,08-15 16:21:01.774  2645  2763 D BtGatt.GattService: registerClient() - UUID=6086af64-5815-403a-aab0-aaeab959debb
08-15 16:21:01.774  2645  2679 D BtGatt.GattService: onClientRegistered() - UUID=6086af64-5815-403a-aab0-aaeab959debb, clientIf=5
,08-15 16:21:01.774  3802  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-15 16:21:01.775  2645  2783 D BtGatt.GattService: start scan with filters
,08-15 16:21:01.776  2645  2679 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-15 16:21:01.776  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.778  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-15 16:21:01.778  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-15 16:21:01.779  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-15 16:21:01.779  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-15 16:21:01.782  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-15 16:21:01.782  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:01.783  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-15 16:21:01.784  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-15 16:21:01.786  2645  2679 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-15 16:21:01.787  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.787  2645  2682 D BtGatt.ScanManager: stopping BLe Batch
,08-15 16:21:01.787  3802  3852 I io.jxcore.node.ConnectionHelper: start: OK,
08-15 16:21:01.787  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:21:01.787  3802  3852 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-15 16:21:01.788  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:01.788  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-15 16:21:01.788  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:01.788  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-15 16:21:01.788  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-15 16:21:01.788  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-15 16:21:01.788  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 16:21:01.788  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:01.788  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-15 16:21:01.788  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-15 16:21:01.789  3802  3852 D BluetoothAdapter: STATE_ON
,08-15 16:21:01.789  2645  2783 D BtGatt.GattService: stopScan() - queue size =0
08-15 16:21:01.790  2645  2657 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-15 16:21:01.791  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:21:01.791  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-15 16:21:01.791  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-15 16:21:01.791  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-15 16:21:01.791  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-15 16:21:01.793  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:01.793  2645  2679 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-15 16:21:01.794  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.794  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-15 16:21:01.794  2645  2682 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-15 16:21:01.794  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 16:21:01.794  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:21:01.794  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-15 16:21:01.796  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:01.796  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-15 16:21:01.796  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.796  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-15 16:21:01.796  3802  3852 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-15 16:21:01.796  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.797  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 16:21:01.797  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.797  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:01.797  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:01.797  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.797  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.797  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.797  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:01.798  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.798  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.798  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.800  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.800  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:01.800  2645  2679 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-15 16:21:01.800  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.800  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.800  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.801  3802  3852 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-15 16:21:01.801  2645  2682 D BtGatt.ScanManager: handling starting scan
,08-15 16:21:01.802  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.802  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.802  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.802  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:01.802  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.803  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.803  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.803  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.803  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.803  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.803  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.803  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.803  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.803  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.805  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.805  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.805  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.805  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.807  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-15 16:21:01.807  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.807  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.807  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.807  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.807  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.807  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.808  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.808  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.808  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.808  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:01.808  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.808  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.808  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.808  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.809  2645  2679 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-15 16:21:01.809  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.809  2645  2682 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-15 16:21:01.810  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.810  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:01.810  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.810  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.811  3802  3852 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-15 16:21:01.811  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.811  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.811  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 16:21:01.811  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.812  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.812  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.812  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.812  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.812  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.812  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.813  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.813  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.813  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.813  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.814  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.814  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.814  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.814  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.816  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-15 16:21:01.816  2645  2679 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-15 16:21:01.816  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.816  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.816  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:01.816  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.816  2645  2682 D BtGatt.ScanManager: Starting BLE batch scan
08-15 16:21:01.816  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.816  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.816  2645  2682 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-15 16:21:01.816  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.816  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.817  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.817  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.817  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.817  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.817  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.817  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:01.817  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.818  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.819  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.819  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.819  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.820  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 16:21:01.822  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:21:01.822  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 16:21:01.822  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 16:21:01.822  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 16:21:01.822  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 16:21:01.823  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:21:01.823  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.823  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.824  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.824  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.824  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.824  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.824  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.824  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.824  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.824  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.825  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.825  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.825  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.828  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.829  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:01.829  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.829  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.830  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-15 16:21:01.831  3802  3852 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-15 16:21:01.831  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-15 16:21:01.836  2645  2679 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-15 16:21:01.836  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.836  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-15 16:21:01.837  3802  3852 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-15 16:21:01.837  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-15 16:21:01.838  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-15 16:21:01.839  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-15 16:21:01.840  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-15 16:21:01.840  3802  3852 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 16:21:01.840  3802  3852 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-15 16:21:01.840  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:21:01.840  3802  3852 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 16:21:01.840  3802  3852 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-15 16:21:01.840  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 16:21:01.840  3802  3852 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-15 16:21:01.840  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-15 16:21:01.843  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-15 16:21:01.844  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-15 16:21:01.844  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-15 16:21:01.845  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-15 16:21:01.845  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-15 16:21:01.845  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-15 16:21:01.845  3802  3852 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-15 16:21:01.845  3802  3852 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-15 16:21:01.846  2645  2679 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-15 16:21:01.846  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.846  3802  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
08-15 16:21:01.846  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.846  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.846  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.846  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.847  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.847  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.847  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-15 16:21:01.848  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.848  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.848  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.848  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.848  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.848  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.848  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.849  3802  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:21:01.849  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.849  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.849  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:01.849  3802  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
08-15 16:21:01.850  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.850  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.850  3802  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
08-15 16:21:01.850  3802  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
08-15 16:21:01.850  3802  3852 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-15 16:21:01.850  3802  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
08-15 16:21:01.851  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.851  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:01.851  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.851  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.851  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.851  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.851  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.851  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.851  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.852  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:01.852  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.852  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.852  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.852  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.855  2645  2679 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-15 16:21:01.855  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:01.856  2645  2682 D BtGatt.ScanManager: stopping BLe Batch
08-15 16:21:01.856  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.857  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.857  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.857  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.857  3802  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-15 16:21:01.858  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.858  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.858  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.858  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.858  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:01.858  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.858  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.858  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.858  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.859  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.859  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.859  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.859  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.859  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.860  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.860  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.860  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.860  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.861  3802  3852 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-15 16:21:01.861  3802  3852 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-15 16:21:01.861  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 16:21:01.861  3802  3852 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-15 16:21:01.861  3802  3852 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-15 16:21:01.861  3802  3852 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-15 16:21:01.861  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 16:21:01.861  3802  3852 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-15 16:21:01.862  3802  3852 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-15 16:21:01.862  3802  3852 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-15 16:21:01.862  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 16:21:01.862  3802  3852 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-15 16:21:01.862  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.862  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.862  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.862  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:01.862  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.862  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.863  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.863  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.863  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.863  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.863  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.863  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.863  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.863  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.864  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.864  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.864  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.864  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.864  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.864  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.864  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.865  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.865  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.865  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.865  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.865  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:01.865  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.865  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.865  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.865  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.865  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.865  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.865  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.865  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.865  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.866  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.866  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.866  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.866  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.866  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.866  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.866  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.866  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.866  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.866  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.866  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.866  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.867  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.867  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.868  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.868  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.868  2645  2679 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-15 16:21:01.868  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.868  2645  2682 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-15 16:21:01.869  3802  3852 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-15 16:21:01.869  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:01.870  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-15 16:21:01.870  3802  3852 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-15 16:21:01.870  3802  3852 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-15 16:21:01.871  3802  3802 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-15 16:21:01.871  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-15 16:21:01.871  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-15 16:21:01.871  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.871  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-15 16:21:01.871  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-15 16:21:01.872  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-15 16:21:01.872  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.872  3802  3852 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-15 16:21:01.872  3802  3802 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-15 16:21:01.872  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.872  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.872  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-15 16:21:01.872  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 16:21:01.872  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:01.872  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.873  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.873  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-15 16:21:01.874  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:01.874  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:01.874  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:01.874  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.874  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.874  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.874  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.874  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:01.874  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.874  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.875  2645  2679 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-15 16:21:01.875  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.875  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.875  2645  2679 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:01.875  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.875  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:01.875  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.875  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.875  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.875  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.876  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.876  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:01.876  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.876  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.877  3802  3852 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-15 16:21:01.877  3802  3852 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-15 16:21:01.877  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 16:21:01.878  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-15 16:21:01.878  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.878  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.878  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:01.878  3802  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-15 16:21:01.879  3802  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-15 16:21:01.879  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.879  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.879  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.879  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
08-15 16:21:01.879  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.879  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.880  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.880  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.880  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.880  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.880  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.881  3802  3802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-15 16:21:01.882  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.882  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.882  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.882  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.886  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:21:01.886  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:01.886  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 16:21:01.886  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:01.886  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.886  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.886  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list
,08-15 16:21:01.886  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.886  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.887  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:01.887  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.887  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.887  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.887  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:01.888  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.888  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.888  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:01.888  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.889  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:01.889  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:01.889  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 16:21:01.889  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:01.889  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.889  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.889  3802  3852 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bcc3b1 not in the list,
08-15 16:21:01.889  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:01.889  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
,08-15 16:21:01.889  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:01.889  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:01.889  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.890  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:01.890  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:01.891  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:01.891  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:01.891  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-15 16:21:01.891  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57096 not in the list
08-15 16:21:01.892  3802  3852 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-15 16:21:01.892  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 16:21:01.892  3802  3852 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-15 16:21:01.892  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 16:21:01.892  3802  3852 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-15 16:21:01.892  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 16:21:01.894  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-15 16:21:01.894  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-15 16:21:01.895  3802  3852 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-15 16:21:01.895  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-15 16:21:01.895  3802  3852 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-15 16:21:01.895  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-15 16:21:01.895  3802  3852 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-15 16:21:01.895  3802  3852 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-15 16:21:01.896  3802  3852 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-15 16:21:01.896  3802  3852 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-15 16:21:01.896  3802  3852 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-15 16:21:01.896  3802  3852 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-15 16:21:01.897  3802  3852 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-15 16:21:01.897  3802  3852 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-15 16:21:01.897  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:01.897  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69f0588 added. We now have 2 listener(s)
08-15 16:21:01.898  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:01.900  3802  3852 D BluetoothAdapter: enable(): BT is already enabled..!
08-15 16:21:01.900   871  1677 D WifiService: setWifiEnabled: true pid=3802, uid=10000
08-15 16:21:01.900   871  1677 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:21:01.901  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:01.901  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@494fb21 added. We now have 3 listener(s)
08-15 16:21:01.901  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:01.909  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:21:01.909  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4792b46 added. We now have 4 listener(s)
08-15 16:21:01.909  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:01.911  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:21:01.911  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eaf107 added. We now have 5 listener(s)
08-15 16:21:01.911  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:01.913   871  2231 D WifiService: setWifiEnabled: false pid=3802, uid=10000
,08-15 16:21:01.913   871  2231 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:21:01.917  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:21:01.918  2645  2675 D BluetoothAdapterState: Current state: ON, message: 23
,08-15 16:21:01.918  2645  2675 D BluetoothAdapterProperties: Setting state to 13
08-15 16:21:01.918  2645  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-15 16:21:01.919  2645  2675 D BluetoothAdapterProperties: onBluetoothDisable()
,08-15 16:21:01.921  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.921  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:01.921  2645  2675 I BluetoothAdapterState: Entering PendingCommandState
08-15 16:21:01.922  2645  2679 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:21:01.923  2645  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-15 16:21:01.923  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:01.923  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:01.923  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:21:01.926  2645  2645 D BluetoothMapService: onReceive
,08-15 16:21:01.926  2645  2645 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:21:01.926  2645  2645 D BluetoothMapService: STATE_TURNING_OFF
08-15 16:21:01.927  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.928  2645  2645 D BluetoothMapService: MAP Service closeService in
,08-15 16:21:01.928  2645  2645 D BluetoothMapMasInstance0: MAP Service shutdown
08-15 16:21:01.929  2645  2645 D ObexServerSockets0: shutdown(block = true)
,08-15 16:21:01.929  2645  2645 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-15 16:21:01.929  2645  2645 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-15 16:21:01.929  2645  2758 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-15 16:21:01.930  2645  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-15 16:21:01.930  2645  2786 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-15 16:21:01.931  2645  2645 I BtOppRfcommListener: stopping Accept Thread,
08-15 16:21:01.931  2645  3487 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:21:01.933  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 16:21:01.933  2645  3487 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-15 16:21:01.934   871  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-15 16:21:01.934   871  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-15 16:21:01.934   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-15 16:21:01.935   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:01.942   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-15 16:21:01.942   871  2088 D DhcpClient: Clearing IP address
,08-15 16:21:01.945  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.949  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:01.949  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:21:01.949  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:01.950  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:01.951  1502  2531 V NativeCrypto: Read error: ssl=0x9af86400: I/O error during system call, Connection timed out
,08-15 16:21:01.952  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.947   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:01.955  1502  2531 V NativeCrypto: SSL shutdown failed: ssl=0x9af86400: I/O error during system call, Broken pipe
,08-15 16:21:01.955  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.959  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:01.960   871  3035 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-15 16:21:01.961   871  2076 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-15 16:21:01.962   871  2076 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-15 16:21:01.962   871   884 I ActivityManager: Start proc 3868:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-15 16:21:01.963   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-15 16:21:01.963   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-15 16:21:01.964  2645  2645 D HeadsetService: Received stop request...Stopping profile...
,08-15 16:21:01.965   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-15 16:21:01.966  1362  1375 D BluetoothHeadset: Proxy object disconnected
,08-15 16:21:01.966   871   871 D BluetoothHeadset: Proxy object disconnected
,08-15 16:21:01.966   871   871 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:01.967   871   871 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:01.967  1942  2033 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:01.974   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED,
08-15 16:21:01.974   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-15 16:21:01.976  2645  2645 D A2dpService: Received stop request...Stopping profile...
08-15 16:21:01.976  2645  2766 D A2dpStateMachine: Exit Disconnected: -1,
08-15 16:21:01.976   456   456 E Parcel  : Reading a NULL string not supported here.
08-15 16:21:01.980  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,08-15 16:21:01.981   871   871 D BluetoothA2dp: Proxy object disconnected
08-15 16:21:01.981  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-15 16:21:01.982   871  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-15 16:21:01.982  2645  2645 V BluetoothAdapterState: isTurningOff()=true
,08-15 16:21:01.982  2645  2645 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:01.982  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:01.982   871  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-15 16:21:01.982  2645  2645 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:01.982   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-15 16:21:01.985  2645  2645 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-15 16:21:01.985  2645  2645 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-15 16:21:01.985  2645  2679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-15 16:21:01.985  2645  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:01.985  2645  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-15 16:21:01.985  2645  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:01.985  2645  2679 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-15 16:21:01.986   871  2132 D DhcpClient: Receive thread stopped
08-15 16:21:01.986  2645  2645 D HidService: Received stop request...Stopping profile...
,08-15 16:21:01.986  2645  2645 D HidService: Stopping Bluetooth HidService,
,08-15 16:21:01.986   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-15 16:21:01.987  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,08-15 16:21:01.987  1362  1362 D HidProfile: Bluetooth service disconnected
,08-15 16:21:01.987  2645  2645 D HealthService: Received stop request...Stopping profile...
,08-15 16:21:01.989  2645  2645 D PanService: Received stop request...Stopping profile...
08-15 16:21:01.991  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-15 16:21:01.991  2645  2645 D BluetoothMapService: Received stop request...Stopping profile...
,08-15 16:21:01.991  2645  2645 D BluetoothMapService: stop()
,08-15 16:21:01.991  1362  1362 D PanProfile: Bluetooth service disconnected
08-15 16:21:01.993  2645  2645 D BluetoothMapAppObserver: deinitObservers()
,08-15 16:21:01.993  2645  2645 D BluetoothMapAppObserver: removeReceiver()
,08-15 16:21:01.995   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-15 16:21:01.999   871  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-15 16:21:02.007  2645  2645 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:02.007  2645  2645 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:02.007  1362  1362 D BluetoothMap: Proxy object disconnected
08-15 16:21:02.007  1362  1362 D MapProfile: Bluetooth service disconnected
08-15 16:21:02.007  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:02.008  2645  2645 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:02.009  2645  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:02.009  2645  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-15 16:21:02.009  2645  2645 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:02.009  2645  2645 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:02.009  2645  2740 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:21:02.009  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:02.009  2645  2740 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:21:02.009  2645  2740 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 16:21:02.009  2645  2645 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:02.009  2645  2740 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-15 16:21:02.009  2645  2679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-15 16:21:02.009  2645  2645 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-15 16:21:02.009  2645  2645 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object,
08-15 16:21:02.009  2645  2645 V BluetoothAdapterState: isTurningOff()=true
,08-15 16:21:02.009  2645  2645 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:02.010  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:02.010  2645  2645 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:02.010  2645  2645 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-15 16:21:02.010  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:02.010  2645  2679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:02.011  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:21:02.011  2645  2679 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-15 16:21:02.011  2645  2645 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-15 16:21:02.011  2645  2645 V BluetoothAdapterState: isTurningOff()=true
,08-15 16:21:02.011  2645  2645 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:02.011  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:02.011  2645  2645 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:02.012  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:02.012  2645  2645 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-15 16:21:02.012  2645  2645 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-15 16:21:02.012  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:02.013  2645  2645 D BluetoothMapService: MAP Service closeService in
,08-15 16:21:02.013  2645  2645 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:02.013  2645  2645 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:02.013  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:02.013  2645  2645 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:02.014  2645  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-15 16:21:02.014  2645  2675 D BluetoothAdapterProperties: Setting state to 15
,08-15 16:21:02.014  2645  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-15 16:21:02.014   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-15 16:21:02.014   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-15 16:21:02.014  1362  1388 D BluetoothPbap: onBluetoothStateChange: up=false
,08-15 16:21:02.015  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:02.015  2645  2675 I BluetoothAdapterState: Entering BleOnState
,08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:02.015  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:21:02.016  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:02.016  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:02.016  2645  2645 D BluetoothMapService: cleanup()
08-15 16:21:02.016  2645  2645 D BluetoothMapService: MAP Service closeService in
08-15 16:21:02.016  1362  1385 D BluetoothPan: onBluetoothStateChange on: false
,08-15 16:21:02.017  1942  2033 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:02.018  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-15 16:21:02.018  1362  2035 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:21:02.019   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:02.019   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:02.019  1362  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:02.019  1362  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-15 16:21:02.020  2645  2675 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-15 16:21:02.020  2645  2675 D BluetoothAdapterProperties: Setting state to 16
08-15 16:21:02.020  2645  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-15 16:21:02.020  2645  2675 D BluetoothAdapterProperties: onBleDisable
08-15 16:21:02.020  2645  2675 I BluetoothAdapterState: Entering PendingCommandState
08-15 16:21:02.020  2645  2676 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-15 16:21:02.021  2645  2679 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:21:02.021  2645  2740 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-15 16:21:02.021  2645  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:02.022  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:02.024  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:02.025  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:02.032  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:02.038   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-15 16:21:02.039  1878  2257 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:21:02.055   871   880 I art     : Background partial concurrent mark sweep GC freed 48019(2MB) AllocSpace objects, 12(232KB) LOS objects, 33% free, 29MB/43MB, paused 992us total 126.970ms
,08-15 16:21:02.067  3868  3868 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-15 16:21:02.067   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:02.068   871  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-15 16:21:02.068   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:02.071   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-15 16:21:02.072  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:02.074  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:02.074  3423  3423 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@908b95d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-15 16:21:02.075  2009  2009 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-15 16:21:02.086  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-15 16:21:02.090  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 16:21:02.093   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fad526e:true
,08-15 16:21:02.103   871  1959 I ActivityManager: Start proc 3889:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-15 16:21:02.122   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-15 16:21:02.123   871  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-15 16:21:02.123   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-15 16:21:02.125  3868  3868 D LocalBluetoothProfileManager: Adding local MAP profile
,08-15 16:21:02.127  3868  3868 D BluetoothMap: Create BluetoothMap proxy object
,08-15 16:21:02.133  3868  3868 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-15 16:21:02.138  3889  3889 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-15 16:21:02.147  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:21:02.154   871  2233 I ActivityManager: Killing 3245:com.google.android.gm/u0a78 (adj 15): empty #17
,08-15 16:21:02.226  2645  2679 I bt_hci  : shut_down
,08-15 16:21:02.226  2645  2683 D bt_hwcfg: hw_epilog_process
,08-15 16:21:02.227  2645  2683 I bt_vendor: low_power_mode_cb
,08-15 16:21:02.253  2645  2683 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-15 16:21:02.254  2645  2683 I bt_vendor: epilog_cb
08-15 16:21:02.254  2645  2683 I bt_hci  : epilog_finished_callback
,08-15 16:21:02.260  2645  2679 I bt_hci_h4: hal_close
,08-15 16:21:02.261  2645  2679 I bt_userial_vendor: device fd = 51 close
,08-15 16:21:02.327  3889  3889 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.327  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.328  3889  3889 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.328  3889  3889 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.328  3889  3889 D StrictMode: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.328  3889  3889 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.328  3889  3889 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:583)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.328  3889  3889 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.328  3889  3889 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.328  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.331  3889  3889 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:02.331  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:02.374   871  1678 I ActivityManager: Start proc 3919:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-15 16:21:02.375  3802  3802 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-15 16:21:02.377   871  1678 I ActivityManager: Killing 3423:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-15 16:21:02.505  3889  3914 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-15 16:21:02.518  2645  2676 D bt_stack_manager: event_shut_down_stack finished.
,08-15 16:21:02.518  2645  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-15 16:21:02.527  3919  3919 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-15 16:21:02.534  2645  2645 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-15 16:21:02.533  2645  2675 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-15 16:21:02.536  2645  2645 D BtGatt.GattService: Received stop request...Stopping profile...
08-15 16:21:02.537  2645  2645 D BtGatt.GattService: stop()
08-15 16:21:02.538  2645  2645 D BtGatt.AdvertiseManager: advertise clients cleared
08-15 16:21:02.540  2645  2645 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:02.540  2645  2645 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:02.541  2645  2645 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:02.541  2645  2645 V BluetoothAdapterState: isBleTurningOff()=true
08-15 16:21:02.541  2645  2675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-15 16:21:02.542  2645  2675 D BluetoothAdapterProperties: Setting state to 10
,08-15 16:21:02.542  2645  2675 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-15 16:21:02.543  2645  2675 I BluetoothAdapterState: Entering OffState
08-15 16:21:02.544   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-15 16:21:02.553  2645  2645 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-15 16:21:02.553  2645  2645 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-15 16:21:02.553  2645  2676 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-15 16:21:02.555  2645  2676 D bt_stack_manager: event_clean_up_stack finished.
08-15 16:21:02.555  2645  2645 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-15 16:21:02.565  2645  2645 I art     : System.exit called, status: 0
08-15 16:21:02.565  2645  2645 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-15 16:21:02.618   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e9f4d0:true
,08-15 16:21:02.634  3919  3919 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-15 16:21:02.636   871  1369 I ActivityManager: Process com.android.bluetooth (pid 2645) has died
,08-15 16:21:02.656  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-15 16:21:02.675   871  1678 I ActivityManager: Start proc 3948:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-15 16:21:02.679  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:21:02.783  3948  3948 D AdapterServiceConfig: Adding HeadsetService
08-15 16:21:02.784  3948  3948 D AdapterServiceConfig: Adding A2dpService
08-15 16:21:02.784  3948  3948 D AdapterServiceConfig: Adding HidService
08-15 16:21:02.784  3948  3948 D AdapterServiceConfig: Adding HealthService
08-15 16:21:02.784  3948  3948 D AdapterServiceConfig: Adding PanService
,08-15 16:21:02.784  3948  3948 D AdapterServiceConfig: Adding GattService
,08-15 16:21:02.786  3948  3948 D AdapterServiceConfig: Adding BluetoothMapService
,08-15 16:21:02.789   871  1959 I ActivityManager: Killing 2769:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-15 16:21:02.823  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 16:21:02.851  1708  1708 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-15 16:21:02.855  1708  1708 D SystemUpdateService: onCreate
,08-15 16:21:02.862  1708  1708 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-15 16:21:02.879  1708  3960 I SystemUpdateService: active receiver: enabled
,08-15 16:21:02.882  1708  3960 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-15 16:21:02.883  1708  3960 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-15 16:21:02.883  1708  3960 I SystemUpdateService: now status is 0 (complete)
08-15 16:21:02.883  1708  3960 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-15 16:21:02.883  1708  3960 I SystemUpdateService: file has been verified
08-15 16:21:02.884  1708  3960 I SystemUpdateService: OTA package size = 12249756
,08-15 16:21:02.887  1708  3960 I SystemUpdateService: showing system update notification
,08-15 16:21:02.900  1708  1708 D SystemUpdateService: onDestroy
,08-15 16:21:02.902  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-15 16:21:02.905  1708  2509 I iu.UploadsManager: num queued entries: 0
,08-15 16:21:02.905  1708  2509 I iu.UploadsManager: num updated entries: 0
,08-15 16:21:02.907  1708  2509 I iu.SyncManager: NEXT; no task
,08-15 16:21:02.909  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-15 16:21:02.910  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-15 16:21:02.925   871  2232 I ActivityManager: Start proc 3962:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-15 16:21:02.959  3962  3962 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-15 16:21:02.962  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:02.968  3962  3962 D SprintDMHelper: simOperator: 
,08-15 16:21:02.968  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-15 16:21:02.987   871  1959 I ActivityManager: Start proc 3974:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-15 16:21:02.990   871  1959 I ActivityManager: Killing 1688:android.process.acore/u0a5 (adj 15): empty #17
,08-15 16:21:03.097  2193  3988 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-15 16:21:03.136   871  1678 I ActivityManager: Start proc 3989:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-15 16:21:03.143   871  1678 I ActivityManager: Killing 3655:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-15 16:21:03.240  3989  3989 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-15 16:21:03.300  3989  3989 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-15 16:21:03.300  3989  3989 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-15 16:21:03.300  3989  3989 I GAv4    :   adb logcat -s GAv4
,08-15 16:21:03.317  3989  3989 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-15 16:21:03.324  3989  3989 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-15 16:21:03.353  3989  4006 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-15 16:21:03.461  3989  3989 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-15 16:21:03.500  3989  3989 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-15 16:21:03.507  3989  3989 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4732-4735)
,08-15 16:21:03.508  3989  3989 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-15 16:21:03.520  3989  3989 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f8fb3cd}
,08-15 16:21:03.520  3989  3989 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-15 16:21:03.520  3989  3989 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-15 16:21:03.529  3989  3989 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-15 16:21:03.531  3989  3989 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-15 16:21:03.547  3989  3989 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-15 16:21:03.562  3989  3989 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-15 16:21:03.562  3989  3989 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-15 16:21:03.562  3989  3989 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-15 16:21:03.562  3989  3989 I Adreno  : Build Date                       : 10/20/15
08-15 16:21:03.562  3989  3989 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-15 16:21:03.562  3989  3989 I Adreno  : Local Branch                     : M14
08-15 16:21:03.562  3989  3989 I Adreno  : Remote Branch                    : 
08-15 16:21:03.562  3989  3989 I Adreno  : Remote Branch                    : 
08-15 16:21:03.562  3989  3989 I Adreno  : Reconstruct Branch               : 
,08-15 16:21:03.622  3989  3989 I NSApplication: Starting up...
,08-15 16:21:03.631  3989  4035 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-15 16:21:03.657   871  1959 I ActivityManager: Start proc 4040:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-15 16:21:03.661   871  1959 I ActivityManager: Killing 3669:com.android.musicfx/u0a18 (adj 15): empty #17
,08-15 16:21:03.765  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-15 16:21:03.953   871  3034 I ActivityManager: Killing 3450:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-15 16:21:04.926   871  2232 D WifiService: setWifiEnabled: true pid=3802, uid=10000
,08-15 16:21:04.926   871  2232 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:21:04.942   871  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-15 16:21:04.951  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:04.952  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:04.952  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:04.953  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:21:04.956  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:04.957  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:04.957  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:04.957  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:04.983   871  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-15 16:21:04.984   871  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-15 16:21:04.985   871  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-15 16:21:04.986   871  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-15 16:21:04.986   871  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-15 16:21:04.986   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-15 16:21:04.987   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-15 16:21:04.998   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-15 16:21:04.999   871  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.62 rxSuccessRate=15.88 delta 1000 -> 994
,08-15 16:21:05.000   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:05.001   871  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-15 16:21:05.001   871  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-15 16:21:05.010   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-15 16:21:05.010   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:05.011   871  1304 D WifiNative-HAL: p2pGetDeviceAddress
08-15 16:21:05.011   871  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-15 16:21:05.035   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-15 16:21:05.106   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-15 16:21:05.108  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-15 16:21:05.527  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-15 16:21:05.566  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 16:21:05.566  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-15 16:21:05.572   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-15 16:21:05.586   871  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-15 16:21:05.586   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:05.587   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-15 16:21:05.610   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:05.620   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:05.621   871  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-15 16:21:05.634   871  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-15 16:21:05.637   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-15 16:21:05.677   871  4065 D DhcpClient: Receive thread started
,08-15 16:21:05.760   871  1305 E native  : do suspend false
,08-15 16:21:05.779   871  2088 D DhcpClient: Broadcasting DHCPDISCOVER
,08-15 16:21:05.795   871  4065 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-15 16:21:05.796   871  2088 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-15 16:21:05.799   871  2088 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-15 16:21:05.812   871  4065 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-15 16:21:05.813   871  2088 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-15 16:21:05.820   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:05.831   871  2088 D DhcpClient: Scheduling renewal in 86399s
,08-15 16:21:05.836   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-15 16:21:05.851   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-15 16:21:05.854   871  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-15 16:21:05.855   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-15 16:21:05.856   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-15 16:21:05.858   871  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-15 16:21:05.867   871  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-15 16:21:05.951   871  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-15 16:21:05.951   871  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-15 16:21:05.954   871  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-15 16:21:05.956   871  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-15 16:21:05.959   871  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-15 16:21:05.971   871  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-15 16:21:05.975   871  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-15 16:21:05.975   871  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-15 16:21:05.975   871  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-15 16:21:05.975   871  1307 D ConnectivityService:    accepting network in place of null
08-15 16:21:05.976   871  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-15 16:21:05.977   871  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-15 16:21:05.977   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-15 16:21:05.994   871  4064 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137221, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-15 16:21:06.019   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:06.052   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:06.062   871  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-15 16:21:06.062   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:06.079   871  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:80d::200e
,08-15 16:21:06.076   871   888 D Tethering: MasterInitialState.processMessage what=3
08-15 16:21:06.069   871  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-15 16:21:06.096  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:06.096  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:21:06.096  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:06.096  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:06.099  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:06.099  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 16:21:06.099  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:06.099  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:06.104  2009  2009 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-15 16:21:06.104  1708  1708 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-15 16:21:06.107  1708  1708 D SystemUpdateService: onCreate
,08-15 16:21:06.110  1708  1708 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-15 16:21:06.114  1708  4075 I SystemUpdateService: active receiver: enabled
,08-15 16:21:06.119  1708  4075 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-15 16:21:06.123  1708  4075 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-15 16:21:06.123  1708  4075 I SystemUpdateService: now status is 0 (complete)
,08-15 16:21:06.124  1708  4075 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-15 16:21:06.124  1708  4075 I SystemUpdateService: file has been verified
08-15 16:21:06.124  1708  4075 I SystemUpdateService: OTA package size = 12249756
,08-15 16:21:06.130  1708  4075 I SystemUpdateService: showing system update notification
,08-15 16:21:06.137  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-15 16:21:06.142  1708  2509 I iu.UploadsManager: num queued entries: 0
,08-15 16:21:06.142  1708  2509 I iu.UploadsManager: num updated entries: 0
08-15 16:21:06.143  1708  4079 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-15 16:21:06.143  1708  2509 I iu.SyncManager: NEXT; no task
,08-15 16:21:06.143  1708  4079 W BaseAppContext: Using Auth Proxy for data requests.
08-15 16:21:06.144  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-15 16:21:06.144  1708  4079 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-15 16:21:06.146  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-15 16:21:06.148  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:06.151  1708  1708 D SystemUpdateService: onDestroy
,08-15 16:21:06.155  3962  3962 D SprintDMHelper: simOperator: 
,08-15 16:21:06.155  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-15 16:21:06.155  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:21:06.158  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:21:06.166   871  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 15 Aug 2016 14:21:06 GMT], X-Android-Received-Millis=[1471270866165], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471270866134]}
,08-15 16:21:06.167   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-15 16:21:06.167   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-15 16:21:06.167   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-15 16:21:06.168   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-15 16:21:06.199  1502  2972 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-15 16:21:06.199  1502  2972 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-15 16:21:06.200  1502  2972 I GLSUser : [GLSUser] Extracting token using key: Auth
08-15 16:21:06.200  1502  2972 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-15 16:21:06.220  1708  4079 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-15 16:21:06.285  2193  4082 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-15 16:21:07.062   871  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-15 16:21:07.746   871  1369 I ActivityManager: Killing 3693:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-15 16:21:07.932   871  2231 D WifiService: setWifiEnabled: false pid=3802, uid=10000
,08-15 16:21:07.933   871  2231 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:21:07.972  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-15 16:21:07.984   871  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-15 16:21:07.984   871  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-15 16:21:07.985   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-15 16:21:07.985   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:08.008   871  2088 D DhcpClient: Clearing IP address
,08-15 16:21:08.009   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-15 16:21:08.020  1502  4087 V NativeCrypto: Read error: ssl=0x9a89a600: I/O error during system call, Connection timed out
,08-15 16:21:08.025   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:08.027   871  4065 D DhcpClient: Receive thread stopped
,08-15 16:21:08.028  1502  4087 V NativeCrypto: SSL shutdown failed: ssl=0x9a89a600: I/O error during system call, Broken pipe
,08-15 16:21:08.033   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-15 16:21:08.033   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-15 16:21:08.036   871  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
08-15 16:21:08.037   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-15 16:21:08.038   456   456 E Parcel  : Reading a NULL string not supported here.
,08-15 16:21:08.038   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-15 16:21:08.044   871  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-15 16:21:08.050   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-15 16:21:08.052  1878  2257 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 16:21:08.052  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:08.052  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:08.052  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:08.052  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:08.053   871  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-15 16:21:08.053  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:08.053  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:08.053  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:08.053  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:08.078   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:08.116   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:08.117   871  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-15 16:21:08.117   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:08.120   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-15 16:21:08.122  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:08.123  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:08.127  2009  2009 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-15 16:21:08.139  1708  1708 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-15 16:21:08.141  1708  1708 D SystemUpdateService: onCreate
,08-15 16:21:08.144  1708  1708 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-15 16:21:08.158  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-15 16:21:08.163  1708  2509 I iu.UploadsManager: num queued entries: 0
,08-15 16:21:08.164  1708  2509 I iu.UploadsManager: num updated entries: 0
,08-15 16:21:08.164  1708  2509 I iu.SyncManager: NEXT; no task
,08-15 16:21:08.169  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-15 16:21:08.170  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-15 16:21:08.171  1708  4100 I SystemUpdateService: active receiver: enabled
,08-15 16:21:08.173  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:08.179  3962  3962 D SprintDMHelper: simOperator: 
08-15 16:21:08.179  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-15 16:21:08.184   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-15 16:21:08.186   871  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-15 16:21:08.199  1708  4100 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-15 16:21:08.206  2193  4104 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-15 16:21:08.210  1708  4100 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-15 16:21:08.210  1708  4100 I SystemUpdateService: now status is 0 (complete)
08-15 16:21:08.210  1708  4100 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-15 16:21:08.210  1708  4100 I SystemUpdateService: file has been verified
08-15 16:21:08.210  1708  4100 I SystemUpdateService: OTA package size = 12249756
,08-15 16:21:08.221  1708  4100 I SystemUpdateService: showing system update notification
,08-15 16:21:08.234  1708  1708 D SystemUpdateService: onDestroy,
,08-15 16:21:08.349  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:21:08.400  1502  2972 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-15 16:21:08.400  1502  2972 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-15 16:21:08.401  1502  2972 I GLSUser : [GLSUser] Extracting token using key: Auth
08-15 16:21:08.401  1502  2972 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-15 16:21:08.432  3543  3543 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-15 16:21:08.432  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-15 16:21:08.432  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-15 16:21:10.991  3948  3948 D BluetoothAdapterState: make() - Creating AdapterState
08-15 16:21:10.991   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6628952:true
,08-15 16:21:10.996  3948  3948 I bt_bluedroid: init
,08-15 16:21:10.997  3948  4108 I BluetoothAdapterState: Entering OffState
,08-15 16:21:11.001  3948  4109 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-15 16:21:11.001  3948  4109 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-15 16:21:11.001  3948  4109 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-15 16:21:11.001  3948  4109 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-15 16:21:11.002  3948  3948 I bt_bluedroid: get_profile_interface socket
,08-15 16:21:11.005  3948  3948 I bt_bluedroid: get_profile_interface sdp
,08-15 16:21:11.010  3948  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-15 16:21:11.013  3948  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,08-15 16:21:11.015  3948  3959 I bt_bluedroid: config_hci_snoop_log
08-15 16:21:11.019   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-15 16:21:11.028  3948  4108 D BluetoothAdapterState: Current state: OFF, message: 0
,08-15 16:21:11.028  3948  4108 D BluetoothAdapterProperties: Setting state to 14
08-15 16:21:11.028  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-15 16:21:11.029  3948  4108 D BluetoothBondStateMachine: make
,08-15 16:21:11.033  3948  4113 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-15 16:21:11.035  3948  4108 I BluetoothAdapterState: Entering PendingCommandState
,08-15 16:21:11.036  3948  3948 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-15 16:21:11.039  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:11.040  3948  3948 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 16:21:11.040  3948  3948 D BtGatt.GattService: Received start request. Starting profile...
,08-15 16:21:11.041  3948  3948 D BtGatt.GattService: start()
08-15 16:21:11.041  3948  3948 I bt_bluedroid: get_profile_interface gatt
08-15 16:21:11.042  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:11.042  3948  3948 D BtGatt.AdvertiseManager: advertise manager created
,08-15 16:21:11.048  3948  3948 V BluetoothAdapterState: isTurningOff()=false
,08-15 16:21:11.048  3948  3948 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:11.048  3948  3948 V BluetoothAdapterState: isBleTurningOn()=true
08-15 16:21:11.048  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:11.049  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-15 16:21:11.049  3948  4108 I bt_bluedroid: enable
08-15 16:21:11.049  3948  4109 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
08-15 16:21:11.049  3948  4109 I bt_hci  : start_up
08-15 16:21:11.055  3948  4109 I bt_vendor: alloc value 0xb3969189
08-15 16:21:11.055  3948  4109 I bt_vendor: init
08-15 16:21:11.055  3948  4109 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-15 16:21:11.055  3948  4109 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-15 16:21:11.162  3948  4109 D bt_hci  : start_up starting async portion
08-15 16:21:11.163  3948  4116 I bt_hci  : event_finish_startup
08-15 16:21:11.163  3948  4116 I bt_hci_h4: hal_open
,08-15 16:21:11.164  3948  4116 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-15 16:21:11.175  3948  4116 I bt_userial_vendor: device fd = 51 open
,08-15 16:21:11.205  3948  4116 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-15 16:21:11.238  3948  4116 D bt_hwcfg: Chipset BCM4354A2
,08-15 16:21:11.238  3948  4116 D bt_hwcfg: Target name = [BCM4354A2]
08-15 16:21:11.239  3948  4116 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-15 16:21:11.909  3948  4116 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-15 16:21:11.911  3948  4116 D bt_hwcfg: Settlement delay -- 100 ms
08-15 16:21:11.911  3948  4116 I bt_hwcfg: Setting fw settlement delay to 100 
,08-15 16:21:12.027  3948  4116 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-15 16:21:12.029  3948  4116 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-15 16:21:12.058  3948  4116 I bt_hwcfg: vendor lib fwcfg completed
,08-15 16:21:12.058  3948  4116 I bt_vendor: firmware callback
08-15 16:21:12.059  3948  4116 I bt_hci  : firmware_config_callback
,08-15 16:21:12.070  3948  4118 I bt_btu  : btu_task pending for preload complete event
,08-15 16:21:12.071  3948  4118 I bt_btu_task: Bluetooth chip preload is complete
08-15 16:21:12.071  3948  4118 I bt_btu  : btu_task received preload complete event
,08-15 16:21:12.083  3948  4118 I         : BTE_InitTraceLevels -- TRC_HCI
,08-15 16:21:12.083  3948  4118 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-15 16:21:12.084  3948  4118 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-15 16:21:12.084  3948  4118 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-15 16:21:12.084  3948  4118 I         : BTE_InitTraceLevels -- TRC_AVRC
08-15 16:21:12.084  3948  4118 I         : BTE_InitTraceLevels -- TRC_A2D
08-15 16:21:12.085  3948  4118 I         : BTE_InitTraceLevels -- TRC_BNEP
08-15 16:21:12.085  3948  4118 I         : BTE_InitTraceLevels -- TRC_BTM
08-15 16:21:12.085  3948  4118 I         : BTE_InitTraceLevels -- TRC_GAP
08-15 16:21:12.086  3948  4118 I         : BTE_InitTraceLevels -- TRC_PAN
08-15 16:21:12.086  3948  4118 I         : BTE_InitTraceLevels -- TRC_SDP
08-15 16:21:12.086  3948  4118 I         : BTE_InitTraceLevels -- TRC_GATT
,08-15 16:21:12.086  3948  4118 I         : BTE_InitTraceLevels -- TRC_SMP
08-15 16:21:12.087  3948  4118 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-15 16:21:12.087  3948  4118 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-15 16:21:12.222  3948  4118 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-15 16:21:12.222  3948  4118 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-15 16:21:12.237  3948  4112 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-15 16:21:12.239  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-15 16:21:12.240  3948  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-15 16:21:12.243  3948  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,08-15 16:21:12.246  3948  4112 D BluetoothAdapterProperties: Scan Mode:20
,08-15 16:21:12.247  3948  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-15 16:21:12.247  3948  4112 D bt_hci  : do_postload posting postload work item
08-15 16:21:12.248  3948  4116 I bt_hci  : event_postload
08-15 16:21:12.248  3948  4116 I bt_vendor: sco_config_cb
,08-15 16:21:12.248  3948  4116 I bt_hci  : sco_config_callback postload finished.
,08-15 16:21:12.253  3948  4112 D bt_bte_conf: Device ID record 1 : primary,
,08-15 16:21:12.254  3948  4112 D bt_bte_conf:   vendorId            = 000f
,08-15 16:21:12.254  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:12.256  3948  4112 D bt_bte_conf:   vendorIdSource      = 0001
08-15 16:21:12.256  3948  4112 D bt_bte_conf:   product             = 1200
08-15 16:21:12.256  3948  4112 D bt_bte_conf:   version             = 1436,
,08-15 16:21:12.257  3948  4112 D bt_bte_conf:   clientExecutableURL = 
08-15 16:21:12.257  3948  4112 D bt_bte_conf:   serviceDescription  = 
08-15 16:21:12.257  3948  4112 D bt_bte_conf:   documentationURL    = 
,08-15 16:21:12.258  3948  4112 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-15 16:21:12.258  3948  4109 D bt_stack_manager: event_start_up_stack finished
08-15 16:21:12.260  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:12.260  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-15 16:21:12.260  3948  4116 I bt_vendor: low_power_mode_cb
,08-15 16:21:12.260  3948  4108 D BluetoothAdapterProperties: Setting state to 15
08-15 16:21:12.261  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-15 16:21:12.261  3948  4108 I BluetoothAdapterState: Entering BleOnState
,08-15 16:21:12.267  3948  4108 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-15 16:21:12.267  3948  4108 D BluetoothAdapterProperties: Setting state to 11
08-15 16:21:12.267  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-15 16:21:12.273  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:12.275  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:12.279  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
08-15 16:21:12.280  3948  3948 D HeadsetService: Received start request. Starting profile...
08-15 16:21:12.290  3948  4108 I BluetoothAdapterState: Entering PendingCommandState
08-15 16:21:12.291  3948  3948 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-15 16:21:12.292  3948  3948 D HeadsetStateMachine: make
,08-15 16:21:12.304  3948  3948 D HeadsetStateMachine: max_hf_connections = 1
,08-15 16:21:12.304  3948  3948 I bt_bluedroid: get_profile_interface handsfree
08-15 16:21:12.304  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-15 16:21:12.305  3948  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-15 16:21:12.309  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:12.309  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:21:12.310  3948  3948 D A2dpService: Received start request. Starting profile...
,08-15 16:21:12.310  3948  3948 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-15 16:21:12.311  3948  3948 I bt_bluedroid: get_profile_interface avrcp
,08-15 16:21:12.316  3948  3948 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-15 16:21:12.317  3948  3948 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-15 16:21:12.317  3948  3948 D A2dpStateMachine: make
,08-15 16:21:12.317  3948  3948 I bt_bluedroid: get_profile_interface a2dp
08-15 16:21:12.318  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-15 16:21:12.320  3948  4127 D A2dpStateMachine: Enter Disconnected: -2
08-15 16:21:12.321  3948  3948 I BluetoothHidServiceJni: classInitNative: succeeds
08-15 16:21:12.322  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
08-15 16:21:12.323  3868  3868 D BluetoothInputDevice: Proxy object connected
08-15 16:21:12.323  3948  3948 D HidService: Received start request. Starting profile...
08-15 16:21:12.323  3948  3948 I bt_bluedroid: get_profile_interface hidhost
08-15 16:21:12.323  3948  4112 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
08-15 16:21:12.323  3868  3868 D HidProfile: Bluetooth service connected
08-15 16:21:12.323  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-15 16:21:12.324  3948  3948 D HidService: setHidService(): set to: null
08-15 16:21:12.324  3948  3948 I BluetoothHealthServiceJni: classInitNative: succeeds
08-15 16:21:12.325  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:12.325  3948  3948 D HealthService: Received start request. Starting profile...
08-15 16:21:12.326  3948  3948 I bt_bluedroid: get_profile_interface health
,08-15 16:21:12.327  3948  3948 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-15 16:21:12.328  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:12.329  3868  3868 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 16:21:12.329  3948  3948 D PanService: Received start request. Starting profile...
08-15 16:21:12.329  3948  3948 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-15 16:21:12.329  3948  3948 I bt_bluedroid: get_profile_interface pan
08-15 16:21:12.329  3948  4112 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-15 16:21:12.329  3868  3868 D PanProfile: Bluetooth service connected
,08-15 16:21:12.332  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:12.333  3948  3948 D BluetoothMapService: Received start request. Starting profile...
,08-15 16:21:12.333  3948  3948 D BluetoothMapService: start()
08-15 16:21:12.333  3868  3868 D BluetoothMap: Proxy object connected
08-15 16:21:12.333  3868  3868 D MapProfile: Bluetooth service connected
08-15 16:21:12.334  3868  3868 D BluetoothMap: getConnectedDevices()
08-15 16:21:12.334  3868  3868 D BluetoothMap: Bluetooth is Not enabled
08-15 16:21:12.335  3948  3948 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-15 16:21:12.335  3948  3948 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-15 16:21:12.336  3948  3948 D BluetoothMapAppObserver: createReceiver()
,08-15 16:21:12.336  3948  3948 D BluetoothMapAppObserver: initObservers()
08-15 16:21:12.336  3948  3948 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-15 16:21:12.343  3948  3948 V BluetoothAdapterState: isTurningOff()=false
,08-15 16:21:12.344  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:12.344  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:12.344  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:12.346  3948  4125 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isTurningOff()=false
,08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:12.347  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isTurningOn()=true
,08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:12.348  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:12.349  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-15 16:21:12.349  3948  4108 D BluetoothAdapterProperties: ScanMode =  20
,08-15 16:21:12.349  3948  4108 D BluetoothAdapterProperties: State =  11
08-15 16:21:12.349  3948  4108 D BluetoothAdapterProperties: Setting state to 12
08-15 16:21:12.349  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-15 16:21:12.350  3948  4108 I BluetoothAdapterState: Entering OnState
08-15 16:21:12.350  3948  4112 D BluetoothAdapterProperties: Scan Mode:21
08-15 16:21:12.350  3948  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 16:21:12.351  3868  3881 D BluetoothPbap: onBluetoothStateChange: up=true
08-15 16:21:12.352   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:12.352  3868  3882 D BluetoothMap: onBluetoothStateChange: up=true
08-15 16:21:12.352   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-15 16:21:12.353  1362  1388 D BluetoothPbap: onBluetoothStateChange: up=true
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:12.353  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:12.354   871   871 D BluetoothA2dp: Proxy object connected
08-15 16:21:12.354  1362  1385 D BluetoothPan: onBluetoothStateChange on: true
08-15 16:21:12.355  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:21:12.355  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 16:21:12.355  1942  2033 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:12.355  1362  1362 D PanProfile: Bluetooth service connected
08-15 16:21:12.356  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-15 16:21:12.357  1362  1362 D BluetoothInputDevice: Proxy object connected
08-15 16:21:12.357  1362  1362 D HidProfile: Bluetooth service connected
08-15 16:21:12.357  3868  3881 D BluetoothPan: onBluetoothStateChange on: true
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:12.357  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:12.357  1362  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 16:21:12.359  1362  1362 D BluetoothA2dp: Proxy object connected
08-15 16:21:12.359   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-15 16:21:12.359   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:12.359  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:21:12.359  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:12.360  1362  1388 D BluetoothMap: onBluetoothStateChange: up=true
08-15 16:21:12.361  3868  3882 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-15 16:21:12.361  1362  1362 D BluetoothMap: Proxy object connected
08-15 16:21:12.361  1362  1362 D MapProfile: Bluetooth service connected
08-15 16:21:12.361  1362  1362 D BluetoothMap: getConnectedDevices()
08-15 16:21:12.362   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-15 16:21:12.362  3948  3948 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-15 16:21:12.364  3948  3948 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-15 16:21:12.365  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:12.365  3948  3948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:21:12.366  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:12.366  3868  3868 D LocalBluetoothProfileManager: Adding local A2DP profile
08-15 16:21:12.367  3948  3948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:21:12.368  3948  3948 D ObexServerSockets: Succeed to create listening sockets 
08-15 16:21:12.368  3948  3948 D ObexServerSockets0: startAccept()
,08-15 16:21:12.368  3948  3948 D ObexServerSockets0: prepareForNewConnect()
08-15 16:21:12.370  3948  3948 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-15 16:21:12.370  3948  3948 D BluetoothSdpJni: SDP Create record success - handle: 0
08-15 16:21:12.370  3948  3948 D BluetoothMapService: onReceive
08-15 16:21:12.370  3948  3948 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:21:12.370  3948  4135 D ObexServerSockets0: Accepting socket connection...
08-15 16:21:12.370  3948  3948 D BluetoothMapService: STATE_ON
08-15 16:21:12.371  3948  4136 D ObexServerSockets0: Accepting socket connection...
08-15 16:21:12.371  3868  3868 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-15 16:21:12.377  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-15 16:21:12.379  3868  3868 D BluetoothA2dp: Proxy object connected
,08-15 16:21:12.383  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-15 16:21:12.389  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:21:12.390  1362  1362 D BluetoothPbap: Proxy object connected
08-15 16:21:12.390  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-15 16:21:12.391  3868  3868 D BluetoothPbap: Proxy object connected
,08-15 16:21:12.393  3868  3868 D PbapServerProfile: Bluetooth service connected
,08-15 16:21:12.397  3948  3948 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-15 16:21:12.398  3948  4140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 16:21:12.398  3948  3948 D ObexServerSockets0: prepareForNewConnect()
,08-15 16:21:12.410  3948  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:21:12.411  3948  4144 I BtOppRfcommListener: Accept thread started.
,08-15 16:21:12.456  1362  1385 D BluetoothHeadset: Proxy object connected
,08-15 16:21:12.456  1362  1362 D HeadsetProfile: Bluetooth service connected
08-15 16:21:12.457   871   871 D BluetoothHeadset: Proxy object connected
08-15 16:21:12.457   871   871 D BluetoothHeadset: Proxy object connected
08-15 16:21:12.457   871   871 D BluetoothHeadset: Proxy object connected
08-15 16:21:12.457  1942  2083 D BluetoothHeadset: Proxy object connected
,08-15 16:21:12.460   871   888 D BluetoothHeadset: Proxy object connected
,08-15 16:21:12.460   871   888 D BluetoothHeadset: Proxy object connected
,08-15 16:21:12.461  1362  2035 D BluetoothHeadset: Proxy object connected
08-15 16:21:12.461  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-15 16:21:12.475  3868  3881 D BluetoothHeadset: Proxy object connected
,08-15 16:21:12.477  3868  3868 D HeadsetProfile: Bluetooth service connected
,08-15 16:21:13.949  3948  4108 D BluetoothAdapterState: Current state: ON, message: 23
,08-15 16:21:13.949  3948  4108 D BluetoothAdapterProperties: Setting state to 13
,08-15 16:21:13.950  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-15 16:21:13.951  3948  4108 D BluetoothAdapterProperties: onBluetoothDisable()
08-15 16:21:13.956  3948  4108 I BluetoothAdapterState: Entering PendingCommandState
08-15 16:21:13.961  3948  3948 D BluetoothMapService: onReceive
,08-15 16:21:13.961  3948  3948 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-15 16:21:13.962  3948  3948 D BluetoothMapService: STATE_TURNING_OFF
,08-15 16:21:13.963  3948  3948 D BluetoothMapService: MAP Service closeService in
,08-15 16:21:13.963  3948  3948 D BluetoothMapMasInstance0: MAP Service shutdown
,08-15 16:21:13.963  3948  3948 D ObexServerSockets0: shutdown(block = true)
,08-15 16:21:13.964  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:13.964  3948  4135 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:13.964  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 16:21:13.965  3948  3948 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-15 16:21:13.966  3948  3948 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-15 16:21:13.966  3948  4120 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-15 16:21:13.966  3948  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-15 16:21:13.969  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:13.970  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:21:13.970  3948  3948 I BtOppRfcommListener: stopping Accept Thread
08-15 16:21:13.971  3948  4144 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 16:21:13.972  3948  4144 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-15 16:21:13.972  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:13.972  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:21:13.973  3802  3802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 16:21:13.973  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 16:21:13.974  3948  4112 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:21:13.974  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-15 16:21:13.976  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-15 16:21:13.976  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:13.978  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:13.979   871  1307 D ConnectivityService: handlePromptUnvalidated 101
08-15 16:21:13.982  3948  3948 D HeadsetService: Received stop request...Stopping profile...
08-15 16:21:13.985  1362  1385 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:13.986   871   871 D BluetoothHeadset: Proxy object disconnected
,08-15 16:21:13.986   871   871 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:13.986   871   871 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:13.986  3948  3948 D A2dpService: Received stop request...Stopping profile...
08-15 16:21:13.986  3868  3882 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:13.986  3948  4127 D A2dpStateMachine: Exit Disconnected: -1
,08-15 16:21:13.987  1942  1954 D BluetoothHeadset: Proxy object disconnected
08-15 16:21:13.988  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-15 16:21:13.989   871   871 D BluetoothA2dp: Proxy object disconnected
08-15 16:21:13.990  1362  1362 D BluetoothA2dp: Proxy object disconnected
,08-15 16:21:13.993  3948  3948 D HidService: Received stop request...Stopping profile...
08-15 16:21:13.993  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:21:13.993  3948  3948 D HidService: Stopping Bluetooth HidService
08-15 16:21:13.994  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-15 16:21:13.994  1362  1362 D HidProfile: Bluetooth service disconnected
08-15 16:21:13.995  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:13.995  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:13.995  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:13.995  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:13.995  3948  3948 D HealthService: Received stop request...Stopping profile...
,08-15 16:21:13.999  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:21:14.000  3948  3948 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-15 16:21:14.001  3868  3868 D HeadsetProfile: Bluetooth service disconnected
,08-15 16:21:14.001  3868  3868 D BluetoothA2dp: Proxy object disconnected
,08-15 16:21:14.001  3948  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-15 16:21:14.001  3948  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-15 16:21:14.001  3948  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:14.001  3948  3948 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 16:21:14.001  3868  3868 D BluetoothInputDevice: Proxy object disconnected
08-15 16:21:14.002  3948  3948 D PanService: Received stop request...Stopping profile...
08-15 16:21:14.001  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-15 16:21:14.003  3948  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-15 16:21:14.001  3868  3868 D HidProfile: Bluetooth service disconnected
08-15 16:21:14.003  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-15 16:21:14.003  1362  1362 D PanProfile: Bluetooth service disconnected
08-15 16:21:14.003  3868  3868 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-15 16:21:14.003  3868  3868 D PanProfile: Bluetooth service disconnected
08-15 16:21:14.003  3948  3948 D BluetoothMapService: Received stop request...Stopping profile...
08-15 16:21:14.003  3948  3948 D BluetoothMapService: stop()
08-15 16:21:14.005  3948  3948 D BluetoothMapAppObserver: deinitObservers()
08-15 16:21:14.005  3948  3948 D BluetoothMapAppObserver: removeReceiver()
08-15 16:21:14.006  1362  1362 D BluetoothMap: Proxy object disconnected
08-15 16:21:14.006  1362  1362 D MapProfile: Bluetooth service disconnected
08-15 16:21:14.006  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:14.006  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:14.006  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:14.006  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:14.006  3868  3868 D BluetoothMap: Proxy object disconnected
,08-15 16:21:14.007  3868  3868 D MapProfile: Bluetooth service disconnected
,08-15 16:21:14.007  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-15 16:21:14.008  3948  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:14.008  3948  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-15 16:21:14.008  3948  4118 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-15 16:21:14.008  3948  4118 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-15 16:21:14.008  3948  4118 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-15 16:21:14.008  3948  4118 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 16:21:14.009  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:14.010  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:14.010  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:14.010  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:14.010  1362  1362 D BluetoothPbap: Proxy object disconnected
08-15 16:21:14.010  1362  1362 D PbapServerProfile: Bluetooth service disconnected
08-15 16:21:14.010  3948  3948 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-15 16:21:14.010  3948  3948 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-15 16:21:14.010  3868  3868 D BluetoothPbap: Proxy object disconnected
,08-15 16:21:14.010  3868  3868 D PbapServerProfile: Bluetooth service disconnected
08-15 16:21:14.010  3948  3948 V BluetoothAdapterState: isTurningOff()=true
,08-15 16:21:14.010  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:14.010  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:14.011  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:14.011  3948  3948 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-15 16:21:14.011  3948  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-15 16:21:14.011  3948  4112 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-15 16:21:14.011  3948  3948 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 16:21:14.012  3948  3948 V BluetoothAdapterState: isTurningOff()=true
,08-15 16:21:14.012  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:14.012  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:14.012  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:14.012  3948  3948 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-15 16:21:14.012  3948  3948 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-15 16:21:14.013  3948  3948 D BluetoothMapService: MAP Service closeService in
08-15 16:21:14.013  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-15 16:21:14.013  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-15 16:21:14.013  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:14.013  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:14.014  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-15 16:21:14.014  3948  4108 D BluetoothAdapterProperties: Setting state to 15
08-15 16:21:14.014  3948  3948 D BluetoothMapService: cleanup()
,08-15 16:21:14.014  3948  3948 D BluetoothMapService: MAP Service closeService in
08-15 16:21:14.014  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-15 16:21:14.016  3948  4108 I BluetoothAdapterState: Entering BleOnState
08-15 16:21:14.016  3868  3881 D BluetoothPbap: onBluetoothStateChange: up=false
08-15 16:21:14.019   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:14.019  3868  3882 D BluetoothMap: onBluetoothStateChange: up=false
08-15 16:21:14.019   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:21:14.020  1362  1385 D BluetoothPbap: onBluetoothStateChange: up=false
08-15 16:21:14.020  3868  3881 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:21:14.021  1362  2035 D BluetoothPan: onBluetoothStateChange on: false
08-15 16:21:14.021  1942  1952 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:14.022  1362  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-15 16:21:14.022  3868  3882 D BluetoothPan: onBluetoothStateChange on: false
08-15 16:21:14.023  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 16:21:14.023   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:14.023   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:14.023  3868  3881 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:14.023  1362  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 16:21:14.024  1362  2035 D BluetoothMap: onBluetoothStateChange: up=false
08-15 16:21:14.024  3868  3882 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-15 16:21:14.025  3948  4108 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-15 16:21:14.025  3948  4108 D BluetoothAdapterProperties: Setting state to 16
08-15 16:21:14.025  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-15 16:21:14.026  3948  4108 D BluetoothAdapterProperties: onBleDisable
08-15 16:21:14.027  3948  4109 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-15 16:21:14.027  3948  4118 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-15 16:21:14.027  3948  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-15 16:21:14.026  3948  4108 I BluetoothAdapterState: Entering PendingCommandState
,08-15 16:21:14.029  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:14.029  3948  4112 D BluetoothAdapterProperties: Scan Mode:20
08-15 16:21:14.029  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-15 16:21:14.030  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:14.032  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:14.033  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 16:21:14.033  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:14.040  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:21:14.228  3948  4112 I bt_hci  : shut_down
,08-15 16:21:14.228  3948  4116 D bt_hwcfg: hw_epilog_process
,08-15 16:21:14.241  3948  4116 I bt_vendor: low_power_mode_cb
,08-15 16:21:14.264  3948  4116 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-15 16:21:14.264  3948  4116 I bt_vendor: epilog_cb
08-15 16:21:14.265  3948  4116 I bt_hci  : epilog_finished_callback
,08-15 16:21:14.272  3948  4112 I bt_hci_h4: hal_close
,08-15 16:21:14.274  3948  4112 I bt_userial_vendor: device fd = 51 close
,08-15 16:21:14.410  3948  4109 D bt_stack_manager: event_shut_down_stack finished.
,08-15 16:21:14.413  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-15 16:21:14.420  3948  4108 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-15 16:21:14.420  3948  3948 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-15 16:21:14.422  3948  3948 D BtGatt.GattService: Received stop request...Stopping profile...
,08-15 16:21:14.422  3948  3948 D BtGatt.GattService: stop()
,08-15 16:21:14.423  3948  3948 D BtGatt.AdvertiseManager: advertise clients cleared
,08-15 16:21:14.430  3948  3948 V BluetoothAdapterState: isTurningOff()=false
,08-15 16:21:14.431  3948  3948 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:14.431  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:14.431  3948  3948 V BluetoothAdapterState: isBleTurningOff()=true
,08-15 16:21:14.433  3948  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-15 16:21:14.433  3948  4108 D BluetoothAdapterProperties: Setting state to 10
,08-15 16:21:14.434  3948  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-15 16:21:14.438  3948  4108 I BluetoothAdapterState: Entering OffState
08-15 16:21:14.438   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-15 16:21:14.467  3948  3948 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-15 16:21:14.467  3948  3948 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-15 16:21:14.470  3948  4109 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-15 16:21:14.476  3948  4109 D bt_stack_manager: event_clean_up_stack finished.
,08-15 16:21:14.476  3948  3948 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-15 16:21:14.480  3948  3948 I art     : System.exit called, status: 0
,08-15 16:21:14.481  3948  3948 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-15 16:21:14.546   871  3034 I ActivityManager: Process com.android.bluetooth (pid 3948) has died
,08-15 16:21:16.946  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:16.947  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:18.605   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-15 16:21:18.617  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-15 16:21:18.628   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-15 16:21:18.628   871   891 I Adreno  : Build Date                       : 10/20/15
08-15 16:21:18.628   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-15 16:21:18.628   871   891 I Adreno  : Local Branch                     : M14
08-15 16:21:18.628   871   891 I Adreno  : Remote Branch                    : 
08-15 16:21:18.628   871   891 I Adreno  : Remote Branch                    : 
08-15 16:21:18.628   871   891 I Adreno  : Reconstruct Branch               : 
,08-15 16:21:18.664   281   347 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (307 us)
,08-15 16:21:19.315  3802  3802 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-15 16:21:19.316  3802  3802 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-15 16:21:19.353   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-15 16:21:19.354  3802  3802 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a50e47 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@da5285d, 16908290=android.view.AbsSavedState$1@da5285d}, android:focusedViewId=100}]}]
08-15 16:21:19.354  3802  3802 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-15 16:21:19.355  3802  3802 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-15 16:21:19.355  3802  3802 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-15 16:21:19.367   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-15 16:21:19.370   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-15 16:21:19.370   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-15 16:21:19.370   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-15 16:21:19.403   871   880 I art     : Background partial concurrent mark sweep GC freed 15648(1244KB) AllocSpace objects, 9(316KB) LOS objects, 33% free, 28MB/43MB, paused 855us total 116.726ms
,08-15 16:21:19.605   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-15 16:21:19.609   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-15 16:21:19.616   871  1329 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,08-15 16:21:19.620   871   891 I DreamManagerService: Entering dreamland.
,08-15 16:21:19.621   871   891 I PowerManagerService: Dozing...
,08-15 16:21:19.624   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-15 16:21:19.673   375  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-15 16:21:19.673   375  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-15 16:21:19.677   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-15 16:21:19.680   871  1305 E native  : do suspend false
,08-15 16:21:19.693  1929  4156 D NfcService: Discovery configuration equal, not updating.
,08-15 16:21:19.717   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-15 16:21:19.722   871  1305 E native  : do suspend true
,08-15 16:21:19.808   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-15 16:21:19.809   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-15 16:21:19.954  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:21:19.954  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68cb5d2 added. We now have 6 listener(s)
08-15 16:21:19.955  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:19.959  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:19.959  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bbb96a3 added. We now have 7 listener(s)
08-15 16:21:19.960  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:19.961  3802  3852 I System.out: IsBluetoothEnabled
,08-15 16:21:19.969  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:20.006   871   888 I ActivityManager: Start proc 4164:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-15 16:21:20.116  4164  4164 D AdapterServiceConfig: Adding HeadsetService
,08-15 16:21:20.116  4164  4164 D AdapterServiceConfig: Adding A2dpService
08-15 16:21:20.117  4164  4164 D AdapterServiceConfig: Adding HidService
,08-15 16:21:20.117  4164  4164 D AdapterServiceConfig: Adding HealthService
,08-15 16:21:20.117  4164  4164 D AdapterServiceConfig: Adding PanService
08-15 16:21:20.117  4164  4164 D AdapterServiceConfig: Adding GattService
,08-15 16:21:20.117  4164  4164 D AdapterServiceConfig: Adding BluetoothMapService
,08-15 16:21:20.133   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@825576a:true
08-15 16:21:20.134  4164  4164 D BluetoothAdapterState: make() - Creating AdapterState
,08-15 16:21:20.143  4164  4164 I bt_bluedroid: init
,08-15 16:21:20.144  4164  4176 I BluetoothAdapterState: Entering OffState
,08-15 16:21:20.152  4164  4177 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-15 16:21:20.152  4164  4177 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-15 16:21:20.152  4164  4177 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-15 16:21:20.153  4164  4177 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-15 16:21:20.157  4164  4164 I bt_bluedroid: get_profile_interface socket
,08-15 16:21:20.160  4164  4164 I bt_bluedroid: get_profile_interface sdp
,08-15 16:21:20.163  4164  4180 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-15 16:21:20.166  4164  4180 D BluetoothAdapterProperties: Name is: Nexus 6
08-15 16:21:20.166  4164  4175 I bt_bluedroid: config_hci_snoop_log
,08-15 16:21:20.169   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-15 16:21:20.180  4164  4176 D BluetoothAdapterState: Current state: OFF, message: 0
,08-15 16:21:20.180  4164  4176 D BluetoothAdapterProperties: Setting state to 14
,08-15 16:21:20.181  4164  4176 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-15 16:21:20.186  4164  4176 D BluetoothBondStateMachine: make
,08-15 16:21:20.191  4164  4181 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-15 16:21:20.199  4164  4176 I BluetoothAdapterState: Entering PendingCommandState
,08-15 16:21:20.202  4164  4164 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-15 16:21:20.210  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:20.212  4164  4164 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-15 16:21:20.213  4164  4164 D BtGatt.GattService: Received start request. Starting profile...
,08-15 16:21:20.213  4164  4164 D BtGatt.GattService: start()
08-15 16:21:20.214  4164  4164 I bt_bluedroid: get_profile_interface gatt
,08-15 16:21:20.216  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:20.216  4164  4164 D BtGatt.AdvertiseManager: advertise manager created
,08-15 16:21:20.223  4164  4164 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:20.224  4164  4164 V BluetoothAdapterState: isTurningOn()=false
,08-15 16:21:20.224  4164  4164 V BluetoothAdapterState: isBleTurningOn()=true
08-15 16:21:20.224  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:20.224  4164  4176 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-15 16:21:20.224  4164  4176 I bt_bluedroid: enable
,08-15 16:21:20.225  4164  4177 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-15 16:21:20.226  4164  4177 I bt_hci  : start_up
,08-15 16:21:20.243  4164  4177 I bt_vendor: alloc value 0xb39bb189
,08-15 16:21:20.244  4164  4177 I bt_vendor: init
08-15 16:21:20.244  4164  4177 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-15 16:21:20.244  4164  4177 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-15 16:21:20.354  4164  4177 D bt_hci  : start_up starting async portion
,08-15 16:21:20.356  4164  4184 I bt_hci  : event_finish_startup
08-15 16:21:20.356  4164  4184 I bt_hci_h4: hal_open
08-15 16:21:20.356  4164  4184 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-15 16:21:20.367  4164  4184 I bt_userial_vendor: device fd = 51 open
,08-15 16:21:20.396  4164  4184 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-15 16:21:20.428  4164  4184 D bt_hwcfg: Chipset BCM4354A2
,08-15 16:21:20.428  4164  4184 D bt_hwcfg: Target name = [BCM4354A2]
08-15 16:21:20.429  4164  4184 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-15 16:21:21.088  4164  4184 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-15 16:21:21.089  4164  4184 D bt_hwcfg: Settlement delay -- 100 ms
08-15 16:21:21.089  4164  4184 I bt_hwcfg: Setting fw settlement delay to 100 
,08-15 16:21:21.206  4164  4184 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-15 16:21:21.207  4164  4184 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-15 16:21:21.237  4164  4184 I bt_hwcfg: vendor lib fwcfg completed
,08-15 16:21:21.238  4164  4184 I bt_vendor: firmware callback
,08-15 16:21:21.238  4164  4184 I bt_hci  : firmware_config_callback
,08-15 16:21:21.249  4164  4186 I bt_btu  : btu_task pending for preload complete event
08-15 16:21:21.249  4164  4186 I bt_btu_task: Bluetooth chip preload is complete
,08-15 16:21:21.249  4164  4186 I bt_btu  : btu_task received preload complete event
,08-15 16:21:21.259  4164  4186 I         : BTE_InitTraceLevels -- TRC_HCI
,08-15 16:21:21.259  4164  4186 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-15 16:21:21.260  4164  4186 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-15 16:21:21.260  4164  4186 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-15 16:21:21.260  4164  4186 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-15 16:21:21.260  4164  4186 I         : BTE_InitTraceLevels -- TRC_A2D
,08-15 16:21:21.261  4164  4186 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-15 16:21:21.261  4164  4186 I         : BTE_InitTraceLevels -- TRC_BTM
,08-15 16:21:21.261  4164  4186 I         : BTE_InitTraceLevels -- TRC_GAP
08-15 16:21:21.261  4164  4186 I         : BTE_InitTraceLevels -- TRC_PAN
08-15 16:21:21.262  4164  4186 I         : BTE_InitTraceLevels -- TRC_SDP
08-15 16:21:21.263  4164  4186 I         : BTE_InitTraceLevels -- TRC_GATT
,08-15 16:21:21.263  4164  4186 I         : BTE_InitTraceLevels -- TRC_SMP
08-15 16:21:21.263  4164  4186 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-15 16:21:21.263  4164  4186 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-15 16:21:21.398  4164  4186 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3938d9d
,08-15 16:21:21.398  4164  4186 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3938d9d 
,08-15 16:21:21.409  4164  4180 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-15 16:21:21.410  4164  4180 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-15 16:21:21.411  4164  4180 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-15 16:21:21.414  4164  4180 D BluetoothAdapterProperties: Name is: Nexus 6
,08-15 16:21:21.418  4164  4180 D BluetoothAdapterProperties: Scan Mode:20
,08-15 16:21:21.419  4164  4180 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-15 16:21:21.419  4164  4180 D bt_hci  : do_postload posting postload work item
,08-15 16:21:21.419  4164  4184 I bt_hci  : event_postload
08-15 16:21:21.419  4164  4184 I bt_vendor: sco_config_cb
08-15 16:21:21.420  4164  4184 I bt_hci  : sco_config_callback postload finished.
,08-15 16:21:21.422  4164  4180 D bt_bte_conf: Device ID record 1 : primary
08-15 16:21:21.422  4164  4180 D bt_bte_conf:   vendorId            = 000f
08-15 16:21:21.423  4164  4180 D bt_bte_conf:   vendorIdSource      = 0001
,08-15 16:21:21.423  4164  4180 D bt_bte_conf:   product             = 1200
08-15 16:21:21.423  4164  4180 D bt_bte_conf:   version             = 1436
08-15 16:21:21.423  4164  4180 D bt_bte_conf:   clientExecutableURL = 
,08-15 16:21:21.423  4164  4180 D bt_bte_conf:   serviceDescription  = 
08-15 16:21:21.423  4164  4180 D bt_bte_conf:   documentationURL    = 
08-15 16:21:21.424  4164  4180 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-15 16:21:21.424  4164  4177 D bt_stack_manager: event_start_up_stack finished
,08-15 16:21:21.425  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:21.426  4164  4176 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
,08-15 16:21:21.427  4164  4184 I bt_vendor: low_power_mode_cb,
,08-15 16:21:21.427  4164  4176 D BluetoothAdapterProperties: Setting state to 15
08-15 16:21:21.427  4164  4176 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-15 16:21:21.428  4164  4176 I BluetoothAdapterState: Entering BleOnState
08-15 16:21:21.434  4164  4176 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-15 16:21:21.435  4164  4176 D BluetoothAdapterProperties: Setting state to 11
08-15 16:21:21.435  4164  4176 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-15 16:21:21.443  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
08-15 16:21:21.446  4164  4164 D HeadsetService: Received start request. Starting profile...
08-15 16:21:21.446  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:21.449  4164  4164 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 16:21:21.450  4164  4164 D HeadsetStateMachine: make
,08-15 16:21:21.457  4164  4176 I BluetoothAdapterState: Entering PendingCommandState
,08-15 16:21:21.461  4164  4164 D HeadsetStateMachine: max_hf_connections = 1
,08-15 16:21:21.462  4164  4164 I bt_bluedroid: get_profile_interface handsfree
08-15 16:21:21.462  4164  4180 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-15 16:21:21.462  4164  4180 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-15 16:21:21.466  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:21.467  4164  4164 D A2dpService: Received start request. Starting profile...
,08-15 16:21:21.468  4164  4164 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-15 16:21:21.468  4164  4164 I bt_bluedroid: get_profile_interface avrcp
,08-15 16:21:21.476  4164  4164 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-15 16:21:21.476  4164  4164 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-15 16:21:21.476  4164  4164 D A2dpStateMachine: make
,08-15 16:21:21.478  4164  4164 I bt_bluedroid: get_profile_interface a2dp
,08-15 16:21:21.479  4164  4180 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-15 16:21:21.482  4164  4195 D A2dpStateMachine: Enter Disconnected: -2
08-15 16:21:21.481  4164  4164 I BluetoothHidServiceJni: classInitNative: succeeds
08-15 16:21:21.482  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 16:21:21.483  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
08-15 16:21:21.483  4164  4164 D HidService: Received start request. Starting profile...
08-15 16:21:21.483  4164  4164 I bt_bluedroid: get_profile_interface hidhost
08-15 16:21:21.483  4164  4180 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391a3e5
,08-15 16:21:21.483  4164  4180 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-15 16:21:21.484  4164  4164 D HidService: setHidService(): set to: null
08-15 16:21:21.484  4164  4164 I BluetoothHealthServiceJni: classInitNative: succeeds
08-15 16:21:21.485  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:21.485  4164  4164 D HealthService: Received start request. Starting profile...
,08-15 16:21:21.487  4164  4164 I bt_bluedroid: get_profile_interface health
,08-15 16:21:21.487  4164  4164 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-15 16:21:21.488  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:21.488  4164  4164 D PanService: Received start request. Starting profile...
08-15 16:21:21.489  4164  4164 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-15 16:21:21.489  4164  4164 I bt_bluedroid: get_profile_interface pan
08-15 16:21:21.489  4164  4180 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-15 16:21:21.491  4164  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
08-15 16:21:21.492  4164  4164 D BluetoothMapService: Received start request. Starting profile...
08-15 16:21:21.492  4164  4164 D BluetoothMapService: start()
,08-15 16:21:21.494  4164  4164 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-15 16:21:21.494  4164  4164 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-15 16:21:21.495  4164  4164 D BluetoothMapAppObserver: createReceiver()
,08-15 16:21:21.495  4164  4164 D BluetoothMapAppObserver: initObservers()
08-15 16:21:21.496  4164  4164 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-15 16:21:21.503  4164  4164 V BluetoothAdapterState: isTurningOff()=false
,08-15 16:21:21.503  4164  4164 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:21.503  4164  4164 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:21.503  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:21.504  4164  4164 V BluetoothAdapterState: isTurningOff()=false
,08-15 16:21:21.505  4164  4164 V BluetoothAdapterState: isTurningOn()=true
,08-15 16:21:21.505  4164  4164 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:21.505  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:21.505  4164  4193 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-15 16:21:21.509  4164  4164 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:21.509  4164  4164 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:21.509  4164  4164 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:21.509  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:21.509  4164  4164 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isBleTurningOn()=false
,08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:21.510  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:21.511  4164  4164 V BluetoothAdapterState: isTurningOff()=false
08-15 16:21:21.511  4164  4164 V BluetoothAdapterState: isTurningOn()=true
08-15 16:21:21.511  4164  4164 V BluetoothAdapterState: isBleTurningOn()=false
08-15 16:21:21.511  4164  4164 V BluetoothAdapterState: isBleTurningOff()=false
,08-15 16:21:21.511  4164  4176 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-15 16:21:21.511  4164  4176 D BluetoothAdapterProperties: ScanMode =  20
08-15 16:21:21.511  4164  4176 D BluetoothAdapterProperties: State =  11
08-15 16:21:21.512  4164  4176 D BluetoothAdapterProperties: Setting state to 12
08-15 16:21:21.512  4164  4176 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-15 16:21:21.513  4164  4176 I BluetoothAdapterState: Entering OnState
08-15 16:21:21.513  4164  4180 D BluetoothAdapterProperties: Scan Mode:21
08-15 16:21:21.513  3868  3882 D BluetoothPbap: onBluetoothStateChange: up=true
,08-15 16:21:21.513  4164  4180 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:21.516  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:21:21.517   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:21.517  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:21.517  3868  3881 D BluetoothMap: onBluetoothStateChange: up=true
,08-15 16:21:21.519   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-15 16:21:21.520  1362  2035 D BluetoothPbap: onBluetoothStateChange: up=true
,08-15 16:21:21.521  3868  3868 D BluetoothMap: Proxy object connected
,08-15 16:21:21.521  3868  3868 D MapProfile: Bluetooth service connected
,08-15 16:21:21.522  3868  3868 D BluetoothMap: getConnectedDevices()
,08-15 16:21:21.522   871   871 D BluetoothA2dp: Proxy object connected
08-15 16:21:21.522  4164  4164 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-15 16:21:21.522  3868  3881 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 16:21:21.523  4164  4164 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-15 16:21:21.524  4164  4164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:21:21.525  3868  3868 D BluetoothA2dp: Proxy object connected
,08-15 16:21:21.525  1362  1375 D BluetoothPan: onBluetoothStateChange on: true
08-15 16:21:21.526  4164  4164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:21:21.527  1942  1954 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-15 16:21:21.527  4164  4164 D ObexServerSockets: Succeed to create listening sockets 
08-15 16:21:21.527  4164  4164 D ObexServerSockets0: startAccept()
,08-15 16:21:21.527  4164  4164 D ObexServerSockets0: prepareForNewConnect()
,08-15 16:21:21.527  1362  1388 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-15 16:21:21.529  3868  4200 D BluetoothPan: onBluetoothStateChange on: true
,08-15 16:21:21.529  4164  4164 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-15 16:21:21.529  4164  4164 D BluetoothSdpJni: SDP Create record success - handle: 0,
08-15 16:21:21.531  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-15 16:21:21.531  4164  4203 D ObexServerSockets0: Accepting socket connection...
,08-15 16:21:21.531  1362  1362 D PanProfile: Bluetooth service connected
,08-15 16:21:21.531  4164  4202 D ObexServerSockets0: Accepting socket connection...
,08-15 16:21:21.531  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-15 16:21:21.532  1362  1362 D HidProfile: Bluetooth service connected
,08-15 16:21:21.532  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-15 16:21:21.533  3868  3868 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 16:21:21.533  3868  3868 D PanProfile: Bluetooth service connected
08-15 16:21:21.533  1362  1362 D BluetoothA2dp: Proxy object connected
08-15 16:21:21.534   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:21.534   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:21.534  3868  3881 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:21.534  1362  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 16:21:21.535  1362  2035 D BluetoothMap: onBluetoothStateChange: up=true
08-15 16:21:21.536  1362  1362 D BluetoothMap: Proxy object connected
08-15 16:21:21.536  1362  1362 D MapProfile: Bluetooth service connected
08-15 16:21:21.536  3868  3882 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-15 16:21:21.536  1362  1362 D BluetoothMap: getConnectedDevices()
08-15 16:21:21.538  3868  3868 D BluetoothInputDevice: Proxy object connected
08-15 16:21:21.538  3868  3868 D HidProfile: Bluetooth service connected
08-15 16:21:21.538   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-15 16:21:21.539  4164  4164 D BluetoothMapService: onReceive
08-15 16:21:21.539  4164  4164 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 16:21:21.540  4164  4164 D BluetoothMapService: STATE_ON
08-15 16:21:21.540  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:21.544  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-15 16:21:21.549  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 16:21:21.550  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,08-15 16:21:21.557  3868  3868 D BluetoothPbap: Proxy object connected
,08-15 16:21:21.557  3868  3868 D PbapServerProfile: Bluetooth service connected
,08-15 16:21:21.564  4164  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:21:21.566  1362  1362 D BluetoothPbap: Proxy object connected
08-15 16:21:21.566  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-15 16:21:21.575  4164  4164 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-15 16:21:21.575  4164  4164 D ObexServerSockets0: prepareForNewConnect()
,08-15 16:21:21.578  4164  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 16:21:21.579  4164  4211 I BtOppRfcommListener: Accept thread started.
,08-15 16:21:21.619  1362  1388 D BluetoothHeadset: Proxy object connected
08-15 16:21:21.620  1362  1362 D HeadsetProfile: Bluetooth service connected
08-15 16:21:21.620   871   871 D BluetoothHeadset: Proxy object connected
08-15 16:21:21.620   871   871 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.621   871   871 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.621  3868  3881 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.622  3868  3868 D HeadsetProfile: Bluetooth service connected
08-15 16:21:21.622  1942  1952 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.628  1942  2033 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.634   871   888 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.634   871   888 D BluetoothHeadset: Proxy object connected
08-15 16:21:21.635  3868  3882 D BluetoothHeadset: Proxy object connected
08-15 16:21:21.635  3868  3868 D HeadsetProfile: Bluetooth service connected
08-15 16:21:21.635  1362  1375 D BluetoothHeadset: Proxy object connected
,08-15 16:21:21.635  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:21.990  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:21:21.997  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:22.002  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:21:22.002  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd6fda0 added. We now have 8 listener(s)
08-15 16:21:22.003  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:22.011   871  1478 D WifiService: setWifiEnabled: false pid=3802, uid=10000
,08-15 16:21:22.011   871  1478 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:21:22.023  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:22.024   871  1677 D WifiService: setWifiEnabled: true pid=3802, uid=10000
,08-15 16:21:22.024   871  1677 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 16:21:22.036   871  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 16:21:22.055  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 16:21:22.060  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-15 16:21:22.071   871  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-15 16:21:22.073   871  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-15 16:21:22.073   871  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-15 16:21:22.074   871  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-15 16:21:22.075   871  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-15 16:21:22.075   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-15 16:21:22.075   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-15 16:21:22.089   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-15 16:21:22.090   871  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.07 rxSuccessRate=0.07 delta 1000 -> 1000
08-15 16:21:22.090   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:22.090   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-15 16:21:22.091   871  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-15 16:21:22.091   871  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-15 16:21:22.103   871  1305 E native  : do suspend true
,08-15 16:21:22.103   871  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-15 16:21:22.110   871  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-15 16:21:22.136   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-15 16:21:22.136   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:22.146   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-15 16:21:22.199   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-15 16:21:22.201  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-15 16:21:22.618  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-15 16:21:22.655  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-15 16:21:22.657  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-15 16:21:22.665   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-15 16:21:22.685   871  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-15 16:21:22.685   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:22.685   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-15 16:21:22.710   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-15 16:21:22.726   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:22.727   871  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-15 16:21:22.737   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-15 16:21:22.748   871  4220 D DhcpClient: Receive thread started
,08-15 16:21:22.835   871  1305 E native  : do suspend false
,08-15 16:21:22.855   871  2088 D DhcpClient: Broadcasting DHCPDISCOVER
,08-15 16:21:22.870   871  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-15 16:21:22.872   871  2088 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-15 16:21:22.875   871  2088 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-15 16:21:22.890   871  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-15 16:21:22.892   871  2088 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-15 16:21:22.896   371   869 D CommandListener: Setting iface cfg
,08-15 16:21:22.907   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-15 16:21:22.908   871  2088 D DhcpClient: Scheduling renewal in 86399s,
,08-15 16:21:22.910   871  1305 E native  : do suspend true
,08-15 16:21:22.937   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-15 16:21:22.941   871  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-15 16:21:22.942   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-15 16:21:22.943   871  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-15 16:21:22.951   871  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-15 16:21:22.986   871  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-15 16:21:22.987   871  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-15 16:21:22.990   871  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-15 16:21:22.992   871  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-15 16:21:22.994   871  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-15 16:21:23.007   871  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-15 16:21:23.016   871  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-15 16:21:23.016   871  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-15 16:21:23.016   871  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-15 16:21:23.017   871  1307 D ConnectivityService:    accepting network in place of null
08-15 16:21:23.017   871  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-15 16:21:23.017   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-15 16:21:23.018   871  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-15 16:21:23.031   871  4219 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154259, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:23.039  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:23.041  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:23.044  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-15 16:21:23.045  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-15 16:21:23.047  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a50e47 Bundle[{}]
,08-15 16:21:23.047  3802  3852 I io.jxcore.node.LifeCycleMonitor: start: OK
08-15 16:21:23.048  3802  3852 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-15 16:21:23.048  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-15 16:21:23.049  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-15 16:21:23.049  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-15 16:21:23.050  3802  3852 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-15 16:21:23.050   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:23.054  3802  3852 I System.out: Running OutgoingSocketThread
,08-15 16:21:23.055  3802  4227 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,08-15 16:21:23.056  3802  4227 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48065
,08-15 16:21:23.056  3802  4227 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-15 16:21:23.097   871  4218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:80c::200e
,08-15 16:21:23.098   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-15 16:21:23.103   871  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-15 16:21:23.103   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:23.106   871  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-15 16:21:23.111   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:23.120  3802  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:23.122  3802  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:23.133  1708  1708 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-15 16:21:23.138  2009  2009 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-15 16:21:23.143  1708  1708 D SystemUpdateService: onCreate
,08-15 16:21:23.147  1708  1708 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-15 16:21:23.165  1708  4230 I SystemUpdateService: active receiver: enabled
,08-15 16:21:23.167  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-15 16:21:23.169  1708  2509 I iu.UploadsManager: num queued entries: 0
,08-15 16:21:23.169  1708  2509 I iu.UploadsManager: num updated entries: 0
08-15 16:21:23.170  1708  2509 I iu.SyncManager: NEXT; no task
,08-15 16:21:23.178   871  4218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 15 Aug 2016 14:21:23 GMT], X-Android-Received-Millis=[1471270883177], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471270883146]}
,08-15 16:21:23.179  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-15 16:21:23.181  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-15 16:21:23.185   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-15 16:21:23.186   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-15 16:21:23.186   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-15 16:21:23.186  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-15 16:21:23.192  1708  4233 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-15 16:21:23.192  1708  4233 W BaseAppContext: Using Auth Proxy for data requests.
,08-15 16:21:23.192   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-15 16:21:23.197  1708  4230 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-15 16:21:23.198  1708  4233 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-15 16:21:23.200  3962  3962 D SprintDMHelper: simOperator: 
,08-15 16:21:23.200  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-15 16:21:23.203  1708  4230 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-15 16:21:23.204  1708  4230 I SystemUpdateService: now status is 0 (complete)
,08-15 16:21:23.204  1708  4230 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-15 16:21:23.204  1708  4230 I SystemUpdateService: file has been verified
,08-15 16:21:23.204  1708  4230 I SystemUpdateService: OTA package size = 12249756
,08-15 16:21:23.208  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:21:23.216  1708  4230 I SystemUpdateService: showing system update notification
,08-15 16:21:23.217  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-15 16:21:23.276  1708  1708 D SystemUpdateService: onDestroy
,08-15 16:21:23.288  1502  2005 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-15 16:21:23.288  1502  2005 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-15 16:21:23.288  1502  2005 I GLSUser : [GLSUser] Extracting token using key: Auth
08-15 16:21:23.288  1502  2005 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-15 16:21:23.300  1708  4233 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-15 16:21:23.353  2193  4236 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-15 16:21:24.057  3802  3852 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
08-15 16:21:24.057  3802  3852 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,08-15 16:21:24.066  3802  3852 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-15 16:21:24.069  3802  3852 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-15 16:21:24.069  3802  3852 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-15 16:21:24.074  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-15 16:21:24.074  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@590ed59 added. We now have 2 listener(s)
,08-15 16:21:24.076  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:21:24.076  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.076  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-15 16:21:24.077  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.077  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc5d1e added. We now have 9 listener(s)
,08-15 16:21:24.077  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:24.077  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 16:21:24.081  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:24.090  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:24.093  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:24.093  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 16:21:24.094  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:21:24.094  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e53cc added. We now have 3 listener(s)
,08-15 16:21:24.097  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:24.101  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:24.103   871  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-15 16:21:24.104  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-15 16:21:24.105  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-15 16:21:24.105  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.105  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 16:21:24.106  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8da0615 added. We now have 10 listener(s)
08-15 16:21:24.106  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:24.106  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:21:24.106  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:24.106  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:24.106  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:24.106  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.106  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.106  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.106  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@590ed59 removed from the list
08-15 16:21:24.107  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.107  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc5d1e removed from the list
08-15 16:21:24.107  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:24.107  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.107  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.107  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.108  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.108  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:24.109  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.109  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc5d1e not in the list
08-15 16:21:24.109  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.109  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.110  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:24.110  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.110  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.110  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8da0615 removed from the list
08-15 16:21:24.110  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:24.110  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.110  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.110  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.111  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e53cc removed from the list
08-15 16:21:24.111  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:21:24.111  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addLis,tener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bed2d2a added. We now have 2 listener(s)
08-15 16:21:24.113  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:21:24.113  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.113  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.114  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.114  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b371b added. We now have 9 listener(s)
08-15 16:21:24.114  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:24.114  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 16:21:24.117  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:24.123  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:24.125  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:24.125  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:21:24.126  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-15 16:21:24.126  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61ee91 added. We now have 3 listener(s)
08-15 16:21:24.127  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-15 16:21:24.130  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:24.133  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-15 16:21:24.133  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-15 16:21:24.134  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.134  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-15 16:21:24.135  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588f1f6 added. We now have 10 listener(s)
,08-15 16:21:24.135  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:24.136  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-15 16:21:24.136  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:21:24.136  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-15 16:21:24.136  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:21:24.137  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-15 16:21:24.142  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
,08-15 16:21:24.142  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-15 16:21:24.151  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-15 16:21:24.152  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-15 16:21:24.152  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 16:21:24.155  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-15 16:21:24.156  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-15 16:21:24.156  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-15 16:21:24.157  3802  3852 D BluetoothAdapter: STATE_ON
,08-15 16:21:24.160  4164  4212 D BtGatt.GattService: registerClient() - UUID=b8fe59a4-b1dd-424b-acde-eb17b7709669
,08-15 16:21:24.161  4164  4180 D BtGatt.GattService: onClientRegistered() - UUID=b8fe59a4-b1dd-424b-acde-eb17b7709669, clientIf=5
,08-15 16:21:24.162  3802  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-15 16:21:24.163  4164  4201 D BtGatt.GattService: start scan with filters
,08-15 16:21:24.167  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-15 16:21:24.167  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-15 16:21:24.167  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-15 16:21:24.167  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-15 16:21:24.167  4164  4183 D BtGatt.ScanManager: handling starting scan
,08-15 16:21:24.169  4164  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e87766b
,08-15 16:21:24.173  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:24.173  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-15 16:21:24.173  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:24.175  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-15 16:21:24.176  4164  4180 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-15 16:21:24.176  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.177  4164  4183 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-15 16:21:24.180  3802  3852 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-15 16:21:24.180  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:24.180  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-15 16:21:24.180  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.180  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-15 16:21:24.181  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-15 16:21:24.181  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 16:21:24.181  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-15 16:21:24.181  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:24.181  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-15 16:21:24.181  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-15 16:21:24.182  3802  3852 D BluetoothAdapter: STATE_ON
,08-15 16:21:24.183  4164  4212 D BtGatt.GattService: stopScan() - queue size =1
08-15 16:21:24.184  4164  4174 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-15 16:21:24.184  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-15 16:21:24.184  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-15 16:21:24.184  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-15 16:21:24.184  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-15 16:21:24.184  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-15 16:21:24.186  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:24.186  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-15 16:21:24.186  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 16:21:24.186  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:21:24.186  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.188  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:24.188  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:24.188  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-15 16:21:24.191  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:24.191  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:24.191  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:24.191  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:24.191  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.191  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-15 16:21:24.191  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.192  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bed2d2a removed from the list
,08-15 16:21:24.192  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:24.192  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b371b removed from the list
08-15 16:21:24.192  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:24.192  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-15 16:21:24.193  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.193  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.193  4164  4180 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-15 16:21:24.193  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.194  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 16:21:24.194  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:24.194  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.194  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b371b not in the list,
08-15 16:21:24.194  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.194  4164  4183 D BtGatt.ScanManager: Starting BLE batch scan
,08-15 16:21:24.194  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.194  4164  4183 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-15 16:21:24.195  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:24.195  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.195  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:24.195  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588f1f6 removed from the list
08-15 16:21:24.196  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:24.196  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.196  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.196  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.196  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61ee91 removed from the list
,08-15 16:21:24.197  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:21:24.197  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44a3782 added. We now have 2 listener(s)
08-15 16:21:24.199  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:21:24.199  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-15 16:21:24.199  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.200  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.200  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f6e93 added. We now have 9 listener(s)
08-15 16:21:24.200  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:24.200  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:21:24.206  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:24.210  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:24.212  4164  4180 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-15 16:21:24.212  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.214  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:24.215  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:21:24.215  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-15 16:21:24.215  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abadec9 added. We now have 3 listener(s)
08-15 16:21:24.218  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:24.220  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:24.221  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-15 16:21:24.221  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.221  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.222  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.222  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e849ce added. We now have 10 listener(s)
,08-15 16:21:24.222  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:24.222  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:21:24.224  4164  4180 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-15 16:21:24.224  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.225  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:21:24.225  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:21:24.225  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:21:24.225  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:21:24.225  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-15 16:21:24.230  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-15 16:21:24.230  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-15 16:21:24.237  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 16:21:24.237  4164  4180 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-15 16:21:24.237  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.238  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-15 16:21:24.238  4164  4183 D BtGatt.ScanManager: stopping BLe Batch
08-15 16:21:24.238  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 16:21:24.241  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-15 16:21:24.241  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-15 16:21:24.241  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-15 16:21:24.243  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:24.244  4164  4180 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-15 16:21:24.244  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.245  4164  4183 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-15 16:21:24.246  4164  4201 D BtGatt.GattService: registerClient() - UUID=f943afd7-3f3e-45e9-942b-1b5b9e7ecca1
08-15 16:21:24.246  4164  4180 D BtGatt.GattService: onClientRegistered() - UUID=f943afd7-3f3e-45e9-942b-1b5b9e7ecca1, clientIf=5
08-15 16:21:24.247  3802  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-15 16:21:24.247  4164  4174 D BtGatt.GattService: start scan with filters
,08-15 16:21:24.250  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-15 16:21:24.250  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-15 16:21:24.250  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-15 16:21:24.250  4164  4180 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-15 16:21:24.250  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-15 16:21:24.251  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.252  4164  4183 D BtGatt.ScanManager: handling starting scan
,08-15 16:21:24.254  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:24.254  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:24.255  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-15 16:21:24.257  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-15 16:21:24.259  4164  4180 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-15 16:21:24.259  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.259  4164  4183 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-15 16:21:24.260  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:21:24.261  3802  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-15 16:21:24.261  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 16:21:24.261  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:24.261  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:24.262  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:24.262  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.262  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-15 16:21:24.262  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.262  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44a3782 removed from the list
08-15 16:21:24.262  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:24.262  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f6e93 removed from the list
,08-15 16:21:24.262  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:24.263  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.263  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.263  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-15 16:21:24.263  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.263  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.265  4164  4180 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-15 16:21:24.265  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.265  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.265  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:24.265  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.265  4164  4183 D BtGatt.ScanManager: Starting BLE batch scan,
08-15 16:21:24.265  4164  4183 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-15 16:21:24.265  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f6e93 not in the list
,08-15 16:21:24.266  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 16:21:24.266  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-15 16:21:24.266  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:24.266  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-15 16:21:24.266  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-15 16:21:24.267  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:24.268  4164  4174 D BtGatt.GattService: stopScan() - queue size =1
,08-15 16:21:24.269  4164  4175 D BtGatt.GattService: unregisterClient() - clientIf=5
08-15 16:21:24.271  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-15 16:21:24.271  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-15 16:21:24.271  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-15 16:21:24.271  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-15 16:21:24.271  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-15 16:21:24.273  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:24.273  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-15 16:21:24.273  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 16:21:24.273  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-15 16:21:24.273  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.274  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:24.274  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 16:21:24.275  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:24.274  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 16:21:24.275  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:24.275  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e849ce removed from the list
,08-15 16:21:24.275  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:24.275  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.275  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.275  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-15 16:21:24.275  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abadec9 removed from the list
08-15 16:21:24.275  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:24.276  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:21:24.276  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4334da added. We now have 2 listener(s)
,08-15 16:21:24.277  4164  4180 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-15 16:21:24.277  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.279  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:21:24.279  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.279  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-15 16:21:24.279  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.279  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541d0b added. We now have 9 listener(s)
08-15 16:21:24.279  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:24.279  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 16:21:24.282  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:24.283  4164  4180 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-15 16:21:24.284  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:24.287  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:24.289  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:24.289  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:21:24.289  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-15 16:21:24.291  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca9e01 added. We now have 3 listener(s)
,08-15 16:21:24.291  4164  4180 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-15 16:21:24.291  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.291  4164  4183 D BtGatt.ScanManager: stopping BLe Batch
,08-15 16:21:24.291  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:24.294  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-15 16:21:24.294  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:24.294  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.294  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.294  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.295  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52fc4a6 added. We now have 10 listener(s)
08-15 16:21:24.295  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:24.295  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 16:21:24.295  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 16:21:24.295  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 16:21:24.295  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 16:21:24.295  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-15 16:21:24.298  4164  4180 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-15 16:21:24.298  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.298  3802  3852 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-15 16:21:24.298  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 16:21:24.298  4164  4183 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-15 16:21:24.301  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-15 16:21:24.302  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-15 16:21:24.302  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 16:21:24.304  4164  4180 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-15 16:21:24.304  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.305  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-15 16:21:24.305  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-15 16:21:24.305  3802  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-15 16:21:24.306  3802  3852 D BluetoothAdapter: STATE_ON
,08-15 16:21:24.307  4164  4201 D BtGatt.GattService: registerClient() - UUID=82fd7c05-ce8b-4644-8dcc-49e904909609
,08-15 16:21:24.307  4164  4180 D BtGatt.GattService: onClientRegistered() - UUID=82fd7c05-ce8b-4644-8dcc-49e904909609, clientIf=5
,08-15 16:21:24.308  3802  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-15 16:21:24.308  4164  4174 D BtGatt.GattService: start scan with filters
,08-15 16:21:24.310  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-15 16:21:24.310  4164  4183 D BtGatt.ScanManager: handling starting scan
,08-15 16:21:24.310  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-15 16:21:24.310  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-15 16:21:24.310  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-15 16:21:24.313  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:24.313  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-15 16:21:24.313  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-15 16:21:24.314  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-15 16:21:24.316  4164  4180 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-15 16:21:24.316  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.316  4164  4183 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-15 16:21:24.318  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-15 16:21:24.318  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:24.318  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:24.318  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-15 16:21:24.318  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.318  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-15 16:21:24.319  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-15 16:21:24.319  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4334da removed from the list
,08-15 16:21:24.319  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.319  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541d0b removed from the list
,08-15 16:21:24.319  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
,08-15 16:21:24.319  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.319  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.319  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-15 16:21:24.319  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.319  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.320  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.320  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:24.320  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.321  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541d0b not in the list
08-15 16:21:24.321  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 16:21:24.321  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 16:21:24.321  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 16:21:24.321  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-15 16:21:24.321  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-15 16:21:24.321  4164  4180 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-15 16:21:24.321  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.321  4164  4183 D BtGatt.ScanManager: Starting BLE batch scan
08-15 16:21:24.321  4164  4183 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-15 16:21:24.321  3802  3852 D BluetoothAdapter: STATE_ON
08-15 16:21:24.322  4164  4192 D BtGatt.GattService: stopScan() - queue size =1
08-15 16:21:24.322  4164  4201 D BtGatt.GattService: unregisterClient() - clientIf=5
08-15 16:21:24.322  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 16:21:24.323  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-15 16:21:24.323  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-15 16:21:24.323  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-15 16:21:24.323  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-15 16:21:24.323  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:24.324  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-15 16:21:24.324  3802  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 16:21:24.324  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 16:21:24.324  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.325  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:2,1:24.325  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.325  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.325  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52fc4a6 removed from the list
08-15 16:21:24.325  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:24.325  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.325  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:24.325  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.325  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.325  3802  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 16:21:24.326  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca9e01 removed from the list
08-15 16:21:24.326  3802  3802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 16:21:24.326  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-15 16:21:24.326  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1038532 added. We now have 2 listener(s)
,08-15 16:21:24.328  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-15 16:21:24.328  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.328  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.328  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.328  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c12283 added. We now have 9 listener(s)
08-15 16:21:24.328  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 16:21:24.328  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 16:21:24.331  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 16:21:24.331  4164  4180 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-15 16:21:24.331  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 16:21:24.338  3802  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 16:21:24.340  3802  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 16:21:24.340  3802  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 16:21:24.340  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 16:21:24.340  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbc0c39 added. We now have 3 listener(s)
,08-15 16:21:24.342  4164  4180 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-15 16:21:24.342  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.342  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 16:21:24.344  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-15 16:21:24.344  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 16:21:24.344  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 16:21:24.344  3802  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 16:21:24.344  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 16:21:24.344  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e0c27e added. We now have 10 listener(s)
08-15 16:21:24.344  3802  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 16:21:24.345  3802  3852 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 16:21:24.345  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 16:21:24.345  3802  3852 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 16:21:24.345  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:24.345  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 16:21:24.345  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 16:21:24.345  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 16:21:24.345  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1038532 removed from the list
08-15 16:21:24.345  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.345  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c12283 removed from the list
,08-15 16:21:24.345  3802  3852 D io.jxcore.node.ConnectivityMonitor: stop
08-15 16:21:24.345  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:24.346  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.346  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.347  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 16:21:24.347  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 16:21:24.347  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.347  3802  3852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c12283 not in the list
08-15 16:21:24.347  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.347  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 16:21:24.348  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 16:21:24.348  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 16:21:24.348  3802  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 16:21:24.348  3802  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e0c27e removed from the list
08-15 16:21:24.348  3802  3852 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 16:21:24.348  3802  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 16:21:24.348  3802  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 16:21:24.348  3802  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-15 16:21:24.348  3802  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbc0c39 removed from the list
,08-15 16:21:24.349  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-15 16:21:24.349  4164  4180 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-15 16:21:24.349  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.349  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-15 16:21:24.349  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-15 16:21:24.349  4164  4183 D BtGatt.ScanManager: stopping BLe Batch
,08-15 16:21:24.349  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-15 16:21:24.349  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-15 16:21:24.349  3802  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-15 16:21:24.355  3802  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
08-15 16:21:24.355  3802  4242 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
,08-15 16:21:24.355  3802  4242 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-15 16:21:24.356  4164  4180 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-15 16:21:24.356  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-15 16:21:24.356  4164  4183 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-15 16:21:24.359  3802  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,08-15 16:21:24.359  3802  4243 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
08-15 16:21:24.359  3802  4243 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-15 16:21:24.361  3802  3852 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-15 16:21:24.361  3802  3852 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-15 16:21:24.361  3802  3852 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-15 16:21:24.361  3802  3852 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-15 16:21:24.361  4164  4180 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-15 16:21:24.361  3802  3852 D com.test.thalitest.ThaliTestRunner: Total duration: 22810 ms
08-15 16:21:24.361  4164  4180 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-15 16:21:24.363  3802  3852 I jxcore-log: Total number of executed tests:  80
08-15 16:21:24.363  3802  3852 I jxcore-log: 
08-15 16:21:24.363  3802  3852 I jxcore-log: Number of passed tests:  80
08-15 16:21:24.363  3802  3852 I jxcore-log: 
,08-15 16:21:24.363  3802  3852 I jxcore-log: Number of failed tests:  0
08-15 16:21:24.363  3802  3852 I jxcore-log: 
08-15 16:21:24.363  3802  3852 I jxcore-log: Number of ignored tests:  0
08-15 16:21:24.363  3802  3852 I jxcore-log: 
08-15 16:21:24.363  3802  3852 I jxcore-log: Total duration:  22810
08-15 16:21:24.363  3802  3852 I jxcore-log: 
,08-15 16:21:24.364  3802  3852 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-15 16:21:24.364  3802  3852 I jxcore-log: 
,08-15 16:21:24.367  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.367  3802  3852 I jxcore-log: 
08-15 16:21:24.370  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.370  3802  3852 I jxcore-log: 
08-15 16:21:24.372  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.372  3802  3852 I jxcore-log: 
08-15 16:21:24.372  3802  3802 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-15 16:21:24.373  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.373  3802  3852 I jxcore-log: 
08-15 16:21:24.374  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.374  3802  3852 I jxcore-log: 
08-15 16:21:24.375  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.375  3802  3852 I jxcore-log: 
,08-15 16:21:24.377  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.377  3802  3852 I jxcore-log: 
,08-15 16:21:24.379  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.379  3802  3852 I jxcore-log: 
,08-15 16:21:24.379  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.379  3802  3852 I jxcore-log: 
,08-15 16:21:24.380  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-15 16:21:24.380  3802  3852 I jxcore-log: 
,08-15 16:21:24.381  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 16:21:24.381  3802  3852 I jxcore-log: 
,08-15 16:21:24.385  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 16:21:24.385  3802  3852 I jxcore-log: 
,08-15 16:21:24.386  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.386  3802  3852 I jxcore-log: 
,08-15 16:21:24.387  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.387  3802  3852 I jxcore-log: 
,08-15 16:21:24.387  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.387  3802  3852 I jxcore-log: 
,08-15 16:21:24.388  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.388  3802  3852 I jxcore-log: 
,08-15 16:21:24.388  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.388  3802  3852 I jxcore-log: 
,08-15 16:21:24.389  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.389  3802  3852 I jxcore-log: 
08-15 16:21:24.389  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.389  3802  3852 I jxcore-log: 
,08-15 16:21:24.390  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.390  3802  3852 I jxcore-log: 
,08-15 16:21:24.391  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.391  3802  3852 I jxcore-log: 
,08-15 16:21:24.391  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 16:21:24.391  3802  3852 I jxcore-log: 
,08-15 16:21:24.392  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-15 16:21:24.392  3802  3852 I jxcore-log: 
,08-15 16:21:24.393  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.393  3802  3852 I jxcore-log: 
08-15 16:21:24.393  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.393  3802  3852 I jxcore-log: 
,08-15 16:21:24.394  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.394  3802  3852 I jxcore-log: 
,08-15 16:21:24.394  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.394  3802  3852 I jxcore-log: 
,08-15 16:21:24.396  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.396  3802  3852 I jxcore-log: 
,08-15 16:21:24.396  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.396  3802  3852 I jxcore-log: 
,08-15 16:21:24.397  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 16:21:24.397  3802  3852 I jxcore-log: 
,08-15 16:21:24.689  3802  3802 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-15 16:21:24.690  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-15 16:21:24.690  3802  3852 I jxcore-log: 
,08-15 16:21:24.775  3802  3802 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-15 16:21:24.777  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-15 16:21:24.777  3802  3852 I jxcore-log: 
,08-15 16:21:24.826  3802  3802 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-15 16:21:24.828  3802  3852 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-15 16:21:24.828  3802  3852 I jxcore-log: 
,08-15 16:21:24.996  4245  4245 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-15 16:21:25.000  4245  4245 D AndroidRuntime: CheckJNI is OFF
,08-15 16:21:25.043  4245  4245 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-15 16:21:25.091  4245  4245 I Radio-JNI: register_android_hardware_Radio DONE
,08-15 16:21:25.113  4245  4245 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-15 16:21:25.126   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-15 16:21:25.127   871   884 I ActivityManager: Killing 3802:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-15 16:21:25.213  1878  2629 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-15 16:21:25.221   871  3034 I WindowState: WIN DEATH: Window{af7a1b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-15 16:21:25.221   871  1369 D GraphicsStats: Buffer count: 2
,08-15 16:21:25.225   871  1306 D WifiService: Client connection lost with reason: 4
,08-15 16:21:25.291   871   894 W PackageSettings: Skipping PackageSetting{9d7042c com.example.hello/10273} due to missing metadata
,08-15 16:21:25.332   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-15 16:21:25.332   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-15 16:21:25.333   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-15 16:21:25.333   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-15 16:21:25.333   871   884 E ActivityManager: 	,at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-15 16:21:25.333   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.333   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.333   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-15 16:21:25.333   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-15 16:21:25.334   871   884 I ActivityManager:   Force finishing activity ActivityRecord{fd1111 u0 com.test.thalitest/.MainActivity t2}
,08-15 16:21:25.341   871  2231 W ActivityManager: Spurious death for ProcessRecord{f3789c7 0:com.test.thalitest/u0a0}, curProc for 3802: null
,08-15 16:21:25.341   871   894 I art     : Starting a blocking GC Explicit
,08-15 16:21:25.398   871   894 I art     : Explicit concurrent mark sweep GC freed 13672(954KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 692us total 54.430ms
,08-15 16:21:25.429   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-15 16:21:25.434  4245  4245 I art     : System.exit called, status: 0
,08-15 16:21:25.434  4245  4245 I AndroidRuntime: VM exiting with result code 0.
,08-15 16:21:25.444   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-15 16:21:25.463   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-15 16:21:25.467  4164  4164 D BluetoothMapAppObserver: onReceive
08-15 16:21:25.467  4164  4164 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-15 16:21:25.472   871  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-15 16:21:25.473  3641  3641 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-15 16:21:25.473  1865  1865 I Keyboard.Facilitator: resetDictionaries() : en_US
08-15 16:21:25.474  1878  2216 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-15 16:21:25.490  1865  4256 I Keyboard.Facilitator.DecoderInitializer: run()
,08-15 16:21:25.499  1865  4256 I Decoder : createOrResetDecoder
,08-15 16:21:25.519  1942  1942 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-15 16:21:25.523   871  1677 I ActivityManager: Start proc 4259:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-15 16:21:25.539  1502  1502 I ConfigService: onCreate
,08-15 16:21:25.560  1865  4256 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-15 16:21:25.568   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-15 16:21:25.580  4259  4259 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-15 16:21:25.593   871   882 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3802 uid 10000
,08-15 16:21:25.595  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-15 16:21:25.600  1960  2037 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-15 16:21:25.600   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-15 16:21:25.601   871   883 E PackageManager: Failed to write settings, restoring backup
08-15 16:21:25.601   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-15 16:21:25.601   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-15 16:21:25.601   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-15 16:21:25.601   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-15 16:21:25.601   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-15 16:21:25.601   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.601   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.601   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-15 16:21:25.605   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-15 16:21:25.605   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-15 16:21:25.605   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:25.605   871   884 E DropBoxManagerService: 	... 13 more
,08-15 16:21:25.606  1865  4256 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-15 16:21:25.608  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-15 16:21:25.608  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-15 16:21:25.610  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-15 16:21:25.610  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-15 16:21:25.611  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-15 16:21:25.611  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-15 16:21:25.612  1865  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-15 16:21:25.612  1865  4256 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-15 16:21:25.612  1865  4256 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-15 16:21:25.612  1865  4256 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-15 16:21:25.612  1865  4256 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-15 16:21:25.613  1865  4256 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-15 16:21:25.615   871  3034 I ActivityManager: Start proc 4275:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
,08-15 16:21:25.616  1960  2037 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-15 16:21:25.616  1960  2037 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1960
08-15 16:21:25.616  1960  2037 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.616  1960  2037 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-15 16:21:25.618   871  3035 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-15 16:21:25.619   871  4281 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:21:25.619   871  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:25.619   871  4281 E DropBoxManagerService: 	... 5 more
,08-15 16:21:25.620  1960  2037 I Process : Sending signal. PID: 1960 SIG: 9
,08-15 16:21:25.689  4259  4259 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-15 16:21:25.699   871  2231 D GraphicsStats: Buffer count: 1
,08-15 16:21:25.700   871   881 I WindowState: WIN DEATH: Window{e8e634 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-15 16:21:25.711   871  1959 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1960) has died
,08-15 16:21:25.712   871  1959 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-15 16:21:25.716   871  1959 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-15 16:21:25.732   871   884 I ActivityManager: Start proc 4291:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-15 16:21:25.741  4259  4274 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.741  4259  4274 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.741  4259  4274 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-15 16:21:25.746  4259  4302 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-15 16:21:25.748   871  1478 I ActivityManager: Start proc 4304:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-15 16:21:25.777  4304  4304 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-15 16:21:25.784  4291  4291 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.784  4291  4291 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:25.784  4291  4291 D AndroidRuntime: Shutting down VM
,08-15 16:21:25.791  1708  4301 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-15 16:21:25.791  4291  4291 E AndroidRuntime: FATAL EXCEPTION: main
08-15 16:21:25.791  4291  4291 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4291
08-15 16:21:25.791  4291  4291 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-15 16:21:25.791  4291  4291 E AndroidRuntime: 	... 10 more
08-15 16:21:25.792  1708  4301 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-15 16:21:25.793   871  1959 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-15 16:21:25.793  4291  4291 I Process : Sending signal. PID: 4291 SIG: 9
08-15 16:21:25.794   871  4317 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:21:25.794   871  4317 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:25.794   871  4317 E DropBoxManagerService: 	... 5 more
,08-15 16:21:25.816  1708  4301 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-15 16:21:25.817  1708  4301 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-15 16:21:25.819  1502  1502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-15 16:21:25.819  1502  1502 D AndroidRuntime: Shutting down VM
,08-15 16:21:25.820  1502  1502 E AndroidRuntime: FATAL EXCEPTION: main
08-15 16:21:25.820  1502  1502 E AndroidRuntime: Process: com.google.process.gapps, PID: 1502
08-15 16:21:25.820  1502  1502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-15 16:21:25.820  1502  1502 E AndroidRuntime: 	... 8 more
,08-15 16:21:25.823   871  4320 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:21:25.823   871  4320 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:25.823   871  4320 E DropBoxManagerService: 	... 5 more
,08-15 16:21:25.824  1502  1502 I Process : Sending signal. PID: 1502 SIG: 9
,08-15 16:21:25.836   871  1678 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4291) has died
,08-15 16:21:25.837   871  1678 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-15 16:21:25.850  4259  4274 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-15 16:21:25.850   871   884 I ActivityManager: Start proc 4322:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-15 16:21:25.852   871  1678 I ActivityManager: Process com.google.process.gapps (pid 1502) has died
08-15 16:21:25.852   871  1678 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-15 16:21:25.853   871  1678 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-15 16:21:25.853   871  1678 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,08-15 16:21:25.853   871  1678 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
08-15 16:21:25.855   871  1306 D WifiService: Client connection lost with reason: 4
,08-15 16:21:25.878  1708  1708 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-15 16:21:25.887   871   881 I ActivityManager: Start proc 4335:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-15 16:21:25.892  4259  4302 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.892  4259  4302 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-15 16:21:25.893  4259  4302 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-15 16:21:25.893  4259  4302 E AndroidRuntime: Process: android.process.acore, PID: 4259
08-15 16:21:25.893  4259  4302 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.893  4259  4302 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-15 16:21:25.897   871  4346 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:21:25.897   871  4346 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:25.897   871  4346 E DropBoxManagerService: 	... 5 more
,08-15 16:21:25.900  4322  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.900  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:25.900  4322  4322 D AndroidRuntime: Shutting down VM
,08-15 16:21:25.910  4259  4302 I Process : Sending signal. PID: 4259 SIG: 9
,08-15 16:21:25.914  4322  4322 E AndroidRuntime: FATAL EXCEPTION: main
08-15 16:21:25.914  4322  4322 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4322
08-15 16:21:25.914  4322  4322 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-15 16:21:25.914  4322  4322 E AndroidRuntime: 	... 10 more
08-15 16:21:25.916   871  1677 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-15 16:21:25.918   871  4349 E DropBoxManagerService: Can't write: system_app_crash
08-15 16:21:25.918   871  4349 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-15 16:21:25.918   871  4349 E DropBoxManagerService: 	... 5 more
,08-15 16:21:25.920  4322  4322 I Process : Sending signal. PID: 4322 SIG: 9
,08-15 16:21:25.924  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-15 16:21:25.924  1708  1708 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-15 16:21:25.925  4335  4335 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-15 16:21:25.930  1708  4301 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-15 16:21:25.931  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-15 16:21:25.931  1708  1708 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-15 16:21:25.932  1708  4301 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-15 16:21:25.936  4335  4335 I MultiDex: VM with version 2.1.0 has multidex support
,08-15 16:21:25.936  4335  4335 I MultiDex: install
,08-15 16:21:25.936  4335  4335 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-15 16:21:25.939  4335  4335 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-15 16:21:25.940  1708  4351 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-15 16:21:25.943   279   279 E lowmemorykiller: Error writing /proc/4259/oom_score_adj; errno=22
,08-15 16:21:25.943  4335  4335 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-15 16:21:25.943   871  2233 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,08-15 16:21:25.944   871  2233 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-15 16:21:25.944   871  2233 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483),
08-15 16:21:25.944   871  2233 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.945  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-15 16:21:25.945  4335  4335 D AndroidRuntime: Shutting down VM
08-15 16:21:25.946  4335  4335 E AndroidRuntime: FATAL EXCEPTION: main
08-15 16:21:25.946  4335  4335 E AndroidRuntime: Process: com.google.process.gapps, PID: 4335
08-15 16:21:25.946  4335  4335 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.946  4335  4335 E AndroidRuntime: ,	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-15 16:21:25.946  4335  4335 E AndroidRuntime: 	... 10 more
,08-15 16:21:25.951   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
