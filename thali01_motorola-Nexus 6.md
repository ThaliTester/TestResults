#### Test 82914073b1ed9e5_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 18:47:46.191  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:47:46.206  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 18:47:46.212  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 18:47:46.291  1513  2329 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 18:47:46.291  1513  2329 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 18:47:46.292  1513  2329 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:47:46.292  1513  2329 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 18:47:46.334  3520  3520 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 18:47:46.335  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 18:47:46.336  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-31 18:47:46.890  3800  3800 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 18:47:46.895  3800  3800 D AndroidRuntime: CheckJNI is OFF
08-31 18:47:46.934  3800  3800 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 18:47:46.979  3800  3800 I Radio-JNI: register_android_hardware_Radio DONE
08-31 18:47:46.998  3800  3800 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 18:47:47.004   872  1694 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 18:47:47.072  2028  2040 W SearchService: Abort, client detached.
08-31 18:47:47.077  2028  2028 I HotwordDetector: Closing mic
08-31 18:47:47.078  2028  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cbf760d
08-31 18:47:47.078  2028  2346 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-31 18:47:47.092  3800  3800 D AndroidRuntime: Shutting down VM
08-31 18:47:47.115   872  2289 I ActivityManager: Start proc 3809:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 18:47:47.136   376  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 18:47:47.138   376  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 18:47:47.143   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 18:47:47.145  2028  2345 I MicroRecognitionRnrImpl: Detection finished
08-31 18:47:47.146  2028  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-31 18:47:47.201  3809  3809 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 18:47:47.232  3809  3809 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 18:47:47.245  3809  3809 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1522-1528)
08-31 18:47:47.246  3809  3809 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 18:47:47.260   872  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-31 18:47:47.290  3809  3809 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {149e86}
08-31 18:47:47.290  3809  3809 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 18:47:47.291  3809  3809 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 18:47:47.300  3809  3809 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 18:47:47.301  3809  3809 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 18:47:47.324  3809  3809 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 18:47:47.348  3809  3809 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 18:47:47.348  3809  3809 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 18:47:47.348  3809  3809 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 18:47:47.348  3809  3809 I Adreno  : Build Date                       : 10/20/15
08-31 18:47:47.348  3809  3809 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 18:47:47.348  3809  3809 I Adreno  : Local Branch                     : M14
08-31 18:47:47.348  3809  3809 I Adreno  : Remote Branch                    : 
08-31 18:47:47.348  3809  3809 I Adreno  : Remote Branch                    : 
08-31 18:47:47.348  3809  3809 I Adreno  : Reconstruct Branch               : 
,08-31 18:47:47.435   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@afffae5:true
,08-31 18:47:47.480  3809  3809 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 18:47:47.493  3809  3809 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 18:47:47.558  3809  3847 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 18:47:47.571  3809  3834 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 18:47:47.605  3809  3847 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 18:47:47.681   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +589ms
,08-31 18:47:47.688  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-31 18:47:47.782  3809  3809 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3809
,08-31 18:47:47.902   872  2288 I ActivityManager: Killing 3205:com.google.android.gm/u0a78 (adj 15): empty #17
,08-31 18:47:47.942  3809  3809 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 18:47:47.960   872  2288 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-31 18:47:48.087  3809  3850 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1679095504
,08-31 18:47:48.094  3809  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 18:47:48.094  3809  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 18:47:48.094  3809  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 18:47:48.094  3809  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 18:47:48.094  3809  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 18:47:48.095  3809  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c35415 added. We now have 1 listener(s)
08-31 18:47:48.099  3809  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 18:47:48.100  3809  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 18:47:48.101  3809  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:47:48.102  3809  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 18:47:48.110  3809  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51f06b8 added. We now have 1 listener(s)
08-31 18:47:48.111  3809  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:47:48.114   872  1309 D WifiService: New client listening to asynchronous messages
08-31 18:47:48.115  3809  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:47:48.115  3809  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 18:47:48.115  3809  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 18:47:48.115  3809  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 18:47:48.116  3809  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 18:47:48.120  3809  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:47:48.120  3809  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-31 18:47:48.127  3809  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:47:48.127  3809  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:47:48.127  3809  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 18:47:48.127  3809  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 18:47:48.130  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:47:48.131  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:47:48.134  3809  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 18:47:48.161  3809  3809 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 18:47:48.924   872  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-31 18:47:49.119  3809  3859 W jxcore-log: Initializing JXcore engine
,08-31 18:47:49.120  3809  3859 W jxcore-log: JXcore engine is ready
,08-31 18:47:49.162  3859  3859 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-31 18:47:49.162  3859  3859 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9722]" dev="sockfs" ino=9722 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 18:47:49.162  3859  3859 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 18:47:49.162  3859  3859 W Thread-330: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25746]" dev="sockfs" ino=25746 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 18:47:49.177  3809  3859 W jxcore-log: Starting JXcore engine
,08-31 18:47:49.261  3809  3859 W jxcore-log: Platform android
08-31 18:47:49.261  3809  3859 W jxcore-log: 
08-31 18:47:49.262  3809  3859 W jxcore-log: Process ARCH arm
08-31 18:47:49.262  3809  3859 W jxcore-log: 
,08-31 18:47:49.513  3809  3859 I jxcore-log: JXcore Cordova bridge is ready!
08-31 18:47:49.513  3809  3859 I jxcore-log: 
08-31 18:47:49.513  3809  3859 W jxcore-log: JXcore engine is started
,08-31 18:47:49.521  3809  3850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 18:47:49.526  3809  3809 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 18:47:51.569   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 18:47:54.599   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 18:47:55.236  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:47:55.238  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:47:55.264  1513  2047 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 18:47:55.264  1513  2047 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 18:47:55.264  1513  2047 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:47:55.264  1513  2047 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:47:55.301  3002  3869 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 18:47:55.301  3002  3869 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jdm.a(PG:82)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jcs.o(PG:406)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jcn.a(PG:1379)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jcs.i(PG:143)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at blb.a(PG:3937)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at czp.a(PG:18188)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at czp.a(PG:9081)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at czq.run(PG:1686)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 18:47:55.301  3002  3869 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jdj.a(PG:4091)
08-31 18:47:55.301  3002  3869 E HttpOperation: ,	at jdj.a(PG:1125)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jdm.a(PG:77)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	... 12 more
08-31 18:47:55.301  3002  3869 E HttpOperation: Caused by: faj: BadAuthentication
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at fal.a(PG:38)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	at jdj.a(PG:4089)
08-31 18:47:55.301  3002  3869 E HttpOperation: 	... 14 more
,08-31 18:47:55.341  1513  2890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 18:47:55.341  1513  2890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 18:47:55.341  1513  2890 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:47:55.341  1513  2890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:47:55.369  3002  3869 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 18:47:55.369  3002  3869 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jdm.a(PG:82)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jcs.o(PG:406)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jcn.a(PG:1379)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jcs.i(PG:143)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at hec.a(PG:42)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at hee.a(PG:102)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at czr.a(PG:65)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at kka.a(PG:108)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at czp.a(PG:19176)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at czp.a(PG:9081)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at czq.run(PG:1686)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 18:47:55.369  3002  3869 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jdj.a(PG:4091)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jdj.a(PG:1125)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jdm.a(PG:77)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	... 15 more
08-31 18:47:55.369  3002  3869 E HttpOperation: Caused by: faj: BadAuthentication
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at fal.a(PG:38)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	at jdj.a(PG:4089)
08-31 18:47:55.369  3002  3869 E HttpOperation: 	... 17 more
08-31 18:47:55.370  3002  3869 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 18:47:55.370  3002  3869 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at hec.a(PG:42)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at hee.a(PG:102)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at czr.a(PG:65)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at kka.a(PG:108)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	... 15 more
08-31 18:47:55.370  3002  3869 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at fal.a(PG:38)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 18:47:55.370  3002  3869 E ExperimentLoader: 	... 17 more
,08-31 18:47:55.492   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 129315, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 18:47:55.593  3588  3872 V KeepSync: Connecting to GoogleApiClient
,08-31 18:47:55.594   872  2289 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 18:47:55.658  1513  2329 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-31 18:47:55.658  1513  2329 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 18:47:55.658  1513  2329 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:47:55.658  1513  2329 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:47:55.696  1718  3873 V BaseAuthAsyncOperation: access token request failed
,08-31 18:47:55.697  3588  3872 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 18:47:55.749  1513  2890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-31 18:47:55.750  1513  2890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-31 18:47:55.750  1513  2890 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:47:55.750  1513  2890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:47:55.769  3588  3872 E KeepSync: IOException
08-31 18:47:55.769  3588  3872 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 18:47:55.769  3588  3872 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 18:47:55.769  3588  3872 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 18:47:55.769  3588  3872 E KeepSync: 	... 10 more
,08-31 18:47:55.769  3588  3872 W KeepSync: Sync result 2
,08-31 18:47:55.780   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129459, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 18:47:59.533  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 18:47:59.533  3809  3859 I jxcore-log: 
,08-31 18:47:59.536  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 18:47:59.536  3809  3859 I jxcore-log: 
,08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:47:59.548  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:47:59.555  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:47:59.562  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 18:47:59.562  3809  3859 I jxcore-log: 
,08-31 18:47:59.571  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 18:47:59.571  3809  3859 I jxcore-log: 
,08-31 18:48:00.130  3809  3859 D executeNativeTests: Running unit tests
,08-31 18:48:00.188  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:48:00.188  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a added. We now have 2 listener(s)
08-31 18:48:00.189  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:00.189  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 18:48:00.189  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:00.190  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:00.190  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b added. We now have 2 listener(s)
08-31 18:48:00.190  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:00.191  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 18:48:00.200  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:00.211  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:00.214  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.214  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:00.217  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 18:48:00.217  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:48:00.217  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:48:00.218  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.219  3809  3859 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 18:48:00.219  3809  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 18:48:00.219  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 18:48:00.219  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:48:00.220  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:48:00.220  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.220  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.220  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.220  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.221  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.221  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.221  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:00.221  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:00.221  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a removed from the list
08-31 18:48:00.221  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.221  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b removed from the list
08-31 18:48:00.221  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.222  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.222  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.222  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.223  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.223  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.223  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.223  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.225  3809  3859 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 18:48:00.225  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.225  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.225  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.226  3809  38,59 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.226  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.226  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.226  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.226  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.226  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.226  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.226  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.226  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.226  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.226  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.227  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.227  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.227  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.227  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.233  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 18:48:00.233  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 18:48:00.233  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 18:48:00.234  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 18:48:00.235  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-31 18:48:00.235  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.235  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.235  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.235  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.236  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.236  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.236  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
,08-31 18:48:00.236  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.236  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.236  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.236  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.236  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.236  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.236  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.237  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 18:48:00.237  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.237  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.237  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.238  3809  3859 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 18:48:00.242  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:00.253  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:00.255  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:00.255  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 18:48:00.256  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 18:48:00.256  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:48:00.256  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:48:00.256  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:00.256  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 18:48:00.259  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:00.260  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 18:48:00.260  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 18:48:00.262  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:00.267  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 18:48:00.269  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 18:48:00.269  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 18:48:00.273  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 18:48:00.276  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 18:48:00.277  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 18:48:00.277  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 18:48:00.278  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 18:48:00.280  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:00.285  2713  2728 D BtGatt.GattService: registerClient() - UUID=c4d7f130-7990-4549-bd14-a8d1c133ad36
,08-31 18:48:00.286  2713  2768 D BtGatt.GattService: onClientRegistered() - UUID=c4d7f130-7990-4549-bd14-a8d1c133ad36, clientIf=5
08-31 18:48:00.287  3809  3821 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 18:48:00.287  2713  2912 D BtGatt.GattService: start scan with filters
,08-31 18:48:00.293  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 18:48:00.294  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 18:48:00.294  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 18:48:00.294  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 18:48:00.294  2713  2786 D BtGatt.ScanManager: handling starting scan
,08-31 18:48:00.297  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:00.297  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:00.299  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 18:48:00.297  2713  2786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:00.302  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 18:48:00.307  2713  2768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 18:48:00.307  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.308  2713  2786 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-31 18:48:00.311  3809  3859 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 18:48:00.316  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.316  3809  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 18:48:00.319  2713  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 18:48:00.319  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.317  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:00.319  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 18:48:00.320  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.320  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 18:48:00.320  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 18:48:00.320  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 18:48:00.320  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 18:48:00.320  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 18:48:00.320  2713  2786 D BtGatt.ScanManager: Starting BLE batch scan
08-31 18:48:00.320  2713  2786 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 18:48:00.320  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 18:48:00.321  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 18:48:00.321  3809  3859 D BluetoothAdapter: STATE_ON,
08-31 18:48:00.322  2713  2727 D BtGatt.GattService: stopScan() - queue size =1
08-31 18:48:00.323  2713  2728 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 18:48:00.323  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:48:00.323  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 18:48:00.323  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 18:48:00.323  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 18:48:00.323  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 18:48:00.325  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.325  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 18:48:00.325  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 18:48:00.325  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 18:48:00.326  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:00.327  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.327  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.327  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.327  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:00.327  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.327  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
,08-31 18:48:00.328  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.328  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.328  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.328  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:00.328  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.328  3809  3859 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 18:48:00.329  2713  2768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 18:48:00.329  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.330  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:00.335  2713  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:00.335  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:00.335  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.337  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.337  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:00.337  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:48:00.337  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:48:00.338  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:48:00.338  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:00.338  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:48:00.341  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 18:48:00.342  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.342  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 18:48:00.345  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.345  2713  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 18:48:00.345  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.345  2713  2786 D BtGatt.ScanManager: stopping BLe Batch
,08-31 18:48:00.349  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:48:00.350  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 18:48:00.350  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 18:48:00.351  2713  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 18:48:00.352  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.352  2713  2786 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 18:48:00.353  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 18:48:00.353  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 18:48:00.353  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 18:48:00.354  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:00.356  2713  2728 D BtGatt.GattService: registerClient() - UUID=fbb83e58-648d-4698-8653-1300edf3967d
,08-31 18:48:00.356  2713  2768 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 18:48:00.356  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.357  2713  2768 D BtGatt.GattService: onClientRegistered() - UUID=fbb83e58-648d-4698-8653-1300edf3967d, clientIf=5
08-31 18:48:00.357  3809  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 18:48:00.358  2713  2727 D BtGatt.GattService: start scan with filters
,08-31 18:48:00.360  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 18:48:00.360  2713  2786 D BtGatt.ScanManager: handling starting scan
08-31 18:48:00.360  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 18:48:00.360  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 18:48:00.360  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 18:48:00.362  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:00.362  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:00.362  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 18:48:00.364  2713  2768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 18:48:00.364  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.364  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 18:48:00.364  2713  2786 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 18:48:00.366  3809  3859 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 18:48:00.368  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.368  3809  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 18:48:00.368  2713  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 18:48:00.368  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.368  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.368  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 18:48:00.368  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.368  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 18:48:00.368  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 18:48:00.368  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 18:48:00.368  2713  2786 D BtGatt.ScanManager: Starting BLE batch scan
08-31 18:48:00.368  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 18:48:00.368  2713  2786 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 18:48:00.368  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 18:48:00.369  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 18:48:00.369  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 18:48:00.369  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:00.373  2713  2728 D BtGatt.GattService: stopScan() - queue size =1
,08-31 18:48:00.373  2713  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 18:48:00.374  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:48:00.374  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 18:48:00.374  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 18:48:00.374  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 18:48:00.374  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 18:48:00.375  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.375  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 18:48:00.375  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 18:48:00.375  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:48:00.375  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 18:48:00.376  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.376  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.376  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.376  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:00.377  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.377  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:00.377  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.377  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.377  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.377  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.377  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.377  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.377  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.378  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.378  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:00.378  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.378  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.379  3809  3859 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 18:48:00.380  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:00.380  2713  2768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 18:48:00.380  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:00.384  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:00.385  2713  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 18:48:00.385  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.385  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.385  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:00.386  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:48:00.386  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 18:48:00.386  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:48:00.386  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:00.386  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 18:48:00.388  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.388  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 18:48:00.388  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 18:48:00.389  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:00.391  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 18:48:00.392  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 18:48:00.392  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 18:48:00.394  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 18:48:00.394  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 18:48:00.394  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 18:48:00.394  2713  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 18:48:00.394  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.394  2713  2786 D BtGatt.ScanManager: stopping BLe Batch
,08-31 18:48:00.394  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:00.395  2713  2728 D BtGatt.GattService: registerClient() - UUID=29563f40-7094-49d1-91b1-fa4be402736d
08-31 18:48:00.396  2713  2768 D BtGatt.GattService: onClientRegistered() - UUID=29563f40-7094-49d1-91b1-fa4be402736d, clientIf=5
,08-31 18:48:00.396  3809  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 18:48:00.396  2713  2912 D BtGatt.GattService: start scan with filters
,08-31 18:48:00.398  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 18:48:00.398  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 18:48:00.398  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 18:48:00.398  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 18:48:00.399  2713  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 18:48:00.399  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.399  2713  2786 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 18:48:00.400  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 18:48:00.400  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 18:48:00.400  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 18:48:00.401  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 18:48:00.403  3809  3859 I io.jxcore.node.ConnectionHelper: start: OK
08-31 18:48:00.403  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.403  3809  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 18:48:00.403  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.403  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 18:48:00.403  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.403  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 18:48:00.403  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 18:48:00.403  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 18:48:00.403  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 18:48:00.403  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 18:48:00.403  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 18:48:00.403  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 18:48:00.404  2713  2768 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 18:48:00.404  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:00.404  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.404  2713  2727 D BtGatt.GattService: stopScan() - queue size =0
,08-31 18:48:00.405  2713  2728 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 18:48:00.405  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:48:00.405  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-31 18:48:00.405  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 18:48:00.405  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 18:48:00.405  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 18:48:00.405  2713  2786 D BtGatt.ScanManager: handling starting scan
08-31 18:48:00.406  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.406  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-31 18:48:00.406  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 18:48:00.406  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 18:48:00.406  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:00.407  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.407  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 18:48:00.407  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.407  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.407  3809  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 18:48:00.407  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.407  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:48:00.407  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.408  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.408  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:00.408  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
,08-31 18:48:00.408  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.408  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.408  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.408  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.408  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.408  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.409  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.409  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.409  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.409  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.409  3809  3859 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 18:48:00.410  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.410  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.410  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.410  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 18:48:00.410  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.410  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.410  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list,
08-31 18:48:00.410  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.410  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.410  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.410  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.410  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.410  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.410  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.410  2713  2768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 18:48:00.411  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.411  2713  2786 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 18:48:00.411  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:48:00.411  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.411  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 18:48:00.411  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.412  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 18:48:00.412  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.412  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.412  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.412  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.412  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 18:48:00.412  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.412  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.413  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 18:48:00.413  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.413  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.413  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.413  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.413  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.413  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 18:48:00.413  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.413  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.413  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.414  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.414  3809  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 18:48:00.414  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.414  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:00.414  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.414  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.414  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.414  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.414  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list,
08-31 18:48:00.414  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.415  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.415  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:00.415  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.415  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.415  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.415  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.416  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.416  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:00.416  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.416  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.416  2713  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 18:48:00.416  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.416  2713  2786 D BtGatt.ScanManager: Starting BLE batch scan
08-31 18:48:00.416  2713  2786 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 18:48:00.416  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 18:48:00.416  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:00.416  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.416  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.416  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.417  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.417  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.417  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.417  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.417  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.417  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.417  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.417  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.417  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.417  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.418  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.418  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.418  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.418  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.418  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 18:48:00.419  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:48:00.419  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 18:48:00.420  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:48:00.420  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 18:48:00.420  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:48:00.420  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.420  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:00.420  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.421  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:00.421  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.421  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.422  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.422  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.422  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.422  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.422  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.422  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.422  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.422  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.426  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.426  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.427  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.427  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.428  2713  2768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 18:48:00.428  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.428  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:48:00.429  3809  3859 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 18:48:00.429  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 18:48:00.433  2713  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 18:48:00.433  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.437  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:48:00.437  3809  3859 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 18:48:00.437  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 18:48:00.437  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 18:48:00.437  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 18:48:00.438  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 18:48:00.439  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 18:48:00.439  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-31 18:48:00.439  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 18:48:00.439  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 18:48:00.440  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 18:48:00.440  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 18:48:00.440  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 18:48:00.440  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 18:48:00.440  2713  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 18:48:00.440  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.440  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-31 18:48:00.440  2713  2786 D BtGatt.ScanManager: stopping BLe Batch
08-31 18:48:00.440  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 18:48:00.441  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 18:48:00.442  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 18:48:00.442  3809  3859 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 18:48:00.442  3809  3859 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 18:48:00.442  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:48:00.443  3809  3859 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 18:48:00.443  3809  3859 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 18:48:00.443  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:48:00.443  3809  3859 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 18:48:00.443  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 18:48:00.445  2713  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 18:48:00.445  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:00.445  2713  2786 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 18:48:00.448  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 18:48:00.448  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 18:48:00.448  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 18:48:00.449  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-31 18:48:00.449  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 18:48:00.449  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 18:48:00.450  3809  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-31 18:48:00.450  2713  2768 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 18:48:00.450  2713  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:00.450  3809  3859 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 18:48:00.451  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.451  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.451  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.451  3809  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
,08-31 18:48:00.451  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.451  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.451  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.452  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 18:48:00.453  3809  3877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:48:00.453  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.453  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.453  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.453  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:00.453  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.453  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.453  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.453  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.454  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.454  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.455  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.455  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.456  3809  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
,08-31 18:48:00.457  3809  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-31 18:48:00.457  2713  2906 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-31 18:48:00.458  3809  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-31 18:48:00.457  3809  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-31 18:48:00.459  3809  3859 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 18:48:00.460  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.460  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.460  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.461  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.461  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.461  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.461  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.461  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.461  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.461  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.461  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.462  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.462  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.462  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.462  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.463  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:00.463  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.463  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.463  3809  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 18:48:00.463  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.463  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.463  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:48:00.464  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.464  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.464  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.464  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.464  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.464  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.464  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.464  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.464  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.464  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.464  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.465  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.465  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.465  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.465  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.465  3809  3859 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 18:48:00.465  3809  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 18:48:00.466  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 18:48:00.466  3809  3859 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 18:48:00.466  3809  3859 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 18:48:00.466  3809  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 18:48:00.466  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 18:48:00.466  3809  3859 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 18:48:00.466  3809  3859 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 18:48:00.466  3809  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 18:48:00.466  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 18:48:00.466  3809  3859 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 18:48:00.466  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.466  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.466  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:48:00.466  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.466  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.466  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.467  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.467  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.467  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.467  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:00.467  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.467  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.467  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.467  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.468  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:48:00.468  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.468  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.468  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.468  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.468  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.468  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.468  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.468  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.468  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.468  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:00.468  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.468  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.469  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.469  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.469  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.469  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.469  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.469  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
,08-31 18:48:00.469  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.469  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.469  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.469  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:00.469  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.469  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.469  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.469  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.469  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.469  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.469  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.469  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.470  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:00.470  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.470  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.470  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.470  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.470  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.471  3809  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-31 18:48:00.472  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:00.472  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 18:48:00.473  3809  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-31 18:48:00.473  3809  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 18:48:00.473  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 18:48:00.473  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 18:48:00.473  3809  3809 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-31 18:48:00.474  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.474  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 18:48:00.474  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 18:48:00.474  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-31 18:48:00.474  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.474  3809  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 18:48:00.474  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
,08-31 18:48:00.474  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:00.474  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 18:48:00.474  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 18:48:00.474  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 18:48:00.474  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.474  3809  3809 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-31 18:48:00.474  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.474  3809  3879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:48:00.475  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.475  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.475  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.475  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.475  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.475  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:00.475  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.475  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.475  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.475  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:00.475  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
,08-31 18:48:00.476  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.476  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:00.476  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.476  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.476  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.476  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:00.476  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.476  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.477  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:48:00.477  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.477  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.477  3809  3879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 18:48:00.477  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
,08-31 18:48:00.477  3809  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-31 18:48:00.477  3809  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-31 18:48:00.477  3809  3809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 18:48:00.478  3809  3859 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-31 18:48:00.478  3809  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 18:48:00.478  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 18:48:00.478  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:48:00.478  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.478  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:00.478  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-31 18:48:00.478  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.478  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.478  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.478  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.478  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.478  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.478  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.479  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.479  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.479  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.479  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.479  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.479  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.479  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.479  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.482  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.482  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.482  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.482  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.482  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.482  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.482  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.482  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.483  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.483  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.483  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.483  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.483  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: rele,ase: The given listener does not exist in the list - probably already removed
08-31 18:48:00.483  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.483  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.483  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.483  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.483  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.484  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:00.484  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:00.484  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:00.484  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:00.484  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.484  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.484  3809  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc1b7a not in the list
08-31 18:48:00.484  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.484  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.484  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:00.484  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.484  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.484  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:00.484  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:00.485  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:00.485  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:00.485  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:00.485  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f730f2b not in the list
08-31 18:48:00.486  3809  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 18:48:00.486  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 18:48:00.486  3809  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 18:48:00.486  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 18:48:00.486  3809  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 18:48:00.486  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 18:48:00.487  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 18:48:00.487  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 18:48:00.488  3809  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 18:48:00.488  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 18:48:00.488  3809  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 18:48:00.488  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 18:48:00.488  3809  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 18:48:00.488  3809  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 18:48:00.488  3809  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 18:48:00.488  3809  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 18:48:00.489  3809  3859 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 18:48:00.489  3809  3859 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 18:48:00.489  3809  3859 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 18:48:00.489  3809  3859 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 18:48:00.490  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:00.490  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab19815 added. We now have 2 listener(s)
08-31 18:48:00.490  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:00.491  3809  3859 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 18:48:00.491   872  1906 D WifiService: setWifiEnabled: true pid=3809, uid=10000
08-31 18:48:00.491   872  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 18:48:00.491  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:00.492  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f32572a added. We now have 3 listener(s)
08-31 18:48:00.492  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:00.494  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:00.495  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37a191b added. We now have 4 listener(s)
08-31 18:48:00.495  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:00.496  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:00.496  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4851ab8 added. We now have 5 listener(s)
08-31 18:48:00.496  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:00.497   872   882 D WifiService: setWifiEnabled: false pid=3809, uid=10000
08-31 18:48:00.497   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 18:48:00.499  2713  2763 D BluetoothAdapterState: Current state: ON, message: 23
08-31 18:48:00.499  2713  2763 D BluetoothAdapterProperties: Setting state to 13
08-31 18:48:00.499  2713  2763 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 18:48:00.500  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:00.500  2713  2763 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 18:48:00.501  2713  2763 I BluetoothAdapterState: Entering PendingCommandState
08-31 18:48:00.504  2713  2713 D BluetoothMapService: onReceive
08-31 18:48:00.504  2713  2713 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:48:00.504  2713  2713 D BluetoothMapService: STATE_TURNING_OFF
08-31 18:48:00.504  2713  2713 D BluetoothMapService: MAP Service closeService in
08-31 18:48:00.504  2713  2713 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 18:48:00.504  2713  2713 D ObexServerSockets0: shutdown(block = true)
08-31 18:48:00.504  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 18:48:00.504  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 18:48:00.505  2713  2906 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 18:48:00.505  2713  2920 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 18:48:00.505  2713  2921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 18:48:00.505  2713  2713 I BtOppRfcommListener: stopping Accept Thread
08-31 18:48:00.503  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:00.506  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:48:00.506  2713  3432 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:48:00.506  2713  3432 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 18:48:00.507  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.507  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.507  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:00.510  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.511  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 18:48:00.512  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.513   872   885 I ActivityManager: Start proc 3882:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-31 18:48:00.513   872  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 18:48:00.514   872  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 18:48:00.514   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 18:48:00.514   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:48:00.514  2713  2768 D BluetoothAdapterProperties: Scan Mode:20
08-31 18:48:00.514  2713  2763 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 18:48:00.516  2713  2713 D HeadsetService: Received stop request...Stopping profile...
08-31 18:48:00.516  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:00.516  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:48:00.518  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.517   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:00.518  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:00.518  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:00.518  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.518  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:00.518  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:00.518  1947  1967 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:00.518   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:00.518   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:00.519  1373  2060 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:00.521  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.521  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 18:48:00.521  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:48:00.522  2713  2768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 18:48:00.522  2713  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:00.522  2713  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:00.522  2713  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:00.522  2713  2768 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 18:48:00.523  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.522  2713  2713 D A2dpService: Received stop request...Stopping profile...
08-31 18:48:00.523  2713  2915 D A2dpStateMachine: Exit Disconnected: -1
08-31 18:48:00.524   872  1880 D DhcpClient: Clearing IP address
08-31 18:48:00.524   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-31 18:48:00.524   872   872 D BluetoothA2dp: Proxy object disconnected
08-31 18:48:00.526  2713  2713 D HidService: Received stop request...Stopping profile...
08-31 18:48:00.526  2713  2713 D HidService: Stopping Bluetooth HidService
08-31 18:48:00.526  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:00.527  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-31 18:48:00.527  1373  1373 D BluetoothA2dp: Proxy object disconnected
,08-31 18:48:00.527  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-31 18:48:00.527  1373  1373 D HidProfile: Bluetooth service disconnected
,08-31 18:48:00.527  2713  2713 D HealthService: Received stop request...Stopping profile...
,08-31 18:48:00.528   372   870 D CommandListener: Setting iface cfg
08-31 18:48:00.528  2713  2713 D PanService: Received stop request...Stopping profile...
08-31 18:48:00.529  2713  2713 D BluetoothMapService: Received stop request...Stopping profile...
08-31 18:48:00.529  2713  2713 D BluetoothMapService: stop()
08-31 18:48:00.530  2713  2713 D BluetoothMapAppObserver: deinitObservers()
08-31 18:48:00.530  2713  2713 D BluetoothMapAppObserver: removeReceiver()
08-31 18:48:00.530  1513  2480 V NativeCrypto: Read error: ssl=0x9b3dc000: I/O error during system call, Connection timed out
08-31 18:48:00.530  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 18:48:00.530  1373  1373 D PanProfile: Bluetooth service disconnected
08-31 18:48:00.530  1373  1373 D BluetoothMap: Proxy object disconnected
08-31 18:48:00.530  1373  1373 D MapProfile: Bluetooth service disconnected
08-31 18:48:00.531   872  1891 D DhcpClient: Receive thread stopped
08-31 18:48:00.532  1513  2480 V NativeCrypto: SSL shutdown failed: ssl=0x9b3dc000: I/O error during system call, Broken pipe
08-31 18:48:00.533   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 18:48:00.533   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-31 18:48:00.534   872  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-31 18:48:00.535   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 18:48:00.535  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:00.535  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.535  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:00.535  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:00.535   395   395 E Parcel  : Reading a NULL string not supported here.
08-31 18:48:00.537   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-31 18:48:00.538   872  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 18:48:00.543  2713  2768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 18:48:00.543  2713  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:00.543  2713  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:00.543  2713  2895 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:48:00.543  2713  2895 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:48:00.543  2713  2895 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:48:00.543  2713  2895 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:48:00.544  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:00.544  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.544  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:00.544  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:00.544   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 18:48:00.544  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 18:48:00.544  2713  2768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 18:48:00.545  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 18:48:00.545  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:00.545  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.546  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:00.546  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:00.546  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 18:48:00.546  2713  2768 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-3,1 18:48:00.546   872  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 18:48:00.546  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 18:48:00.547  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:00.547  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.547  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:00.547  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:00.548  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 18:48:00.548  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 18:48:00.548  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:00.548  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:48:00.549  2713  2713 D BluetoothMapService: MAP Service closeService in
08-31 18:48:00.549  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:00.549  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.549  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:00.549  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:00.550  2713  2763 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 18:48:00.550  2713  2763 D BluetoothAdapterProperties: Setting state to 15
08-31 18:48:00.550  2713  2763 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 18:48:00.551  1373  1388 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 18:48:00.551  2713  2763 I BluetoothAdapterState: Entering BleOnState
08-31 18:48:00.551  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 18:48:00.551  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.551  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:00.552  1373  2060 D BluetoothPan: onBluetoothStateChange on: false
08-31 18:48:00.552   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 18:48:00.552  1373  2052 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 18:48:00.553  1373  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:00.553  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:00.553  3809  3809 V io.jxcore.nod,e.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:00.553  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:48:00.554   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:00.554  1947  1968 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:00.554  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:00.554  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:00.554  1373  1387 D BluetoothMap: onBluetoothStateChange: up=false
08-31 18:48:00.555   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:00.555   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:00.555  2713  2763 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 18:48:00.555  2713  2763 D BluetoothAdapterProperties: Setting state to 16
08-31 18:48:00.555  2713  2763 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 18:48:00.556  2713  2763 D BluetoothAdapterProperties: onBleDisable
08-31 18:48:00.556  2713  2763 I BluetoothAdapterState: Entering PendingCommandState
08-31 18:48:00.556  2713  2765 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 18:48:00.557  2713  2768 D BluetoothAdapterProperties: Scan Mode:20
08-31 18:48:00.558  2713  2895 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 18:48:00.558  2713  2895 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:00.557  2713  2713 D BluetoothMapService: cleanup()
08-31 18:48:00.558  2713  2713 D BluetoothMapService: MAP Service closeService in
08-31 18:48:00.561  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.562  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.563  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.564  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.568  1991  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:48:00.578   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 18:48:00.582  3882  3882 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-31 18:48:00.595   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 18:48:00.595   872  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 18:48:00.596   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:48:00.596  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 18:48:00.599   872   889 D Tethering: MasterInitialState.processMessage what=3
08-31 18:48:00.602  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:48:00.604  3383  3383 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a8c63a0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-31 18:48:00.607  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.608  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:00.616   872  2288 I ActivityManager: Start proc 3901:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-31 18:48:00.622   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@453178a:true
08-31 18:48:00.635  3882  3882 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 18:48:00.639  3882  3882 D BluetoothMap: Create BluetoothMap proxy object
08-31 18:48:00.647   372   870 E Netd    : netlink response contains error (No such file or directory)
08-31 18:48:00.648   872  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 18:48:00.648  3882  3882 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 18:48:00.650  3901  3901 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-31 18:48:00.659  3882  3882 D DockEventReceiver: finishStartingService: stopping service
08-31 18:48:00.665   872  2290 I ActivityManager: Killing 3383:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 18:48:00.761  2713  2768 I bt_hci  : shut_down
,08-31 18:48:00.780  2713  2787 I bt_vendor: low_power_mode_cb
,08-31 18:48:00.785  2713  2787 D bt_hwcfg: hw_epilog_process
,08-31 18:48:00.802  2713  2787 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 18:48:00.802  2713  2787 I bt_vendor: epilog_cb
,08-31 18:48:00.802  2713  2787 I bt_hci  : epilog_finished_callback
,08-31 18:48:00.805  2713  2768 I bt_hci_h4: hal_close
08-31 18:48:00.805  2713  2768 I bt_userial_vendor: device fd = 51 close
,08-31 18:48:00.883  3901  3901 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:00.883  3901  3901 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:00.883  3901  3901 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java),
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148),
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 18:48:00.883  3901  3901 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263),
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 18:48:00.883  3901  3901 D StrictMode: ,	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 18:48:00.883  3901  3901 D StrictMode: 	,at com.google.r.k.d(PG:1187)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23),
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 18:48:00.883  3901  3901 D StrictMode: ,	at com.google.r.y.a(PG:2188)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:15188),
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.883  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:00.884  3901  3901 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.884  3901  3901 D Stri,ctMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:00.884  3901  3901 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.884  3901  3901 D StrictMode: 	,at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.884  3901  3901 D StrictMode: ,	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method),
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 18:48:00.884  3901  3901 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263),
08-31 18:48:00.884  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 18:48:00.884  3901  3901 D StrictMode: ,	at java.io.File.exists(File.java:361)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
,08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.884  3901  3901 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174),
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
,08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.884  3901  3901 D StrictMode: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(Ac,tivityThread.java:5417)
08-31 18:48:00.884  3901  3901 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:00.884  3901  3901 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.io.File.lastModified(File.java:569)
,08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 18:48:00.884  3901  3901 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,08-31 18:48:00.884  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:00.884  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 18:48:00.928   872  2284 I ActivityManager: Start proc 3933:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 18:48:00.929   872  2284 I ActivityManager: Killing 3563:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-31 18:48:00.976  3809  3809 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 18:48:00.985  2713  2765 D bt_stack_manager: event_shut_down_stack finished.
,08-31 18:48:00.985  2713  2763 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 18:48:00.988  3933  3933 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 18:48:00.990  2713  2713 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 18:48:00.990  2713  2763 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 18:48:00.991  2713  2713 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 18:48:00.991  2713  2713 D BtGatt.GattService: stop()
,08-31 18:48:00.991  2713  2713 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 18:48:00.993  2713  2713 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:00.993  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:00.993  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 18:48:00.993  2713  2713 V BluetoothAdapterState: isBleTurningOff()=true
,08-31 18:48:00.994  2713  2763 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 18:48:00.994  2713  2763 D BluetoothAdapterProperties: Setting state to 10
,08-31 18:48:00.994  2713  2763 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 18:48:00.996  2713  2763 I BluetoothAdapterState: Entering OffState
08-31 18:48:00.996   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 18:48:01.005  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 18:48:01.006  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 18:48:01.006  2713  2713 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 18:48:01.006  2713  2765 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 18:48:01.010  2713  2765 D bt_stack_manager: event_clean_up_stack finished.
,08-31 18:48:01.020  2713  2713 I art     : System.exit called, status: 0
,08-31 18:48:01.020  2713  2713 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 18:48:01.057  3933  3933 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 18:48:01.096  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 18:48:01.111   872  2288 I ActivityManager: Process com.android.bluetooth (pid 2713) has died
,08-31 18:48:01.128  3901  3926 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 18:48:01.141   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efe638c:true
,08-31 18:48:01.143   872  1384 I ActivityManager: Start proc 3961:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-31 18:48:01.144  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-31 18:48:01.221  3961  3961 D AdapterServiceConfig: Adding HeadsetService
,08-31 18:48:01.221  3961  3961 D AdapterServiceConfig: Adding A2dpService
08-31 18:48:01.221  3961  3961 D AdapterServiceConfig: Adding HidService
08-31 18:48:01.221  3961  3961 D AdapterServiceConfig: Adding HealthService
08-31 18:48:01.222  3961  3961 D AdapterServiceConfig: Adding PanService
,08-31 18:48:01.222  3961  3961 D AdapterServiceConfig: Adding GattService
08-31 18:48:01.222  3961  3961 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 18:48:01.232   872  1909 I ActivityManager: Killing 2788:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 18:48:01.272  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:48:01.289  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 18:48:01.297  1718  1718 D SystemUpdateService: onCreate
,08-31 18:48:01.305  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 18:48:01.309  1718  3973 I SystemUpdateService: active receiver: enabled
,08-31 18:48:01.314  1718  3973 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 18:48:01.317  1718  3973 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 18:48:01.317  1718  3973 I SystemUpdateService: now status is 0 (complete)
,08-31 18:48:01.317  1718  3973 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 18:48:01.317  1718  3973 I SystemUpdateService: file has been verified
,08-31 18:48:01.318  1718  3973 I SystemUpdateService: OTA package size = 12249756
,08-31 18:48:01.326  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 18:48:01.326  1718  3973 I SystemUpdateService: showing system update notification
,08-31 18:48:01.331  1718  2458 I iu.UploadsManager: num queued entries: 0
,08-31 18:48:01.333  1718  2458 I iu.UploadsManager: num updated entries: 0
,08-31 18:48:01.336  1718  2458 I iu.SyncManager: NEXT; no task
,08-31 18:48:01.348  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 18:48:01.351  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 18:48:01.352  1718  1718 D SystemUpdateService: onDestroy
,08-31 18:48:01.380   872  1908 I ActivityManager: Start proc 3975:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 18:48:01.416  3975  3975 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 18:48:01.419  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:01.424  3975  3975 D SprintDMHelper: simOperator: 
08-31 18:48:01.424  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 18:48:01.438   872  1694 I ActivityManager: Start proc 3987:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 18:48:01.438   872  1694 I ActivityManager: Killing 3500:android.process.acore/u0a5 (adj 15): empty #17
,08-31 18:48:01.569   872  2288 I ActivityManager: Start proc 4002:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 18:48:01.575   872  1909 I ActivityManager: Killing 3662:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 18:48:01.641  4002  4002 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 18:48:01.700  4002  4002 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 18:48:01.700  4002  4002 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 18:48:01.700  4002  4002 I GAv4    :   adb logcat -s GAv4
,08-31 18:48:01.724  4002  4002 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 18:48:01.731  4002  4002 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 18:48:01.760  4002  4019 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 18:48:01.870  4002  4002 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 18:48:01.908  4002  4002 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 18:48:01.925  4002  4002 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 6197-6208)
08-31 18:48:01.925  4002  4002 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 18:48:01.935  4002  4002 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {456eada}
08-31 18:48:01.935  4002  4002 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 18:48:01.935  4002  4002 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 18:48:01.944  4002  4002 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 18:48:01.946  4002  4002 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 18:48:01.967  4002  4002 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 18:48:01.983  4002  4002 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 18:48:01.983  4002  4002 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 18:48:01.983  4002  4002 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 18:48:01.983  4002  4002 I Adreno  : Build Date                       : 10/20/15
08-31 18:48:01.983  4002  4002 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 18:48:01.983  4002  4002 I Adreno  : Local Branch                     : M14
08-31 18:48:01.983  4002  4002 I Adreno  : Remote Branch                    : 
08-31 18:48:01.983  4002  4002 I Adreno  : Remote Branch                    : 
08-31 18:48:01.983  4002  4002 I Adreno  : Reconstruct Branch               : 
,08-31 18:48:02.048  4002  4002 I NSApplication: Starting up...
,08-31 18:48:02.034  4002  4048 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 18:48:02.075   872  2289 I ActivityManager: Start proc 4053:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 18:48:02.076   872  2289 I ActivityManager: Killing 3677:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 18:48:02.146  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 18:48:02.334   872   882 I ActivityManager: Killing 3459:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 18:48:03.510   872   882 D WifiService: setWifiEnabled: true pid=3809, uid=10000
,08-31 18:48:03.510   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:48:03.521   872  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-31 18:48:03.529  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:03.529  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:03.530  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:03.530  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:03.537  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:03.538  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:48:03.538  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:03.538  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:03.548   872  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-31 18:48:03.550   872  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 18:48:03.550   872  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 18:48:03.551   872  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 18:48:03.551   872  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 18:48:03.552   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 18:48:03.552   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 18:48:03.571   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 18:48:03.574   372   870 D CommandListener: Setting iface cfg
,08-31 18:48:03.575   872  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.12 rxSuccessRate=13.38 delta 1000 -> 994
,08-31 18:48:03.575   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,08-31 18:48:03.575   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 18:48:03.579   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-31 18:48:03.579   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 18:48:03.585   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-31 18:48:03.586   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 18:48:03.593   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 18:48:03.646   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 18:48:03.647  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 18:48:04.065  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 18:48:04.109  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 18:48:04.113  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 18:48:04.120   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 18:48:04.134   872  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 18:48:04.134   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:48:04.134   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 18:48:04.154   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 18:48:04.164   372   870 D CommandListener: Setting iface cfg
,08-31 18:48:04.165   872  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-31 18:48:04.177   872  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 18:48:04.178   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 18:48:04.196   872  4076 D DhcpClient: Receive thread started
,08-31 18:48:04.277   872  1308 E native  : do suspend false
,08-31 18:48:04.298   872  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 18:48:04.311   872  4076 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-31 18:48:04.312   872  1880 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-31 18:48:04.318   872  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 18:48:04.330   872  4076 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 18:48:04.331   872  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 18:48:04.338   372   870 D CommandListener: Setting iface cfg
,08-31 18:48:04.352   872  1880 D DhcpClient: Scheduling renewal in 86399s
08-31 18:48:04.352   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 18:48:04.368   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 18:48:04.371   872  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 18:48:04.371   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 18:48:04.372   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 18:48:04.375   872  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 18:48:04.392   872  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 18:48:04.428   872  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 18:48:04.430   872  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 18:48:04.431   872  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 18:48:04.432   872  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 18:48:04.433   872  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 18:48:04.442   872  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 18:48:04.445   872  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-31 18:48:04.446   872  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-31 18:48:04.446   872  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 18:48:04.447   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 18:48:04.447   872  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-31 18:48:04.447   872  1310 D ConnectivityService:    accepting network in place of null
,08-31 18:48:04.449   872  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 18:48:04.463   872  4075 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138746, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 18:48:04.477   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 18:48:04.514   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 18:48:04.519   872  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 18:48:04.520   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:04.522   872  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 18:48:04.523   872   889 D Tethering: MasterInitialState.processMessage what=3
08-31 18:48:04.533   872  4074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:80c::200e
08-31 18:48:04.536  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:04.536  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:48:04.537  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 18:48:04.537  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:04.541  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:04.542  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:48:04.542  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:04.542  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:04.553  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 18:48:04.557  1718  1718 D SystemUpdateService: onCreate
,08-31 18:48:04.560  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 18:48:04.564  1718  4086 I SystemUpdateService: active receiver: enabled
,08-31 18:48:04.570  1718  4086 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 18:48:04.573  1718  4086 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 18:48:04.573  1718  4086 I SystemUpdateService: now status is 0 (complete)
,08-31 18:48:04.573  1718  4086 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 18:48:04.573  1718  4086 I SystemUpdateService: file has been verified
08-31 18:48:04.573  1718  4086 I SystemUpdateService: OTA package size = 12249756
,08-31 18:48:04.577  1718  4086 I SystemUpdateService: showing system update notification
,08-31 18:48:04.586  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 18:48:04.588  1718  2458 I iu.UploadsManager: num queued entries: 0
,08-31 18:48:04.588  1718  2458 I iu.UploadsManager: num updated entries: 0
,08-31 18:48:04.589  1718  2458 I iu.SyncManager: NEXT; no task
,08-31 18:48:04.590  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 18:48:04.592  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 18:48:04.593  1718  4090 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 18:48:04.593  1718  4090 W BaseAppContext: Using Auth Proxy for data requests.
08-31 18:48:04.594  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:04.594  1718  4090 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 18:48:04.598  1718  1718 D SystemUpdateService: onDestroy
,08-31 18:48:04.601  3975  3975 D SprintDMHelper: simOperator: 
,08-31 18:48:04.601  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 18:48:04.601  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:48:04.603  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:48:04.620   872  4074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 16:48:04 GMT], X-Android-Received-Millis=[1472662084619], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472662084581]}
08-31 18:48:04.620   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 18:48:04.621   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-31 18:48:04.621   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 18:48:04.621   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 18:48:04.634  1513  2329 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-31 18:48:04.634  1513  2329 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 18:48:04.634  1513  2329 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:48:04.634  1513  2329 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:48:04.648  1718  4090 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-31 18:48:04.741  2415  4092 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 18:48:05.521   872  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 18:48:06.305   872   882 I ActivityManager: Killing 3701:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 18:48:06.516   872  2283 D WifiService: setWifiEnabled: false pid=3809, uid=10000
,08-31 18:48:06.516   872  2283 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:48:06.530  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 18:48:06.534   872  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 18:48:06.534   872  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-31 18:48:06.535   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 18:48:06.535   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 18:48:06.567   872  1880 D DhcpClient: Clearing IP address
,08-31 18:48:06.567   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-31 18:48:06.571   372   870 D CommandListener: Setting iface cfg
,08-31 18:48:06.574   872  4076 D DhcpClient: Receive thread stopped
,08-31 18:48:06.582  1513  4097 V NativeCrypto: Read error: ssl=0x9a8f9600: I/O error during system call, Connection timed out
,08-31 18:48:06.583  1513  4097 V NativeCrypto: SSL shutdown failed: ssl=0x9a8f9600: I/O error during system call, Broken pipe
08-31 18:48:06.586   872  1908 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-31 18:48:06.586   872  4074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-31 18:48:06.591   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 18:48:06.591   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-31 18:48:06.592   395   395 E Parcel  : Reading a NULL string not supported here.
,08-31 18:48:06.596   872  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-31 18:48:06.596   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 18:48:06.598   872  4074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-31 18:48:06.599   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-31 18:48:06.599   872  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-31 18:48:06.607   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 18:48:06.609  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:06.609  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:06.609  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:06.609  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:06.610  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:06.610  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:48:06.610  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:06.610  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:06.611   872  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 18:48:06.615  1991  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:48:06.635   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 18:48:06.674   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 18:48:06.675   872  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 18:48:06.675   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:06.678   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-31 18:48:06.680  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:06.681  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:06.686  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 18:48:06.689  1718  1718 D SystemUpdateService: onCreate
08-31 18:48:06.691  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 18:48:06.699  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 18:48:06.701  1718  2458 I iu.UploadsManager: num queued entries: 0
,08-31 18:48:06.702  1718  2458 I iu.UploadsManager: num updated entries: 0
08-31 18:48:06.702  1718  2458 I iu.SyncManager: NEXT; no task
,08-31 18:48:06.714  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 18:48:06.716  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 18:48:06.718  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:06.723  3975  3975 D SprintDMHelper: simOperator: 
,08-31 18:48:06.723  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 18:48:06.736  1718  4109 I SystemUpdateService: active receiver: enabled
,08-31 18:48:06.740  2415  4113 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 18:48:06.747  4002  4002 I art     : Waiting for a blocking GC DisableMovingGc
,08-31 18:48:06.750  4002  4002 I art     : Starting a blocking GC DisableMovingGc
,08-31 18:48:06.763   372   870 E Netd    : netlink response contains error (No such file or directory),
08-31 18:48:06.764  1718  4109 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-31 18:48:06.764   872  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 18:48:06.764   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 18:48:06.773  1718  4109 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 18:48:06.773  1718  4109 I SystemUpdateService: now status is 0 (complete)
08-31 18:48:06.773  1718  4109 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 18:48:06.773  1718  4109 I SystemUpdateService: file has been verified
,08-31 18:48:06.773  1718  4109 I SystemUpdateService: OTA package size = 12249756
,08-31 18:48:06.799  1718  4109 I SystemUpdateService: showing system update notification
,08-31 18:48:06.813  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:48:06.813  1718  1718 D SystemUpdateService: onDestroy
,08-31 18:48:06.840  1513  2329 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 18:48:06.840  1513  2329 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 18:48:06.840  1513  2329 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 18:48:06.840  1513  2329 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:48:06.860  3520  3520 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 18:48:06.860  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 18:48:06.860  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-31 18:48:09.566  3961  3961 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 18:48:09.566   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b21fbae:true
,08-31 18:48:09.571  3961  3961 I bt_bluedroid: init
,08-31 18:48:09.572  3961  4116 I BluetoothAdapterState: Entering OffState
,08-31 18:48:09.574  3961  4117 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 18:48:09.574  3961  4117 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 18:48:09.574  3961  4117 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 18:48:09.575  3961  4117 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 18:48:09.575  3961  3961 I bt_bluedroid: get_profile_interface socket
,08-31 18:48:09.579  3961  3961 I bt_bluedroid: get_profile_interface sdp
,08-31 18:48:09.582  3961  3972 I bt_bluedroid: config_hci_snoop_log
,08-31 18:48:09.584   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 18:48:09.584  3961  4120 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 18:48:09.589  3961  4120 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 18:48:09.591  3961  4116 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 18:48:09.591  3961  4116 D BluetoothAdapterProperties: Setting state to 14
,08-31 18:48:09.591  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 18:48:09.593  3961  4116 D BluetoothBondStateMachine: make
,08-31 18:48:09.597  3961  4121 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 18:48:09.600  3961  4116 I BluetoothAdapterState: Entering PendingCommandState
,08-31 18:48:09.601  3961  3961 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 18:48:09.604  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:09.605  3961  3961 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 18:48:09.605  3961  3961 D BtGatt.GattService: Received start request. Starting profile...
,08-31 18:48:09.606  3961  3961 D BtGatt.GattService: start()
08-31 18:48:09.606  3961  3961 I bt_bluedroid: get_profile_interface gatt
,08-31 18:48:09.607  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
08-31 18:48:09.607  3961  3961 D BtGatt.AdvertiseManager: advertise manager created
,08-31 18:48:09.612  3961  3961 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:09.612  3961  3961 V BluetoothAdapterState: isTurningOn()=false
,08-31 18:48:09.612  3961  3961 V BluetoothAdapterState: isBleTurningOn()=true
08-31 18:48:09.613  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:09.613  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 18:48:09.613  3961  4116 I bt_bluedroid: enable
08-31 18:48:09.613  3961  4117 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 18:48:09.614  3961  4117 I bt_hci  : start_up
,08-31 18:48:09.621  3961  4117 I bt_vendor: alloc value 0xb3972189
,08-31 18:48:09.621  3961  4117 I bt_vendor: init
08-31 18:48:09.621  3961  4117 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-31 18:48:09.621  3961  4117 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 18:48:09.727  3961  4117 D bt_hci  : start_up starting async portion
,08-31 18:48:09.728  3961  4124 I bt_hci  : event_finish_startup
,08-31 18:48:09.728  3961  4124 I bt_hci_h4: hal_open
,08-31 18:48:09.728  3961  4124 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 18:48:09.735  3961  4124 I bt_userial_vendor: device fd = 51 open
,08-31 18:48:09.770  3961  4124 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 18:48:09.802  3961  4124 D bt_hwcfg: Chipset BCM4354A2
,08-31 18:48:09.802  3961  4124 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 18:48:09.804  3961  4124 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 18:48:10.484  3961  4124 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 18:48:10.485  3961  4124 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 18:48:10.485  3961  4124 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 18:48:10.602  3961  4124 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 18:48:10.603  3961  4124 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 18:48:10.634  3961  4124 I bt_hwcfg: vendor lib fwcfg completed
,08-31 18:48:10.634  3961  4124 I bt_vendor: firmware callback
,08-31 18:48:10.634  3961  4124 I bt_hci  : firmware_config_callback
,08-31 18:48:10.645  3961  4128 I bt_btu  : btu_task pending for preload complete event
08-31 18:48:10.646  3961  4128 I bt_btu_task: Bluetooth chip preload is complete
08-31 18:48:10.646  3961  4128 I bt_btu  : btu_task received preload complete event
,08-31 18:48:10.655  3961  4128 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 18:48:10.656  3961  4128 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 18:48:10.656  3961  4128 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 18:48:10.656  3961  4128 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 18:48:10.657  3961  4128 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 18:48:10.657  3961  4128 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 18:48:10.657  3961  4128 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 18:48:10.659  3961  4128 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 18:48:10.659  3961  4128 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 18:48:10.660  3961  4128 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 18:48:10.660  3961  4128 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 18:48:10.661  3961  4128 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 18:48:10.662  3961  4128 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 18:48:10.662  3961  4128 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 18:48:10.662  3961  4128 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 18:48:10.797  3961  4128 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38efd9d
,08-31 18:48:10.798  3961  4128 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38efd9d 
,08-31 18:48:10.811  3961  4120 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 18:48:10.813  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 18:48:10.814  3961  4120 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 18:48:10.816  3961  4120 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 18:48:10.819  3961  4120 D BluetoothAdapterProperties: Scan Mode:20
,08-31 18:48:10.820  3961  4120 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 18:48:10.823  3961  4120 D bt_hci  : do_postload posting postload work item
,08-31 18:48:10.825  3961  4124 I bt_hci  : event_postload
,08-31 18:48:10.825  3961  4124 I bt_vendor: sco_config_cb
,08-31 18:48:10.825  3961  4124 I bt_hci  : sco_config_callback postload finished.
,08-31 18:48:10.827  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:10.831  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:10.834  3961  4120 D bt_bte_conf: Device ID record 1 : primary
08-31 18:48:10.834  3961  4120 D bt_bte_conf:   vendorId            = 000f
,08-31 18:48:10.834  3961  4120 D bt_bte_conf:   vendorIdSource      = 0001
08-31 18:48:10.834  3961  4120 D bt_bte_conf:   product             = 1200
08-31 18:48:10.834  3961  4120 D bt_bte_conf:   version             = 1436
,08-31 18:48:10.834  3961  4120 D bt_bte_conf:   clientExecutableURL = 
,08-31 18:48:10.834  3961  4124 I bt_vendor: low_power_mode_cb
,08-31 18:48:10.834  3961  4120 D bt_bte_conf:   serviceDescription  = 
,08-31 18:48:10.834  3961  4120 D bt_bte_conf:   documentationURL    = 
,08-31 18:48:10.835  3961  4120 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 18:48:10.835  3961  4117 D bt_stack_manager: event_start_up_stack finished
,08-31 18:48:10.836  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 18:48:10.836  3961  4116 D BluetoothAdapterProperties: Setting state to 15
08-31 18:48:10.836  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 18:48:10.837  3961  4116 I BluetoothAdapterState: Entering BleOnState
,08-31 18:48:10.839  3961  4116 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 18:48:10.839  3961  4116 D BluetoothAdapterProperties: Setting state to 11
08-31 18:48:10.839  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 18:48:10.845  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
08-31 18:48:10.848  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 18:48:10.849  3961  3961 D HeadsetService: Received start request. Starting profile...
08-31 18:48:10.849  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:10.853  3961  3961 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 18:48:10.854  3961  3961 D HeadsetStateMachine: make
08-31 18:48:10.864  3961  4116 I BluetoothAdapterState: Entering PendingCommandState
08-31 18:48:10.866  3961  3961 D HeadsetStateMachine: max_hf_connections = 1
08-31 18:48:10.866  3961  3961 I bt_bluedroid: get_profile_interface handsfree
08-31 18:48:10.866  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 18:48:10.866  3961  4120 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 18:48:10.870  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:10.871  3961  3961 D A2dpService: Received start request. Starting profile...
08-31 18:48:10.871  3961  3961 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 18:48:10.872  3961  3961 I bt_bluedroid: get_profile_interface avrcp
,08-31 18:48:10.878  3961  3961 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 18:48:10.878  3961  3961 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 18:48:10.878  3961  3961 D A2dpStateMachine: make
,08-31 18:48:10.880  3961  3961 I bt_bluedroid: get_profile_interface a2dp
,08-31 18:48:10.881  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 18:48:10.882  3961  4137 D A2dpStateMachine: Enter Disconnected: -2
,08-31 18:48:10.883  3961  3961 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 18:48:10.884  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:10.885  3961  3961 D HidService: Received start request. Starting profile...
08-31 18:48:10.885  3961  3961 I bt_bluedroid: get_profile_interface hidhost
08-31 18:48:10.885  3961  3961 D HidService: setHidService(): set to: null
08-31 18:48:10.885  3961  4120 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d13e5
,08-31 18:48:10.885  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 18:48:10.886  3961  3961 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 18:48:10.887  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
08-31 18:48:10.887  3961  3961 D HealthService: Received start request. Starting profile...
,08-31 18:48:10.889  3961  3961 I bt_bluedroid: get_profile_interface health
,08-31 18:48:10.890  3961  3961 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 18:48:10.891  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
08-31 18:48:10.891  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:48:10.885  3882  3882 D BluetoothInputDevice: Proxy object connected
,08-31 18:48:10.892  3961  3961 D PanService: Received start request. Starting profile...
08-31 18:48:10.892  3961  3961 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 18:48:10.892  3961  3961 I bt_bluedroid: get_profile_interface pan
08-31 18:48:10.894  3961  4120 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 18:48:10.895  3961  3961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:10.896  3882  3882 D HidProfile: Bluetooth service connected
,08-31 18:48:10.898  3961  3961 D BluetoothMapService: Received start request. Starting profile...
,08-31 18:48:10.898  3961  3961 D BluetoothMapService: start()
08-31 18:48:10.898  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 18:48:10.899  3882  3882 D PanProfile: Bluetooth service connected
,08-31 18:48:10.899  3882  3882 D BluetoothMap: Proxy object connected
08-31 18:48:10.900  3882  3882 D MapProfile: Bluetooth service connected
,08-31 18:48:10.900  3961  3961 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 18:48:10.901  3882  3882 D BluetoothMap: getConnectedDevices(),
,08-31 18:48:10.901  3961  3961 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 18:48:10.901  3961  3961 D BluetoothMapAppObserver: createReceiver()
08-31 18:48:10.902  3882  3882 D BluetoothMap: Bluetooth is Not enabled
08-31 18:48:10.902  3961  3961 D BluetoothMapAppObserver: initObservers()
08-31 18:48:10.902  3961  3961 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 18:48:10.909  3961  3961 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:10.909  3961  3961 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:10.909  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:10.909  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 18:48:10.912  3961  4134 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 18:48:10.912  3961  3961 V BluetoothAdapterState: isTurningOff()=false
08-31 18:48:10.912  3961  3961 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:10.912  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:10.912  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 18:48:10.912  3961  3961 V BluetoothAdapterState: isTurningOff()=false
08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:10.913  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 18:48:10.914  3961  3961 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:10.915  3961  3961 V BluetoothAdapterState: isTurningOn()=true
,08-31 18:48:10.915  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 18:48:10.915  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 18:48:10.915  3961  3961 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:10.916  3961  3961 V BluetoothAdapterState: isTurningOn()=true
,08-31 18:48:10.916  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 18:48:10.916  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 18:48:10.916  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 18:48:10.916  3961  4116 D BluetoothAdapterProperties: ScanMode =  20
08-31 18:48:10.916  3961  4116 D BluetoothAdapterProperties: State =  11
08-31 18:48:10.917  3961  4116 D BluetoothAdapterProperties: Setting state to 12
,08-31 18:48:10.918  3961  4120 D BluetoothAdapterProperties: Scan Mode:21
,08-31 18:48:10.918  3961  4120 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 18:48:10.917  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 18:48:10.919  1373  2060 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 18:48:10.920  3961  4116 I BluetoothAdapterState: Entering OnState,
,08-31 18:48:10.921  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:10.923  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:10.923  3882  3894 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 18:48:10.923  1373  2052 D BluetoothPan: onBluetoothStateChange on: true
,08-31 18:48:10.924  1373  1373 D BluetoothInputDevice: Proxy object connected
,08-31 18:48:10.924  1373  1373 D HidProfile: Bluetooth service connected
,08-31 18:48:10.926  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:10.927  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 18:48:10.927  1373  1373 D PanProfile: Bluetooth service connected
,08-31 18:48:10.927   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 18:48:10.929  3882  3895 D BluetoothPan: onBluetoothStateChange on: true
,08-31 18:48:10.929  3961  3961 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 18:48:10.929  1373  1387 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 18:48:10.930  3961  3961 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:10.930  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:10.931  1373  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:48:10.931  3961  3961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:48:10.933  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:10.932  3882  3894 D BluetoothMap: onBluetoothStateChange: up=true
08-31 18:48:10.933   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:48:10.933  1947  2220 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:48:10.934  1373  2060 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 18:48:10.935  1373  1373 D BluetoothMap: Proxy object connected
08-31 18:48:10.935  1373  1373 D MapProfile: Bluetooth service connected
08-31 18:48:10.935  1373  1373 D BluetoothMap: getConnectedDevices()
08-31 18:48:10.936  3882  3895 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 18:48:10.936  3961  3961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:48:10.937   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:48:10.937   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:48:10.938  3961  3961 D ObexServerSockets: Succeed to create listening sockets 
08-31 18:48:10.938  3961  3961 D ObexServerSockets0: startAccept()
08-31 18:48:10.938  3961  3961 D ObexServerSockets0: prepareForNewConnect()
08-31 18:48:10.939   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 18:48:10.941  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:10.942  3961  3961 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 18:48:10.942  3961  3961 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 18:48:10.943  3961  4143 D ObexServerSockets0: Accepting socket connection...
08-31 18:48:10.943  3961  4144 D ObexServerSockets0: Accepting socket connection...
08-31 18:48:10.943  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:10.943   872   872 D BluetoothA2dp: Proxy object connected
08-31 18:48:10.944  3961  3961 D BluetoothMapService: onReceive
,08-31 18:48:10.944  3961  3961 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:48:10.944  1373  1373 D BluetoothA2dp: Proxy object connected
08-31 18:48:10.944  3961  3961 D BluetoothMapService: STATE_ON
08-31 18:48:10.945  3882  3882 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 18:48:10.948  3882  3882 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 18:48:10.958  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 18:48:10.963  3961  3961 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 18:48:10.964  3961  3961 D ObexServerSockets0: prepareForNewConnect()
,08-31 18:48:10.964  3882  3882 D BluetoothA2dp: Proxy object connected
,08-31 18:48:10.971  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:48:10.975  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-31 18:48:10.990  3882  3882 D BluetoothPbap: Proxy object connected
,08-31 18:48:10.990  3882  3882 D PbapServerProfile: Bluetooth service connected
08-31 18:48:10.990  1373  1373 D BluetoothPbap: Proxy object connected
08-31 18:48:10.990  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-31 18:48:11.005  3961  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 18:48:11.029  3961  4152 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 18:48:11.031  3961  4152 I BtOppRfcommListener: Accept thread started.
,08-31 18:48:11.033   872   889 D BluetoothHeadset: Proxy object connected
,08-31 18:48:11.033   872   872 D BluetoothHeadset: Proxy object connected
08-31 18:48:11.034  1947  1967 D BluetoothHeadset: Proxy object connected
08-31 18:48:11.034  1947  1968 D BluetoothHeadset: Proxy object connected
,08-31 18:48:11.034   872   872 D BluetoothHeadset: Proxy object connected
08-31 18:48:11.034   872   872 D BluetoothHeadset: Proxy object connected
,08-31 18:48:11.035  1373  1388 D BluetoothHeadset: Proxy object connected
,08-31 18:48:11.035  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-31 18:48:11.037   872   889 D BluetoothHeadset: Proxy object connected
,08-31 18:48:11.038   872   889 D BluetoothHeadset: Proxy object connected
,08-31 18:48:11.052  3882  3895 D BluetoothHeadset: Proxy object connected
08-31 18:48:11.054  3882  3882 D HeadsetProfile: Bluetooth service connected
,08-31 18:48:12.451   872  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-31 18:48:12.533  3961  4116 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 18:48:12.533  3961  4116 D BluetoothAdapterProperties: Setting state to 13
08-31 18:48:12.534  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 18:48:12.535  3961  4116 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 18:48:12.537  3961  4116 I BluetoothAdapterState: Entering PendingCommandState
,08-31 18:48:12.544  3961  4120 D BluetoothAdapterProperties: Scan Mode:20,
,08-31 18:48:12.545  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 18:48:12.548  3961  3961 D BluetoothMapService: onReceive
08-31 18:48:12.548  3961  3961 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:48:12.549  3961  3961 D BluetoothMapService: STATE_TURNING_OFF
,08-31 18:48:12.550  3961  3961 D BluetoothMapService: MAP Service closeService in
08-31 18:48:12.550  3961  3961 D BluetoothMapMasInstance0: MAP Service shutdown
,08-31 18:48:12.550  3961  3961 D ObexServerSockets0: shutdown(block = true)
08-31 18:48:12.552  3961  3961 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 18:48:12.552  3961  4143 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 18:48:12.553  3961  3961 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 18:48:12.553  3961  4144 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 18:48:12.553  3961  4131 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-31 18:48:12.555  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:12.555  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:48:12.557  3961  3961 I BtOppRfcommListener: stopping Accept Thread
08-31 18:48:12.559  3961  4152 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:48:12.559  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:12.559  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:48:12.560  3961  4152 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 18:48:12.562  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 18:48:12.565  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:12.566  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:48:12.568  3961  3961 D HeadsetService: Received stop request...Stopping profile...
,08-31 18:48:12.569  3809  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:48:12.569  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:12.571   872   872 D BluetoothHeadset: Proxy object disconnected
,08-31 18:48:12.572  1947  2220 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:12.572  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:12.573  3882  3894 D BluetoothHeadset: Proxy object disconnected
,08-31 18:48:12.573   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:12.573   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 18:48:12.574  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:12.574  3961  3961 D A2dpService: Received stop request...Stopping profile...
08-31 18:48:12.575  3961  4137 D A2dpStateMachine: Exit Disconnected: -1
08-31 18:48:12.576  1373  1388 D BluetoothHeadset: Proxy object disconnected
,08-31 18:48:12.576   872   872 D BluetoothA2dp: Proxy object disconnected
08-31 18:48:12.577  3882  3882 D DockEventReceiver: finishStartingService: stopping service
08-31 18:48:12.577  3961  3961 D HidService: Received stop request...Stopping profile...
,08-31 18:48:12.577  3961  3961 D HidService: Stopping Bluetooth HidService
08-31 18:48:12.579  3882  3882 D HeadsetProfile: Bluetooth service disconnected
,08-31 18:48:12.581  3882  3882 D BluetoothA2dp: Proxy object disconnected
,08-31 18:48:12.582  3961  3961 D HealthService: Received stop request...Stopping profile...
08-31 18:48:12.582  3882  3882 D BluetoothInputDevice: Proxy object disconnected
08-31 18:48:12.582  3882  3882 D HidProfile: Bluetooth service disconnected
,08-31 18:48:12.584  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-31 18:48:12.585  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-31 18:48:12.585  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-31 18:48:12.585  1373  1373 D HidProfile: Bluetooth service disconnected
08-31 18:48:12.586  3961  3961 D PanService: Received stop request...Stopping profile...
08-31 18:48:12.586  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:48:12.587  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 18:48:12.587  1373  1373 D PanProfile: Bluetooth service disconnected
08-31 18:48:12.588  3961  3961 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:12.588  3961  3961 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:12.588  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:12.588  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:12.590  3882  3882 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 18:48:12.590  3882  3882 D PanProfile: Bluetooth service disconnected
08-31 18:48:12.590  3961  3961 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 18:48:12.590  3961  3961 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
,08-31 18:48:12.590  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-31 18:48:12.590  3961  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:12.590  3961  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 18:48:12.590  3961  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 18:48:12.591  3961  4120 E bt_btif : btif_hf_upstreams_evt: Invalid index 30574
,08-31 18:48:12.591  3961  3961 D BluetoothMapService: Received stop request...Stopping profile...
08-31 18:48:12.592  3961  3961 D BluetoothMapService: stop()
08-31 18:48:12.592  3961  3961 D BluetoothMapAppObserver: deinitObservers()
08-31 18:48:12.592  3961  3961 D BluetoothMapAppObserver: removeReceiver()
,08-31 18:48:12.593  1373  1373 D BluetoothMap: Proxy object disconnected
08-31 18:48:12.593  1373  1373 D MapProfile: Bluetooth service disconnected
08-31 18:48:12.594  3961  3961 V BluetoothAdapterState: isTurningOff()=true
,08-31 18:48:12.594  3961  3961 V BluetoothAdapterState: isTurningOn()=false
,08-31 18:48:12.594  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:12.594  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:12.595  3882  3882 D BluetoothMap: Proxy object disconnected
08-31 18:48:12.595  3882  3882 D MapProfile: Bluetooth service disconnected
,08-31 18:48:12.595  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 18:48:12.595  3961  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:12.596  3961  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:12.596  3961  4128 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 18:48:12.596  3961  4128 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:48:12.596  3961  4128 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:48:12.596  3961  4128 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:48:12.596  3961  3961 V BluetoothAdapterState: isTurningOff()=true
,08-31 18:48:12.597  3961  3961 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:12.597  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:12.597  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:12.597  3961  3961 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 18:48:12.597  3961  3961 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 18:48:12.598  3961  3961 V BluetoothAdapterState: isTurningOff()=true
,08-31 18:48:12.598  3961  3961 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:12.598  3961  4120 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 18:48:12.598  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:12.598  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:12.598  3961  3961 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 18:48:12.598  3961  4120 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-31 18:48:12.599  3961  3961 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 18:48:12.602  3961  3961 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:12.602  3961  3961 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:12.602  1373  1373 D BluetoothPbap: Proxy object disconnected
,08-31 18:48:12.602  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:12.602  1373  1373 D PbapServerProfile: Bluetooth service disconnected
08-31 18:48:12.602  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:12.602  3882  3882 D BluetoothPbap: Proxy object disconnected
08-31 18:48:12.602  3882  3882 D PbapServerProfile: Bluetooth service disconnected
08-31 18:48:12.602  3961  3961 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 18:48:12.602  3961  3961 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 18:48:12.605  3961  3961 D BluetoothMapService: MAP Service closeService in,
08-31 18:48:12.605  3961  3961 V BluetoothAdapterState: isTurningOff()=true
08-31 18:48:12.605  3961  3961 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:12.605  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 18:48:12.605  3961  3961 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:12.606  3961  3961 D BluetoothMapService: cleanup()
08-31 18:48:12.606  3961  3961 D BluetoothMapService: MAP Service closeService in
08-31 18:48:12.606  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-31 18:48:12.607  3961  4116 D BluetoothAdapterProperties: Setting state to 15
08-31 18:48:12.607  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 18:48:12.608  1373  2052 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 18:48:12.608  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 18:48:12.608  3961  4116 I BluetoothAdapterState: Entering BleOnState
08-31 18:48:12.609  3882  3895 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 18:48:12.611  1373  1388 D BluetoothPan: onBluetoothStateChange on: false
08-31 18:48:12.612   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 18:48:12.612  3882  3894 D BluetoothPan: onBluetoothStateChange on: false
,08-31 18:48:12.613  1373  2060 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 18:48:12.614  1373  2052 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 18:48:12.614  3882  3895 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 18:48:12.615  3882  3894 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 18:48:12.615  3882  3895 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 18:48:12.616   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 18:48:12.616  1947  1967 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:12.617  1373  1387 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 18:48:12.617  3882  3894 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 18:48:12.618   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:48:12.618   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 18:48:12.618  3961  4116 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 18:48:12.618  3961  4116 D BluetoothAdapterProperties: Setting state to 16
,08-31 18:48:12.618  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-31 18:48:12.619  3961  4116 D BluetoothAdapterProperties: onBleDisable
08-31 18:48:12.620  3961  4116 I BluetoothAdapterState: Entering PendingCommandState
,08-31 18:48:12.620  3961  4117 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 18:48:12.621  3961  4128 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 18:48:12.621  3961  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 18:48:12.622  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:12.625  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:12.625  3961  4120 D BluetoothAdapterProperties: Scan Mode:20
,08-31 18:48:12.627  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:12.628  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:12.629  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 18:48:12.633  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:48:12.633  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,08-31 18:48:12.822  3961  4120 I bt_hci  : shut_down
,08-31 18:48:12.823  3961  4124 D bt_hwcfg: hw_epilog_process
,08-31 18:48:12.826  3961  4124 I bt_vendor: low_power_mode_cb
,08-31 18:48:12.852  3961  4124 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 18:48:12.852  3961  4124 I bt_vendor: epilog_cb
,08-31 18:48:12.852  3961  4124 I bt_hci  : epilog_finished_callback
,08-31 18:48:12.863  3961  4120 I bt_hci_h4: hal_close
,08-31 18:48:12.864  3961  4120 I bt_userial_vendor: device fd = 51 close
,08-31 18:48:12.984  3961  4117 D bt_stack_manager: event_shut_down_stack finished.
,08-31 18:48:12.985  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 18:48:12.991  3961  4116 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 18:48:12.991  3961  3961 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 18:48:12.993  3961  3961 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 18:48:12.993  3961  3961 D BtGatt.GattService: stop()
08-31 18:48:12.993  3961  3961 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 18:48:12.998  3961  3961 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:12.998  3961  3961 V BluetoothAdapterState: isTurningOn()=false
,08-31 18:48:12.999  3961  3961 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 18:48:12.999  3961  3961 V BluetoothAdapterState: isBleTurningOff()=true
,08-31 18:48:13.000  3961  4116 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 18:48:13.001  3961  4116 D BluetoothAdapterProperties: Setting state to 10
08-31 18:48:13.001  3961  4116 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 18:48:13.003  3961  4116 I BluetoothAdapterState: Entering OffState
,08-31 18:48:13.005   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 18:48:13.035  3961  3961 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 18:48:13.036  3961  3961 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 18:48:13.036  3961  4117 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 18:48:13.045  3961  4117 D bt_stack_manager: event_clean_up_stack finished.
,08-31 18:48:13.045  3961  3961 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 18:48:13.052  3961  3961 I art     : System.exit called, status: 0
,08-31 18:48:13.053  3961  3961 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 18:48:13.133   872   882 I ActivityManager: Process com.android.bluetooth (pid 3961) has died
,08-31 18:48:15.529  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:15.530  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:18.537  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:18.538  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f6bbf6 added. We now have 6 listener(s)
,08-31 18:48:18.538  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:18.542  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:18.543  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4972bf7 added. We now have 7 listener(s)
08-31 18:48:18.543  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:18.545  3809  3859 I System.out: IsBluetoothEnabled
,08-31 18:48:18.554  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:18.582   872   889 I ActivityManager: Start proc 4163:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 18:48:18.684   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-31 18:48:18.704  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-31 18:48:18.710   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 18:48:18.710   872   892 I Adreno  : Build Date                       : 10/20/15
08-31 18:48:18.710   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 18:48:18.710   872   892 I Adreno  : Local Branch                     : M14
08-31 18:48:18.710   872   892 I Adreno  : Remote Branch                    : 
08-31 18:48:18.710   872   892 I Adreno  : Remote Branch                    : 
08-31 18:48:18.710   872   892 I Adreno  : Reconstruct Branch               : 
,08-31 18:48:18.722  4163  4163 D AdapterServiceConfig: Adding HeadsetService
,08-31 18:48:18.722  4163  4163 D AdapterServiceConfig: Adding A2dpService
,08-31 18:48:18.722  4163  4163 D AdapterServiceConfig: Adding HidService
,08-31 18:48:18.722  4163  4163 D AdapterServiceConfig: Adding HealthService
,08-31 18:48:18.723  4163  4163 D AdapterServiceConfig: Adding PanService
,08-31 18:48:18.723  4163  4163 D AdapterServiceConfig: Adding GattService
,08-31 18:48:18.723  4163  4163 D AdapterServiceConfig: Adding BluetoothMapService,
,08-31 18:48:18.738  4163  4163 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 18:48:18.739   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d96bcb3:true
,08-31 18:48:18.745  4163  4175 I BluetoothAdapterState: Entering OffState
,08-31 18:48:18.745  4163  4163 I bt_bluedroid: init
,08-31 18:48:18.748   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (405 us)
,08-31 18:48:18.749  4163  4176 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 18:48:18.749  4163  4176 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 18:48:18.749  4163  4176 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 18:48:18.749  4163  4176 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 18:48:18.750  4163  4163 I bt_bluedroid: get_profile_interface socket
08-31 18:48:18.752  4163  4163 I bt_bluedroid: get_profile_interface sdp
,08-31 18:48:18.757  4163  4179 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 18:48:18.758  4163  4179 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 18:48:18.760  4163  4174 I bt_bluedroid: config_hci_snoop_log
,08-31 18:48:18.763   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 18:48:18.768  4163  4175 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 18:48:18.769  4163  4175 D BluetoothAdapterProperties: Setting state to 14
,08-31 18:48:18.769  4163  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 18:48:18.770  4163  4175 D BluetoothBondStateMachine: make
,08-31 18:48:18.774  4163  4180 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 18:48:18.777  4163  4175 I BluetoothAdapterState: Entering PendingCommandState
,08-31 18:48:18.778  4163  4163 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 18:48:18.781  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:18.781  4163  4163 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 18:48:18.782  4163  4163 D BtGatt.GattService: Received start request. Starting profile...
08-31 18:48:18.782  4163  4163 D BtGatt.GattService: start()
08-31 18:48:18.782  4163  4163 I bt_bluedroid: get_profile_interface gatt
08-31 18:48:18.783  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:18.783  4163  4163 D BtGatt.AdvertiseManager: advertise manager created
,08-31 18:48:18.789  4163  4163 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:18.789  4163  4163 V BluetoothAdapterState: isTurningOn()=false
08-31 18:48:18.789  4163  4163 V BluetoothAdapterState: isBleTurningOn()=true
08-31 18:48:18.789  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:18.790  4163  4175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 18:48:18.790  4163  4175 I bt_bluedroid: enable
08-31 18:48:18.790  4163  4176 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 18:48:18.790  4163  4176 I bt_hci  : start_up
,08-31 18:48:18.797  4163  4176 I bt_vendor: alloc value 0xb39c3189
,08-31 18:48:18.797  4163  4176 I bt_vendor: init
08-31 18:48:18.797  4163  4176 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 18:48:18.797  4163  4176 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 18:48:18.903  4163  4176 D bt_hci  : start_up starting async portion
,08-31 18:48:18.904  4163  4184 I bt_hci  : event_finish_startup
,08-31 18:48:18.904  4163  4184 I bt_hci_h4: hal_open
08-31 18:48:18.904  4163  4184 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 18:48:18.912  4163  4184 I bt_userial_vendor: device fd = 51 open
,08-31 18:48:18.946  4163  4184 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 18:48:18.978  4163  4184 D bt_hwcfg: Chipset BCM4354A2
,08-31 18:48:18.979  4163  4184 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 18:48:18.979  4163  4184 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 18:48:19.442  3809  3809 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 18:48:19.443  3809  3809 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 18:48:19.489   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-31 18:48:19.494  3809  3809 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ec0810c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bcd2a64, 16908290=android.view.AbsSavedState$1@bcd2a64}, android:focusedViewId=100}]}]
08-31 18:48:19.495  3809  3809 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-31 18:48:19.496  3809  3809 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 18:48:19.497  3809  3809 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 18:48:19.500   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-31 18:48:19.506   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-31 18:48:19.506   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-31 18:48:19.506   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-31 18:48:19.524   872   881 I art     : Background partial concurrent mark sweep GC freed 20728(1716KB) AllocSpace objects, 13(448KB) LOS objects, 33% free, 29MB/43MB, paused 2.518ms total 122.079ms
,08-31 18:48:19.696  4163  4184 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 18:48:19.696  4163  4184 D bt_hwcfg: Settlement delay -- 100 ms
08-31 18:48:19.697  4163  4184 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 18:48:19.739   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-31 18:48:19.742   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-31 18:48:19.743   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-31 18:48:19.750   872   892 I DreamManagerService: Entering dreamland.
,08-31 18:48:19.751   872   892 I PowerManagerService: Dozing...
,08-31 18:48:19.753   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-31 18:48:19.812  4163  4184 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 18:48:19.813  4163  4184 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 18:48:19.820   376  1488 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-31 18:48:19.820   376  1488 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-31 18:48:19.833   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 18:48:19.836  1939  4187 D NfcService: Discovery configuration equal, not updating.
,08-31 18:48:19.844   872  1308 E native  : do suspend false
,08-31 18:48:19.844  4163  4184 I bt_hwcfg: vendor lib fwcfg completed
08-31 18:48:19.844  4163  4184 I bt_vendor: firmware callback
08-31 18:48:19.844  4163  4184 I bt_hci  : firmware_config_callback
,08-31 18:48:19.851  4163  4189 I bt_btu  : btu_task pending for preload complete event
,08-31 18:48:19.851  4163  4189 I bt_btu_task: Bluetooth chip preload is complete
,08-31 18:48:19.851  4163  4189 I bt_btu  : btu_task received preload complete event
,08-31 18:48:19.858  4163  4189 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 18:48:19.859  4163  4189 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-31 18:48:19.859  4163  4189 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 18:48:19.860  4163  4189 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 18:48:19.860  4163  4189 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 18:48:19.860  4163  4189 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 18:48:19.860  4163  4189 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 18:48:19.860  4163  4189 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 18:48:19.861  4163  4189 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 18:48:19.862   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 18:48:19.865   872  1308 E native  : do suspend true
,08-31 18:48:19.962   376  1486 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-31 18:48:19.963   376  1486 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-31 18:48:19.995  4163  4189 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3940d9d
,08-31 18:48:19.995  4163  4189 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3940d9d 
,08-31 18:48:20.007  4163  4179 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 18:48:20.010  4163  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 18:48:20.011  4163  4179 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 18:48:20.018  4163  4179 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 18:48:20.022  4163  4179 D BluetoothAdapterProperties: Scan Mode:20
,08-31 18:48:20.022  4163  4179 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 18:48:20.022  4163  4179 D bt_hci  : do_postload posting postload work item
08-31 18:48:20.022  4163  4184 I bt_hci  : event_postload
08-31 18:48:20.023  4163  4184 I bt_vendor: sco_config_cb
,08-31 18:48:20.023  4163  4184 I bt_hci  : sco_config_callback postload finished.
08-31 18:48:20.024  4163  4179 D bt_bte_conf: Device ID record 1 : primary
08-31 18:48:20.024  4163  4179 D bt_bte_conf:   vendorId            = 000f
08-31 18:48:20.024  4163  4179 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 18:48:20.024  4163  4179 D bt_bte_conf:   product             = 1200
,08-31 18:48:20.024  4163  4179 D bt_bte_conf:   version             = 1436
08-31 18:48:20.024  4163  4179 D bt_bte_conf:   clientExecutableURL = 
,08-31 18:48:20.024  4163  4179 D bt_bte_conf:   serviceDescription  = 
08-31 18:48:20.024  4163  4179 D bt_bte_conf:   documentationURL    = 
,08-31 18:48:20.024  4163  4179 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 18:48:20.024  4163  4176 D bt_stack_manager: event_start_up_stack finished
08-31 18:48:20.025  4163  4175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 18:48:20.025  4163  4175 D BluetoothAdapterProperties: Setting state to 15
,08-31 18:48:20.025  4163  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 18:48:20.025  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:20.026  4163  4175 I BluetoothAdapterState: Entering BleOnState
08-31 18:48:20.030  4163  4184 I bt_vendor: low_power_mode_cb
08-31 18:48:20.030  4163  4175 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 18:48:20.030  4163  4175 D BluetoothAdapterProperties: Setting state to 11
08-31 18:48:20.031  4163  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 18:48:20.035  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
08-31 18:48:20.036  4163  4163 D HeadsetService: Received start request. Starting profile...
,08-31 18:48:20.039  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:20.041  4163  4163 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 18:48:20.041  4163  4163 D HeadsetStateMachine: make
,08-31 18:48:20.053  4163  4175 I BluetoothAdapterState: Entering PendingCommandState
,08-31 18:48:20.053  4163  4163 D HeadsetStateMachine: max_hf_connections = 1
08-31 18:48:20.053  4163  4163 I bt_bluedroid: get_profile_interface handsfree
,08-31 18:48:20.054  4163  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 18:48:20.054  4163  4179 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-31 18:48:20.058  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:20.058  4163  4163 D A2dpService: Received start request. Starting profile...
,08-31 18:48:20.059  4163  4163 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 18:48:20.059  4163  4163 I bt_bluedroid: get_profile_interface avrcp
,08-31 18:48:20.064  4163  4163 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 18:48:20.065  4163  4163 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 18:48:20.065  4163  4163 D A2dpStateMachine: make
,08-31 18:48:20.066  4163  4163 I bt_bluedroid: get_profile_interface a2dp
,08-31 18:48:20.067  4163  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 18:48:20.070  4163  4200 D A2dpStateMachine: Enter Disconnected: -2
,08-31 18:48:20.071  4163  4163 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 18:48:20.072  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:20.072  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:48:20.073  4163  4163 D HidService: Received start request. Starting profile...
08-31 18:48:20.073  4163  4163 I bt_bluedroid: get_profile_interface hidhost
08-31 18:48:20.073  4163  4163 D HidService: setHidService(): set to: null
08-31 18:48:20.073  4163  4179 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39223e5
08-31 18:48:20.073  4163  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 18:48:20.073  4163  4163 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 18:48:20.074  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:20.074  4163  4163 D HealthService: Received start request. Starting profile...
,08-31 18:48:20.076  4163  4163 I bt_bluedroid: get_profile_interface health
,08-31 18:48:20.077  4163  4163 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 18:48:20.077  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:20.079  4163  4163 D PanService: Received start request. Starting profile...
,08-31 18:48:20.079  4163  4163 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 18:48:20.079  4163  4163 I bt_bluedroid: get_profile_interface pan
08-31 18:48:20.079  4163  4179 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 18:48:20.082  4163  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
08-31 18:48:20.082  4163  4163 D BluetoothMapService: Received start request. Starting profile...
08-31 18:48:20.082  4163  4163 D BluetoothMapService: start()
,08-31 18:48:20.084  4163  4163 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 18:48:20.085  4163  4163 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 18:48:20.085  4163  4163 D BluetoothMapAppObserver: createReceiver()
,08-31 18:48:20.086  4163  4163 D BluetoothMapAppObserver: initObservers()
,08-31 18:48:20.086  4163  4163 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 18:48:20.092  4163  4163 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:20.092  4163  4163 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:20.092  4163  4163 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:20.092  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:20.092  4163  4197 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isTurningOff()=false
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isTurningOff()=false
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:20.094  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isTurningOff()=false
,08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isTurningOff()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isTurningOff()=false
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isTurningOn()=true
08-31 18:48:20.095  4163  4163 V BluetoothAdapterState: isBleTurningOn()=false
08-31 18:48:20.096  4163  4163 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 18:48:20.099  4163  4175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 18:48:20.099  4163  4175 D BluetoothAdapterProperties: ScanMode =  20
08-31 18:48:20.099  4163  4175 D BluetoothAdapterProperties: State =  11
08-31 18:48:20.100  4163  4175 D BluetoothAdapterProperties: Setting state to 12
08-31 18:48:20.100  4163  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 18:48:20.101  1373  1388 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 18:48:20.101  4163  4175 I BluetoothAdapterState: Entering OnState
,08-31 18:48:20.101  4163  4179 D BluetoothAdapterProperties: Scan Mode:21
08-31 18:48:20.102  4163  4179 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 18:48:20.103  1373  2052 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:20.105  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:20.106  3882  3895 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 18:48:20.106  1373  1373 D BluetoothInputDevice: Proxy object connected
08-31 18:48:20.107  1373  1373 D HidProfile: Bluetooth service connected
,08-31 18:48:20.108  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:20.109  3882  3882 D BluetoothInputDevice: Proxy object connected
,08-31 18:48:20.109  1373  1387 D BluetoothPan: onBluetoothStateChange on: true
08-31 18:48:20.109  3882  3882 D HidProfile: Bluetooth service connected
08-31 18:48:20.111   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 18:48:20.111  3882  3894 D BluetoothPan: onBluetoothStateChange on: true
,08-31 18:48:20.112  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 18:48:20.112  1373  1373 D PanProfile: Bluetooth service connected
08-31 18:48:20.112  4163  4163 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 18:48:20.113  1373  2052 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 18:48:20.113  4163  4163 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 18:48:20.114  4163  4163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:48:20.115  1373  2060 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:48:20.116  3882  4205 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 18:48:20.116  4163  4163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:48:20.118  4163  4163 D ObexServerSockets: Succeed to create listening sockets 
08-31 18:48:20.118  4163  4163 D ObexServerSockets0: startAccept()
08-31 18:48:20.118  4163  4163 D ObexServerSockets0: prepareForNewConnect()
,08-31 18:48:20.118  3882  3895 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:48:20.119  3882  3894 D BluetoothMap: onBluetoothStateChange: up=true
08-31 18:48:20.120  4163  4163 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 18:48:20.120  4163  4163 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 18:48:20.121  4163  4206 D ObexServerSockets0: Accepting socket connection...
,08-31 18:48:20.121  4163  4207 D ObexServerSockets0: Accepting socket connection...
,08-31 18:48:20.121   872   872 D BluetoothA2dp: Proxy object connected
08-31 18:48:20.122  1373  1373 D BluetoothA2dp: Proxy object connected
08-31 18:48:20.122   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:48:20.122  1947  1968 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:48:20.123  1373  1388 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 18:48:20.125  1373  1373 D BluetoothMap: Proxy object connected
,08-31 18:48:20.125  1373  1373 D MapProfile: Bluetooth service connected
08-31 18:48:20.125  1373  1373 D BluetoothMap: getConnectedDevices()
08-31 18:48:20.126  3882  4205 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 18:48:20.127   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:48:20.127   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:48:20.128   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 18:48:20.129  4163  4163 D BluetoothMapService: onReceive
08-31 18:48:20.130  4163  4163 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:48:20.129  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 18:48:20.130  4163  4163 D BluetoothMapService: STATE_ON
,08-31 18:48:20.130  3882  3882 D PanProfile: Bluetooth service connected
08-31 18:48:20.131  3882  3882 D BluetoothA2dp: Proxy object connected
,08-31 18:48:20.131  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:20.133  3882  3882 D BluetoothMap: Proxy object connected
08-31 18:48:20.133  3882  3882 D MapProfile: Bluetooth service connected
08-31 18:48:20.133  3882  3882 D BluetoothMap: getConnectedDevices()
,08-31 18:48:20.138  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 18:48:20.145  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:48:20.145  3882  3882 D DockEventReceiver: finishStartingService: stopping service,
,08-31 18:48:20.155  3882  3882 D BluetoothPbap: Proxy object connected
08-31 18:48:20.155  1373  1373 D BluetoothPbap: Proxy object connected
08-31 18:48:20.155  3882  3882 D PbapServerProfile: Bluetooth service connected
08-31 18:48:20.155  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-31 18:48:20.161  4163  4163 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 18:48:20.161  4163  4163 D ObexServerSockets0: prepareForNewConnect()
,08-31 18:48:20.164  4163  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 18:48:20.177  4163  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 18:48:20.179  4163  4215 I BtOppRfcommListener: Accept thread started.
,08-31 18:48:20.216   872   872 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.217  1947  2220 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.218  3882  3895 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.218  3882  3882 D HeadsetProfile: Bluetooth service connected
,08-31 18:48:20.218   872   872 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.218   872   872 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.219  1373  1388 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.219  3882  4205 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.219  1373  1373 D HeadsetProfile: Bluetooth service connected
08-31 18:48:20.221  3882  3882 D HeadsetProfile: Bluetooth service connected
08-31 18:48:20.222   872   889 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.224  1947  1967 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.227   872   889 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.227   872   889 D BluetoothHeadset: Proxy object connected
,08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:20.575  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:20.582  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:20.586  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:20.586  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69db4cd added. We now have 8 listener(s)
,08-31 18:48:20.587  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:20.592   872  1906 D WifiService: setWifiEnabled: false pid=3809, uid=10000
,08-31 18:48:20.592   872  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:48:20.605  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:20.606   872  2283 D WifiService: setWifiEnabled: true pid=3809, uid=10000
,08-31 18:48:20.606   872  2283 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:48:20.620   872  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:20.636  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:20.643  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:20.661   872  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-31 18:48:20.662   872  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 18:48:20.662   872  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 18:48:20.663   872  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 18:48:20.663   872  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 18:48:20.664   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 18:48:20.664   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 18:48:20.676   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 18:48:20.676   872  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,08-31 18:48:20.676   872  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-31 18:48:20.677   372   870 D CommandListener: Setting iface cfg
08-31 18:48:20.678   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
08-31 18:48:20.678   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 18:48:20.686   872  1308 E native  : do suspend true
,08-31 18:48:20.694   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-31 18:48:20.694   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 18:48:20.700   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 18:48:20.700   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 18:48:20.725   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 18:48:20.783   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 18:48:20.785  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 18:48:21.221  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 18:48:21.262  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 18:48:21.264  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 18:48:21.271   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 18:48:21.289   872  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 18:48:21.290   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:48:21.290   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 18:48:21.323   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 18:48:21.342   372   870 D CommandListener: Setting iface cfg
,08-31 18:48:21.346   872  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 18:48:21.353   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 18:48:21.412   872  4224 D DhcpClient: Receive thread started
,08-31 18:48:21.502   872  1308 E native  : do suspend false
,08-31 18:48:21.522   872  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 18:48:21.539   872  4224 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-31 18:48:21.541   872  1880 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-31 18:48:21.546   872  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 18:48:21.563   872  4224 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 18:48:21.564   872  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 18:48:21.570   372   870 D CommandListener: Setting iface cfg
,08-31 18:48:21.581   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 18:48:21.581   872  1880 D DhcpClient: Scheduling renewal in 86399s
,08-31 18:48:21.584   872  1308 E native  : do suspend true
,08-31 18:48:21.607   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 18:48:21.612   872  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 18:48:21.613   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 18:48:21.619   872  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-31 18:48:21.625   872  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:48:21.638  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:48:21.644  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 18:48:21.649  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 18:48:21.650  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 18:48:21.653  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ec0810c Bundle[{}]
,08-31 18:48:21.654  3809  3859 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 18:48:21.654  3809  3859 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 18:48:21.654  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 18:48:21.655  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 18:48:21.655  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 18:48:21.656  3809  3859 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 18:48:21.661  3809  3859 I System.out: Running OutgoingSocketThread
,08-31 18:48:21.662  3809  4228 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-31 18:48:21.663  3809  4228 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48801
08-31 18:48:21.663  3809  4228 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 18:48:21.676   872  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 18:48:21.677   872  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 18:48:21.679   872  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 18:48:21.681   872  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-31 18:48:21.683   872  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 18:48:21.692   872  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 18:48:21.700   872  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-31 18:48:21.700   872  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-31 18:48:21.701   872  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 18:48:21.701   872  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-31 18:48:21.701   872  1310 D ConnectivityService:    accepting network in place of null
,08-31 18:48:21.702   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 18:48:21.702   872  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 18:48:21.717   872  4223 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156000, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 18:48:21.739   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 18:48:21.774   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 18:48:21.783   872  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-31 18:48:21.785   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:21.792   872  4222 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.206,2a00:1450:400d:807::200e
,08-31 18:48:21.792   872  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-31 18:48:21.794   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:21.813  3809  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:21.816  3809  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:21.822  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 18:48:21.828  1718  1718 D SystemUpdateService: onCreate
,08-31 18:48:21.832  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 18:48:21.844  1718  4235 I SystemUpdateService: active receiver: enabled
,08-31 18:48:21.852  1718  4235 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 18:48:21.853  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 18:48:21.856  1718  2458 I iu.UploadsManager: num queued entries: 0
,08-31 18:48:21.861  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 18:48:21.863  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 18:48:21.864  1718  4235 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 18:48:21.865  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:48:21.868   872  4222 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 16:48:21 GMT], X-Android-Received-Millis=[1472662101867], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472662101841]}
,08-31 18:48:21.868   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 18:48:21.869   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-31 18:48:21.869   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 18:48:21.871   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 18:48:21.874  3975  3975 D SprintDMHelper: simOperator: 
,08-31 18:48:21.874  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 18:48:21.877  1718  4238 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 18:48:21.878  1718  4238 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 18:48:21.886  1718  4238 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 18:48:21.864  1718  4235 I SystemUpdateService: now status is 0 (complete)
,08-31 18:48:21.888  1718  4235 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 18:48:21.888  1718  4235 I SystemUpdateService: file has been verified
,08-31 18:48:21.894  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:48:21.898  1718  4235 I SystemUpdateService: OTA package size = 12249756
08-31 18:48:21.898  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 18:48:21.901  1718  2458 I iu.UploadsManager: num updated entries: 0
,08-31 18:48:21.901  1718  2458 I iu.SyncManager: NEXT; no task
,08-31 18:48:21.916  1718  4235 I SystemUpdateService: showing system update notification
,08-31 18:48:21.934  1718  1718 D SystemUpdateService: onDestroy
,08-31 18:48:21.947  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 18:48:21.947  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 18:48:21.947  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 18:48:21.947  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 18:48:21.963  1718  4238 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-31 18:48:22.000  2415  4241 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 18:48:22.664  3809  3859 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-31 18:48:22.664  3809  3859 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-31 18:48:22.673  3809  3859 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-31 18:48:22.676  3809  3859 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 18:48:22.676  3809  3859 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-31 18:48:22.681  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:48:22.682  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1caa182 added. We now have 2 listener(s)
,08-31 18:48:22.683  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:22.684  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:48:22.684  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 18:48:22.684  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:22.684  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d089093 added. We now have 9 listener(s)
,08-31 18:48:22.684  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:22.685  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:48:22.687  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:22.694  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:22.698  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:22.698  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:22.698  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:48:22.698  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65dd0c9 added. We now have 3 listener(s)
,08-31 18:48:22.701  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 18:48:22.701  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 18:48:22.701  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.702  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:22.702  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@553ce added. We now have 10 listener(s)
08-31 18:48:22.702  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:22.702  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:22.702  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:22.702  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:22.702  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:48:22.702  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:22.702  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.703  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:22.703  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 18:48:22.703  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1caa182 removed from the list
08-31 18:48:22.703  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.703  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d089093 removed from the list
,08-31 18:48:22.707  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:22.707  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:22.707  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.709  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.709  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.710  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.710  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:22.710  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.710  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d089093 not in the list
08-31 18:48:22.710  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.710  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.713  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:22.713  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.713  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.713  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@553ce removed from the list
08-31 18:48:22.713  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:22.714  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.714  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.714  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:22.714  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65dd0c9 removed from the list
08-31 18:48:22.715  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:48:22.715  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121a2ef added. We now have 2 listener(s)
,08-31 18:48:22.716  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:22.716  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 18:48:22.717  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.717  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:22.717  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed161fc added. We now have 9 listener(s)
08-31 18:48:22.717  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:22.717  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:48:22.720  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:22.730  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:22.734  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:22.734  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 18:48:22.734  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:48:22.734  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@626deda added. We now have 3 listener(s),
08-31 18:48:22.736  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:22.736  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-31 18:48:22.736  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.736  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:22.736  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0f7f0b added. We now have 10 listener(s)
08-31 18:48:22.737  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:22.737  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:48:22.737  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 18:48:22.737  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:48:22.737  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:22.737  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:48:22.737  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:22.742  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 18:48:22.742  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 18:48:22.742  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:22.746  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 18:48:22.747  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 18:48:22.747  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 18:48:22.750  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 18:48:22.750  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 18:48:22.751  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 18:48:22.751  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:22.757  4163  4216 D BtGatt.GattService: registerClient() - UUID=a47db2e5-10e7-433a-86ed-42ef5edddc81
,08-31 18:48:22.759  4163  4179 D BtGatt.GattService: onClientRegistered() - UUID=a47db2e5-10e7-433a-86ed-42ef5edddc81, clientIf=5
,08-31 18:48:22.760  3809  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 18:48:22.761  4163  4198 D BtGatt.GattService: start scan with filters
,08-31 18:48:22.765  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 18:48:22.765  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 18:48:22.765  4163  4183 D BtGatt.ScanManager: handling starting scan
08-31 18:48:22.765  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 18:48:22.765  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 18:48:22.768  4163  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@534d6e0
,08-31 18:48:22.769  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 18:48:22.769  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:22.769  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 18:48:22.771  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 18:48:22.772  4163  4179 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 18:48:22.773  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:22.773  4163  4183 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 18:48:22.774  3809  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 18:48:22.774  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:22.774  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 18:48:22.774  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.774  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 18:48:22.774  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 18:48:22.774  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 18:48:22.775  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 18:48:22.775  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 18:48:22.775  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 18:48:22.775  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 18:48:22.776  3809  3859 D BluetoothAdapter: STATE_ON
08-31 18:48:22.777  4163  4173 D BtGatt.GattService: stopScan() - queue size =1
08-31 18:48:22.778  4163  4216 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 18:48:22.778  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 18:48:22.779  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 18:48:22.779  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 18:48:22.779  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 18:48:22.779  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 18:48:22.781  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 18:48:22.781  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 18:48:22.781  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-31 18:48:22.781  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:48:22.781  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-31 18:48:22.781  4163  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 18:48:22.782  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.783  4163  4183 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 18:48:22.783  4163  4183 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 18:48:22.783   872  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-31 18:48:22.783  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:22.783  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 18:48:22.783  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 18:48:22.787  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:22.787  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:22.787  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:48:22.788  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:22.788  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.788  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 18:48:22.788  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 18:48:22.788  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121a2ef removed from the list
08-31 18:48:22.788  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.788  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed161fc removed from the list
,08-31 18:48:22.788  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:48:22.788  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.789  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.790  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.791  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.791  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:22.791  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.791  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed161fc not in the list
,08-31 18:48:22.791  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.791  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.792  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:22.792  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:48:22.792  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.792  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0f7f0b removed from the list
,08-31 18:48:22.793  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:22.793  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.793  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.793  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:22.793  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@626deda removed from the list
,08-31 18:48:22.794  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:48:22.794  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b500e7 added. We now have 2 listener(s)
,08-31 18:48:22.796  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 18:48:22.796  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:48:22.796  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 18:48:22.796  4163  4179 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 18:48:22.796  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:22.796  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:22.796  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501f494 added. We now have 9 listener(s)
,08-31 18:48:22.796  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:22.797  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 18:48:22.799  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:22.804  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:22.805  4163  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 18:48:22.805  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.806  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-31 18:48:22.806  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:22.807  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:48:22.807  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c726f32 added. We now have 3 listener(s)
,08-31 18:48:22.808  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:22.808  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 18:48:22.808  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.809  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:22.809  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d46c483 added. We now have 10 listener(s)
,08-31 18:48:22.809  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:48:22.809  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 18:48:22.810  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 18:48:22.810  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:48:22.810  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 18:48:22.810  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:22.810  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:48:22.812  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:22.813  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 18:48:22.813  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 18:48:22.817  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:22.817  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:48:22.818  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 18:48:22.818  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 18:48:22.822  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 18:48:22.822  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 18:48:22.822  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 18:48:22.823  3809  3859 D BluetoothAdapter: STATE_ON
08-31 18:48:22.823  4163  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 18:48:22.823  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.824  4163  4183 D BtGatt.ScanManager: stopping BLe Batch
08-31 18:48:22.825  4163  4173 D BtGatt.GattService: registerClient() - UUID=cc5d1b56-d0da-48b8-a98b-de0e485ccea3
08-31 18:48:22.826  4163  4179 D BtGatt.GattService: onClientRegistered() - UUID=cc5d1b56-d0da-48b8-a98b-de0e485ccea3, clientIf=5
,08-31 18:48:22.826  3809  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 18:48:22.826  4163  4216 D BtGatt.GattService: start scan with filters
,08-31 18:48:22.828  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 18:48:22.828  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 18:48:22.828  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 18:48:22.829  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 18:48:22.831  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:22.831  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 18:48:22.831  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 18:48:22.833  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 18:48:22.834  4163  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 18:48:22.834  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:22.834  4163  4183 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 18:48:22.836  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 18:48:22.836  3809  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 18:48:22.837  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:22.837  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:22.837  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:48:22.837  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:22.837  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.837  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 18:48:22.837  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:22.837  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b500e7 removed from the list
08-31 18:48:22.837  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.838  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501f494 removed from the list
,08-31 18:48:22.838  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:22.838  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:22.838  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.838  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 18:48:22.838  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.838  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 18:48:22.839  4163  4179 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 18:48:22.839  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.839  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.840  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:22.840  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.840  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501f494 not in the list
08-31 18:48:22.840  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 18:48:22.840  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 18:48:22.840  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 18:48:22.840  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 18:48:22.840  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 18:48:22.841  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:22.841  4163  4183 D BtGatt.ScanManager: handling starting scan
,08-31 18:48:22.841  4163  4174 D BtGatt.GattService: stopScan() - queue size =0
,08-31 18:48:22.842  4163  4173 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 18:48:22.842  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-31 18:48:22.842  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 18:48:22.842  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 18:48:22.842  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 18:48:22.842  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 18:48:22.843  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:22.843  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 18:48:22.843  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 18:48:22.843  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:48:22.843  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.844  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:22.844  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:22.845  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 18:48:22.845  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:48:22.845  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.845  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.845  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d46c483 removed from the list
,08-31 18:48:22.845  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:22.845  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.845  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.845  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 18:48:22.845  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c726f32 removed from the list
,08-31 18:48:22.846  4163  4179 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 18:48:22.846  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.846  4163  4183 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 18:48:22.846  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:48:22.846  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a725df added. We now have 2 listener(s)
08-31 18:48:22.848  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 18:48:22.848  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:48:22.848  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.848  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:22.848  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62f422c added. We now have 9 listener(s)
08-31 18:48:22.848  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:22.849  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:48:22.851  4163  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 18:48:22.851  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:22.851  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:22.851  4163  4183 D BtGatt.ScanManager: Starting BLE batch scan
08-31 18:48:22.851  4163  4183 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:22.854  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:22.856  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:22.856  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:48:22.856  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:48:22.856  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e4b28a added. We now have 3 listener(s)
08-31 18:48:22.858  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:22.858  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 18:48:22.858  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.858  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:22.858  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:48:22.858  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8240fb added. We now have 10 listener(s)
08-31 18:48:22.858  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:22.858  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:48:22.858  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 18:48:22.858  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:48:22.858  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:48:22.858  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 18:48:22.860  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:22.860  4163  4179 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 18:48:22.860  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.861  3809  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 18:48:22.861  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 18:48:22.864  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:48:22.865  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 18:48:22.865  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 18:48:22.865  4163  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 18:48:22.865  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:22.867  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 18:48:22.867  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 18:48:22.868  3809  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 18:48:22.868  3809  3859 D BluetoothAdapter: STATE_ON
,08-31 18:48:22.870  4163  4173 D BtGatt.GattService: registerClient() - UUID=e34901ae-038e-40ca-878d-6fc0bc753388
,08-31 18:48:22.871  4163  4179 D BtGatt.GattService: onClientRegistered() - UUID=e34901ae-038e-40ca-878d-6fc0bc753388, clientIf=5
08-31 18:48:22.871  3809  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 18:48:22.871  4163  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 18:48:22.871  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.871  4163  4183 D BtGatt.ScanManager: stopping BLe Batch
,08-31 18:48:22.872  4163  4174 D BtGatt.GattService: start scan with filters
,08-31 18:48:22.874  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 18:48:22.874  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 18:48:22.874  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 18:48:22.874  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 18:48:22.876  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:22.876  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 18:48:22.877  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 18:48:22.877  4163  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 18:48:22.877  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-31 18:48:22.878  4163  4183 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 18:48:22.878  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 18:48:22.882  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:48:22.882  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:22.882  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:22.882  4163  4179 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 18:48:22.883  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:22.883  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.883  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.883  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 18:48:22.883  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 18:48:22.883  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a725df removed from the list
08-31 18:48:22.883  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.883  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62f422c removed from the list
,08-31 18:48:22.883  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:22.883  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 18:48:22.883  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.883  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 18:48:22.884  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.884  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:22.884  4163  4183 D BtGatt.ScanManager: handling starting scan
,08-31 18:48:22.884  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.884  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:22.884  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.884  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62f422c not in the list
08-31 18:48:22.885  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 18:48:22.885  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 18:48:22.885  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 18:48:22.886  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 18:48:22.886  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 18:48:22.886  3809  3859 D BluetoothAdapter: STATE_ON
08-31 18:48:22.887  4163  4174 D BtGatt.GattService: stopScan() - queue size =1
08-31 18:48:22.887  4163  4198 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 18:48:22.887  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 18:48:22.887  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 18:48:22.887  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 18:48:22.888  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 18:48:22.888  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 18:48:22.888  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:48:22.889  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 18:48:22.889  3809  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 18:48:22.889  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:48:22.889  4163  4179 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 18:48:22.889  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.889  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.889  4163  4183 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
08-31 18:48:22.890  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:22.890  3809  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:48:22.890  3809  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 18:48:22.890  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:22.890  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:48:22.890  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.891  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8240fb removed from the list
08-31 18:48:22.891  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 18:48:22.891  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.891  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.891  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:22.891  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e4b28a removed from the list
,08-31 18:48:22.891  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:48:22.892  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@729f1d7 added. We now have 2 listener(s)
08-31 18:48:22.893  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 18:48:22.893  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:48:22.893  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 18:48:22.893  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:22.893  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d5aac4 added. We now have 9 listener(s)
08-31 18:48:22.894  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-31 18:48:22.894  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:48:22.894  4163  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 18:48:22.895  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.895  4163  4183 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 18:48:22.895  4163  4183 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 18:48:22.897  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:48:22.900  3809  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:48:22.902  3809  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 18:48:22.902  3809  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 18:48:22.902  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:48:22.903  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4108e2 added. We now have 3 listener(s)
,08-31 18:48:22.904  4163  4179 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 18:48:22.904  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.904  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:48:22.905  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 18:48:22.905  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 18:48:22.905  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:48:22.906  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:48:22.906  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c31d473 added. We now have 10 listener(s)
08-31 18:48:22.906  3809  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:48:22.906  3809  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:48:22.906  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:48:22.906  3809  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:48:22.906  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:22.906  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:48:22.906  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.906  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:48:22.906  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:22.906  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@729f1d7 removed from the list
08-31 18:48:22.907  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 18:48:22.907  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d5aac4 removed from the list
08-31 18:48:22.907  3809  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:48:22.907  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.907  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:48:22.907  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:48:22.908  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:48:22.908  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:22.908  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.908  3809  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d5aac4 not in the list
08-31 18:48:22.908  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.908  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.909  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:48:22.909  4163  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 18:48:22.909  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:48:22.909  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.909  3809  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:48:22.909  3809  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c31d473 removed from the list
08-31 18:48:22.909  3809  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:48:22.909  3809  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 18:48:22.909  3809  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:48:22.909  3809  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:48:22.910  3809  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4108e2 removed from the list
,08-31 18:48:22.910  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 18:48:22.910  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 18:48:22.911  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 18:48:22.911  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:48:22.911  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-31 18:48:22.911  3809  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 18:48:22.916  3809  4247 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,08-31 18:48:22.916  4163  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 18:48:22.916  3809  4247 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-31 18:48:22.916  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 18:48:22.916  3809  4247 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 18:48:22.916  4163  4183 D BtGatt.ScanManager: stopping BLe Batch
,08-31 18:48:22.918  3809  4248 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-31 18:48:22.918  3809  4248 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-31 18:48:22.918  3809  4248 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 18:48:22.920  3809  3859 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-31 18:48:22.920  3809  3859 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 18:48:22.920  3809  3859 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 18:48:22.920  3809  3859 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 18:48:22.920  3809  3859 D com.test.thalitest.ThaliTestRunner: Total duration: 22733 ms
,08-31 18:48:22.922  3809  3859 I jxcore-log: *Native tests were executed*
08-31 18:48:22.922  3809  3859 I jxcore-log: 
,08-31 18:48:22.922  3809  3859 I jxcore-log: Total number of executed tests:  80
08-31 18:48:22.922  3809  3859 I jxcore-log: 
08-31 18:48:22.922  3809  3859 I jxcore-log: Number of passed tests:  80
08-31 18:48:22.922  3809  3859 I jxcore-log: 
08-31 18:48:22.922  3809  3859 I jxcore-log: Number of failed tests:  0
08-31 18:48:22.922  3809  3859 I jxcore-log: 
08-31 18:48:22.922  4163  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 18:48:22.922  3809  3859 I jxcore-log: Number of ignored tests:  0
08-31 18:48:22.922  3809  3859 I jxcore-log: 
08-31 18:48:22.922  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.923  4163  4183 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 18:48:22.923  3809  3859 I jxcore-log: Total duration:  22733
08-31 18:48:22.923  3809  3859 I jxcore-log: 
08-31 18:48:22.923  3809  3859 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 18:48:22.923  3809  3859 I jxcore-log: 
,08-31 18:48:22.928  4163  4179 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 18:48:22.928  4163  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 18:48:22.928  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.928  3809  3859 I jxcore-log: 
08-31 18:48:22.931  3809  3809 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 18:48:22.931  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.931  3809  3859 I jxcore-log: 
08-31 18:48:22.932  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.932  3809  3859 I jxcore-log: 
08-31 18:48:22.933  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.933  3809  3859 I jxcore-log: 
08-31 18:48:22.934  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.934  3809  3859 I jxcore-log: 
08-31 18:48:22.935  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.935  3809  3859 I jxcore-log: 
08-31 18:48:22.938  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.938  3809  3859 I jxcore-log: 
,08-31 18:48:22.939  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.939  3809  3859 I jxcore-log: 
,08-31 18:48:22.940  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.940  3809  3859 I jxcore-log: 
,08-31 18:48:22.941  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 18:48:22.941  3809  3859 I jxcore-log: 
,08-31 18:48:22.942  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 18:48:22.942  3809  3859 I jxcore-log: 
,08-31 18:48:22.943  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 18:48:22.943  3809  3859 I jxcore-log: 
,08-31 18:48:22.944  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.944  3809  3859 I jxcore-log: 
08-31 18:48:22.945  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.945  3809  3859 I jxcore-log: 
08-31 18:48:22.945  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.945  3809  3859 I jxcore-log: 
,08-31 18:48:22.946  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.946  3809  3859 I jxcore-log: 
,08-31 18:48:22.947  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.947  3809  3859 I jxcore-log: 
08-31 18:48:22.948  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.948  3809  3859 I jxcore-log: 
08-31 18:48:22.948  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.948  3809  3859 I jxcore-log: 
08-31 18:48:22.949  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.949  3809  3859 I jxcore-log: 
08-31 18:48:22.950  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.950  3809  3859 I jxcore-log: 
,08-31 18:48:22.950  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:48:22.950  3809  3859 I jxcore-log: 
,08-31 18:48:22.951  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 18:48:22.951  3809  3859 I jxcore-log: 
,08-31 18:48:22.952  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 18:48:22.952  3809  3859 I jxcore-log: 
,08-31 18:48:22.953  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.953  3809  3859 I jxcore-log: 
,08-31 18:48:22.953  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.953  3809  3859 I jxcore-log: 
08-31 18:48:22.954  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.954  3809  3859 I jxcore-log: 
08-31 18:48:22.955  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.955  3809  3859 I jxcore-log: 
08-31 18:48:22.955  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.955  3809  3859 I jxcore-log: 
,08-31 18:48:22.956  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:48:22.956  3809  3859 I jxcore-log: 
,08-31 18:48:23.284  3809  3809 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 18:48:23.286  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 18:48:23.286  3809  3859 I jxcore-log: 
,08-31 18:48:23.345  3809  3809 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 18:48:23.347  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 18:48:23.347  3809  3859 I jxcore-log: 
,08-31 18:48:23.391  3809  3809 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 18:48:23.393  3809  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 18:48:23.393  3809  3859 I jxcore-log: 
,08-31 18:48:23.617  4249  4249 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 18:48:23.622  4249  4249 D AndroidRuntime: CheckJNI is OFF
,08-31 18:48:23.664  4249  4249 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 18:48:23.712  4249  4249 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 18:48:23.734  4249  4249 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 18:48:23.747   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-31 18:48:23.748   872   885 I ActivityManager: Killing 3809:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 18:48:23.854   872   895 W PackageSettings: Skipping PackageSetting{efe34ad com.example.hello/10273} due to missing metadata
,08-31 18:48:23.865   872  1909 D GraphicsStats: Buffer count: 2
,08-31 18:48:23.865   872  2283 I WindowState: WIN DEATH: Window{83e6755 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 18:48:23.866   872  1309 D WifiService: Client connection lost with reason: 4
,08-31 18:48:23.895   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 18:48:23.895   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-31 18:48:23.896   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-31 18:48:23.896   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 18:48:23.896   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:23.896   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:23.896   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 18:48:23.896   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 18:48:23.897   872   895 I art     : Starting a blocking GC Explicit
08-31 18:48:23.897   872   885 I ActivityManager:   Force finishing activity ActivityRecord{53716b2 u0 com.test.thalitest/.MainActivity t2}
,08-31 18:48:23.908   872  2291 W ActivityManager: Spurious death for ProcessRecord{78aac33 0:com.test.thalitest/u0a0}, curProc for 3809: null
,08-31 18:48:23.960   872   895 I art     : Explicit concurrent mark sweep GC freed 55501(3MB) AllocSpace objects, 9(228KB) LOS objects, 33% free, 29MB/43MB, paused 851us total 62.150ms
,08-31 18:48:23.980   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 18:48:23.983  4249  4249 I art     : System.exit called, status: 0
,08-31 18:48:23.983  4249  4249 I AndroidRuntime: VM exiting with result code 0.
,08-31 18:48:23.988   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 18:48:24.001   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 18:48:24.005  4163  4163 D BluetoothMapAppObserver: onReceive
08-31 18:48:24.005  4163  4163 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-31 18:48:24.010  1991  2293 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 18:48:24.010   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 18:48:24.014  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 18:48:24.018  3647  3647 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 18:48:24.041  1947  1947 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 18:48:24.042  1881  4261 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 18:48:24.047  1881  4261 I Decoder : createOrResetDecoder
,08-31 18:48:24.050   872  1402 I ActivityManager: Start proc 4263:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 18:48:24.084  4263  4263 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 18:48:24.088  1513  1513 I ConfigService: onCreate
,08-31 18:48:24.100   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 18:48:24.104  1881  4261 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 18:48:24.114   872  2289 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3809 uid 10000
,08-31 18:48:24.115  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-31 18:48:24.128  1969  2059 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 18:48:24.128  1881  4261 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 18:48:24.129   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-31 18:48:24.129   872   884 E PackageManager: Failed to write settings, restoring backup
08-31 18:48:24.129   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 18:48:24.129   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 18:48:24.129   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 18:48:24.129   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 18:48:24.129   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 18:48:24.129   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.129   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.129   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 18:48:24.130  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 18:48:24.130  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 18:48:24.132  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 18:48:24.132  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 18:48:24.133   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-31 18:48:24.133   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 18:48:24.133   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.133   872   885 E DropBoxManagerService: 	... 13 more
,08-31 18:48:24.134  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 18:48:24.134  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-31 18:48:24.141  1881  4261 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 18:48:24.141  1881  4261 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 18:48:24.141  1881  4261 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 18:48:24.142  1881  4261 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-31 18:48:24.142   872  1978 I ActivityManager: Start proc 4279:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-31 18:48:24.142  1881  4261 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 18:48:24.142  1881  4261 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
--------- beginning of crash
08-31 18:48:24.143  1969  2059 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 18:48:24.143  1969  2059 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1969
08-31 18:48:24.143  1969  2059 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148),
08-31 18:48:24.143  1969  2059 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 18:48:24.145   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 18:48:24.146   872  4285 E DropBoxManagerService: Can't write: system_app_crash
08-31 18:48:24.146   872  4285 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.146   872  4285 E DropBoxManagerService: 	... 5 more
08-31 18:48:24.148  1969  2059 I Process : Sending signal. PID: 1969 SIG: 9
,08-31 18:48:24.175  4263  4263 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 18:48:24.182  4263  4293 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 18:48:24.184  4263  4278 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.184  4263  4278 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.185  4263  4278 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 18:48:24.193   872  1906 I WindowState: WIN DEATH: Window{1dfcc21 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 18:48:24.193   872  2290 D GraphicsStats: Buffer count: 1
,08-31 18:48:24.193   872  1693 I ActivityManager: Start proc 4294:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 18:48:24.210   872  1978 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1969) has died
,08-31 18:48:24.210   872  1978 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-31 18:48:24.212   872  1978 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 18:48:24.230   872   882 I ActivityManager: Start proc 4307:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 18:48:24.254  4294  4294 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm,
,08-31 18:48:24.273  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 18:48:24.274  1513  1513 D AndroidRuntime: Shutting down VM
08-31 18:48:24.275  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
08-31 18:48:24.275  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
08-31 18:48:24.275  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 18:48:24.275  1513  1513 E AndroidRuntime: 	... 8 more
08-31 18:48:24.279  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
08-31 18:48:24.279   872  4322 E DropBoxManagerService: Can't write: system_app_crash
08-31 18:48:24.279   872  4322 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file ,system)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.279   872  4322 E DropBoxManagerService: 	... 5 more
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:7,26)
08-31 18:48:24.280  4307  4307 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:24.280  4307  4307 D AndroidRuntime: Shutting down VM
08-31 18:48:24.289  4307  4307 E AndroidRuntime: FATAL EXCEPTION: main
08-31 18:48:24.289  4307  4307 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4307
08-31 18:48:24.289  4307  4307 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 18:48:24.289  4307  4307 E AndroidRuntime: 	... 10 more
08-31 18:48:24.293  1991  2656 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
08-31 18:48:24.293   872  2289 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 18:48:24.294   872  4324 E DropBoxManagerService: Can't write: system_app_crash
08-31 18:48:24.294   872  4324 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.294   872  4324 E DropBoxManagerService: 	... 5 more
08-31 18:48:24.294  4307  4307 I Process : Sending signal. PID: 4307 SIG: 9
08-31 18:48:24.295  1718  4323 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
08-31 18:48:24.296  1718  4323 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@f81a694
08-31 18:48:24.296   872  2288 I ActivityManager: Process com.google.process.gapps (pid 1513) early provider death
08-31 18:48:24.314   872  1309 D WifiService: Client connection lost with reason: 4
,08-31 18:48:24.317   872  2288 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
08-31 18:48:24.317   872  2288 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-31 18:48:24.317   872  2288 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-31 18:48:24.317   872  2288 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
08-31 18:48:24.317   872  2288 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
08-31 18:48:24.320   872  1384 W ActivityManager: Spurious death for ProcessRecord{35a82d1 0:com.google.process.gapps/u0a11}, curProc for 1513: null
08-31 18:48:24.329  1718  1718 W RocketImpressions: ClearcutLogger connection suspended: 1
08-31 18:48:24.335   872   882 I ActivityManager: Start proc 4326:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-31 18:48:24.338   872  2284 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4307) has died
08-31 18:48:24.339   872  2284 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 18:48:24.356   872   885 I ActivityManager: Start proc 4339:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 18:48:24.369  4263  4278 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-31 18:48:24.370  4326  4326 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-31 18:48:24.375  4326  4326 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-31 18:48:24.378  4326  4326 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:24.378  4326  4326 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 18:48:24.378  4326  4326 D AndroidRuntime: Shutting down VM
08-31 18:48:24.379  4326  4326 E AndroidRuntime: FATAL EXCEPTION: main
08-31 18:48:24.379  4326  4326 E AndroidRuntime: Process: com.google.process.gapps, PID: 4326
08-31 18:48:24.379  4326  4326 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 18:48:24.379  4326  4326 E AndroidRuntime: 	... 10 more
,08-31 18:48:24.379  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 18:48:24.379  1718  1718 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 18:48:24.383  4326  4326 I Process : Sending signal. PID: 4326 SIG: 9
,08-31 18:48:24.386   872  4352 E DropBoxManagerService: Can't write: system_app_crash
08-31 18:48:24.386   872  4352 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.386   872  4352 E DropBoxManagerService: 	... 5 more
,08-31 18:48:24.402  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-31 18:48:24.402  1718  1718 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded,
,08-31 18:48:24.403  4339  4339 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:24.403  4339  4339 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 18:48:24.403  4339  4339 D AndroidRuntime: Shutting down VM
,08-31 18:48:24.409  1718  4354 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 18:48:24.410  4339  4339 E AndroidRuntime: FATAL EXCEPTION: main
08-31 18:48:24.410  4339  4339 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4339
08-31 18:48:24.410  4339  4339 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 18:48:24.410  4339  4339 E AndroidRuntime: 	... 10 more
08-31 18:48:24.412   872  1978 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 18:48:24.413  4339  4339 I Process : Sending signal. PID: 4339 SIG: 9
,08-31 18:48:24.413   872  4356 E DropBoxManagerService: Can't write: system_app_crash
08-31 18:48:24.413   872  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.413   872  4356 E DropBoxManagerService: 	... 5 more
,08-31 18:48:24.420   872  1693 I ActivityManager: Process com.google.process.gapps (pid 4326) has died
,08-31 18:48:24.421   872  1693 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{902174b u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,08-31 18:48:24.421   872  1693 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{6636638 u0 com.google.android.gms/.gcm.GcmService}
08-31 18:48:24.421   872  1693 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{33ea042 u0 com.google.android.gms/.auth.GetToken}
08-31 18:48:24.421   872  1693 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{16cd875 u0 com.google.android.gms/.config.ConfigService}
08-31 18:48:24.430   872  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-31 18:48:24.433  1718  4354 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-31 18:48:24.433  1718  4354 E AndroidRuntime: Process: com.google.android.gms, PID: 1718
08-31 18:48:24.433  1718  4354 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 18:48:24.433  1718  4354 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-31 18:48:24.434   872  1693 I ActivityManager: Start proc 4357:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-31 18:48:24.441  4263  4293 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.441  4263  4293 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 18:48:24.442  4263  4293 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 18:48:24.442  4263  4293 E AndroidRuntime: Process: android.process.acore, PID: 4263
08-31 18:48:24.442  4263  4293 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
,08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 18:48:24.442  4263  4293 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 18:48:24.445  4263  4278 I Process : Sending signal. PID: 4263 SIG: 9
,08-31 18:48:24.456   872  1384 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4339) has died
,08-31 18:48:24.457   872  1384 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 18:48:24.462  2028  4353 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-31 18:48:24.466   872  4369 E DropBoxManagerService: Can't write: system_app_crash
08-31 18:48:24.466   872  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 18:48:24.466   872  4369 E DropBoxManagerService: 	... 5 more
,08-31 18:48:24.487   872  2284 I ActivityManager: Start proc 4370:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
