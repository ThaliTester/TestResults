#### Test 8288334166fab8f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 16:40:29.171  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 16:40:29.190  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 16:40:29.196  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 16:40:29.292  1556  1574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 16:40:29.292  1556  1574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 16:40:29.293  1556  1574 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:40:29.293  1556  1574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 16:40:29.358  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 16:40:29.359  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 16:40:29.362  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 16:40:30.602  3788  3788 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 16:40:30.606  3788  3788 D AndroidRuntime: CheckJNI is OFF
08-29 16:40:30.642  3788  3788 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 16:40:30.684  3788  3788 I Radio-JNI: register_android_hardware_Radio DONE
08-29 16:40:30.704  3788  3788 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 16:40:30.708   873  2014 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 16:40:30.753  2050  2061 W SearchService: Abort, client detached.
08-29 16:40:30.759  2050  2050 I HotwordDetector: Closing mic
08-29 16:40:30.760  2050  2336 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4a1e87c
08-29 16:40:30.760  2050  2351 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 16:40:30.762  3788  3788 D AndroidRuntime: Shutting down VM
08-29 16:40:30.781   873  1926 I ActivityManager: Start proc 3797:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 16:40:30.819   375  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 16:40:30.820   375  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 16:40:30.825   375  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 16:40:30.829  2050  2350 I MicroRecognitionRnrImpl: Detection finished
08-29 16:40:30.829  2050  2339 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 16:40:30.857  3797  3797 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 16:40:30.882  3797  3797 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 16:40:30.888  3797  3797 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1574-1577)
08-29 16:40:30.889  3797  3797 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 16:40:30.903  3797  3797 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {da61595}
08-29 16:40:30.903  3797  3797 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 16:40:30.904  3797  3797 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 16:40:30.910  3797  3797 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 16:40:30.911  3797  3797 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 16:40:30.926  3797  3797 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 16:40:30.936  3797  3797 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:40:30.936  3797  3797 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:40:30.936  3797  3797 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 16:40:30.936  3797  3797 I Adreno  : Build Date                       : 10/20/15
08-29 16:40:30.936  3797  3797 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 16:40:30.936  3797  3797 I Adreno  : Local Branch                     : M14
08-29 16:40:30.936  3797  3797 I Adreno  : Remote Branch                    : 
08-29 16:40:30.936  3797  3797 I Adreno  : Remote Branch                    : 
08-29 16:40:30.936  3797  3797 I Adreno  : Reconstruct Branch               : 
08-29 16:40:31.003   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@187f8ea:true
,08-29 16:40:31.057  3797  3797 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 16:40:31.072  3797  3797 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 16:40:31.123   873  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 16:40:31.130  3797  3836 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 16:40:31.144  3797  3822 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 16:40:31.190  3797  3836 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 16:40:31.286   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +520ms
,08-29 16:40:31.296  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-29 16:40:31.367  3797  3797 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3797
,08-29 16:40:31.527  3797  3797 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 16:40:31.570   873  1926 I ActivityManager: Killing 3069:com.google.android.talk/u0a61 (adj 15): empty #17
,08-29 16:40:31.619   873  1926 I ActivityManager: Killing 2968:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-29 16:40:31.708  3797  3838 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1713768144
,08-29 16:40:31.716  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 16:40:31.716  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 16:40:31.716  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 16:40:31.716  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 16:40:31.716  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 16:40:31.717  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4b7409 added. We now have 1 listener(s)
,08-29 16:40:31.721  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 16:40:31.723  3797  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:40:31.724  3797  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 16:40:31.725  3797  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 16:40:31.729  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 16:40:31.730  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f8ce3c added. We now have 1 listener(s)
,08-29 16:40:31.730  3797  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:40:31.734   873  1313 D WifiService: New client listening to asynchronous messages
,08-29 16:40:31.738  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:40:31.738  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 16:40:31.740  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 16:40:31.740  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 16:40:31.740  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 16:40:31.745  3797  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:31.745  3797  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 16:40:31.749  3797  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:31.750  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:40:31.750  3797  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 16:40:31.750  3797  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:40:31.751  3797  3838 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 16:40:31.814  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:31.816  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:31.818  3797  3797 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 16:40:32.664  3797  3848 W jxcore-log: Initializing JXcore engine
,08-29 16:40:32.664  3797  3848 W jxcore-log: JXcore engine is ready
,08-29 16:40:32.700  3848  3848 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 16:40:32.703  3848  3848 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11650]" dev="sockfs" ino=11650 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 16:40:32.703  3848  3848 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 16:40:32.703  3848  3848 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26087]" dev="sockfs" ino=26087 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 16:40:32.714  3797  3848 W jxcore-log: Starting JXcore engine
,08-29 16:40:32.797  3797  3848 W jxcore-log: Platform android
08-29 16:40:32.797  3797  3848 W jxcore-log: 
08-29 16:40:32.797  3797  3848 W jxcore-log: Process ARCH arm
08-29 16:40:32.797  3797  3848 W jxcore-log: 
,08-29 16:40:33.008  3797  3848 I jxcore-log: JXcore Cordova bridge is ready!
08-29 16:40:33.008  3797  3848 I jxcore-log: 
,08-29 16:40:33.008  3797  3848 W jxcore-log: JXcore engine is started
,08-29 16:40:33.020  3797  3838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 16:40:33.025  3797  3797 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 16:40:33.913   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:40:36.348  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:40:36.351  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:40:36.384  1556  2107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:40:36.385  1556  2107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 16:40:36.385  1556  2107 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:40:36.385  1556  2107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:40:36.411  3546  3856 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 16:40:36.411  3546  3856 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at blb.a(PG:3937)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at czp.a(PG:18188)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:40:36.411  3546  3856 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	... 12 more
08-29 16:40:36.411  3546  3856 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at fal.a(PG:38)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:40:36.411  3546  3856 E HttpOperation: 	... 14 more
,08-29 16:40:36.466  1556  1574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:40:36.466  1556  1574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:40:36.466  1556  1574 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:40:36.466  1556  1574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:40:36.483  3546  3856 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 16:40:36.483  3546  3856 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at hec.a(PG:42)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at hee.a(PG:102)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at czr.a(PG:65)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at kka.a(PG:108)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at czp.a(PG:19176)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:40:36.483  3546  3856 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	... 15 more
08-29 16:40:36.483  3546  3856 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at fal.a(PG:38)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:40:36.483  3546  3856 E HttpOperation: 	... 17 more
,08-29 16:40:36.484  3546  3856 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 16:40:36.484  3546  3856 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at hec.a(PG:42)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at hee.a(PG:102)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at czr.a(PG:65)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at kka.a(PG:108)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	... 15 more
08-29 16:40:36.484  3546  3856 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at fal.a(PG:38)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 16:40:36.484  3546  3856 E ExperimentLoader: 	... 17 more
,08-29 16:40:36.575   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126839, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:40:36.940   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:40:39.971   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:40:43.002   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:40:43.162  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 16:40:43.162  3797  3848 I jxcore-log: 
,08-29 16:40:43.164  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 16:40:43.164  3797  3848 I jxcore-log: 
,08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:43.172  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:43.178  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:43.180  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 16:40:43.180  3797  3848 I jxcore-log: 
,08-29 16:40:43.182  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 16:40:43.182  3797  3848 I jxcore-log: 
,08-29 16:40:43.764   873  2000 D WifiService: setWifiEnabled: true pid=3797, uid=10000
,08-29 16:40:43.764   873  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:40:43.770  3797  3848 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 16:40:43.774  3797  3848 I jxcore-log: Unit Test app is loaded
08-29 16:40:43.774  3797  3848 I jxcore-log: 
,08-29 16:40:43.777  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:40:43.777  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a9cae added. We now have 2 listener(s)
,08-29 16:40:43.779  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 16:40:43.785  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:40:43.785  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:40:43.786  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:40:43.786  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:40:43.786  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b55ea4f added. We now have 2 listener(s)
08-29 16:40:43.787  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:40:43.787   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 16:40:43.788  3797  3797 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 16:40:43.788   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 16:40:43.789   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-29 16:40:43.789  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:40:43.789   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:43.795  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:43.803  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:43.806  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:43.806  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:40:43.807  3797  3848 D ExecuteNativeTests: Running unit tests
,08-29 16:40:43.808   873  1842 D DhcpClient: Clearing IP address
,08-29 16:40:43.808   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 16:40:43.809  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:43.811   371   871 D CommandListener: Setting iface cfg
08-29 16:40:43.811  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:43.813  1556  2139 V NativeCrypto: Read error: ssl=0xaebaa800: I/O error during system call, Connection timed out
08-29 16:40:43.815   873  1845 D DhcpClient: Receive thread stopped
08-29 16:40:43.817   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 16:40:43.818   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 16:40:43.818   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 16:40:43.819  1556  2139 V NativeCrypto: SSL shutdown failed: ssl=0xaebaa800: I/O error during system call, Broken pipe
08-29 16:40:43.819   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:40:43.822   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 16:40:43.822   873  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-29 16:40:43.834   407   407 E Parcel  : Reading a NULL string not supported here.
,08-29 16:40:43.839   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 16:40:43.840   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 16:40:43.853   873   886 I ActivityManager: Start proc 3863:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-29 16:40:43.874   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:40:43.895  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-29 16:40:43.901   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 16:40:43.902   873  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 16:40:43.902   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 16:40:43.904   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 16:40:43.906  3382  3382 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f4b7409 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 16:40:43.911  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:40:43.911  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 added. We now have 3 listener(s)
08-29 16:40:43.913  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:40:43.913  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:40:43.913  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:40:43.913  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:40:43.913  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a added. We now have 3 listener(s)
08-29 16:40:43.913  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:40:43.914  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:43.915  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:40:43.916  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:43.917  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:43.919  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:43.921  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:40:43.922  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:43.922  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:40:43.924  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:43.924  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 16:40:43.925  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:43.925  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:40:43.926  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:40:43.926  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 16:40:43.927  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:43.929  3797  3848 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 16:40:43.929  3797  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 16:40:43.929  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 16:40:43.930  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:40:43.931  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:40:43.931  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:40:43.931  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:40:43.932  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:40:43.932  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:40:43.932  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:43.932  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.933  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:40:43.933  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:40:43.933  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 removed from the list
08-29 16:40:43.933  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:43.933  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a removed from the list
08-29 16:40:43.933  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:43.933  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.934  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.934  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.935  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:43.935  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:43.935  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:43.935  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:40:43.936  3797  3848 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 16:40:43.937  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:40:43.937  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:40:43.937  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:40:43.937  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:43.937  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.937  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.937  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:40:43.937  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:43.937  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:40:43.937  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:43.937  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.937  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.937  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.937  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.938  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:43.938  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:43.938  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:43.938  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:40:43.942  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 16:40:43.942  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 16:40:43.942  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 16:40:43.943  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 16:40:43.944  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 16:40:43.944  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:40:43.944  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:40:43.944  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:40:43.944  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:43.944  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.944  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.944  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:40:43.944  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:43.945  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:40:43.945  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:43.945  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.945  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.945  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:43.945  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:43.946  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:43.946  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:43.946  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:43.946  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:40:43.948  3797  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-29 16:40:43.950  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:43.952  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:40:43.953  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:43.953  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:40:43.954  3797  3848 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 16:40:43.954  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 16:40:43.954  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:43.955  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:43.955  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 16:40:43.956  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 16:40:43.958  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 16:40:43.959  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:43.960  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 16:40:43.961  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 16:40:43.961  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 16:40:43.961  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:40:43.961  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 16:40:43.961  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 16:40:43.961  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:43.961  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 16:40:43.963  3797  3883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:40:43.964  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:40:43.964  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 16:40:43.964  3797  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 16:40:43.968  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:40:43.969  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:40:43.970  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 16:40:43.971  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 16:40:43.971  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:40:43.972  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-29 16:40:43.972  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:43.972  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:43.973  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 16:40:43.973   371   871 E Netd    : netlink response contains error (No such file or directory)
08-29 16:40:43.973  3797  3848 D BluetoothAdapter: STATE_ON
08-29 16:40:43.977  2687  2698 D BtGatt.GattService: registerClient() - UUID=b9d57fbb-6185-42f3-8604-ce9c31508bf6
08-29 16:40:43.978  2687  2706 D BtGatt.GattService: onClientRegistered() - UUID=b9d57fbb-6185-42f3-8604-ce9c31508bf6, clientIf=5
08-29 16:40:43.978  3797  3808 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-29 16:40:43.979  2687  2708 D BtGatt.AdvertiseManager: message : 0
08-29 16:40:43.981  2687  2708 D BtGatt.AdvertiseManager: starting multi advertising
08-29 16:40:43.991  2687  2706 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
08-29 16:40:43.996  2687  2706 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-29 16:40:43.997  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 16:40:43.997  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 16:40:43.998  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 16:40:43.999  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 16:40:43.999  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 16:40:44.000  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 16:40:44.000  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 16:40:44.000  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 16:40:44.000  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 16:40:44.000  3797  3848 I io.jxcore.node.ConnectionHelper: start: OK
08-29 16:40:44.001  3797  3797 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 16:40:44.002  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:40:44.068  3863  3888 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 16:40:44.068  3863  3888 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 16:40:44.078  3863  3888 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 16:40:44.078  3863  3888 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 16:40:44.105  3863  3888 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 16:40:44.105  3863  3888 I Babel_SMS: MmsConfig.loadFromResources
,08-29 16:40:44.107  3863  3888 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 16:40:44.107  3863  3888 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 16:40:44.139  3863  3863 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 16:40:44.142  3863  3863 I Babel_Crash: startup - clean
,08-29 16:40:44.169  3863  3863 I Babel_telephony: TeleModule.launchCompleted
,08-29 16:40:44.182   873   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 16:40:44.193  3863  3863 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-29 16:40:44.204  3863  3863 W Babel   : BAM#gBA: invalid account id: -1
08-29 16:40:44.204  3863  3863 W Babel   : BAM#gBA: invalid account id: -1
08-29 16:40:44.205  3863  3863 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-29 16:40:44.211  3863  3893 I Babel   : deleted: false for 0
,08-29 16:40:44.218   873  1909 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 16:40:44.239  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:40:44.244  1738  1738 D SystemUpdateService: onCreate
,08-29 16:40:44.248  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:40:44.278  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 16:40:44.283  1738  2342 I iu.UploadsManager: num queued entries: 0
,08-29 16:40:44.296  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:40:44.301  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:40:44.314  1738  3895 I SystemUpdateService: active receiver: enabled
,08-29 16:40:44.325  3863  3863 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:44.284  1738  2342 I iu.UploadsManager: num updated entries: 0
,08-29 16:40:44.329  1738  2342 I iu.SyncManager: NEXT; no task
,08-29 16:40:44.341   873  2014 I ActivityManager: Start proc 3897:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 16:40:44.355  1738  3895 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:40:44.383  1738  3895 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 16:40:44.383  1738  3895 I SystemUpdateService: now status is 0 (complete)
08-29 16:40:44.383  1738  3895 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 16:40:44.384  1738  3895 I SystemUpdateService: file has been verified
,08-29 16:40:44.384  1738  3895 I SystemUpdateService: OTA package size = 12249756
,08-29 16:40:44.395  3863  3863 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 16:40:44.407  3863  3863 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:44.416  3863  3863 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:44.421  3897  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 16:40:44.430  3863  3863 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:44.436  3897  3897 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:44.441  3863  3863 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:44.455  3863  3863 I vclib   : onServiceConnected
,08-29 16:40:44.459  3897  3897 D SprintDMHelper: simOperator: 
,08-29 16:40:44.459  3897  3897 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:40:44.465  1738  3895 I SystemUpdateService: showing system update notification
,08-29 16:40:44.491   873   883 I ActivityManager: Start proc 3909:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 16:40:44.493   873   883 I ActivityManager: Killing 3233:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
08-29 16:40:44.503  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-29 16:40:44.503  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 16:40:44.503  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:40:44.589  1738  1738 D SystemUpdateService: onDestroy
,08-29 16:40:44.597   873  2014 I ActivityManager: Killing 3382:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 16:40:44.679   873   884 I ActivityManager: Start proc 3924:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 16:40:44.682  3863  3923 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 16:40:44.686   873  2018 I ActivityManager: Killing 3568:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 16:40:44.752  3924  3924 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 16:40:44.841  3924  3924 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 16:40:44.841  3924  3924 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 16:40:44.841  3924  3924 I GAv4    :   adb logcat -s GAv4
,08-29 16:40:44.856  3924  3924 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:40:44.863  3924  3924 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:40:44.891  3924  3941 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:40:44.995  3924  3924 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 16:40:45.038  3924  3924 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 16:40:45.048  3924  3924 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5734-5737)
08-29 16:40:45.048  3924  3924 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 16:40:45.066  3924  3924 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33c7179}
,08-29 16:40:45.067  3924  3924 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 16:40:45.068  3924  3924 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 16:40:45.077  3924  3924 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 16:40:45.079  3924  3924 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 16:40:45.093  3924  3924 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 16:40:45.110  3924  3924 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:40:45.110  3924  3924 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:40:45.110  3924  3924 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 16:40:45.110  3924  3924 I Adreno  : Build Date                       : 10/20/15
08-29 16:40:45.110  3924  3924 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 16:40:45.110  3924  3924 I Adreno  : Local Branch                     : M14
08-29 16:40:45.110  3924  3924 I Adreno  : Remote Branch                    : 
08-29 16:40:45.110  3924  3924 I Adreno  : Remote Branch                    : 
08-29 16:40:45.110  3924  3924 I Adreno  : Reconstruct Branch               : 
,08-29 16:40:45.173  3924  3924 I NSApplication: Starting up...
,08-29 16:40:45.182  3924  3970 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 16:40:45.210   873  1981 I ActivityManager: Start proc 3975:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 16:40:45.211   873  1981 I ActivityManager: Killing 3450:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 16:40:45.212   280   280 E lowmemorykiller: Error writing /proc/3450/oom_score_adj; errno=22
,08-29 16:40:45.301  3975  3975 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 16:40:45.415   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=16.75 rxSuccessRate=18.50 delta 1000 -> 994
,08-29 16:40:45.417   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 16:40:45.417   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 16:40:45.447   873  1311 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:45.479   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 16:40:45.480  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 16:40:45.526   873  2002 I ActivityManager: Killing 3491:android.process.acore/u0a5 (adj 15): empty #17
,08-29 16:40:45.914  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 16:40:45.962  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 16:40:45.963  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 16:40:45.971   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:40:45.977   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:40:45.978   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 16:40:45.978   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:45.995   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:46.005   371   871 D CommandListener: Setting iface cfg
,08-29 16:40:46.006   873  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 16:40:46.021   873  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 16:40:46.029   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 16:40:46.052   873  3995 D DhcpClient: Receive thread started
,08-29 16:40:46.136   873  1311 E native  : do suspend false
,08-29 16:40:46.159   873  1842 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 16:40:46.178   873  3995 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-29 16:40:46.181   873  1842 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-29 16:40:46.185   873  1842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 16:40:46.198   873  3995 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 16:40:46.199   873  1842 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 16:40:46.208   371   871 D CommandListener: Setting iface cfg
,08-29 16:40:46.220   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 16:40:46.222   873  1842 D DhcpClient: Scheduling renewal in 86399s
,08-29 16:40:46.232   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 16:40:46.236   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 16:40:46.236   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 16:40:46.238   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 16:40:46.240   873  1314 D ConnectivityService: Adding iface wlan0 to network 101
08-29 16:40:46.241   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 16:40:46.308   873  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 16:40:46.308   873  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 16:40:46.313   873  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 16:40:46.317   873  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 16:40:46.320   873  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 16:40:46.328   873  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 16:40:46.332   873  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 16:40:46.332   873  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-29 16:40:46.333   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 16:40:46.333   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:40:46.333   873  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 16:40:46.333   873  1314 D ConnectivityService:    accepting network in place of null
,08-29 16:40:46.335   873  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:40:46.366   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:40:46.399   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:40:46.407   873  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 16:40:46.408   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:46.417   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 16:40:46.426   873  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:46.439  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:46.443  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:46.450  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:46.452  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:46.455  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:46.456  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:46.458  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:46.459  1738  1738 D SystemUpdateService: onCreate
,08-29 16:40:46.461  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:40:46.466   873  3994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137155, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 16:40:46.479  1738  4005 I SystemUpdateService: active receiver: enabled
,08-29 16:40:46.483  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 16:40:46.485  1738  2342 I iu.UploadsManager: num queued entries: 0
,08-29 16:40:46.486  1738  2342 I iu.UploadsManager: num updated entries: 0
,08-29 16:40:46.486  1738  2342 I iu.SyncManager: NEXT; no task
,08-29 16:40:46.495  1738  4005 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-29 16:40:46.496  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:40:46.497  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:40:46.499  3897  3897 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:46.503  1738  4008 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 16:40:46.503  1738  4008 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 16:40:46.505  1738  4008 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:40:46.506  3897  3897 D SprintDMHelper: simOperator: 
08-29 16:40:46.506  3897  3897 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:40:46.516  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:40:46.521  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 16:40:46.522  1738  4005 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 16:40:46.522  1738  4005 I SystemUpdateService: now status is 0 (complete)
08-29 16:40:46.522  1738  4005 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:40:46.522  1738  4005 I SystemUpdateService: file has been verified
08-29 16:40:46.522  1738  4005 I SystemUpdateService: OTA package size = 12249756
,08-29 16:40:46.545  1738  4005 I SystemUpdateService: showing system update notification
,08-29 16:40:46.585  1556  2107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 16:40:46.585  1556  2107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 16:40:46.585  1556  2107 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:40:46.585  1556  2107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:40:46.592   873  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.78,2a00:1450:4001:814::200e
,08-29 16:40:46.602  1738  1738 D SystemUpdateService: onDestroy
,08-29 16:40:46.610  1738  4008 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-29 16:40:46.678   873  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:40:46 GMT], X-Android-Received-Millis=[1472481646677], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472481646637]}
,08-29 16:40:46.680   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 16:40:46.681   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 16:40:46.681   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 16:40:46.685   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 16:40:46.698  3863  4011 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 16:40:47.407   873  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 16:40:49.007  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:40:49.008  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 16:40:49.008  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 16:40:49.009  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 16:40:49.009  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 16:40:49.009  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 16:40:49.011  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:40:49.011  3797  3883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-29 16:40:49.011  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 16:40:49.011  3797  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:40:49.012  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:40:49.012  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 16:40:49.012  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:40:49.012  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:40:49.013  3797  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 16:40:49.013  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:40:49.014  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:40:49.016  3797  3848 D BluetoothAdapter: STATE_ON
08-29 16:40:49.017  3797  3848 D BluetoothLeScanner: could not find callback wrapper
08-29 16:40:49.017  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:40:49.018  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 16:40:49.020  2687  2708 D BtGatt.AdvertiseManager: message : 1
08-29 16:40:49.021  2687  2708 D BtGatt.AdvertiseManager: stop advertise for client 5
08-29 16:40:49.029   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 16:40:49.031  2687  2706 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 16:40:49.031  2687  2706 D BtGatt.GattService: Client app is not null!
08-29 16:40:49.034  2687  2698 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 16:40:49.035  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 16:40:49.035  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 16:40:49.035  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 16:40:49.035  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 16:40:49.035  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 16:40:49.039  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:40:49.039  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 16:40:49.039  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:40:49.040  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:40:49.041  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:49.041  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:49.041  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:40:49.041  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:40:49.041  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:49.041  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:40:49.041  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:40:49.042  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:49.041  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 16:40:49.042  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:40:49.042  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:40:49.043  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:40:49.544  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:40:49.689  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:40:49.748  1556  1571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 16:40:49.748  1556  1571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 16:40:49.748  1556  1571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:40:49.749  1556  1571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:40:49.782  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 16:40:49.782  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 16:40:49.782  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 16:40:51.127   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,08-29 16:40:52.059   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 16:40:54.052  3797  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-29 16:40:54.061  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:54.079  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:54.088  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:54.089  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:40:54.091  3797  3848 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
08-29 16:40:54.091  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-29 16:40:54.095  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:40:54.095  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 16:40:54.096  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 16:40:54.096  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:54.099  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 16:40:54.103  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 16:40:54.104  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 16:40:54.105  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:40:54.106  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:54.110  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true,
08-29 16:40:54.110  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:54.110  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 16:40:54.115  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:54.115  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 16:40:54.115  3797  4020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:40:54.120  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:40:54.120  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:40:54.121  3797  4020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 16:40:54.125  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:40:54.126  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:40:54.126  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:40:54.130  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 16:40:54.130  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:40:54.130  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
08-29 16:40:54.130  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:54.131  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:54.131  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 16:40:54.132  3797  3848 D BluetoothAdapter: STATE_ON
,08-29 16:40:54.137  2687  2699 D BtGatt.GattService: registerClient() - UUID=62ca0fbb-fe11-41d9-a683-5cde17b1f682
,08-29 16:40:54.138  2687  2706 D BtGatt.GattService: onClientRegistered() - UUID=62ca0fbb-fe11-41d9-a683-5cde17b1f682, clientIf=5
08-29 16:40:54.139  3797  3808 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 16:40:54.142  2687  2708 D BtGatt.AdvertiseManager: message : 0
,08-29 16:40:54.147  2687  2708 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 16:40:54.167  2687  2706 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 16:40:54.187  2687  2706 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 16:40:54.189  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 16:40:54.189  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:40:54.193  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:40:54.195  3797  3848 I io.jxcore.node.ConnectionHelper: start: OK
08-29 16:40:54.195  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 16:40:54.196  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 16:40:54.196  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 16:40:54.196  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 16:40:54.197  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-29 16:40:54.197  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 16:40:54.208  3797  3797 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 16:40:54.208  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:40:54.335   873  1314 D ConnectivityService: handlePromptUnvalidated 101
,08-29 16:40:54.710  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-29 16:40:54.710  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 16:40:54.710  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:40:55.088   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 16:40:59.203  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:40:59.204  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 16:40:59.204  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 16:40:59.204  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 16:40:59.205  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 16:40:59.205  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 16:40:59.206  3797  4020 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-29 16:40:59.207  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:40:59.207  3797  4020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:40:59.207  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 16:40:59.208  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:40:59.208  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 16:40:59.208  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:40:59.207  3797  4020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 16:40:59.208  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:40:59.208  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:40:59.209  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:40:59.212  3797  3848 D BluetoothAdapter: STATE_ON
08-29 16:40:59.215  3797  3848 D BluetoothLeScanner: could not find callback wrapper
08-29 16:40:59.215  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 16:40:59.216  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 16:40:59.219  2687  2708 D BtGatt.AdvertiseManager: message : 1
08-29 16:40:59.220  2687  2708 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 16:40:59.242  2687  2706 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 16:40:59.242  2687  2706 D BtGatt.GattService: Client app is not null!
08-29 16:40:59.245  2687  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:40:59.247  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:40:59.248  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 16:40:59.248  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 16:40:59.249  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-29 16:40:59.249  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 16:40:59.254  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:40:59.255  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:40:59.255  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:40:59.256  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:40:59.257  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:40:59.257  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 16:40:59.258  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 16:40:59.258  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:40:59.258  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 16:40:59.258  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:40:59.259  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:59.259  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:40:59.259  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:40:59.259  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:40:59.259  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:40:59.259  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:40:59.259  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:40:59.259  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:40:59.260  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:59.260  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:40:59.261  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:59.261  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:40:59.261  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:59.261  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:40:59.262  3797  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 16:40:59.264  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:59.274  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:59.277  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:59.277  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:40:59.277  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:40:59.277  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 16:40:59.277  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:40:59.277  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:59.278  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 16:40:59.281  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 16:40:59.281  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 16:40:59.282  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:59.286  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:59.286  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:40:59.287  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:40:59.287  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:40:59.290  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 16:40:59.293  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 16:40:59.293  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 16:40:59.293  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 16:40:59.295  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 16:40:59.297  3797  3848 D BluetoothAdapter: STATE_ON
,08-29 16:40:59.303  2687  2699 D BtGatt.GattService: registerClient() - UUID=286864c6-eec1-4910-b0b1-6098257237ce
08-29 16:40:59.303  2687  2706 D BtGatt.GattService: onClientRegistered() - UUID=286864c6-eec1-4910-b0b1-6098257237ce, clientIf=5
08-29 16:40:59.304  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 16:40:59.305  2687  2698 D BtGatt.GattService: start scan with filters
,08-29 16:40:59.308  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 16:40:59.308  2687  2709 D BtGatt.ScanManager: handling starting scan
08-29 16:40:59.309  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 16:40:59.309  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 16:40:59.309  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:40:59.312  2687  2709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:40:59.314  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:40:59.314  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 16:40:59.314  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:40:59.315  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:40:59.318  3797  3848 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 16:40:59.325  2687  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 16:40:59.325  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:40:59.326  2687  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:40:59.334  2687  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 16:40:59.334  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:40:59.335  2687  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:40:59.335  2687  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 16:40:59.348  2687  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 16:40:59.348  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:40:59.355  2687  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 16:40:59.356  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:40:59.623   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 16:40:59.642  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-29 16:40:59.644   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 16:40:59.644   873   893 I Adreno  : Build Date                       : 10/20/15
08-29 16:40:59.644   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 16:40:59.644   873   893 I Adreno  : Local Branch                     : M14
08-29 16:40:59.644   873   893 I Adreno  : Remote Branch                    : 
08-29 16:40:59.644   873   893 I Adreno  : Remote Branch                    : 
08-29 16:40:59.644   873   893 I Adreno  : Reconstruct Branch               : 
,08-29 16:40:59.669   282   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (178 us)
,08-29 16:40:59.815  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 16:40:59.816  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:40:59.816  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:41:00.314  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 16:41:00.315  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 16:41:00.375   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 16:41:00.377  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1f4ba13 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ff6bc2f, 16908290=android.view.AbsSavedState$1@ff6bc2f}, android:focusedViewId=100}]}]
,08-29 16:41:00.381  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 16:41:00.382  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 16:41:00.382  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-29 16:41:00.385   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 16:41:00.389   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 16:41:00.392   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-29 16:41:00.392   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 16:41:00.618   282   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 16:41:00.622   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 16:41:00.628   873  1336 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,08-29 16:41:00.633   873   893 I DreamManagerService: Entering dreamland.
08-29 16:41:00.634   873   893 I PowerManagerService: Dozing...
,08-29 16:41:00.637   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 16:41:00.685   375  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-29 16:41:00.686   375  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 16:41:00.691  2687  2687 D BtGatt.ScanManager: awakened up at time 151380
,08-29 16:41:00.693  2687  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:41:00.700   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:00.706  1953  4025 D NfcService: Discovery configuration equal, not updating.
,08-29 16:41:00.717   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 16:41:00.721  2687  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 16:41:00.721  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:41:00.722  2687  2706 D BtGatt.GattService: current time is 151411085144
,08-29 16:41:00.722  2687  2706 D BtGatt.GattService: Batch record : [-17, 107, 56, 115, -10, 83, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 16:41:00.723  2687  2706 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96]
08-29 16:41:00.724  2687  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 16:41:00.724  2687  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 16:41:00.725  2687  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 16:41:00.725  2687  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 16:41:00.725  2687  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 16:41:00.731   873  1311 E native  : do suspend false
08-29 16:41:00.731  3797  3797 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 2], added - the peer count is 1
,08-29 16:41:00.733  3797  3797 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 2], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-29 16:41:00.750   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 16:41:00.760   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:00.763   873  1311 E native  : do suspend true
,08-29 16:41:00.818   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 16:41:00.818   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 16:41:01.206   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-29 16:41:02.229  2687  2687 D BtGatt.ScanManager: awakened up at time 152917
,08-29 16:41:02.232  2687  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:41:02.246  2687  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-29 16:41:02.247  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:41:02.247  2687  2706 D BtGatt.GattService: current time is 152936531557
08-29 16:41:02.248  2687  2706 D BtGatt.GattService: Batch record : [-17, 107, 56, 115, -10, 83, 1, -128, -75, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 16:41:02.248  2687  2706 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96]
,08-29 16:41:02.249  2687  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 16:41:02.251  3797  3797 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 2] updated - the peer count is 1
,08-29 16:41:03.753  2687  2687 D BtGatt.ScanManager: awakened up at time 154442
,08-29 16:41:03.755  2687  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:41:03.766  2687  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 16:41:03.766  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:41:04.318  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:41:04.319  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:41:04.319  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:41:04.320  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:04.320  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 16:41:04.320  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:41:04.322  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 16:41:04.323  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:41:04.323  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 16:41:04.329  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:41:04.330  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 16:41:04.334  3797  3848 D BluetoothAdapter: STATE_ON
,08-29 16:41:04.337  2687  2699 D BtGatt.GattService: stopScan() - queue size =1
,08-29 16:41:04.339  2687  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:41:04.340  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 16:41:04.341  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:41:04.342  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 16:41:04.343  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 16:41:04.343  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 16:41:04.345  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:41:04.346  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:41:04.349  2687  2687 D BtGatt.ScanManager: awakened up at time 155038
,08-29 16:41:04.351  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 16:41:04.351  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 16:41:04.352  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:41:04.352  3797  3848 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-29 16:41:04.353  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:41:04.353  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 16:41:04.354  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:41:04.362  2687  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 16:41:04.362  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:41:04.363  2687  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:41:04.378  2687  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 16:41:04.378  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:41:04.378  2687  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:41:04.388  2687  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 16:41:04.388  2687  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:41:04.855  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:41:04.856  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:04.856  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:41:05.725  2140  2638 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 16:41:06.313   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-29 16:41:07.462   873  3994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158150, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:41:09.354  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:41:09.355  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:09.355  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:41:09.355  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.356  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.357  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:41:09.359  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:09.360  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.360  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.362  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:09.362  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.365  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.366  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.369  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:41:09.369  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:41:09.370  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.370  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.373  3797  3848 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 16:41:09.375  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:41:09.375  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:09.376  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:09.376  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:41:09.376  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.376  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.376  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:09.376  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.376  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.377  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:09.377  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.377  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.377  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.377  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.379  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:09.379  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:41:09.379  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.380  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.382  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 16:41:09.383  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.383  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:41:09.383  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:09.384  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.384  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.384  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.384  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:09.385  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.385  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.385  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:09.385  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.386  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.386  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.386  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.388  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:09.389  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:09.389  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.389  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:09.391  3797  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 16:41:09.391  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.392  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:09.392  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:41:09.392  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.393  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.393  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.393  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:09.393  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.394  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.394  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:09.394  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.395  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.395  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.395  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.397  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:41:09.397  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:09.398  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.398  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:09.400  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 16:41:09.400  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.400  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:41:09.400  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:09.401  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.401  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.401  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.402  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:09.402  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.402  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.402  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:09.403  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.403  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.403  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.403  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.406  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:41:09.406  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:09.406  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.406  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:09.408  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 16:41:09.409  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:41:09.409  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:41:09.409  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 16:41:09.410  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:41:09.410  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:41:09.410  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 16:41:09.411  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:41:09.412  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 16:41:09.412  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.413  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:41:09.413  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:41:09.414  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.415  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.415  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.415  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:09.415  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.415  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.415  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:09.415  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.415  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.415  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.415  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.419  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:09.419  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:41:09.419  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.419  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:09.422  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:41:09.422  3797  3848 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 16:41:09.422  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 16:41:09.428  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:41:09.429  3797  3848 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 16:41:09.429  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 16:41:09.430  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 16:41:09.431  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 16:41:09.432  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 16:41:09.432  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 16:41:09.432  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 16:41:09.432  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 16:41:09.432  3797  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 16:41:09.433  3797  3848 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 16:41:09.433  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:41:09.433  3797  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 16:41:09.433  3797  3848 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 16:41:09.433  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:41:09.433  3797  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 16:41:09.433  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 16:41:09.436  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 16:41:09.437  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-29 16:41:09.437  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 16:41:09.438  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-29 16:41:09.438  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 16:41:09.438  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 16:41:09.438  3797  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:41:09.439  3797  3848 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 16:41:09.439  3797  4030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 396)
08-29 16:41:09.440  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.440  3797  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:09.440  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-29 16:41:09.440  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-29 16:41:09.440  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:41:09.441  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.441  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.441  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads,
08-29 16:41:09.442  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:09.442  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.442  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:09.442  3797  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 396
,08-29 16:41:09.442  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:09.442  3797  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 396),
08-29 16:41:09.442  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.443  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.443  3797  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 396)
,08-29 16:41:09.443  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:09.443  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.445  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:09.445  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:09.445  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:09.445  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.445  3797  4030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 396)
08-29 16:41:09.446  3797  3848 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 16:41:09.448  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.449  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:09.449  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:41:09.449  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:41:09.449  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.450  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.450  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:09.450  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.450  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.450  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:09.450  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.450  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.450  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.450  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.451  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:09.452  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:41:09.452  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.452  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.453  3797  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 16:41:09.453  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.453  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:09.453  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:41:09.454  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.454  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.454  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.454  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:09.455  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.455  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:09.455  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:09.455  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.455  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.455  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.455  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.457  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:41:09.457  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:09.457  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.457  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.458  3797  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 16:41:09.458  3797  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 16:41:09.458  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 16:41:09.458  3797  3848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-29 16:41:09.458  3797  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 16:41:09.459  3797  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 16:41:09.459  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 16:41:09.459  3797  3848 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 16:41:09.459  3797  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 16:41:09.459  3797  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-29 16:41:09.459  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 16:41:09.459  3797  3848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 16:41:09.459  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:09.459  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:09.459  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:09.460  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:41:09.460  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.460  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.460  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:09.460  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.460  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.460  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:09.460  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.460  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.460  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.460  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.462  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:09.462  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:41:09.462  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.462  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.463  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:09.463  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.463  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:09.463  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:09.463  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:09.463  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:09.463  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:09.463  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:09.463  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:09.877  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:10.028  1556  4033 I VacuumService: Vacuum at: now=1472481670028 tag=VacuumService
,08-29 16:41:10.029  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:10.041  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:10.043  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:10.101  1556  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 16:41:10.101  1556  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 16:41:10.101  1556  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:41:10.101  1556  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:10.122  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 16:41:10.123  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 16:41:10.123  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-29 16:41:10.191  1556  4034 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-29 16:41:10.194  1556  4034 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 16:41:10.224  1556  4034 W Uploader:  no longer exists, so no auth token.
,08-29 16:41:14.465  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:14.465  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:14.465  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:41:14.466  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:41:14.466  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:14.466  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:14.467  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:14.467  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:41:14.467  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:41:14.468  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:41:14.468  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.468  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.469  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:14.469  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.470  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.470  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:14.470  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.471  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.471  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.471  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.475  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:14.475  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:14.475  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:14.476  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
,08-29 16:41:14.480  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 16:41:14.482  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:41:14.482  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 16:41:14.483  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 16:41:14.483  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 16:41:14.483  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-29 16:41:14.483  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:41:14.483  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 16:41:14.484  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 16:41:14.485  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 16:41:14.485  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 16:41:14.485  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
08-29 16:41:14.485  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.485  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 16:41:14.485  3797  4041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:41:14.487  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:14.488  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:14.488  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:41:14.488  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:41:14.488  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:41:14.488  3797  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 16:41:14.488  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 16:41:14.488  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.488  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.490  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:41:14.490  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.490  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:14.491  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:41:14.491  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:14.491  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:14.491  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.491  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:14.491  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:41:14.491  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:14.491  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:14.491  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.491  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:14.491  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 16:41:14.491  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.491  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 16:41:14.492  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.492  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:14.492  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 16:41:14.493  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:41:14.493  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:14.493  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:14.493  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.493  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.495  3797  3848 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 16:41:14.495  3797  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 16:41:14.495  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 16:41:14.495  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:41:14.495  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:41:14.495  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:14.496  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:14.496  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:14.496  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:14.496  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.496  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.496  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
,08-29 16:41:14.496  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.496  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.496  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:14.496  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.496  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.496  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.497  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.498  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:14.498  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:41:14.498  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.498  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.501  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:14.501  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:14.502  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:14.502  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:14.502  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.502  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:14.502  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:14.502  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.502  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.502  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:14.502  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.502  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.502  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.502  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.505  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:41:14.505  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:14.505  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.506  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.506  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:41:14.506  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:41:14.507  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:41:14.507  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:41:14.507  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.507  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 16:41:14.507  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@702355 not in the list
08-29 16:41:14.507  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.507  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.507  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:14.507  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.507  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:41:14.507  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:14.507  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:14.508  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:41:14.509  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:41:14.509  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:41:14.509  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@341216a not in the list
08-29 16:41:14.510  3797  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 16:41:14.510  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 16:41:14.510  3797  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 16:41:14.510  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 16:41:14.510  3797  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 16:41:14.510  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 16:41:14.513  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 16:41:14.513  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 16:41:14.513  3797  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 16:41:14.513  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 16:41:14.514  3797  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 16:41:14.514  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 16:41:14.514  3797  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 16:41:14.514  3797  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-29 16:41:14.514  3797  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 16:41:14.515  3797  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 16:41:14.515  3797  3848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 16:41:14.515  3797  3848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 16:41:14.515  3797  3848 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 16:41:14.515  3797  3848 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 16:41:14.516  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:41:14.517  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83cec4b added. We now have 3 listener(s)
08-29 16:41:14.517  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:41:14.518  3797  3848 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 16:41:14.519   873  1981 D WifiService: setWifiEnabled: true pid=3797, uid=10000
08-29 16:41:14.519   873  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:41:14.568  2687  2800 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 16:41:14.568  2687  2810 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 6
,08-29 16:41:14.994  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:41:15.255   873  3994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:41:16.655  3748  4043 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:41:16.676  3748  4045 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:41:16.686  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:16.687  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:16.712  1556  1574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 16:41:16.712  1556  1574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 16:41:16.712  1556  1574 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:41:16.712  1556  1574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:16.756  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 16:41:16.757  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:16.764  3006  4044 V KeepSync: Connecting to GoogleApiClient
,08-29 16:41:16.765   873  1378 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:41:16.782  1556  1571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 16:41:16.782  1556  1571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 16:41:16.782  1556  1571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:41:16.782  1556  1571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:16.804  3748  4045 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 16:41:16.811  3748  4043 E BooksSync: Soft error
08-29 16:41:16.811  3748  4043 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:41:16.811  3748  4043 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:41:16.812  3748  4043 E BooksSync: Sync error
08-29 16:41:16.812  3748  4043 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:41:16.812  3748  4043 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 16:41:16.812  3748  4043 I BooksSync: Finished books sync
,08-29 16:41:16.819   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159166, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:41:16.833  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:16.835  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:16.860  1556  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 16:41:16.860  1556  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 16:41:16.861  1556  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:41:16.861  1556  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:16.874  1738  4047 V BaseAuthAsyncOperation: access token request failed
,08-29 16:41:16.875  3006  4044 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:41:16.917  1556  2887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 16:41:16.917  1556  2887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 16:41:16.917  1556  2887 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:41:16.917  1556  2887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:16.934  3006  4044 E KeepSync: IOException
08-29 16:41:16.934  3006  4044 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:41:16.934  3006  4044 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:41:16.934  3006  4044 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:41:16.934  3006  4044 E KeepSync: 	... 10 more
,08-29 16:41:16.935  3006  4044 W KeepSync: Sync result 2
,08-29 16:41:16.942   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 159844, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:41:19.385  1556  4034 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-29 16:41:19.385  1556  4034 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-29 16:41:19.385  1556  4034 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:41:19.385  1556  4034 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:19.402  1556  4034 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 16:41:19.402  1556  4034 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 16:41:19.402  1556  4034 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 16:41:19.525  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:41:19.525  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef1a628 added. We now have 4 listener(s)
,08-29 16:41:19.526  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:41:19.544  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:19.545  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef1a628 removed from the list
,08-29 16:41:19.545  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:19.546  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:19.546  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:19.548  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:41:19.548  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8741f41 added. We now have 4 listener(s)
,08-29 16:41:19.548  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:41:19.551  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:19.552  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8741f41 removed from the list
,08-29 16:41:19.552  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:19.552  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:19.552  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:19.554  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:41:19.555  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83d4ce6 added. We now have 4 listener(s)
,08-29 16:41:19.555  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:41:19.560   873  1981 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,08-29 16:41:19.561   873  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:41:19.570  2687  2702 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 16:41:19.570  2687  2702 D BluetoothAdapterProperties: Setting state to 13
08-29 16:41:19.570  2687  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 16:41:19.571  2687  2702 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 16:41:19.574  2687  2687 D BluetoothMapService: onReceive
08-29 16:41:19.574  2687  2687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 16:41:19.574  2687  2687 D BluetoothMapService: STATE_TURNING_OFF
08-29 16:41:19.574  2687  2687 D BluetoothMapService: MAP Service closeService in
,08-29 16:41:19.574  2687  2687 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 16:41:19.574  2687  2687 D ObexServerSockets0: shutdown(block = true)
,08-29 16:41:19.575  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 16:41:19.575  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 16:41:19.575  2687  2844 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 16:41:19.576  2687  2846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 16:41:19.579  2687  2810 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 16:41:19.580  2687  2702 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:41:19.581  2687  2687 I BtOppRfcommListener: stopping Accept Thread
08-29 16:41:19.582  2687  3431 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 16:41:19.583  2687  3431 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 16:41:19.583  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:41:19.583  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:41:19.585  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.585  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:19.588  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 16:41:19.589   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 16:41:19.589   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 16:41:19.589   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:41:19.589   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:41:19.591  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:41:19.591  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:41:19.592  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:19.592  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:41:19.604   873   886 I ActivityManager: Start proc 4054:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 16:41:19.605   873  1311 E native  : do suspend true
08-29 16:41:19.605  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:41:19.607  2687  2706 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:41:19.607  2687  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 16:41:19.611  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:41:19.611  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:41:19.611  2687  2687 D HeadsetService: Received stop request...Stopping profile...
,08-29 16:41:19.612  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.612  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:19.612  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:41:19.614  2687  2687 D A2dpService: Received stop request...Stopping profile...
,08-29 16:41:19.614  1965  1980 D BluetoothHeadset: Proxy object disconnected
,08-29 16:41:19.614  2687  2823 D A2dpStateMachine: Exit Disconnected: -1
,08-29 16:41:19.614   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 16:41:19.615   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 16:41:19.615  1366  1380 D BluetoothHeadset: Proxy object disconnected
08-29 16:41:19.615  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.615  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-29 16:41:19.616   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 16:41:19.617   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 16:41:19.617  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-29 16:41:19.617   873  1842 D DhcpClient: Clearing IP address
08-29 16:41:19.618   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 16:41:19.618  2687  2687 D HidService: Received stop request...Stopping profile...
08-29 16:41:19.618  2687  2687 D HidService: Stopping Bluetooth HidService
08-29 16:41:19.619  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-29 16:41:19.619  1366  1366 D HidProfile: Bluetooth service disconnected
08-29 16:41:19.620  2687  2687 D HealthService: Received stop request...Stopping profile...
08-29 16:41:19.620  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.620   371   871 D CommandListener: Setting iface cfg
08-29 16:41:19.622  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:19.622  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:19.622  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:19.622  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:19.623  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.623  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 16:41:19.624  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 16:41:19.624  2687  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 16:41:19.624  1556  4016 V NativeCrypto: Read error: ssl=0x9a384c00: I/O error during system call, Connection timed out
08-29 16:41:19.624  2687  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:19.624  2687  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:19.624  2687  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:19.624  2687  2706 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 16:41:19.625  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.625  1556  4016 V NativeCrypto: SSL shutdown failed: ssl=0x9a384c00: I/O error during system call, Broken pipe
08-29 16:41:19.627  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.627  2687  2687 D PanService: Received stop request...Stopping profile...
08-29 16:41:19.628  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 16:41:19.628  1366  1366 D PanProfile: Bluetooth service disconnected
08-29 16:41:19.628   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 16:41:19.629   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:41:19.629   873  1311 E native  : do suspend true
08-29 16:41:19.630   873  2002 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-29 16:41:19.630   873  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-29 16:41:19.632   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 16:41:19.632   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 16:41:19.634  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:19.634  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:19.634,  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:19.634  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:19.635  2687  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 16:41:19.635   873  3995 D DhcpClient: Receive thread stopped
08-29 16:41:19.635  2687  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:19.636  2687  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:19.636  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:19.636  2687  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 16:41:19.636  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:19.636  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:19.636  2687  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 16:41:19.636  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:19.636  2687  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 16:41:19.636  2687  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 16:41:19.636  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 16:41:19.636  2687  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 16:41:19.636  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 16:41:19.639   873  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 16:41:19.639   407   407 E Parcel  : Reading a NULL string not supported here.
08-29 16:41:19.637  2687  2687 D BluetoothMapService: Received stop request...Stopping profile...
08-29 16:41:19.643  2687  2687 D BluetoothMapService: stop()
08-29 16:41:19.643  2687  2687 D BluetoothMapAppObserver: deinitObservers()
08-29 16:41:19.643  2687  2687 D BluetoothMapAppObserver: removeReceiver()
08-29 16:41:19.645   873  3993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 16:41:19.646  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:19.646  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:19.646  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:19.646  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:19.646  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 16:41:19.646  2687  2706 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 16:41:19.648  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 16:41:19.648  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:19.649  1366  1366 D BluetoothMap: Proxy object disconnected
08-29 16:41:19.649  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:41:19.649  1366  1366 D MapProfile: Bluetooth service disconnected,
08-29 16:41:19.649  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:19.649  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:19.649  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 16:41:19.649  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 16:41:19.649  2687  2687 D BluetoothMapService: MAP Service closeService in
,08-29 16:41:19.650  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:19.650  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:19.650  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:19.650  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:19.650  2687  2687 D BluetoothMapService: cleanup()
08-29 16:41:19.650  2687  2687 D BluetoothMapService: MAP Service closeService in
08-29 16:41:19.650  2687  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26,
08-29 16:41:19.650  2687  2702 D BluetoothAdapterProperties: Setting state to 15
08-29 16:41:19.650  2687  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 16:41:19.651  2687  2702 I BluetoothAdapterState: Entering BleOnState
,08-29 16:41:19.653  1366  2074 D BluetoothInputDevice: onBluetoothStateChange: up=false,
08-29 16:41:19.654  1366  1386 D BluetoothPan: onBluetoothStateChange on: false
08-29 16:41:19.655  1366  1380 D BluetoothMap: onBluetoothStateChange: up=false
08-29 16:41:19.655  1366  2074 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 16:41:19.656   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 16:41:19.656   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:19.656   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 16:41:19.656  1965  1977 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:19.656  1366  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 16:41:19.656  1366  1380 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 16:41:19.658   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:19.658  2687  2702 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-29 16:41:19.658  2687  2702 D BluetoothAdapterProperties: Setting state to 16
,08-29 16:41:19.658  2687  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 16:41:19.659  2687  2702 D BluetoothAdapterProperties: onBleDisable
08-29 16:41:19.659  2687  2702 I BluetoothAdapterState: Entering PendingCommandState
08-29 16:41:19.659  2687  2703 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 16:41:19.660  2687  2800 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 16:41:19.660  2687  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:19.660  2687  2706 D BluetoothAdapterProperties: Scan Mode:20
08-29 16:41:19.664  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:19.664  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:19.664  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.664  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:19.666  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:19.666  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:19.666  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.667  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:19.668   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 16:41:19.669  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:19.669  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:19.669  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.669  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:19.670  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.671  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.672  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.689   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 16:41:19.689   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 16:41:19.690  4054  4054 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-29 16:41:19.691   873  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 16:41:19.691   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 16:41:19.695   873   890 D Tethering: Master,InitialState.processMessage what=3
08-29 16:41:19.699   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 16:41:19.700  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.701  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:19.703  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:19.717   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:19.719  2140  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 16:41:19.719  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:19.720  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:19.720   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 16:41:19.720  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.720  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:19.721  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:19.721  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:19.722  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.722  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:19.723  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:19.723  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:19.724  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:19.724  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:19.732  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:41:19.736  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:19.738   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3891f0:true
,08-29 16:41:19.748   873  1909 I ActivityManager: Start proc 4077:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 16:41:19.749   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 16:41:19.749   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 16:41:19.756  4054  4054 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 16:41:19.759  4054  4054 D BluetoothMap: Create BluetoothMap proxy object
,08-29 16:41:19.766  4054  4054 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 16:41:19.775  1556  4034 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-29 16:41:19.801  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:41:19.814  4077  4077 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 16:41:19.824   873   884 I ActivityManager: Killing 3652:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 16:41:19.866  2687  2706 I bt_hci  : shut_down
,08-29 16:41:19.866  2687  2710 D bt_hwcfg: hw_epilog_process
,08-29 16:41:19.879  2687  2710 I bt_vendor: low_power_mode_cb
,08-29 16:41:19.903  2687  2710 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 16:41:19.903  2687  2710 I bt_vendor: epilog_cb
,08-29 16:41:19.903  2687  2710 I bt_hci  : epilog_finished_callback
,08-29 16:41:19.910  2687  2706 I bt_hci_h4: hal_close
,08-29 16:41:19.911  2687  2706 I bt_userial_vendor: device fd = 51 close
,08-29 16:41:20.025  4077  4077 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.025  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026,  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:41:20.026  4077  4077 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:41:20.026  4077  4077 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:41:20.034  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 16:41:20.035  2687  2703 D bt_stack_manager: event_shut_down_stack finished.
08-29 16:41:20.037  2687  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 16:41:20.043  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:41:20.048  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:20.050  2687  2702 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 16:41:20.050  2687  2687 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 16:41:20.051  2687  2687 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 16:41:20.051  2687  2687 D BtGatt.GattService: stop()
08-29 16:41:20.052  2687  2687 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 16:41:20.054   873  1378 I ActivityManager: Killing 3669:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 16:41:20.125  2687  2687 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:20.125  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:20.126  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:20.126  2687  2687 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 16:41:20.127  2687  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 16:41:20.128  2687  2702 D BluetoothAdapterProperties: Setting state to 10
,08-29 16:41:20.128  2687  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 16:41:20.129  2687  2702 I BluetoothAdapterState: Entering OffState
08-29 16:41:20.133   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 16:41:20.143  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:41:20.153  1738  1738 D SystemUpdateService: onCreate
,08-29 16:41:20.160  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 16:41:20.160  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 16:41:20.160  2687  2687 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 16:41:20.161  2687  2703 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 16:41:20.166  2687  2703 D bt_stack_manager: event_clean_up_stack finished.
,08-29 16:41:20.166  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:41:20.179  2687  2687 I art     : System.exit called, status: 0
,08-29 16:41:20.179  2687  2687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 16:41:20.188  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 16:41:20.196  1738  2342 I iu.UploadsManager: num queued entries: 0
,08-29 16:41:20.197  1738  2342 I iu.UploadsManager: num updated entries: 0
,08-29 16:41:20.197  1738  2342 I iu.SyncManager: NEXT; no task
,08-29 16:41:20.211  1738  4110 I SystemUpdateService: active receiver: enabled
,08-29 16:41:20.214  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:41:20.215  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:41:20.218  3897  3897 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:41:20.229  3897  3897 D SprintDMHelper: simOperator: 
,08-29 16:41:20.230  3897  3897 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:41:20.250  3863  4112 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 16:41:20.261   873  2002 I ActivityManager: Process com.android.bluetooth (pid 2687) has died
,08-29 16:41:20.268  1738  4110 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:41:20.279  1738  4110 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 16:41:20.279  1738  4110 I SystemUpdateService: now status is 0 (complete)
08-29 16:41:20.279  1738  4110 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:41:20.279  1738  4110 I SystemUpdateService: file has been verified
,08-29 16:41:20.280  1738  4110 I SystemUpdateService: OTA package size = 12249756
,08-29 16:41:20.294  1738  4110 I SystemUpdateService: showing system update notification
,08-29 16:41:20.297   873  1983 I ActivityManager: Start proc 4113:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 16:41:20.339  4113  4113 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 16:41:20.372  1738  1738 D SystemUpdateService: onDestroy
,08-29 16:41:20.436  4113  4113 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 16:41:20.445  4077  4098 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 16:41:20.471   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c15197c:true
,08-29 16:41:24.615   873  1909 D WifiService: setWifiEnabled: true pid=3797, uid=10000
,08-29 16:41:24.615   873  1909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:41:24.633   873  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-29 16:41:24.640  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:24.640  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:24.640  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:24.641  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:24.644  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:24.645  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:24.645  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:24.645  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:24.649  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:24.649  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:24.649  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:24.650  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:24.683   873  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-29 16:41:24.684   873  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 16:41:24.685   873  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 16:41:24.686   873  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 16:41:24.687   873  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 16:41:24.687   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 16:41:24.687   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 16:41:24.702   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:41:24.702   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 16:41:24.706   371   871 D CommandListener: Setting iface cfg
,08-29 16:41:24.712   873  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-29 16:41:24.712   873  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 16:41:24.712   873  1311 E native  : do suspend true
,08-29 16:41:24.724   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:24.727   873  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 16:41:24.739   873  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 16:41:25.556   873  1909 I ActivityManager: Killing 2236:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 16:41:26.090   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:41:26.129   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=7.06 delta 1000 -> 994
,08-29 16:41:26.132   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 16:41:26.132   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:41:26.153   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 16:41:26.221   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 16:41:26.226  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 16:41:26.646  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 16:41:26.694  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 16:41:26.695  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 16:41:26.698   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:26.712   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:41:26.712   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:41:26.712   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 16:41:26.733   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:41:26.747   371   871 D CommandListener: Setting iface cfg
,08-29 16:41:26.748   873  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 16:41:26.757   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 16:41:26.794   873  4148 D DhcpClient: Receive thread started
,08-29 16:41:26.880   873  1311 E native  : do suspend false
,08-29 16:41:26.902   873  1842 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 16:41:26.918   873  4148 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172759, domain null
,08-29 16:41:26.919   873  1842 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172759 seconds
,08-29 16:41:26.922   873  1842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 16:41:26.947   873  4148 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 16:41:26.948   873  1842 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 16:41:26.953   371   871 D CommandListener: Setting iface cfg
,08-29 16:41:26.964   873  1842 D DhcpClient: Scheduling renewal in 86399s
,08-29 16:41:26.965   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 16:41:26.970   873  1311 E native  : do suspend true
,08-29 16:41:26.995   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 16:41:26.998   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 16:41:27.000   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 16:41:27.003   873  1314 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 16:41:27.016   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 16:41:27.059   873  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 16:41:27.059   873  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 16:41:27.061   873  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 16:41:27.062   873  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 16:41:27.065   873  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 16:41:27.075   873  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 16:41:27.082   873  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 16:41:27.083   873  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-29 16:41:27.083   873  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-29 16:41:27.083   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 16:41:27.083   873  1314 D ConnectivityService:    accepting network in place of null
,08-29 16:41:27.084   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:41:27.085   873  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:41:27.116   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:41:27.148   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:41:27.158   873  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 16:41:27.158   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:41:27.168   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 16:41:27.175   873  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 16:41:27.176  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:41:27.177  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:41:27.177  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:27.177  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:27.183  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:41:27.183  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:41:27.183  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:27.183  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:41:27.191  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:41:27.192  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:41:27.192  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:27.192  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:41:27.197   873  4147 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177886, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 16:41:27.201  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:41:27.205  1738  1738 D SystemUpdateService: onCreate
,08-29 16:41:27.212  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:41:27.238  1738  4157 I SystemUpdateService: active receiver: enabled
,08-29 16:41:27.242  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 16:41:27.250  1738  2342 I iu.UploadsManager: num queued entries: 0
,08-29 16:41:27.251  1738  2342 I iu.UploadsManager: num updated entries: 0
,08-29 16:41:27.253  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:41:27.255  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:41:27.259  1738  4157 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:41:27.261  3897  3897 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:41:27.276  1738  4159 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 16:41:27.277  1738  4159 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 16:41:27.280  3897  3897 D SprintDMHelper: simOperator: 
,08-29 16:41:27.280  3897  3897 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:41:27.284  1738  4159 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:41:27.290  1738  2342 I iu.SyncManager: NEXT; no task
,08-29 16:41:27.290  1738  4157 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 16:41:27.299  1738  4157 I SystemUpdateService: now status is 0 (complete)
,08-29 16:41:27.300  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:27.303  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:27.299  1738  4157 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 16:41:27.305  1738  4157 I SystemUpdateService: file has been verified
,08-29 16:41:27.308  1738  4157 I SystemUpdateService: OTA package size = 12249756
,08-29 16:41:27.324  1738  4157 I SystemUpdateService: showing system update notification
,08-29 16:41:27.390  1738  1738 D SystemUpdateService: onDestroy
,08-29 16:41:27.415  1556  2887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 16:41:27.415  1556  2887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 16:41:27.415  1556  2887 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:41:27.415  1556  2887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:41:27.435  1738  4159 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-29 16:41:27.489   873  4146 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:817::200e
,08-29 16:41:27.609  3863  4162 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 16:41:27.779   873  4146 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:41:27 GMT], X-Android-Received-Millis=[1472481687776], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472481687560]}
,08-29 16:41:27.784   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 16:41:27.785   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 16:41:27.785   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 16:41:27.791   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 16:41:28.157   873  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 16:41:29.628   873  1981 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,08-29 16:41:29.628   873  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:41:29.666  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 16:41:29.669   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 16:41:29.669   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 16:41:29.669   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:41:29.669   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:41:29.687   873  1311 E native  : do suspend true
,08-29 16:41:29.701   873  1842 D DhcpClient: Clearing IP address
,08-29 16:41:29.701   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 16:41:29.705   371   871 D CommandListener: Setting iface cfg
,08-29 16:41:29.708   873  4148 D DhcpClient: Receive thread stopped
08-29 16:41:29.709  1556  4167 V NativeCrypto: Read error: ssl=0x9a384c00: I/O error during system call, Connection timed out
,08-29 16:41:29.715  1556  4167 V NativeCrypto: SSL shutdown failed: ssl=0x9a384c00: I/O error during system call, Broken pipe
,08-29 16:41:29.719   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 16:41:29.720   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
,08-29 16:41:29.726   407   407 E Parcel  : Reading a NULL string not supported here.
,08-29 16:41:29.726   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 3
08-29 16:41:29.730   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 16:41:29.731   873  1311 E native  : do suspend true
08-29 16:41:29.736   873  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,08-29 16:41:29.790   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:41:29.826   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:41:29.828   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 16:41:29.829   873  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 16:41:29.829   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 16:41:29.833   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:41:29.845  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:29.846  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:29.846  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:29.846  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:29.848   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 16:41:29.849  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:29.849  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:29.850  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:29.850  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:29.853  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:29.853  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:29.853  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.854  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:29.862  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:41:29.868   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:29.871  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:29.871  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:29.871  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.871  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:29.872  1738  1738 D SystemUpdateService: onCreate
08-29 16:41:29.872  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:29.872  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:29.872  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.873  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:29.873  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:29.873  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:29.874  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:29.874  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:29.874   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 16:41:29.875  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 16:41:29.877  2140  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 16:41:29.893  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 16:41:29.895  1738  2342 I iu.UploadsManager: num queued entries: 0
,08-29 16:41:29.900  1738  4177 I SystemUpdateService: active receiver: enabled
,08-29 16:41:29.902  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:41:29.903  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:41:29.906  3897  3897 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:41:29.910  3897  3897 D SprintDMHelper: simOperator: 
,08-29 16:41:29.910  3897  3897 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:41:29.920  1738  2342 I iu.UploadsManager: num updated entries: 0
,08-29 16:41:29.925   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 16:41:29.926   873  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 16:41:29.933  3863  4181 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 16:41:29.945  1738  4177 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:41:29.947  1738  2342 I iu.SyncManager: NEXT; no task
,08-29 16:41:29.952  1738  4177 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 16:41:29.953  1738  4177 I SystemUpdateService: now status is 0 (complete)
08-29 16:41:29.953  1738  4177 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:41:29.953  1738  4177 I SystemUpdateService: file has been verified
,08-29 16:41:29.953  1738  4177 I SystemUpdateService: OTA package size = 12249756
,08-29 16:41:29.959  1738  4177 I SystemUpdateService: showing system update notification
,08-29 16:41:29.968  1738  1738 D SystemUpdateService: onDestroy
,08-29 16:41:30.728  1556  1556 I art     : Waiting for a blocking GC DisableMovingGc
,08-29 16:41:30.741  1556  1556 I art     : WaitForGcToComplete blocked for 13.197ms for cause DisableMovingGc
,08-29 16:41:30.741  1556  1556 I art     : Starting a blocking GC DisableMovingGc
,08-29 16:41:34.688   873   890 I ActivityManager: Start proc 4186:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 16:41:34.833  4186  4186 D AdapterServiceConfig: Adding HeadsetService
,08-29 16:41:34.834  4186  4186 D AdapterServiceConfig: Adding A2dpService
08-29 16:41:34.834  4186  4186 D AdapterServiceConfig: Adding HidService
08-29 16:41:34.834  4186  4186 D AdapterServiceConfig: Adding HealthService
,08-29 16:41:34.835  4186  4186 D AdapterServiceConfig: Adding PanService
08-29 16:41:34.835  4186  4186 D AdapterServiceConfig: Adding GattService
08-29 16:41:34.836  4186  4186 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 16:41:34.852   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@95c9fd1:true
,08-29 16:41:34.854  4186  4186 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 16:41:34.863  4186  4186 I bt_bluedroid: init
,08-29 16:41:34.863  4186  4198 I BluetoothAdapterState: Entering OffState
,08-29 16:41:34.869  4186  4199 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 16:41:34.870  4186  4199 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 16:41:34.870  4186  4199 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 16:41:34.870  4186  4199 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 16:41:34.873  4186  4186 I bt_bluedroid: get_profile_interface socket
,08-29 16:41:34.878  4186  4186 I bt_bluedroid: get_profile_interface sdp
,08-29 16:41:34.879  4186  4202 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 16:41:34.882  4186  4202 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:41:34.882  4186  4197 I bt_bluedroid: config_hci_snoop_log
,08-29 16:41:34.884   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 16:41:34.891  4186  4198 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 16:41:34.892  4186  4198 D BluetoothAdapterProperties: Setting state to 14
,08-29 16:41:34.892  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14,
,08-29 16:41:34.896  4186  4198 D BluetoothBondStateMachine: make
,08-29 16:41:34.901  4186  4203 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 16:41:34.907  4186  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:41:34.908  4186  4186 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 16:41:34.912  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:34.912  4186  4186 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 16:41:34.913  4186  4186 D BtGatt.GattService: Received start request. Starting profile...
,08-29 16:41:34.913  4186  4186 D BtGatt.GattService: start()
,08-29 16:41:34.913  4186  4186 I bt_bluedroid: get_profile_interface gatt
,08-29 16:41:34.914  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:34.914  4186  4186 D BtGatt.AdvertiseManager: advertise manager created
,08-29 16:41:34.925  4186  4186 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:41:34.925  4186  4186 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:34.925  4186  4186 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 16:41:34.926  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:34.926  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 16:41:34.927  4186  4198 I bt_bluedroid: enable
,08-29 16:41:34.927  4186  4199 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 16:41:34.929  4186  4199 I bt_hci  : start_up
,08-29 16:41:34.942  4186  4199 I bt_vendor: alloc value 0xb3a49189
,08-29 16:41:34.942  4186  4199 I bt_vendor: init
08-29 16:41:34.942  4186  4199 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 16:41:34.943  4186  4199 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 16:41:35.049  4186  4199 D bt_hci  : start_up starting async portion
,08-29 16:41:35.050  4186  4206 I bt_hci  : event_finish_startup
,08-29 16:41:35.050  4186  4206 I bt_hci_h4: hal_open
08-29 16:41:35.050  4186  4206 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 16:41:35.062  4186  4206 I bt_userial_vendor: device fd = 51 open
,08-29 16:41:35.087   873  1314 D ConnectivityService: handlePromptUnvalidated 102
,08-29 16:41:35.091  4186  4206 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:41:35.123  4186  4206 D bt_hwcfg: Chipset BCM4354A2
,08-29 16:41:35.124  4186  4206 D bt_hwcfg: Target name = [BCM4354A2]
08-29 16:41:35.125  4186  4206 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 16:41:35.787  4186  4206 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 16:41:35.787  4186  4206 D bt_hwcfg: Settlement delay -- 100 ms
08-29 16:41:35.788  4186  4206 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 16:41:35.903  4186  4206 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 16:41:35.903  4186  4206 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 16:41:35.935  4186  4206 I bt_hwcfg: vendor lib fwcfg completed
,08-29 16:41:35.935  4186  4206 I bt_vendor: firmware callback
08-29 16:41:35.935  4186  4206 I bt_hci  : firmware_config_callback
,08-29 16:41:35.943  4186  4211 I bt_btu  : btu_task pending for preload complete event
,08-29 16:41:35.943  4186  4211 I bt_btu_task: Bluetooth chip preload is complete
,08-29 16:41:35.944  4186  4211 I bt_btu  : btu_task received preload complete event
,08-29 16:41:35.953  4186  4211 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 16:41:35.953  4186  4211 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 16:41:35.954  4186  4211 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 16:41:35.954  4186  4211 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 16:41:35.954  4186  4211 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 16:41:35.954  4186  4211 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 16:41:35.955  4186  4211 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 16:41:35.955  4186  4211 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 16:41:35.955  4186  4211 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 16:41:35.955  4186  4211 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 16:41:35.955  4186  4211 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 16:41:35.956  4186  4211 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 16:41:35.956  4186  4211 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 16:41:35.956  4186  4211 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 16:41:35.956  4186  4211 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 16:41:36.058  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:36.070  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:36.074  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:41:36.087  4186  4211 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c6d9d
,08-29 16:41:36.087  4186  4211 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c6d9d 
,08-29 16:41:36.097  4186  4202 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 16:41:36.098  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 16:41:36.099  4186  4202 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 16:41:36.102  4186  4202 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:41:36.103  4186  4202 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:41:36.103  4186  4202 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 16:41:36.104  4186  4202 D bt_hci  : do_postload posting postload work item
08-29 16:41:36.105  4186  4206 I bt_hci  : event_postload
,08-29 16:41:36.105  4186  4206 I bt_vendor: sco_config_cb
08-29 16:41:36.105  4186  4206 I bt_hci  : sco_config_callback postload finished.
,08-29 16:41:36.106  4186  4202 D bt_bte_conf: Device ID record 1 : primary
08-29 16:41:36.107  4186  4202 D bt_bte_conf:   vendorId            = 000f
,08-29 16:41:36.107  4186  4202 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 16:41:36.107  4186  4202 D bt_bte_conf:   product             = 1200
,08-29 16:41:36.107  4186  4202 D bt_bte_conf:   version             = 1436
,08-29 16:41:36.108  4186  4202 D bt_bte_conf:   clientExecutableURL = 
08-29 16:41:36.108  4186  4202 D bt_bte_conf:   serviceDescription  = 
08-29 16:41:36.108  4186  4202 D bt_bte_conf:   documentationURL    = 
08-29 16:41:36.108  4186  4202 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 16:41:36.108  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.109  4186  4199 D bt_stack_manager: event_start_up_stack finished
08-29 16:41:36.109  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 16:41:36.110  4186  4198 D BluetoothAdapterProperties: Setting state to 15
08-29 16:41:36.110  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 16:41:36.111  4186  4206 I bt_vendor: low_power_mode_cb
08-29 16:41:36.112  4186  4198 I BluetoothAdapterState: Entering BleOnState
08-29 16:41:36.116  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.120  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:36.121  4186  4198 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 16:41:36.121  4186  4198 D BluetoothAdapterProperties: Setting state to 11
08-29 16:41:36.121  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 16:41:36.127  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
08-29 16:41:36.129  4186  4186 D HeadsetService: Received start request. Starting profile...
,08-29 16:41:36.132  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.134  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.137  1556  1574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 16:41:36.137  1556  1574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 16:41:36.137  1556  1574 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:41:36.138  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.137  1556  1574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 16:41:36.140  4186  4186 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 16:41:36.140  4186  4186 D HeadsetStateMachine: make
08-29 16:41:36.144  4186  4198 I BluetoothAdapterState: Entering PendingCommandState
08-29 16:41:36.153  4186  4186 D HeadsetStateMachine: max_hf_connections = 1
08-29 16:41:36.153  4186  4186 I bt_bluedroid: get_profile_interface handsfree
,08-29 16:41:36.153  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 16:41:36.154  4186  4202 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 16:41:36.159  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:36.161  4186  4186 D A2dpService: Received start request. Starting profile...
,08-29 16:41:36.162  4186  4186 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 16:41:36.163  4186  4186 I bt_bluedroid: get_profile_interface avrcp
08-29 16:41:36.163  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 16:41:36.163  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 16:41:36.165  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-29 16:41:36.169  4186  4186 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 16:41:36.169  4186  4186 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 16:41:36.169  4186  4186 D A2dpStateMachine: make
,08-29 16:41:36.171  4186  4186 I bt_bluedroid: get_profile_interface a2dp
08-29 16:41:36.171  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 16:41:36.172  4186  4220 D A2dpStateMachine: Enter Disconnected: -2
,08-29 16:41:36.174  4186  4186 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 16:41:36.174  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:36.176  4186  4186 D HidService: Received start request. Starting profile...
08-29 16:41:36.176  4186  4186 I bt_bluedroid: get_profile_interface hidhost
08-29 16:41:36.176  4054  4054 D BluetoothInputDevice: Proxy object connected
,08-29 16:41:36.176  4186  4202 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a83e5
08-29 16:41:36.176  4186  4186 D HidService: setHidService(): set to: null
08-29 16:41:36.176  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 16:41:36.177  4186  4186 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 16:41:36.177  4054  4054 D HidProfile: Bluetooth service connected
08-29 16:41:36.178  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:36.178  4186  4186 D HealthService: Received start request. Starting profile...
,08-29 16:41:36.179  4186  4186 I bt_bluedroid: get_profile_interface health
,08-29 16:41:36.180  4186  4186 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 16:41:36.181  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:36.182  4186  4186 D PanService: Received start request. Starting profile...
08-29 16:41:36.182  4186  4186 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 16:41:36.182  4186  4186 I bt_bluedroid: get_profile_interface pan
08-29 16:41:36.183  4186  4202 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 16:41:36.183  4054  4054 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 16:41:36.184  4054  4054 D PanProfile: Bluetooth service connected
,08-29 16:41:36.187  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:36.188  4186  4186 D BluetoothMapService: Received start request. Starting profile...
,08-29 16:41:36.188  4054  4054 D BluetoothMap: Proxy object connected
08-29 16:41:36.188  4186  4186 D BluetoothMapService: start()
08-29 16:41:36.189  4054  4054 D MapProfile: Bluetooth service connected
08-29 16:41:36.189  4054  4054 D BluetoothMap: getConnectedDevices()
08-29 16:41:36.190  4054  4054 D BluetoothMap: Bluetooth is Not enabled
08-29 16:41:36.190  4186  4186 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 16:41:36.191  4186  4186 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 16:41:36.191  4186  4186 D BluetoothMapAppObserver: createReceiver()
08-29 16:41:36.192  4186  4186 D BluetoothMapAppObserver: initObservers()
08-29 16:41:36.192  4186  4186 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 16:41:36.202  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:36.202  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:36.202  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:36.202  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:36.202  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:36.205  4186  4218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 16:41:36.205  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:36.205  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:36.205  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:36.205  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:36.205  4186  4186 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:41:36.205  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:36.206  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:36.207  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:36.207  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:36.207  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:36.207  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:36.207  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 16:41:36.208  4186  4198 D BluetoothAdapterProperties: ScanMode =  20
,08-29 16:41:36.208  4186  4198 D BluetoothAdapterProperties: State =  11
08-29 16:41:36.209  4186  4202 D BluetoothAdapterProperties: Scan Mode:21
,08-29 16:41:36.209  4186  4202 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 16:41:36.209  4186  4198 D BluetoothAdapterProperties: Setting state to 12
08-29 16:41:36.209  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 16:41:36.210  4186  4198 I BluetoothAdapterState: Entering OnState
08-29 16:41:36.210  1366  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 16:41:36.213  1366  1366 D BluetoothInputDevice: Proxy object connected
,08-29 16:41:36.213  1366  1366 D HidProfile: Bluetooth service connected
08-29 16:41:36.213  4054  4065 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 16:41:36.214  1366  2074 D BluetoothPan: onBluetoothStateChange on: true
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:36.214  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:36.216  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:36.216  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 16:41:36.216  1366  1366 D PanProfile: Bluetooth service connected
,08-29 16:41:36.217  1366  1380 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 16:41:36.218  1366  1366 D BluetoothMap: Proxy object connected
08-29 16:41:36.218  1366  1366 D MapProfile: Bluetooth service connected
08-29 16:41:36.219  1366  1366 D BluetoothMap: getConnectedDevices()
08-29 16:41:36.219  4054  4067 D BluetoothPan: onBluetoothStateChange on: true
08-29 16:41:36.219  1366  2074 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 16:41:36.220  4186  4186 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:36.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:36.220  4186  4186 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 16:41:36.220   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 16:41:36.221   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:36.221   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 16:41:36.221  1965  1977 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:36.222  4054  4065 D BluetoothMap: onBluetoothStateChange: up=true
08-29 16:41:36.222  4054  4067 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:41:36.222  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:36.222  4186  4186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:36.225  1366  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:36.226  1366  1380 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:36.226  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:36.226  4186  4186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:41:36.227   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:36.228  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:36.228  4186  4186 D ObexServerSockets: Succeed to create listening sockets 
08-29 16:41:36.229  4186  4186 D ObexServerSockets0: startAccept()
,08-29 16:41:36.229  4186  4186 D ObexServerSockets0: prepareForNewConnect()
08-29 16:41:36.229   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 16:41:36.230  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.232  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.233  4186  4186 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 16:41:36.233  4054  4054 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 16:41:36.233  4186  4186 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 16:41:36.235  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:36.235  4186  4227 D ObexServerSockets0: Accepting socket connection...
08-29 16:41:36.235  4186  4228 D ObexServerSockets0: Accepting socket connection...
,08-29 16:41:36.236   873   873 D BluetoothA2dp: Proxy object connected
08-29 16:41:36.236  4186  4186 D BluetoothMapService: onReceive
08-29 16:41:36.236  4186  4186 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 16:41:36.236  1366  1366 D BluetoothA2dp: Proxy object connected
08-29 16:41:36.236  4186  4186 D BluetoothMapService: STATE_ON
08-29 16:41:36.238  4054  4054 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 16:41:36.245  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:41:36.248  4054  4054 D BluetoothA2dp: Proxy object connected
,08-29 16:41:36.256  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:36.257  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:41:36.269  1366  1366 D BluetoothPbap: Proxy object connected
,08-29 16:41:36.269  4054  4054 D BluetoothPbap: Proxy object connected
08-29 16:41:36.269  1366  1366 D PbapServerProfile: Bluetooth service connected
08-29 16:41:36.270  4054  4054 D PbapServerProfile: Bluetooth service connected
08-29 16:41:36.270  4186  4186 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:41:36.270  4186  4186 D ObexServerSockets0: prepareForNewConnect()
,08-29 16:41:36.279  4186  4232 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:36.298  4186  4236 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:36.300  4186  4236 I BtOppRfcommListener: Accept thread started.
,08-29 16:41:36.321  1965  2098 D BluetoothHeadset: Proxy object connected
,08-29 16:41:36.321   873   873 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.321   873   873 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.321   873   890 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.322  1965  2131 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.322  1366  1386 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.322  1366  1366 D HeadsetProfile: Bluetooth service connected
08-29 16:41:36.322   873   873 D BluetoothHeadset: Proxy object connected
,08-29 16:41:36.325  1366  1380 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.325  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-29 16:41:36.328   873   890 D BluetoothHeadset: Proxy object connected
,08-29 16:41:36.341  4054  4067 D BluetoothHeadset: Proxy object connected
08-29 16:41:36.341  4054  4054 D HeadsetProfile: Bluetooth service connected
,08-29 16:41:39.645  4186  4198 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 16:41:39.646  4186  4198 D BluetoothAdapterProperties: Setting state to 13
08-29 16:41:39.646  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 16:41:39.648  4186  4198 D BluetoothAdapterProperties: onBluetoothDisable(),
08-29 16:41:39.649  4186  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:41:39.655  4186  4202 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:41:39.655  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 16:41:39.666  4186  4186 D BluetoothMapService: onReceive
,08-29 16:41:39.666  4186  4186 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 16:41:39.667  4186  4186 D BluetoothMapService: STATE_TURNING_OFF
08-29 16:41:39.668  4186  4186 D BluetoothMapService: MAP Service closeService in
08-29 16:41:39.668  4186  4186 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 16:41:39.668  4186  4186 D ObexServerSockets0: shutdown(block = true)
,08-29 16:41:39.670  4186  4186 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 16:41:39.670  4186  4227 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 16:41:39.672  4186  4228 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 16:41:39.674  4186  4186 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 16:41:39.674  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:39.675  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:39.675  4186  4186 I BtOppRfcommListener: stopping Accept Thread
,08-29 16:41:39.678  4186  4236 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 16:41:39.678  4186  4236 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 16:41:39.675  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:41:39.679  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:39.674  4186  4213 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 16:41:39.681  4186  4186 D HeadsetService: Received stop request...Stopping profile...
08-29 16:41:39.682  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:39.682  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:39.683  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:39.683  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:39.683  1965  1980 D BluetoothHeadset: Proxy object disconnected
08-29 16:41:39.684  4054  4065 D BluetoothHeadset: Proxy object disconnected
,08-29 16:41:39.684   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 16:41:39.684   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 16:41:39.684  4186  4186 D A2dpService: Received stop request...Stopping profile...
08-29 16:41:39.684  1366  1386 D BluetoothHeadset: Proxy object disconnected
08-29 16:41:39.685   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 16:41:39.685  4186  4220 D A2dpStateMachine: Exit Disconnected: -1
08-29 16:41:39.685  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:39.685  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:39.686  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:41:39.686  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:39.686   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 16:41:39.687  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-29 16:41:39.687  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 16:41:39.687  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-29 16:41:39.687  4186  4186 D HidService: Received stop request...Stopping profile...
08-29 16:41:39.687  4186  4186 D HidService: Stopping Bluetooth HidService
08-29 16:41:39.688  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.690  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.691  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.692  4054  4054 D HeadsetProfile: Bluetooth service disconnected
08-29 16:41:39.692  4054  4054 D BluetoothA2dp: Proxy object disconnected
08-29 16:41:39.694  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-29 16:41:39.694  1366  1366 D HidProfile: Bluetooth service disconnected
08-29 16:41:39.695  4186  4186 D HealthService: Received stop request...Stopping profile...
08-29 16:41:39.696  4186  4186 D PanService: Received stop request...Stopping profile...
08-29 16:41:39.697  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 16:41:39.697  4054  4054 D DockEventReceiver: finishStartingService: stopping service
08-29 16:41:39.697  1366  1366 D PanProfile: Bluetooth service disconnected
08-29 16:41:39.698  4054  4054 D BluetoothInputDevice: Proxy object disconnected
08-29 16:41:39.698  4054  4054 D HidProfile: Bluetooth service disconnected
08-29 16:41:39.698  4054  4054 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 16:41:39.699  4054  4054 D PanProfile: Bluetooth service disconnected
08-29 16:41:39.699  4186  4186 D Blueto,othMapService: Received stop request...Stopping profile...
08-29 16:41:39.699  4186  4186 D BluetoothMapService: stop()
08-29 16:41:39.700  4186  4186 D BluetoothMapAppObserver: deinitObservers()
08-29 16:41:39.700  4186  4186 D BluetoothMapAppObserver: removeReceiver()
08-29 16:41:39.701  4054  4054 D BluetoothMap: Proxy object disconnected
08-29 16:41:39.702  1366  1366 D BluetoothMap: Proxy object disconnected
08-29 16:41:39.702  4054  4054 D MapProfile: Bluetooth service disconnected
08-29 16:41:39.702  4186  4186 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:39.702  1366  1366 D MapProfile: Bluetooth service disconnected
08-29 16:41:39.702  4186  4186 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:39.702  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:39.702  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:39.704  4186  4186 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 16:41:39.704  4186  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:39.704  4186  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:39.704  4186  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:39.704  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 16:41:39.704  4186  4202 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 16:41:39.704  4186  4186 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 16:41:39.705  4186  4186 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:39.705  4186  4186 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:39.705  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:39.705  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:39.706  4186  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:39.707  4186  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 16:41:39.707  4186  4211 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 16:41:39.707  4186  4211 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 16:41:39.707  4186  4211 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 16:41:39.707  4186  4211 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 16:41:39.707  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 16:41:39.708  4186  4186 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:39.708  4186  4186 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:39.708  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:39.708  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:39.709  4186  4186 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 16:41:39.709  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 16:41:39.709  4186  4186 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 16:41:39.711  4186  4186 V BluetoothAdapterState: isTurningOff()=true
,08-29 16:41:39.711  4186  4186 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:39.711  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:39.712  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:39.712  4186  4186 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 16:41:39.712  4186  4202 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 16:41:39.712  4186  4186 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 16:41:39.713  4186  4186 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:39.713  4186  4186 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:41:39.713  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:39.713  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:39.713  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:39.713  4186  4186 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 16:41:39.714  4186  4186 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 16:41:39.715  4186  4186 D BluetoothMapService: MAP Service closeService in
,08-29 16:41:39.715  4186  4186 V BluetoothAdapterState: isTurningOff()=true
08-29 16:41:39.715  4186  4186 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:41:39.715  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:39.715  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:39.715  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 16:41:39.715  4186  4198 D BluetoothAdapterProperties: Setting state to 15
,08-29 16:41:39.715  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 16:41:39.716  4186  4198 I BluetoothAdapterState: Entering BleOnState
,08-29 16:41:39.716  4186  4186 D BluetoothMapService: cleanup()
,08-29 16:41:39.716  4186  4186 D BluetoothMapService: MAP Service closeService in
,08-29 16:41:39.716  1366  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 16:41:39.717  4054  4067 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 16:41:39.718  1366  1366 D BluetoothPbap: Proxy object disconnected
,08-29 16:41:39.719  1366  1366 D PbapServerProfile: Bluetooth service disconnected
08-29 16:41:39.719  1366  1386 D BluetoothPan: onBluetoothStateChange on: false
,08-29 16:41:39.719  4054  4054 D BluetoothPbap: Proxy object disconnected
,08-29 16:41:39.719  4054  4054 D PbapServerProfile: Bluetooth service disconnected
08-29 16:41:39.719  1366  2074 D BluetoothMap: onBluetoothStateChange: up=false
08-29 16:41:39.720  4054  4067 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 16:41:39.721  4054  4065 D BluetoothPan: onBluetoothStateChange on: false
08-29 16:41:39.722  1366  1380 D BluetoothA2dp: onBluetoothStateChange: up=false,
08-29 16:41:39.722   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:39.722   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:39.723  4054  4067 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 16:41:39.723   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 16:41:39.723  1965  1977 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:39.724  4054  4065 D BluetoothMap: onBluetoothStateChange: up=false
08-29 16:41:39.724  4054  4067 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 16:41:39.725  1366  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:41:39.726  1366  2074 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 16:41:39.726   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 16:41:39.727  4186  4198 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-29 16:41:39.727  4186  4198 D BluetoothAdapterProperties: Setting state to 16
,08-29 16:41:39.727  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 16:41:39.728  4186  4198 D BluetoothAdapterProperties: onBleDisable
,08-29 16:41:39.728  4186  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:41:39.728  4186  4199 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 16:41:39.729  4186  4202 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:41:39.729  4186  4211 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 16:41:39.729  4186  4211 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:41:39.730  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:39.731  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.734  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.735  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:39.735  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 16:41:39.737  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.738  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:39.741  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 16:41:39.747  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:41:39.932  4186  4202 I bt_hci  : shut_down
,08-29 16:41:39.948  4186  4206 D bt_hwcfg: hw_epilog_process
,08-29 16:41:39.948  4186  4206 I bt_vendor: low_power_mode_cb
,08-29 16:41:39.966  4186  4206 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 16:41:39.966  4186  4206 I bt_vendor: epilog_cb
08-29 16:41:39.967  4186  4206 I bt_hci  : epilog_finished_callback
,08-29 16:41:39.976  4186  4202 I bt_hci_h4: hal_close
,08-29 16:41:39.978  4186  4202 I bt_userial_vendor: device fd = 51 close
,08-29 16:41:40.106  4186  4199 D bt_stack_manager: event_shut_down_stack finished.
,08-29 16:41:40.107  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 16:41:40.115  4186  4198 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 16:41:40.115  4186  4186 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 16:41:40.117  4186  4186 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 16:41:40.117  4186  4186 D BtGatt.GattService: stop()
08-29 16:41:40.118  4186  4186 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 16:41:40.124  4186  4186 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:41:40.125  4186  4186 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:41:40.125  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:40.125  4186  4186 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 16:41:40.126  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 16:41:40.127  4186  4198 D BluetoothAdapterProperties: Setting state to 10
08-29 16:41:40.127  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 16:41:40.129  4186  4198 I BluetoothAdapterState: Entering OffState
08-29 16:41:40.131   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 16:41:40.163  4186  4186 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 16:41:40.164  4186  4186 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 16:41:40.166  4186  4199 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 16:41:40.166  4186  4186 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 16:41:40.169  4186  4199 D bt_stack_manager: event_clean_up_stack finished.
08-29 16:41:40.170  4186  4186 I art     : System.exit called, status: 0
08-29 16:41:40.171  4186  4186 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 16:41:40.236   873   883 I ActivityManager: Process com.android.bluetooth (pid 4186) has died
,08-29 16:41:44.642  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:41:44.642  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:44.648  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:44.648  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83d4ce6 removed from the list
08-29 16:41:44.649  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:44.649  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:44.649  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:44.656  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:41:44.656  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@acefcd4 added. We now have 4 listener(s)
,08-29 16:41:44.656  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:41:44.659  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:44.659  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@acefcd4 removed from the list
08-29 16:41:44.659  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:44.660  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:44.660  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:44.663  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:41:44.664  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b226e7d added. We now have 4 listener(s)
,08-29 16:41:44.664  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:41:49.676  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:49.723   873   890 I ActivityManager: Start proc 4249:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 16:41:49.873  4249  4249 D AdapterServiceConfig: Adding HeadsetService
,08-29 16:41:49.874  4249  4249 D AdapterServiceConfig: Adding A2dpService
08-29 16:41:49.875  4249  4249 D AdapterServiceConfig: Adding HidService
08-29 16:41:49.875  4249  4249 D AdapterServiceConfig: Adding HealthService
,08-29 16:41:49.876  4249  4249 D AdapterServiceConfig: Adding PanService
08-29 16:41:49.877  4249  4249 D AdapterServiceConfig: Adding GattService
08-29 16:41:49.878  4249  4249 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 16:41:49.895  4249  4249 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 16:41:49.895   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67eeafc:true
,08-29 16:41:49.900  4249  4249 I bt_bluedroid: init
,08-29 16:41:49.902  4249  4261 I BluetoothAdapterState: Entering OffState
,08-29 16:41:49.908  4249  4262 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 16:41:49.909  4249  4262 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 16:41:49.909  4249  4262 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 16:41:49.909  4249  4262 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 16:41:49.911  4249  4249 I bt_bluedroid: get_profile_interface socket
,08-29 16:41:49.914  4249  4249 I bt_bluedroid: get_profile_interface sdp
,08-29 16:41:49.917  4249  4265 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 16:41:49.918  4249  4260 I bt_bluedroid: config_hci_snoop_log
,08-29 16:41:49.920  4249  4265 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 16:41:49.922   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 16:41:49.933  4249  4261 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 16:41:49.934  4249  4261 D BluetoothAdapterProperties: Setting state to 14
,08-29 16:41:49.934  4249  4261 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 16:41:49.939  4249  4261 D BluetoothBondStateMachine: make
,08-29 16:41:49.943  4249  4266 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 16:41:49.953  4249  4261 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:41:49.956  4249  4249 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 16:41:49.964  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:49.965  4249  4249 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 16:41:49.966  4249  4249 D BtGatt.GattService: Received start request. Starting profile...
08-29 16:41:49.967  4249  4249 D BtGatt.GattService: start()
,08-29 16:41:49.967  4249  4249 I bt_bluedroid: get_profile_interface gatt
08-29 16:41:49.968  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:49.968  4249  4249 D BtGatt.AdvertiseManager: advertise manager created
,08-29 16:41:49.978  4249  4249 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:41:49.978  4249  4249 V BluetoothAdapterState: isTurningOn()=false
08-29 16:41:49.978  4249  4249 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 16:41:49.978  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:49.979  4249  4261 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 16:41:49.980  4249  4261 I bt_bluedroid: enable
,08-29 16:41:49.980  4249  4262 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 16:41:49.981  4249  4262 I bt_hci  : start_up
,08-29 16:41:50.002  4249  4262 I bt_vendor: alloc value 0xb3a49189
,08-29 16:41:50.003  4249  4262 I bt_vendor: init
,08-29 16:41:50.003  4249  4262 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 16:41:50.004  4249  4262 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 16:41:50.114  4249  4262 D bt_hci  : start_up starting async portion
,08-29 16:41:50.115  4249  4269 I bt_hci  : event_finish_startup
,08-29 16:41:50.115  4249  4269 I bt_hci_h4: hal_open
,08-29 16:41:50.116  4249  4269 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 16:41:50.124  4249  4269 I bt_userial_vendor: device fd = 51 open
,08-29 16:41:50.155  4249  4269 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:41:50.187  4249  4269 D bt_hwcfg: Chipset BCM4354A2
,08-29 16:41:50.187  4249  4269 D bt_hwcfg: Target name = [BCM4354A2]
08-29 16:41:50.188  4249  4269 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 16:41:50.841  4249  4269 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 16:41:50.843  4249  4269 D bt_hwcfg: Settlement delay -- 100 ms
08-29 16:41:50.843  4249  4269 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 16:41:50.960  4249  4269 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:41:50.961  4249  4269 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 16:41:50.991  4249  4269 I bt_hwcfg: vendor lib fwcfg completed
,08-29 16:41:50.991  4249  4269 I bt_vendor: firmware callback
08-29 16:41:50.991  4249  4269 I bt_hci  : firmware_config_callback
,08-29 16:41:51.002  4249  4271 I bt_btu  : btu_task pending for preload complete event
,08-29 16:41:51.002  4249  4271 I bt_btu_task: Bluetooth chip preload is complete
,08-29 16:41:51.003  4249  4271 I bt_btu  : btu_task received preload complete event
,08-29 16:41:51.013  4249  4271 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 16:41:51.013  4249  4271 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 16:41:51.013  4249  4271 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 16:41:51.013  4249  4271 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 16:41:51.014  4249  4271 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 16:41:51.014  4249  4271 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 16:41:51.014  4249  4271 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 16:41:51.015  4249  4271 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 16:41:51.015  4249  4271 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 16:41:51.015  4249  4271 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 16:41:51.015  4249  4271 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 16:41:51.016  4249  4271 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 16:41:51.016  4249  4271 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 16:41:51.016  4249  4271 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 16:41:51.016  4249  4271 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 16:41:51.149  4249  4271 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c6d9d
,08-29 16:41:51.150  4249  4271 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c6d9d 
,08-29 16:41:51.161  4249  4265 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 16:41:51.163  4249  4265 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 16:41:51.164  4249  4265 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 16:41:51.167  4249  4265 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:41:51.170  4249  4265 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:41:51.172  4249  4265 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 16:41:51.175  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:51.177  4249  4265 D bt_hci  : do_postload posting postload work item
,08-29 16:41:51.177  4249  4269 I bt_hci  : event_postload
,08-29 16:41:51.177  4249  4269 I bt_vendor: sco_config_cb
,08-29 16:41:51.177  4249  4269 I bt_hci  : sco_config_callback postload finished.
08-29 16:41:51.179  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:51.181  4249  4265 D bt_bte_conf: Device ID record 1 : primary
08-29 16:41:51.181  4249  4265 D bt_bte_conf:   vendorId            = 000f
08-29 16:41:51.181  4249  4265 D bt_bte_conf:   vendorIdSource      = 0001
08-29 16:41:51.181  4249  4265 D bt_bte_conf:   product             = 1200
08-29 16:41:51.181  4249  4265 D bt_bte_conf:   version             = 1436
,08-29 16:41:51.182  4249  4265 D bt_bte_conf:   clientExecutableURL = 
,08-29 16:41:51.182  4249  4265 D bt_bte_conf:   serviceDescription  = 
08-29 16:41:51.182  4249  4265 D bt_bte_conf:   documentationURL    = 
08-29 16:41:51.182  4249  4265 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 16:41:51.183  4249  4262 D bt_stack_manager: event_start_up_stack finished
08-29 16:41:51.184  4249  4269 I bt_vendor: low_power_mode_cb
08-29 16:41:51.185  4249  4261 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 16:41:51.185  4249  4261 D BluetoothAdapterProperties: Setting state to 15
08-29 16:41:51.186  4249  4261 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 16:41:51.187  4249  4261 I BluetoothAdapterState: Entering BleOnState
,08-29 16:41:51.194  4249  4261 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 16:41:51.194  4249  4261 D BluetoothAdapterProperties: Setting state to 11
08-29 16:41:51.194  4249  4261 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 16:41:51.201  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:51.203  4249  4249 D HeadsetService: Received start request. Starting profile...,
,08-29 16:41:51.207  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:51.207  4249  4249 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 16:41:51.208  4249  4249 D HeadsetStateMachine: make
08-29 16:41:51.209  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:51.219  4249  4249 D HeadsetStateMachine: max_hf_connections = 1
,08-29 16:41:51.219  4249  4249 I bt_bluedroid: get_profile_interface handsfree
08-29 16:41:51.219  4249  4265 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 16:41:51.219  4249  4265 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 16:41:51.222  4249  4261 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:41:51.224  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:51.224  4249  4249 D A2dpService: Received start request. Starting profile...
,08-29 16:41:51.225  4249  4249 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 16:41:51.225  4249  4249 I bt_bluedroid: get_profile_interface avrcp
,08-29 16:41:51.231  4249  4249 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 16:41:51.232  4249  4249 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 16:41:51.232  4249  4249 D A2dpStateMachine: make
,08-29 16:41:51.233  4249  4249 I bt_bluedroid: get_profile_interface a2dp
08-29 16:41:51.233  4249  4265 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 16:41:51.237  4249  4249 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 16:41:51.235  4249  4280 D A2dpStateMachine: Enter Disconnected: -2
,08-29 16:41:51.242  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:51.243  4249  4249 D HidService: Received start request. Starting profile...
08-29 16:41:51.243  4249  4249 I bt_bluedroid: get_profile_interface hidhost
,08-29 16:41:51.243  4249  4265 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a83e5
08-29 16:41:51.243  4249  4265 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 16:41:51.243  4249  4249 D HidService: setHidService(): set to: null
,08-29 16:41:51.244  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:51.246  4249  4249 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 16:41:51.248  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:51.248  4249  4249 D HealthService: Received start request. Starting profile...
,08-29 16:41:51.250  4249  4249 I bt_bluedroid: get_profile_interface health
08-29 16:41:51.250  4249  4249 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 16:41:51.251  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:51.252  4249  4249 D PanService: Received start request. Starting profile...
08-29 16:41:51.252  4249  4249 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 16:41:51.252  4249  4249 I bt_bluedroid: get_profile_interface pan
08-29 16:41:51.253  4249  4265 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 16:41:51.256  4249  4249 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:41:51.256  4249  4249 D BluetoothMapService: Received start request. Starting profile...
08-29 16:41:51.256  4249  4249 D BluetoothMapService: start()
,08-29 16:41:51.260  4249  4249 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 16:41:51.260  4249  4249 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 16:41:51.260  4249  4249 D BluetoothMapAppObserver: createReceiver()
,08-29 16:41:51.262  4249  4249 D BluetoothMapAppObserver: initObservers()
08-29 16:41:51.262  4249  4249 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 16:41:51.273  4249  4249 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:41:51.273  4249  4249 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:51.273  4249  4249 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:51.273  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:51.275  4249  4278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:41:51.275  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isTurningOn()=true
,08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:51.277  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:41:51.278  4249  4249 V BluetoothAdapterState: isTurningOff()=false
08-29 16:41:51.278  4249  4249 V BluetoothAdapterState: isTurningOn()=true
08-29 16:41:51.278  4249  4249 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:41:51.278  4249  4249 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:41:51.278  4249  4261 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 16:41:51.278  4249  4261 D BluetoothAdapterProperties: ScanMode =  20
08-29 16:41:51.278  4249  4261 D BluetoothAdapterProperties: State =  11
08-29 16:41:51.278  4249  4261 D BluetoothAdapterProperties: Setting state to 12
08-29 16:41:51.278  4249  4261 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 16:41:51.279  4249  4261 I BluetoothAdapterState: Entering OnState
08-29 16:41:51.279  1366  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 16:41:51.280  4249  4265 D BluetoothAdapterProperties: Scan Mode:21
,08-29 16:41:51.280  4249  4265 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 16:41:51.282  4054  4067 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 16:41:51.283  1366  1366 D BluetoothInputDevice: Proxy object connected
08-29 16:41:51.283  1366  1366 D HidProfile: Bluetooth service connected
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:51.283  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:51.285  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:51.285  1366  1380 D BluetoothPan: onBluetoothStateChange on: true
,08-29 16:41:51.288  1366  1386 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:51.288  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:41:51.288  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 16:41:51.288  1366  1366 D PanProfile: Bluetooth service connected
,08-29 16:41:51.290  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:41:51.290  4054  4240 D BluetoothHeadset: onBluetoothStateChange: up=true,
08-29 16:41:51.291  1366  1366 D BluetoothMap: Proxy object connected
08-29 16:41:51.291  1366  1366 D MapProfile: Bluetooth service connected
08-29 16:41:51.291  1366  1366 D BluetoothMap: getConnectedDevices()
08-29 16:41:51.291  4054  4065 D BluetoothPan: onBluetoothStateChange on: true
,08-29 16:41:51.293  1366  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 16:41:51.294  4249  4249 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:41:51.294  4249  4249 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 16:41:51.296  4054  4054 D BluetoothInputDevice: Proxy object connected
,08-29 16:41:51.296  4249  4249 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:51.296   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 16:41:51.296   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:51.296  4054  4240 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 16:41:51.298  4249  4249 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:41:51.296  4054  4054 D HidProfile: Bluetooth service connected
08-29 16:41:51.298   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 16:41:51.299  4249  4249 D ObexServerSockets: Succeed to create listening sockets 
,08-29 16:41:51.299  4249  4249 D ObexServerSockets0: startAccept()
08-29 16:41:51.299  4249  4249 D ObexServerSockets0: prepareForNewConnect()
,08-29 16:41:51.299  1965  2098 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:51.300  4054  4067 D BluetoothMap: onBluetoothStateChange: up=true
08-29 16:41:51.300  4054  4054 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 16:41:51.300  4054  4054 D PanProfile: Bluetooth service connected
08-29 16:41:51.300  4249  4249 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 16:41:51.300  4249  4249 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 16:41:51.301   873   873 D BluetoothA2dp: Proxy object connected
08-29 16:41:51.301  4249  4286 D ObexServerSockets0: Accepting socket connection...
,08-29 16:41:51.301  4054  4067 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:41:51.302  1366  1366 D BluetoothA2dp: Proxy object connected
08-29 16:41:51.302  4249  4287 D ObexServerSockets0: Accepting socket connection...
08-29 16:41:51.303  1366  2074 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:41:51.303  4054  4054 D BluetoothMap: Proxy object connected
,08-29 16:41:51.303  4054  4054 D MapProfile: Bluetooth service connected
08-29 16:41:51.303  4054  4054 D BluetoothMap: getConnectedDevices()
08-29 16:41:51.304  1366  1380 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:41:51.304  4054  4054 D BluetoothA2dp: Proxy object connected
,08-29 16:41:51.305   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 16:41:51.306   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 16:41:51.307  4249  4249 D BluetoothMapService: onReceive
08-29 16:41:51.307  4249  4249 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 16:41:51.307  4249  4249 D BluetoothMapService: STATE_ON
08-29 16:41:51.309  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:41:51.311  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:51.314  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:41:51.319  1556  1556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:41:51.322  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:41:51.326  4054  4054 D BluetoothPbap: Proxy object connected
,08-29 16:41:51.326  4054  4054 D PbapServerProfile: Bluetooth service connected
08-29 16:41:51.326  4249  4290 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:51.331  1366  1366 D BluetoothPbap: Proxy object connected
,08-29 16:41:51.331  1366  1366 D PbapServerProfile: Bluetooth service connected
08-29 16:41:51.332  4249  4249 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:41:51.332  4249  4249 D ObexServerSockets0: prepareForNewConnect()
,08-29 16:41:51.354  4249  4296 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:41:51.356  4249  4296 I BtOppRfcommListener: Accept thread started.
,08-29 16:41:51.393  1965  1980 D BluetoothHeadset: Proxy object connected
,08-29 16:41:51.393  4054  4067 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.394   873   873 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.394   873   873 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.394  4054  4054 D HeadsetProfile: Bluetooth service connected
08-29 16:41:51.394  1366  1386 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.394  1366  1366 D HeadsetProfile: Bluetooth service connected
08-29 16:41:51.394   873   873 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.396   873   890 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.396   873   890 D BluetoothHeadset: Proxy object connected
,08-29 16:41:51.400  1965  1977 D BluetoothHeadset: Proxy object connected
,08-29 16:41:51.404  1366  2074 D BluetoothHeadset: Proxy object connected
08-29 16:41:51.404  1366  1366 D HeadsetProfile: Bluetooth service connected
08-29 16:41:51.405   873   890 D BluetoothHeadset: Proxy object connected
,08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:54.700  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:54.707  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:54.708  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:41:54.708  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b226e7d removed from the list
,08-29 16:41:54.709  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:41:54.709  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:41:54.709  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:41:54.712  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:41:54.712  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d015172 added. We now have 4 listener(s)
,08-29 16:41:54.713  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:41:54.718   873  2018 D WifiService: setWifiEnabled: false pid=3797, uid=10000
08-29 16:41:54.719   873  2018 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:41:59.683  1869  1939 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-29 16:41:59.683  1869  1939 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-29 16:41:59.732  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:41:59.733   873  1378 D WifiService: setWifiEnabled: true pid=3797, uid=10000
,08-29 16:41:59.733   873  1378 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:41:59.735  1556  1556 I ConfigService: onCreate
,08-29 16:41:59.746   873  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:59.759  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:59.765  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:41:59.771  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:41:59.773  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:41:59.784   873  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-29 16:41:59.785   873  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 16:41:59.785   873  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 16:41:59.786   873  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 16:41:59.786   873  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 16:41:59.787   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 16:41:59.787   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 16:41:59.801   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:41:59.802   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 16:41:59.804   371   871 D CommandListener: Setting iface cfg
,08-29 16:41:59.855   873  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '179 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 179 Failed to set address (No such device)'
,08-29 16:41:59.855   873  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 16:41:59.862   873  1311 E native  : do suspend true
,08-29 16:41:59.881   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:41:59.882   873  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 16:41:59.888   873  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 16:42:01.252   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:42:01.404   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.38 rxSuccessRate=8.69 delta 1000 -> 994
08-29 16:42:01.406   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 16:42:01.406   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:42:01.421   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 16:42:01.495   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 16:42:01.497  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 16:42:01.939  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 16:42:01.986  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 16:42:01.988  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 16:42:01.990   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:42:02.004   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 16:42:02.004   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:42:02.005   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 16:42:02.029   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:42:02.052   371   871 D CommandListener: Setting iface cfg
,08-29 16:42:02.053   873  1311 D WifiStateMachine: Start Dhcp Watchdog 4
,08-29 16:42:02.068   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 16:42:02.083   873  4307 D DhcpClient: Receive thread started
,08-29 16:42:02.183   873  1311 E native  : do suspend false
,08-29 16:42:02.210   873  1842 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 16:42:02.228   873  4307 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-29 16:42:02.229   873  1842 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-29 16:42:02.233   873  1842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 16:42:02.293   873  4307 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 16:42:02.294   873  1842 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 16:42:02.299   371   871 D CommandListener: Setting iface cfg
,08-29 16:42:02.314   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 16:42:02.319   873  1842 D DhcpClient: Scheduling renewal in 86399s
,08-29 16:42:02.320   873  1311 E native  : do suspend true
,08-29 16:42:02.351   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 16:42:02.355   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 16:42:02.356   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 16:42:02.361   873  1314 D ConnectivityService: Adding iface wlan0 to network 103
08-29 16:42:02.372   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 16:42:02.427   873  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 16:42:02.427   873  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,08-29 16:42:02.430   873  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,08-29 16:42:02.432   873  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,08-29 16:42:02.434   873  1314 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,08-29 16:42:02.456   873  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-29 16:42:02.466   873  1314 D ConnectivityService: scheduleUnvalidatedPrompt 103
,08-29 16:42:02.466   873  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
08-29 16:42:02.466   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 16:42:02.468   873  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
,08-29 16:42:02.468   873  1314 D ConnectivityService:    accepting network in place of null
08-29 16:42:02.468   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:42:02.469   873  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:42:02.501   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:42:02.532   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:42:02.541   873  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,08-29 16:42:02.541   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 16:42:02.549   873  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
,08-29 16:42:02.549   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:02.566  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:02.572  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:02.580  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:02.582  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:02.583  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:42:02.586  1738  1738 D SystemUpdateService: onCreate
,08-29 16:42:02.590  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:42:02.605  1738  4316 I SystemUpdateService: active receiver: enabled
,08-29 16:42:02.610  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 16:42:02.616  1738  2342 I iu.UploadsManager: num queued entries: 0
,08-29 16:42:02.618  1738  4316 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:42:02.620  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:42:02.621  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:42:02.623  3897  3897 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:42:02.627  1738  4318 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 16:42:02.627  1738  4318 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 16:42:02.629  3897  3897 D SprintDMHelper: simOperator: 
08-29 16:42:02.629  3897  3897 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 16:42:02.631  1738  4318 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:42:02.616  1738  2342 I iu.UploadsManager: num updated entries: 0
,08-29 16:42:02.634  1738  2342 I iu.SyncManager: NEXT; no task
,08-29 16:42:02.635  1738  4316 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 16:42:02.635  1738  4316 I SystemUpdateService: now status is 0 (complete)
,08-29 16:42:02.635  1738  4316 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:42:02.636  1738  4316 I SystemUpdateService: file has been verified
08-29 16:42:02.636  1738  4316 I SystemUpdateService: OTA package size = 12249756
,08-29 16:42:02.645  1738  4316 I SystemUpdateService: showing system update notification
,08-29 16:42:02.652  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:42:02.656  1556  1556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:42:02.681  3748  4322 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:42:02.787  1738  1738 D SystemUpdateService: onDestroy
,08-29 16:42:02.796  1556  2107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 16:42:02.796  1556  2107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 16:42:02.796  1556  2107 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:42:02.796  1556  2107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:42:02.798   873  4306 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213487, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 16:42:02.825  3748  4327 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:42:02.831  1738  4318 E MDM     : [187] SitrepService.a: Error sending sitrep.
,08-29 16:42:02.874  1556  1574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:42:02.874  1556  1574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:42:02.874  1556  1574 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:42:02.874  1556  1574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:42:02.881  3006  4323 V KeepSync: Connecting to GoogleApiClient
,08-29 16:42:02.881   873  1378 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:42:02.893   873  4305 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:812::200e
,08-29 16:42:02.959  3863  4321 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 16:42:02.968  1556  3164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:42:02.968  1556  3164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:42:02.968  1556  3164 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:42:02.968  1556  3164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:42:02.996  3748  4327 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 16:42:02.997  3748  4322 E BooksSync: Soft error
08-29 16:42:02.997  3748  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:42:02.997  3748  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:42:02.997  3748  4322 E BooksSync: Sync error
08-29 16:42:02.997  3748  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:42:02.997  3748  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 16:42:02.997  3748  4322 I BooksSync: Finished books sync
,08-29 16:42:03.005   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199220, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:42:03.012   873  4305 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:42:02 GMT], X-Android-Received-Millis=[1472481723011], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472481722968]}
,08-29 16:42:03.014   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 16:42:03.015   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
,08-29 16:42:03.015   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-29 16:42:03.019   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 16:42:03.054  1556  2887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 16:42:03.054  1556  2887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 16:42:03.054  1556  2887 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:42:03.054  1556  2887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:42:03.067  1738  4329 V BaseAuthAsyncOperation: access token request failed
,08-29 16:42:03.068  3006  4323 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:42:03.100  4113  4332 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:42:03.139  1556  2887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 16:42:03.139  1556  2887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-29 16:42:03.139  1556  2887 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:42:03.139  1556  2887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:42:03.171  4113  4332 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 16:42:03.172  4113  4332 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 16:42:03.186  1556  3164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 16:42:03.186  1556  3164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 16:42:03.186  1556  3164 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:42:03.186  1556  3164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:42:03.243  3006  4323 E KeepSync: IOException
08-29 16:42:03.243  3006  4323 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:42:03.243  3006  4323 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:42:03.243  3006  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:42:03.243  3006  4323 E KeepSync: 	... 10 more
08-29 16:42:03.243  3006  4323 W KeepSync: Sync result 2
,08-29 16:42:03.254   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 199661, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:42:03.540   873  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:04.759  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:04.767  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:04.769  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:42:04.769  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d015172 removed from the list
,08-29 16:42:04.769  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:42:04.770  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:04.770  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:04.782  3797  4333 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-29 16:42:04.783  3797  4333 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 16:42:04.855  1556  1556 I ConfigService: onDestroy
,08-29 16:42:07.789  3797  4336 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-29 16:42:07.790  3797  4333 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-29 16:42:07.791  3797  4336 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-29 16:42:07.792  3797  4333 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 16:42:07.793  3797  4333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:42:07.793  3797  4336 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:42:07.794  3797  4336 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:42:07.795  3797  4333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:42:07.796  3797  4336 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 16:42:07.796  3797  4333 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 16:42:07.808  3797  4339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Sender)
,08-29 16:42:07.808  3797  4338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
,08-29 16:42:07.808  3797  4340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
08-29 16:42:07.809  3797  4341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Receiver)
,08-29 16:42:07.811  3797  4341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: OutgoingSocketThread/Receiver)
,08-29 16:42:07.811  3797  4340 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
08-29 16:42:07.811  3797  4341 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 16:42:07.811  3797  4340 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 16:42:07.812  3797  4341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 16:42:07.812  3797  4340 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 16:42:10.474   873  1314 D ConnectivityService: handlePromptUnvalidated 103
,08-29 16:42:10.789  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 16:42:10.792  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 16:42:10.799  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1f4ba13 Bundle[{}]
,08-29 16:42:10.800  3797  3848 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 16:42:10.800  3797  3848 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 16:42:10.801  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 16:42:10.801  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 16:42:10.802  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 16:42:10.802  3797  3848 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 16:42:10.807  3797  3848 I System.out: Running OutgoingSocketThread
,08-29 16:42:10.810  3797  4342 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-29 16:42:10.810  3797  4342 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 16:42:13.819  3797  4343 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-29 16:42:13.819  3797  4343 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 16:42:13.820  3797  4343 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:42:13.821  3797  4342 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-29 16:42:13.821  3797  4342 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-29 16:42:13.822  3797  4342 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:42:13.822  3797  4343 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:42:13.823  3797  4342 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:42:13.826  3797  4343 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 16:42:13.828  3797  4345 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Sender)
08-29 16:42:13.829  3797  4342 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 16:42:13.833  3797  4346 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Sender)
,08-29 16:42:13.836  3797  4347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: IncomingSocketThread/Receiver)
08-29 16:42:13.837  3797  4347 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: IncomingSocketThread/Receiver)
08-29 16:42:13.838  3797  4348 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: OutgoingSocketThread/Receiver)
08-29 16:42:13.838  3797  4347 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 16:42:13.838  3797  4347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 16:42:13.840  3797  4348 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: OutgoingSocketThread/Receiver)
,08-29 16:42:13.840  3797  4348 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 16:42:13.840  3797  4348 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 16:42:16.822  3797  3848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,08-29 16:42:16.824  3797  3848 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 16:42:16.825  3797  3848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,08-29 16:42:16.831  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:42:16.831  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c99c3 added. We now have 3 listener(s)
,08-29 16:42:16.833  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:42:16.833  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 16:42:16.833  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:42:16.833  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:42:16.833  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2891240 added. We now have 4 listener(s)
08-29 16:42:16.833  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:42:16.834  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:42:16.838  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:16.852  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:16.859  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:16.859  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:42:16.861  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:42:16.862  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:42:16.863  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:42:16.863  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:16.863  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:16.863  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:42:16.863  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:42:16.863  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c99c3 removed from the list
08-29 16:42:16.864  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:16.864  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2891240 removed from the list
08-29 16:42:16.865  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:16.874  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:16.874  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:42:16.875  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:16.875  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:16.876  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:16.879  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:42:16.879  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:42:16.879  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:16.879  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2891240 not in the list
08-29 16:42:16.880  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:16.880  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:16.884  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:42:16.884  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:42:16.885  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:16.885  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2891240 not in the list
08-29 16:42:16.886  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:16.886  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:16.886  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:16.886  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c99c3 not in the list
08-29 16:42:16.889  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 16:42:16.889  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8f12be added. We now have 3 listener(s)
,08-29 16:42:16.895  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:42:16.896  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:42:16.896  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:42:16.896  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:42:16.897  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4950f1f added. We now have 4 listener(s)
08-29 16:42:16.897  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:42:16.898  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:42:16.906  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:16.917  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:16.922  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:16.923  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:42:16.923  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:42:16.924  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:42:16.924  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:42:16.924  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:42:16.925  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:42:16.926  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:16.929  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:16.932  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:42:16.933  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:42:16.943  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:42:16.944  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:42:16.944  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:42:16.950  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 16:42:16.950  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:42:16.951  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 16:42:16.952  3797  3848 D BluetoothAdapter: STATE_ON
,08-29 16:42:16.955  4249  4288 D BtGatt.GattService: registerClient() - UUID=4a33b455-d671-42c0-8619-7c582670882e
,08-29 16:42:16.957  4249  4265 D BtGatt.GattService: onClientRegistered() - UUID=4a33b455-d671-42c0-8619-7c582670882e, clientIf=5
,08-29 16:42:16.958  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 16:42:16.960  4249  4259 D BtGatt.GattService: start scan with filters
,08-29 16:42:16.966  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 16:42:16.966  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 16:42:16.966  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 16:42:16.966  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 16:42:16.967  4249  4268 D BtGatt.ScanManager: handling starting scan
,08-29 16:42:16.969  4249  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@50bbd77
,08-29 16:42:16.975  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:42:16.976  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:42:16.976  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:42:16.981  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:42:16.987  4249  4265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 16:42:16.987  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-29 16:42:16.988  4249  4268 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:42:16.990  3797  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 16:42:16.991  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 16:42:16.991  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 16:42:16.991  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:16.992  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:42:16.992  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:42:16.992  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:42:16.992  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:42:16.992  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:42:16.993  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:42:16.993  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 16:42:16.995  3797  3848 D BluetoothAdapter: STATE_ON
08-29 16:42:16.996  4249  4259 D BtGatt.GattService: stopScan() - queue size =1
08-29 16:42:16.997  4249  4277 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 16:42:16.998  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 16:42:16.998  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:42:16.998  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 16:42:16.998  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 16:42:16.998  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 16:42:17.000  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:42:17.000  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:42:17.000  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:42:17.000  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:42:17.001  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:42:17.002  4249  4265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 16:42:17.002  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:42:17.003  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:42:17.003  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:42:17.003  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:42:17.003  4249  4268 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:42:17.003  4249  4268 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 16:42:17.018  4249  4265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 16:42:17.018  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:17.027  4249  4265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 16:42:17.027  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:17.039  4249  4265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 16:42:17.039  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 16:42:17.040  4249  4268 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:42:17.051  4249  4265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 16:42:17.051  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:42:17.052  4249  4268 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:42:17.064  4249  4265 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 16:42:17.064  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:17.504  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:42:17.505  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:42:17.505  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:42:20.003  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:42:20.004  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:42:20.004  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:42:20.005  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:42:20.005  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:20.006  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:42:20.006  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:42:20.006  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8f12be removed from the list
08-29 16:42:20.007  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:42:20.007  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4950f1f removed from the list
08-29 16:42:20.007  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:42:20.008  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:20.009  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:20.010  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:20.013  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:42:20.013  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:42:20.013  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:42:20.014  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4950f1f not in the list
08-29 16:42:20.014  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:20.015  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 16:42:20.018  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:42:20.018  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:42:20.019  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:20.019  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4950f1f not in the list
08-29 16:42:20.019  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:20.019  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:20.020  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:20.020  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8f12be not in the list
08-29 16:42:20.023  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:42:20.023  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8eee958 added. We now have 3 listener(s)
,08-29 16:42:20.028  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:42:20.028  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:42:20.028  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:42:20.029  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:42:20.029  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae25ab1 added. We now have 4 listener(s)
08-29 16:42:20.029  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:42:20.030  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:42:20.035  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:20.044  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:20.049  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:20.049  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:42:20.049  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:42:20.051  3797  3848 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3,
,08-29 16:42:20.051  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-29 16:42:20.052  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:42:20.052  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-29 16:42:20.052  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 16:42:20.052  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:42:20.054  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 16:42:20.055  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:42:20.056  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 16:42:20.057  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 16:42:20.057  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:42:20.057  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-29 16:42:20.058  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:20.058  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:42:20.059  3797  4349 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:42:20.066  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 16:42:20.066  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 16:42:20.067  3797  4349 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 16:42:20.069  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:42:20.069  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:42:20.079  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:42:20.080  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:42:20.080  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:42:20.084  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 16:42:20.084  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:42:20.084  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-29 16:42:20.085  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-29 16:42:20.085  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:42:20.085  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 16:42:20.086  3797  3848 D BluetoothAdapter: STATE_ON
,08-29 16:42:20.092  4249  4288 D BtGatt.GattService: registerClient() - UUID=35708d1a-340c-4a0b-90c0-f4156b985d5a
,08-29 16:42:20.093  4249  4265 D BtGatt.GattService: onClientRegistered() - UUID=35708d1a-340c-4a0b-90c0-f4156b985d5a, clientIf=5
,08-29 16:42:20.094  3797  3809 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 16:42:20.097  4249  4267 D BtGatt.AdvertiseManager: message : 0
,08-29 16:42:20.103  4249  4267 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 16:42:20.125  4249  4265 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 16:42:20.143  4249  4265 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 16:42:20.145  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 16:42:20.145  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:42:20.149  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:42:20.152  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:42:20.153  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-29 16:42:20.153  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-29 16:42:20.153  3797  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-29 16:42:20.153  3797  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-29 16:42:20.154  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 16:42:20.161  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 16:42:20.162  3797  3797 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:42:20.162  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:42:20.664  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 16:42:20.664  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 16:42:20.665  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:42:23.162  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:42:23.163  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 16:42:23.163  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 16:42:23.164  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 16:42:23.165  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 16:42:23.166  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 16:42:23.168  3797  4349 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 16:42:23.169  3797  4349 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 16:42:23.168  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:42:23.169  3797  4349 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 16:42:23.169  3797  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 16:42:23.169  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:42:23.169  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 16:42:23.170  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:42:23.170  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 16:42:23.170  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:42:23.170  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 16:42:23.171  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:42:23.173  3797  3848 D BluetoothAdapter: STATE_ON
08-29 16:42:23.173  3797  3848 D BluetoothLeScanner: could not find callback wrapper
08-29 16:42:23.174  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:42:23.174  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 16:42:23.177  4249  4267 D BtGatt.AdvertiseManager: message : 1
08-29 16:42:23.178  4249  4267 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 16:42:23.185  4249  4265 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 16:42:23.186  4249  4265 D BtGatt.GattService: Client app is not null!
,08-29 16:42:23.187  4249  4285 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:42:23.189  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:42:23.189  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-29 16:42:23.190  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 16:42:23.191  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-29 16:42:23.191  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 16:42:23.193  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:42:23.193  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:42:23.193  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:42:23.193  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:42:23.196  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:42:23.196  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:42:23.196  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:23.196  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:42:23.197  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:42:23.197  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:42:23.197  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:42:23.197  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8eee958 removed from the list
08-29 16:42:23.197  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:23.198  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae25ab1 removed from the list
08-29 16:42:23.198  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:42:23.198  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:23.199  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:23.200  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:23.202  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:42:23.203  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:42:23.203  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:23.203  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae25ab1 not in the list
08-29 16:42:23.203  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:23.204  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:23.206  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:42:23.206  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:42:23.207  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:42:23.207  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae25ab1 not in the list
08-29 16:42:23.207  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:42:23.207  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:23.208  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:23.208  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8eee958 not in the list
,08-29 16:42:23.210  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 16:42:23.210  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36cfb22 added. We now have 3 listener(s)
,08-29 16:42:23.216  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:42:23.216  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:42:23.216  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 16:42:23.217  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:42:23.217  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83779b3 added. We now have 4 listener(s)
,08-29 16:42:23.218  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:42:23.219  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:42:23.224  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:23.232  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:23.235  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:23.235  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:42:23.236  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:42:23.236  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 16:42:23.236  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 16:42:23.236  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:23.236  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:42:23.241  3797  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 16:42:23.242  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:42:23.242  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:23.248  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:23.248  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:42:23.249  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 16:42:23.250  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:42:23.256  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 16:42:23.256  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:42:23.257  3797  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 16:42:23.258  3797  3848 D BluetoothAdapter: STATE_ON
,08-29 16:42:23.262  4249  4259 D BtGatt.GattService: registerClient() - UUID=65cacb39-ef5c-4891-914e-fa5308eb7844
,08-29 16:42:23.263  4249  4265 D BtGatt.GattService: onClientRegistered() - UUID=65cacb39-ef5c-4891-914e-fa5308eb7844, clientIf=5
08-29 16:42:23.263  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 16:42:23.264  4249  4285 D BtGatt.GattService: start scan with filters
,08-29 16:42:23.269  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 16:42:23.269  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 16:42:23.269  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 16:42:23.270  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:42:23.269  4249  4268 D BtGatt.ScanManager: handling starting scan
,08-29 16:42:23.275  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:42:23.275  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:42:23.275  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:42:23.279  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:42:23.284  4249  4265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 16:42:23.284  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-29 16:42:23.285  4249  4268 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:42:23.298  4249  4265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 16:42:23.298  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:23.299  4249  4268 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:42:23.299  4249  4268 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 16:42:23.326  4249  4265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 16:42:23.326  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:23.339  4249  4265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 16:42:23.339  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:23.698  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:42:23.775  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 16:42:23.776  3797  3797 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 16:42:23.776  3797  3797 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:42:23.782   873  4306 D NetlinkSocketObserver: NeighborEvent{elapsedMs=234470, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:42:24.847  4249  4249 D BtGatt.ScanManager: awakened up at time 235536
,08-29 16:42:24.850  4249  4268 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:42:24.900  4249  4265 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=10
,08-29 16:42:24.900  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:42:24.900  4249  4265 D BtGatt.GattService: current time is 235589804056
,08-29 16:42:24.902  4249  4265 D BtGatt.GattService: Batch record : [100, 22, 120, -125, 84, 94, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96, 0, 53, 33, -121, 80, 73, -44, 1, -128, -106, 29, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -12, -92, -19, 2, 1, -29, 25, 63, -104, -127, 14, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -96, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -52, 11, 57, -70, 107, -17, 1, 0, -104, 3, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, 100, 22, 120, -125, 84, 94, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96, 0]
,08-29 16:42:24.906  4249  4265 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96]
,08-29 16:42:24.908  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -12, -92, -19, 2, 1, -29, 25, 63, -104, -127, 14]
,08-29 16:42:24.909  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 16:42:24.909  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 16:42:24.910  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 16:42:24.911  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 16:42:24.912  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-29 16:42:24.913  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 16:42:24.913  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
08-29 16:42:24.914  4249  4265 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96]
,08-29 16:42:24.917  3797  3797 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 3], added - the peer count is 1
,08-29 16:42:24.919  3797  3797 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 3] updated - the peer count is 1
,08-29 16:42:24.919  3797  3797 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 3], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-29 16:42:26.292  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:42:26.293  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:42:26.293  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 16:42:26.294  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:26.294  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:42:26.294  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 16:42:26.295  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 16:42:26.295  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:42:26.295  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:42:26.296  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:42:26.296  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 16:42:26.298  3797  3848 D BluetoothAdapter: STATE_ON
08-29 16:42:26.300  4249  4259 D BtGatt.GattService: stopScan() - queue size =1
,08-29 16:42:26.308  4249  4285 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:42:26.313  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 16:42:26.313  4249  4249 D BtGatt.ScanManager: awakened up at time 237002
08-29 16:42:26.313  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:42:26.313  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 16:42:26.314  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 16:42:26.314  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 16:42:26.318  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:42:26.318  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:42:26.319  3797  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:42:26.319  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:42:26.321  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:42:26.321  3797  3848 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-29 16:42:26.325  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:42:26.325  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:42:26.326  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:26.326  4249  4265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 16:42:26.326  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.326  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:42:26.326  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:42:26.326  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:42:26.325  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:42:26.327  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36cfb22 removed from the list
08-29 16:42:26.327  4249  4268 D BtGatt.ScanManager: stopping BLe Batch
08-29 16:42:26.327  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:26.327  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83779b3 removed from the list
08-29 16:42:26.328  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:42:26.328  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:26.331  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.331  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:26.334  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:42:26.334  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:42:26.334  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:26.334  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83779b3 not in the list
08-29 16:42:26.334  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.334  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:26.337  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:42:26.337  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:42:26.337  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:26.337  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83779b3 not in the list
08-29 16:42:26.337  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:26.337  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.337  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:42:26.338  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36cfb22 not in the list
08-29 16:42:26.338  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:42:26.339  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@746cc7a added. We now have 3 listener(s)
08-29 16:42:26.340  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:42:26.341  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 16:42:26.341  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:42:26.341  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:42:26.341  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6c2b added. We now have 4 listener(s)
08-29 16:42:26.341  3797  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:42:26.342  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:42:26.344  4249  4265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 16:42:26.344  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:42:26.344  4249  4268 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 16:42:26.348  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:42:26.357  3797  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:42:26.360  3797  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:42:26.361  3797  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:42:26.361  3797  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:42:26.362  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:42:26.362  3797  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:42:26.362  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:26.362  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:42:26.363  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:42:26.363  3797  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:42:26.363  3797  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@746cc7a removed from the list
08-29 16:42:26.363  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:26.363  3797  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6c2b removed from the list
,08-29 16:42:26.365  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:42:26.365  3797  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:42:26.365  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:26.366  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.366  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:26.370  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:42:26.370  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:42:26.370  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:42:26.370  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:26.371  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6c2b not in the list
08-29 16:42:26.371  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.371  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:26.373  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:42:26.373  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:42:26.373  3797  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:42:26.374  3797  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6c2b not in the list
08-29 16:42:26.374  3797  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:42:26.374  3797  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:42:26.374  3797  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:42:26.375  3797  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@746cc7a not in the list
08-29 16:42:26.376  4249  4265 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-29 16:42:26.376  4249  4265 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:42:26.376  4249  4265 D BtGatt.GattService: current time is 237065388890
08-29 16:42:26.376  4249  4265 D BtGatt.GattService: Batch record : [100, 22, 120, -125, 84, 94, 1, -128, -70, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -104, 1, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 35, 97, 126, -92, 22, -56, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 16:42:26.376  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 16:42:26.377  4249  4265 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96]
08-29 16:42:26.377  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 16:42:26.377  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 16:42:26.377  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 16:42:26.377  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
08-29 16:42:26.377  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:42:26.377  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 16:42:26.378  4249  4265 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 16:42:26.378  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-29 16:42:26.378  3797  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:42:26.828  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:42:28.397  3797  4350 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,08-29 16:42:30.395  3797  3848 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 461
,08-29 16:42:30.395  3797  3848 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 461, name: My test thread name)
,08-29 16:42:30.402  3797  4351 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
08-29 16:42:30.403  3797  4351 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: My test thread name)
,08-29 16:42:30.403  3797  4351 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 16:42:30.407  3797  3848 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:42:30.416  3797  4352 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,08-29 16:42:30.417  3797  4352 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 466, thread name: My test thread name): Test exception.
,08-29 16:42:30.417  3797  4352 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 16:42:30.425  3797  3848 I jxcore-log: Total number of executed tests:  82
08-29 16:42:30.425  3797  3848 I jxcore-log: 
,08-29 16:42:30.425  3797  3848 I jxcore-log: Number of passed tests:  82
08-29 16:42:30.425  3797  3848 I jxcore-log: 
08-29 16:42:30.427  3797  3848 I jxcore-log: Number of failed tests:  0
08-29 16:42:30.427  3797  3848 I jxcore-log: 
,08-29 16:42:30.428  3797  3848 I jxcore-log: Number of ignored tests:  0
08-29 16:42:30.428  3797  3848 I jxcore-log: 
,08-29 16:42:30.430  3797  3848 I jxcore-log: Total duration:  106513
08-29 16:42:30.430  3797  3848 I jxcore-log: 
,08-29 16:42:30.434  3797  3848 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 16:42:30.434  3797  3848 I jxcore-log: 
,08-29 16:42:30.456  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.456  3797  3848 I jxcore-log: 
,08-29 16:42:30.461  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.461  3797  3848 I jxcore-log: 
,08-29 16:42:30.462  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.462  3797  3848 I jxcore-log: 
,08-29 16:42:30.464  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.464  3797  3848 I jxcore-log: 
,08-29 16:42:30.465  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.465  3797  3848 I jxcore-log: 
,08-29 16:42:30.466  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.466  3797  3848 I jxcore-log: 
,08-29 16:42:30.468  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 16:42:30.468  3797  3848 I jxcore-log: 
,08-29 16:42:30.470  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.470  3797  3848 I jxcore-log: 
,08-29 16:42:30.471  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.471  3797  3848 I jxcore-log: 
,08-29 16:42:30.472  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.472  3797  3848 I jxcore-log: 
,08-29 16:42:30.473  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:42:30.473  3797  3848 I jxcore-log: 
08-29 16:42:30.474  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.474  3797  3848 I jxcore-log: 
,08-29 16:42:30.475  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 16:42:30.475  3797  3848 I jxcore-log: 
,08-29 16:42:30.476  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.476  3797  3848 I jxcore-log: 
08-29 16:42:30.477  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 16:42:30.477  3797  3848 I jxcore-log: 
,08-29 16:42:30.478  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-29 16:42:30.478  3797  3848 I jxcore-log: 
,08-29 16:42:30.479  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:42:30.479  3797  3848 I jxcore-log: 
,08-29 16:42:30.480  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:42:30.480  3797  3848 I jxcore-log: 
08-29 16:42:30.481  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.481  3797  3848 I jxcore-log: 
,08-29 16:42:30.481  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.481  3797  3848 I jxcore-log: 
,08-29 16:42:30.482  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.482  3797  3848 I jxcore-log: 
08-29 16:42:30.483  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.483  3797  3848 I jxcore-log: 
,08-29 16:42:30.484  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.484  3797  3848 I jxcore-log: 
,08-29 16:42:30.484  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.484  3797  3848 I jxcore-log: 
08-29 16:42:30.485  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.485  3797  3848 I jxcore-log: 
,08-29 16:42:30.486  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.486  3797  3848 I jxcore-log: 
08-29 16:42:30.487  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.487  3797  3848 I jxcore-log: 
,08-29 16:42:30.488  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.488  3797  3848 I jxcore-log: 
,08-29 16:42:30.488  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.488  3797  3848 I jxcore-log: 
08-29 16:42:30.489  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.489  3797  3848 I jxcore-log: 
,08-29 16:42:30.490  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.490  3797  3848 I jxcore-log: 
08-29 16:42:30.491  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.491  3797  3848 I jxcore-log: 
,08-29 16:42:30.491  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.491  3797  3848 I jxcore-log: 
08-29 16:42:30.492  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.492  3797  3848 I jxcore-log: 
,08-29 16:42:30.493  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.493  3797  3848 I jxcore-log: 
08-29 16:42:30.494  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.494  3797  3848 I jxcore-log: 
,08-29 16:42:30.495  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.495  3797  3848 I jxcore-log: 
08-29 16:42:30.496  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.496  3797  3848 I jxcore-log: 
08-29 16:42:30.496  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.496  3797  3848 I jxcore-log: 
,08-29 16:42:30.497  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.497  3797  3848 I jxcore-log: 
,08-29 16:42:30.498  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.498  3797  3848 I jxcore-log: 
08-29 16:42:30.498  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.498  3797  3848 I jxcore-log: 
,08-29 16:42:30.499  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.499  3797  3848 I jxcore-log: 
08-29 16:42:30.499  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.499  3797  3848 I jxcore-log: 
08-29 16:42:30.500  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.500  3797  3848 I jxcore-log: 
08-29 16:42:30.500  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.500  3797  3848 I jxcore-log: 
08-29 16:42:30.501  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.501  3797  3848 I jxcore-log: 
,08-29 16:42:30.502  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:42:30.502  3797  3848 I jxcore-log: 
08-29 16:42:30.502  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.502  3797  3848 I jxcore-log: 
,08-29 16:42:30.503  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:42:30.503  3797  3848 I jxcore-log: 
08-29 16:42:30.503  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.503  3797  3848 I jxcore-log: 
,08-29 16:42:30.504  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.504  3797  3848 I jxcore-log: 
,08-29 16:42:30.505  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.505  3797  3848 I jxcore-log: 
08-29 16:42:30.505  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.505  3797  3848 I jxcore-log: 
,08-29 16:42:30.506  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.506  3797  3848 I jxcore-log: 
,08-29 16:42:30.506  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:42:30.506  3797  3848 I jxcore-log: 
08-29 16:42:30.507  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.507  3797  3848 I jxcore-log: 
,08-29 16:42:30.507  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 16:42:30.507  3797  3848 I jxcore-log: 
08-29 16:42:30.508  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.508  3797  3848 I jxcore-log: 
,08-29 16:42:30.509  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:42:30.509  3797  3848 I jxcore-log: 
08-29 16:42:30.509  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 16:42:30.509  3797  3848 I jxcore-log: 
,08-29 16:42:30.510  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-29 16:42:30.510  3797  3848 I jxcore-log: 
08-29 16:42:30.510  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:42:30.510  3797  3848 I jxcore-log: 
,08-29 16:42:30.511  3797  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:42:30.511  3797  3848 I jxcore-log: 
,08-29 16:42:30.514  3797  3848 I jxcore-log: My device name is: motorola-Nexus 6
08-29 16:42:30.514  3797  3848 I jxcore-log: 
,08-29 16:42:30.579  3797  4350 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-29 16:42:31.091  4353  4353 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 16:42:31.097  4353  4353 D AndroidRuntime: CheckJNI is OFF
,08-29 16:42:31.141  4353  4353 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 16:42:31.187  4353  4353 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 16:42:31.208  4353  4353 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 16:42:31.232   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 16:42:31.232   873   886 I ActivityManager: Killing 3797:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 16:42:31.306   873  2014 D GraphicsStats: Buffer count: 2
,08-29 16:42:31.306   873  1378 I WindowState: WIN DEATH: Window{508709a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 16:42:31.306   873  1313 D WifiService: Client connection lost with reason: 4
,08-29 16:42:31.342   873   896 W PackageSettings: Skipping PackageSetting{bc7b88 com.example.hello/10273} due to missing metadata
,08-29 16:42:31.363   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 16:42:31.364   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 16:42:31.364   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-29 16:42:31.364   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 16:42:31.364   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.364   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.364   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:42:31.364   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 16:42:31.365   873   886 I ActivityManager:   Force finishing activity ActivityRecord{917d373 u0 com.test.thalitest/.MainActivity t2}
08-29 16:42:31.365   873   896 I art     : Starting a blocking GC Explicit
,08-29 16:42:31.380   873  2014 W ActivityManager: Spurious death for ProcessRecord{9463c6a 0:com.test.thalitest/u0a0}, curProc for 3797: null
,08-29 16:42:31.419   873   896 I art     : Explicit concurrent mark sweep GC freed 29561(1869KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 802us total 49.984ms
,08-29 16:42:31.449   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 16:42:31.454  4353  4353 I art     : System.exit called, status: 0
08-29 16:42:31.454  4353  4353 I AndroidRuntime: VM exiting with result code 0.
,08-29 16:42:31.473   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 16:42:31.497   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 16:42:31.516  4249  4249 D BluetoothMapAppObserver: onReceive
,08-29 16:42:31.516  4249  4249 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 16:42:31.517  1869  1869 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 16:42:31.518  2140  2284 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 16:42:31.526   873  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 16:42:31.532  1869  4365 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 16:42:31.538  3638  3638 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 16:42:31.542  1869  4365 I Decoder : createOrResetDecoder
,08-29 16:42:31.552  1965  1965 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 16:42:31.560   873   884 I ActivityManager: Start proc 4367:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 16:42:31.564  1556  1556 I ConfigService: onCreate
,08-29 16:42:31.583   873  1308 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-29 16:42:31.597  1556  4378 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 16:42:31.597  1556  4378 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 16:42:31.598  1556  4378 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-29 16:42:31.601  1556  4378 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-29 16:42:31.606  4367  4367 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 16:42:31.610   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 16:42:31.625  1869  4365 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 16:42:31.629   873  2002 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3797 uid 10000
,08-29 16:42:31.630  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-29 16:42:31.644  1982  2071 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 16:42:31.654   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 16:42:31.655   873   885 E PackageManager: Failed to write settings, restoring backup
08-29 16:42:31.655   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 16:42:31.655   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 16:42:31.655   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 16:42:31.655   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 16:42:31.655   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 16:42:31.655   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.655   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.655   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 16:42:31.657   873  2014 I ActivityManager: Start proc 4384:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 16:42:31.657  1982  2071 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 16:42:31.657  1982  2071 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1982
08-29 16:42:31.657  1982  2071 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.657  1982  2071 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 16:42:31.660   873  1983 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 16:42:31.661   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-29 16:42:31.661   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 16:42:31.661   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:42:31.661   873   886 E DropBoxManagerService: 	... 13 more
08-29 16:42:31.664   873  4390 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:42:31.664   873  4390 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:42:31.664   873  4390 E DropBoxManagerService: 	... 5 more
,08-29 16:42:31.674  1982  2071 I Process : Sending signal. PID: 1982 SIG: 9
,08-29 16:42:31.683  1869  4365 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 16:42:31.685  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 16:42:31.685  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 16:42:31.687  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 16:42:31.687  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 16:42:31.688  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 16:42:31.688  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 16:42:31.690  1869  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 16:42:31.690  1869  4365 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 16:42:31.691  1869  4365 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-29 16:42:31.699  4367  4367 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 16:42:31.701  1869  4365 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 16:42:31.701  1869  4365 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 16:42:31.701  1869  4365 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 16:42:31.715  4367  4397 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 16:42:31.719   873  1981 I ActivityManager: Start proc 4398:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 16:42:31.747  4398  4398 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 16:42:31.749   873  1981 D GraphicsStats: Buffer count: 1
,08-29 16:42:31.749   873  2000 I WindowState: WIN DEATH: Window{7a85f6f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-29 16:42:31.758  4367  4397 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.758  4367  4397 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 16:42:31.759  4367  4397 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 16:42:31.759  4367  4397 E AndroidRuntime: Process: android.process.acore, PID: 4367
08-29 16:42:31.759  4367  4397 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.759  4367  4397 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 16:42:31.765   873  2014 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1982) has died
,08-29 16:42:31.766   873  2014 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-29 16:42:31.767   873  2014 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 16:42:31.787  4367  4381 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.787  4367  4381 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.787  4367  4381 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 16:42:31.787   873   886 I ActivityManager: Start proc 4412:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 16:42:31.794   873  4419 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:42:31.794   873  4419 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:42:31.794   873  4419 E DropBoxManagerService: 	... 5 more
,08-29 16:42:31.802  4367  4397 I Process : Sending signal. PID: 4367 SIG: 9
,08-29 16:42:31.824  1556  1556 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 16:42:31.825  1556  1556 D AndroidRuntime: Shutting down VM
,08-29 16:42:31.826   280   280 E lowmemorykiller: Error writing /proc/4367/oom_score_adj; errno=22
08-29 16:42:31.826  1556  1556 E AndroidRuntime: FATAL EXCEPTION: main
08-29 16:42:31.826  1556  1556 E AndroidRuntime: Process: com.google.process.gapps, PID: 1556
08-29 16:42:31.826  1556  1556 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 16:42:31.826  1556  1556 E AndroidRuntime: 	... 8 more
,08-29 16:42:31.826   280   280 E lowmemorykiller: Error writing /proc/4367/oom_score_adj; errno=22
,08-29 16:42:31.831  1556  1556 I Process : Sending signal. PID: 1556 SIG: 9
,08-29 16:42:31.833   873  4429 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:42:31.833   873  4429 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:42:31.833   873  4429 E DropBoxManagerService: 	... 5 more
,08-29 16:42:31.837  4412  4412 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:42:31.837  4412  4412 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:42:31.837  4412  4412 D AndroidRuntime: Shutting down VM
,08-29 16:42:31.846  4412  4412 E AndroidRuntime: FATAL EXCEPTION: main
08-29 16:42:31.846  4412  4412 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4412
08-29 16:42:31.846  4412  4412 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 16:42:31.846  4412  4412 E AndroidRuntime: 	... 10 more
,08-29 16:42:31.849   873  1378 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 16:42:31.850   873  4430 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:42:31.850   873  4430 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:42:31.850   873  4430 E DropBoxManagerService: 	... 5 more
08-29 16:42:31.851  4412  4412 I Process : Sending signal. PID: 4412 SIG: 9
,08-29 16:42:31.851   280   280 E lowmemorykiller: Error writing /proc/4367/oom_score_adj; errno=22
,08-29 16:42:31.863   280   280 E lowmemorykiller: Error writing /proc/4367/oom_score_adj; errno=22
,08-29 16:42:31.864   873  2000 I ActivityManager: Killing 3697:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 16:42:31.896   873  1313 D WifiService: Client connection lost with reason: 4
,08-29 16:42:31.906  1738  4426 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@f7c1846
,08-29 16:42:31.910   873   883 I ActivityManager: Process com.google.process.gapps (pid 1556) has died
,08-29 16:42:31.910   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,08-29 16:42:31.910   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,08-29 16:42:31.910   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms

```
