#### Test 81738796b06b234_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-18 02:37:25.994   872  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-18 02:37:26.561  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 02:37:26.583  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 02:37:26.585  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 02:37:26.603  1509  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-18 02:37:26.603  1509  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-18 02:37:26.603  1509  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:37:26.603  1509  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-18 02:37:26.614  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-18 02:37:26.614  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-18 02:37:26.614  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-18 02:37:26.694  3809  3809 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-18 02:37:26.698  3809  3809 D AndroidRuntime: CheckJNI is OFF
08-18 02:37:26.737  3809  3809 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-18 02:37:26.786  3809  3809 I Radio-JNI: register_android_hardware_Radio DONE
08-18 02:37:26.807  3809  3809 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-18 02:37:26.816   872   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-18 02:37:26.849  1992  2004 W SearchService: Abort, client detached.
08-18 02:37:26.862  1992  2320 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7d251
08-18 02:37:26.863  1992  2332 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-18 02:37:26.861  1992  1992 I HotwordDetector: Closing mic
08-18 02:37:26.867  3809  3809 D AndroidRuntime: Shutting down VM
08-18 02:37:26.872   872  1976 I ActivityManager: Start proc 3819:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-18 02:37:26.918   377  2335 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-18 02:37:26.919   377  2335 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-18 02:37:26.924   377  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-18 02:37:26.926  1992  2325 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-18 02:37:26.927  1992  2331 I MicroRecognitionRnrImpl: Detection finished
08-18 02:37:26.955  3819  3819 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-18 02:37:26.975  3819  3819 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-18 02:37:26.982  3819  3819 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3561-3563)
08-18 02:37:26.982  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 02:37:26.995  3819  3819 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {af03e56}
08-18 02:37:26.995  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 02:37:26.996  3819  3819 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 02:37:27.002  3819  3819 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-18 02:37:27.003  3819  3819 E SysUtils: ApplicationContext is null in ApplicationStatus
08-18 02:37:27.024  3819  3819 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-18 02:37:27.037  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 02:37:27.037  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 02:37:27.037  3819  3819 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 02:37:27.037  3819  3819 I Adreno  : Build Date                       : 10/20/15
08-18 02:37:27.037  3819  3819 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 02:37:27.037  3819  3819 I Adreno  : Local Branch                     : M14
08-18 02:37:27.037  3819  3819 I Adreno  : Remote Branch                    : 
08-18 02:37:27.037  3819  3819 I Adreno  : Remote Branch                    : 
08-18 02:37:27.037  3819  3819 I Adreno  : Reconstruct Branch               : 
,08-18 02:37:27.102   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ede17df:true
,08-18 02:37:27.190  3819  3819 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-18 02:37:27.208  3819  3819 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-18 02:37:27.340  3819  3857 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-18 02:37:27.358  3819  3844 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-18 02:37:27.418  3819  3857 I OpenGLRenderer: Initialized EGL, version 1.4
,08-18 02:37:27.469   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +612ms
,08-18 02:37:27.480  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-18 02:37:27.571  3819  3819 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3819
,08-18 02:37:27.719   872  1926 I ActivityManager: Killing 3401:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-18 02:37:27.757   872  1926 I ActivityManager: Killing 3048:com.google.android.talk/u0a61 (adj 15): empty #18
,08-18 02:37:27.811  3819  3819 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 02:37:27.947  3819  3859 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1696728784
,08-18 02:37:27.959  3819  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 02:37:27.959  3819  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 02:37:27.959  3819  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 02:37:27.959  3819  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 02:37:27.959  3819  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-18 02:37:27.960  3819  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5349fa added. We now have 1 listener(s)
,08-18 02:37:27.973  3819  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-18 02:37:27.974  3819  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:37:27.976  3819  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 02:37:27.977  3819  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-18 02:37:27.984  3819  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14d0da1 added. We now have 1 listener(s)
,08-18 02:37:27.985  3819  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:37:27.990   872  1304 D WifiService: New client listening to asynchronous messages
,08-18 02:37:27.991  3819  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:37:27.991  3819  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-18 02:37:27.992  3819  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 02:37:27.992  3819  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-18 02:37:27.992  3819  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-18 02:37:28.003  3819  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:37:28.004  3819  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-18 02:37:28.015  3819  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:28.016  3819  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:28.016  3819  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
08-18 02:37:28.016  3819  3859 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-18 02:37:28.017  3819  3859 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 02:37:28.095  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:28.099  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:28.101  3819  3819 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 02:37:29.371  3819  3867 W jxcore-log: Initializing JXcore engine
,08-18 02:37:29.371  3819  3867 W jxcore-log: JXcore engine is ready
,08-18 02:37:29.406  3867  3867 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-18 02:37:29.406  3867  3867 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12043]" dev="sockfs" ino=12043 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-18 02:37:29.406  3867  3867 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-18 02:37:29.406  3867  3867 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24192]" dev="sockfs" ino=24192 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-18 02:37:29.419  3819  3867 W jxcore-log: Starting JXcore engine
,08-18 02:37:29.496  3819  3867 W jxcore-log: Platform android
08-18 02:37:29.496  3819  3867 W jxcore-log: 
,08-18 02:37:29.496  3819  3867 W jxcore-log: Process ARCH arm
08-18 02:37:29.496  3819  3867 W jxcore-log: 
,08-18 02:37:29.708  3819  3867 I jxcore-log: JXcore Cordova bridge is ready!
08-18 02:37:29.708  3819  3867 I jxcore-log: 
08-18 02:37:29.709  3819  3867 W jxcore-log: JXcore engine is started
,08-18 02:37:29.719  3819  3859 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-18 02:37:29.726  3819  3819 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-18 02:37:30.385  1509  2187 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 02:37:30.385  1509  2187 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:37:30.385  1509  2187 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:37:30.386  1509  2187 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:37:30.422  3547  3871 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-18 02:37:30.422  3547  3871 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at blb.a(PG:3937)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at czp.a(PG:18188)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:37:30.422  3547  3871 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	... 12 more
08-18 02:37:30.422  3547  3871 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at fal.a(PG:38)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:37:30.422  3547  3871 E HttpOperation: 	... 14 more
,08-18 02:37:30.512  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 02:37:30.513  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-18 02:37:30.513  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:37:30.513  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:37:30.544  3547  3871 E HttpOperation: [getmobileexperiments] Unexpected exception
08-18 02:37:30.544  3547  3871 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at hec.a(PG:42)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at hee.a(PG:102)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at czr.a(PG:65)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at kka.a(PG:108)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at czp.a(PG:19176)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:37:30.544  3547  3871 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	... 15 more
08-18 02:37:30.544  3547  3871 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at fal.a(PG:38)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:37:30.544  3547  3871 E HttpOperation: 	... 17 more
,08-18 02:37:30.544  3547  3871 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-18 02:37:30.544  3547  3871 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jdm.a(PG:82)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jcs.o(PG:406)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jcn.a(PG:1379)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jcs.i(PG:143)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at hec.a(PG:42)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at hee.a(PG:102)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at czr.a(PG:65)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at kka.a(PG:108)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at czp.a(PG:19176)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at czp.a(PG:9081)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at czq.run(PG:1686)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
,08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jdj.a(PG:4091)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jdj.a(PG:1125)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jdm.a(PG:77)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	... 15 more
08-18 02:37:30.544  3547  3871 E ExperimentLoader: Caused by: faj: BadAuthentication
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at fal.a(PG:38)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	at jdj.a(PG:4089)
08-18 02:37:30.544  3547  3871 E ExperimentLoader: 	... 17 more
,08-18 02:37:30.696   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126766, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:37:46.058  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-18 02:37:46.058  3819  3867 I jxcore-log: 
,08-18 02:37:46.061  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-18 02:37:46.061  3819  3867 I jxcore-log: 
,08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:46.075  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:46.080  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:37:46.083  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-18 02:37:46.083  3819  3867 I jxcore-log: 
,08-18 02:37:46.085  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-18 02:37:46.085  3819  3867 I jxcore-log: 
,08-18 02:37:46.430  3819  3867 I jxcore-log: Running unit tests
08-18 02:37:46.430  3819  3867 I jxcore-log: 
,08-18 02:37:46.431  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 02:37:46.431  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d638f29 added. We now have 2 listener(s)
,08-18 02:37:46.433  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:37:46.433  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:37:46.433  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:37:46.433  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:37:46.433  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb8a2ae added. We now have 2 listener(s)
08-18 02:37:46.433  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:37:46.434  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:37:46.442  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:46.453  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:46.458  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:37:46.459  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:37:46.460  3819  3867 D ExecuteNativeTests: Running unit tests
,08-18 02:37:46.465  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:46.469  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:46.548  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 02:37:46.548  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c added. We now have 3 listener(s)
08-18 02:37:46.549  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:37:46.549  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:37:46.549  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:37:46.549  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:37:46.549  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 added. We now have 3 listener(s)
08-18 02:37:46.549  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:37:46.550  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:37:46.556  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:46.568  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:46.579  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:37:46.579  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:37:46.584  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-18 02:37:46.586  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:37:46.586  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:37:46.586  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:37:46.586  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:46.593  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:46.593  3819  3867 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-18 02:37:46.595  3819  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-18 02:37:46.595  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-18 02:37:46.595  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 02:37:46.595  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 02:37:46.596  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 02:37:46.596  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:37:46.597  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:37:46.597  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 02:37:46.598  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:37:46.598  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:46.598  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:37:46.598  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-18 02:37:46.598  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c removed from the list
08-18 02:37:46.598  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:37:46.598  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 removed from the list
08-18 02:37:46.598  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:37:46.598  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:37:46.600  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:46.600  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:37:46.601  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 02:37:46.601  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:37:46.605  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:37:46.605  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:37:46.610  3819  3867 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-18 02:37:46.610  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:37:46.611  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:37:46.611  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:37:46.611  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:37:46.611  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:46.611  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-18 02:37:46.611  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
,08-18 02:37:46.611  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:37:46.611  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:37:46.611  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:37:46.611  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:37:46.611  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:37:46.611  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:46.611  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:37:46.613  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:37:46.613  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:37:46.613  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:37:46.613  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:37:46.621  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-18 02:37:46.621  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-18 02:37:46.622  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-18 02:37:46.622  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 02:37:46.622  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-18 02:37:46.622  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 02:37:46.623  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-18 02:37:46.623  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-18 02:37:46.623  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-18 02:37:46.624  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 02:37:46.624  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 02:37:46.624  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-18 02:37:46.624  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 02:37:46.624  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-18 02:37:46.625  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-18 02:37:46.625  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 02:37:46.625  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 02:37:46.625  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-18 02:37:46.626  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-18 02:37:46.626  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 02:37:46.626  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-18 02:37:46.626  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 02:37:46.627  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 02:37:46.627  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-18 02:37:46.627  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 02:37:46.627  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 02:37:46.627  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-18 02:37:46.628  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 02:37:46.628  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-18 02:37:46.628  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-18 02:37:46.629  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 02:37:46.629  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:37:46.629  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:37:46.629  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 02:37:46.630  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:37:46.630  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:46.631  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:37:46.631  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
,08-18 02:37:46.631  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:37:46.631  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:37:46.632  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:37:46.632  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:46.632  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:37:46.632  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:37:46.633  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:37:46.638  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:37:46.638  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:37:46.638  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:37:46.639  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:37:46.641  3819  3867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-18 02:37:46.644  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:46.655  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:46.660  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:37:46.661  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:37:46.661  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 02:37:46.662  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-18 02:37:46.662  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 02:37:46.663  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 02:37:46.663  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 02:37:46.664  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:46.666  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:46.667  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 02:37:46.667  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 02:37:46.672  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 02:37:46.674  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-18 02:37:46.674  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 02:37:46.676  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-18 02:37:46.682  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-18 02:37:46.682  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 02:37:46.682  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-18 02:37:46.683  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 02:37:46.685  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:37:46.688  2639  2762 D BtGatt.GattService: registerClient() - UUID=8af5141e-08c0-4618-a2f2-37cf55d33246
,08-18 02:37:46.689  2639  2659 D BtGatt.GattService: onClientRegistered() - UUID=8af5141e-08c0-4618-a2f2-37cf55d33246, clientIf=5
,08-18 02:37:46.690  3819  3830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 02:37:46.690  2639  2652 D BtGatt.GattService: start scan with filters
,08-18 02:37:46.694  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 02:37:46.694  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 02:37:46.695  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 02:37:46.695  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-18 02:37:46.695  2639  2666 D BtGatt.ScanManager: handling starting scan
,08-18 02:37:46.696  2639  2666 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:37:46.697  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:37:46.698  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 02:37:46.698  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:37:46.699  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 02:37:46.701  3819  3867 I io.jxcore.node.ConnectionHelper: start: OK
,08-18 02:37:46.703  2639  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 02:37:46.703  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:46.704  2639  2666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 02:37:46.709  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 02:37:46.709  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:46.709  2639  2666 D BtGatt.ScanManager: Starting BLE batch scan
08-18 02:37:46.709  2639  2666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 02:37:46.717  2639  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 02:37:46.717  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:46.721  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-18 02:37:46.721  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:46.771  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:37:46.780  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:37:46.782  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:37:46.823  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-18 02:37:46.823  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-18 02:37:46.823  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:37:46.823  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:37:46.842  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-18 02:37:46.842  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-18 02:37:46.842  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-18 02:37:47.200  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-18 02:37:47.201  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 02:37:47.201  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 02:37:48.228  2639  2639 D BtGatt.ScanManager: awakened up at time 144810
,08-18 02:37:48.231  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:37:48.272  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-18 02:37:48.272  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:48.273  2639  2659 D BtGatt.GattService: current time is 144854412927
,08-18 02:37:48.273  2639  2659 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -93, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -62, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,08-18 02:37:48.275  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-18 02:37:48.276  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-18 02:37:48.276  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-18 02:37:48.276  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-18 02:37:48.276  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-18 02:37:48.276  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-18 02:37:49.780  2639  2639 D BtGatt.ScanManager: awakened up at time 146361
,08-18 02:37:49.784  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:37:49.833  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-18 02:37:49.833  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:49.834  2639  2659 D BtGatt.GattService: current time is 146415754020
08-18 02:37:49.835  2639  2659 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-18 02:37:49.836  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-18 02:37:49.837  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-18 02:37:49.838  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-18 02:37:49.839  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-18 02:37:49.840  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-18 02:37:50.243   872  1834 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-18 02:37:51.336  2639  2639 D BtGatt.ScanManager: awakened up at time 147917
,08-18 02:37:51.338  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:37:51.368  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-18 02:37:51.369  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:51.370  2639  2659 D BtGatt.GattService: current time is 147952028347
,08-18 02:37:51.371  2639  2659 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -98, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-18 02:37:51.372  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-18 02:37:51.711  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:37:51.712  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 02:37:51.713  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-18 02:37:51.713  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:37:51.723  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-18 02:37:51.725  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 02:37:51.726  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 02:37:51.726  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 02:37:51.726  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 02:37:51.727  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 02:37:51.727  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 02:37:51.728  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:37:51.729  2639  2763 D BtGatt.GattService: stopScan() - queue size =1
,08-18 02:37:51.730  2639  2762 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 02:37:51.730  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 02:37:51.730  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 02:37:51.731  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-18 02:37:51.731  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-18 02:37:51.731  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 02:37:51.732  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:37:51.733  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 02:37:51.733  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 02:37:51.733  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 02:37:51.734  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:37:51.736  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:37:51.736  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:37:51.736  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:37:51.737  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:37:51.737  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:51.737  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:37:51.737  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:37:51.737  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:37:51.737  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:37:51.737  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 02:37:51.737  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:37:51.746  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 02:37:51.746  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:51.746  2639  2666 D BtGatt.ScanManager: stopping BLe Batch
,08-18 02:37:51.757  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 02:37:51.757  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:51.757  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:37:51.765  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 02:37:51.765  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:52.238  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 02:37:53.532   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-18 02:37:53.543  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-18 02:37:53.551   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 02:37:53.551   872   892 I Adreno  : Build Date                       : 10/20/15
08-18 02:37:53.551   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 02:37:53.551   872   892 I Adreno  : Local Branch                     : M14
08-18 02:37:53.551   872   892 I Adreno  : Remote Branch                    : 
08-18 02:37:53.551   872   892 I Adreno  : Remote Branch                    : 
08-18 02:37:53.551   872   892 I Adreno  : Reconstruct Branch               : 
,08-18 02:37:53.591   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (191 us)
,08-18 02:37:54.219  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-18 02:37:54.219  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-18 02:37:54.273   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-18 02:37:54.279  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@db7675c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a9f2b37, 16908290=android.view.AbsSavedState$1@a9f2b37}, android:focusedViewId=100}]}]
08-18 02:37:54.279  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-18 02:37:54.280  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-18 02:37:54.280  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-18 02:37:54.281   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-18 02:37:54.286   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-18 02:37:54.286   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-18 02:37:54.287   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-18 02:37:54.525   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-18 02:37:54.528   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-18 02:37:54.528   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,08-18 02:37:54.537   872   892 I DreamManagerService: Entering dreamland.
,08-18 02:37:54.538   872   892 I PowerManagerService: Dozing...
,08-18 02:37:54.539   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-18 02:37:54.589   377  1275 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-18 02:37:54.589   377  1275 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-18 02:37:54.600   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:37:54.604  1905  3886 D NfcService: Discovery configuration equal, not updating.
,08-18 02:37:54.621   872  1303 E native  : do suspend false
,08-18 02:37:54.642   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-18 02:37:54.655   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:37:54.660   872  1303 E native  : do suspend true
,08-18 02:37:54.727   377  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-18 02:37:54.728   377  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-18 02:37:55.111   872  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-18 02:37:55.897  1509  2195 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-18 02:37:56.738  3819  3867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-18 02:37:56.744  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:56.758  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:56.765  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:37:56.766  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:37:56.766  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 02:37:56.767  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 02:37:56.767  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 02:37:56.767  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 02:37:56.767  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 02:37:56.775  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:56.779  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 02:37:56.779  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 02:37:56.784  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:37:56.793  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 02:37:56.796  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-18 02:37:56.796  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 02:37:56.808  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 02:37:56.808  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 02:37:56.809  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 02:37:56.812  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:37:56.820  2639  2762 D BtGatt.GattService: registerClient() - UUID=f77f1c96-56b9-427f-8950-609c801444c3
,08-18 02:37:56.821  2639  2659 D BtGatt.GattService: onClientRegistered() - UUID=f77f1c96-56b9-427f-8950-609c801444c3, clientIf=5
,08-18 02:37:56.824  3819  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 02:37:56.825  2639  2652 D BtGatt.GattService: start scan with filters
,08-18 02:37:56.834  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 02:37:56.834  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 02:37:56.835  2639  2666 D BtGatt.ScanManager: handling starting scan
,08-18 02:37:56.835  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 02:37:56.835  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 02:37:56.851  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:37:56.853  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:37:56.854  2639  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 02:37:56.854  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 02:37:56.854  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.855  2639  2666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 02:37:56.865  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 02:37:56.877  3819  3867 I io.jxcore.node.ConnectionHelper: start: OK
,08-18 02:37:56.881  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 02:37:56.882  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.883  2639  2666 D BtGatt.ScanManager: Starting BLE batch scan
,08-18 02:37:56.883  2639  2666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 02:37:56.884  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:37:56.885  3819  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 02:37:56.885  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 02:37:56.885  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 02:37:56.885  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:56.885  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-18 02:37:56.885  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 02:37:56.886  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 02:37:56.886  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 02:37:56.886  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 02:37:56.886  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 02:37:56.886  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 02:37:56.887  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:37:56.892  2639  2762 D BtGatt.GattService: stopScan() - queue size =1
,08-18 02:37:56.893  2639  2652 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-18 02:37:56.893  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 02:37:56.893  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 02:37:56.894  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 02:37:56.894  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 02:37:56.894  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 02:37:56.896  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:37:56.897  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 02:37:56.897  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 02:37:56.897  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 02:37:56.898  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:37:56.900  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:37:56.900  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 02:37:56.900  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 02:37:56.900  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:37:56.900  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:56.900  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:37:56.900  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:37:56.900  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:37:56.901  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:37:56.901  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 02:37:56.901  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:37:56.902  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:37:56.902  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:37:56.904  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:37:56.904  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 02:37:56.904  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:37:56.904  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:37:56.906  3819  3867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-18 02:37:56.909  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:37:56.912  2639  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-18 02:37:56.912  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:37:56.916  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:37:56.919  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:37:56.919  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:37:56.920  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 02:37:56.920  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 02:37:56.920  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 02:37:56.920  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 02:37:56.920  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 02:37:56.924  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 02:37:56.924  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 02:37:56.925  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 02:37:56.925  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.928  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:37:56.931  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 02:37:56.931  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:37:56.932  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 02:37:56.932  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 02:37:56.937  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 02:37:56.937  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 02:37:56.937  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 02:37:56.938  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:37:56.940  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 02:37:56.940  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.940  2639  2666 D BtGatt.ScanManager: stopping BLe Batch
,08-18 02:37:56.942  2639  2763 D BtGatt.GattService: registerClient() - UUID=2a12495f-c901-45f0-8d5e-3bc3817cd854
08-18 02:37:56.942  2639  2659 D BtGatt.GattService: onClientRegistered() - UUID=2a12495f-c901-45f0-8d5e-3bc3817cd854, clientIf=5
,08-18 02:37:56.943  3819  3830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 02:37:56.943  2639  2651 D BtGatt.GattService: start scan with filters
,08-18 02:37:56.947  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 02:37:56.947  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 02:37:56.947  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 02:37:56.947  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 02:37:56.949  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 02:37:56.950  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.950  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:37:56.953  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:37:56.953  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 02:37:56.953  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 02:37:56.957  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 02:37:56.957  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-18 02:37:56.957  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:56.960  2639  2666 D BtGatt.ScanManager: handling starting scan
,08-18 02:37:56.960  3819  3867 I io.jxcore.node.ConnectionHelper: start: OK
,08-18 02:37:56.968  2639  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 02:37:56.968  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.968  2639  2666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 02:37:56.976  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-18 02:37:56.976  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:56.976  2639  2666 D BtGatt.ScanManager: Starting BLE batch scan
08-18 02:37:56.976  2639  2666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 02:37:56.997  2639  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-18 02:37:56.997  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:57.011  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-18 02:37:57.012  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:37:57.455  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-18 02:37:57.456  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 02:37:57.456  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 02:37:58.514  2639  2639 D BtGatt.ScanManager: awakened up at time 155096
,08-18 02:37:58.517  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:37:58.587  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-18 02:37:58.588  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:37:58.589  2639  2659 D BtGatt.GattService: current time is 155170346143
,08-18 02:37:58.590  2639  2659 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -95, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-18 02:37:58.591  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-18 02:37:58.592  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-18 02:37:58.593  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-18 02:37:58.594  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-18 02:37:58.595  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-18 02:37:58.596  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-18 02:38:00.094  2639  2639 D BtGatt.ScanManager: awakened up at time 156675
,08-18 02:38:00.099  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:38:00.130  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-18 02:38:00.130  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:38:00.132  2639  2659 D BtGatt.GattService: current time is 156714234060
,08-18 02:38:00.136  2639  2659 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -98, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-18 02:38:00.137  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-18 02:38:00.139  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-18 02:38:00.143  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-18 02:38:00.144  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-18 02:38:00.145  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-18 02:38:00.642  2095  2624 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-18 02:38:00.852  2639  2639 D BtGatt.ScanManager: awakened up at time 157434
,08-18 02:38:00.854  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:38:00.856  3593  3891 I BooksSync: Starting books sync for 61035162, extras: ade
,08-18 02:38:00.878  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-18 02:38:00.878  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:38:00.878  2639  2659 D BtGatt.GattService: current time is 157460310277
08-18 02:38:00.879  2639  2659 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -94, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-18 02:38:00.879  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-18 02:38:00.899  3593  3893 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-18 02:38:00.921  3061  3892 V KeepSync: Connecting to GoogleApiClient
,08-18 02:38:00.923   872  1926 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-18 02:38:00.923  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:38:00.928  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:38:00.987  1509  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:38:00.987  1509  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-18 02:38:00.988  1509  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:38:00.988  1509  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:01.031  1509  2187 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-18 02:38:01.031  1509  2187 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-18 02:38:01.031  1509  2187 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:38:01.032  1509  2187 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:01.071  1733  3894 V BaseAuthAsyncOperation: access token request failed
,08-18 02:38:01.073  3061  3892 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-18 02:38:01.079  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:38:01.079  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-18 02:38:01.080  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:38:01.080  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-18 02:38:01.112  3593  3893 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-18 02:38:01.113  3593  3891 E BooksSync: Soft error
08-18 02:38:01.113  3593  3891 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:38:01.113  3593  3891 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:38:01.113  3593  3891 E BooksSync: Sync error
08-18 02:38:01.113  3593  3891 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:38:01.113  3593  3891 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:38:01.114  3593  3891 I BooksSync: Finished books sync
,08-18 02:38:01.128   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127893, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:38:01.166  1509  2957 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-18 02:38:01.166  1509  2957 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-18 02:38:01.166  1509  2957 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:38:01.166  1509  2957 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:01.187  3061  3892 E KeepSync: IOException
08-18 02:38:01.187  3061  3892 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-18 02:38:01.187  3061  3892 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 02:38:01.187  3061  3892 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-18 02:38:01.187  3061  3892 E KeepSync: 	... 10 more
,08-18 02:38:01.187  3061  3892 W KeepSync: Sync result 2
08-18 02:38:01.196   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 129029, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:38:01.382  2639  2639 D BtGatt.ScanManager: awakened up at time 157964
,08-18 02:38:01.385  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:38:01.407  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 02:38:01.407  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:38:01.961  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:01.961  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:01.962  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-18 02:38:01.962  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:01.962  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-18 02:38:01.963  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-18 02:38:01.963  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 02:38:01.963  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 02:38:01.964  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-18 02:38:01.965  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 02:38:01.965  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 02:38:01.967  3819  3867 D BluetoothAdapter: STATE_ON
08-18 02:38:01.969  2639  2652 D BtGatt.GattService: stopScan() - queue size =1
08-18 02:38:01.972  2639  2762 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 02:38:01.973  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 02:38:01.974  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 02:38:01.974  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 02:38:01.974  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 02:38:01.975  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 02:38:01.980  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 02:38:01.980  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 02:38:01.980  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 02:38:01.981  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 02:38:01.983  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:38:01.985  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:38:01.985  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:38:01.986  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:38:01.987  2639  2639 D BtGatt.ScanManager: awakened up at time 158568
,08-18 02:38:01.992  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 02:38:01.992  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:38:01.992  2639  2666 D BtGatt.ScanManager: stopping BLe Batch
,08-18 02:38:02.009  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 02:38:02.009  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:38:02.010  2639  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:38:02.019  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 02:38:02.020  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:38:02.064  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:38:02.340  1509  3896 I VacuumService: Vacuum at: now=1471480682340 tag=VacuumService
,08-18 02:38:02.458  1509  3897 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-18 02:38:02.464  1509  3897 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-18 02:38:02.486  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 02:38:02.487  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:02.487  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 02:38:02.497  1509  3897 W Uploader:  no longer exists, so no auth token.
,08-18 02:38:03.688  1509  3897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-18 02:38:03.689  1509  3897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-18 02:38:03.689  1509  3897 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:38:03.690  1509  3897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:03.731  1509  3897 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-18 02:38:03.731  1509  3897 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-18 02:38:03.731  1509  3897 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-18 02:38:04.196  1509  3897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-18 02:38:04.197  1509  3897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-18 02:38:04.197  1509  3897 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:38:04.198  1509  3897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:04.247  1509  3897 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-18 02:38:04.247  1509  3897 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-18 02:38:04.247  1509  3897 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-18 02:38:04.997  1509  3897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-18 02:38:04.997  1509  3897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-18 02:38:04.998  1509  3897 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:38:04.998  1509  3897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:05.054  1509  3897 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-18 02:38:05.054  1509  3897 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-18 02:38:05.054  1509  3897 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-18 02:38:06.010   872  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-18 02:38:06.986  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:38:06.987  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:06.987  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:06.988  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:06.988  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:06.988  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:38:06.989  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:06.989  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:06.989  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:06.990  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:06.991  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:06.992  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:06.993  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:06.997  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:06.997  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:06.997  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:06.998  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.000  3819  3867 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-18 02:38:07.002  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:38:07.002  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.003  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 02:38:07.003  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.003  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:07.004  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.004  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.004  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.005  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.005  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.005  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.006  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.006  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.006  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.009  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 02:38:07.009  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:07.010  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.010  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.013  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-18 02:38:07.013  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.013  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.013  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.014  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.014  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.014  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.015  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.015  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.015  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.015  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.016  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.016  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.016  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.016  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.019  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.020  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 02:38:07.020  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.020  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.022  3819  3867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-18 02:38:07.023  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.023  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:38:07.023  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.024  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.024  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.024  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.024  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.025  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.025  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.025  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 02:38:07.025  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.026  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.026  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.026  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.030  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.030  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 02:38:07.030  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.030  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.032  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-18 02:38:07.032  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.032  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.033  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.033  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.033  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.033  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.033  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.034  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.034  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.034  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.034  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.034  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.034  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.035  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.038  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.038  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 02:38:07.038  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.038  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.040  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-18 02:38:07.040  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:38:07.040  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:38:07.040  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 02:38:07.041  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 02:38:07.041  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 02:38:07.041  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 02:38:07.041  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:38:07.042  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 02:38:07.042  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.042  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:38:07.042  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.043  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.043  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.043  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.043  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.043  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.044  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.044  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.044  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.044  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.044  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.044  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.047  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 02:38:07.047  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:07.047  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.048  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.049  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 02:38:07.050  3819  3867 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 02:38:07.050  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-18 02:38:07.057  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 02:38:07.057  3819  3867 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-18 02:38:07.057  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-18 02:38:07.057  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-18 02:38:07.057  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 02:38:07.058  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 02:38:07.059  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 02:38:07.060  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 02:38:07.061  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-18 02:38:07.061  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 02:38:07.061  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-18 02:38:07.061  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-18 02:38:07.061  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 02:38:07.061  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-18 02:38:07.062  3819  3867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-18 02:38:07.062  3819  3867 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-18 02:38:07.062  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 02:38:07.062  3819  3867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 02:38:07.063  3819  3867 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-18 02:38:07.063  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 02:38:07.063  3819  3867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 02:38:07.063  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-18 02:38:07.068  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-18 02:38:07.070  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-18 02:38:07.070  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-18 02:38:07.071  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-18 02:38:07.071  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-18 02:38:07.071  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-18 02:38:07.072  3819  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 02:38:07.072  3819  3867 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-18 02:38:07.073  3819  3912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-18 02:38:07.073  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.074  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.074  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.074  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.074  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.074  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.074  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-18 02:38:07.076  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.076  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.076  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.076  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.076  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:07.077  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.077  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.077  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.078  3819  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
,08-18 02:38:07.080  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.080  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:07.081  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:07.081  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.081  3819  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 02:38:07.082  3819  3867 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-18 02:38:07.083  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.083  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.084  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.084  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.084  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.084  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.084  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.084  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:07.084  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.084  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.085  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.085  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.085  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:07.085  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.087  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.087  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:07.087  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.087  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.088  3819  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-18 02:38:07.088  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.089  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.089  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.089  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.089  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.089  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.089  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.089  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.089  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.089  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.089  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:07.090  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.090  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.090  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.091  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.091  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:07.091  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:07.091  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.092  3819  3867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-18 02:38:07.092  3819  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-18 02:38:07.092  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 02:38:07.092  3819  3867 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-18 02:38:07.092  3819  3867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 02:38:07.093  3819  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-18 02:38:07.093  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 02:38:07.093  3819  3867 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-18 02:38:07.093  3819  3867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 02:38:07.093  3819  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 02:38:07.093  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-18 02:38:07.093  3819  3867 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-18 02:38:07.094  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:07.094  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:07.094  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:07.094  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:38:07.094  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.094  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.094  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.095  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.095  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:07.095  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.095  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.095  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.095  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.095  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.096  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:07.098  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:07.098  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:07.098  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.099  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:07.099  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.099  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:07.099  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:07.099  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:07.099  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:07.099  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:07.099  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:07.100  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:07.550   872  1834 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 02:38:12.100  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:12.101  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.101  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:12.102  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.102  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:12.103  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
,08-18 02:38:12.111  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:38:12.111  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:12.111  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:12.112  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:38:12.112  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.113  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:12.113  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
,08-18 02:38:12.113  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:12.114  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.114  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:12.114  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:12.115  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:12.115  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.115  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:12.119  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:12.119  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:12.119  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:12.120  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:12.124  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-18 02:38:12.125  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:38:12.127  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-18 02:38:12.130  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-18 02:38:12.130  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-18 02:38:12.131  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-18 02:38:12.131  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-18 02:38:12.131  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 02:38:12.132  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:12.132  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-18 02:38:12.133  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-18 02:38:12.133  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-18 02:38:12.133  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.133  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-18 02:38:12.134  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-18 02:38:12.134  3819  3914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-18 02:38:12.134  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:12.134  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.134  3819  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-18 02:38:12.134  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 02:38:12.134  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 02:38:12.135  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-18 02:38:12.135  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.136  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.139  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 02:38:12.139  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:38:12.139  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:38:12.139  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.139  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-18 02:38:12.139  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:38:12.139  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:12.140  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:12.140  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:12.140  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:12.140  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.141  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.141  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:12.141  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.141  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.142  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 02:38:12.142  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.142  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.142  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.143  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.146  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:12.146  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:12.146  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.146  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:12.155  3819  3867 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-18 02:38:12.155  3819  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-18 02:38:12.155  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 02:38:12.155  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 02:38:12.156  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 02:38:12.156  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:38:12.156  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:12.156  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:12.156  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:12.156  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.156  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.156  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:12.156  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:12.156  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.156  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:12.156  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.157  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.157  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:12.157  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.158  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:12.158  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:12.159  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.159  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
,08-18 02:38:12.162  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:12.162  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:12.162  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:38:12.162  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:12.163  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.163  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.163  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
,08-18 02:38:12.163  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.163  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.163  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:12.163  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.163  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.163  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.163  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:12.165  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:12.165  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:12.165  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.165  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.166  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:38:12.166  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:38:12.166  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 02:38:12.166  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:38:12.166  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.166  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.166  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17940c not in the list
08-18 02:38:12.167  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.167  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.167  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:12.167  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:38:12.167  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.167  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:12.167  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:12.168  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:38:12.168  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:38:12.168  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:12.168  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de155 not in the list
08-18 02:38:12.169  3819  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-18 02:38:12.169  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-18 02:38:12.169  3819  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-18 02:38:12.169  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 02:38:12.169  3819  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-18 02:38:12.170  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-18 02:38:12.175  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 02:38:12.176  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-18 02:38:12.176  3819  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-18 02:38:12.176  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-18 02:38:12.176  3819  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-18 02:38:12.177  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-18 02:38:12.177  3819  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-18 02:38:12.177  3819  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-18 02:38:12.177  3819  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-18 02:38:12.177  3819  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-18 02:38:12.178  3819  3867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-18 02:38:12.178  3819  3867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-18 02:38:12.178  3819  3867 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-18 02:38:12.178  3819  3867 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-18 02:38:12.179  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:38:12.179  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ae183c added. We now have 3 listener(s)
,08-18 02:38:12.179  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:38:12.180  3819  3867 D BluetoothAdapter: enable(): BT is already enabled..!
08-18 02:38:12.181   872  1391 D WifiService: setWifiEnabled: true pid=3819, uid=10000
08-18 02:38:12.181   872  1391 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 02:38:12.220  2639  2741 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-18 02:38:12.221  3819  3912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-18 02:38:12.221  2639  2746 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-18 02:38:12.640  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 02:38:17.187  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 02:38:17.188  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4eac9c5 added. We now have 4 listener(s)
08-18 02:38:17.188  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:38:17.204  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-18 02:38:17.205  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4eac9c5 removed from the list
08-18 02:38:17.205  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:17.205  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:17.206  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:17.207  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 02:38:17.208  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d01f1a added. We now have 4 listener(s)
08-18 02:38:17.208  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:38:17.209  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:17.209  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d01f1a removed from the list
08-18 02:38:17.210  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:17.210  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:17.210  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:17.210  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 02:38:17.210  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e335a4b added. We now have 4 listener(s)
08-18 02:38:17.210  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:38:17.213   872  3139 D WifiService: setWifiEnabled: false pid=3819, uid=10000
08-18 02:38:17.213   872  3139 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 02:38:17.223  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:38:17.229  2639  2655 D BluetoothAdapterState: Current state: ON, message: 23
,08-18 02:38:17.229  2639  2655 D BluetoothAdapterProperties: Setting state to 13
08-18 02:38:17.229  2639  2655 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-18 02:38:17.232  2639  2655 D BluetoothAdapterProperties: onBluetoothDisable()
,08-18 02:38:17.237  2639  2639 D BluetoothMapService: onReceive
08-18 02:38:17.237  2639  2639 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 02:38:17.237  2639  2639 D BluetoothMapService: STATE_TURNING_OFF
08-18 02:38:17.237  2639  2639 D BluetoothMapService: MAP Service closeService in
08-18 02:38:17.237  2639  2639 D BluetoothMapMasInstance0: MAP Service shutdown
,08-18 02:38:17.237  2639  2639 D ObexServerSockets0: shutdown(block = true)
08-18 02:38:17.238  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.238  2639  2639 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:38:17.239  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:38:17.239  2639  2639 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 02:38:17.239  2639  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-18 02:38:17.239  2639  2786 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-18 02:38:17.240  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.240  2639  2746 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-18 02:38:17.240  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:17.240  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 02:38:17.240  2639  2639 I BtOppRfcommListener: stopping Accept Thread
,08-18 02:38:17.240  2639  3449 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 02:38:17.242  2639  2655 I BluetoothAdapterState: Entering PendingCommandState
08-18 02:38:17.244  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.245  2639  3449 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 02:38:17.247  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:17.249  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 02:38:17.251   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-18 02:38:17.251   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-18 02:38:17.251   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 02:38:17.251   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 02:38:17.252  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:38:17.253  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:38:17.253  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.253  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:17.257  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:38:17.257  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 02:38:17.258  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.258  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:17.260  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:17.265   872  1303 E native  : do suspend true
,08-18 02:38:17.265   872   885 I ActivityManager: Start proc 3918:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-18 02:38:17.265  2639  2659 D BluetoothAdapterProperties: Scan Mode:20
08-18 02:38:17.265  2639  2655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-18 02:38:17.268  2639  2639 D HeadsetService: Received stop request...Stopping profile...
,08-18 02:38:17.270  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:17.271  1921  2171 D BluetoothHeadset: Proxy object disconnected
08-18 02:38:17.272   872   872 D BluetoothHeadset: Proxy object disconnected
08-18 02:38:17.272  1348  1368 D BluetoothHeadset: Proxy object disconnected
,08-18 02:38:17.272   872   872 D BluetoothHeadset: Proxy object disconnected
,08-18 02:38:17.273   872   872 D BluetoothHeadset: Proxy object disconnected
,08-18 02:38:17.273  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.273  2639  2639 D A2dpService: Received stop request...Stopping profile...
08-18 02:38:17.274  1348  1348 D HeadsetProfile: Bluetooth service disconnected
,08-18 02:38:17.274  2639  2769 D A2dpStateMachine: Exit Disconnected: -1
,08-18 02:38:17.274  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.275   872   872 D BluetoothA2dp: Proxy object disconnected
08-18 02:38:17.276  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-18 02:38:17.276  2639  2639 D HidService: Received stop request...Stopping profile...
08-18 02:38:17.276  2639  2639 D HidService: Stopping Bluetooth HidService
08-18 02:38:17.277  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-18 02:38:17.277  1348  1348 D HidProfile: Bluetooth service disconnected
,08-18 02:38:17.278   872  1838 D DhcpClient: Clearing IP address
08-18 02:38:17.278  2639  2639 D HealthService: Received stop request...Stopping profile...
,08-18 02:38:17.278   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-18 02:38:17.280  2639  2639 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:17.281  2639  2639 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:17.281  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:17.281  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:17.281   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:17.283  2639  2639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-18 02:38:17.283  2639  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-18 02:38:17.283  2639  2741 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:17.283  2639  2741 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:17.283  2639  2639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 02:38:17.283  2639  2741 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:17.283  2639  2659 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-18 02:38:17.285  2639  2639 D PanService: Received stop request...Stopping profile...
,08-18 02:38:17.285  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 02:38:17.285  1348  1348 D PanProfile: Bluetooth service disconnected
08-18 02:38:17.286   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-18 02:38:17.286   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-18 02:38:17.286   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
08-18 02:38:17.287   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 02:38:17.287   872  1303 E native  : do suspend true
08-18 02:38:17.291   404   404 E Parcel  : Reading a NULL string not supported here.
,08-18 02:38:17.292  2639  2639 D BluetoothMapService: Received stop request...Stopping profile...
08-18 02:38:17.292  2639  2639 D BluetoothMapService: stop()
,08-18 02:38:17.292  2639  2639 D BluetoothMapAppObserver: deinitObservers()
08-18 02:38:17.293  2639  2639 D BluetoothMapAppObserver: removeReceiver()
,08-18 02:38:17.293  1348  1348 D BluetoothMap: Proxy object disconnected
,08-18 02:38:17.293  1348  1348 D MapProfile: Bluetooth service disconnected
,08-18 02:38:17.294  2639  2639 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:17.294  2639  2639 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:17.294  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:17.294  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:17.296  2639  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-18 02:38:17.296  2639  2741 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:17.296  2639  2741 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:17.296  2639  2741 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 02:38:17.296  2639  2741 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 02:38:17.296  2639  2741 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 02:38:17.296  2639  2741 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 02:38:17.296  2639  2639 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:17.296  2639  2639 V BluetoothAdapterState: isTurningOn()=false
,08-18 02:38:17.297  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:17.297  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:17.296   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-18 02:38:17.297  2639  2639 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-18 02:38:17.297  2639  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-18 02:38:17.297  2639  2639 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-18 02:38:17.300  2639  2639 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:17.300  2639  2639 V BluetoothAdapterState: isTurningOn()=false
,08-18 02:38:17.300  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:17.300  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:17.300  2639  2639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-18 02:38:17.300  2639  2659 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-18 02:38:17.301  2639  2639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 02:38:17.302   872  1851 D DhcpClient: Receive thread stopped
08-18 02:38:17.302  2639  2639 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:17.302  2639  2639 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:17.302  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:17.302  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:17.302  2639  2639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 02:38:17.303  2639  2639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-18 02:38:17.304  1509  2094 V NativeCrypto: Read error: ssl=0xaed23000: I/O error during system call, Connection timed out
08-18 02:38:17.304  2639  2639 D BluetoothMapService: MAP Service closeService in
08-18 02:38:17.304  2639  2639 V BluetoothAdapterState: isTurningOff()=true
,08-18 02:38:17.304  2639  2639 V BluetoothAdapterState: isTurningOn()=false
,08-18 02:38:17.304  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:17.304  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:17.304  2639  2655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-18 02:38:17.304  2639  2655 D BluetoothAdapterProperties: Setting state to 15
08-18 02:38:17.304  2639  2655 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-18 02:38:17.305  2639  2655 I BluetoothAdapterState: Entering BleOnState
08-18 02:38:17.305  1348  2157 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-18 02:38:17.306   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:17.306  1348  1368 D BluetoothPan: onBluetoothStateChange on: false
08-18 02:38:17.306   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:17.307  1348  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-18 02:38:17.307  1348  2170 D BluetoothMap: onBluetoothStateChange: up=false
08-18 02:38:17.308   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 02:38:17.308  2639  2639 D BluetoothMapService: cleanup()
08-18 02:38:17.308  1348  2157 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:17.308  2639  2639 D BluetoothMapService: MAP Service closeService in
08-18 02:38:17.309  1921  2171 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 02:38:17.309  1509  2094 V NativeCrypto: SSL shutdown failed: ssl=0xaed23000: I/O error during system call, Broken pipe
,08-18 02:38:17.309   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 02:38:17.309  1348  1368 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 02:38:17.311  2639  2655 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-18 02:38:17.311  2639  2655 D BluetoothAdapterProperties: Setting state to 16
08-18 02:38:17.311  2639  2655 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-18 02:38:17.311  2639  2655 D BluetoothAdapterProperties: onBleDisable
,08-18 02:38:17.311  2639  2655 I BluetoothAdapterState: Entering PendingCommandState
08-18 02:38:17.312  2639  2656 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-18 02:38:17.312  2639  2741 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-18 02:38:17.312  2639  2741 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 02:38:17.314  2639  2659 D BluetoothAdapterProperties: Scan Mode:20
08-18 02:38:17.320  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:17.320  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:17.320  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.320  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:17.322  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:17.322  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:17.323  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.323  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:17.325  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:17.325  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:17.325  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.325  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:17.327  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.328  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.329  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.337  3918  3918 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-18 02:38:17.339   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=,0
08-18 02:38:17.350  3918  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 02:38:17.361   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-18 02:38:17.361  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 02:38:17.361   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-18 02:38:17.361   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-18 02:38:17.361   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 02:38:17.363   872   889 D Tethering: MasterInitialState.processMessage what=3
08-18 02:38:17.365  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.366  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.368  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:17.370  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-18 02:38:17.373   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7936eb1:true
08-18 02:38:17.377   872  1901 I ActivityManager: Start proc 3935:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-18 02:38:17.379   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-18 02:38:17.390  3918  3918 D LocalBluetoothProfileManager: Adding local MAP profile
08-18 02:38:17.393  3918  3918 D BluetoothMap: Create BluetoothMap proxy object
08-18 02:38:17.395   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
08-18 02:38:17.397  2095  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 02:38:17.397   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-18 02:38:17.398  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:17.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:17.398  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.398  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:17.400  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:17.400  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:17.400  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.400  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:17.402  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:17.402  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:17.402  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:17.402  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:17.409  3918  3918 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-18 02:38:17.413   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-18 02:38:17.419  3935  3935 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-18 02:38:17.422  3918  3918 D DockEventReceiver: finishStartingService: stopping service
08-18 02:38:17.430   872  2965 I ActivityManager: Killing 1665:android.process.acore/u0a5 (adj 15): empty #17
,08-18 02:38:17.516  2639  2659 I bt_hci  : shut_down
,08-18 02:38:17.522  2639  2667 I bt_vendor: low_power_mode_cb
08-18 02:38:17.523  2639  2667 D bt_hwcfg: hw_epilog_process
,08-18 02:38:17.550  2639  2667 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-18 02:38:17.550  2639  2667 I bt_vendor: epilog_cb
08-18 02:38:17.550  2639  2667 I bt_hci  : epilog_finished_callback
,08-18 02:38:17.556  2639  2659 I bt_hci_h4: hal_close
08-18 02:38:17.557  2639  2659 I bt_userial_vendor: device fd = 51 close
,08-18 02:38:17.628  3935  3935 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.628  3935  3935 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.628  3935  3935 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.628  3935  3935 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.r.e.b(PG:170)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.628  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.629  3935  3935 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.k.d(PG:583)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.e.b(PG:170)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.629  3935  3935 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.629  3935  3935 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.629  3935  3935 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:38:17.629  3935  3935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:38:17.638  3918  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 02:38:17.649  3918  3918 D DockEventReceiver: finishStartingService: stopping service
08-18 02:38:17.652  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 02:38:17.655   872  1926 I ActivityManager: Killing 3668:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-18 02:38:17.757   872  1926 I ActivityManager: Start proc 3969:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-18 02:38:17.759  2639  2656 D bt_stack_manager: event_shut_down_stack finished.
,08-18 02:38:17.760  2639  2655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-18 02:38:17.765  2639  2639 D BtGatt.DebugUtils: handleDebugAction() action=null
08-18 02:38:17.765  2639  2655 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-18 02:38:17.765  2639  2639 D BtGatt.GattService: Received stop request...Stopping profile...
08-18 02:38:17.765  2639  2639 D BtGatt.GattService: stop()
08-18 02:38:17.765  2639  2639 D BtGatt.AdvertiseManager: advertise clients cleared
08-18 02:38:17.767  2639  2639 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:17.767  2639  2639 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:17.767  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:17.767  2639  2639 V BluetoothAdapterState: isBleTurningOff()=true
08-18 02:38:17.767  2639  2655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-18 02:38:17.769  2639  2655 D BluetoothAdapterProperties: Setting state to 10
08-18 02:38:17.770  2639  2655 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-18 02:38:17.771   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-18 02:38:17.771  2639  2655 I BluetoothAdapterState: Entering OffState
,08-18 02:38:17.794  2639  2639 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-18 02:38:17.794  2639  2639 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-18 02:38:17.794  2639  2639 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-18 02:38:17.795  2639  2656 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-18 02:38:17.797  2639  2656 D bt_stack_manager: event_clean_up_stack finished.
,08-18 02:38:17.809  2639  2639 I art     : System.exit called, status: 0
08-18 02:38:17.809  2639  2639 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 02:38:17.826  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-18 02:38:17.872   872  2965 I ActivityManager: Process com.android.bluetooth (pid 2639) has died
,08-18 02:38:18.022  3969  3988 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-18 02:38:18.022  3969  3988 I Babel_SMS: MmsConfig.loadMmsSettings
,08-18 02:38:18.027  3969  3988 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-18 02:38:18.028  3969  3988 I Babel_SMS: MmsConfig.loadFromDatabase
,08-18 02:38:18.056  3969  3988 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-18 02:38:18.056  3969  3988 I Babel_SMS: MmsConfig.loadFromResources
08-18 02:38:18.058  3969  3988 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-18 02:38:18.063  3969  3988 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-18 02:38:18.085  3969  3969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 02:38:18.088  3969  3969 I Babel_Crash: startup - clean
,08-18 02:38:18.127  3969  3969 I Babel_telephony: TeleModule.launchCompleted
,08-18 02:38:18.144   872  1379 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-18 02:38:18.156  3969  3969 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-18 02:38:18.164  3969  3969 W Babel   : BAM#gBA: invalid account id: -1
08-18 02:38:18.164  3969  3969 W Babel   : BAM#gBA: invalid account id: -1
08-18 02:38:18.164  3969  3969 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-18 02:38:18.186  3969  3994 I Babel   : deleted: false for 0
,08-18 02:38:18.189   872  1901 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-18 02:38:18.199  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-18 02:38:18.203  1733  1733 D SystemUpdateService: onCreate
,08-18 02:38:18.206  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-18 02:38:18.210  1733  3996 I SystemUpdateService: active receiver: enabled
,08-18 02:38:18.213  1733  3996 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-18 02:38:18.215  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-18 02:38:18.215  1733  3996 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-18 02:38:18.216  1733  3996 I SystemUpdateService: now status is 0 (complete)
08-18 02:38:18.216  1733  3996 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-18 02:38:18.216  1733  3996 I SystemUpdateService: file has been verified
,08-18 02:38:18.216  1733  2403 I iu.UploadsManager: num queued entries: 0
,08-18 02:38:18.216  1733  3996 I SystemUpdateService: OTA package size = 12249756
,08-18 02:38:18.222  1733  2403 I iu.UploadsManager: num updated entries: 0
,08-18 02:38:18.224  1733  3996 I SystemUpdateService: showing system update notification
,08-18 02:38:18.225  1733  2403 I iu.SyncManager: NEXT; no task
,08-18 02:38:18.228  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 02:38:18.230  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 02:38:18.241   872  1940 I ActivityManager: Start proc 3998:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-18 02:38:18.243  1733  1733 D SystemUpdateService: onDestroy
,08-18 02:38:18.285  3998  3998 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-18 02:38:18.286  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 02:38:18.291  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:38:18.310  3998  3998 D SprintDMHelper: simOperator: 
,08-18 02:38:18.310  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 02:38:18.338   872  1901 I ActivityManager: Start proc 4010:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-18 02:38:18.341  3969  3969 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-18 02:38:18.356  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 02:38:18.360  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 02:38:18.370  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 02:38:18.391  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 02:38:18.394   872  1974 I ActivityManager: Killing 3684:com.android.musicfx/u0a18 (adj 15): empty #17
,08-18 02:38:18.458  3969  3969 I vclib   : onServiceConnected
,08-18 02:38:18.528  3935  3961 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-18 02:38:18.533   872   882 I ActivityManager: Start proc 4025:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-18 02:38:18.535  3969  4024 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-18 02:38:18.539   872   883 I ActivityManager: Killing 2219:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-18 02:38:18.560   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af653da:true
,08-18 02:38:18.613  4025  4025 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-18 02:38:18.671  4025  4025 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-18 02:38:18.671  4025  4025 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-18 02:38:18.671  4025  4025 I GAv4    :   adb logcat -s GAv4
,08-18 02:38:18.702  4025  4025 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-18 02:38:18.708  4025  4025 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-18 02:38:18.739  4025  4043 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-18 02:38:18.850  4025  4025 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-18 02:38:18.886  4025  4025 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-18 02:38:18.900  4025  4025 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5479-5481)
08-18 02:38:18.900  4025  4025 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 02:38:18.913  4025  4025 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f1225aa}
08-18 02:38:18.913  4025  4025 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 02:38:18.913  4025  4025 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-18 02:38:18.922  4025  4025 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-18 02:38:18.923  4025  4025 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-18 02:38:18.939  4025  4025 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-18 02:38:18.951  4025  4025 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-18 02:38:18.951  4025  4025 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-18 02:38:18.955  4025  4025 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 02:38:18.955  4025  4025 I Adreno  : Build Date                       : 10/20/15
08-18 02:38:18.955  4025  4025 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 02:38:18.955  4025  4025 I Adreno  : Local Branch                     : M14
08-18 02:38:18.955  4025  4025 I Adreno  : Remote Branch                    : 
08-18 02:38:18.955  4025  4025 I Adreno  : Remote Branch                    : 
08-18 02:38:18.955  4025  4025 I Adreno  : Reconstruct Branch               : 
,08-18 02:38:19.016  4025  4025 I NSApplication: Starting up...
,08-18 02:38:19.025  4025  4071 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-18 02:38:19.065   872  2965 I ActivityManager: Start proc 4076:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-18 02:38:19.066   872  2965 I ActivityManager: Killing 3630:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-18 02:38:19.154  4076  4076 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-18 02:38:19.349   872  1940 I ActivityManager: Killing 3706:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-18 02:38:19.470   872   882 I ActivityManager: Start proc 4090:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-18 02:38:19.532  4090  4090 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-18 02:38:19.592  4090  4090 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-18 02:38:19.660   872   882 I ActivityManager: Killing 2959:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-18 02:38:22.245   872  2965 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,08-18 02:38:22.245   872  2965 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-18 02:38:22.261   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-18 02:38:22.271  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:22.272  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:22.272  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:22.272  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 02:38:22.276  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:22.276  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:22.277  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:22.277  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 02:38:22.280  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:22.280  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:22.281  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:22.281  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:22.294   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-18 02:38:22.295   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-18 02:38:22.296   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-18 02:38:22.297   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-18 02:38:22.298   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-18 02:38:22.298   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-18 02:38:22.298   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-18 02:38:22.321   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-18 02:38:22.321   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-18 02:38:22.324   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:22.331   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-18 02:38:22.331   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-18 02:38:22.332   872  1303 E native  : do suspend true
,08-18 02:38:22.351   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:38:22.352   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-18 02:38:22.361   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-18 02:38:23.412   872  1940 I ActivityManager: Killing 3770:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-18 02:38:23.638   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-18 02:38:23.704   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.50 rxSuccessRate=7.44 delta 1000 -> 994
08-18 02:38:23.707   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-18 02:38:23.707   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:23.723   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-18 02:38:23.762   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-18 02:38:23.764  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-18 02:38:24.178  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 02:38:24.229  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 02:38:24.229  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-18 02:38:24.233   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:38:24.245   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-18 02:38:24.245   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-18 02:38:24.245   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:24.261   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:24.272   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:24.273   872  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,08-18 02:38:24.279   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-18 02:38:24.326   872  4125 D DhcpClient: Receive thread started
,08-18 02:38:24.410   872  1303 E native  : do suspend false
,08-18 02:38:24.430   872  1838 D DhcpClient: Broadcasting DHCPDISCOVER
,08-18 02:38:24.444   872  4125 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172641, domain null
,08-18 02:38:24.445   872  1838 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172641 seconds
,08-18 02:38:24.452   872  1838 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-18 02:38:24.467   872  4125 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-18 02:38:24.470   872  1838 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-18 02:38:24.476   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:24.487   872  1838 D DhcpClient: Scheduling renewal in 86399s
,08-18 02:38:24.489   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-18 02:38:24.491   872  1303 E native  : do suspend true
,08-18 02:38:24.510   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-18 02:38:24.514   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-18 02:38:24.516   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-18 02:38:24.521   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-18 02:38:24.521   872  1305 D ConnectivityService: Adding iface wlan0 to network 101
,08-18 02:38:24.593   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-18 02:38:24.593   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-18 02:38:24.594   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-18 02:38:24.595   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-18 02:38:24.597   872  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-18 02:38:24.605   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-18 02:38:24.610   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-18 02:38:24.610   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-18 02:38:24.610   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-18 02:38:24.610   872  1305 D ConnectivityService:    accepting network in place of null
,08-18 02:38:24.610   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-18 02:38:24.611   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-18 02:38:24.613   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 02:38:24.623   872  4124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181204, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 02:38:24.660   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 02:38:24.695   872  4123 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:80d::200e
,08-18 02:38:24.709   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 02:38:24.717   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-18 02:38:24.718   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:38:24.724   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-18 02:38:24.733   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-18 02:38:24.734  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:38:24.734  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:38:24.734  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:24.735  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:24.741  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:38:24.742  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:38:24.742  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:24.742  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:38:24.747  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:38:24.747  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 02:38:24.747  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:24.747  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 02:38:24.755  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-18 02:38:24.761  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-18 02:38:24.767  1733  1733 D SystemUpdateService: onCreate
,08-18 02:38:24.770  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-18 02:38:24.778   872  4123 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 00:38:24 GMT], X-Android-Received-Millis=[1471480704778], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471480704748]}
,08-18 02:38:24.779   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-18 02:38:24.779   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-18 02:38:24.779   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-18 02:38:24.780   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-18 02:38:24.794  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-18 02:38:24.807  1733  4134 I SystemUpdateService: active receiver: enabled
,08-18 02:38:24.809  1733  2403 I iu.UploadsManager: num queued entries: 0
,08-18 02:38:24.809  1733  2403 I iu.UploadsManager: num updated entries: 0
,08-18 02:38:24.812  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 02:38:24.813  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 02:38:24.815  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:38:24.825  1733  4138 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-18 02:38:24.825  1733  4138 W BaseAppContext: Using Auth Proxy for data requests.
,08-18 02:38:24.827  1733  4138 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-18 02:38:24.828  3998  3998 D SprintDMHelper: simOperator: 
,08-18 02:38:24.828  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 02:38:24.835  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 02:38:24.837  1733  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-18 02:38:24.841  1733  2403 I iu.SyncManager: NEXT; no task
08-18 02:38:24.841  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:38:24.844  1733  4134 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-18 02:38:24.844  1733  4134 I SystemUpdateService: now status is 0 (complete)
08-18 02:38:24.854  1733  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-18 02:38:24.854  1733  4134 I SystemUpdateService: file has been verified
,08-18 02:38:24.854  1733  4134 I SystemUpdateService: OTA package size = 12249756
,08-18 02:38:24.871  1733  4134 I SystemUpdateService: showing system update notification
,08-18 02:38:24.936  1509  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-18 02:38:24.936  1509  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-18 02:38:24.936  1509  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:38:24.936  1509  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:38:24.949  1733  1733 D SystemUpdateService: onDestroy
,08-18 02:38:24.955  3969  4140 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-18 02:38:24.972  1733  4138 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-18 02:38:25.717   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-18 02:38:27.255   872  1901 D WifiService: setWifiEnabled: false pid=3819, uid=10000
,08-18 02:38:27.256   872  1901 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 02:38:27.292  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-18 02:38:27.301   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-18 02:38:27.301   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-18 02:38:27.302   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 02:38:27.302   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:27.324   872  1303 E native  : do suspend true
,08-18 02:38:27.343   872  1838 D DhcpClient: Clearing IP address
08-18 02:38:27.343   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-18 02:38:27.349  1509  4146 V NativeCrypto: Read error: ssl=0x9a60f200: I/O error during system call, Connection timed out
,08-18 02:38:27.352   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:27.355   872  4125 D DhcpClient: Receive thread stopped
,08-18 02:38:27.359   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-18 02:38:27.360   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-18 02:38:27.370   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
08-18 02:38:27.372   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 02:38:27.372   872  1303 E native  : do suspend true
08-18 02:38:27.373   404   404 E Parcel  : Reading a NULL string not supported here.
08-18 02:38:27.377  1509  4146 V NativeCrypto: SSL shutdown failed: ssl=0x9a60f200: I/O error during system call, Broken pipe
,08-18 02:38:27.381   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-18 02:38:27.385   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-18 02:38:27.387   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-18 02:38:27.403   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:38:27.406  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:27.406  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:27.406  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:27.406  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:27.407  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:27.407  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:27.407  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:27.407  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:27.408  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:27.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:27.409  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:27.409  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:27.410   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-18 02:38:27.411  2095  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 02:38:27.445   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 02:38:27.473   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 02:38:27.476   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-18 02:38:27.476   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:38:27.482   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-18 02:38:27.500  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-18 02:38:27.500  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:27.503  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:27.503  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:27.512  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-18 02:38:27.516  1733  1733 D SystemUpdateService: onCreate
,08-18 02:38:27.520  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-18 02:38:27.533  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-18 02:38:27.539  1733  2403 I iu.UploadsManager: num queued entries: 0
,08-18 02:38:27.540  1733  4157 I SystemUpdateService: active receiver: enabled
,08-18 02:38:27.542  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 02:38:27.543  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 02:38:27.545  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:38:27.549  3998  3998 D SprintDMHelper: simOperator: 
,08-18 02:38:27.549  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 02:38:27.565   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-18 02:38:27.566   872  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-18 02:38:27.540  1733  2403 I iu.UploadsManager: num updated entries: 0
,08-18 02:38:27.579  3969  4161 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-18 02:38:27.583  1733  4157 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-18 02:38:27.584  1733  2403 I iu.SyncManager: NEXT; no task
,08-18 02:38:27.586  1733  4157 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-18 02:38:27.586  1733  4157 I SystemUpdateService: now status is 0 (complete)
08-18 02:38:27.586  1733  4157 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-18 02:38:27.586  1733  4157 I SystemUpdateService: file has been verified
,08-18 02:38:27.586  1733  4157 I SystemUpdateService: OTA package size = 12249756
,08-18 02:38:27.591  1733  4157 I SystemUpdateService: showing system update notification
,08-18 02:38:27.602  1733  1733 D SystemUpdateService: onDestroy
,08-18 02:38:32.317   872   889 I ActivityManager: Start proc 4166:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-18 02:38:32.451  4166  4166 D AdapterServiceConfig: Adding HeadsetService
,08-18 02:38:32.452  4166  4166 D AdapterServiceConfig: Adding A2dpService
08-18 02:38:32.452  4166  4166 D AdapterServiceConfig: Adding HidService
08-18 02:38:32.452  4166  4166 D AdapterServiceConfig: Adding HealthService
08-18 02:38:32.452  4166  4166 D AdapterServiceConfig: Adding PanService
,08-18 02:38:32.453  4166  4166 D AdapterServiceConfig: Adding GattService
08-18 02:38:32.453  4166  4166 D AdapterServiceConfig: Adding BluetoothMapService
,08-18 02:38:32.468   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6200ee:true
,08-18 02:38:32.468  4166  4166 D BluetoothAdapterState: make() - Creating AdapterState
,08-18 02:38:32.474  4166  4166 I bt_bluedroid: init
,08-18 02:38:32.474  4166  4178 I BluetoothAdapterState: Entering OffState
,08-18 02:38:32.482  4166  4179 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-18 02:38:32.482  4166  4179 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 02:38:32.483  4166  4179 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-18 02:38:32.485  4166  4179 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-18 02:38:32.488  4166  4166 I bt_bluedroid: get_profile_interface socket
,08-18 02:38:32.490  4166  4166 I bt_bluedroid: get_profile_interface sdp
,08-18 02:38:32.493  4166  4177 I bt_bluedroid: config_hci_snoop_log
,08-18 02:38:32.494  4166  4182 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 02:38:32.495   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-18 02:38:32.497  4166  4182 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 02:38:32.504  4166  4178 D BluetoothAdapterState: Current state: OFF, message: 0
,08-18 02:38:32.505  4166  4178 D BluetoothAdapterProperties: Setting state to 14
08-18 02:38:32.505  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-18 02:38:32.510  4166  4178 D BluetoothBondStateMachine: make
,08-18 02:38:32.515  4166  4183 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-18 02:38:32.522  4166  4178 I BluetoothAdapterState: Entering PendingCommandState
,08-18 02:38:32.526  4166  4166 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-18 02:38:32.535  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:32.537  4166  4166 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 02:38:32.539  4166  4166 D BtGatt.GattService: Received start request. Starting profile...
,08-18 02:38:32.539  4166  4166 D BtGatt.GattService: start()
,08-18 02:38:32.539  4166  4166 I bt_bluedroid: get_profile_interface gatt
,08-18 02:38:32.541  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:32.542  4166  4166 D BtGatt.AdvertiseManager: advertise manager created
,08-18 02:38:32.557  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:32.558  4166  4166 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:32.558  4166  4166 V BluetoothAdapterState: isBleTurningOn()=true
08-18 02:38:32.559  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:32.560  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-18 02:38:32.562  4166  4178 I bt_bluedroid: enable
08-18 02:38:32.562  4166  4179 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-18 02:38:32.563  4166  4179 I bt_hci  : start_up
,08-18 02:38:32.583  4166  4179 I bt_vendor: alloc value 0xb3a17189
,08-18 02:38:32.584  4166  4179 I bt_vendor: init
08-18 02:38:32.584  4166  4179 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-18 02:38:32.584  4166  4179 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-18 02:38:32.615   872  1305 D ConnectivityService: handlePromptUnvalidated 101
,08-18 02:38:32.693  4166  4179 D bt_hci  : start_up starting async portion
,08-18 02:38:32.694  4166  4186 I bt_hci  : event_finish_startup
08-18 02:38:32.694  4166  4186 I bt_hci_h4: hal_open
,08-18 02:38:32.694  4166  4186 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-18 02:38:32.704  4166  4186 I bt_userial_vendor: device fd = 51 open
,08-18 02:38:32.736  4166  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 02:38:32.768  4166  4186 D bt_hwcfg: Chipset BCM4354A2
,08-18 02:38:32.768  4166  4186 D bt_hwcfg: Target name = [BCM4354A2]
08-18 02:38:32.769  4166  4186 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-18 02:38:33.428  4166  4186 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-18 02:38:33.429  4166  4186 D bt_hwcfg: Settlement delay -- 100 ms
08-18 02:38:33.430  4166  4186 I bt_hwcfg: Setting fw settlement delay to 100 
,08-18 02:38:33.546  4166  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 02:38:33.547  4166  4186 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-18 02:38:33.577  4166  4186 I bt_hwcfg: vendor lib fwcfg completed
,08-18 02:38:33.577  4166  4186 I bt_vendor: firmware callback
08-18 02:38:33.577  4166  4186 I bt_hci  : firmware_config_callback
,08-18 02:38:33.589  4166  4188 I bt_btu  : btu_task pending for preload complete event
,08-18 02:38:33.589  4166  4188 I bt_btu_task: Bluetooth chip preload is complete
08-18 02:38:33.589  4166  4188 I bt_btu  : btu_task received preload complete event
,08-18 02:38:33.599  4166  4188 I         : BTE_InitTraceLevels -- TRC_HCI
,08-18 02:38:33.599  4166  4188 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-18 02:38:33.599  4166  4188 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-18 02:38:33.599  4166  4188 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-18 02:38:33.600  4166  4188 I         : BTE_InitTraceLevels -- TRC_AVRC
08-18 02:38:33.600  4166  4188 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 02:38:33.601  4166  4188 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 02:38:33.602  4166  4188 I         : BTE_InitTraceLevels -- TRC_BTM
08-18 02:38:33.602  4166  4188 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 02:38:33.602  4166  4188 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 02:38:33.602  4166  4188 I         : BTE_InitTraceLevels -- TRC_SDP
08-18 02:38:33.603  4166  4188 I         : BTE_InitTraceLevels -- TRC_GATT
08-18 02:38:33.603  4166  4188 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 02:38:33.603  4166  4188 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-18 02:38:33.603  4166  4188 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 02:38:33.736  4166  4188 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3994d9d
,08-18 02:38:33.736  4166  4188 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3994d9d 
,08-18 02:38:33.747  4166  4182 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-18 02:38:33.750  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-18 02:38:33.751  4166  4182 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 02:38:33.756  4166  4182 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 02:38:33.760  4166  4182 D BluetoothAdapterProperties: Scan Mode:20
08-18 02:38:33.760  4166  4182 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 02:38:33.761  4166  4182 D bt_hci  : do_postload posting postload work item
08-18 02:38:33.761  4166  4186 I bt_hci  : event_postload
,08-18 02:38:33.761  4166  4186 I bt_vendor: sco_config_cb
,08-18 02:38:33.761  4166  4186 I bt_hci  : sco_config_callback postload finished.
08-18 02:38:33.764  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:33.765  4166  4182 D bt_bte_conf: Device ID record 1 : primary
,08-18 02:38:33.765  4166  4182 D bt_bte_conf:   vendorId            = 000f
,08-18 02:38:33.765  4166  4182 D bt_bte_conf:   vendorIdSource      = 0001
08-18 02:38:33.765  4166  4182 D bt_bte_conf:   product             = 1200
,08-18 02:38:33.766  4166  4182 D bt_bte_conf:   version             = 1436
08-18 02:38:33.766  4166  4182 D bt_bte_conf:   clientExecutableURL = 
08-18 02:38:33.766  4166  4182 D bt_bte_conf:   serviceDescription  = 
,08-18 02:38:33.766  4166  4182 D bt_bte_conf:   documentationURL    = 
08-18 02:38:33.766  4166  4182 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-18 02:38:33.767  4166  4179 D bt_stack_manager: event_start_up_stack finished
08-18 02:38:33.769  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:33.769  4166  4186 I bt_vendor: low_power_mode_cb
08-18 02:38:33.769  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-18 02:38:33.770  4166  4178 D BluetoothAdapterProperties: Setting state to 15
,08-18 02:38:33.770  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-18 02:38:33.773  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:33.773  4166  4178 I BluetoothAdapterState: Entering BleOnState
08-18 02:38:33.777  4166  4178 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-18 02:38:33.778  4166  4178 D BluetoothAdapterProperties: Setting state to 11
08-18 02:38:33.778  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-18 02:38:33.784  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:33.785  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:33.788  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:33.789  4166  4166 D HeadsetService: Received start request. Starting profile...
08-18 02:38:33.789  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:33.793  4166  4166 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-18 02:38:33.793  4166  4166 D HeadsetStateMachine: make
08-18 02:38:33.799  4166  4178 I BluetoothAdapterState: Entering PendingCommandState
,08-18 02:38:33.802  4166  4166 D HeadsetStateMachine: max_hf_connections = 1
,08-18 02:38:33.802  4166  4166 I bt_bluedroid: get_profile_interface handsfree
08-18 02:38:33.802  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-18 02:38:33.803  4166  4182 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-18 02:38:33.807  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:33.807  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 02:38:33.807  4166  4166 D A2dpService: Received start request. Starting profile...
08-18 02:38:33.808  4166  4166 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-18 02:38:33.809  4166  4166 I bt_bluedroid: get_profile_interface avrcp
,08-18 02:38:33.814  4166  4166 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-18 02:38:33.814  4166  4166 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 02:38:33.814  4166  4166 D A2dpStateMachine: make
08-18 02:38:33.815  4166  4166 I bt_bluedroid: get_profile_interface a2dp
,08-18 02:38:33.816  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-18 02:38:33.819  4166  4198 D A2dpStateMachine: Enter Disconnected: -2
,08-18 02:38:33.820  4166  4166 I BluetoothHidServiceJni: classInitNative: succeeds
,08-18 02:38:33.821  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:33.823  4166  4166 D HidService: Received start request. Starting profile...
,08-18 02:38:33.823  3918  3918 D BluetoothInputDevice: Proxy object connected
08-18 02:38:33.823  4166  4166 I bt_bluedroid: get_profile_interface hidhost
08-18 02:38:33.823  4166  4166 D HidService: setHidService(): set to: null
08-18 02:38:33.823  4166  4182 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39763e5
08-18 02:38:33.823  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-18 02:38:33.823  3918  3918 D HidProfile: Bluetooth service connected
08-18 02:38:33.824  4166  4166 I BluetoothHealthServiceJni: classInitNative: succeeds
08-18 02:38:33.824  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:33.825  4166  4166 D HealthService: Received start request. Starting profile...
,08-18 02:38:33.826  4166  4166 I bt_bluedroid: get_profile_interface health
,08-18 02:38:33.827  4166  4166 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-18 02:38:33.827  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:33.828  4166  4166 D PanService: Received start request. Starting profile...
,08-18 02:38:33.829  4166  4166 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 02:38:33.829  4166  4166 I bt_bluedroid: get_profile_interface pan
08-18 02:38:33.828  3918  3918 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 02:38:33.829  4166  4182 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-18 02:38:33.829  3918  3918 D PanProfile: Bluetooth service connected
,08-18 02:38:33.831  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:33.832  4166  4166 D BluetoothMapService: Received start request. Starting profile...
08-18 02:38:33.832  4166  4166 D BluetoothMapService: start()
08-18 02:38:33.833  3918  3918 D BluetoothMap: Proxy object connected
08-18 02:38:33.833  3918  3918 D MapProfile: Bluetooth service connected
08-18 02:38:33.833  3918  3918 D BluetoothMap: getConnectedDevices()
08-18 02:38:33.833  3918  3918 D BluetoothMap: Bluetooth is Not enabled
,08-18 02:38:33.834  4166  4166 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-18 02:38:33.835  4166  4166 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-18 02:38:33.835  4166  4166 D BluetoothMapAppObserver: createReceiver()
,08-18 02:38:33.836  4166  4166 D BluetoothMapAppObserver: initObservers()
08-18 02:38:33.836  4166  4166 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-18 02:38:33.844  4166  4196 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-18 02:38:33.844  4166  4166 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:33.844  4166  4166 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:33.844  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:33.844  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isTurningOn()=true
,08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:33.848  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isTurningOn()=true
,08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:33.849  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:33.850  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-18 02:38:33.850  4166  4178 D BluetoothAdapterProperties: ScanMode =  20
,08-18 02:38:33.850  4166  4178 D BluetoothAdapterProperties: State =  11
08-18 02:38:33.850  4166  4178 D BluetoothAdapterProperties: Setting state to 12
08-18 02:38:33.850  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 02:38:33.852  4166  4182 D BluetoothAdapterProperties: Scan Mode:21
08-18 02:38:33.852  4166  4182 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 02:38:33.852  1348  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-18 02:38:33.852  4166  4178 I BluetoothAdapterState: Entering OnState
,08-18 02:38:33.854  1348  1348 D BluetoothInputDevice: Proxy object connected
,08-18 02:38:33.854  1348  1348 D HidProfile: Bluetooth service connected
08-18 02:38:33.856  3918  3929 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 02:38:33.856   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:33.857  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:33.857  1348  1368 D BluetoothPan: onBluetoothStateChange on: true
08-18 02:38:33.859  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 02:38:33.859  1348  1348 D PanProfile: Bluetooth service connected
08-18 02:38:33.859  3918  3928 D BluetoothPan: onBluetoothStateChange on: true
,08-18 02:38:33.859   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:33.859  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:33.860  1348  2170 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 02:38:33.861  3918  3929 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 02:38:33.862  1348  1348 D BluetoothA2dp: Proxy object connected
08-18 02:38:33.862  4166  4166 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-18 02:38:33.863  4166  4166 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:33.863  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:33.864  1348  2157 D BluetoothMap: onBluetoothStateChange: up=true
08-18 02:38:33.865  1348  1348 D BluetoothMap: Proxy object connected
08-18 02:38:33.866  1348  1348 D MapProfile: Bluetooth service connected
08-18 02:38:33.866  1348  1348 D BluetoothMap: getConnectedDevices()
08-18 02:38:33.866   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:33.866  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:33.866  1348  2170 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 02:38:33.866  4166  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 02:38:33.867  1921  1939 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:33.868   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 02:38:33.869   872   872 D BluetoothA2dp: Proxy object connected
08-18 02:38:33.869  3918  3928 D BluetoothMap: onBluetoothStateChange: up=true
08-18 02:38:33.870  4166  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:33.870  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:33.870  1348  1361 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 02:38:33.871  4166  4166 D ObexServerSockets: Succeed to create listening sockets 
08-18 02:38:33.871  4166  4166 D ObexServerSockets0: startAccept()
08-18 02:38:33.871  4166  4166 D ObexServerSockets0: prepareForNewConnect()
08-18 02:38:33.873  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:33.874   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-18 02:38:33.876  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:33.877  4166  4166 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-18 02:38:33.877  4166  4166 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-18 02:38:33.878  4166  4166 D BluetoothMapService: onReceive
08-18 02:38:33.878  4166  4166 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 02:38:33.878  4166  4166 D BluetoothMapService: STATE_ON
08-18 02:38:33.879  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:33.879  4166  4204 D ObexServerSockets0: Accepting socket connection...
08-18 02:38:33.880  4166  4205 D ObexServerSockets0: Accepting socket connection...
08-18 02:38:33.881  3918  3918 D LocalBluetoothProfileManager: Adding local A2DP profile
08-18 02:38:33.881  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:33.886  3918  3918 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-18 02:38:33.892  3918  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 02:38:33.896  3918  3918 D BluetoothA2dp: Proxy object connected
,08-18 02:38:33.899  4166  4166 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 02:38:33.899  4166  4166 D ObexServerSockets0: prepareForNewConnect()
08-18 02:38:33.906  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 02:38:33.906  1348  1348 D BluetoothPbap: Proxy object connected
,08-18 02:38:33.906  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-18 02:38:33.908  4166  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 02:38:33.914  3918  3918 D DockEventReceiver: finishStartingService: stopping service
,08-18 02:38:33.914  3918  3918 D BluetoothPbap: Proxy object connected
08-18 02:38:33.915  3918  3918 D PbapServerProfile: Bluetooth service connected
,08-18 02:38:33.936  4166  4213 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 02:38:33.942  4166  4213 I BtOppRfcommListener: Accept thread started.
,08-18 02:38:33.958  1921  2171 D BluetoothHeadset: Proxy object connected
,08-18 02:38:33.959   872   872 D BluetoothHeadset: Proxy object connected
,08-18 02:38:33.960  1348  1361 D BluetoothHeadset: Proxy object connected
08-18 02:38:33.960   872   889 D BluetoothHeadset: Proxy object connected
08-18 02:38:33.960  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-18 02:38:33.960   872   872 D BluetoothHeadset: Proxy object connected
08-18 02:38:33.960   872   872 D BluetoothHeadset: Proxy object connected
,08-18 02:38:33.966   872   889 D BluetoothHeadset: Proxy object connected
08-18 02:38:33.966  1348  1368 D BluetoothHeadset: Proxy object connected
,08-18 02:38:33.967  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-18 02:38:33.968  1921  1942 D BluetoothHeadset: Proxy object connected
,08-18 02:38:33.989  3918  3928 D BluetoothHeadset: Proxy object connected
,08-18 02:38:33.989  3918  3918 D HeadsetProfile: Bluetooth service connected
,08-18 02:38:37.276  4166  4178 D BluetoothAdapterState: Current state: ON, message: 23
,08-18 02:38:37.277  4166  4178 D BluetoothAdapterProperties: Setting state to 13
,08-18 02:38:37.277  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-18 02:38:37.279  4166  4178 D BluetoothAdapterProperties: onBluetoothDisable()
08-18 02:38:37.292  4166  4166 D BluetoothMapService: onReceive
08-18 02:38:37.293  4166  4166 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 02:38:37.293  4166  4166 D BluetoothMapService: STATE_TURNING_OFF
08-18 02:38:37.294  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:37.294  4166  4166 D BluetoothMapService: MAP Service closeService in
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:37.294  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:37.294  4166  4166 D BluetoothMapMasInstance0: MAP Service shutdown
,08-18 02:38:37.295  4166  4178 I BluetoothAdapterState: Entering PendingCommandState
08-18 02:38:37.295  4166  4166 D ObexServerSockets0: shutdown(block = true)
,08-18 02:38:37.296  4166  4182 D BluetoothAdapterProperties: Scan Mode:20
08-18 02:38:37.296  4166  4204 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-18 02:38:37.297  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:37.298  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:37.300  4166  4166 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 02:38:37.301  4166  4205 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-18 02:38:37.298  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-18 02:38:37.302  4166  4190 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-18 02:38:37.303  4166  4166 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 02:38:37.304  4166  4166 I BtOppRfcommListener: stopping Accept Thread
08-18 02:38:37.304  4166  4213 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-18 02:38:37.304  3918  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 02:38:37.306  4166  4213 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 02:38:37.307  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:37.308  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:37.309  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 02:38:37.309  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:37.311  4166  4166 D HeadsetService: Received stop request...Stopping profile...
08-18 02:38:37.312  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:37.312  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:37.313  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 02:38:37.313  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:37.315  1921  1939 D BluetoothHeadset: Proxy object disconnected
,08-18 02:38:37.316   872   872 D BluetoothHeadset: Proxy object disconnected
08-18 02:38:37.316  1348  1368 D BluetoothHeadset: Proxy object disconnected
08-18 02:38:37.316   872   872 D BluetoothHeadset: Proxy object disconnected
08-18 02:38:37.317  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.317  3918  3928 D BluetoothHeadset: Proxy object disconnected
,08-18 02:38:37.317   872   872 D BluetoothHeadset: Proxy object disconnected
08-18 02:38:37.318  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.319  4166  4166 D A2dpService: Received stop request...Stopping profile...
08-18 02:38:37.319  4166  4198 D A2dpStateMachine: Exit Disconnected: -1
08-18 02:38:37.320  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.320   872   872 D BluetoothA2dp: Proxy object disconnected
08-18 02:38:37.323  4166  4166 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:37.323  4166  4166 V BluetoothAdapterState: isTurningOn()=false
,08-18 02:38:37.323  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:37.323  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:37.324  4166  4166 D HidService: Received stop request...Stopping profile...
08-18 02:38:37.324  4166  4166 D HidService: Stopping Bluetooth HidService
,08-18 02:38:37.326  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 02:38:37.326  4166  4166 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-18 02:38:37.327  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-18 02:38:37.327  4166  4188 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:37.327  4166  4188 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 02:38:37.327  4166  4188 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:37.327  4166  4166 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 02:38:37.327  4166  4182 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-18 02:38:37.328  4166  4166 D HealthService: Received stop request...Stopping profile...
,08-18 02:38:37.331  4166  4166 D PanService: Received stop request...Stopping profile...
08-18 02:38:37.331  1348  1348 D HeadsetProfile: Bluetooth service disconnected
,08-18 02:38:37.331  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-18 02:38:37.332  3918  3918 D DockEventReceiver: finishStartingService: stopping service
08-18 02:38:37.332  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-18 02:38:37.332  1348  1348 D HidProfile: Bluetooth service disconnected
08-18 02:38:37.332  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 02:38:37.332  1348  1348 D PanProfile: Bluetooth service disconnected
08-18 02:38:37.333  4166  4166 D BluetoothMapService: Received stop request...Stopping profile...
08-18 02:38:37.333  4166  4166 D BluetoothMapService: stop()
08-18 02:38:37.334  4166  4166 D BluetoothMapAppObserver: deinitObservers()
,08-18 02:38:37.334  4166  4166 D BluetoothMapAppObserver: removeReceiver()
08-18 02:38:37.334  3918  3918 D HeadsetProfile: Bluetooth service disconnected
08-18 02:38:37.335  4166  4166 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:37.335  4166  4166 V BluetoothAdapterState: isTurningOn()=false
,08-18 02:38:37.336  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:37.336  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:37.336  3918  3918 D BluetoothA2dp: Proxy object disconnected
,08-18 02:38:37.336  3918  3918 D BluetoothInputDevice: Proxy object disconnected
,08-18 02:38:37.336  3918  3918 D HidProfile: Bluetooth service disconnected
08-18 02:38:37.337  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-18 02:38:37.337  4166  4188 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:37.337  4166  4188 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 02:38:37.337  4166  4188 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 02:38:37.337  4166  4188 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-18 02:38:37.337  4166  4188 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 02:38:37.337  4166  4188 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-18 02:38:37.339  1348  1348 D BluetoothMap: Proxy object disconnected
08-18 02:38:37.339  1348  1348 D MapProfile: Bluetooth service disconnected
08-18 02:38:37.340  1348  1348 D BluetoothPbap: Proxy object disconnected
08-18 02:38:37.340  3918  3918 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 02:38:37.340  1348  1348 D PbapServerProfile: Bluetooth service disconnected
08-18 02:38:37.340  3918  3918 D PanProfile: Bluetooth service disconnected
,08-18 02:38:37.340  4166  4166 V BluetoothAdapterState: isTurningOff()=true
,08-18 02:38:37.340  3918  3918 D BluetoothMap: Proxy object disconnected
08-18 02:38:37.340  4166  4166 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:37.340  3918  3918 D MapProfile: Bluetooth service disconnected
08-18 02:38:37.340  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:37.340  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:37.340  4166  4166 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-18 02:38:37.340  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-18 02:38:37.341  4166  4166 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-18 02:38:37.340  3918  3918 D BluetoothPbap: Proxy object disconnected
,08-18 02:38:37.341  4166  4166 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:37.341  3918  3918 D PbapServerProfile: Bluetooth service disconnected
08-18 02:38:37.341  4166  4166 V BluetoothAdapterState: isTurningOn()=false
,08-18 02:38:37.341  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:37.341  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:37.342  4166  4166 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-18 02:38:37.342  4166  4182 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-18 02:38:37.342  4166  4166 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 02:38:37.342  4166  4166 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:37.342  4166  4166 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:37.342  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:37.342  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:37.343  4166  4166 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 02:38:37.343  4166  4166 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-18 02:38:37.344  4166  4166 D BluetoothMapService: MAP Service closeService in
08-18 02:38:37.344  4166  4166 V BluetoothAdapterState: isTurningOff()=true
08-18 02:38:37.344  4166  4166 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:37.344  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:37.344  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:37.344  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-18 02:38:37.344  4166  4178 D BluetoothAdapterProperties: Setting state to 15
08-18 02:38:37.344  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-18 02:38:37.345  4166  4166 D BluetoothMapService: cleanup()
08-18 02:38:37.345  4166  4166 D BluetoothMapService: MAP Service closeService in
08-18 02:38:37.346  1348  1361 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-18 02:38:37.346  4166  4178 I BluetoothAdapterState: Entering BleOnState
08-18 02:38:37.349  3918  3928 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 02:38:37.350   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:37.350  1348  1368 D BluetoothPan: onBluetoothStateChange on: false
08-18 02:38:37.351  3918  3929 D BluetoothPan: onBluetoothStateChange on: false
08-18 02:38:37.351   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:37.352  3918  3928 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 02:38:37.352  1348  2157 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-18 02:38:37.353  3918  3929 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 02:38:37.353  1348  2170 D BluetoothMap: onBluetoothStateChange: up=false
,08-18 02:38:37.353   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:37.354  1348  1361 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:37.354  3918  3928 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:37.354  1921  2080 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 02:38:37.354   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 02:38:37.355  3918  3929 D BluetoothMap: onBluetoothStateChange: up=false
08-18 02:38:37.355  1348  1368 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 02:38:37.356  4166  4178 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-18 02:38:37.356  4166  4178 D BluetoothAdapterProperties: Setting state to 16
08-18 02:38:37.356  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-18 02:38:37.357  4166  4178 D BluetoothAdapterProperties: onBleDisable
08-18 02:38:37.357  4166  4178 I BluetoothAdapterState: Entering PendingCommandState
08-18 02:38:37.357  4166  4179 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-18 02:38:37.357  4166  4188 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-18 02:38:37.358  4166  4188 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 02:38:37.360  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.360  4166  4182 D BluetoothAdapterProperties: Scan Mode:20
08-18 02:38:37.361  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:37.362  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.362  3918  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 02:38:37.364  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.365  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.366  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:37.366  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 02:38:37.373  3918  3918 D DockEventReceiver: finishStartingService: stopping service
,08-18 02:38:37.564  4166  4182 I bt_hci  : shut_down
,08-18 02:38:37.564  4166  4186 D bt_hwcfg: hw_epilog_process
,08-18 02:38:37.578  4166  4186 I bt_vendor: low_power_mode_cb
,08-18 02:38:37.608  4166  4186 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-18 02:38:37.608  4166  4186 I bt_vendor: epilog_cb
08-18 02:38:37.608  4166  4186 I bt_hci  : epilog_finished_callback
,08-18 02:38:37.616  4166  4182 I bt_hci_h4: hal_close
,08-18 02:38:37.617  4166  4182 I bt_userial_vendor: device fd = 51 close
,08-18 02:38:37.737  4166  4179 D bt_stack_manager: event_shut_down_stack finished.
,08-18 02:38:37.738  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-18 02:38:37.745  4166  4178 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-18 02:38:37.745  4166  4166 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 02:38:37.747  4166  4166 D BtGatt.GattService: Received stop request...Stopping profile...
08-18 02:38:37.747  4166  4166 D BtGatt.GattService: stop()
08-18 02:38:37.748  4166  4166 D BtGatt.AdvertiseManager: advertise clients cleared
,08-18 02:38:37.753  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:37.753  4166  4166 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:37.753  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:37.754  4166  4166 V BluetoothAdapterState: isBleTurningOff()=true
08-18 02:38:37.754  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-18 02:38:37.755  4166  4178 D BluetoothAdapterProperties: Setting state to 10
08-18 02:38:37.756  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-18 02:38:37.758  4166  4178 I BluetoothAdapterState: Entering OffState
,08-18 02:38:37.759   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-18 02:38:37.786  4166  4166 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-18 02:38:37.786  4166  4166 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-18 02:38:37.787  4166  4179 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-18 02:38:37.794  4166  4179 D bt_stack_manager: event_clean_up_stack finished.
,08-18 02:38:37.794  4166  4166 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-18 02:38:37.799  4166  4166 I art     : System.exit called, status: 0
,08-18 02:38:37.800  4166  4166 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 02:38:37.863   872  1940 I ActivityManager: Process com.android.bluetooth (pid 4166) has died
,08-18 02:38:42.273  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 02:38:42.274  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:42.280  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:42.280  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e335a4b removed from the list
,08-18 02:38:42.280  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:42.281  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:42.281  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:42.288  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 02:38:42.289  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b33d41 added. We now have 4 listener(s)
08-18 02:38:42.289  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:38:42.292  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:38:42.292  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b33d41 removed from the list
08-18 02:38:42.293  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:38:42.293  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:42.293  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:38:42.295  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:38:42.296  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4112e6 added. We now have 4 listener(s)
08-18 02:38:42.296  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:38:47.309  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:47.362   872   889 I ActivityManager: Start proc 4223:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-18 02:38:47.481  4223  4223 D AdapterServiceConfig: Adding HeadsetService
,08-18 02:38:47.482  4223  4223 D AdapterServiceConfig: Adding A2dpService
08-18 02:38:47.482  4223  4223 D AdapterServiceConfig: Adding HidService
08-18 02:38:47.482  4223  4223 D AdapterServiceConfig: Adding HealthService
,08-18 02:38:47.482  4223  4223 D AdapterServiceConfig: Adding PanService
,08-18 02:38:47.483  4223  4223 D AdapterServiceConfig: Adding GattService
08-18 02:38:47.483  4223  4223 D AdapterServiceConfig: Adding BluetoothMapService
,08-18 02:38:47.497  4223  4223 D BluetoothAdapterState: make() - Creating AdapterState
08-18 02:38:47.497   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65574f3:true
,08-18 02:38:47.504  4223  4223 I bt_bluedroid: init
,08-18 02:38:47.505  4223  4235 I BluetoothAdapterState: Entering OffState
,08-18 02:38:47.509  4223  4236 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-18 02:38:47.509  4223  4236 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 02:38:47.509  4223  4236 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-18 02:38:47.509  4223  4236 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-18 02:38:47.511  4223  4223 I bt_bluedroid: get_profile_interface socket
08-18 02:38:47.513  4223  4223 I bt_bluedroid: get_profile_interface sdp
,08-18 02:38:47.517  4223  4239 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 02:38:47.517  4223  4234 I bt_bluedroid: config_hci_snoop_log
,08-18 02:38:47.518  4223  4239 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 02:38:47.524   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-18 02:38:47.537  4223  4235 D BluetoothAdapterState: Current state: OFF, message: 0
,08-18 02:38:47.537  4223  4235 D BluetoothAdapterProperties: Setting state to 14
08-18 02:38:47.538  4223  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-18 02:38:47.541  4223  4235 D BluetoothBondStateMachine: make
,08-18 02:38:47.547  4223  4240 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-18 02:38:47.552  4223  4235 I BluetoothAdapterState: Entering PendingCommandState
,08-18 02:38:47.557  4223  4223 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-18 02:38:47.567  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:47.569  4223  4223 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 02:38:47.571  4223  4223 D BtGatt.GattService: Received start request. Starting profile...
,08-18 02:38:47.572  4223  4223 D BtGatt.GattService: start()
08-18 02:38:47.572  4223  4223 I bt_bluedroid: get_profile_interface gatt
,08-18 02:38:47.576  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:47.576  4223  4223 D BtGatt.AdvertiseManager: advertise manager created
,08-18 02:38:47.596  4223  4223 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:47.597  4223  4223 V BluetoothAdapterState: isTurningOn()=false
08-18 02:38:47.597  4223  4223 V BluetoothAdapterState: isBleTurningOn()=true
08-18 02:38:47.597  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:47.599  4223  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-18 02:38:47.600  4223  4235 I bt_bluedroid: enable
08-18 02:38:47.601  4223  4236 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-18 02:38:47.602  4223  4236 I bt_hci  : start_up
,08-18 02:38:47.624  4223  4236 I bt_vendor: alloc value 0xb3a17189
08-18 02:38:47.625  4223  4236 I bt_vendor: init
,08-18 02:38:47.625  4223  4236 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-18 02:38:47.625  4223  4236 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-18 02:38:47.734  4223  4236 D bt_hci  : start_up starting async portion
,08-18 02:38:47.735  4223  4243 I bt_hci  : event_finish_startup
,08-18 02:38:47.735  4223  4243 I bt_hci_h4: hal_open
08-18 02:38:47.735  4223  4243 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-18 02:38:47.746  4223  4243 I bt_userial_vendor: device fd = 51 open
,08-18 02:38:47.777  4223  4243 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 02:38:47.808  4223  4243 D bt_hwcfg: Chipset BCM4354A2
08-18 02:38:47.809  4223  4243 D bt_hwcfg: Target name = [BCM4354A2]
,08-18 02:38:47.810  4223  4243 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-18 02:38:48.506  4223  4243 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-18 02:38:48.508  4223  4243 D bt_hwcfg: Settlement delay -- 100 ms
08-18 02:38:48.508  4223  4243 I bt_hwcfg: Setting fw settlement delay to 100 
,08-18 02:38:48.624  4223  4243 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 02:38:48.626  4223  4243 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-18 02:38:48.655  4223  4243 I bt_hwcfg: vendor lib fwcfg completed
,08-18 02:38:48.656  4223  4243 I bt_vendor: firmware callback
,08-18 02:38:48.656  4223  4243 I bt_hci  : firmware_config_callback
,08-18 02:38:48.668  4223  4245 I bt_btu  : btu_task pending for preload complete event
,08-18 02:38:48.668  4223  4245 I bt_btu_task: Bluetooth chip preload is complete
,08-18 02:38:48.669  4223  4245 I bt_btu  : btu_task received preload complete event
,08-18 02:38:48.680  4223  4245 I         : BTE_InitTraceLevels -- TRC_HCI
,08-18 02:38:48.680  4223  4245 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-18 02:38:48.681  4223  4245 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-18 02:38:48.681  4223  4245 I         : BTE_InitTraceLevels -- TRC_AVDT
08-18 02:38:48.681  4223  4245 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-18 02:38:48.682  4223  4245 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 02:38:48.683  4223  4245 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-18 02:38:48.684  4223  4245 I         : BTE_InitTraceLevels -- TRC_BTM
08-18 02:38:48.684  4223  4245 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 02:38:48.684  4223  4245 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 02:38:48.685  4223  4245 I         : BTE_InitTraceLevels -- TRC_SDP
08-18 02:38:48.685  4223  4245 I         : BTE_InitTraceLevels -- TRC_GATT
08-18 02:38:48.685  4223  4245 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 02:38:48.686  4223  4245 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-18 02:38:48.686  4223  4245 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 02:38:48.820  4223  4245 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3994d9d
,08-18 02:38:48.820  4223  4245 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3994d9d 
,08-18 02:38:48.842  4223  4239 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-18 02:38:48.844  4223  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-18 02:38:48.845  4223  4239 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 02:38:48.850  4223  4239 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 02:38:48.854  4223  4239 D BluetoothAdapterProperties: Scan Mode:20
08-18 02:38:48.854  4223  4239 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-18 02:38:48.855  4223  4239 D bt_hci  : do_postload posting postload work item
08-18 02:38:48.856  4223  4243 I bt_hci  : event_postload
,08-18 02:38:48.856  4223  4243 I bt_vendor: sco_config_cb
,08-18 02:38:48.856  4223  4243 I bt_hci  : sco_config_callback postload finished.
08-18 02:38:48.860  4223  4239 D bt_bte_conf: Device ID record 1 : primary
08-18 02:38:48.861  4223  4239 D bt_bte_conf:   vendorId            = 000f
08-18 02:38:48.862  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:48.861  4223  4239 D bt_bte_conf:   vendorIdSource      = 0001
08-18 02:38:48.863  4223  4239 D bt_bte_conf:   product             = 1200
08-18 02:38:48.863  4223  4239 D bt_bte_conf:   version             = 1436
08-18 02:38:48.863  4223  4239 D bt_bte_conf:   clientExecutableURL = 
08-18 02:38:48.863  4223  4239 D bt_bte_conf:   serviceDescription  = 
08-18 02:38:48.863  4223  4239 D bt_bte_conf:   documentationURL    = 
08-18 02:38:48.863  4223  4239 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-18 02:38:48.864  4223  4236 D bt_stack_manager: event_start_up_stack finished
08-18 02:38:48.865  4223  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-18 02:38:48.865  4223  4235 D BluetoothAdapterProperties: Setting state to 15
08-18 02:38:48.865  4223  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-18 02:38:48.866  4223  4243 I bt_vendor: low_power_mode_cb
08-18 02:38:48.866  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:48.866  4223  4235 I BluetoothAdapterState: Entering BleOnState
,08-18 02:38:48.870  4223  4235 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-18 02:38:48.870  4223  4235 D BluetoothAdapterProperties: Setting state to 11
08-18 02:38:48.870  4223  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-18 02:38:48.878  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:48.882  4223  4223 D HeadsetService: Received start request. Starting profile...
,08-18 02:38:48.884  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:48.886  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:48.886  4223  4223 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-18 02:38:48.886  4223  4223 D HeadsetStateMachine: make
,08-18 02:38:48.896  4223  4235 I BluetoothAdapterState: Entering PendingCommandState
,08-18 02:38:48.902  4223  4223 D HeadsetStateMachine: max_hf_connections = 1
,08-18 02:38:48.902  4223  4223 I bt_bluedroid: get_profile_interface handsfree
,08-18 02:38:48.903  4223  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-18 02:38:48.903  4223  4239 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-18 02:38:48.911  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:38:48.912  4223  4223 D A2dpService: Received start request. Starting profile...
,08-18 02:38:48.914  4223  4223 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-18 02:38:48.916  4223  4223 I bt_bluedroid: get_profile_interface avrcp
,08-18 02:38:48.926  4223  4223 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-18 02:38:48.926  4223  4223 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 02:38:48.926  4223  4223 D A2dpStateMachine: make
,08-18 02:38:48.927  4223  4223 I bt_bluedroid: get_profile_interface a2dp
,08-18 02:38:48.928  4223  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-18 02:38:48.932  4223  4223 I BluetoothHidServiceJni: classInitNative: succeeds
,08-18 02:38:48.933  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:48.934  4223  4223 D HidService: Received start request. Starting profile...
,08-18 02:38:48.934  4223  4223 I bt_bluedroid: get_profile_interface hidhost
,08-18 02:38:48.932  4223  4253 D A2dpStateMachine: Enter Disconnected: -2
08-18 02:38:48.935  4223  4239 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39763e5
08-18 02:38:48.935  4223  4223 D HidService: setHidService(): set to: null
08-18 02:38:48.935  4223  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-18 02:38:48.935  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 02:38:48.935  4223  4223 I BluetoothHealthServiceJni: classInitNative: succeeds
08-18 02:38:48.936  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:48.937  4223  4223 D HealthService: Received start request. Starting profile...
,08-18 02:38:48.940  4223  4223 I bt_bluedroid: get_profile_interface health
,08-18 02:38:48.940  4223  4223 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-18 02:38:48.941  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:48.941  4223  4223 D PanService: Received start request. Starting profile...
08-18 02:38:48.941  4223  4223 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 02:38:48.941  4223  4223 I bt_bluedroid: get_profile_interface pan
08-18 02:38:48.943  4223  4239 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-18 02:38:48.946  4223  4223 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
08-18 02:38:48.947  4223  4223 D BluetoothMapService: Received start request. Starting profile...
08-18 02:38:48.947  4223  4223 D BluetoothMapService: start()
,08-18 02:38:48.950  4223  4223 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-18 02:38:48.951  4223  4223 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-18 02:38:48.952  4223  4223 D BluetoothMapAppObserver: createReceiver()
,08-18 02:38:48.953  4223  4223 D BluetoothMapAppObserver: initObservers()
,08-18 02:38:48.953  4223  4223 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-18 02:38:48.963  4223  4223 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:48.963  4223  4223 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:48.963  4223  4223 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:48.964  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:48.966  4223  4223 V BluetoothAdapterState: isTurningOff()=false
,08-18 02:38:48.966  4223  4223 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:48.967  4223  4251 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isTurningOn()=true
,08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:48.967  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:48.968  4223  4223 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:48.968  4223  4223 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:48.968  4223  4223 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 02:38:48.968  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 02:38:48.969  4223  4223 V BluetoothAdapterState: isTurningOff()=false
08-18 02:38:48.969  4223  4223 V BluetoothAdapterState: isTurningOn()=true
08-18 02:38:48.969  4223  4223 V BluetoothAdapterState: isBleTurningOn()=false
08-18 02:38:48.969  4223  4223 V BluetoothAdapterState: isBleTurningOff()=false
08-18 02:38:48.970  4223  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-18 02:38:48.970  4223  4235 D BluetoothAdapterProperties: ScanMode =  20
08-18 02:38:48.970  4223  4235 D BluetoothAdapterProperties: State =  11
08-18 02:38:48.971  4223  4239 D BluetoothAdapterProperties: Scan Mode:21
08-18 02:38:48.971  4223  4235 D BluetoothAdapterProperties: Setting state to 12
08-18 02:38:48.971  4223  4239 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-18 02:38:48.971  4223  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 02:38:48.972  4223  4235 I BluetoothAdapterState: Entering OnState
08-18 02:38:48.972  1348  2157 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 02:38:48.974  3918  3928 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 02:38:48.975  1348  1348 D BluetoothInputDevice: Proxy object connected
08-18 02:38:48.975  1348  1348 D HidProfile: Bluetooth service connected
08-18 02:38:48.976  3918  3918 D BluetoothInputDevice: Proxy object connected
,08-18 02:38:48.976  3918  3918 D HidProfile: Bluetooth service connected
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:48.977  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 02:38:48.977   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:48.977  1348  1361 D BluetoothPan: onBluetoothStateChange on: true
08-18 02:38:48.979  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 02:38:48.980  3918  3928 D BluetoothPan: onBluetoothStateChange on: true
08-18 02:38:48.980  4223  4223 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-18 02:38:48.981  4223  4223 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-18 02:38:48.983  4223  4223 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 02:38:48.983   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:48.983  3918  3929 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:48.984  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:48.985  1348  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 02:38:48.985  4223  4223 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 02:38:48.987  4223  4223 D ObexServerSockets: Succeed to create listening sockets 
,08-18 02:38:48.987  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 02:38:48.987  4223  4223 D ObexServerSockets0: startAccept()
08-18 02:38:48.987  4223  4223 D ObexServerSockets0: prepareForNewConnect()
,08-18 02:38:48.988  3918  4259 D BluetoothPbap: onBluetoothStateChange: up=true
,08-18 02:38:48.989  4223  4223 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-18 02:38:48.989  4223  4223 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-18 02:38:48.990  4223  4261 D ObexServerSockets0: Accepting socket connection...
,08-18 02:38:48.990  4223  4262 D ObexServerSockets0: Accepting socket connection...
08-18 02:38:48.990  1348  2157 D BluetoothMap: onBluetoothStateChange: up=true
,08-18 02:38:48.991  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 02:38:48.991  1348  1348 D PanProfile: Bluetooth service connected
08-18 02:38:48.991   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:48.992  1348  1348 D BluetoothA2dp: Proxy object connected
08-18 02:38:48.992  1348  2170 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 02:38:48.992  3918  4259 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:48.992  1921  2080 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 02:38:48.993   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 02:38:48.993   872   872 D BluetoothA2dp: Proxy object connected
08-18 02:38:48.993  3918  3928 D BluetoothMap: onBluetoothStateChange: up=true
08-18 02:38:48.994  1348  1348 D BluetoothMap: Proxy object connected
,08-18 02:38:48.994  1348  1348 D MapProfile: Bluetooth service connected
08-18 02:38:48.994  1348  1348 D BluetoothMap: getConnectedDevices()
08-18 02:38:48.995  1348  2157 D BluetoothPbap: onBluetoothStateChange: up=true
,08-18 02:38:48.996  3918  3918 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 02:38:48.996  3918  3918 D PanProfile: Bluetooth service connected
08-18 02:38:48.996  3918  3918 D BluetoothA2dp: Proxy object connected
,08-18 02:38:48.997   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-18 02:38:48.999  4223  4223 D BluetoothMapService: onReceive
08-18 02:38:48.999  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:38:49.000  4223  4223 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 02:38:49.000  4223  4223 D BluetoothMapService: STATE_ON
08-18 02:38:49.000  3918  3918 D BluetoothMap: Proxy object connected
,08-18 02:38:49.001  3918  3918 D MapProfile: Bluetooth service connected
08-18 02:38:49.001  3918  3918 D BluetoothMap: getConnectedDevices()
08-18 02:38:49.001  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:49.005  3918  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 02:38:49.010  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 02:38:49.010  3918  3918 D DockEventReceiver: finishStartingService: stopping service
,08-18 02:38:49.018  3918  3918 D BluetoothPbap: Proxy object connected
,08-18 02:38:49.018  3918  3918 D PbapServerProfile: Bluetooth service connected
,08-18 02:38:49.023  1348  1348 D BluetoothPbap: Proxy object connected
08-18 02:38:49.023  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-18 02:38:49.026  4223  4223 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 02:38:49.026  4223  4223 D ObexServerSockets0: prepareForNewConnect()
,08-18 02:38:49.028  4223  4266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 02:38:49.045  4223  4270 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 02:38:49.046  4223  4270 I BtOppRfcommListener: Accept thread started.
,08-18 02:38:49.079  1921  2171 D BluetoothHeadset: Proxy object connected
08-18 02:38:49.080   872   872 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.080  1348  2157 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.080  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-18 02:38:49.080   872   872 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.081  3918  4259 D BluetoothHeadset: Proxy object connected
08-18 02:38:49.081   872   872 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.082  3918  3918 D HeadsetProfile: Bluetooth service connected
08-18 02:38:49.083   872   889 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.092   872   889 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.093  1348  1368 D BluetoothHeadset: Proxy object connected
08-18 02:38:49.093  1348  1348 D HeadsetProfile: Bluetooth service connected
08-18 02:38:49.093  3918  3929 D BluetoothHeadset: Proxy object connected
08-18 02:38:49.094  1921  1942 D BluetoothHeadset: Proxy object connected
,08-18 02:38:49.094  3918  3918 D HeadsetProfile: Bluetooth service connected
,08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:52.329  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:52.336  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 02:38:52.337  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:38:52.338  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4112e6 removed from the list
08-18 02:38:52.338  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 02:38:52.339  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:38:52.339  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:38:52.343  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:38:52.344  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95b5027 added. We now have 4 listener(s)
08-18 02:38:52.344  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:38:52.348   872  1940 D WifiService: setWifiEnabled: false pid=3819, uid=10000
,08-18 02:38:52.349   872  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 02:38:53.584  1855  1888 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-18 02:38:53.584  1855  1888 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-18 02:38:53.634  1509  1509 I ConfigService: onCreate
,08-18 02:38:57.360  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:38:57.361   872  3139 D WifiService: setWifiEnabled: true pid=3819, uid=10000
08-18 02:38:57.361   872  3139 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 02:38:57.378   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:57.396  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:57.402  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 02:38:57.410  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 02:38:57.416  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 02:38:57.423   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-18 02:38:57.424   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-18 02:38:57.425   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-18 02:38:57.426   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-18 02:38:57.426   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-18 02:38:57.426   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-18 02:38:57.426   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-18 02:38:57.439   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-18 02:38:57.439   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-18 02:38:57.442   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:57.492   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-18 02:38:57.492   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-18 02:38:57.498   872  1303 E native  : do suspend true
,08-18 02:38:57.515   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-18 02:38:57.516   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-18 02:38:57.529   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:38:58.699  1509  1509 I ConfigService: onDestroy
,08-18 02:38:58.838   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-18 02:38:58.985   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.25 rxSuccessRate=8.94 delta 1000 -> 994
,08-18 02:38:58.987   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-18 02:38:58.987   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:59.004   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-18 02:38:59.077   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-18 02:38:59.081  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-18 02:38:59.515  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 02:38:59.560  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-18 02:38:59.561  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-18 02:38:59.564   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 02:38:59.575   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 02:38:59.575   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-18 02:38:59.575   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:59.597   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 02:38:59.614   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:59.616   872  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,08-18 02:38:59.635   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-18 02:38:59.686   872  4280 D DhcpClient: Receive thread started
,08-18 02:38:59.783   872  1303 E native  : do suspend false
,08-18 02:38:59.809   872  1838 D DhcpClient: Broadcasting DHCPDISCOVER
,08-18 02:38:59.823   872  4280 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-18 02:38:59.824   872  1838 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-18 02:38:59.829   872  1838 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-18 02:38:59.844   872  4280 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-18 02:38:59.845   872  1838 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-18 02:38:59.851   373   871 D CommandListener: Setting iface cfg
,08-18 02:38:59.864   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-18 02:38:59.864   872  1838 D DhcpClient: Scheduling renewal in 86399s
,08-18 02:38:59.868   872  1303 E native  : do suspend true
,08-18 02:38:59.886   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-18 02:38:59.887   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-18 02:38:59.888   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-18 02:38:59.892   872  1305 D ConnectivityService: Adding iface wlan0 to network 102
08-18 02:38:59.893   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-18 02:38:59.948   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-18 02:38:59.949   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-18 02:38:59.953   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-18 02:38:59.958   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-18 02:38:59.963   872  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-18 02:38:59.983   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-18 02:38:59.995   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-18 02:38:59.995   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-18 02:38:59.996   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-18 02:38:59.996   872  1305 D ConnectivityService:    accepting network in place of null
,08-18 02:38:59.996   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-18 02:38:59.997   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-18 02:38:59.998   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 02:39:00.003   872  4279 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 02:39:00.069   872  4278 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:816::200e
,08-18 02:39:00.073   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 02:39:00.107   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 02:39:00.119   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-18 02:39:00.120   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:39:00.128   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-18 02:39:00.132   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-18 02:39:00.136   872  4278 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 00:39:00 GMT], X-Android-Received-Millis=[1471480740135], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471480740110]}
,08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:00.148  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:00.149   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-18 02:39:00.150   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-18 02:39:00.150   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-18 02:39:00.151  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-18 02:39:00.156  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:00.158   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:00.161  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:00.164  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:00.168  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-18 02:39:00.174  1733  1733 D SystemUpdateService: onCreate
,08-18 02:39:00.178  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-18 02:39:00.198  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-18 02:39:00.207  1733  2403 I iu.UploadsManager: num queued entries: 0
,08-18 02:39:00.208  1733  2403 I iu.UploadsManager: num updated entries: 0
08-18 02:39:00.209  1733  4290 I SystemUpdateService: active receiver: enabled
,08-18 02:39:00.210  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 02:39:00.211  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 02:39:00.213  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 02:39:00.229  1733  2403 I iu.SyncManager: NEXT; no task
,08-18 02:39:00.234  1733  4292 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-18 02:39:00.234  1733  4292 W BaseAppContext: Using Auth Proxy for data requests.
,08-18 02:39:00.235  3998  3998 D SprintDMHelper: simOperator: 
08-18 02:39:00.235  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 02:39:00.245  1733  4292 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-18 02:39:00.247  1733  4290 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-18 02:39:00.266  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:39:00.273  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:39:00.293  1733  4290 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-18 02:39:00.293  1733  4290 I SystemUpdateService: now status is 0 (complete)
08-18 02:39:00.293  1733  4290 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-18 02:39:00.293  1733  4290 I SystemUpdateService: file has been verified
08-18 02:39:00.293  1733  4290 I SystemUpdateService: OTA package size = 12249756
,08-18 02:39:00.325  1733  4290 I SystemUpdateService: showing system update notification
,08-18 02:39:00.353  1509  3591 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-18 02:39:00.353  1509  3591 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-18 02:39:00.353  1509  3591 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:39:00.353  1509  3591 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-18 02:39:00.354  1733  1733 D SystemUpdateService: onDestroy
,08-18 02:39:00.392  1733  4292 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-18 02:39:00.405  3969  4295 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-18 02:39:01.116   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:02.390  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:02.398  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:02.399  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:02.399  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95b5027 removed from the list
08-18 02:39:02.400  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:39:02.401  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:02.401  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:02.417  3819  4301 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-18 02:39:02.418  3819  4301 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-18 02:39:05.426  3819  4302 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-18 02:39:05.427  3819  4301 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-18 02:39:05.428  3819  4302 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-18 02:39:05.428  3819  4301 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-18 02:39:05.429  3819  4301 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-18 02:39:05.430  3819  4302 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-18 02:39:05.430  3819  4301 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-18 02:39:05.431  3819  4302 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-18 02:39:05.434  3819  4301 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-18 02:39:05.436  3819  4304 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: OutgoingSocketThread/Sender)
08-18 02:39:05.436  3819  4305 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
08-18 02:39:05.437  3819  4302 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-18 02:39:05.439  3819  4306 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Receiver)
08-18 02:39:05.440  3819  4306 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: OutgoingSocketThread/Receiver)
,08-18 02:39:05.440  3819  4306 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-18 02:39:05.440  3819  4306 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-18 02:39:05.442  3819  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
08-18 02:39:05.442  3819  4307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
08-18 02:39:05.442  3819  4307 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-18 02:39:05.442  3819  4307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-18 02:39:08.003   872  1305 D ConnectivityService: handlePromptUnvalidated 102
,08-18 02:39:08.425  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-18 02:39:08.429  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-18 02:39:08.435  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@db7675c Bundle[{}]
,08-18 02:39:08.436  3819  3867 I io.jxcore.node.LifeCycleMonitor: start: OK
08-18 02:39:08.436  3819  3867 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-18 02:39:08.436  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-18 02:39:08.437  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-18 02:39:08.438  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-18 02:39:08.439  3819  3867 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-18 02:39:08.444  3819  3867 I System.out: Running OutgoingSocketThread
,08-18 02:39:08.448  3819  4308 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-18 02:39:08.448  3819  4308 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-18 02:39:11.458  3819  4308 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-18 02:39:11.459  3819  4308 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-18 02:39:11.459  3819  4309 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-18 02:39:11.459  3819  4308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-18 02:39:11.459  3819  4309 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-18 02:39:11.460  3819  4309 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
08-18 02:39:11.461  3819  4308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-18 02:39:11.462  3819  4309 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-18 02:39:11.463  3819  4308 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-18 02:39:11.468  3819  4312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
08-18 02:39:11.469  3819  4309 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-18 02:39:11.470  3819  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: OutgoingSocketThread/Sender)
,08-18 02:39:11.474  3819  4313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Receiver)
,08-18 02:39:11.475  3819  4314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Receiver)
,08-18 02:39:11.475  3819  4313 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: OutgoingSocketThread/Receiver)
,08-18 02:39:11.476  3819  4314 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: IncomingSocketThread/Receiver)
,08-18 02:39:11.476  3819  4313 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-18 02:39:11.476  3819  4314 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-18 02:39:11.476  3819  4314 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-18 02:39:11.476  3819  4313 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-18 02:39:14.459  3819  3867 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,08-18 02:39:14.462  3819  3867 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-18 02:39:14.463  3819  3867 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-18 02:39:14.469  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 02:39:14.469  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37732d4 added. We now have 3 listener(s)
,08-18 02:39:14.472  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 02:39:14.472  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:39:14.472  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:39:14.472  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:39:14.472  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f356c7d added. We now have 4 listener(s)
08-18 02:39:14.472  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:39:14.473  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 02:39:14.476  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:14.483  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:14.487  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:14.488  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:39:14.489  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 02:39:14.490  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:39:14.490  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:39:14.490  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:39:14.490  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:14.490  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-18 02:39:14.491  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 02:39:14.491  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37732d4 removed from the list
08-18 02:39:14.491  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:14.491  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f356c7d removed from the list
,08-18 02:39:14.494  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:14.501  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:14.501  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:39:14.502  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:14.503  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:14.503  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:14.505  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:14.505  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:14.505  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:14.505  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f356c7d not in the list
,08-18 02:39:14.505  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:14.505  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:14.506  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:14.506  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:14.506  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:14.506  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f356c7d not in the list
08-18 02:39:14.507  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:39:14.507  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:14.507  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:14.507  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37732d4 not in the list
08-18 02:39:14.508  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 02:39:14.508  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@522c7c3 added. We now have 3 listener(s)
,08-18 02:39:14.510  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 02:39:14.510  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:39:14.511  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:39:14.511  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:39:14.511  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7ea840 added. We now have 4 listener(s)
08-18 02:39:14.511  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:39:14.512  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:39:14.518  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:14.529  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:14.532  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:14.532  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 02:39:14.533  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 02:39:14.533  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-18 02:39:14.533  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 02:39:14.533  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:14.533  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 02:39:14.538  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 02:39:14.538  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 02:39:14.540  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:14.548  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:14.549  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 02:39:14.551  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 02:39:14.551  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 02:39:14.559  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 02:39:14.559  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 02:39:14.560  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 02:39:14.561  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:39:14.566  4223  4234 D BtGatt.GattService: registerClient() - UUID=d3ceef88-e2e9-4fd6-8876-9100e5a1a0e6
,08-18 02:39:14.567  4223  4239 D BtGatt.GattService: onClientRegistered() - UUID=d3ceef88-e2e9-4fd6-8876-9100e5a1a0e6, clientIf=5
,08-18 02:39:14.568  3819  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 02:39:14.571  4223  4233 D BtGatt.GattService: start scan with filters
,08-18 02:39:14.580  4223  4242 D BtGatt.ScanManager: handling starting scan
08-18 02:39:14.580  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 02:39:14.580  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 02:39:14.581  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 02:39:14.581  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 02:39:14.583  4223  4242 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ee2f830
,08-18 02:39:14.586  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:39:14.586  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 02:39:14.586  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:39:14.590  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 02:39:14.596  3819  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-18 02:39:14.596  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 02:39:14.596  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 02:39:14.596  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:14.596  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-18 02:39:14.596  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 02:39:14.596  4223  4239 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 02:39:14.596  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 02:39:14.597  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:14.597  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 02:39:14.597  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 02:39:14.597  4223  4242 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-18 02:39:14.597  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 02:39:14.598  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-18 02:39:14.600  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:39:14.602  4223  4233 D BtGatt.GattService: stopScan() - queue size =1
,08-18 02:39:14.603  4223  4258 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-18 02:39:14.604  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 02:39:14.605  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 02:39:14.605  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 02:39:14.605  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 02:39:14.606  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 02:39:14.609  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:39:14.609  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 02:39:14.609  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 02:39:14.609  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 02:39:14.610  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:39:14.613  4223  4239 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 02:39:14.613  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:14.613  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 02:39:14.614  4223  4242 D BtGatt.ScanManager: Starting BLE batch scan
08-18 02:39:14.614  4223  4242 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 02:39:14.614  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:39:14.614  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:39:14.627  4223  4239 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 02:39:14.627  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:14.634  4223  4239 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 02:39:14.634  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:14.647  4223  4239 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 02:39:14.647  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:14.648  4223  4242 D BtGatt.ScanManager: stopping BLe Batch
,08-18 02:39:14.664  4223  4239 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 02:39:14.664  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:14.665  4223  4242 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:39:14.683  4223  4239 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 02:39:14.683  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:15.115  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 02:39:15.116  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:39:15.116  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 02:39:17.614  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:39:17.614  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:39:17.615  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 02:39:17.615  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:39:17.616  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:17.616  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:39:17.617  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 02:39:17.617  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@522c7c3 removed from the list
,08-18 02:39:17.618  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:17.618  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7ea840 removed from the list
,08-18 02:39:17.619  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:39:17.619  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:17.623  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:17.623  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:17.626  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 02:39:17.627  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:17.627  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:17.627  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7ea840 not in the list
08-18 02:39:17.628  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:17.628  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:17.631  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:17.631  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:17.632  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:17.632  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7ea840 not in the list
08-18 02:39:17.632  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:39:17.633  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:17.633  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:17.633  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@522c7c3 not in the list
,08-18 02:39:17.635  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 02:39:17.635  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76aae35 added. We now have 3 listener(s)
,08-18 02:39:17.641  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:39:17.641  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:39:17.641  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 02:39:17.642  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:39:17.642  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7e82ca added. We now have 4 listener(s)
08-18 02:39:17.643  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 02:39:17.644  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:39:17.651  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:17.660  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:17.664  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:17.664  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:39:17.665  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-18 02:39:17.667  3819  3867 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-18 02:39:17.667  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-18 02:39:17.671  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:17.671  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-18 02:39:17.672  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-18 02:39:17.673  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-18 02:39:17.673  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:17.677  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:17.676  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-18 02:39:17.678  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-18 02:39:17.679  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-18 02:39:17.679  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-18 02:39:17.679  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-18 02:39:17.679  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-18 02:39:17.680  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:17.680  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 02:39:17.681  3819  4315 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 02:39:17.685  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 02:39:17.685  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 02:39:17.686  3819  4315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-18 02:39:17.693  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 02:39:17.694  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-18 02:39:17.694  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 02:39:17.699  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-18 02:39:17.699  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 02:39:17.700  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-18 02:39:17.701  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-18 02:39:17.701  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-18 02:39:17.701  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-18 02:39:17.702  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:39:17.708  4223  4260 D BtGatt.GattService: registerClient() - UUID=a7cde671-5f29-4e8e-a659-aeae9a7c7ac8
,08-18 02:39:17.709  4223  4239 D BtGatt.GattService: onClientRegistered() - UUID=a7cde671-5f29-4e8e-a659-aeae9a7c7ac8, clientIf=5
,08-18 02:39:17.711  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-18 02:39:17.713  4223  4241 D BtGatt.AdvertiseManager: message : 0
,08-18 02:39:17.717  4223  4241 D BtGatt.AdvertiseManager: starting multi advertising
,08-18 02:39:17.740  4223  4239 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-18 02:39:17.759  4223  4239 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-18 02:39:17.762  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-18 02:39:17.763  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 02:39:17.770  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 02:39:17.774  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-18 02:39:17.775  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-18 02:39:17.776  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-18 02:39:17.776  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-18 02:39:17.776  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-18 02:39:17.777  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-18 02:39:17.784  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-18 02:39:17.789  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-18 02:39:17.789  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-18 02:39:18.291  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-18 02:39:18.291  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-18 02:39:18.292  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 02:39:20.785  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:39:20.786  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-18 02:39:20.786  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-18 02:39:20.787  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-18 02:39:20.787  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-18 02:39:20.787  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-18 02:39:20.792  3819  4315 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-18 02:39:20.792  3819  4315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-18 02:39:20.792  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-18 02:39:20.792  3819  4315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-18 02:39:20.793  3819  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-18 02:39:20.793  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-18 02:39:20.793  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-18 02:39:20.794  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-18 02:39:20.794  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 02:39:20.796  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 02:39:20.796  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-18 02:39:20.796  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-18 02:39:20.799  3819  3867 D BluetoothAdapter: STATE_ON
08-18 02:39:20.799  3819  3867 D BluetoothLeScanner: could not find callback wrapper
08-18 02:39:20.800  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-18 02:39:20.800  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-18 02:39:20.803  4223  4241 D BtGatt.AdvertiseManager: message : 1
08-18 02:39:20.804  4223  4241 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-18 02:39:20.813  4223  4239 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-18 02:39:20.813  4223  4239 D BtGatt.GattService: Client app is not null!
,08-18 02:39:20.814  4223  4258 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-18 02:39:20.815  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 02:39:20.815  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-18 02:39:20.815  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-18 02:39:20.815  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-18 02:39:20.815  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-18 02:39:20.816  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:39:20.817  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 02:39:20.817  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 02:39:20.818  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:39:20.821  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:39:20.821  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:20.822  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:39:20.822  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:39:20.822  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 02:39:20.822  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 02:39:20.822  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 02:39:20.822  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76aae35 removed from the list
08-18 02:39:20.823  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:20.823  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7e82ca removed from the list
08-18 02:39:20.823  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:39:20.823  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:20.825  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:20.828  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:20.830  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 02:39:20.830  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:20.830  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:20.830  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7e82ca not in the list
08-18 02:39:20.831  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:20.831  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:20.832  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 02:39:20.832  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:20.832  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:20.833  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7e82ca not in the list
,08-18 02:39:20.833  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:39:20.833  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:20.833  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:20.833  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76aae35 not in the list
08-18 02:39:20.834  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 02:39:20.835  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea29117 added. We now have 3 listener(s)
,08-18 02:39:20.838  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:39:20.838  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 02:39:20.838  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:39:20.838  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:39:20.838  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@236f904 added. We now have 4 listener(s)
08-18 02:39:20.839  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:39:20.839  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:39:20.843  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:20.849  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:20.851  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:20.852  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:39:20.852  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 02:39:20.853  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 02:39:20.853  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 02:39:20.853  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 02:39:20.853  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 02:39:20.856  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:20.859  3819  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 02:39:20.859  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 02:39:20.860  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:20.864  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 02:39:20.865  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-18 02:39:20.866  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 02:39:20.871  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 02:39:20.872  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 02:39:20.872  3819  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 02:39:20.874  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:39:20.878  4223  4234 D BtGatt.GattService: registerClient() - UUID=b90b8020-84cf-4cae-b955-a3eb5bf84b93
,08-18 02:39:20.879  4223  4239 D BtGatt.GattService: onClientRegistered() - UUID=b90b8020-84cf-4cae-b955-a3eb5bf84b93, clientIf=5
,08-18 02:39:20.880  3819  3830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 02:39:20.881  4223  4260 D BtGatt.GattService: start scan with filters
,08-18 02:39:20.886  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 02:39:20.886  4223  4242 D BtGatt.ScanManager: handling starting scan
08-18 02:39:20.886  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 02:39:20.886  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 02:39:20.886  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 02:39:20.894  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:39:20.895  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 02:39:20.895  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 02:39:20.900  4223  4239 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-18 02:39:20.900  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:20.900  4223  4242 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 02:39:20.902  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 02:39:20.912  4223  4239 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-18 02:39:20.912  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:20.912  4223  4242 D BtGatt.ScanManager: Starting BLE batch scan
08-18 02:39:20.912  4223  4242 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 02:39:20.927  4223  4239 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-18 02:39:20.928  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:20.937  4223  4239 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 02:39:20.937  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:21.324  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 02:39:21.395  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-18 02:39:21.396  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 02:39:21.396  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 02:39:22.444  4223  4223 D BtGatt.ScanManager: awakened up at time 239026
,08-18 02:39:22.447  4223  4242 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:39:22.483  4223  4239 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-18 02:39:22.483  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:22.484  4223  4239 D BtGatt.GattService: current time is 239065674279
,08-18 02:39:22.485  4223  4239 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -94, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-18 02:39:22.490  4223  4239 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-18 02:39:22.494  4223  4239 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-18 02:39:22.496  4223  4239 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-18 02:39:23.917  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:39:23.917  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:39:23.918  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 02:39:23.918  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.919  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-18 02:39:23.919  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-18 02:39:23.919  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 02:39:23.919  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 02:39:23.920  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 02:39:23.920  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-18 02:39:23.920  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 02:39:23.923  3819  3867 D BluetoothAdapter: STATE_ON
,08-18 02:39:23.924  4223  4260 D BtGatt.GattService: stopScan() - queue size =1
08-18 02:39:23.927  4223  4233 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 02:39:23.929  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-18 02:39:23.929  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 02:39:23.929  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-18 02:39:23.930  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 02:39:23.930  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 02:39:23.935  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 02:39:23.936  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 02:39:23.936  3819  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 02:39:23.937  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 02:39:23.938  4223  4223 D BtGatt.ScanManager: awakened up at time 240519
08-18 02:39:23.939  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 02:39:23.942  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 02:39:23.943  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 02:39:23.943  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 02:39:23.944  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:39:23.944  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.945  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:39:23.945  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 02:39:23.945  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea29117 removed from the list
08-18 02:39:23.946  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:23.946  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@236f904 removed from the list
08-18 02:39:23.946  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:39:23.947  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:23.948  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.949  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:23.951  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:23.951  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 02:39:23.951  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:23.951  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@236f904 not in the list
08-18 02:39:23.951  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.951  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:23.952  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:23.952  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:23.952  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:23.952  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@236f904 not in the list
08-18 02:39:23.952  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:39:23.953  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.953  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:23.953  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea29117 not in the list
08-18 02:39:23.953  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 02:39:23.954  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2510ce9 added. We now have 3 listener(s)
08-18 02:39:23.956  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:39:23.956  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:39:23.956  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:39:23.956  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 02:39:23.956  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7ad6e added. We now have 4 listener(s)
08-18 02:39:23.956  4223  4239 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 02:39:23.957  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:39:23.957  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:23.957  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 02:39:23.957  4223  4242 D BtGatt.ScanManager: stopping BLe Batch
,08-18 02:39:23.960  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:39:23.965  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:39:23.967  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:39:23.968  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 02:39:23.970  3819  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 02:39:23.970  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 02:39:23.970  4223  4239 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 02:39:23.970  3819  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 02:39:23.970  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 02:39:23.970  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 02:39:23.970  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:23.971  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 02:39:23.971  4223  4242 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 02:39:23.971  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-18 02:39:23.971  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2510ce9 removed from the list
08-18 02:39:23.971  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:23.971  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7ad6e removed from the list
08-18 02:39:23.972  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 02:39:23.975  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:39:23.975  3819  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-18 02:39:23.975  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:23.976  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.976  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 02:39:23.977  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:23.977  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:23.977  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 02:39:23.977  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7ad6e not in the list
08-18 02:39:23.977  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 02:39:23.977  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:23.978  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 02:39:23.978  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 02:39:23.978  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 02:39:23.978  3819  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7ad6e not in the list
08-18 02:39:23.978  3819  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 02:39:23.979  3819  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 02:39:23.979  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 02:39:23.979  3819  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2510ce9 not in the list
,08-18 02:39:23.980  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-18 02:39:23.980  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-18 02:39:23.980  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-18 02:39:23.980  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 02:39:23.980  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-18 02:39:23.980  3819  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 02:39:23.984  4223  4239 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-18 02:39:23.985  4223  4239 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 02:39:23.985  4223  4239 D BtGatt.GattService: current time is 240566532098
08-18 02:39:23.985  4223  4239 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-18 02:39:23.985  4223  4239 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-18 02:39:24.445  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 02:39:25.995  3819  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,08-18 02:39:27.993  3819  3867 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 458
,08-18 02:39:27.993  3819  3867 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 458, name: My test thread name)
,08-18 02:39:28.000  3819  4318 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,08-18 02:39:28.000  3819  4318 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: My test thread name)
08-18 02:39:28.001  3819  4318 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-18 02:39:28.004  3819  3867 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-18 02:39:28.013  3819  4319 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,08-18 02:39:28.014  3819  4319 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 463, thread name: My test thread name): Test exception.
08-18 02:39:28.014  3819  4319 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-18 02:39:28.022  3819  3867 I jxcore-log: Total number of executed tests:  82
08-18 02:39:28.022  3819  3867 I jxcore-log: 
,08-18 02:39:28.023  3819  3867 I jxcore-log: Number of passed tests:  82
08-18 02:39:28.023  3819  3867 I jxcore-log: 
08-18 02:39:28.023  3819  3867 I jxcore-log: Number of failed tests:  0
08-18 02:39:28.023  3819  3867 I jxcore-log: 
08-18 02:39:28.024  3819  3867 I jxcore-log: Number of ignored tests:  0
08-18 02:39:28.024  3819  3867 I jxcore-log: 
,08-18 02:39:28.026  3819  3867 I jxcore-log: Total duration:  101470
08-18 02:39:28.026  3819  3867 I jxcore-log: 
,08-18 02:39:28.034  3819  3867 I jxcore-log: Unit Test app is loaded
08-18 02:39:28.034  3819  3867 I jxcore-log: 
,08-18 02:39:28.052  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.052  3819  3867 I jxcore-log: 
,08-18 02:39:28.057  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.057  3819  3867 I jxcore-log: 
,08-18 02:39:28.058  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.058  3819  3867 I jxcore-log: 
,08-18 02:39:28.059  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.059  3819  3867 I jxcore-log: 
08-18 02:39:28.060  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-18 02:39:28.060  3819  3867 I jxcore-log: 
08-18 02:39:28.062  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 02:39:28.062  3819  3867 I jxcore-log: 
08-18 02:39:28.064  3819  3819 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-18 02:39:28.065  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.065  3819  3867 I jxcore-log: 
,08-18 02:39:28.067  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.067  3819  3867 I jxcore-log: 
08-18 02:39:28.068  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-18 02:39:28.068  3819  3867 I jxcore-log: 
,08-18 02:39:28.069  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 02:39:28.069  3819  3867 I jxcore-log: 
08-18 02:39:28.070  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 02:39:28.070  3819  3867 I jxcore-log: 
,08-18 02:39:28.070  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.070  3819  3867 I jxcore-log: 
08-18 02:39:28.071  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.071  3819  3867 I jxcore-log: 
,08-18 02:39:28.072  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.072  3819  3867 I jxcore-log: 
08-18 02:39:28.073  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.073  3819  3867 I jxcore-log: 
,08-18 02:39:28.074  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.074  3819  3867 I jxcore-log: 
08-18 02:39:28.075  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.075  3819  3867 I jxcore-log: 
,08-18 02:39:28.076  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.076  3819  3867 I jxcore-log: 
08-18 02:39:28.077  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.077  3819  3867 I jxcore-log: 
08-18 02:39:28.077  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.077  3819  3867 I jxcore-log: 
,08-18 02:39:28.078  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.078  3819  3867 I jxcore-log: 
08-18 02:39:28.079  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.079  3819  3867 I jxcore-log: 
,08-18 02:39:28.080  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.080  3819  3867 I jxcore-log: 
08-18 02:39:28.081  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.081  3819  3867 I jxcore-log: 
,08-18 02:39:28.081  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.081  3819  3867 I jxcore-log: 
08-18 02:39:28.082  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.082  3819  3867 I jxcore-log: 
,08-18 02:39:28.083  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.083  3819  3867 I jxcore-log: 
08-18 02:39:28.084  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.084  3819  3867 I jxcore-log: 
08-18 02:39:28.085  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.085  3819  3867 I jxcore-log: 
,08-18 02:39:28.085  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.085  3819  3867 I jxcore-log: 
08-18 02:39:28.086  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.086  3819  3867 I jxcore-log: 
,08-18 02:39:28.087  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.087  3819  3867 I jxcore-log: 
,08-18 02:39:28.088  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.088  3819  3867 I jxcore-log: 
,08-18 02:39:28.088  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.088  3819  3867 I jxcore-log: 
08-18 02:39:28.089  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.089  3819  3867 I jxcore-log: 
08-18 02:39:28.090  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.090  3819  3867 I jxcore-log: 
,08-18 02:39:28.090  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.090  3819  3867 I jxcore-log: 
08-18 02:39:28.091  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 02:39:28.091  3819  3867 I jxcore-log: 
08-18 02:39:28.092  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.092  3819  3867 I jxcore-log: 
,08-18 02:39:28.094  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 02:39:28.094  3819  3867 I jxcore-log: 
08-18 02:39:28.094  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.094  3819  3867 I jxcore-log: 
08-18 02:39:28.095  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.095  3819  3867 I jxcore-log: 
,08-18 02:39:28.095  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.095  3819  3867 I jxcore-log: 
08-18 02:39:28.096  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.096  3819  3867 I jxcore-log: 
08-18 02:39:28.096  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.096  3819  3867 I jxcore-log: 
08-18 02:39:28.097  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 02:39:28.097  3819  3867 I jxcore-log: 
,08-18 02:39:28.097  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.097  3819  3867 I jxcore-log: 
08-18 02:39:28.098  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-18 02:39:28.098  3819  3867 I jxcore-log: 
08-18 02:39:28.098  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.098  3819  3867 I jxcore-log: 
,08-18 02:39:28.099  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 02:39:28.099  3819  3867 I jxcore-log: 
08-18 02:39:28.099  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-18 02:39:28.099  3819  3867 I jxcore-log: 
08-18 02:39:28.100  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:39:28.100  3819  3867 I jxcore-log: 
,08-18 02:39:28.100  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 02:39:28.100  3819  3867 I jxcore-log: 
,08-18 02:39:28.103  3819  3867 I jxcore-log: My device name is: motorola-Nexus 6
08-18 02:39:28.103  3819  3867 I jxcore-log: 
,08-18 02:39:28.127  3819  4317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-18 02:39:30.356  3819  3867 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-18 02:39:30.356  3819  3867 I jxcore-log: 
,08-18 02:39:30.371  3819  3867 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-18 02:39:30.372  3819  3867 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-18 02:39:30.372  3819  3867 I jxcore-log: 
,08-18 02:39:31.890  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:39:31.893  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:39:31.930  1509  2187 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-18 02:39:31.930  1509  2187 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:39:31.930  1509  2187 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:39:31.930  1509  2187 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:39:31.953  3547  4322 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-18 02:39:31.953  3547  4322 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at blb.a(PG:3937)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at czp.a(PG:18188)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:39:31.953  3547  4322 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	... 12 more
08-18 02:39:31.953  3547  4322 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at fal.a(PG:38)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:39:31.953  3547  4322 E HttpOperation: 	... 14 more
,08-18 02:39:32.002  1509  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 02:39:32.003  1509  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:39:32.003  1509  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:39:32.003  1509  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:39:32.026  3547  4322 E HttpOperation: [getmobileexperiments] Unexpected exception
08-18 02:39:32.026  3547  4322 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at hec.a(PG:42)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at hee.a(PG:102)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at czr.a(PG:65)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at kka.a(PG:108)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at czp.a(PG:19176)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:39:32.026  3547  4322 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	... 15 more
08-18 02:39:32.026  3547  4322 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at fal.a(PG:38)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:39:32.026  3547  4322 E HttpOperation: 	... 17 more
08-18 02:39:32.027  3547  4322 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-18 02:39:32.027  3547  4322 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jdm.a(PG:82)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jcs.o(PG:406)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jcn.a(PG:1379)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jcs.i(PG:143)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at hec.a(PG:42)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at hee.a(PG:102)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at czr.a(PG:65)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at kka.a(PG:108)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at czp.a(PG:19176)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at czp.a(PG:9081)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at czq.run(PG:1686)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jdj.a(PG:4091)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jdm.a(PG:77)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	... 15 more
08-18 02:39:32.027  3547  4322 E ExperimentLoader: Caused by: faj: BadAuthentication
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at fal.a(PG:38)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	at jdj.a(PG:4089)
08-18 02:39:32.027  3547  4322 E ExperimentLoader: 	... 17 more
,08-18 02:39:32.182   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 248306, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:39:44.663   872  4279 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261244, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-18 02:39:50.936   872  4279 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-18 02:40:02.911  3593  4325 I BooksSync: Starting books sync for 61035162, extras: ade
,08-18 02:40:02.945  3593  4326 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-18 02:40:02.965  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:40:02.970  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:40:03.009  1509  2957 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:40:03.009  1509  2957 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-18 02:40:03.009  1509  2957 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:40:03.009  1509  2957 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:40:03.048  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:40:03.054  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:40:03.092  1509  2957 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:40:03.092  1509  2957 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-18 02:40:03.092  1509  2957 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:40:03.093  1509  2957 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:40:03.113  3593  4326 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-18 02:40:03.114  3593  4325 E BooksSync: Soft error
08-18 02:40:03.114  3593  4325 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:40:03.114  3593  4325 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-18 02:40:03.115  3593  4325 E BooksSync: Sync error
08-18 02:40:03.115  3593  4325 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:40:03.115  3593  4325 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:40:03.115  3593  4325 I BooksSync: Finished books sync
,08-18 02:40:03.127   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279310, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:40:33.579  3061  4334 V KeepSync: Connecting to GoogleApiClient
,08-18 02:40:33.579   872  2965 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-18 02:40:33.587  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:40:33.596  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:40:33.687  1509  2187 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-18 02:40:33.687  1509  2187 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:40:33.687  1509  2187 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:40:33.687  1509  2187 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:40:33.725  3547  4335 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-18 02:40:33.725  3547  4335 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at blb.a(PG:3937)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at czp.a(PG:18188)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:40:33.725  3547  4335 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	... 12 more
08-18 02:40:33.725  3547  4335 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at fal.a(PG:38)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:40:33.725  3547  4335 E HttpOperation: 	... 14 more
,08-18 02:40:33.740  1509  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-18 02:40:33.740  1509  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-18 02:40:33.740  1509  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:40:33.740  1509  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:40:33.760  1733  4336 V BaseAuthAsyncOperation: access token request failed
,08-18 02:40:33.760  3061  4334 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-18 02:40:33.774  1509  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 02:40:33.774  1509  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:40:33.774  1509  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:40:33.774  1509  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:40:33.786  3547  4335 E HttpOperation: [getmobileexperiments] Unexpected exception
08-18 02:40:33.786  3547  4335 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at hec.a(PG:42)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at hee.a(PG:102)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at czr.a(PG:65)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at kka.a(PG:108)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at czp.a(PG:19176)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:40:33.786  3547  4335 E HttpOperation: ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:40:33.786  3547  4335 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
,08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	... 15 more
08-18 02:40:33.786  3547  4335 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at fal.a(PG:38)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:40:33.786  3547  4335 E HttpOperation: 	... 17 more
,08-18 02:40:33.786  3547  4335 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-18 02:40:33.786  3547  4335 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jdm.a(PG:82)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jcs.o(PG:406)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jcn.a(PG:1379)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jcs.i(PG:143)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at hec.a(PG:42)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at hee.a(PG:102)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at czr.a(PG:65)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at kka.a(PG:108)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at czp.a(PG:19176)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at czp.a(PG:9081)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at czq.run(PG:1686)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jdj.a(PG:4091)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jdj.a(PG:1125)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jdm.a(PG:77)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	... 15 more
08-18 02:40:33.786  3547  4335 E ExperimentLoader: Caused by: faj: BadAuthentication
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at fal.a(PG:38)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	at jdj.a(PG:4089)
08-18 02:40:33.786  3547  4335 E ExperimentLoader: 	... 17 more
,08-18 02:40:33.855  1509  2957 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-18 02:40:33.856  1509  2957 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-18 02:40:33.856  1509  2957 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:40:33.856  1509  2957 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:40:33.873  3061  4334 E KeepSync: IOException
08-18 02:40:33.873  3061  4334 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
,08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-18 02:40:33.873  3061  4334 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 02:40:33.873  3061  4334 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-18 02:40:33.873  3061  4334 E KeepSync: 	... 10 more
08-18 02:40:33.873  3061  4334 W KeepSync: Sync result 2
,08-18 02:40:33.885   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 283122, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:40:33.911   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 281418, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:40:35.043   872  4279 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-18 02:40:41.736   872  4279 D NetlinkSocketObserver: NeighborEvent{elapsedMs=318317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-18 02:41:04.066  3593  4348 I BooksSync: Starting books sync for 61035162, extras: ade
,08-18 02:41:04.087  3593  4349 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-18 02:41:04.104  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:04.109  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:04.147  1509  2187 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:41:04.148  1509  2187 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-18 02:41:04.148  1509  2187 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:41:04.148  1509  2187 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:41:04.185  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:04.187  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:04.218  1509  2957 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:41:04.218  1509  2957 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-18 02:41:04.218  1509  2957 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:41:04.218  1509  2957 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:41:04.239  3593  4349 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-18 02:41:04.240  3593  4348 E BooksSync: Soft error
08-18 02:41:04.240  3593  4348 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:41:04.240  3593  4348 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:41:04.242  3593  4348 E BooksSync: Sync error
08-18 02:41:04.242  3593  4348 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:41:04.242  3593  4348 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:41:04.244  3593  4348 I BooksSync: Finished books sync
,08-18 02:41:04.255   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 312061, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:41:06.167  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:06.184  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:06.187  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:06.254  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-18 02:41:06.255  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-18 02:41:06.255  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:41:06.256  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:41:06.298  1509  1520 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-18 02:41:06.298  1509  1520 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-18 02:41:06.298  1509  1520 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-18 02:41:06.298  1509  1520 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-18 02:41:06.298  1509  1520 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-18 02:41:06.298  1509  1520 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-18 02:41:06.298  1509  1520 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-18 02:41:06.317  3506  3537 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-18 02:41:06.317  3506  3537 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-18 02:41:06.317  3506  3537 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-18 02:41:06.317  3506  3537 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-18 02:41:06.317  3506  3537 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-18 02:41:06.317  3506  3537 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-18 02:41:06.317  3506  3537 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-18 02:41:34.521  3061  4356 V KeepSync: Connecting to GoogleApiClient
,08-18 02:41:34.522   872  1940 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-18 02:41:34.564  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:34.566  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:41:34.599  1509  2187 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-18 02:41:34.599  1509  2187 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-18 02:41:34.599  1509  2187 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:41:34.599  1509  2187 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:41:34.616  1733  4357 V BaseAuthAsyncOperation: access token request failed
,08-18 02:41:34.617  3061  4356 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-18 02:41:34.665  1509  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-18 02:41:34.665  1509  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-18 02:41:34.665  1509  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:41:34.665  1509  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:41:34.680  3061  4356 E KeepSync: IOException
08-18 02:41:34.680  3061  4356 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-18 02:41:34.680  3061  4356 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 02:41:34.680  3061  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-18 02:41:34.680  3061  4356 E KeepSync: 	... 10 more
08-18 02:41:34.681  3061  4356 W KeepSync: Sync result 2
,08-18 02:41:34.692   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 342890, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:42:05.076  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:42:05.079  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:42:05.124  1509  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 02:42:05.125  1509  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:42:05.125  1509  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:42:05.125  1509  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:42:05.157  3547  4360 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-18 02:42:05.157  3547  4360 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at blb.a(PG:3937)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at czp.a(PG:18188)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:42:05.157  3547  4360 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error,
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	... 12 more
08-18 02:42:05.157  3547  4360 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at fal.a(PG:38)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:42:05.157  3547  4360 E HttpOperation: 	... 14 more
,08-18 02:42:05.223  1509  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 02:42:05.224  1509  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 02:42:05.224  1509  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:42:05.224  1509  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:42:05.258  3547  4360 E HttpOperation: [getmobileexperiments] Unexpected exception
08-18 02:42:05.258  3547  4360 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jdm.a(PG:82)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jcs.o(PG:406)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jcn.a(PG:1379)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jcs.i(PG:143)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at hec.a(PG:42)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at hee.a(PG:102)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at czr.a(PG:65)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at kka.a(PG:108)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at czp.a(PG:19176)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at czp.a(PG:9081)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at czq.run(PG:1686)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:42:05.258  3547  4360 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jdj.a(PG:4091)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jdj.a(PG:1125)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jdm.a(PG:77)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	... 15 more
08-18 02:42:05.258  3547  4360 E HttpOperation: Caused by: faj: BadAuthentication
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at fal.a(PG:38)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	at jdj.a(PG:4089)
08-18 02:42:05.258  3547  4360 E HttpOperation: 	... 17 more
,08-18 02:42:05.259  3547  4360 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-18 02:42:05.259  3547  4360 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jdm.a(PG:82)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jcs.o(PG:406)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jcn.a(PG:1379)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jcs.i(PG:143)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at hec.a(PG:42)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at hee.a(PG:102)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at czr.a(PG:65)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at kka.a(PG:108)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at czp.a(PG:19176)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at czp.a(PG:9081)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at czq.run(PG:1686)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jdj.a(PG:4091)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jdj.a(PG:1125)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jdm.a(PG:77)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	... 15 more
08-18 02:42:05.259  3547  4360 E ExperimentLoader: Caused by: faj: BadAuthentication
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at fal.a(PG:38)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	at jdj.a(PG:4089)
08-18 02:42:05.259  3547  4360 E ExperimentLoader: 	... 17 more
,08-18 02:42:05.415   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 375800, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:42:35.501  3593  4364 I BooksSync: Starting books sync for 61035162, extras: ade
,08-18 02:42:35.534  3593  4365 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-18 02:42:35.553  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:42:35.556  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:42:35.589  1509  2957 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:42:35.590  1509  2957 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-18 02:42:35.590  1509  2957 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 02:42:35.590  1509  2957 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:42:35.629  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:42:35.633  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 02:42:35.668  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-18 02:42:35.668  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-18 02:42:35.668  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 02:42:35.668  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 02:42:35.694  3593  4365 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-18 02:42:35.695  3593  4364 E BooksSync: Soft error
08-18 02:42:35.695  3593  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:42:35.695  3593  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:42:35.696  3593  4364 E BooksSync: Sync error
08-18 02:42:35.696  3593  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-18 02:42:35.696  3593  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-18 02:42:35.696  3593  4364 I BooksSync: Finished books sync
,08-18 02:42:35.708   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 405544, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-18 02:42:50.963  3819  3867 I jxcore-log: TAP version 13
08-18 02:42:50.963  3819  3867 I jxcore-log: 
,08-18 02:42:50.968  3819  3867 I jxcore-log: # setup
08-18 02:42:50.968  3819  3867 I jxcore-log: 
,08-18 02:42:51.167  3819  3867 I jxcore-log: # 1. onPeerLost calls jxcore
08-18 02:42:51.167  3819  3867 I jxcore-log: 
,08-18 02:42:51.341  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 02:42:51.341  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d92649c added. We now have 3 listener(s)
,08-18 02:42:51.343  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 02:42:51.343  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:42:51.343  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:42:51.343  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:42:51.343  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea48ea5 added. We now have 4 listener(s)
08-18 02:42:51.343  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:42:51.344  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:42:51.349  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:42:51.360  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:42:51.365  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:42:51.366  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 02:42:51.366  3819  3867 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
08-18 02:42:51.366  3819  3867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-18 02:42:51.370  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:42:51.379  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:42:53.372  3819  3867 I jxcore-log: onPeerLost
08-18 02:42:53.372  3819  3867 I jxcore-log: 
,08-18 02:42:53.377  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:42:53.377  3819  3867 I jxcore-log: 
,08-18 02:42:53.394  3819  3867 I jxcore-log: # teardown
08-18 02:42:53.394  3819  3867 I jxcore-log: 
,08-18 02:42:53.406  3819  3867 I jxcore-log: ok 1 check if callback was fired by onPeerLost
08-18 02:42:53.406  3819  3867 I jxcore-log: 
,08-18 02:42:53.408  3819  3867 I jxcore-log: ok 2 check if peerAvailable is false
08-18 02:42:53.408  3819  3867 I jxcore-log: 
,08-18 02:42:53.564  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-18 02:42:53.564  3819  3867 I jxcore-log: 
,08-18 02:42:53.568  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-18 02:42:53.568  3819  3867 I jxcore-log: 
,08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:42:53.577  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:42:53.581  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:42:53.584  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-18 02:42:53.584  3819  3867 I jxcore-log: 
,08-18 02:42:53.586  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-18 02:42:53.586  3819  3867 I jxcore-log: 
,08-18 02:42:53.589  3819  3867 I jxcore-log: # setup
08-18 02:42:53.589  3819  3867 I jxcore-log: 
,08-18 02:42:53.592  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:42:53.592  3819  3867 I jxcore-log: 
,08-18 02:42:53.697  3819  3867 I jxcore-log: # 2. onPeerDiscovered calls jxcore
08-18 02:42:53.697  3819  3867 I jxcore-log: 
,08-18 02:42:53.790  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 02:42:53.790  3819  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193da2b added. We now have 4 listener(s)
,08-18 02:42:53.792  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 02:42:53.792  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 02:42:53.792  3819  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 02:42:53.792  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 02:42:53.792  3819  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af2e88 added. We now have 5 listener(s)
08-18 02:42:53.792  3819  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 02:42:53.793  3819  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 02:42:53.797  3819  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:42:53.804  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:42:53.808  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:42:53.808  3819  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 02:42:53.808  3819  3867 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-18 02:42:53.813  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:42:53.817  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 02:42:55.811  3819  3867 I jxcore-log: onPeerDiscovered
08-18 02:42:55.811  3819  3867 I jxcore-log: 
,08-18 02:42:55.818  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:42:55.818  3819  3867 I jxcore-log: 
,08-18 02:42:55.833  3819  3867 I jxcore-log: # teardown
08-18 02:42:55.833  3819  3867 I jxcore-log: 
,08-18 02:42:55.840  3819  3867 I jxcore-log: ok 3 check if callback was fired by onPeerDiscovered
08-18 02:42:55.840  3819  3867 I jxcore-log: 
,08-18 02:42:55.841  3819  3867 I jxcore-log: ok 4 check if peerAvailable is true
08-18 02:42:55.841  3819  3867 I jxcore-log: 
,08-18 02:42:56.058  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-18 02:42:56.058  3819  3867 I jxcore-log: 
,08-18 02:42:56.064  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-18 02:42:56.064  3819  3867 I jxcore-log: 
,08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 02:42:56.077  3819  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 02:42:56.079  3819  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 02:42:56.081  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-18 02:42:56.081  3819  3867 I jxcore-log: 
,08-18 02:42:56.085  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-18 02:42:56.085  3819  3867 I jxcore-log: 
,08-18 02:42:56.089  3819  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 02:42:56.089  3819  3867 I jxcore-log: 
,08-18 02:42:56.221  3819  3867 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-18 02:42:56.221  3819  3867 I jxcore-log: 
,08-18 02:42:56.912  4366  4366 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-18 02:42:56.917  4366  4366 D AndroidRuntime: CheckJNI is OFF
,08-18 02:42:56.984  4366  4366 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-18 02:42:57.036  4366  4366 I Radio-JNI: register_android_hardware_Radio DONE
,08-18 02:42:57.058  4366  4366 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-18 02:42:57.069   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-18 02:42:57.069   872   885 I ActivityManager: Killing 3819:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-18 02:42:57.186   872   896 W PackageSettings: Skipping PackageSetting{4deaebd com.example.hello/10273} due to missing metadata
,08-18 02:42:57.196   872  1928 D GraphicsStats: Buffer count: 2
,08-18 02:42:57.197   872  1940 I WindowState: WIN DEATH: Window{5a2b6cf u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-18 02:42:57.198   872  1304 D WifiService: Client connection lost with reason: 4
,08-18 02:42:57.231   872   896 I art     : Starting a blocking GC Explicit
,08-18 02:42:57.246   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-18 02:42:57.247   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-18 02:42:57.253   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-18 02:42:57.253   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-18 02:42:57.253   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.253   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.253   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 02:42:57.253   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-18 02:42:57.254   872   885 I ActivityManager:   Force finishing activity ActivityRecord{5587464 u0 com.test.thalitest/.MainActivity t2}
,08-18 02:42:57.261   872  3139 W ActivityManager: Spurious death for ProcessRecord{f17d15d 0:com.test.thalitest/u0a0}, curProc for 3819: null
,08-18 02:42:57.276   872   896 I art     : Explicit concurrent mark sweep GC freed 46918(2MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 823us total 44.847ms
,08-18 02:42:57.298   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-18 02:42:57.300  4366  4366 I art     : System.exit called, status: 0
08-18 02:42:57.300  4366  4366 I AndroidRuntime: VM exiting with result code 0.
,08-18 02:42:57.314   872   896 I ActivityManager: Start proc 4376:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-18 02:42:57.315   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-18 02:42:57.326   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-18 02:42:57.330  4223  4223 D BluetoothMapAppObserver: onReceive
,08-18 02:42:57.330  4223  4223 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-18 02:42:57.334  2095  2270 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-18 02:42:57.338   872  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-18 02:42:57.346  3654  3654 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-18 02:42:57.361  1855  1855 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-18 02:42:57.382  1921  1921 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-18 02:42:57.392  1855  4391 I Keyboard.Facilitator.DecoderInitializer: run()
,08-18 02:42:57.396   872  1391 I ActivityManager: Start proc 4392:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-18 02:42:57.398  1855  4391 I Decoder : createOrResetDecoder
,08-18 02:42:57.414   872  3139 I ActivityManager: Killing 3788:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-18 02:42:57.418   872  1940 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3819 uid 10000
,08-18 02:42:57.420  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-18 02:42:57.436   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-18 02:42:57.476  1509  1509 I ConfigService: onCreate
,08-18 02:42:57.479   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-18 02:42:57.479  1934  2018 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-18 02:42:57.479   872   884 E PackageManager: Failed to write settings, restoring backup
08-18 02:42:57.479   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-18 02:42:57.479   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-18 02:42:57.479   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-18 02:42:57.479   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-18 02:42:57.479   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-18 02:42:57.479   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.479   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.479   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 02:42:57.486   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-18 02:42:57.486   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-18 02:42:57.486   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 02:42:57.486   872   885 E DropBoxManagerService: 	... 13 more
,08-18 02:42:57.494   872  1901 I ActivityManager: Start proc 4405:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-18 02:42:57.494  1934  2018 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-18 02:42:57.494  1934  2018 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1934
08-18 02:42:57.494  1934  2018 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.494  1934  2018 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 02:42:57.496   872  2965 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-18 02:42:57.497   872  4413 E DropBoxManagerService: Can't write: system_app_crash
08-18 02:42:57.497   872  4413 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 02:42:57.497   872  4413 E DropBoxManagerService: 	... 5 more
,08-18 02:42:57.505  1934  2018 I Process : Sending signal. PID: 1934 SIG: 9
,08-18 02:42:57.521  4392  4392 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-18 02:42:57.530  1509  4404 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-18 02:42:57.530  1509  4404 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-18 02:42:57.530  1509  4404 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-18 02:42:57.546  1509  4404 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-18 02:42:57.562  1855  4391 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-18 02:42:57.576   872  1379 D GraphicsStats: Buffer count: 1
,08-18 02:42:57.576   872  1974 I WindowState: WIN DEATH: Window{a1d3ae1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-18 02:42:57.603   872  1379 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1934) has died
,08-18 02:42:57.603   872  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-18 02:42:57.605   872  1379 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-18 02:42:57.617  1855  4391 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-18 02:42:57.621  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-18 02:42:57.621  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-18 02:42:57.622  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-18 02:42:57.622  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-18 02:42:57.629  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-18 02:42:57.629  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-18 02:42:57.630  1855  4391 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-18 02:42:57.630  1855  4391 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-18 02:42:57.630  1855  4391 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-18 02:42:57.631  1855  4391 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-18 02:42:57.631  1855  4391 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-18 02:42:57.631  1855  4391 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-18 02:42:57.635   872   885 I ActivityManager: Start proc 4424:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-18 02:42:57.643  4392  4392 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-18 02:42:57.683   872  2965 I ActivityManager: Start proc 4438:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-18 02:42:57.687  4392  4443 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-18 02:42:57.692  4424  4424 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:42:57.692  4424  4424 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 02:42:57.692  4424  4424 D AndroidRuntime: Shutting down VM
,08-18 02:42:57.704  4424  4424 E AndroidRuntime: FATAL EXCEPTION: main
08-18 02:42:57.704  4424  4424 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4424
08-18 02:42:57.704  4424  4424 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 02:42:57.704  4424  4424 E AndroidRuntime: 	... 10 more
08-18 02:42:57.708   872  1928 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-18 02:42:57.708  4424  4424 I Process : Sending signal. PID: 4424 SIG: 9
,08-18 02:42:57.712   872  4451 E DropBoxManagerService: Can't write: system_app_crash
08-18 02:42:57.712   872  4451 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 02:42:57.712   872  4451 E DropBoxManagerService: 	... 5 more
,08-18 02:42:57.714  1733  4437 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-18 02:42:57.717  1733  4437 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-18 02:42:57.721  1733  4437 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-18 02:42:57.722  1733  4437 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-18 02:42:57.728  4392  4422 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.728  4392  4422 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.729  4392  4422 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 02:42:57.734  4438  4438 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-18 02:42:57.736   872  1901 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4424) has died
,08-18 02:42:57.737   872  1901 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-18 02:42:57.752   872   885 I ActivityManager: Start proc 4454:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-18 02:42:57.762   872  1928 I ActivityManager: Killing 3468:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-18 02:42:57.778  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-18 02:42:57.779  1509  1509 D AndroidRuntime: Shutting down VM
,08-18 02:42:57.780  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
08-18 02:42:57.780  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
08-18 02:42:57.780  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-18 02:42:57.780  1509  1509 E AndroidRuntime: 	... 8 more
,08-18 02:42:57.787   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
