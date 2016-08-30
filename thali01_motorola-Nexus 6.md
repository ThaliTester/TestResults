#### Test 82865362c4ce6b4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 12:58:25.200  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:58:25.212  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:58:25.215  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:58:25.269  1512  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 12:58:25.270  1512  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:58:25.270  1512  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:58:25.271  1512  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:58:25.310  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:58:25.311  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 12:58:25.312  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 12:58:25.786   873  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
08-30 12:58:25.998  3783  3783 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 12:58:26.004  3783  3783 D AndroidRuntime: CheckJNI is OFF
08-30 12:58:26.050  3783  3783 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 12:58:26.101  3783  3783 I Radio-JNI: register_android_hardware_Radio DONE
08-30 12:58:26.124  3783  3783 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 12:58:26.129   873  1975 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:58:26.173  2008  2393 W SearchService: Abort, client detached.
08-30 12:58:26.173  3783  3783 D AndroidRuntime: Shutting down VM
08-30 12:58:26.181  2008  2008 I HotwordDetector: Closing mic
08-30 12:58:26.182  2008  2334 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e81ae81
08-30 12:58:26.182  2008  2347 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 12:58:26.206   873   883 I ActivityManager: Start proc 3792:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 12:58:26.228   376  2351 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 12:58:26.235   376  2351 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 12:58:26.243   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 12:58:26.244  2008  2346 I MicroRecognitionRnrImpl: Detection finished
08-30 12:58:26.244  2008  2340 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 12:58:26.299  3792  3792 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 12:58:26.330  3792  3792 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 12:58:26.340  3792  3792 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2046-2050)
08-30 12:58:26.340  3792  3792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:58:26.372  3792  3792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3eeab4c}
08-30 12:58:26.373  3792  3792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:58:26.373  3792  3792 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:58:26.383  3792  3792 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 12:58:26.385  3792  3792 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 12:58:26.411  3792  3792 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 12:58:26.428  3792  3792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:58:26.428  3792  3792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:58:26.428  3792  3792 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:58:26.428  3792  3792 I Adreno  : Build Date                       : 10/20/15
08-30 12:58:26.428  3792  3792 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:58:26.428  3792  3792 I Adreno  : Local Branch                     : M14
08-30 12:58:26.428  3792  3792 I Adreno  : Remote Branch                    : 
08-30 12:58:26.428  3792  3792 I Adreno  : Remote Branch                    : 
08-30 12:58:26.428  3792  3792 I Adreno  : Reconstruct Branch               : 
,08-30 12:58:26.518   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7cadc3e:true
,08-30 12:58:26.565  3792  3792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 12:58:26.585  3792  3792 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 12:58:26.655  3792  3831 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 12:58:26.665  3792  3817 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 12:58:26.687  3792  3831 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 12:58:26.758   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +581ms
,08-30 12:58:26.762  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-30 12:58:26.830  3792  3792 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3792
,08-30 12:58:27.031   873  1986 I ActivityManager: Killing 2971:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 12:58:27.045  3792  3792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:58:27.085   873  1986 I ActivityManager: Killing 3189:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 12:58:27.180  3792  3833 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1696335568
,08-30 12:58:27.184  3792  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:58:27.184  3792  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:58:27.184  3792  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:58:27.184  3792  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:58:27.184  3792  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:58:27.184  3792  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d724b10 added. We now have 1 listener(s)
,08-30 12:58:27.188  3792  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 12:58:27.188  3792  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:58:27.190  3792  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:58:27.190  3792  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:58:27.194  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 12:58:27.195  3792  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec2fa2f added. We now have 1 listener(s)
08-30 12:58:27.195  3792  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:58:27.197   873  1302 D WifiService: New client listening to asynchronous messages
,08-30 12:58:27.198  3792  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:58:27.199  3792  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:58:27.199  3792  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:58:27.199  3792  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 12:58:27.199  3792  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:58:27.203  3792  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:58:27.203  3792  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 12:58:27.210  3792  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:27.210  3792  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:27.210  3792  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 12:58:27.211  3792  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:58:27.212  3792  3833 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 12:58:27.297  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:27.306  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:27.307  3792  3792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:58:28.073  3792  3842 W jxcore-log: Initializing JXcore engine
,08-30 12:58:28.073  3792  3842 W jxcore-log: JXcore engine is ready
,08-30 12:58:28.107  3842  3842 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-30 12:58:28.107  3842  3842 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11061]" dev="sockfs" ino=11061 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 12:58:28.107  3842  3842 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 12:58:28.107  3842  3842 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25763]" dev="sockfs" ino=25763 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 12:58:28.120  3792  3842 W jxcore-log: Starting JXcore engine
,08-30 12:58:28.199  3792  3842 W jxcore-log: Platform android
08-30 12:58:28.199  3792  3842 W jxcore-log: 
,08-30 12:58:28.199  3792  3842 W jxcore-log: Process ARCH arm
08-30 12:58:28.199  3792  3842 W jxcore-log: 
,08-30 12:58:28.484  3792  3842 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:58:28.484  3792  3842 I jxcore-log: 
,08-30 12:58:28.484  3792  3842 W jxcore-log: JXcore engine is started
,08-30 12:58:28.501  3792  3833 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:58:28.505  3792  3792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:58:30.805  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:58:30.809  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:58:30.858  1512  3043 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 12:58:30.859  1512  3043 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 12:58:30.859  1512  3043 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:58:30.859  1512  3043 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:58:30.881  3547  3845 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 12:58:30.881  3547  3845 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jdm.a(PG:82)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jcs.o(PG:406)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jcn.a(PG:1379)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jcs.i(PG:143)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at blb.a(PG:3937)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at czp.a(PG:18188)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at czp.a(PG:9081)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at czq.run(PG:1686)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:58:30.881  3547  3845 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jdj.a(PG:4091)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jdj.a(PG:1125)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jdm.a(PG:77)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	... 12 more
08-30 12:58:30.881  3547  3845 E HttpOperation: Caused by: faj: BadAuthentication
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at fal.a(PG:38)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	at jdj.a(PG:4089)
08-30 12:58:30.881  3547  3845 E HttpOperation: 	... 14 more
,08-30 12:58:30.921  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 12:58:30.921  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 12:58:30.921  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:58:30.922  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:58:30.939  3547  3845 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 12:58:30.939  3547  3845 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jdm.a(PG:82)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jcs.o(PG:406)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jcn.a(PG:1379)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jcs.i(PG:143)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at hec.a(PG:42)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at hee.a(PG:102)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at czr.a(PG:65)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at kka.a(PG:108)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at czp.a(PG:19176)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at czp.a(PG:9081)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at czq.run(PG:1686)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:58:30.939  3547  3845 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jdj.a(PG:4091)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jdj.a(PG:1125)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jdm.a(PG:77)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	... 15 more
08-30 12:58:30.939  3547  3845 E HttpOperation: Caused by: faj: BadAuthentication
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at fal.a(PG:38)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	at jdj.a(PG:4089)
08-30 12:58:30.939  3547  3845 E HttpOperation: 	... 17 more
,08-30 12:58:30.939  3547  3845 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 12:58:30.939  3547  3845 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at hec.a(PG:42)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at hee.a(PG:102)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at czr.a(PG:65)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at kka.a(PG:108)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	... 15 more
08-30 12:58:30.939  3547  3845 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at fal.a(PG:38)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 12:58:30.939  3547  3845 E ExperimentLoader: 	... 17 more
,08-30 12:58:31.040   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126284, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:58:37.651   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 12:58:40.682   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 12:58:42.493  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:58:42.493  3792  3842 I jxcore-log: 
,08-30 12:58:42.495  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:58:42.495  3792  3842 I jxcore-log: 
,08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:42.505  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:42.510  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:58:42.513  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:58:42.513  3792  3842 I jxcore-log: 
,08-30 12:58:42.515  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:58:42.515  3792  3842 I jxcore-log: 
,08-30 12:58:42.888  3792  3842 I jxcore-log: Running unit tests
08-30 12:58:42.888  3792  3842 I jxcore-log: 
,08-30 12:58:42.890  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:58:42.890  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7794af added. We now have 2 listener(s)
,08-30 12:58:42.899  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:58:42.899  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:58:42.900  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:58:42.900  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:58:42.900  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291d0bc added. We now have 2 listener(s)
,08-30 12:58:42.901  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:58:42.902  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:58:42.910  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:42.921  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:42.927  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:58:42.927  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:58:42.927  3792  3842 D executeNativeTests: Running unit tests
,08-30 12:58:42.933  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:42.940  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:42.984  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 12:58:42.984  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a added. We now have 3 listener(s)
08-30 12:58:42.985  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:58:42.985  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:58:42.985  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:58:42.985  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:58:42.985  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb added. We now have 3 listener(s)
08-30 12:58:42.985  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:58:42.985  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:58:42.988  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:43.003  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:43.008  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:58:43.009  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:58:43.011  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:43.013  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:43.016  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:58:43.017  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:58:43.017  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:58:43.017  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:58:43.022  3792  3842 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 12:58:43.023  3792  3842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 12:58:43.024  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 12:58:43.024  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 12:58:43.024  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 12:58:43.024  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:58:43.026  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:58:43.027  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:58:43.027  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:58:43.027  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:58:43.027  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.027  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:58:43.027  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:58:43.028  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a removed from the list
08-30 12:58:43.028  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:43.028  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb removed from the list
08-30 12:58:43.028  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:58:43.028  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:58:43.028  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.029  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.030  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:58:43.030  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:58:43.030  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:43.030  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:43.032  3792  3842 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 12:58:43.032  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:58:43.032  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:58:43.032  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:58:43.033  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:58:43.033  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.033  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.033  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:58:43.033  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:43.033  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:43.033  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:58:43.033  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.033  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.033  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.033  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.034  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:58:43.034  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:58:43.034  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:43.034  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
,08-30 12:58:43.040  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 12:58:43.040  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:58:43.040  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:58:43.041  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:58:43.042  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:58:43.042  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:58:43.042  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:58:43.042  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:58:43.043  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:58:43.043  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.043  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.043  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:58:43.043  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:43.043  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:43.043  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:58:43.043  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.043  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.043  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:43.043  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:58:43.044  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:58:43.044  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:58:43.044  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:43.044  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:43.045  3792  3842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:58:43.046  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:43.050  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:43.053  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:43.053  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:58:43.053  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:58:43.053  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:58:43.053  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 12:58:43.053  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:58:43.053  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:58:43.055  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:43.057  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:58:43.057  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:58:43.058  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:43.063  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:58:43.065  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:58:43.065  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:58:43.068  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 12:58:43.070  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 12:58:43.070  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:58:43.071  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 12:58:43.071  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 12:58:43.073  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 12:58:43.077  2682  2692 D BtGatt.GattService: registerClient() - UUID=ce3ed60a-7712-49e9-a0bc-0ae1cef70ee1
,08-30 12:58:43.079  2682  2707 D BtGatt.GattService: onClientRegistered() - UUID=ce3ed60a-7712-49e9-a0bc-0ae1cef70ee1, clientIf=5
,08-30 12:58:43.081  3792  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:58:43.082  2682  2851 D BtGatt.GattService: start scan with filters
,08-30 12:58:43.085  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 12:58:43.085  2682  2710 D BtGatt.ScanManager: handling starting scan
08-30 12:58:43.085  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:58:43.085  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:58:43.086  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 12:58:43.087  2682  2710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:58:43.087  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:58:43.088  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:58:43.088  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:58:43.090  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 12:58:43.091  3792  3842 I io.jxcore.node.ConnectionHelper: start: OK
08-30 12:58:43.095  2682  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:58:43.095  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:43.096  2682  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:58:43.104  2682  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:58:43.104  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:43.105  2682  2710 D BtGatt.ScanManager: Starting BLE batch scan
08-30 12:58:43.105  2682  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:58:43.115  2682  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:58:43.115  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:43.121  2682  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:58:43.121  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:43.590  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:58:43.590  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-30 12:58:43.591  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:58:44.628  2682  2682 D BtGatt.ScanManager: awakened up at time 140339
,08-30 12:58:44.632  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:44.680  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 12:58:44.680  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:44.681  2682  2707 D BtGatt.GattService: current time is 140391866393
,08-30 12:58:44.682  2682  2707 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -86, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -65, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 12:58:44.685  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:58:44.687  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 12:58:44.688  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 12:58:44.688  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:58:44.689  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-30 12:58:44.689  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 12:58:46.182  2682  2682 D BtGatt.ScanManager: awakened up at time 141893
,08-30 12:58:46.184  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:46.284  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-30 12:58:46.284  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:46.284  2682  2707 D BtGatt.GattService: current time is 141995137176
08-30 12:58:46.284  2682  2707 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -85, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-30 12:58:46.285  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 12:58:46.285  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 12:58:46.285  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-30 12:58:46.285  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-30 12:58:46.285  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-30 12:58:46.351  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:58:46.361  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:58:46.363  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:58:46.393  1512  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 12:58:46.393  1512  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:58:46.393  1512  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:58:46.393  1512  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:58:46.414  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:58:46.415  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 12:58:46.415  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 12:58:47.785  2682  2682 D BtGatt.ScanManager: awakened up at time 143496
,08-30 12:58:47.788  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:47.799  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:58:47.800  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:48.101  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:58:48.102  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:58:48.102  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:58:48.102  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:48.103  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:58:48.103  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:58:48.103  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:58:48.104  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:58:48.104  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:58:48.106  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:58:48.106  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:58:48.108  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 12:58:48.110  2682  2694 D BtGatt.GattService: stopScan() - queue size =1
08-30 12:58:48.113  2682  2851 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:58:48.114  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 12:58:48.114  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 12:58:48.114  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 12:58:48.115  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 12:58:48.115  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 12:58:48.119  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:58:48.120  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:58:48.121  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 12:58:48.122  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:58:48.123  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:58:48.127  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:58:48.128  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:58:48.128  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:58:48.129  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:58:48.130  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:48.130  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:58:48.130  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:58:48.131  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:58:48.131  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:48.132  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:58:48.132  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:58:48.136  2682  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 12:58:48.136  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:48.137  2682  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-30 12:58:48.147  2682  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 12:58:48.147  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:48.147  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:48.156  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:58:48.156  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:48.630  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:58:53.134  3792  3842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 12:58:53.140  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:53.154  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:53.157  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:53.157  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:58:53.158  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:58:53.158  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 12:58:53.159  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 12:58:53.159  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:58:53.159  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:53.160  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:58:53.162  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:53.177  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:58:53.177  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:58:53.181  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:58:53.181  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:58:53.182  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:58:53.185  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:58:53.185  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 12:58:53.185  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:58:53.186  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 12:58:53.188  2682  2834 D BtGatt.GattService: registerClient() - UUID=21cda541-78cb-434e-b4b5-d1b04fa6be2f
,08-30 12:58:53.189  2682  2707 D BtGatt.GattService: onClientRegistered() - UUID=21cda541-78cb-434e-b4b5-d1b04fa6be2f, clientIf=5
08-30 12:58:53.189  3792  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 12:58:53.189  2682  2694 D BtGatt.GattService: start scan with filters
,08-30 12:58:53.192  2682  2710 D BtGatt.ScanManager: handling starting scan
,08-30 12:58:53.192  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:58:53.193  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:58:53.193  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:58:53.193  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:58:53.196  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:58:53.196  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:58:53.196  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:58:53.197  2682  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 12:58:53.197  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.197  2682  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 12:58:53.198  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:58:53.201  3792  3842 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:58:53.203  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:58:53.204  3792  3842 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 12:58:53.204  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:58:53.204  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:58:53.204  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:53.204  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:58:53.205  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:58:53.205  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:58:53.205  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 12:58:53.205  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:58:53.205  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:58:53.205  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:58:53.206  3792  3842 D BluetoothAdapter: STATE_ON
08-30 12:58:53.211  2682  2834 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:58:53.212  2682  2694 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 12:58:53.212  2682  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:58:53.212  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.212  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:58:53.213  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 12:58:53.213  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:58:53.213  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 12:58:53.213  2682  2710 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 12:58:53.214  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 12:58:53.214  2682  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:58:53.215  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:58:53.215  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 12:58:53.215  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:58:53.215  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:58:53.216  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:58:53.217  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:58:53.217  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:58:53.217  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:53.217  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:58:53.217  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:58:53.218  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:58:53.218  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
,08-30 12:58:53.218  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:58:53.218  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:53.218  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop,
,08-30 12:58:53.218  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:58:53.218  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:53.219  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:58:53.220  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:58:53.220  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:58:53.220  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:58:53.220  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:58:53.221  3792  3842 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-30 12:58:53.223  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:58:53.231  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:58:53.236  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:58:53.236  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:58:53.236  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:58:53.236  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 12:58:53.236  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:58:53.236  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:58:53.236  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:58:53.240  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:53.241  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 12:58:53.241  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:58:53.241  2682  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 12:58:53.241  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:53.243  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:58:53.248  2682  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:58:53.248  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.248  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:58:53.248  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:58:53.248  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:58:53.252  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:58:53.252  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 12:58:53.252  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:58:53.252  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 12:58:53.255  2682  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 12:58:53.255  2682  2692 D BtGatt.GattService: registerClient() - UUID=a9fa2c7b-e637-4c8f-9292-b9af59f97905
08-30 12:58:53.255  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:53.255  2682  2710 D BtGatt.ScanManager: stopping BLe Batch
08-30 12:58:53.255  2682  2707 D BtGatt.GattService: onClientRegistered() - UUID=a9fa2c7b-e637-4c8f-9292-b9af59f97905, clientIf=5
,08-30 12:58:53.256  3792  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:58:53.256  2682  2834 D BtGatt.GattService: start scan with filters,
08-30 12:58:53.259  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 12:58:53.259  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:58:53.259  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 12:58:53.259  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:58:53.261  2682  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 12:58:53.261  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.261  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:53.262  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:58:53.262  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-30 12:58:53.262  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:58:53.263  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:58:53.265  3792  3842 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:58:53.267  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:58:53.267  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:53.268  2682  2710 D BtGatt.ScanManager: handling starting scan
,08-30 12:58:53.276  2682  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:58:53.276  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.276  2682  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:58:53.285  2682  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 12:58:53.285  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.285  2682  2710 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 12:58:53.285  2682  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:58:53.295  2682  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:58:53.295  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:53.300  2682  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:58:53.300  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:53.763  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:58:53.763  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:58:53.764  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:58:54.101   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 12:58:54.111  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-30 12:58:54.120   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:58:54.120   873   893 I Adreno  : Build Date                       : 10/20/15
08-30 12:58:54.120   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:58:54.120   873   893 I Adreno  : Local Branch                     : M14
08-30 12:58:54.120   873   893 I Adreno  : Remote Branch                    : 
08-30 12:58:54.120   873   893 I Adreno  : Remote Branch                    : 
08-30 12:58:54.120   873   893 I Adreno  : Reconstruct Branch               : 
,08-30 12:58:54.168   281  1753 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (197 us)
,08-30 12:58:54.783  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:58:54.783  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 12:58:54.828   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 12:58:54.830  2682  2682 D BtGatt.ScanManager: awakened up at time 150541
,08-30 12:58:54.830  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@eca0b02 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9bc5d1c, 16908290=android.view.AbsSavedState$1@9bc5d1c}, android:focusedViewId=100}]}]
08-30 12:58:54.830  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-30 12:58:54.831  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 12:58:54.831  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 12:58:54.832  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:54.848   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 12:58:54.856  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 12:58:54.856  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:54.857  2682  2707 D BtGatt.GattService: current time is 150567532509,
,08-30 12:58:54.857  2682  2707 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -101, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0],
08-30 12:58:54.857  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 12:58:54.857  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 12:58:54.857  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 12:58:54.857  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-30 12:58:54.857  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 12:58:54.858  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-30 12:58:54.858   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 12:58:54.859   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-30 12:58:54.860   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 12:58:55.096   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 12:58:55.099   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 12:58:55.105   873  1327 D SurfaceControl: Excessive delay in setPowerMode(): 247ms
,08-30 12:58:55.112   873   893 I DreamManagerService: Entering dreamland.
,08-30 12:58:55.112   873   893 I PowerManagerService: Dozing...
,08-30 12:58:55.113   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 12:58:55.181   376  1309 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 12:58:55.182   376  1309 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 12:58:55.195   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:58:55.208  1918  3861 D NfcService: Discovery configuration equal, not updating.
,08-30 12:58:55.219   873  1301 E native  : do suspend false
,08-30 12:58:55.243   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:58:55.262   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:58:55.274   873  1301 E native  : do suspend true
,08-30 12:58:55.311   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 12:58:55.312   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 12:58:55.372  2682  2682 D BtGatt.ScanManager: awakened up at time 151082
,08-30 12:58:55.378  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:55.409  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-30 12:58:55.409  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:55.409  2682  2707 D BtGatt.GattService: current time is 151120071262
,08-30 12:58:55.410  2682  2707 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -64, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:58:55.410  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 12:58:55.411  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 12:58:55.411  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74],
08-30 12:58:55.412  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:58:55.412  2682  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:58:55.703   873  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 12:58:56.915  2682  2682 D BtGatt.ScanManager: awakened up at time 152626
,08-30 12:58:56.918  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:56.929  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:58:56.929  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:57.351  1512  2133 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 12:58:58.266  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:58:58.267  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:58:58.267  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 12:58:58.267  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:58:58.267  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:58:58.268  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:58:58.268  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:58:58.268  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:58:58.269  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:58:58.270  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:58:58.270  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:58:58.272  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 12:58:58.275  2682  2834 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:58:58.277  2682  2694 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:58:58.281  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 12:58:58.281  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 12:58:58.281  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 12:58:58.282  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 12:58:58.282  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 12:58:58.288  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:58:58.288  2682  2682 D BtGatt.ScanManager: awakened up at time 153998
,08-30 12:58:58.288  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:58:58.290  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 12:58:58.291  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:58:58.293  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:58:58.294  2682  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 12:58:58.295  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:58:58.295  2682  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-30 12:58:58.298  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:58:58.298  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:58:58.298  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:58:58.308  2682  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 12:58:58.309  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:58.309  2682  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:58:58.317  2682  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:58:58.318  2682  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:58:58.800  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:58:58.800  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:58:58.801  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:58:59.935  2106  2641 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 12:59:03.000  3014  3866 V KeepSync: Connecting to GoogleApiClient
,08-30 12:59:03.001   873   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 12:59:03.055  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:03.058  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:03.121  1512  2281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 12:59:03.122  1512  2281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 12:59:03.122  1512  2281 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:03.122  1512  2281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:03.163  1723  3867 V BaseAuthAsyncOperation: access token request failed
,08-30 12:59:03.164  3014  3866 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 12:59:03.268  1512  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 12:59:03.268  1512  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 12:59:03.270  1512  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:59:03.270  1512  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:03.299  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.299  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.299  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.299  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.299  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.299  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:59:03.300  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.300  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.300  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.300  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.300  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.301  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:03.302  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:03.303  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.303  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:59:03.303  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.304  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
,08-30 12:59:03.304  3792  3842 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 12:59:03.305  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.306  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.306  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:59:03.306  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.306  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.306  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.306  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list,
08-30 12:59:03.306  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.307  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.307  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.307  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.307  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.307  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:03.307  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.308  3014  3866 E KeepSync: IOException
08-30 12:59:03.308  3014  3866 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 12:59:03.308  3014  3866 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 12:59:03.308  3014  3866 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 12:59:03.308  3014  3866 E KeepSync: 	... 10 more
08-30 12:59:03.308  3014  3866 W KeepSync: Sync result 2
08-30 12:59:03.310  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.310  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.310  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:03.310  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.312  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:59:03.312  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.312  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.312  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.312  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.313  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.313  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.313  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.313  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.313  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.313  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.313  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.313  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.314  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.314  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.315  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.316  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.316  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.316  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.317  3792  3842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 12:59:03.317  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.317  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.318  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.318  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.318  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.318  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.318  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.318  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.318  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.319  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.319  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.319  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.319  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.319  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.321  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.321  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.321  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.321  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.323  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 12:59:03.323  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.323  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.323  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.323  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.323  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.323  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.324  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.324  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.324  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.324  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.324  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.324  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.324  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.325  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.326  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.326  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.327  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.327  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.328  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:59:03.331  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:59:03.331  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:59:03.331  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:59:03.332   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 158515, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-30 12:59:03.332  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:59:03.332  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:59:03.332  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:59:03.332  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:59:03.332  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:59:03.333  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.333  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.333  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.333  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.333  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.333  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.334  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.334  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.334  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.334  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.334  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:03.334  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.334  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.334  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.336  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.336  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.336  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.336  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.337  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:59:03.337  3792  3842 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:59:03.337  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 12:59:03.341  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:59:03.341  3792  3842 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:59:03.342  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:59:03.343  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:59:03.344  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:59:03.344  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:59:03.344  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:59:03.344  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:59:03.344  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:59:03.344  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:59:03.344  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 12:59:03.344  3792  3842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:59:03.345  3792  3842 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 12:59:03.345  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:59:03.345  3792  3842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:59:03.345  3792  3842 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 12:59:03.347  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:59:03.348  3792  3842 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:59:03.348  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 12:59:03.350  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 12:59:03.351  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 12:59:03.351  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 12:59:03.352  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 12:59:03.352  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 12:59:03.352  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 12:59:03.352  3792  3842 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:59:03.353  3792  3842 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 12:59:03.354  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.354  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.354  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.354  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.354  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.354  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.355  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 12:59:03.355  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.355  3792  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-30 12:59:03.355  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.356  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.356  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.356  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.356  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.356  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.356  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.357  3792  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-30 12:59:03.361  3792  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:59:03.361  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.361  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.361  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.361  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.362  3792  3842 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 12:59:03.363  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.363  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.363  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.363  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.363  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.363  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.363  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.363  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.363  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.363  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.364  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.364  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.364  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.364  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.365  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.365  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.365  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.365  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.367  3792  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 12:59:03.368  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.368  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.368  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.368  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.368  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.368  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.369  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.369  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.369  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.369  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.369  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.369  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.369  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.369  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.371  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.371  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.371  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.371  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.372  3792  3842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 12:59:03.372  3792  3842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 12:59:03.372  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:59:03.372  3792  3842 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 12:59:03.372  3792  3842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:59:03.372  3792  3842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 12:59:03.372  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:59:03.372  3792  3842 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 12:59:03.372  3792  3842 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:59:03.372  3792  3842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:59:03.373  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:59:03.373  3792  3842 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 12:59:03.373  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:03.373  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:03.373  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:03.373  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.373  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.373  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.373  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.373  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.373  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.373  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.374  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.374  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.374  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:03.374  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.375  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:03.375  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:03.375  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.375  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.377  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:03.377  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.377  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:03.377  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:03.377  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:03.377  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:03.377  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:03.377  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:03.377  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:05.801   873  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 12:59:06.561  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:06.704  1512  3871 I VacuumService: Vacuum at: now=1472554746704 tag=VacuumService
,08-30 12:59:06.840  1512  3872 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 12:59:06.850  1512  3872 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 12:59:06.921  1512  3872 W Uploader:  no longer exists, so no auth token.
,08-30 12:59:06.965  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:07.004  1512  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:59:07.005  1512  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:59:07.005  1512  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:07.006  1512  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:07.048  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:59:07.048  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 12:59:07.048  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 12:59:08.378  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.379  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
,08-30 12:59:08.379  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:08.379  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.380  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.380  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:08.380  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:08.381  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:08.381  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:08.382  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:08.382  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.383  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.383  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:08.383  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.384  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.384  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:08.384  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.384  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.385  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.385  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:08.388  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:08.389  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:59:08.389  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:08.390  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
,08-30 12:59:08.397  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 12:59:08.398  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:59:08.400  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 12:59:08.401  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:59:08.402  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 12:59:08.402  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:59:08.402  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:59:08.402  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:59:08.403  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:59:08.403  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 12:59:08.403  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:59:08.403  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 12:59:08.403  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.403  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:59:08.403  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:08.403  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.403  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:59:08.403  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:59:08.404  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:59:08.404  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:59:08.404  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.404  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.404  3792  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:59:08.405  3792  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:59:08.405  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:59:08.406  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.406  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:08.406  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:59:08.406  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:08.406  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:59:08.406  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:08.406  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.406  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:59:08.406  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.406  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:08.406  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.406  3792  3792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 12:59:08.407  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.407  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:08.407  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.407  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.407  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:59:08.407  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:08.407  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.408  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:08.408  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:08.408  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.408  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.410  3792  3842 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 12:59:08.410  3792  3842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 12:59:08.410  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:59:08.413  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:59:08.413  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:59:08.414  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:59:08.415  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:08.415  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:59:08.416  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:08.417  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.417  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.418  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
08-30 12:59:08.419  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.421  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.421  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:59:08.422  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.423  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.423  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.424  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.427  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:08.427  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:08.427  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:08.428  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
,08-30 12:59:08.433  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:59:08.433  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:08.433  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:08.433  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:08.433  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.433  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.433  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
,08-30 12:59:08.433  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.434  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.434  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:08.434  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.434  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.434  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:08.434  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:08.436  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:59:08.436  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:08.436  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.436  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.437  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:59:08.437  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:59:08.437  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:59:08.437  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:59:08.438  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.438  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.438  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664f4a not in the list
,08-30 12:59:08.438  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.438  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.438  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:08.438  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:08.438  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.438  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:08.438  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:08.440  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:59:08.440  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:59:08.440  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:08.441  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f47ebb not in the list
08-30 12:59:08.442  3792  3842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 12:59:08.442  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:59:08.442  3792  3842 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-30 12:59:08.442  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:59:08.442  3792  3842 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 12:59:08.442  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:59:08.446  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:59:08.446  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 12:59:08.446  3792  3842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 12:59:08.447  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 12:59:08.447  3792  3842 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 12:59:08.447  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:59:08.447  3792  3842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 12:59:08.447  3792  3842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 12:59:08.448  3792  3842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 12:59:08.448  3792  3842 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 12:59:08.448  3792  3842 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 12:59:08.448  3792  3842 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 12:59:08.448  3792  3842 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 12:59:08.449  3792  3842 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 12:59:08.450  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:59:08.450  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5d91efa added. We now have 3 listener(s)
08-30 12:59:08.450  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:59:08.452  3792  3842 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 12:59:08.453   873  1736 D WifiService: setWifiEnabled: true pid=3792, uid=10000
08-30 12:59:08.453   873  1736 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:59:08.490  2682  2801 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 12:59:08.491  3792  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-30 12:59:08.491  2682  2818 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-30 12:59:08.907  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:59:11.954   873  1859 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 12:59:13.462  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:59:13.462  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43e8cab added. We now have 4 listener(s)
,08-30 12:59:13.463  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:59:13.480  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:13.481  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43e8cab removed from the list
08-30 12:59:13.481  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:59:13.481  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:13.481  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:13.485  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:59:13.486  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c02f08 added. We now have 4 listener(s)
08-30 12:59:13.486  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:59:13.490  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:13.491  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c02f08 removed from the list
08-30 12:59:13.491  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:13.491  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:13.491  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:13.493  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:59:13.493  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c58a6a1 added. We now have 4 listener(s)
,08-30 12:59:13.494  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:59:13.501   873  1392 D WifiService: setWifiEnabled: false pid=3792, uid=10000
,08-30 12:59:13.501   873  1392 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:59:13.519  2682  2703 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 12:59:13.519  2682  2703 D BluetoothAdapterProperties: Setting state to 13
,08-30 12:59:13.520  2682  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:59:13.521  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:59:13.522  2682  2703 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 12:59:13.525  2682  2703 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:59:13.528  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:59:13.530  2682  2707 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:59:13.531  2682  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 12:59:13.533  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:13.533  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:13.535  2682  2682 D BluetoothMapService: onReceive
08-30 12:59:13.535  2682  2682 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:59:13.536  2682  2682 D BluetoothMapService: STATE_TURNING_OFF
,08-30 12:59:13.536  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.536  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:13.537  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:59:13.537  2682  2682 D BluetoothMapService: MAP Service closeService in
08-30 12:59:13.537  2682  2682 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 12:59:13.537  2682  2682 D ObexServerSockets0: shutdown(block = true)
08-30 12:59:13.538  2682  2854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 12:59:13.540  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:13.540  2682  2682 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:59:13.540  2682  2855 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 12:59:13.540  2682  2818 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 12:59:13.541  2682  2682 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 12:59:13.541  2682  2682 I BtOppRfcommListener: stopping Accept Thread
08-30 12:59:13.541  2682  3420 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 12:59:13.542  2682  3420 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 12:59:13.542  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:13.542   873  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 12:59:13.543   873  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 12:59:13.543   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:59:13.543   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:59:13.547  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:13.547  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:13.548  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:13.549  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:13.554   873  1301 E native  : do suspend true
,08-30 12:59:13.555  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:13.555  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:13.557   873   886 I ActivityManager: Start proc 3883:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 12:59:13.558  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:13.558  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:13.561  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:13.564  2682  2682 D HeadsetService: Received stop request...Stopping profile...
,08-30 12:59:13.567  1934  2173 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:13.568   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:59:13.568   873  1862 D DhcpClient: Clearing IP address
,08-30 12:59:13.568  1346  1358 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:13.568  1346  1346 D HeadsetProfile: Bluetooth service disconnected
08-30 12:59:13.568  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.568  2682  2682 D A2dpService: Received stop request...Stopping profile...
08-30 12:59:13.568   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 12:59:13.569   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:13.569   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:13.569  2682  2839 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:59:13.570   873   873 D BluetoothA2dp: Proxy object disconnected
08-30 12:59:13.570  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-30 12:59:13.570  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.570  2682  2682 D HidService: Received stop request...Stopping profile...
,08-30 12:59:13.570  2682  2682 D HidService: Stopping Bluetooth HidService
08-30 12:59:13.571   372   871 D CommandListener: Setting iface cfg
08-30 12:59:13.573  2682  2682 D HealthService: Received stop request...Stopping profile...
08-30 12:59:13.573  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:13.576  1346  1346 D BluetoothInputDevice: Proxy object disconnected
,08-30 12:59:13.577   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:59:13.577   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 12:59:13.579   401   401 E Parcel  : Reading a NULL string not supported here.
08-30 12:59:13.579   873  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 12:59:13.580   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:59:13.580   873  1301 E native  : do suspend true
08-30 12:59:13.580   873  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 12:59:13.576  1346  1346 D HidProfile: Bluetooth service disconnected
,08-30 12:59:13.584  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:13.584  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:13.584  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:13.584  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:13.584   873  1875 D DhcpClient: Receive thread stopped
08-30 12:59:13.585  2682  2682 D PanService: Received stop request...Stopping profile...
08-30 12:59:13.586  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:59:13.586  1346  1346 D PanProfile: Bluetooth service disconnected
08-30 12:59:13.587  1512  2755 V NativeCrypto: Read error: ssl=0x9af50c00: I/O error during system call, Connection timed out
08-30 12:59:13.588  2682  2682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 12:59:13.589  2682  2682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:59:13.589  2682  2801 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:13.589  2682  2801 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:13.589  2682  2801 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:13.589  2682  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 12:59:13.589  2682  2707 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 12:59:13.590  1512  2755 V NativeCrypto: SSL shutdown failed: ssl=0x9af50c00: I/O error during system call, Broken pipe
08-30 12:59:13.591  2682  2682 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 12:59:13.593  2682  2682 D BluetoothMapService: stop()
08-30 12:59:13.596  2682  2682 D BluetoothMapAppObserver: deinitObservers()
08-30 12:59:13.596  2682  2682 D BluetoothMapAppObserver: removeReceiver()
08-30 12:59:13.597  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:13.597  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:13.598  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:13.598  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:13.599  2682  2801 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:13.599  2682  2801 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:13.599  2682  2801 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 12:59:13.599  2682  2801 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:59:13.599  2682  2801 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:59:13.599  2682  2801 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:59:13.599  2682  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 12:59:13.599  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:13.599  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:13.600  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:13.600  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:13.600  2682  2682 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:59:13.600  2682  2682 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:59:13.600  2682  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 12:59:13.601  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:13.601  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:13.601  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:13.601  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:13.602  2682  2682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:59:13.602  2682  2707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 12:59:13.602  2682  2682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:59:13.603  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:13.603  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:13.603  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:13.603  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:59:13.604  2682  2682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:59:13.604  2682  2682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:59:13.605  2682  2682 D BluetoothMapService: MAP Service closeService in
,08-30 12:59:13.606  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:13.606  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:13.606  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:13.606  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:13.606  2682  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 12:59:13.607  2682  2703 D BluetoothAdapterProperties: Setting state to 15
08-30 12:59:13.607  2682  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 12:59:13.607  2682  2682 D BluetoothMapService: cleanup()
,08-30 12:59:13.607  2682  2703 I BluetoothAdapterState: Entering BleOnState
08-30 12:59:13.607  2682  2682 D BluetoothMapService: MAP Service closeService in
08-30 12:59:13.608  1346  1369 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:59:13.609  1934  2173 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:13.609  1346  1365 D BluetoothPan: onBluetoothStateChange on: false
,08-30 12:59:13.611   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:13.611   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:13.612  1346  1358 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 12:59:13.614   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:13.614  1346  1369 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 12:59:13.615  1346  1346 D BluetoothMap: Proxy object disconnected
,08-30 12:59:13.615  1346  1346 D MapProfile: Bluetooth service disconnected
08-30 12:59:13.615   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:59:13.615  1346  1358 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:59:13.616  1346  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:13.616   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:13.617  2682  2703 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 12:59:13.617  2682  2703 D BluetoothAdapterProperties: Setting state to 16
08-30 12:59:13.617  2682  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 12:59:13.617  2682  2703 D BluetoothAdapterProperties: onBleDisable
08-30 12:59:13.617  2682  2703 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:59:13.617  2682  2704 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 12:59:13.619  2682  2801 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 12:59:13.619  2682  2801 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:13.620  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:13.620  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:13.621  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.621  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:13.621  2682  2707 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:59:13.622  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:13.623  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:13.623  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.623  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:13.625  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:13.625  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:13.626  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:13.626  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:13.627  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.628  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.629  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.630   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 12:59:13.630   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:59:13.631   873  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 12:59:13.631   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:59:13.633   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:59:13.634   873   890 D Tethering: MasterInitialState.processMessage what=3
08-30 12:59:13.636  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.638  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:13.638  3370  3370 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d724b10 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-30 12:59:13.639  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:13.652  3883  3883 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 12:59:13.658   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:59:13.661  2106  2296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:59:13.661  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:13.661  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:13.662   873  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:59:13.662  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.662  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:13.664  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:13.664  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:13.665  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:13.665  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:13.667  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:13.667  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:13.668  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:13.668  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:13.670  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:59:13.675  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:13.676   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9604a64:true
,08-30 12:59:13.688   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 12:59:13.688   873  1969 I ActivityManager: Start proc 3903:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-30 12:59:13.688   873  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 12:59:13.721  3883  3883 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 12:59:13.730  3883  3883 D BluetoothMap: Create BluetoothMap proxy object
,08-30 12:59:13.733  3903  3903 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 12:59:13.739  3883  3883 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 12:59:13.755  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:59:13.761   873   884 I ActivityManager: Killing 3370:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 12:59:13.820  2682  2707 I bt_hci  : shut_down
,08-30 12:59:13.821  2682  2711 D bt_hwcfg: hw_epilog_process
,08-30 12:59:13.831  2682  2711 I bt_vendor: low_power_mode_cb
,08-30 12:59:13.851  2682  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 12:59:13.851  2682  2711 I bt_vendor: epilog_cb
,08-30 12:59:13.852  2682  2711 I bt_hci  : epilog_finished_callback
08-30 12:59:13.857  2682  2707 I bt_hci_h4: hal_close
08-30 12:59:13.858  2682  2707 I bt_userial_vendor: device fd = 51 close
,08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.919  3903  3903 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.919  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.920  3903  3903 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:59:13.920  3903  3903 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:59:13.929  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:59:13.937  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:59:13.956  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:59:13.967   873  1392 I ActivityManager: Killing 3560:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 12:59:14.017  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:59:14.023  1723  1723 D SystemUpdateService: onCreate
,08-30 12:59:14.027  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:59:14.027  2682  2704 D bt_stack_manager: event_shut_down_stack finished.
08-30 12:59:14.028  2682  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 12:59:14.035  2682  2703 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 12:59:14.035  2682  2682 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:59:14.037  2682  2682 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 12:59:14.038  2682  2682 D BtGatt.GattService: stop()
08-30 12:59:14.038  2682  2682 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 12:59:14.039  1723  3934 I SystemUpdateService: active receiver: enabled
,08-30 12:59:14.040  2682  2682 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:14.040  2682  2682 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:59:14.040  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:14.040  2682  2682 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 12:59:14.040  2682  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 12:59:14.041  2682  2703 D BluetoothAdapterProperties: Setting state to 10
08-30 12:59:14.041  2682  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 12:59:14.041  2682  2703 I BluetoothAdapterState: Entering OffState
08-30 12:59:14.043   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 12:59:14.047  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 12:59:14.050  1723  2414 I iu.UploadsManager: num queued entries: 0
,08-30 12:59:14.051  1723  2414 I iu.UploadsManager: num updated entries: 0
,08-30 12:59:14.057  2682  2682 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 12:59:14.057  2682  2682 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 12:59:14.057  2682  2682 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 12:59:14.058  2682  2704 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 12:59:14.061  2682  2704 D bt_stack_manager: event_clean_up_stack finished.
,08-30 12:59:14.069  1723  3934 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:59:14.071  2682  2682 I art     : System.exit called, status: 0
,08-30 12:59:14.071  2682  2682 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:59:14.083  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:59:14.084  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:59:14.086  1723  2414 I iu.SyncManager: NEXT; no task
,08-30 12:59:14.086  1723  3934 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 12:59:14.086  1723  3934 I SystemUpdateService: now status is 0 (complete)
,08-30 12:59:14.086  1723  3934 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 12:59:14.086  1723  3934 I SystemUpdateService: file has been verified
,08-30 12:59:14.086  1723  3934 I SystemUpdateService: OTA package size = 12249756
,08-30 12:59:14.099  1723  3934 I SystemUpdateService: showing system update notification
,08-30 12:59:14.122   873  1986 I ActivityManager: Start proc 3937:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 12:59:14.145   873  1986 I ActivityManager: Process com.android.bluetooth (pid 2682) has died
,08-30 12:59:14.161  1723  1723 D SystemUpdateService: onDestroy
,08-30 12:59:14.184  3937  3937 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 12:59:14.193  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:59:14.211  3937  3937 D SprintDMHelper: simOperator: 
08-30 12:59:14.211  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:59:14.235   873   883 I ActivityManager: Start proc 3952:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 12:59:14.340   873  1999 I ActivityManager: Start proc 3968:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 12:59:14.342  2453  3967 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 12:59:14.344   873  1392 I ActivityManager: Killing 3439:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 12:59:14.360  3903  3920 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 12:59:14.380   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4077473:true
,08-30 12:59:14.402  3968  3968 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 12:59:14.463  3968  3968 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 12:59:14.463  3968  3968 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 12:59:14.463  3968  3968 I GAv4    :   adb logcat -s GAv4
,08-30 12:59:14.481  3968  3968 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:59:14.487  3968  3968 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:59:14.527  3968  3985 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:59:14.636  3968  3968 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 12:59:14.678  3968  3968 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 12:59:14.690  3968  3968 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 394-401)
08-30 12:59:14.690  3968  3968 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 12:59:14.701  3968  3968 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c769840}
,08-30 12:59:14.701  3968  3968 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:59:14.702  3968  3968 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 12:59:14.711  3968  3968 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 12:59:14.712  3968  3968 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 12:59:14.729  3968  3968 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 12:59:14.744  3968  3968 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:59:14.744  3968  3968 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:59:14.744  3968  3968 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:59:14.744  3968  3968 I Adreno  : Build Date                       : 10/20/15
08-30 12:59:14.744  3968  3968 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:59:14.744  3968  3968 I Adreno  : Local Branch                     : M14
08-30 12:59:14.744  3968  3968 I Adreno  : Remote Branch                    : 
08-30 12:59:14.744  3968  3968 I Adreno  : Remote Branch                    : 
08-30 12:59:14.744  3968  3968 I Adreno  : Reconstruct Branch               : 
,08-30 12:59:14.810  3968  3968 I NSApplication: Starting up...
,08-30 12:59:14.818  3968  4014 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 12:59:14.856   873  1736 I ActivityManager: Start proc 4019:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 12:59:14.858   873  1736 I ActivityManager: Killing 3489:android.process.acore/u0a5 (adj 15): empty #17
,08-30 12:59:14.926  4019  4019 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 12:59:15.105   873  1986 I ActivityManager: Killing 3647:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 12:59:15.219   873  1375 I ActivityManager: Start proc 4033:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 12:59:15.268  4033  4033 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 12:59:15.311  4033  4033 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 12:59:15.331   873  1975 I ActivityManager: Killing 3664:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 12:59:16.963  1512  3872 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-30 12:59:18.539   873  1968 D WifiService: setWifiEnabled: true pid=3792, uid=10000
,08-30 12:59:18.540   873  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-30 12:59:18.559   873  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-30 12:59:18.587  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:18.588  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:18.588  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:18.588  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:18.589  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:18.589  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:18.589  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:18.589  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:18.590  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:18.590  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:18.591  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:18.591  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:18.600   873  1301 D WifiConfigStore: loaded 0 passpoint configs
08-30 12:59:18.602   873  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 12:59:18.603   873  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 12:59:18.603   873  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 12:59:18.604   873  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 12:59:18.604   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 12:59:18.604   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 12:59:18.624   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 12:59:18.625   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:59:18.627   372   871 D CommandListener: Setting iface cfg
,08-30 12:59:18.634   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 12:59:18.634   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 12:59:18.635   873  1301 E native  : do suspend true
,08-30 12:59:18.648   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:59:18.666   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:59:18.666   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 12:59:19.313   873   883 I ActivityManager: Killing 2228:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 12:59:20.017   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:59:20.045   873  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.62 rxSuccessRate=4.50 delta 1000 -> 1000
,08-30 12:59:20.047   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 12:59:20.047   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:59:20.069   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 12:59:20.111   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 12:59:20.113  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 12:59:20.569  1449  1449 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:59:20.613  1449  1449 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 12:59:20.615  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 12:59:20.621   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:59:20.638   873  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:59:20.639   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 12:59:20.639   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:59:20.661   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:59:20.680   372   871 D CommandListener: Setting iface cfg
,08-30 12:59:20.681   873  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 12:59:20.690   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 12:59:20.708   873  4068 D DhcpClient: Receive thread started
,08-30 12:59:20.792   873  1301 E native  : do suspend false
,08-30 12:59:20.812   873  1862 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 12:59:20.828   873  4068 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172645, domain null
,08-30 12:59:20.829   873  1862 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172645 seconds
,08-30 12:59:20.834   873  1862 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 12:59:20.852   873  4068 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 12:59:20.853   873  1862 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 12:59:20.859   372   871 D CommandListener: Setting iface cfg
,08-30 12:59:20.870   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 12:59:20.870   873  1862 D DhcpClient: Scheduling renewal in 86399s
,08-30 12:59:20.873   873  1301 E native  : do suspend true
,08-30 12:59:20.893   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 12:59:20.896   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:59:20.897   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 12:59:20.900   873  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 12:59:20.908   873  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 12:59:20.969   873  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 12:59:20.970   873  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 12:59:20.973   873  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 12:59:20.975   873  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 12:59:20.979   873  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 12:59:20.989   873  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 12:59:20.998   873  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 12:59:20.998   873  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 12:59:20.998   873  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 12:59:20.998   873  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 12:59:20.998   873  1303 D ConnectivityService:    accepting network in place of null
08-30 12:59:20.999   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:59:20.999   873  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:59:21.023   873  4067 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176733, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 12:59:21.029   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:21.076   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:21.086   873  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 12:59:21.086   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:59:21.100   873   890 D Tethering: MasterInitialState.processMessage what=3
08-30 12:59:21.100   873  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 12:59:21.103   873  4066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:400d:802::200e
08-30 12:59:21.119  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:21.119  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:21.119  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:21.120  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:21.131  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:21.131  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:21.131  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:21.131  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:21.133  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:21.133  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:21.133  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:21.133  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:21.148  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 12:59:21.152  1723  1723 D SystemUpdateService: onCreate
08-30 12:59:21.155  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 12:59:21.158  3745  4078 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 12:59:21.172  1723  4079 I SystemUpdateService: active receiver: enabled
,08-30 12:59:21.176  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 12:59:21.180  1723  2414 I iu.UploadsManager: num queued entries: 0
,08-30 12:59:21.180  1723  2414 I iu.UploadsManager: num updated entries: 0
08-30 12:59:21.181  1723  2414 I iu.SyncManager: NEXT; no task
,08-30 12:59:21.189  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:59:21.190  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:59:21.196  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:59:21.200  1723  4082 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 12:59:21.200  1723  4082 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 12:59:21.201  1723  4079 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:59:21.202  1723  4082 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:59:21.205  3937  3937 D SprintDMHelper: simOperator: 
,08-30 12:59:21.205  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:59:21.222  1723  4079 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 12:59:21.222  1723  4079 I SystemUpdateService: now status is 0 (complete)
,08-30 12:59:21.222  1723  4079 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:59:21.222  1723  4079 I SystemUpdateService: file has been verified
,08-30 12:59:21.223  1723  4079 I SystemUpdateService: OTA package size = 12249756
,08-30 12:59:21.226  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-30 12:59:21.228  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:21.234   873  4066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:59:21 GMT], X-Android-Received-Millis=[1472554761233], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472554761180]}
,08-30 12:59:21.238   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 12:59:21.238   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-30 12:59:21.239   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 12:59:21.242   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 12:59:21.264  1723  4079 I SystemUpdateService: showing system update notification
,08-30 12:59:21.281  3745  4090 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 12:59:21.303  1512  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:59:21.303  1512  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 12:59:21.303  1512  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:21.303  1512  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-30 12:59:21.333  1512  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:59:21.333  1512  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 12:59:21.333  1512  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:21.333  1512  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:21.346  2453  4086 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 12:59:21.349  3745  4090 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 12:59:21.349  3745  4078 E BooksSync: Soft error
08-30 12:59:21.349  3745  4078 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:59:21.349  3745  4078 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 12:59:21.350  3745  4078 E BooksSync: Sync error
08-30 12:59:21.350  3745  4078 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:59:21.350  3745  4078 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 12:59:21.350  3745  4078 I BooksSync: Finished books sync
,08-30 12:59:21.362   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159433, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:59:21.366  1512  2281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 12:59:21.366  1512  2281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 12:59:21.366  1512  2281 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:59:21.366  1512  2281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-30 12:59:21.384  1723  1723 D SystemUpdateService: onDestroy
,08-30 12:59:21.390  1723  4082 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-30 12:59:22.084   873  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 12:59:23.547   873  1968 D WifiService: setWifiEnabled: false pid=3792, uid=10000
,08-30 12:59:23.547   873  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:59:23.586  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:59:23.594   873  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 12:59:23.594   873  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 12:59:23.595   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:59:23.596   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:59:23.620   873  1301 E native  : do suspend true
,08-30 12:59:23.630   873  1862 D DhcpClient: Clearing IP address
,08-30 12:59:23.630   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:59:23.634   372   871 D CommandListener: Setting iface cfg
,08-30 12:59:23.638  1512  4093 V NativeCrypto: Read error: ssl=0x9af50c00: I/O error during system call, Connection timed out
,08-30 12:59:23.641   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:59:23.641   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 12:59:23.642  1512  4093 V NativeCrypto: SSL shutdown failed: ssl=0x9af50c00: I/O error during system call, Broken pipe
,08-30 12:59:23.647   401   401 E Parcel  : Reading a NULL string not supported here.
,08-30 12:59:23.650   873  4068 D DhcpClient: Receive thread stopped
08-30 12:59:23.653   873  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 12:59:23.654   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:59:23.655   873  1301 E native  : do suspend true
08-30 12:59:23.659   873  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 12:59:23.698   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:23.731   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:23.732   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:59:23.736   873  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 12:59:23.736   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:59:23.738   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:59:23.747  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:23.747   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:23.747  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:23.748  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.748  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:23.752  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:23.752  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:23.753  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:23.754  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:23.757  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:23.758  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:23.758  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.758  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:23.769   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 12:59:23.771  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:23.772  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:23.772  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.772  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:23.773  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:23.773  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:23.773  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.773  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:23.774   873  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:59:23.774  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:23.774  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:23.774  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:23.774  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:23.775  2106  2296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:59:23.776  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 12:59:23.788  1723  1723 D SystemUpdateService: onCreate
08-30 12:59:23.792  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 12:59:23.801  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 12:59:23.804  1723  2414 I iu.UploadsManager: num queued entries: 0
08-30 12:59:23.804  1723  2414 I iu.UploadsManager: num updated entries: 0
08-30 12:59:23.807  1723  4102 I SystemUpdateService: active receiver: enabled
08-30 12:59:23.809  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 12:59:23.812  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 12:59:23.814  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:59:23.818  3937  3937 D SprintDMHelper: simOperator: 
08-30 12:59:23.818  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 12:59:23.824  1723  4102 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-30 12:59:23.825  1723  2414 I iu.SyncManager: NEXT; no task
08-30 12:59:23.834  2453  4106 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-30 12:59:23.836   372   871 E Netd    : netlink response contains error (No such file or directory)
08-30 12:59:23.836   873  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 12:59:23.838  1723  4102 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 12:59:23.838  1723  4102 I SystemUpdateService: now status is 0 (complete)
08-30 12:59:23.838  1723  4102 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:59:23.839  1723  4102 I SystemUpdateService: file has been verified
08-30 12:59:23.842  1723  4102 I SystemUpdateService: OTA package size = 12249756
,08-30 12:59:23.859  1723  4102 I SystemUpdateService: showing system update notification
,08-30 12:59:23.867  1723  1723 D SystemUpdateService: onDestroy
,08-30 12:59:28.605   873   890 I ActivityManager: Start proc 4109:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 12:59:28.733  4109  4109 D AdapterServiceConfig: Adding HeadsetService
,08-30 12:59:28.734  4109  4109 D AdapterServiceConfig: Adding A2dpService
08-30 12:59:28.734  4109  4109 D AdapterServiceConfig: Adding HidService
,08-30 12:59:28.734  4109  4109 D AdapterServiceConfig: Adding HealthService
,08-30 12:59:28.735  4109  4109 D AdapterServiceConfig: Adding PanService
08-30 12:59:28.736  4109  4109 D AdapterServiceConfig: Adding GattService
08-30 12:59:28.737  4109  4109 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 12:59:28.759   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e2a2ebd:true
08-30 12:59:28.759  4109  4109 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 12:59:28.763  4109  4109 I bt_bluedroid: init
08-30 12:59:28.763  4109  4121 I BluetoothAdapterState: Entering OffState
,08-30 12:59:28.766  4109  4122 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 12:59:28.766  4109  4122 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:59:28.766  4109  4122 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:59:28.767  4109  4122 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 12:59:28.767  4109  4109 I bt_bluedroid: get_profile_interface socket
,08-30 12:59:28.770  4109  4125 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:59:28.772  4109  4125 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:59:28.772  4109  4109 I bt_bluedroid: get_profile_interface sdp
,08-30 12:59:28.778  4109  4120 I bt_bluedroid: config_hci_snoop_log
,08-30 12:59:28.781   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 12:59:28.790  4109  4121 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 12:59:28.790  4109  4121 D BluetoothAdapterProperties: Setting state to 14
08-30 12:59:28.791  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 12:59:28.793  4109  4121 D BluetoothBondStateMachine: make
,08-30 12:59:28.797  4109  4126 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 12:59:28.801  4109  4121 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:59:28.805  4109  4109 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 12:59:28.813  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:28.815  4109  4109 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:59:28.817  4109  4109 D BtGatt.GattService: Received start request. Starting profile...
,08-30 12:59:28.817  4109  4109 D BtGatt.GattService: start()
,08-30 12:59:28.818  4109  4109 I bt_bluedroid: get_profile_interface gatt,
08-30 12:59:28.820  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
08-30 12:59:28.820  4109  4109 D BtGatt.AdvertiseManager: advertise manager created
,08-30 12:59:28.839  4109  4109 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:28.839  4109  4109 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:59:28.839  4109  4109 V BluetoothAdapterState: isBleTurningOn()=true
08-30 12:59:28.840  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:28.841  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 12:59:28.843  4109  4121 I bt_bluedroid: enable
,08-30 12:59:28.843  4109  4122 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 12:59:28.844  4109  4122 I bt_hci  : start_up
,08-30 12:59:28.867  4109  4122 I bt_vendor: alloc value 0xb39ed189
08-30 12:59:28.868  4109  4122 I bt_vendor: init
08-30 12:59:28.868  4109  4122 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 12:59:28.868  4109  4122 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 12:59:28.977  4109  4122 D bt_hci  : start_up starting async portion
,08-30 12:59:28.978  4109  4129 I bt_hci  : event_finish_startup
08-30 12:59:28.978  4109  4129 I bt_hci_h4: hal_open
08-30 12:59:28.978  4109  4129 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 12:59:28.991  4109  4129 I bt_userial_vendor: device fd = 51 open
,08-30 12:59:29.003   873  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-30 12:59:29.021  4109  4129 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:59:29.052  4109  4129 D bt_hwcfg: Chipset BCM4354A2
08-30 12:59:29.053  4109  4129 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 12:59:29.054  4109  4129 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 12:59:29.902  4109  4129 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 12:59:29.903  4109  4129 D bt_hwcfg: Settlement delay -- 100 ms
08-30 12:59:29.904  4109  4129 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 12:59:30.022  4109  4129 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:59:30.024  4109  4129 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 12:59:30.050  4109  4129 I bt_hwcfg: vendor lib fwcfg completed
,08-30 12:59:30.051  4109  4129 I bt_vendor: firmware callback
08-30 12:59:30.051  4109  4129 I bt_hci  : firmware_config_callback
,08-30 12:59:30.064  4109  4132 I bt_btu  : btu_task pending for preload complete event
,08-30 12:59:30.064  4109  4132 I bt_btu_task: Bluetooth chip preload is complete
08-30 12:59:30.064  4109  4132 I bt_btu  : btu_task received preload complete event
,08-30 12:59:30.075  4109  4132 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 12:59:30.076  4109  4132 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 12:59:30.076  4109  4132 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 12:59:30.076  4109  4132 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 12:59:30.077  4109  4132 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:59:30.077  4109  4132 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 12:59:30.077  4109  4132 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 12:59:30.078  4109  4132 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 12:59:30.078  4109  4132 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 12:59:30.078  4109  4132 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:59:30.078  4109  4132 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 12:59:30.079  4109  4132 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 12:59:30.079  4109  4132 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 12:59:30.079  4109  4132 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:59:30.079  4109  4132 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:59:30.230  4109  4132 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ad9d
,08-30 12:59:30.231  4109  4132 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ad9d 
,08-30 12:59:30.243  4109  4125 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 12:59:30.245  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 12:59:30.246  4109  4125 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:59:30.250  4109  4125 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:59:30.255  4109  4125 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:59:30.256  4109  4125 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:59:30.257  4109  4125 D bt_hci  : do_postload posting postload work item
,08-30 12:59:30.257  4109  4129 I bt_hci  : event_postload
,08-30 12:59:30.257  4109  4129 I bt_vendor: sco_config_cb
08-30 12:59:30.257  4109  4129 I bt_hci  : sco_config_callback postload finished.
08-30 12:59:30.259  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:30.261  4109  4125 D bt_bte_conf: Device ID record 1 : primary
08-30 12:59:30.262  4109  4125 D bt_bte_conf:   vendorId            = 000f
08-30 12:59:30.262  4109  4125 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 12:59:30.262  4109  4125 D bt_bte_conf:   product             = 1200
08-30 12:59:30.264  4109  4125 D bt_bte_conf:   version             = 1436
,08-30 12:59:30.264  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:30.264  4109  4125 D bt_bte_conf:   clientExecutableURL = 
08-30 12:59:30.265  4109  4125 D bt_bte_conf:   serviceDescription  = 
,08-30 12:59:30.265  4109  4125 D bt_bte_conf:   documentationURL    = 
08-30 12:59:30.265  4109  4125 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 12:59:30.265  4109  4122 D bt_stack_manager: event_start_up_stack finished
08-30 12:59:30.266  4109  4129 I bt_vendor: low_power_mode_cb
,08-30 12:59:30.266  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 12:59:30.267  4109  4121 D BluetoothAdapterProperties: Setting state to 15
08-30 12:59:30.267  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 12:59:30.268  4109  4121 I BluetoothAdapterState: Entering BleOnState
08-30 12:59:30.268  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:30.271  4109  4121 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 12:59:30.271  4109  4121 D BluetoothAdapterProperties: Setting state to 11
08-30 12:59:30.271  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 12:59:30.276  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
08-30 12:59:30.278  4109  4109 D HeadsetService: Received start request. Starting profile...
,08-30 12:59:30.279  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:30.281  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:30.284  4109  4109 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:59:30.284  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:30.284  4109  4109 D HeadsetStateMachine: make
08-30 12:59:30.293  4109  4121 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:59:30.295  4109  4109 D HeadsetStateMachine: max_hf_connections = 1
,08-30 12:59:30.295  4109  4109 I bt_bluedroid: get_profile_interface handsfree
08-30 12:59:30.295  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 12:59:30.295  4109  4125 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 12:59:30.299  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
08-30 12:59:30.299  4109  4109 D A2dpService: Received start request. Starting profile...
,08-30 12:59:30.300  4109  4109 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:59:30.301  4109  4109 I bt_bluedroid: get_profile_interface avrcp
,08-30 12:59:30.308  4109  4109 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 12:59:30.308  4109  4109 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 12:59:30.308  4109  4109 D A2dpStateMachine: make
08-30 12:59:30.310  4109  4109 I bt_bluedroid: get_profile_interface a2dp
,08-30 12:59:30.310  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 12:59:30.312  4109  4141 D A2dpStateMachine: Enter Disconnected: -2
,08-30 12:59:30.314  4109  4109 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 12:59:30.314  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:30.316  3883  3883 D BluetoothInputDevice: Proxy object connected
,08-30 12:59:30.317  4109  4109 D HidService: Received start request. Starting profile...
08-30 12:59:30.317  3883  3883 D HidProfile: Bluetooth service connected
08-30 12:59:30.317  4109  4109 I bt_bluedroid: get_profile_interface hidhost
08-30 12:59:30.317  4109  4125 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394c3e5
08-30 12:59:30.317  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 12:59:30.317  4109  4109 D HidService: setHidService(): set to: null
08-30 12:59:30.318  4109  4109 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 12:59:30.319  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
08-30 12:59:30.319  4109  4109 D HealthService: Received start request. Starting profile...
,08-30 12:59:30.321  4109  4109 I bt_bluedroid: get_profile_interface health
,08-30 12:59:30.323  4109  4109 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 12:59:30.324  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
08-30 12:59:30.325  4109  4109 D PanService: Received start request. Starting profile...
08-30 12:59:30.325  4109  4109 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:59:30.325  4109  4109 I bt_bluedroid: get_profile_interface pan
08-30 12:59:30.326  4109  4125 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 12:59:30.326  3883  3883 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 12:59:30.327  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:30.329  3883  3883 D PanProfile: Bluetooth service connected
,08-30 12:59:30.330  4109  4109 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:30.332  4109  4109 D BluetoothMapService: Received start request. Starting profile...
,08-30 12:59:30.332  3883  3883 D BluetoothMap: Proxy object connected
08-30 12:59:30.332  4109  4109 D BluetoothMapService: start()
08-30 12:59:30.332  3883  3883 D MapProfile: Bluetooth service connected
,08-30 12:59:30.332  3883  3883 D BluetoothMap: getConnectedDevices()
08-30 12:59:30.333  3883  3883 D BluetoothMap: Bluetooth is Not enabled
08-30 12:59:30.334  4109  4109 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 12:59:30.335  4109  4109 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 12:59:30.335  4109  4109 D BluetoothMapAppObserver: createReceiver()
,08-30 12:59:30.336  4109  4109 D BluetoothMapAppObserver: initObservers()
08-30 12:59:30.336  4109  4109 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 12:59:30.343  4109  4109 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:30.343  4109  4109 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:30.344  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:30.344  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:30.346  4109  4139 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:30.346  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isTurningOff()=false,
,08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:30.347  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:30.350  4109  4109 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:30.350  4109  4109 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:30.350  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:30.350  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:30.350  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 12:59:30.350  4109  4121 D BluetoothAdapterProperties: ScanMode =  20
,08-30 12:59:30.350  4109  4121 D BluetoothAdapterProperties: State =  11
,08-30 12:59:30.354  4109  4125 D BluetoothAdapterProperties: Scan Mode:21
,08-30 12:59:30.355  4109  4125 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:59:30.355  4109  4121 D BluetoothAdapterProperties: Setting state to 12
08-30 12:59:30.355  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 12:59:30.355  4109  4121 I BluetoothAdapterState: Entering OnState
08-30 12:59:30.356  3883  3894 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 12:59:30.356  1346  1369 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:59:30.358  3883  3893 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:59:30.360  1346  1346 D BluetoothA2dp: Proxy object connected
,08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:30.363  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:30.363  1934  2062 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:30.364  4109  4109 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:59:30.364  1346  1365 D BluetoothPan: onBluetoothStateChange on: true
,08-30 12:59:30.365  4109  4109 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 12:59:30.365  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:30.367  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:59:30.367   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:59:30.367  1346  1346 D PanProfile: Bluetooth service connected
08-30 12:59:30.367   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:30.367  4109  4109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:59:30.367  3883  3894 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:59:30.368  1346  1358 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:30.370  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:30.370  4109  4109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:59:30.371  1346  1346 D BluetoothInputDevice: Proxy object connected
,08-30 12:59:30.371  1346  1346 D HidProfile: Bluetooth service connected
08-30 12:59:30.371  3883  3893 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:59:30.372  1346  1365 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:59:30.372  4109  4109 D ObexServerSockets: Succeed to create listening sockets 
08-30 12:59:30.373  4109  4109 D ObexServerSockets0: startAccept()
,08-30 12:59:30.373  4109  4109 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:59:30.374  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:30.374   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 12:59:30.375  1346  1369 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 12:59:30.375   873   873 D BluetoothA2dp: Proxy object connected
08-30 12:59:30.376  4109  4109 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 12:59:30.377  4109  4109 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 12:59:30.378  1346  1346 D BluetoothMap: Proxy object connected
08-30 12:59:30.378  1346  1346 D MapProfile: Bluetooth service connected
08-30 12:59:30.378  1346  1346 D BluetoothMap: getConnectedDevices()
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:30.378  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:30.379  4109  4146 D ObexServerSockets0: Accepting socket connection...
08-30 12:59:30.380  1346  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:30.380   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:30.381  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:30.381   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 12:59:30.383  4109  4109 D BluetoothMapService: onReceive
08-30 12:59:30.383  4109  4109 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:59:30.383  4109  4109 D BluetoothMapService: STATE_ON
,08-30 12:59:30.383  4109  4147 D ObexServerSockets0: Accepting socket connection...
08-30 12:59:30.385  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:30.387  3883  3883 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 12:59:30.387  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:30.388  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:30.397  3883  3883 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 12:59:30.404  4109  4109 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:59:30.404  4109  4109 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:59:30.406  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:59:30.409  3883  3883 D BluetoothA2dp: Proxy object connected
,08-30 12:59:30.414  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:30.421  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:59:30.421  1346  1346 D BluetoothPbap: Proxy object connected
08-30 12:59:30.421  1346  1346 D PbapServerProfile: Bluetooth service connected
,08-30 12:59:30.422  3883  3883 D BluetoothPbap: Proxy object connected
,08-30 12:59:30.424  3883  3883 D PbapServerProfile: Bluetooth service connected
,08-30 12:59:30.425  4109  4152 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:59:30.457  4109  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:59:30.458  4109  4158 I BtOppRfcommListener: Accept thread started.
,08-30 12:59:30.466  1934  2173 D BluetoothHeadset: Proxy object connected
,08-30 12:59:30.467  1346  1358 D BluetoothHeadset: Proxy object connected
,08-30 12:59:30.467  1346  1346 D HeadsetProfile: Bluetooth service connected
08-30 12:59:30.467   873   890 D BluetoothHeadset: Proxy object connected
08-30 12:59:30.467   873   873 D BluetoothHeadset: Proxy object connected
,08-30 12:59:30.467   873   890 D BluetoothHeadset: Proxy object connected
08-30 12:59:30.467   873   873 D BluetoothHeadset: Proxy object connected
08-30 12:59:30.467   873   873 D BluetoothHeadset: Proxy object connected
,08-30 12:59:30.480  1346  1369 D BluetoothHeadset: Proxy object connected
,08-30 12:59:30.480  1346  1346 D HeadsetProfile: Bluetooth service connected
08-30 12:59:30.480   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:59:30.501  3883  3894 D BluetoothHeadset: Proxy object connected
08-30 12:59:30.503  3883  3883 D HeadsetProfile: Bluetooth service connected
,08-30 12:59:32.131  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:32.143  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:32.147  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:32.193  1512  3043 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:59:32.194  1512  3043 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 12:59:32.194  1512  3043 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:59:32.194  1512  3043 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:32.233  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 12:59:32.234  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 12:59:32.234  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 12:59:33.573  4109  4121 D BluetoothAdapterState: Current state: ON, message: 23
08-30 12:59:33.573  4109  4121 D BluetoothAdapterProperties: Setting state to 13
,08-30 12:59:33.574  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:59:33.576  4109  4121 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 12:59:33.580  4109  4121 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:59:33.586  4109  4109 D BluetoothMapService: onReceive
,08-30 12:59:33.587  4109  4109 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:59:33.587  4109  4109 D BluetoothMapService: STATE_TURNING_OFF,
08-30 12:59:33.588  4109  4109 D BluetoothMapService: MAP Service closeService in
08-30 12:59:33.588  4109  4109 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 12:59:33.589  4109  4109 D ObexServerSockets0: shutdown(block = true)
08-30 12:59:33.589  4109  4146 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 12:59:33.595  4109  4109 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:59:33.595  4109  4109 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:59:33.595  4109  4134 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 12:59:33.600  4109  4125 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:59:33.601  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 12:59:33.598  4109  4147 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 12:59:33.603  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:33.603  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:33.604  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:33.604  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:33.607  4109  4109 D HeadsetService: Received stop request...Stopping profile...
,08-30 12:59:33.608  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:33.608  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:33.610  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:59:33.611  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:33.611  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:33.613  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:33.613  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:33.615  1934  1949 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:33.615  4109  4109 D A2dpService: Received stop request...Stopping profile...
08-30 12:59:33.615  1346  1358 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:33.615  4109  4141 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:59:33.615  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:59:33.615   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:33.615   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 12:59:33.615  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:33.616   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:33.616  3883  3894 D BluetoothHeadset: Proxy object disconnected
08-30 12:59:33.620  1346  1346 D HeadsetProfile: Bluetooth service disconnected
08-30 12:59:33.620   873   873 D BluetoothA2dp: Proxy object disconnected
08-30 12:59:33.620  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:33.621  4109  4109 I BtOppRfcommListener: stopping Accept Thread
08-30 12:59:33.621  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-30 12:59:33.621  4109  4158 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:59:33.621  4109  4158 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:59:33.622  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:33.623  4109  4109 D HidService: Received stop request...Stopping profile...
08-30 12:59:33.623  4109  4109 D HidService: Stopping Bluetooth HidService
08-30 12:59:33.624  1346  1346 D BluetoothInputDevice: Proxy object disconnected
08-30 12:59:33.624  1346  1346 D HidProfile: Bluetooth service disconnected
08-30 12:59:33.624  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:33.624  4109  4109 D HealthService: Received stop request...Stopping profile...
08-30 12:59:33.625  4109  4109 D PanService: Received stop request...Stopping profile...
08-30 12:59:33.626  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:59:33.626  1346  1346 D PanProfile: Bluetooth service disconnected
08-30 12:59:33.627  4109  4109 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:59:33.627  4109  4109 D BluetoothMapService: stop()
08-30 12:59:33.627  3883  3883 D DockEventReceiver: finishStartingService: stopping service
08-30 12:59:33.627  4109  4109 D BluetoothMapAppObserver: deinitObservers()
08-30 12:59:33.628  4109  4109 D BluetoothMapAppObserver: removeReceiver()
08-30 12:59:33.628  3883  3883 D HeadsetProfile: Bluetooth service disconnected
08-30 12:59:33.628  3883  3883 D BluetoothA2dp: Proxy object disconnected
08-30 12:59:33.629  1346  1346 D BluetoothMap: Proxy object disconnected
08-30 12:59:33.629  1346  1346 D MapProfile: Bluetooth service disconnected
08-30 12:59:33.629  4109  4109 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:33.629  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:33.629  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:33.629  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:33.629  3883  3883 D BluetoothInputDevice: Proxy object disconnected
08-30 12:59:33.630  3883  3883 D HidProfile: Bluetooth service disconnected
,08-30 12:59:33.633  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:33.633  4109  4109 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:59:33.633  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 12:59:33.633  4109  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:33.633  4109  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:33.633  4109  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:33.633  4109  4125 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 12:59:33.633  4109  4109 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:59:33.634  4109  4109 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:33.634  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:33.634  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:33.634  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:33.634  3883  3883 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:59:33.634  3883  3883 D PanProfile: Bluetooth service disconnected
08-30 12:59:33.635  4109  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:33.635  3883  3883 D BluetoothMap: Proxy object disconnected
08-30 12:59:33.635  4109  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:33.636  4109  4132 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:59:33.636  4109  4132 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:59:33.636  4109  4132 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:59:33.636  4109  4132 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:59:33.636  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 12:59:33.636  3883  3883 D MapProfile: Bluetooth service disconnected
,08-30 12:59:33.638  4109  4109 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:33.638  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:33.638  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:33.638  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:33.638  4109  4109 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:59:33.638  4109  4125 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 12:59:33.639  4109  4109 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 12:59:33.639  4109  4109 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:33.639  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:33.639  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:33.639  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:33.639  4109  4109 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 12:59:33.639  4109  4125 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 12:59:33.640  4109  4109 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:59:33.640  4109  4109 V BluetoothAdapterState: isTurningOff()=true
08-30 12:59:33.640  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:33.640  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:33.640  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:33.640  4109  4109 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:59:33.641  4109  4109 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:59:33.641  4109  4109 D BluetoothMapService: MAP Service closeService in
08-30 12:59:33.641  4109  4109 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:59:33.642  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:33.642  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:33.642  4109  4109 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:33.642  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 12:59:33.642  4109  4121 D BluetoothAdapterProperties: Setting state to 15
08-30 12:59:33.642  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 12:59:33.642  4109  4109 D BluetoothMapService: cleanup()
,08-30 12:59:33.642  4109  4109 D BluetoothMapService: MAP Service closeService in
08-30 12:59:33.643  3883  3893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:59:33.643  4109  4121 I BluetoothAdapterState: Entering BleOnState
08-30 12:59:33.643  3883  3894 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:59:33.644  1346  1346 D BluetoothPbap: Proxy object disconnected,
08-30 12:59:33.644  1346  1346 D PbapServerProfile: Bluetooth service disconnected
08-30 12:59:33.645  1346  1365 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:59:33.645  3883  3883 D BluetoothPbap: Proxy object disconnected
08-30 12:59:33.645  3883  3883 D PbapServerProfile: Bluetooth service disconnected
08-30 12:59:33.646  3883  3894 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:59:33.647  1934  2062 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:33.647  1346  1358 D BluetoothPan: onBluetoothStateChange on: false
,08-30 12:59:33.648   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:33.648   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:33.648  3883  3893 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:59:33.648  1346  1369 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:59:33.649  3883  3894 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 12:59:33.650  1346  1365 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:59:33.650  3883  3893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:33.650   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:59:33.650  1346  1358 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 12:59:33.651  1346  1369 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:59:33.651   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:59:33.651  4109  4121 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 12:59:33.651  4109  4121 D BluetoothAdapterProperties: Setting state to 16
08-30 12:59:33.651  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 12:59:33.652  4109  4121 D BluetoothAdapterProperties: onBleDisable
08-30 12:59:33.652  4109  4121 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:59:33.653  4109  4122 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 12:59:33.654  4109  4125 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:59:33.655  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:33.655  4109  4132 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 12:59:33.655  4109  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:59:33.656  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:33.657  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:33.658  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 12:59:33.659  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:33.660  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:33.665  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:59:33.669  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:33.671  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:59:33.856  4109  4125 I bt_hci  : shut_down
,08-30 12:59:33.873  4109  4129 D bt_hwcfg: hw_epilog_process
,08-30 12:59:33.873  4109  4129 I bt_vendor: low_power_mode_cb
,08-30 12:59:33.893  4109  4129 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 12:59:33.894  4109  4129 I bt_vendor: epilog_cb
,08-30 12:59:33.894  4109  4129 I bt_hci  : epilog_finished_callback
,08-30 12:59:33.902  4109  4125 I bt_hci_h4: hal_close
,08-30 12:59:33.903  4109  4125 I bt_userial_vendor: device fd = 51 close
,08-30 12:59:34.029  4109  4122 D bt_stack_manager: event_shut_down_stack finished.
,08-30 12:59:34.030  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 12:59:34.041  4109  4121 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 12:59:34.041  4109  4109 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:59:34.042  4109  4109 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:59:34.043  4109  4109 D BtGatt.GattService: stop()
08-30 12:59:34.043  4109  4109 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 12:59:34.048  4109  4109 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:34.048  4109  4109 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:34.048  4109  4109 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:34.049  4109  4109 V BluetoothAdapterState: isBleTurningOff()=true
08-30 12:59:34.049  4109  4121 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 12:59:34.051  4109  4121 D BluetoothAdapterProperties: Setting state to 10
08-30 12:59:34.051  4109  4121 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 12:59:34.054  4109  4121 I BluetoothAdapterState: Entering OffState
,08-30 12:59:34.055   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 12:59:34.068  4109  4109 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 12:59:34.068  4109  4109 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 12:59:34.068  4109  4122 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 12:59:34.071  4109  4122 D bt_stack_manager: event_clean_up_stack finished.
,08-30 12:59:34.072  4109  4109 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 12:59:34.074  4109  4109 I art     : System.exit called, status: 0
,08-30 12:59:34.074  4109  4109 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:59:34.152   873  1969 I ActivityManager: Process com.android.bluetooth (pid 4109) has died
,08-30 12:59:38.571  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:59:38.571  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:38.577  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:38.577  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c58a6a1 removed from the list
,08-30 12:59:38.577  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:59:38.578  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:59:38.578  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:38.582  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-30 12:59:38.582  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c574887 added. We now have 4 listener(s)
08-30 12:59:38.583  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:59:38.585  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:38.586  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c574887 removed from the list
08-30 12:59:38.586  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:59:38.587  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:38.587  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:38.591  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:59:38.591  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ad33b4 added. We now have 4 listener(s)
08-30 12:59:38.591  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:59:43.602  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:43.653   873   890 I ActivityManager: Start proc 4169:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 12:59:43.811  4169  4169 D AdapterServiceConfig: Adding HeadsetService
,08-30 12:59:43.811  4169  4169 D AdapterServiceConfig: Adding A2dpService
08-30 12:59:43.812  4169  4169 D AdapterServiceConfig: Adding HidService
08-30 12:59:43.812  4169  4169 D AdapterServiceConfig: Adding HealthService
08-30 12:59:43.813  4169  4169 D AdapterServiceConfig: Adding PanService
08-30 12:59:43.813  4169  4169 D AdapterServiceConfig: Adding GattService
08-30 12:59:43.815  4169  4169 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 12:59:43.839   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce34358:true
,08-30 12:59:43.840  4169  4169 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 12:59:43.847  4169  4169 I bt_bluedroid: init
,08-30 12:59:43.847  4169  4181 I BluetoothAdapterState: Entering OffState
,08-30 12:59:43.854  4169  4182 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 12:59:43.854  4169  4182 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:59:43.855  4169  4182 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:59:43.855  4169  4182 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 12:59:43.857  4169  4169 I bt_bluedroid: get_profile_interface socket
,08-30 12:59:43.861  4169  4169 I bt_bluedroid: get_profile_interface sdp
,08-30 12:59:43.863  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:59:43.866  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:59:43.871  4169  4180 I bt_bluedroid: config_hci_snoop_log
,08-30 12:59:43.874   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 12:59:43.888  4169  4181 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 12:59:43.888  4169  4181 D BluetoothAdapterProperties: Setting state to 14
,08-30 12:59:43.888  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 12:59:43.895  4169  4181 D BluetoothBondStateMachine: make
,08-30 12:59:43.901  4169  4186 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 12:59:43.913  4169  4169 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 12:59:43.913  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:59:43.921  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:43.923  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:59:43.925  4169  4169 D BtGatt.GattService: Received start request. Starting profile...
,08-30 12:59:43.927  4169  4169 D BtGatt.GattService: start()
,08-30 12:59:43.928  4169  4169 I bt_bluedroid: get_profile_interface gatt
08-30 12:59:43.929  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
08-30 12:59:43.929  4169  4169 D BtGatt.AdvertiseManager: advertise manager created
,08-30 12:59:43.939  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:43.939  4169  4169 V BluetoothAdapterState: isTurningOn()=false
08-30 12:59:43.939  4169  4169 V BluetoothAdapterState: isBleTurningOn()=true
08-30 12:59:43.939  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:43.940  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 12:59:43.940  4169  4181 I bt_bluedroid: enable
08-30 12:59:43.940  4169  4182 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 12:59:43.941  4169  4182 I bt_hci  : start_up
,08-30 12:59:43.961  4169  4182 I bt_vendor: alloc value 0xb39ed189
,08-30 12:59:43.962  4169  4182 I bt_vendor: init
08-30 12:59:43.962  4169  4182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 12:59:43.962  4169  4182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 12:59:44.071  4169  4182 D bt_hci  : start_up starting async portion
,08-30 12:59:44.072  4169  4189 I bt_hci  : event_finish_startup
08-30 12:59:44.073  4169  4189 I bt_hci_h4: hal_open
,08-30 12:59:44.073  4169  4189 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 12:59:44.085  4169  4189 I bt_userial_vendor: device fd = 51 open
,08-30 12:59:44.115  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:59:44.146  4169  4189 D bt_hwcfg: Chipset BCM4354A2
,08-30 12:59:44.146  4169  4189 D bt_hwcfg: Target name = [BCM4354A2]
08-30 12:59:44.147  4169  4189 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 12:59:45.025  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 12:59:45.026  4169  4189 D bt_hwcfg: Settlement delay -- 100 ms
08-30 12:59:45.027  4169  4189 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 12:59:45.143  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:59:45.144  4169  4189 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 12:59:45.175  4169  4189 I bt_hwcfg: vendor lib fwcfg completed
,08-30 12:59:45.175  4169  4189 I bt_vendor: firmware callback
08-30 12:59:45.175  4169  4189 I bt_hci  : firmware_config_callback
,08-30 12:59:45.186  4169  4191 I bt_btu  : btu_task pending for preload complete event
,08-30 12:59:45.186  4169  4191 I bt_btu_task: Bluetooth chip preload is complete
08-30 12:59:45.187  4169  4191 I bt_btu  : btu_task received preload complete event
,08-30 12:59:45.196  4169  4191 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 12:59:45.197  4169  4191 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 12:59:45.197  4169  4191 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:59:45.197  4169  4191 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:59:45.197  4169  4191 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:59:45.198  4169  4191 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 12:59:45.198  4169  4191 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:59:45.198  4169  4191 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 12:59:45.198  4169  4191 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 12:59:45.199  4169  4191 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:59:45.199  4169  4191 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 12:59:45.199  4169  4191 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:59:45.199  4169  4191 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 12:59:45.200  4169  4191 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:59:45.200  4169  4191 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:59:45.336  4169  4191 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ad9d
,08-30 12:59:45.336  4169  4191 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ad9d 
,08-30 12:59:45.347  4169  4185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 12:59:45.348  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 12:59:45.349  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:59:45.351  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:59:45.354  4169  4185 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:59:45.355  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:59:45.355  4169  4185 D bt_hci  : do_postload posting postload work item
,08-30 12:59:45.356  4169  4189 I bt_hci  : event_postload
,08-30 12:59:45.357  4169  4189 I bt_vendor: sco_config_cb
,08-30 12:59:45.357  4169  4189 I bt_hci  : sco_config_callback postload finished.
08-30 12:59:45.359  4169  4185 D bt_bte_conf: Device ID record 1 : primary
,08-30 12:59:45.360  4169  4185 D bt_bte_conf:   vendorId            = 000f
,08-30 12:59:45.360  4169  4185 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 12:59:45.360  4169  4185 D bt_bte_conf:   product             = 1200
,08-30 12:59:45.360  4169  4185 D bt_bte_conf:   version             = 1436
,08-30 12:59:45.361  4169  4185 D bt_bte_conf:   clientExecutableURL = 
08-30 12:59:45.361  4169  4185 D bt_bte_conf:   serviceDescription  = 
08-30 12:59:45.361  4169  4185 D bt_bte_conf:   documentationURL    = 
,08-30 12:59:45.362  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:45.362  4169  4185 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 12:59:45.363  4169  4182 D bt_stack_manager: event_start_up_stack finished
08-30 12:59:45.364  4169  4189 I bt_vendor: low_power_mode_cb
08-30 12:59:45.365  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 12:59:45.365  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:59:45.365  4169  4181 D BluetoothAdapterProperties: Setting state to 15
08-30 12:59:45.366  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 12:59:45.369  4169  4181 I BluetoothAdapterState: Entering BleOnState
,08-30 12:59:45.375  4169  4181 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 12:59:45.375  4169  4181 D BluetoothAdapterProperties: Setting state to 11
08-30 12:59:45.375  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 12:59:45.384  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:45.385  4169  4169 D HeadsetService: Received start request. Starting profile...
,08-30 12:59:45.389  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:45.392  4169  4169 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 12:59:45.393  4169  4169 D HeadsetStateMachine: make
08-30 12:59:45.394  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:45.404  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:59:45.406  4169  4169 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:59:45.406  4169  4169 I bt_bluedroid: get_profile_interface handsfree
,08-30 12:59:45.406  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 12:59:45.407  4169  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 12:59:45.410  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:45.411  4169  4169 D A2dpService: Received start request. Starting profile...
08-30 12:59:45.412  4169  4169 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:59:45.412  4169  4169 I bt_bluedroid: get_profile_interface avrcp
,08-30 12:59:45.418  4169  4169 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 12:59:45.418  4169  4169 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:59:45.418  4169  4169 D A2dpStateMachine: make
,08-30 12:59:45.419  4169  4169 I bt_bluedroid: get_profile_interface a2dp
,08-30 12:59:45.420  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-30 12:59:45.421  4169  4200 D A2dpStateMachine: Enter Disconnected: -2
,08-30 12:59:45.422  4169  4169 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 12:59:45.424  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:45.424  4169  4169 D HidService: Received start request. Starting profile...
,08-30 12:59:45.424  4169  4169 I bt_bluedroid: get_profile_interface hidhost
08-30 12:59:45.424  4169  4169 D HidService: setHidService(): set to: null
,08-30 12:59:45.424  4169  4185 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394c3e5
08-30 12:59:45.425  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 12:59:45.426  4169  4169 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 12:59:45.427  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:45.427  4169  4169 D HealthService: Received start request. Starting profile...
08-30 12:59:45.427  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:45.429  4169  4169 I bt_bluedroid: get_profile_interface health
,08-30 12:59:45.430  4169  4169 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 12:59:45.430  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:45.431  4169  4169 D PanService: Received start request. Starting profile...
08-30 12:59:45.431  4169  4169 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 12:59:45.431  4169  4169 I bt_bluedroid: get_profile_interface pan
08-30 12:59:45.432  4169  4185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 12:59:45.435  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 12:59:45.436  4169  4169 D BluetoothMapService: Received start request. Starting profile...
,08-30 12:59:45.436  4169  4169 D BluetoothMapService: start()
08-30 12:59:45.439  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 12:59:45.439  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 12:59:45.439  4169  4169 D BluetoothMapAppObserver: createReceiver()
,08-30 12:59:45.440  4169  4169 D BluetoothMapAppObserver: initObservers()
08-30 12:59:45.440  4169  4169 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 12:59:45.446  4169  4198 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 12:59:45.446  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:45.446  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:45.446  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:45.446  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:59:45.447  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:45.447  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:45.447  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:45.448  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:59:45.449  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:59:45.450  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 12:59:45.450  4169  4181 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:59:45.450  4169  4181 D BluetoothAdapterProperties: State =  11
,08-30 12:59:45.450  4169  4181 D BluetoothAdapterProperties: Setting state to 12
08-30 12:59:45.450  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 12:59:45.451  4169  4181 I BluetoothAdapterState: Entering OnState
08-30 12:59:45.451  3883  4164 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:59:45.452  4169  4185 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:59:45.452  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:59:45.454  3883  3894 D BluetoothInputDevice: onBluetoothStateChange: up=true,
,08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:45.454  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:45.455  1346  1369 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 12:59:45.456  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:45.457  1346  1346 D BluetoothA2dp: Proxy object connected
,08-30 12:59:45.457  3883  4164 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 12:59:45.459  1934  1952 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:45.459  3883  3883 D BluetoothA2dp: Proxy object connected
,08-30 12:59:45.460  1346  1365 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:45.461  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:59:45.462   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:45.462   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:45.462  3883  3894 D BluetoothPan: onBluetoothStateChange on: true,
08-30 12:59:45.463  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:45.463  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:59:45.463  1346  1346 D PanProfile: Bluetooth service connected
,08-30 12:59:45.464  1346  1369 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:59:45.466  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:59:45.466  4169  4169 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 12:59:45.466  3883  4164 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 12:59:45.467  1346  1346 D BluetoothInputDevice: Proxy object connected
,08-30 12:59:45.467  1346  1346 D HidProfile: Bluetooth service connected
08-30 12:59:45.467  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:59:45.468  1346  1369 D BluetoothPbap: onBluetoothStateChange: up=true,
08-30 12:59:45.469  3883  3883 D BluetoothInputDevice: Proxy object connected
,08-30 12:59:45.469  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:59:45.469  3883  3883 D HidProfile: Bluetooth service connected
,08-30 12:59:45.470  3883  3893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:45.470  4169  4169 D ObexServerSockets: Succeed to create listening sockets 
08-30 12:59:45.470  4169  4169 D ObexServerSockets0: startAccept()
,08-30 12:59:45.470  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:59:45.470   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:59:45.471  1346  1358 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:59:45.471   873   873 D BluetoothA2dp: Proxy object connected
,08-30 12:59:45.472  4169  4169 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 12:59:45.472  4169  4169 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 12:59:45.473  1346  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:45.473  4169  4208 D ObexServerSockets0: Accepting socket connection...
,08-30 12:59:45.473   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:59:45.473  4169  4207 D ObexServerSockets0: Accepting socket connection...
08-30 12:59:45.473  1346  1346 D BluetoothMap: Proxy object connected
08-30 12:59:45.474  1346  1346 D MapProfile: Bluetooth service connected
08-30 12:59:45.474  1346  1346 D BluetoothMap: getConnectedDevices()
,08-30 12:59:45.475   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 12:59:45.476  4169  4169 D BluetoothMapService: onReceive
,08-30 12:59:45.476  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:59:45.476  4169  4169 D BluetoothMapService: STATE_ON
08-30 12:59:45.477  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:45.478  3883  3883 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:59:45.478  3883  3883 D PanProfile: Bluetooth service connected
08-30 12:59:45.478  3883  3883 D BluetoothMap: Proxy object connected
,08-30 12:59:45.478  3883  3883 D MapProfile: Bluetooth service connected
08-30 12:59:45.478  3883  3883 D BluetoothMap: getConnectedDevices()
08-30 12:59:45.478  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:45.483  3883  3883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:59:45.487  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:59:45.490  3883  3883 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:59:45.494  3883  3883 D BluetoothPbap: Proxy object connected
,08-30 12:59:45.494  3883  3883 D PbapServerProfile: Bluetooth service connected
,08-30 12:59:45.499  4169  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:59:45.500  1346  1346 D BluetoothPbap: Proxy object connected
08-30 12:59:45.500  1346  1346 D PbapServerProfile: Bluetooth service connected
,08-30 12:59:45.511  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 12:59:45.511  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:59:45.514  4169  4216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:59:45.515  4169  4216 I BtOppRfcommListener: Accept thread started.
,08-30 12:59:45.561  1934  1949 D BluetoothHeadset: Proxy object connected
,08-30 12:59:45.561  1346  1358 D BluetoothHeadset: Proxy object connected
,08-30 12:59:45.561  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-30 12:59:45.561   873   873 D BluetoothHeadset: Proxy object connected
08-30 12:59:45.561   873   873 D BluetoothHeadset: Proxy object connected
08-30 12:59:45.561   873   873 D BluetoothHeadset: Proxy object connected,
08-30 12:59:45.562  3883  3893 D BluetoothHeadset: Proxy object connected
,08-30 12:59:45.562  3883  3883 D HeadsetProfile: Bluetooth service connected
08-30 12:59:45.563   873   890 D BluetoothHeadset: Proxy object connected
08-30 12:59:45.563   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:59:45.570  3883  3894 D BluetoothHeadset: Proxy object connected
,08-30 12:59:45.570  3883  3883 D HeadsetProfile: Bluetooth service connected
,08-30 12:59:45.573  1346  1365 D BluetoothHeadset: Proxy object connected
,08-30 12:59:45.573  1346  1346 D HeadsetProfile: Bluetooth service connected
08-30 12:59:45.573   873   890 D BluetoothHeadset: Proxy object connected
,08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:48.623  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:48.629  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:48.630  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:59:48.631  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ad33b4 removed from the list
,08-30 12:59:48.631  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:59:48.631  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:48.632  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:59:48.634  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:59:48.635  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b80bdd added. We now have 4 listener(s)
08-30 12:59:48.636  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:59:48.640   873  1968 D WifiService: setWifiEnabled: false pid=3792, uid=10000
08-30 12:59:48.641   873  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:59:53.654  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:59:53.655   873  1986 D WifiService: setWifiEnabled: true pid=3792, uid=10000
08-30 12:59:53.655   873  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:59:53.668   873  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:53.687  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:53.693  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:59:53.697  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:59:53.700   873  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-30 12:59:53.700  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:59:53.700   873  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 12:59:53.701   873  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 12:59:53.702   873  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 12:59:53.702   873  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 12:59:53.702   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 12:59:53.702   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 12:59:53.713   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 12:59:53.713   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:59:53.714   372   871 D CommandListener: Setting iface cfg
08-30 12:59:53.714   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
08-30 12:59:53.715   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 12:59:53.768   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:59:53.769   873  1301 E native  : do suspend true
,08-30 12:59:53.769   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 12:59:53.815   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:59:54.152  1863  1991 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-30 12:59:54.152  1863  1991 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 12:59:54.203  1512  1512 I ConfigService: onCreate
,08-30 12:59:55.203   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:59:55.346   873  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.38 rxSuccessRate=5.94 delta 1000 -> 994
,08-30 12:59:55.348   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 12:59:55.348   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:59:55.370   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 12:59:55.449   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 12:59:55.455  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 12:59:55.898  1449  1449 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:59:55.966  1449  1449 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 12:59:55.968  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 12:59:55.975   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:59:55.991   873  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:59:55.991   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:59:55.992   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 12:59:56.008   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:59:56.020   372   871 D CommandListener: Setting iface cfg
,08-30 12:59:56.020   873  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 12:59:56.028   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 12:59:56.065   873  4227 D DhcpClient: Receive thread started
,08-30 12:59:56.164   873  1301 E native  : do suspend false
,08-30 12:59:56.190   873  1862 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 12:59:56.208   873  4227 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-30 12:59:56.210   873  1862 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-30 12:59:56.213   873  1862 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 12:59:56.229   873  4227 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 12:59:56.231   873  1862 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 12:59:56.236   372   871 D CommandListener: Setting iface cfg
,08-30 12:59:56.246   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 12:59:56.248   873  1862 D DhcpClient: Scheduling renewal in 86399s
,08-30 12:59:56.249   873  1301 E native  : do suspend true
,08-30 12:59:56.276   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 12:59:56.280   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:59:56.282   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 12:59:56.285   873  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 12:59:56.288   873  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 12:59:56.346   873  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 12:59:56.346   873  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 12:59:56.348   873  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 12:59:56.349   873  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 12:59:56.350   873  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 12:59:56.361   873  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 12:59:56.366   873  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 12:59:56.366   873  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 12:59:56.367   873  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 12:59:56.367   873  1303 D ConnectivityService:    accepting network in place of null
08-30 12:59:56.367   873  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 12:59:56.368   873  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 12:59:56.368   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 12:59:56.397   873  4226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212107, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 12:59:56.428   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:56.465   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:59:56.470   873  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 12:59:56.471   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:59:56.471   873  4225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 12:59:56.472   873  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 12:59:56.475   873   890 D Tethering: MasterInitialState.processMessage what=3
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:56.487  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:59:56.492  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:56.500  3792  3792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:59:56.503  3792  3792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:56.507  1723  1723 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:59:56.517  1723  1723 D SystemUpdateService: onCreate
,08-30 12:59:56.519  3745  4236 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 12:59:56.527  1723  1723 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:59:56.549   873  4225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:59:56 GMT], X-Android-Received-Millis=[1472554796549], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472554796525]}
,08-30 12:59:56.550   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 12:59:56.550   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 12:59:56.550   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 12:59:56.551   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 12:59:56.548  1723  4237 I SystemUpdateService: active receiver: enabled
,08-30 12:59:56.561  1723  1723 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 12:59:56.564  1723  2414 I iu.UploadsManager: num queued entries: 0
,08-30 12:59:56.564  1723  2414 I iu.UploadsManager: num updated entries: 0
,08-30 12:59:56.570  1723  2414 I iu.SyncManager: NEXT; no task
,08-30 12:59:56.573  1723  1723 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:59:56.574  1723  1723 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:59:56.578  3937  3937 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:59:56.579  1723  4240 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 12:59:56.579  1723  4240 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 12:59:56.581  1723  4240 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:59:56.585  3937  3937 D SprintDMHelper: simOperator: 
,08-30 12:59:56.586  3937  3937 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:59:56.590  1723  4237 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:59:56.600  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:56.606  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:59:56.621  3745  4243 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 12:59:56.619  1723  4237 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 12:59:56.624  1723  4237 I SystemUpdateService: now status is 0 (complete)
,08-30 12:59:56.625  1723  4237 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:59:56.625  1723  4237 I SystemUpdateService: file has been verified
,08-30 12:59:56.625  1723  4237 I SystemUpdateService: OTA package size = 12249756
,08-30 12:59:56.679  1512  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:59:56.680  1512  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 12:59:56.680  1512  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:56.680  1512  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:56.707  1723  4237 I SystemUpdateService: showing system update notification
,08-30 12:59:56.713  1512  3043 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 12:59:56.713  1512  3043 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:59:56.713  1512  3043 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:56.713  1512  3043 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:56.724  3745  4243 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 12:59:56.724  3745  4236 E BooksSync: Soft error
08-30 12:59:56.724  3745  4236 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:59:56.724  3745  4236 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:59:56.724  3745  4236 E BooksSync: Sync error
08-30 12:59:56.724  3745  4236 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:59:56.724  3745  4236 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:59:56.724  3745  4236 I BooksSync: Finished books sync
,08-30 12:59:56.737   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 209496, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:59:56.751  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 12:59:56.751  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 12:59:56.751  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:59:56.751  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:59:56.752  1723  1723 D SystemUpdateService: onDestroy
,08-30 12:59:56.781  1723  4240 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-30 12:59:56.844  2453  4244 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 12:59:57.472   873  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:59:58.681  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:59:58.689  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:59:58.690  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:59:58.690  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b80bdd removed from the list
08-30 12:59:58.690  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:59:58.691  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:59:58.691  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:59:58.706  3792  4250 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-30 12:59:58.707  3792  4250 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 12:59:59.292  1512  1512 I ConfigService: onDestroy
,08-30 13:00:01.714  3792  4252 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-30 13:00:01.715  3792  4250 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 13:00:01.716  3792  4250 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 13:00:01.716  3792  4252 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 13:00:01.718  3792  4252 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 13:00:01.718  3792  4250 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:00:01.719  3792  4252 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:00:01.719  3792  4250 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:00:01.721  3792  4252 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 13:00:01.721  3792  4250 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 13:00:01.727  3792  4254 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Sender)
08-30 13:00:01.730  3792  4255 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
,08-30 13:00:01.733  3792  4257 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
08-30 13:00:01.734  3792  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: IncomingSocketThread/Receiver)
,08-30 13:00:01.736  3792  4257 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver)
,08-30 13:00:01.737  3792  4256 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: IncomingSocketThread/Receiver)
08-30 13:00:01.737  3792  4257 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 13:00:01.737  3792  4256 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-30 13:00:01.737  3792  4257 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 13:00:01.737  3792  4256 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 13:00:04.374   873  1303 D ConnectivityService: handlePromptUnvalidated 102
,08-30 13:00:04.714  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 13:00:04.715  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 13:00:04.724  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@eca0b02 Bundle[{}]
,08-30 13:00:04.725  3792  3842 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 13:00:04.725  3792  3842 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 13:00:04.726  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 13:00:04.726  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 13:00:04.727  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 13:00:04.727  3792  3842 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 13:00:04.731  3792  3842 I System.out: Running OutgoingSocketThread
,08-30 13:00:04.733  3792  4258 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 13:00:04.733  3792  4258 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 13:00:07.744  3792  4259 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 13:00:07.744  3792  4259 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 13:00:07.744  3792  4259 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 13:00:07.745  3792  4258 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 13:00:07.745  3792  4258 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 13:00:07.747  3792  4259 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 13:00:07.746  3792  4258 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:00:07.749  3792  4261 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Sender)
,08-30 13:00:07.751  3792  4259 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 13:00:07.755  3792  4258 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:00:07.756  3792  4262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
08-30 13:00:07.758  3792  4262 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
,08-30 13:00:07.758  3792  4262 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 13:00:07.758  3792  4262 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 13:00:07.759  3792  4263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Sender)
,08-30 13:00:07.760  3792  4258 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 13:00:07.765  3792  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Receiver)
08-30 13:00:07.767  3792  4264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: OutgoingSocketThread/Receiver)
,08-30 13:00:07.767  3792  4264 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 13:00:07.767  3792  4264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 13:00:10.747  3792  3842 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,08-30 13:00:10.750  3792  3842 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 13:00:10.750  3792  3842 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-30 13:00:10.757  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 13:00:10.757  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e89352 added. We now have 3 listener(s)
,08-30 13:00:10.758  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 13:00:10.759  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:00:10.759  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:00:10.759  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:00:10.759  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a55e623 added. We now have 4 listener(s)
08-30 13:00:10.759  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:00:10.761  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:00:10.766  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:00:10.775  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:00:10.777  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:00:10.777  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:00:10.778  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:00:10.778  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:00:10.778  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:00:10.778  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:10.778  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:10.778  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:10.779  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 13:00:10.779  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e89352 removed from the list
08-30 13:00:10.779  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:10.779  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a55e623 removed from the list
08-30 13:00:10.783  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:00:10.790  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:00:10.790  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:00:10.790  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:10.791  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:10.792  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:00:10.794  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:00:10.794  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:10.794  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:10.794  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a55e623 not in the list
08-30 13:00:10.795  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:10.795  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:00:10.796  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:10.796  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:00:10.796  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:10.797  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a55e623 not in the list
08-30 13:00:10.797  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:10.797  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:10.797  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:10.797  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e89352 not in the list
08-30 13:00:10.798  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:00:10.798  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae88d9 added. We now have 3 listener(s)
08-30 13:00:10.800  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:00:10.801  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:00:10.801  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:00:10.801  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:00:10.801  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d8929e added. We now have 4 listener(s)
,08-30 13:00:10.801  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:00:10.802  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 13:00:10.805  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:00:10.815  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:00:10.818  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-30 13:00:10.818  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:00:10.819  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:00:10.819  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 13:00:10.819  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 13:00:10.819  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:00:10.819  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:00:10.825  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:00:10.827  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 13:00:10.827  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:00:10.835  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:00:10.834  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:00:10.835  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 13:00:10.835  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:00:10.844  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 13:00:10.845  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 13:00:10.845  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 13:00:10.847  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 13:00:10.853  4169  4180 D BtGatt.GattService: registerClient() - UUID=725b39ad-68fd-4b74-bd1d-1adb54c7cdb2
,08-30 13:00:10.855  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=725b39ad-68fd-4b74-bd1d-1adb54c7cdb2, clientIf=5
,08-30 13:00:10.856  3792  3804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 13:00:10.857  4169  4206 D BtGatt.GattService: start scan with filters
,08-30 13:00:10.865  4169  4188 D BtGatt.ScanManager: handling starting scan
,08-30 13:00:10.865  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 13:00:10.866  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 13:00:10.866  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 13:00:10.867  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 13:00:10.868  4169  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aca8d76
,08-30 13:00:10.872  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-30 13:00:10.873  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 13:00:10.873  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:00:10.877  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:00:10.885  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 13:00:10.885  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:10.886  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:00:10.889  3792  3842 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 13:00:10.889  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:00:10.890  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:00:10.890  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:10.890  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 13:00:10.890  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 13:00:10.891  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 13:00:10.891  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 13:00:10.891  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:00:10.892  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 13:00:10.892  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 13:00:10.894  3792  3842 D BluetoothAdapter: STATE_ON
08-30 13:00:10.896  4169  4205 D BtGatt.GattService: stopScan() - queue size =1
,08-30 13:00:10.898  4169  4197 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:00:10.900  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 13:00:10.900  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 13:00:10.900  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 13:00:10.900  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:00:10.901  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 13:00:10.904  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 13:00:10.904  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:10.905  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
08-30 13:00:10.905  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 13:00:10.907  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:00:10.907  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 13:00:10.907  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 13:00:10.908  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 13:00:10.909  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:10.912  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:00:10.912  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:00:10.913  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:00:10.931  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 13:00:10.932  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:10.943  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 13:00:10.943  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:10.958  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 13:00:10.958  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:10.959  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
,08-30 13:00:10.974  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 13:00:10.974  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:10.975  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:00:10.989  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 13:00:10.989  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:11.415  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:00:11.415  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:00:11.415  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:00:13.914  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:00:13.915  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:00:13.915  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:00:13.916  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:00:13.917  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:13.917  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:13.917  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 13:00:13.918  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae88d9 removed from the list
08-30 13:00:13.918  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:13.918  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d8929e removed from the list
,08-30 13:00:13.919  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:00:13.919  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:13.920  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:00:13.921  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:13.924  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:00:13.924  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:00:13.925  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:13.925  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d8929e not in the list
08-30 13:00:13.925  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:13.926  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:00:13.929  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:13.929  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:00:13.930  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:13.930  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d8929e not in the list
08-30 13:00:13.930  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:13.930  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:13.931  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:13.931  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae88d9 not in the list
08-30 13:00:13.933  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:00:13.934  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edff69b added. We now have 3 listener(s)
,08-30 13:00:13.939  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 13:00:13.940  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:00:13.940  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:00:13.941  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:00:13.941  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9616a38 added. We now have 4 listener(s)
,08-30 13:00:13.941  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:00:13.942  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:00:13.948  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:00:13.956  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:00:13.959  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:00:13.960  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:00:13.960  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 13:00:13.961  3792  3842 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 13:00:13.961  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 13:00:13.964  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 13:00:13.964  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 13:00:13.964  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 13:00:13.964  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:00:13.966  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:00:13.967  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 13:00:13.967  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 13:00:13.968  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 13:00:13.969  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 13:00:13.969  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 13:00:13.969  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:00:13.969  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:00:13.973  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:00:13.973  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 13:00:13.975  3792  4265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:00:13.979  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 13:00:13.979  3792  4265 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 13:00:13.979  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:00:13.988  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:00:13.989  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 13:00:13.989  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:00:13.992  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 13:00:13.992  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 13:00:13.993  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-30 13:00:13.994  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 13:00:13.995  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 13:00:13.995  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 13:00:13.996  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 13:00:14.000  4169  4180 D BtGatt.GattService: registerClient() - UUID=34ad3b0e-ab72-4c74-a3d7-40273591ef0c
,08-30 13:00:14.001  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=34ad3b0e-ab72-4c74-a3d7-40273591ef0c, clientIf=5
08-30 13:00:14.001  3792  3803 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 13:00:14.007  4169  4187 D BtGatt.AdvertiseManager: message : 0
,08-30 13:00:14.012  4169  4187 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 13:00:14.038  4169  4185 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 13:00:14.055  4169  4185 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 13:00:14.057  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 13:00:14.057  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 13:00:14.061  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:00:14.064  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 13:00:14.065  3792  3792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 13:00:14.065  3792  3792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 13:00:14.066  3792  3792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 13:00:14.066  3792  3792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 13:00:14.066  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 13:00:14.068  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 13:00:14.075  3792  3792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 13:00:14.075  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 13:00:14.577  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 13:00:14.577  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 13:00:14.578  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:00:17.070  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:00:17.070  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-30 13:00:17.071  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:00:17.071  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 13:00:17.071  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 13:00:17.072  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 13:00:17.073  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 13:00:17.073  3792  4265 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 13:00:17.073  3792  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 13:00:17.073  3792  4265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 13:00:17.073  3792  4265 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 13:00:17.074  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 13:00:17.074  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 13:00:17.074  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 13:00:17.074  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:00:17.075  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 13:00:17.076  3792  3792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 13:00:17.077  3792  3842 D BluetoothAdapter: STATE_ON
08-30 13:00:17.078  3792  3842 D BluetoothLeScanner: could not find callback wrapper
08-30 13:00:17.078  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 13:00:17.078  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 13:00:17.080  4169  4187 D BtGatt.AdvertiseManager: message : 1
08-30 13:00:17.082  4169  4187 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 13:00:17.093  4169  4185 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 13:00:17.093  4169  4185 D BtGatt.GattService: Client app is not null!
,08-30 13:00:17.094  4169  4179 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:00:17.095  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 13:00:17.095  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 13:00:17.095  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 13:00:17.096  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 13:00:17.096  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 13:00:17.098  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:00:17.098  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 13:00:17.098  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 13:00:17.099  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:17.100  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:17.100  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:00:17.100  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:00:17.100  3792  3792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 13:00:17.103  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 13:00:17.103  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edff69b removed from the list
,08-30 13:00:17.103  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:17.103  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:00:17.103  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9616a38 removed from the list
08-30 13:00:17.104  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:00:17.104  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:00:17.104  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:17.104  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:00:17.104  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:00:17.104  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:17.106  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:00:17.106  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:17.107  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:17.107  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9616a38 not in the list
,08-30 13:00:17.107  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:17.107  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:00:17.110  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:00:17.110  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:00:17.110  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:17.110  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9616a38 not in the list
08-30 13:00:17.110  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:00:17.110  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:17.110  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:00:17.110  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edff69b not in the list
,08-30 13:00:17.111  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:00:17.111  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f8a64d added. We now have 3 listener(s)
,08-30 13:00:17.113  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:00:17.113  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 13:00:17.114  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:00:17.114  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 13:00:17.114  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d187502 added. We now have 4 listener(s)
,08-30 13:00:17.114  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:00:17.115  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:00:17.119  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:00:17.127  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:00:17.132  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:00:17.133  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:00:17.133  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 13:00:17.133  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 13:00:17.134  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 13:00:17.134  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:00:17.136  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:00:17.137  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:00:17.141  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:00:17.143  3792  3842 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 13:00:17.143  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:00:17.151  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:00:17.153  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 13:00:17.153  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 13:00:17.158  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 13:00:17.158  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 13:00:17.159  3792  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 13:00:17.160  3792  3842 D BluetoothAdapter: STATE_ON,
,08-30 13:00:17.163  4169  4179 D BtGatt.GattService: registerClient() - UUID=01239beb-c66e-40fd-a910-d7fa1171bdad
,08-30 13:00:17.163  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=01239beb-c66e-40fd-a910-d7fa1171bdad, clientIf=5
,08-30 13:00:17.164  3792  3804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 13:00:17.164  4169  4205 D BtGatt.GattService: start scan with filters,
,08-30 13:00:17.168  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 13:00:17.168  4169  4188 D BtGatt.ScanManager: handling starting scan
,08-30 13:00:17.168  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 13:00:17.169  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 13:00:17.169  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 13:00:17.174  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:00:17.175  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 13:00:17.175  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 13:00:17.179  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:00:17.183  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 13:00:17.183  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:17.183  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:00:17.197  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 13:00:17.197  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:17.198  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
08-30 13:00:17.198  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 13:00:17.228  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 13:00:17.228  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:17.244  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 13:00:17.245  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:00:17.606  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:00:17.675  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 13:00:17.676  3792  3792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:00:17.676  3792  3792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:00:18.751  4169  4169 D BtGatt.ScanManager: awakened up at time 234461
,08-30 13:00:18.755  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:00:18.819  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-30 13:00:18.819  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:18.820  4169  4185 D BtGatt.GattService: current time is 234530613305
,08-30 13:00:18.821  4169  4185 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -96, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 53, 33, -121, 80, 73, -44, 1, 0, -106, 24, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 105, -62, -18, 2, 2, -29, 21, 63, -108, 113, 42, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -87, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 13:00:18.825  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 13:00:18.827  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 13:00:18.828  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 13:00:18.829  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 105, -62, -18, 2, 2, -29, 21, 63, -108, 113, 42, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-30 13:00:18.830  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 13:00:18.830  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 13:00:18.831  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 13:00:20.194  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:00:20.194  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 13:00:20.194  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:00:20.195  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.195  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 13:00:20.195  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 13:00:20.196  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 13:00:20.196  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 13:00:20.196  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 13:00:20.197  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 13:00:20.197  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-30 13:00:20.199  3792  3842 D BluetoothAdapter: STATE_ON
,08-30 13:00:20.201  4169  4179 D BtGatt.GattService: stopScan() - queue size =1
,08-30 13:00:20.204  4169  4205 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:00:20.205  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 13:00:20.205  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 13:00:20.206  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 13:00:20.206  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:00:20.207  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 13:00:20.214  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:00:20.215  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 13:00:20.215  4169  4169 D BtGatt.ScanManager: awakened up at time 235925
08-30 13:00:20.215  3792  3842 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 13:00:20.216  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 13:00:20.222  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:20.224  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:20.224  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.224  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:00:20.224  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:20.224  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 13:00:20.225  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f8a64d removed from the list
08-30 13:00:20.225  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:00:20.225  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:20.225  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d187502 removed from the list
08-30 13:00:20.225  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:00:20.225  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.225  3792  3792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:00:20.226  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.226  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.228  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:00:20.228  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:20.228  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:20.228  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d187502 not in the list
,08-30 13:00:20.229  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.229  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.229  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 13:00:20.229  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:20.230  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:20.230  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:00:20.230  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:00:20.230  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d187502 not in the list
08-30 13:00:20.230  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:20.230  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.230  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.231  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f8a64d not in the list
08-30 13:00:20.231  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
08-30 13:00:20.231  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:00:20.231  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a9086f added. We now have 3 listener(s)
,08-30 13:00:20.233  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:00:20.233  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:00:20.233  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:00:20.234  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 13:00:20.234  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264997c added. We now have 4 listener(s)
08-30 13:00:20.234  3792  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:00:20.235  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:00:20.238  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:00:20.243  3792  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:00:20.245  3792  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:00:20.246  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 13:00:20.246  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:20.246  3792  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:00:20.246  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 13:00:20.246  3792  3842 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:00:20.247  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:00:20.247  3792  3842 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:00:20.247  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:00:20.247  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.247  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:00:20.247  3792  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 13:00:20.247  3792  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a9086f removed from the list
08-30 13:00:20.247  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:00:20.247  3792  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264997c removed from the list,
08-30 13:00:20.249  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:00:20.249  3792  3842 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:00:20.249  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:00:20.250  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.250  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.251  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:00:20.251  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:20.251  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:00:20.252  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264997c not in the list
,08-30 13:00:20.252  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.252  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:00:20.252  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.253  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:00:20.253  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:00:20.253  3792  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:00:20.253  3792  3842 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264997c not in the list
08-30 13:00:20.253  3792  3842 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:00:20.253  3792  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:00:20.253  3792  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:00:20.254  3792  3842 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a9086f not in the list
08-30 13:00:20.255  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
08-30 13:00:20.255  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 13:00:20.255  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 13:00:20.255  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:00:20.255  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 13:00:20.256  3792  3842 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:00:20.262  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-30 13:00:20.262  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:00:20.262  4169  4185 D BtGatt.GattService: current time is 235972813965
08-30 13:00:20.262  4169  4185 D BtGatt.GattService: Batch record : [11, 20, 30, -111, -57, 121, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 13:00:20.262  4169  4185 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-30 13:00:20.263  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 13:00:20.727  3792  3792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:00:22.273  3792  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,08-30 13:00:24.271  3792  3842 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 458
,08-30 13:00:24.271  3792  3842 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 458, name: My test thread name)
,08-30 13:00:24.278  3792  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,08-30 13:00:24.278  3792  4268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: My test thread name)
,08-30 13:00:24.279  3792  4268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 13:00:24.284  3792  3842 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:00:24.294  3792  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,08-30 13:00:24.295  3792  4269 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 463, thread name: My test thread name): Test exception.
,08-30 13:00:24.295  3792  4269 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 13:00:24.303  3792  3842 I jxcore-log: Total number of executed tests:  82
08-30 13:00:24.303  3792  3842 I jxcore-log: 
,08-30 13:00:24.304  3792  3842 I jxcore-log: Number of passed tests:  82
08-30 13:00:24.304  3792  3842 I jxcore-log: 
08-30 13:00:24.305  3792  3842 I jxcore-log: Number of failed tests:  0
08-30 13:00:24.305  3792  3842 I jxcore-log: 
08-30 13:00:24.305  3792  3842 I jxcore-log: Number of ignored tests:  0
08-30 13:00:24.305  3792  3842 I jxcore-log: 
,08-30 13:00:24.306  3792  3842 I jxcore-log: Total duration:  101314
08-30 13:00:24.306  3792  3842 I jxcore-log: 
,08-30 13:00:24.316  3792  3842 I jxcore-log: Unit Test app is loaded
08-30 13:00:24.316  3792  3842 I jxcore-log: 
,08-30 13:00:24.341  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.341  3792  3842 I jxcore-log: 
,08-30 13:00:24.344  3792  3792 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 13:00:24.346  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.346  3792  3842 I jxcore-log: 
,08-30 13:00:24.347  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.347  3792  3842 I jxcore-log: 
,08-30 13:00:24.348  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.348  3792  3842 I jxcore-log: 
,08-30 13:00:24.350  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 13:00:24.350  3792  3842 I jxcore-log: 
,08-30 13:00:24.351  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:00:24.351  3792  3842 I jxcore-log: 
,08-30 13:00:24.354  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.354  3792  3842 I jxcore-log: 
,08-30 13:00:24.355  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.355  3792  3842 I jxcore-log: 
,08-30 13:00:24.356  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 13:00:24.356  3792  3842 I jxcore-log: 
08-30 13:00:24.357  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:00:24.357  3792  3842 I jxcore-log: 
,08-30 13:00:24.358  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:00:24.358  3792  3842 I jxcore-log: 
,08-30 13:00:24.359  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.359  3792  3842 I jxcore-log: 
08-30 13:00:24.360  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.360  3792  3842 I jxcore-log: 
08-30 13:00:24.361  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.361  3792  3842 I jxcore-log: 
,08-30 13:00:24.362  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.362  3792  3842 I jxcore-log: 
,08-30 13:00:24.363  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.363  3792  3842 I jxcore-log: 
,08-30 13:00:24.364  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.364  3792  3842 I jxcore-log: 
08-30 13:00:24.365  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.365  3792  3842 I jxcore-log: 
08-30 13:00:24.366  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.366  3792  3842 I jxcore-log: 
,08-30 13:00:24.367  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.367  3792  3842 I jxcore-log: 
08-30 13:00:24.368  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.368  3792  3842 I jxcore-log: 
,08-30 13:00:24.369  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.369  3792  3842 I jxcore-log: 
08-30 13:00:24.369  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.369  3792  3842 I jxcore-log: 
,08-30 13:00:24.370  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.370  3792  3842 I jxcore-log: 
,08-30 13:00:24.371  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.371  3792  3842 I jxcore-log: 
08-30 13:00:24.372  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.372  3792  3842 I jxcore-log: 
08-30 13:00:24.373  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.373  3792  3842 I jxcore-log: 
08-30 13:00:24.373  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.373  3792  3842 I jxcore-log: 
,08-30 13:00:24.374  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.374  3792  3842 I jxcore-log: 
08-30 13:00:24.375  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.375  3792  3842 I jxcore-log: 
08-30 13:00:24.376  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.376  3792  3842 I jxcore-log: 
,08-30 13:00:24.376  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.376  3792  3842 I jxcore-log: 
08-30 13:00:24.377  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.377  3792  3842 I jxcore-log: 
,08-30 13:00:24.378  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.378  3792  3842 I jxcore-log: 
,08-30 13:00:24.379  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.379  3792  3842 I jxcore-log: 
08-30 13:00:24.380  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.380  3792  3842 I jxcore-log: 
,08-30 13:00:24.381  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.381  3792  3842 I jxcore-log: 
,08-30 13:00:24.382  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.382  3792  3842 I jxcore-log: 
08-30 13:00:24.382  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.382  3792  3842 I jxcore-log: 
08-30 13:00:24.383  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.383  3792  3842 I jxcore-log: 
,08-30 13:00:24.383  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:00:24.383  3792  3842 I jxcore-log: 
08-30 13:00:24.384  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.384  3792  3842 I jxcore-log: 
,08-30 13:00:24.384  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 13:00:24.384  3792  3842 I jxcore-log: 
08-30 13:00:24.384  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.384  3792  3842 I jxcore-log: 
08-30 13:00:24.385  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.385  3792  3842 I jxcore-log: 
,08-30 13:00:24.386  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.386  3792  3842 I jxcore-log: 
08-30 13:00:24.386  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.386  3792  3842 I jxcore-log: 
,08-30 13:00:24.387  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.387  3792  3842 I jxcore-log: 
08-30 13:00:24.387  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:00:24.387  3792  3842 I jxcore-log: 
,08-30 13:00:24.388  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.388  3792  3842 I jxcore-log: 
08-30 13:00:24.388  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 13:00:24.388  3792  3842 I jxcore-log: 
08-30 13:00:24.389  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.389  3792  3842 I jxcore-log: 
,08-30 13:00:24.389  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:00:24.389  3792  3842 I jxcore-log: 
08-30 13:00:24.390  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 13:00:24.390  3792  3842 I jxcore-log: 
,08-30 13:00:24.390  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:00:24.390  3792  3842 I jxcore-log: 
08-30 13:00:24.391  3792  3842 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:00:24.391  3792  3842 I jxcore-log: 
,08-30 13:00:24.394  3792  3842 I jxcore-log: My device name is: motorola-Nexus 6
08-30 13:00:24.394  3792  3842 I jxcore-log: 
,08-30 13:00:24.454  3792  4267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-30 13:00:26.928  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 13:00:26.928  3792  3842 I jxcore-log: 
,08-30 13:00:27.376  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 13:00:27.376  3792  3842 I jxcore-log: 
,08-30 13:00:27.400  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 13:00:27.400  3792  3842 I jxcore-log: 
,08-30 13:00:28.784  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 13:00:28.784  3792  3842 I jxcore-log: 
,08-30 13:00:28.967  3745  4270 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 13:00:28.989  3745  4271 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 13:00:29.013  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:00:29.014  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:00:29.036  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-30 13:00:29.036  3792  3842 I jxcore-log: 
,08-30 13:00:29.041  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-30 13:00:29.041  3792  3842 I jxcore-log: 
,08-30 13:00:29.041  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 13:00:29.041  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:00:29.041  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:00:29.041  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:00:29.048  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
08-30 13:00:29.048  3792  3842 I jxcore-log: 
,08-30 13:00:29.063  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:00:29.065  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:00:29.085  1512  3043 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:00:29.085  1512  3043 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:00:29.085  1512  3043 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:00:29.086  1512  3043 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:00:29.104  3745  4271 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 13:00:29.105  3745  4270 E BooksSync: Soft error
08-30 13:00:29.105  3745  4270 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:00:29.105  3745  4270 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 13:00:29.105  3745  4270 E BooksSync: Sync error
08-30 13:00:29.105  3745  4270 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:00:29.105  3745  4270 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:00:29.105  3745  4270 I BooksSync: Finished books sync
,08-30 13:00:29.113   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 244550, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:00:29.132  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-30 13:00:29.132  3792  3842 I jxcore-log: 
,08-30 13:00:29.150  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-30 13:00:29.150  3792  3842 I jxcore-log: 
,08-30 13:00:29.155  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
08-30 13:00:29.155  3792  3842 I jxcore-log: 
,08-30 13:00:30.095  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
08-30 13:00:30.095  3792  3842 I jxcore-log: 
,08-30 13:00:30.271  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-30 13:00:30.271  3792  3842 I jxcore-log: 
,08-30 13:00:30.677  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-30 13:00:30.677  3792  3842 I jxcore-log: 
,08-30 13:00:30.690  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-30 13:00:30.690  3792  3842 I jxcore-log: 
,08-30 13:00:30.700  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-30 13:00:30.700  3792  3842 I jxcore-log: 
,08-30 13:00:30.708  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-30 13:00:30.708  3792  3842 I jxcore-log: 
,08-30 13:00:30.771  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-30 13:00:30.771  3792  3842 I jxcore-log: 
,08-30 13:00:30.826  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-30 13:00:30.826  3792  3842 I jxcore-log: 
,08-30 13:00:30.833  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-30 13:00:30.833  3792  3842 I jxcore-log: 
,08-30 13:00:30.842  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-30 13:00:30.842  3792  3842 I jxcore-log: 
,08-30 13:00:30.865  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-30 13:00:30.865  3792  3842 I jxcore-log: 
,08-30 13:00:30.870  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-30 13:00:30.870  3792  3842 I jxcore-log: 
,08-30 13:00:30.876  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-30 13:00:30.876  3792  3842 I jxcore-log: 
,08-30 13:00:30.892  3792  3842 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-30 13:00:30.892  3792  3842 I jxcore-log: 
,08-30 13:00:31.020  3792  3842 I jxcore-log: ERROR runTests: 
08-30 13:00:31.020  3792  3842 I jxcore-log: 
,08-30 13:00:31.022  3792  3842 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-30 13:00:31.022  3792  3842 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 13:00:31.034  3792  3842 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _functionName: 'loadFile',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _lineNumber: '26',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _columnNumber: '11',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 13:00:31.034  3792  3842 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _functionName: '',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _lineNumber: '38',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _columnNumber: '7',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 13:00:31.034  3792  3842 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _functionName: '',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _lineNumber: '35',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _columnNumber: '3',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 13:00:31.034  3792  3842 I jxcore-log:   { _fileName: 'module.js',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _lineNumber: '621',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _columnNumber: '8',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 13:00:31.034  3792  3842 I jxcore-log:   { _fileName: 'module.js',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _lineNumber: '651',
08-30 13:00:31.034  3792  3842 I jxcore-log:     _columnNumber: '1',
08-30 13:00:31.034  3792  3842 I jxcore-log:    
,08-30 13:00:31.034  3792  3842 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 13:00:31.034  3792  3842 I jxcore-log: 
08-30 13:00:31.035  3792  3842 E jxcore-log: Error: 
08-30 13:00:31.035  3792  3842 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-30 13:00:31.035  3792  3842 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
,08-30 13:00:31.035  3792  3842 E jxcore-log: 
,08-30 13:00:31.657  4273  4273 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 13:00:31.666  4273  4273 D AndroidRuntime: CheckJNI is OFF
,08-30 13:00:31.708  4273  4273 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 13:00:31.756  4273  4273 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 13:00:31.773   873  4226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=247483, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:00:31.780  4273  4273 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 13:00:31.794   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg,
08-30 13:00:31.795   873   886 I ActivityManager: Killing 3792:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 13:00:31.889   873  1980 D GraphicsStats: Buffer count: 2
,08-30 13:00:31.889   873  1958 I WindowState: WIN DEATH: Window{184d0ee u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 13:00:31.890   873  1302 D WifiService: Client connection lost with reason: 4
,08-30 13:00:31.946   873   896 W PackageSettings: Skipping PackageSetting{1b43d2b com.example.hello/10273} due to missing metadata
,08-30 13:00:31.978   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 13:00:31.978   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 13:00:31.979   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-30 13:00:31.979   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 13:00:31.979   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:31.979   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:31.979   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 13:00:31.979   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 13:00:31.979   873   886 I ActivityManager:   Force finishing activity ActivityRecord{f7358b7 u0 com.test.thalitest/.MainActivity t2}
08-30 13:00:31.980   873   896 I art     : Starting a blocking GC Explicit
,08-30 13:00:31.991   873  1968 W ActivityManager: Spurious death for ProcessRecord{be26311 0:com.test.thalitest/u0a0}, curProc for 3792: null
,08-30 13:00:32.025   873   896 I art     : Explicit concurrent mark sweep GC freed 30742(1956KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 779us total 43.603ms
,08-30 13:00:32.050   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 13:00:32.053  4273  4273 I art     : System.exit called, status: 0
,08-30 13:00:32.053  4273  4273 I AndroidRuntime: VM exiting with result code 0.
,08-30 13:00:32.059   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 13:00:32.080   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-30 13:00:32.085  4169  4169 D BluetoothMapAppObserver: onReceive
08-30 13:00:32.085  4169  4169 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 13:00:32.092  2106  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 13:00:32.094   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 13:00:32.090  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 13:00:32.111  3633  3633 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 13:00:32.129   873   884 I ActivityManager: Start proc 4287:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 13:00:32.132  1934  1934 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 13:00:32.156  1863  4286 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 13:00:32.163  1863  4286 I Decoder : createOrResetDecoder
,08-30 13:00:32.175  4287  4287 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 13:00:32.181  1512  1512 I ConfigService: onCreate
08-30 13:00:32.181   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 13:00:32.191  1512  4299 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 13:00:32.191  1512  4299 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 13:00:32.192  1512  4299 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 13:00:32.193   873  1969 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3792 uid 10000
08-30 13:00:32.194  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-30 13:00:32.195  1951  2031 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 13:00:32.196   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 13:00:32.198   873   885 E PackageManager: Failed to write settings, restoring backup
08-30 13:00:32.198   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 13:00:32.198   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 13:00:32.198   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 13:00:32.198   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 13:00:32.198   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 13:00:32.198   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.198   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.198   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 13:00:32.203  1512  4299 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-30 13:00:32.203   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-30 13:00:32.203   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 13:00:32.203   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:00:32.203   873   886 E DropBoxManagerService: 	... 13 more
,08-30 13:00:32.207   873  1968 I ActivityManager: Start proc 4300:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 13:00:32.208  1951  2031 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 13:00:32.208  1951  2031 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1951
08-30 13:00:32.208  1951  2031 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.208  1951  2031 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 13:00:32.210   873  4305 E DropBoxManagerService: Can't write: system_app_crash
08-30 13:00:32.210   873  4305 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:00:32.210   873  4305 E DropBoxManagerService: 	... 5 more
,08-30 13:00:32.214   873   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 13:00:32.215  1863  4286 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 13:00:32.220  1951  2031 I Process : Sending signal. PID: 1951 SIG: 9
,08-30 13:00:32.254  1863  4286 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 13:00:32.255  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 13:00:32.255  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 13:00:32.257  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 13:00:32.257  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 13:00:32.258  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 13:00:32.258  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 13:00:32.258  1863  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 13:00:32.258  1863  4286 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 13:00:32.258  1863  4286 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-30 13:00:32.259  1863  4286 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 13:00:32.259  1863  4286 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 13:00:32.259  1863  4286 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 13:00:32.273  4287  4287 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 13:00:32.282  4287  4318 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 13:00:32.290   873  1375 I ActivityManager: Start proc 4319:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 13:00:32.309   279   279 E lowmemorykiller: Error writing /proc/1951/oom_score_adj; errno=22
,08-30 13:00:32.309   873  1736 D GraphicsStats: Buffer count: 1
08-30 13:00:32.309   873   884 I WindowState: WIN DEATH: Window{32f0fb2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 13:00:32.316   873   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1951) has died
,08-30 13:00:32.317   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-30 13:00:32.318   873   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 13:00:32.336   873   886 I ActivityManager: Start proc 4332:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 13:00:32.344  4319  4319 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 13:00:32.386  4332  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:00:32.386  4332  4332 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 13:00:32.387  4332  4332 D AndroidRuntime: Shutting down VM
,08-30 13:00:32.387  1512  1512 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 13:00:32.389  1512  1512 D AndroidRuntime: Shutting down VM
,08-30 13:00:32.389  1512  1512 E AndroidRuntime: FATAL EXCEPTION: main
08-30 13:00:32.389  1512  1512 E AndroidRuntime: Process: com.google.process.gapps, PID: 1512
08-30 13:00:32.389  1512  1512 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 13:00:32.389  1512  1512 E AndroidRuntime: 	... 8 more
08-30 13:00:32.391  1723  4344 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 13:00:32.395  1723  4344 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-30 13:00:32.396  4332  4332 E AndroidRuntime: FATAL EXCEPTION: main
08-30 13:00:32.396  4332  4332 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4332
08-30 13:00:32.396  4332  4332 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 13:00:32.396  4332  4332 E AndroidRuntime: 	... 10 more
08-30 13:00:32.397   873  4347 E DropBoxManagerService: Can't write: system_app_crash
08-30 13:00:32.397   873  4347 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:00:32.397   873  4347 E DropBoxManagerService: 	... 5 more
,08-30 13:00:32.400  1512  1512 I Process : Sending signal. PID: 1512 SIG: 9
,08-30 13:00:32.400   873  1993 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 13:00:32.401  4332  4332 I Process : Sending signal. PID: 4332 SIG: 9
,08-30 13:00:32.406   873  4348 E DropBoxManagerService: Can't write: system_app_crash
08-30 13:00:32.406   873  4348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:00:32.406   873  4348 E DropBoxManagerService: 	... 5 more
,08-30 13:00:32.413  1723  4344 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 13:00:32.413  1723  4344 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 13:00:32.420  4287  4314 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.420  4287  4314 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.420  4287  4314 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 13:00:32.427   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4332) has died
,08-30 13:00:32.429   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 13:00:32.444   873   886 I ActivityManager: Start proc 4350:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 13:00:32.445   873  1736 I ActivityManager: Killing 3685:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 13:00:32.451   873  1302 D WifiService: Client connection lost with reason: 4
,08-30 13:00:32.471  4287  4314 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 13:00:32.475  4287  4318 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.475  4287  4318 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 13:00:32.476  4287  4318 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 13:00:32.476  4287  4318 E AndroidRuntime: Process: android.process.acore, PID: 4287
08-30 13:00:32.476  4287  4318 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.476  4287  4318 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 13:00:32.476  4287  4314 I Process : Sending signal. PID: 4287 SIG: 9
,08-30 13:00:32.488   873  1968 I ActivityManager: Process com.google.process.gapps (pid 1512) has died
,08-30 13:00:32.488   873  1968 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-30 13:00:32.489   873  1968 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-30 13:00:32.489   873  1968 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
,08-30 13:00:32.502   873  1993 I ActivityManager: Process android.process.acore (pid 4287) has died
,08-30 13:00:32.502   873  1993 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30986ms
,08-30 13:00:32.507   873  4362 E DropBoxManagerService: Can't write: system_app_crash
08-30 13:00:32.507   873  4362 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:00:32.507   873  4362 E DropBoxManagerService: 	... 5 more
,08-30 13:00:32.510  1723  1723 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-30 13:00:32.527  4350  4350 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:00:32.527  4350  4350 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 13:00:32.527  4350  4350 D AndroidRuntime: Shutting down VM
,08-30 13:00:32.530   873  1736 I ActivityManager: Start proc 4363:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-30 13:00:32.540  4350  4350 E AndroidRuntime: FATAL EXCEPTION: main
08-30 13:00:32.540  4350  4350 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4350
08-30 13:00:32.540  4350  4350 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 13:00:32.540  4350  4350 E AndroidRuntime: 	... 10 more
08-30 13:00:32.541   873  1968 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 13:00:32.542  4350  4350 I Process : Sending signal. PID: 4350 SIG: 9
08-30 13:00:32.542   873  4375 E DropBoxManagerService: Can't write: system_app_crash
08-30 13:00:32.542   873  4375 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:00:32.542   873  4375 E DropBoxManagerService: 	... 5 more

```
