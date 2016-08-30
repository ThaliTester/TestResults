#### Test 82883341e52143e_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 09:34:01.696   871  1884 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 09:34:01.828  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 09:34:01.839  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 09:34:01.842  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 09:34:01.892  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 09:34:01.892  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 09:34:01.892  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:01.893  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 09:34:01.923  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 09:34:01.923  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 09:34:01.923  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 09:34:02.331  3815  3815 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 09:34:02.335  3815  3815 D AndroidRuntime: CheckJNI is OFF
08-30 09:34:02.371  3815  3815 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 09:34:02.414  3815  3815 I Radio-JNI: register_android_hardware_Radio DONE
08-30 09:34:02.435  3815  3815 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 09:34:02.439   871  2008 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 09:34:02.477  2013  2039 W SearchService: Abort, client detached.
08-30 09:34:02.496  3815  3815 D AndroidRuntime: Shutting down VM
08-30 09:34:02.497  2013  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a3ec8b4
08-30 09:34:02.497  2013  2350 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 09:34:02.497  2013  2013 I HotwordDetector: Closing mic
08-30 09:34:02.513   871  1742 I ActivityManager: Start proc 3824:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 09:34:02.562   376  2352 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 09:34:02.563   376  2352 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 09:34:02.567   376  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 09:34:02.570  2013  2349 I MicroRecognitionRnrImpl: Detection finished
08-30 09:34:02.570  2013  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 09:34:02.596  3824  3824 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 09:34:02.620  3824  3824 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 09:34:02.626  3824  3824 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1405-1407)
08-30 09:34:02.626  3824  3824 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:34:02.639  3824  3824 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4c81931}
08-30 09:34:02.639  3824  3824 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 09:34:02.639  3824  3824 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 09:34:02.644  3824  3824 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 09:34:02.645  3824  3824 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 09:34:02.657  3824  3824 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 09:34:02.666  3824  3824 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 09:34:02.666  3824  3824 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 09:34:02.666  3824  3824 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 09:34:02.666  3824  3824 I Adreno  : Build Date                       : 10/20/15
08-30 09:34:02.666  3824  3824 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 09:34:02.666  3824  3824 I Adreno  : Local Branch                     : M14
08-30 09:34:02.666  3824  3824 I Adreno  : Remote Branch                    : 
08-30 09:34:02.666  3824  3824 I Adreno  : Remote Branch                    : 
08-30 09:34:02.666  3824  3824 I Adreno  : Reconstruct Branch               : 
,08-30 09:34:02.750   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6af9bc6:true
,08-30 09:34:02.779  3824  3824 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 09:34:02.792  3824  3824 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 09:34:02.843  3824  3862 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 09:34:02.853  3824  3849 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 09:34:02.897  3824  3862 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 09:34:03.018   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms
,08-30 09:34:03.019  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-30 09:34:03.120  3824  3824 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3824
,08-30 09:34:03.257  3824  3824 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 09:34:03.320   871   881 I ActivityManager: Killing 2984:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 09:34:03.380   871   881 I ActivityManager: Killing 3211:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 09:34:03.494  3824  3864 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1695876816
,08-30 09:34:03.507  3824  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 09:34:03.507  3824  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 09:34:03.507  3824  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 09:34:03.507  3824  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 09:34:03.507  3824  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 09:34:03.509  3824  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90357dc added. We now have 1 listener(s)
,08-30 09:34:03.516  3824  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 09:34:03.519  3824  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 09:34:03.520  3824  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:34:03.520  3824  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 09:34:03.529  3824  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5c15c8 added. We now have 1 listener(s)
08-30 09:34:03.529  3824  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:34:03.532   871  1311 D WifiService: New client listening to asynchronous messages
,08-30 09:34:03.533  3824  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 09:34:03.533  3824  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 09:34:03.533  3824  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 09:34:03.534  3824  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 09:34:03.534  3824  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 09:34:03.536  3824  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:34:03.536  3824  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 09:34:03.545  3824  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:03.545  3824  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:34:03.545  3824  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 09:34:03.546  3824  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:34:03.546  3824  3864 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 09:34:03.624   871  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 09:34:03.712  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:03.714  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:03.717  3824  3824 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 09:34:04.433  3824  3874 W jxcore-log: Initializing JXcore engine
08-30 09:34:04.433  3824  3874 W jxcore-log: JXcore engine is ready
,08-30 09:34:04.485  3874  3874 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 09:34:04.485  3874  3874 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12033]" dev="sockfs" ino=12033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 09:34:04.485  3874  3874 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 09:34:04.485  3874  3874 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26963]" dev="sockfs" ino=26963 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 09:34:04.501  3824  3874 W jxcore-log: Starting JXcore engine
,08-30 09:34:04.630  3824  3874 W jxcore-log: Platform android
08-30 09:34:04.630  3824  3874 W jxcore-log: 
,08-30 09:34:04.630  3824  3874 W jxcore-log: Process ARCH arm
08-30 09:34:04.630  3824  3874 W jxcore-log: 
,08-30 09:34:04.892  3824  3874 I jxcore-log: JXcore Cordova bridge is ready!
08-30 09:34:04.892  3824  3874 I jxcore-log: 
08-30 09:34:04.892  3824  3874 W jxcore-log: JXcore engine is started
,08-30 09:34:04.898  3824  3864 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 09:34:04.902  3824  3824 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 09:34:09.561   871  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 09:34:09.856  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:09.863  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:09.914  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 09:34:09.915  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 09:34:09.915  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:09.916  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:09.950  3547  3882 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 09:34:09.950  3547  3882 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jdm.a(PG:82)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jcs.o(PG:406)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jcn.a(PG:1379)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jcs.i(PG:143)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at blb.a(PG:3937)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at czp.a(PG:18188)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at czp.a(PG:9081)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at czq.run(PG:1686)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 09:34:09.950  3547  3882 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jdj.a(PG:4091)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jdj.a(PG:1125)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jdm.a(PG:77)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	... 12 more
08-30 09:34:09.950  3547  3882 E HttpOperation: Caused by: faj: BadAuthentication
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at fal.a(PG:38)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	at jdj.a(PG:4089)
08-30 09:34:09.950  3547  3882 E HttpOperation: 	... 14 more
,08-30 09:34:10.019  1513  3080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 09:34:10.019  1513  3080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 09:34:10.019  1513  3080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:10.019  1513  3080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:10.035  3547  3882 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 09:34:10.035  3547  3882 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jdm.a(PG:82)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jcs.o(PG:406)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jcn.a(PG:1379)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jcs.i(PG:143)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at hec.a(PG:42)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at hee.a(PG:102)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at czr.a(PG:65)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at kka.a(PG:108)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at czp.a(PG:19176)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at czp.a(PG:9081)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at czq.run(PG:1686)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 09:34:10.035  3547  3882 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jdj.a(PG:4091)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jdj.a(PG:1125)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jdm.a(PG:77)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	... 15 more
08-30 09:34:10.035  3547  3882 E HttpOperation: Caused by: faj: BadAuthentication
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at fal.a(PG:38)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	at jdj.a(PG:4089)
08-30 09:34:10.035  3547  3882 E HttpOperation: 	... 17 more
,08-30 09:34:10.035  3547  3882 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 09:34:10.035  3547  3882 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at hec.a(PG:42)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at hee.a(PG:102)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at czr.a(PG:65)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at kka.a(PG:108)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: ,	at czq.run(PG:1686)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	... 15 more
08-30 09:34:10.035  3547  3882 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at fal.a(PG:38)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 09:34:10.035  3547  3882 E ExperimentLoader: 	... 17 more
,08-30 09:34:10.118   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128423, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 09:34:12.580   871  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 09:34:14.669  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 09:34:14.669  3824  3874 I jxcore-log: 
,08-30 09:34:14.671  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 09:34:14.671  3824  3874 I jxcore-log: 
,08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:14.684  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:34:14.690  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:34:14.693  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 09:34:14.693  3824  3874 I jxcore-log: 
,08-30 09:34:14.695  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 09:34:14.695  3824  3874 I jxcore-log: 
,08-30 09:34:15.186  3824  3874 I jxcore-log: Unit Test app is loaded
08-30 09:34:15.186  3824  3874 I jxcore-log: 
,08-30 09:34:15.192  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:34:15.192  3824  3874 I jxcore-log: 
,08-30 09:34:15.197  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:34:15.197  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@774b85a added. We now have 2 listener(s)
,08-30 09:34:15.198  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 09:34:15.198  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:34:15.198  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:34:15.198  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:34:15.198  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7a1a8b added. We now have 2 listener(s)
,08-30 09:34:15.198  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:34:15.199  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:34:15.201  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:15.207  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:34:15.208  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:15.208  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 09:34:15.210  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:15.210  3824  3874 D ExecuteNativeTests: Running unit tests
,08-30 09:34:15.212  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:15.217  3824  3824 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 09:34:15.304  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:34:15.304  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 added. We now have 3 listener(s)
,08-30 09:34:15.305  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:34:15.305  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:34:15.305  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 09:34:15.305  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:34:15.305  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 added. We now have 3 listener(s)
08-30 09:34:15.305  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:34:15.306  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:34:15.309  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:15.316  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:34:15.318  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:34:15.318  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 09:34:15.320  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 09:34:15.321  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:34:15.321  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:34:15.321  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 09:34:15.323  3824  3874 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 09:34:15.323  3824  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 09:34:15.323  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 09:34:15.323  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:34:15.324  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:34:15.324  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 09:34:15.324  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:15.324  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.324  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:34:15.324  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:34:15.324  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 removed from the list
08-30 09:34:15.324  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:15.324  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:15.325  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 removed from the list
,08-30 09:34:15.329  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:15.329  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:15.330  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:15.330  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.330  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:15.331  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:15.331  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:15.332  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:15.332  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:15.335  3824  3874 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 09:34:15.337  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:15.338  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.338  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:15.338  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:15.338  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:15.338  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:15.339  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:15.339  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.339  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:15.339  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.339  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:15.340  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:15.341  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:15.341  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:15.341  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:15.346  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 09:34:15.346  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 09:34:15.347  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 09:34:15.347  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 09:34:15.347  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 09:34:15.347  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 09:34:15.347  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 09:34:15.348  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 09:34:15.349  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections,: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 09:34:15.349  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:15.350  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.350  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:15.350  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:15.350  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:15.350  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:15.350  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:15.350  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.350  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:15.350  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:15.350  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:15.351  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:15.352  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:15.352  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:15.352  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:15.355  3824  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-30 09:34:15.356  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:15.360  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:34:15.361  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:15.362  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:34:15.362  3824  3874 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 09:34:15.362  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 09:34:15.364  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:15.364  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 09:34:15.364  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 09:34:15.364  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 09:34:15.365  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:15.365  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 09:34:15.366  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:15.367  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 09:34:15.367  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 09:34:15.368  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 09:34:15.368  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 09:34:15.368  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 09:34:15.368  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:15.368  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:34:15.371  3824  3888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:34:15.372  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 09:34:15.372  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 09:34:15.373  3824  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 09:34:15.377  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 09:34:15.378  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 09:34:15.379  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 09:34:15.380  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-30 09:34:15.381  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:34:15.381  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-30 09:34:15.382  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 09:34:15.382  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 09:34:15.382  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 09:34:15.383  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:34:15.388  2697  2830 D BtGatt.GattService: registerClient() - UUID=d688f052-9762-41d3-a06c-449a51627582
08-30 09:34:15.389  2697  2716 D BtGatt.GattService: onClientRegistered() - UUID=d688f052-9762-41d3-a06c-449a51627582, clientIf=5
08-30 09:34:15.391  3824  3834 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-30 09:34:15.392  2697  2730 D BtGatt.AdvertiseManager: message : 0
08-30 09:34:15.396  2697  2730 D BtGatt.AdvertiseManager: starting multi advertising
08-30 09:34:15.417  2697  2716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
08-30 09:34:15.424  2697  2716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 09:34:15.426  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 09:34:15.427  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 09:34:15.429  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 09:34:15.431  3824  3874 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 09:34:15.431  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 09:34:15.432  3824  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 09:34:15.432  3824  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 09:34:15.432  3824  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 09:34:15.432  3824  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 09:34:15.432  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 09:34:15.436  3824  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 09:34:15.436  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 09:34:15.938  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-30 09:34:15.939  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 09:34:15.939  3824  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:34:20.449  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-30 09:34:20.450  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
08-30 09:34:20.450  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:34:24.732  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:24.735  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:24.752  3729  3891 V GoogleAuthProtoRequest: [306] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 09:34:24.783  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 09:34:24.783  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 09:34:24.783  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:24.783  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 09:34:24.820  3729  3891 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 09:34:24.917  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:24.982  1513  2463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 09:34:24.982  1513  2463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 09:34:24.982  1513  2463 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:24.982  1513  2463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:25.021  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 09:34:25.021  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 09:34:25.022  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 09:34:25.092  1513  3892 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 09:34:25.099  1513  3892 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 09:34:25.161  1513  3892 W Uploader:  no longer exists, so no auth token.
,08-30 09:34:25.460  3824  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 09:34:25.460  3824  3874 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-30 09:34:25.461  3824  3874 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-30 09:34:25.461  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-30 09:34:25.469  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 09:34:25.469  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:34:25.470  3824  3874 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 09:34:25.980  1513  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 09:34:25.981  1513  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 09:34:25.981  1513  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:25.982  1513  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:26.038  1513  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 09:34:26.038  1513  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 09:34:26.038  1513  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 09:34:26.917  1513  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-30 09:34:26.917  1513  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-30 09:34:26.917  1513  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:26.917  1513  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:26.946  1513  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 09:34:26.946  1513  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 09:34:26.946  1513  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 09:34:27.189  1513  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 09:34:27.189  1513  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-30 09:34:27.190  1513  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:34:27.190  1513  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:27.244  1513  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 09:34:27.244  1513  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 09:34:27.244  1513  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 09:34:27.887  1513  3892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 09:34:27.887  1513  3892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 09:34:27.888  1513  3892 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:27.888  1513  3892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:27.934  1513  3892 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 09:34:27.934  1513  3892 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 09:34:27.934  1513  3892 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 09:34:30.229   871  1884 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 09:34:30.480  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:30.481  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 09:34:30.481  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 09:34:30.482  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 09:34:30.485  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 09:34:30.485  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 09:34:30.486  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
,08-30 09:34:30.486  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 09:34:30.486  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:30.486  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 09:34:30.487  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 09:34:30.487  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 09:34:30.487  3824  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 09:34:30.488  3824  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 09:34:30.489  3824  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 09:34:30.489  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 09:34:30.493  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:34:30.494  3824  3874 D BluetoothLeScanner: could not find callback wrapper
08-30 09:34:30.494  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:34:30.495  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 09:34:30.498  2697  2730 D BtGatt.AdvertiseManager: message : 1
08-30 09:34:30.500  2697  2730 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 09:34:30.517  2697  2716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 09:34:30.517  2697  2716 D BtGatt.GattService: Client app is not null!
,08-30 09:34:30.520  2697  2709 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 09:34:30.521  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 09:34:30.522  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 09:34:30.522  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 09:34:30.522  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-30 09:34:30.523  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-30 09:34:30.525  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:34:30.526  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 09:34:30.526  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 09:34:30.528  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 09:34:30.531  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 09:34:30.531  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 09:34:30.531  3824  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 09:34:30.532  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:34:30.532  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:30.533  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:30.533  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:30.534  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:30.535  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:30.538  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:30.539  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:30.539  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:30.539  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:30.541  3824  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 09:34:30.546  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:30.559  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:34:30.565  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:34:30.566  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 09:34:30.567  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 09:34:30.567  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 09:34:30.567  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 09:34:30.568  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:30.568  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 09:34:30.572  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:30.575  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 09:34:30.575  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 09:34:30.579  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:30.580  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 09:34:30.582  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 09:34:30.582  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 09:34:30.588  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 09:34:30.592  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 09:34:30.593  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 09:34:30.593  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 09:34:30.594  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 09:34:30.596  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:34:30.602  2697  2829 D BtGatt.GattService: registerClient() - UUID=b61b0e64-24ec-40dd-ba23-dbf584f9cc1d
,08-30 09:34:30.603  2697  2716 D BtGatt.GattService: onClientRegistered() - UUID=b61b0e64-24ec-40dd-ba23-dbf584f9cc1d, clientIf=5
,08-30 09:34:30.604  3824  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 09:34:30.605  2697  2709 D BtGatt.GattService: start scan with filters
,08-30 09:34:30.612  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 09:34:30.613  2697  2731 D BtGatt.ScanManager: handling starting scan
,08-30 09:34:30.613  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 09:34:30.614  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 09:34:30.614  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 09:34:30.614  2697  2731 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:34:30.623  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 09:34:30.624  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 09:34:30.624  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-30 09:34:30.627  2697  2716 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 09:34:30.627  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:34:30.628  2697  2731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 09:34:30.632  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 09:34:30.637  3824  3874 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 09:34:30.641  2697  2716 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 09:34:30.641  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:34:30.641  2697  2731 D BtGatt.ScanManager: Starting BLE batch scan,
08-30 09:34:30.641  2697  2731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 09:34:30.659  2697  2716 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 09:34:30.659  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:34:30.668  2697  2716 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 09:34:30.668  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:34:31.124  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 09:34:31.125  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:34:31.125  3824  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:34:31.378   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 09:34:31.391  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-30 09:34:31.398   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 09:34:31.398   871   891 I Adreno  : Build Date                       : 10/20/15
08-30 09:34:31.398   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 09:34:31.398   871   891 I Adreno  : Local Branch                     : M14
08-30 09:34:31.398   871   891 I Adreno  : Remote Branch                    : 
08-30 09:34:31.398   871   891 I Adreno  : Remote Branch                    : 
08-30 09:34:31.398   871   891 I Adreno  : Reconstruct Branch               : 
,08-30 09:34:31.446   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (616 us)
,08-30 09:34:32.078  3824  3824 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 09:34:32.079  3824  3824 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 09:34:32.115   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 09:34:32.117  3824  3824 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@26b4433 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@912e84f, 16908290=android.view.AbsSavedState$1@912e84f}, android:focusedViewId=100}]}]
,08-30 09:34:32.117  3824  3824 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 09:34:32.117  3824  3824 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 09:34:32.117  3824  3824 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 09:34:32.132   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 09:34:32.137   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 09:34:32.141   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-30 09:34:32.141   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 09:34:32.169  2697  2697 D BtGatt.ScanManager: awakened up at time 150950
,08-30 09:34:32.170  2697  2731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:34:32.193  2697  2716 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
08-30 09:34:32.193  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:34:32.194  2697  2716 D BtGatt.GattService: current time is 150975615779
,08-30 09:34:32.196  2697  2716 D BtGatt.GattService: Batch record : [-97, 123, -101, -9, 13, 91, 1, -128, -75, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -93, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 78, -20, -96, 83, -39, -56, 1, -128, -74, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39, 0, -97, 123, -101, -9, 13, 91, 1, -128, -75, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0]
,08-30 09:34:32.199  2697  2716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
,08-30 09:34:32.201  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-30 09:34:32.201  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 09:34:32.202  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 09:34:32.203  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-30 09:34:32.204  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 09:34:32.204  2697  2716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39]
08-30 09:34:32.205  2697  2716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
,08-30 09:34:32.214  3824  3824 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 3], added - the peer count is 1
,08-30 09:34:32.215  3824  3824 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 3], added - the peer count is 2
,08-30 09:34:32.217  3824  3824 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 90:E7:C4:FE:AC:EF 3] updated - the peer count is 2
,08-30 09:34:32.217  3824  3824 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 3], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,08-30 09:34:32.218  3824  3824 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 3], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,08-30 09:34:32.373   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-30 09:34:32.375   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-30 09:34:32.381   871  1334 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,08-30 09:34:32.384   871   891 I DreamManagerService: Entering dreamland.
,08-30 09:34:32.385   871   891 I PowerManagerService: Dozing...
,08-30 09:34:32.386   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 09:34:32.433   376  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 09:34:32.434   376  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 09:34:32.452   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 09:34:32.465  1919  3907 D NfcService: Discovery configuration equal, not updating.
08-30 09:34:32.468   871  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-30 09:34:32.470   871  1310 E native  : do suspend false
,08-30 09:34:32.493   871  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 09:34:32.506   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 09:34:32.510   871  1310 E native  : do suspend true
,08-30 09:34:32.575   376  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 09:34:32.576   376  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 09:34:32.698  2697  2697 D BtGatt.ScanManager: awakened up at time 151480
,08-30 09:34:32.699  2697  2731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:34:32.744  2697  2716 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-30 09:34:32.744  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:34:32.745  2697  2716 D BtGatt.GattService: current time is 151526839115
08-30 09:34:32.746  2697  2716 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -97, 123, -101, -9, 13, 91, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0, 35, 97, 126, -92, 22, -56, 1, -128, -77, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -97, 123, -101, -9, 13, 91, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0]
,08-30 09:34:32.747  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-30 09:34:32.747  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-30 09:34:32.748  2697  2716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
,08-30 09:34:32.749  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-30 09:34:32.750  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 09:34:32.751  2697  2716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-30 09:34:32.751  2697  2716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
,08-30 09:34:32.754  3824  3824 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 90:E7:C4:FE:AC:EF 3] updated - the peer count is 2
08-30 09:34:32.755  3824  3824 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 90:E7:C4:FE:AC:EF 3] updated - the peer count is 2
,08-30 09:34:32.959   871  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 09:34:34.247  2697  2697 D BtGatt.ScanManager: awakened up at time 153028
,08-30 09:34:34.253  2697  2731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:34:34.283  2697  2716 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-30 09:34:34.283  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:34:34.283  2697  2716 D BtGatt.GattService: current time is 153065148278
08-30 09:34:34.284  2697  2716 D BtGatt.GattService: Batch record : [-97, 123, -101, -9, 13, 91, 1, -128, -74, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0]
08-30 09:34:34.285  2697  2716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
,08-30 09:34:34.289  3824  3824 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 90:E7:C4:FE:AC:EF 3] updated - the peer count is 2
,08-30 09:34:35.638  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:34:35.638  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 09:34:35.639  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 09:34:35.639  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:35.639  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 09:34:35.640  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 09:34:35.640  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 09:34:35.640  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 09:34:35.640  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:34:35.641  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 09:34:35.641  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 09:34:35.645  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:34:35.647  2697  2829 D BtGatt.GattService: stopScan() - queue size =1
,08-30 09:34:35.649  2697  2830 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 09:34:35.650  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:34:35.651  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 09:34:35.651  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 09:34:35.652  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 09:34:35.652  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 09:34:35.656  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:34:35.657  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 09:34:35.657  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 09:34:35.657  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:34:35.658  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 09:34:35.660  2697  2697 D BtGatt.ScanManager: awakened up at time 154441
,08-30 09:34:35.660  3824  3874 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-30 09:34:35.664  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 09:34:35.664  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:34:35.664  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:34:35.665  2697  2716 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 09:34:35.665  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:34:35.666  2697  2731 D BtGatt.ScanManager: stopping BLe Batch
,08-30 09:34:35.676  2697  2716 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 09:34:35.676  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:34:35.676  2697  2731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:34:35.686  2697  2716 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 09:34:35.686  2697  2716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:34:36.165  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:34:36.166  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:34:36.166  3824  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:34:37.474  2025  2680 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 09:34:40.296  3767  3912 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 09:34:40.349  3767  3913 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 09:34:40.385  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:40.393  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:40.477  1513  2463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 09:34:40.478  1513  2463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 09:34:40.478  1513  2463 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:40.479  1513  2463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:40.566  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:40.575  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:40.658  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 09:34:40.659  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 09:34:40.659  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:40.660  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:40.666  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:40.667  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.667  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 09:34:40.667  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.668  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.668  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.668  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:40.669  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.672  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:40.673  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.677  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:40.678  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:40.678  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.678  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.680  3824  3874 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 09:34:40.684  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:40.684  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.685  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.686  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.686  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.686  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.686  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:40.687  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:40.687  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.687  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.688  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.690  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:40.691  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:40.691  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.691  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list,
,08-30 09:34:40.695  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 09:34:40.696  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:40.696  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.696  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.696  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
,08-30 09:34:40.696  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-30 09:34:40.697  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.697  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop,
,08-30 09:34:40.697  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.697  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.697  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.698  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.700  3767  3913 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 09:34:40.700  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:40.700  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:40.700  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.700  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.701  3824  3874 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 09:34:40.701  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:40.701  3767  3912 E BooksSync: Soft error
08-30 09:34:40.701  3767  3912 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 09:34:40.701  3767  3912 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 09:34:40.701  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.702  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.702  3767  3912 E BooksSync: Sync error
08-30 09:34:40.702  3767  3912 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 09:34:40.702  3767  3912 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 09:34:40.702  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.702  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.702  3767  3912 I BooksSync: Finished books sync
08-30 09:34:40.702  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.702  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:40.702  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.702  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.702  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.702  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-30 09:34:40.703  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:40.703  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:40.703  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.704  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.704  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-30 09:34:40.704  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:40.704  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.704  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.705  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.705  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.705  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.705  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:40.705  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.705  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.705  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.705  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.706  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:40.706  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:40.706  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.707  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.707  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 09:34:40.707  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 09:34:40.707  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:34:40.708  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 09:34:40.708  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 09:34:40.708  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:34:40.708  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 09:34:40.708  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 09:34:40.708  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 09:34:40.708  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:40.708  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.708  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.708  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.709  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.709  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.709  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:40.709  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.709  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.709  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.709  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.710  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:40.710  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:40.710  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.710  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.712  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 09:34:40.712  3824  3874 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 09:34:40.712  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 09:34:40.717  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 09:34:40.717  3824  3874 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 09:34:40.718  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 09:34:40.718  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 09:34:40.718  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 09:34:40.718  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 09:34:40.719  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 09:34:40.719  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-30 09:34:40.719  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 09:34:40.719  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 09:34:40.719  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 09:34:40.719  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-30 09:34:40.719   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158934, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-30 09:34:40.720  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 09:34:40.720  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 09:34:40.720  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 09:34:40.720  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 09:34:40.720  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 09:34:40.721  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 09:34:40.722  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 09:34:40.722  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-30 09:34:40.722  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 09:34:40.722  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 09:34:40.722  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 09:34:40.722  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 09:34:40.723  3824  3874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 09:34:40.723  3824  3874 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 09:34:40.723  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:34:40.723  3824  3874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 09:34:40.723  3824  3874 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 09:34:40.723  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 09:34:40.723  3824  3874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 09:34:40.723  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 09:34:40.727  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 09:34:40.728  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 09:34:40.728  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 09:34:40.729  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-30 09:34:40.729  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 09:34:40.732  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 09:34:40.732  3824  3874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 09:34:40.732  3824  3874 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 09:34:40.733  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:40.735  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.735  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.736  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 09:34:40.736  3824  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-30 09:34:40.737  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.737  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.737  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.737  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:40.737  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.737  3824  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-30 09:34:40.737  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.738  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.738  3824  3914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:34:40.738  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.740  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:40.740  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:40.740  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.741  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.741  3824  3874 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 09:34:40.742  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:40.742  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.742  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.742  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.742  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.742  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.742  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:40.743  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:40.743  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.743  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:40.743  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.744  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:40.744  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:40.744  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.744  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.745  3824  3874 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 09:34:40.745  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:40.745  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.745  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.746  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.746  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.746  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:40.746  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:40.746  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.746  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.746  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.746  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.747  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:40.747  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:40.747  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:40.748  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.748  3824  3874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 09:34:40.749  3824  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 09:34:40.749  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 09:34:40.749  3824  3874 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 09:34:40.749  3824  3874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 09:34:40.749  3824  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-30 09:34:40.749  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 09:34:40.749  3824  3874 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 09:34:40.749  3824  3874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 09:34:40.749  3824  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 09:34:40.749  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 09:34:40.749  3824  3874 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 09:34:40.749  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:40.750  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.750  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.750  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:40.750  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.750  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.750  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:40.750  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:40.750  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:40.750  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:40.750  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:40.751  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:40.751  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:40.751  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:40.751  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:40.754  3824  3874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 09:34:40.755  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:40.759  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:34:40.760  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:34:40.760  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:34:40.761  3824  3874 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
08-30 09:34:40.761  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-30 09:34:40.761  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 09:34:40.761  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 09:34:40.761  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 09:34:40.761  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:40.762  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 09:34:40.763  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:40.763  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 09:34:40.763  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 09:34:40.764  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 09:34:40.764  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 09:34:40.764  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:34:40.764  3824  3917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:34:40.764  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:34:40.766  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:40.766  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 09:34:40.768  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 09:34:40.768  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 09:34:40.768  3824  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 09:34:40.772  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 09:34:40.772  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 09:34:40.772  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 09:34:40.774  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 09:34:40.775  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:34:40.775  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-30 09:34:40.775  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 09:34:40.775  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 09:34:40.775  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 09:34:40.776  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:34:40.779  2697  2708 D BtGatt.GattService: registerClient() - UUID=c5d30e6d-4f24-4bf1-a838-35f189a40c12
,08-30 09:34:40.779  2697  2716 D BtGatt.GattService: onClientRegistered() - UUID=c5d30e6d-4f24-4bf1-a838-35f189a40c12, clientIf=5
,08-30 09:34:40.780  3824  3836 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 09:34:40.781  2697  2730 D BtGatt.AdvertiseManager: message : 0
,08-30 09:34:40.783  2697  2730 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 09:34:40.795  3756  3916 V KeepSync: Connecting to GoogleApiClient
,08-30 09:34:40.795   871  1388 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-30 09:34:40.796  2697  2716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 09:34:40.804  2697  2716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-30 09:34:40.804  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-30 09:34:40.805  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 09:34:40.806  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 09:34:40.808  3824  3874 I io.jxcore.node.ConnectionHelper: start: OK
08-30 09:34:40.809  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 09:34:40.809  3824  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 09:34:40.809  3824  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 09:34:40.809  3824  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 09:34:40.809  3824  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 09:34:40.809  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 09:34:40.812  3824  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 09:34:40.812  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 09:34:40.844  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:40.847  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:40.888  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 09:34:40.889  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 09:34:40.889  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:40.890  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:40.928  1727  3918 V BaseAuthAsyncOperation: access token request failed
,08-30 09:34:40.930  3756  3916 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 09:34:41.017  1513  2463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 09:34:41.018  1513  2463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 09:34:41.018  1513  2463 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:41.019  1513  2463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:41.059  3756  3916 E KeepSync: IOException
08-30 09:34:41.059  3756  3916 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 09:34:41.059  3756  3916 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 09:34:41.059  3756  3916 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 09:34:41.059  3756  3916 E KeepSync: 	... 10 more
08-30 09:34:41.059  3756  3916 W KeepSync: Sync result 2
,08-30 09:34:41.076   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 159468, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 09:34:41.313  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 09:34:41.313  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 09:34:41.314  3824  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:34:43.640   871  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 09:34:45.280  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:34:45.349  1513  2463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 09:34:45.349  1513  2463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 09:34:45.349  1513  2463 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:34:45.349  1513  2463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:34:45.379  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 09:34:45.381  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 09:34:45.384  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 09:34:45.809  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:45.809  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 09:34:45.809  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 09:34:45.810  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 09:34:45.810  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 09:34:45.810  3824  3917 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 09:34:45.811  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 09:34:45.811  3824  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 09:34:45.811  3824  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 09:34:45.812  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 09:34:45.812  3824  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 09:34:45.813  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:45.813  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:45.814  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 09:34:45.814  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 09:34:45.814  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:34:45.816  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 09:34:45.818  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:34:45.819  3824  3874 D BluetoothLeScanner: could not find callback wrapper
,08-30 09:34:45.819  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 09:34:45.819  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 09:34:45.821  2697  2730 D BtGatt.AdvertiseManager: message : 1
,08-30 09:34:45.823  2697  2730 D BtGatt.AdvertiseManager: stop advertise for client 5
08-30 09:34:45.833  2697  2716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-30 09:34:45.833  2697  2716 D BtGatt.GattService: Client app is not null!,
,08-30 09:34:45.835  2697  2709 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 09:34:45.836  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 09:34:45.836  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 09:34:45.836  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 09:34:45.838  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-30 09:34:45.838  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 09:34:45.841  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:34:45.841  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 09:34:45.842  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 09:34:45.843  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,08-30 09:34:45.846  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:45.847  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:45.847  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:34:45.848  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:45.848  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:34:45.849  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:34:45.869  2697  2798 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 09:34:45.869  2697  2826 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,08-30 09:34:45.870  3824  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
,08-30 09:34:46.350  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:34:50.849  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:50.851  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:50.851  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:50.852  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.853  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:50.854  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:50.854  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:50.854  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:50.855  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.855  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:50.855  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:50.856  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.856  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:50.856  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:50.856  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.857  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.857  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:50.864  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:50.865  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:50.867  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.867  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:50.871  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 09:34:50.872  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:34:50.874  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 09:34:50.875  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 09:34:50.875  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 09:34:50.876  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 09:34:50.876  3824  3920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:34:50.876  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 09:34:50.876  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 09:34:50.879  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:50.879  3824  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 09:34:50.879  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 09:34:50.879  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 09:34:50.879  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 09:34:50.880  3824  3920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 09:34:50.880  3824  3920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 09:34:50.880  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.880  3824  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 09:34:50.880  3824  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 09:34:50.880  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 09:34:50.881  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 09:34:50.882  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:50.882  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.882  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 09:34:50.882  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 09:34:50.883  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:34:50.884  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.884  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.887  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:34:50.887  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:34:50.888  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:34:50.888  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:34:50.889  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.889  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:50.889  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.890  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.890  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
,08-30 09:34:50.890  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.891  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.891  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:50.891  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.891  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.891  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:50.892  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.894  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:34:50.895  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:50.895  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.895  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:50.900  3824  3874 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 09:34:50.901  3824  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 09:34:50.901  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 09:34:50.906  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 09:34:50.906  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 09:34:50.907  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:34:50.907  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.907  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:50.908  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:50.908  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.908  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.909  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:50.909  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.909  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.909  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.910  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:50.911  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 09:34:50.912  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:50.912  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-30 09:34:50.912  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
,08-30 09:34:50.917  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:50.917  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:50.917  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.918  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
08-30 09:34:50.918  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:50.918  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.918  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:34:50.919  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.919  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.919  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.919  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:50.920  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:50.920  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:34:50.920  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:50.920  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.921  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:34:50.921  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.921  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.921  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb62f1 not in the list
,08-30 09:34:50.921  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.922  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.922  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:50.922  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:50.922  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.922  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:34:50.922  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:50.923  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:34:50.923  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:34:50.923  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:50.924  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@494bed6 not in the list
08-30 09:34:50.925  3824  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 09:34:50.925  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 09:34:50.925  3824  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 09:34:50.925  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 09:34:50.925  3824  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-30 09:34:50.925  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 09:34:50.927  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 09:34:50.928  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 09:34:50.928  3824  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 09:34:50.928  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 09:34:50.928  3824  3874 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1,
08-30 09:34:50.928  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 09:34:50.929  3824  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 09:34:50.929  3824  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 09:34:50.929  3824  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
08-30 09:34:50.929  3824  3874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-30 09:34:50.930  3824  3874 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 09:34:50.930  3824  3874 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 09:34:50.930  3824  3874 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 09:34:50.930  3824  3874 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-30 09:34:50.931  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:34:50.931  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1970be3 added. We now have 3 listener(s)
,08-30 09:34:50.931  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:34:50.934  3824  3874 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 09:34:50.934   871  1388 D WifiService: setWifiEnabled: true pid=3824, uid=10000
,08-30 09:34:50.934   871  1388 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:34:51.390  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:34:52.363   871  1884 D NetlinkSocketObserver: NeighborEvent{elapsedMs=171144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 09:34:55.943  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 09:34:55.943  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78169e0 added. We now have 4 listener(s)
,08-30 09:34:55.944  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:34:55.960  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:34:55.961  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78169e0 removed from the list,
,08-30 09:34:55.961  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:55.961  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:55.962  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:34:55.966  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 09:34:55.966  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39c8499 added. We now have 4 listener(s)
08-30 09:34:55.966  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:34:55.970  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:34:55.970  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39c8499 removed from the list
08-30 09:34:55.970  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:34:55.971  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:34:55.971  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:34:55.973  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:34:55.974  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@161435e added. We now have 4 listener(s)
08-30 09:34:55.974  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:34:55.981   871   882 D WifiService: setWifiEnabled: false pid=3824, uid=10000
,08-30 09:34:55.981   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:34:55.996  2697  2712 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 09:34:55.997  2697  2712 D BluetoothAdapterProperties: Setting state to 13
08-30 09:34:55.997  2697  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 09:34:55.997  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:34:55.999  2697  2712 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 09:34:56.003  2697  2712 I BluetoothAdapterState: Entering PendingCommandState
08-30 09:34:56.008  2697  2697 D BluetoothMapService: onReceive
08-30 09:34:56.008  2697  2697 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:34:56.009  2697  2697 D BluetoothMapService: STATE_TURNING_OFF
08-30 09:34:56.009  2697  2697 D BluetoothMapService: MAP Service closeService in
08-30 09:34:56.009  2697  2697 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 09:34:56.009  2697  2697 D ObexServerSockets0: shutdown(block = true)
08-30 09:34:56.010  2697  2697 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 09:34:56.010  2697  2697 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 09:34:56.014  2697  2854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 09:34:56.014  2697  2855 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 09:34:56.014  2697  2826 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 09:34:56.015  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:56.016  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:34:56.017  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:34:56.017  2697  2697 I BtOppRfcommListener: stopping Accept Thread
08-30 09:34:56.017  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:34:56.018  2697  3426 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 09:34:56.018  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:34:56.019  2697  3426 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 09:34:56.021  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:56.024  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.024  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 09:34:56.027  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:56.027  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:34:56.028  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.028  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:56.029   871  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 09:34:56.029   871  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 09:34:56.029   871  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 09:34:56.029   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:34:56.032  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:34:56.032  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:34:56.033  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:34:56.033  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:34:56.036  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:56.039   871  1310 E native  : do suspend true
,08-30 09:34:56.044   871   884 I ActivityManager: Start proc 3924:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 09:34:56.045  2697  2716 D BluetoothAdapterProperties: Scan Mode:20
,08-30 09:34:56.046  2697  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 09:34:56.048  2697  2697 D HeadsetService: Received stop request...Stopping profile...
,08-30 09:34:56.049  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.050   871  1885 D DhcpClient: Clearing IP address
08-30 09:34:56.051  1366  1377 D BluetoothHeadset: Proxy object disconnected
08-30 09:34:56.051   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:34:56.051  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:56.051   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 09:34:56.051  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-30 09:34:56.051  1935  1947 D BluetoothHeadset: Proxy object disconnected
,08-30 09:34:56.051   871   871 D BluetoothHeadset: Proxy object disconnected
,08-30 09:34:56.052   871   871 D BluetoothHeadset: Proxy object disconnected
,08-30 09:34:56.053  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.053  2697  2697 D A2dpService: Received stop request...Stopping profile...
08-30 09:34:56.054  2697  2835 D A2dpStateMachine: Exit Disconnected: -1
08-30 09:34:56.055   871   871 D BluetoothA2dp: Proxy object disconnected
08-30 09:34:56.055  1366  1366 D BluetoothA2dp: Proxy object disconnected
,08-30 09:34:56.056  2697  2697 V BluetoothAdapterState: isTurningOff()=true
,08-30 09:34:56.056  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,08-30 09:34:56.056  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:34:56.056  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:34:56.056  2697  2697 D HidService: Received stop request...Stopping profile...
08-30 09:34:56.056  2697  2697 D HidService: Stopping Bluetooth HidService
08-30 09:34:56.055   372   869 D CommandListener: Setting iface cfg
08-30 09:34:56.057  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-30 09:34:56.057  1366  1366 D HidProfile: Bluetooth service disconnected
08-30 09:34:56.058  2697  2697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 09:34:56.058  2697  2697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:34:56.059  2697  2716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 09:34:56.060  2697  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 09:34:56.060  2697  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:34:56.060  2697  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:34:56.059  2697  2697 D HealthService: Received stop request...Stopping profile...
08-30 09:34:56.060  2697  2716 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 09:34:56.061  2697  2697 D PanService: Received stop request...Stopping profile...
08-30 09:34:56.062   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 09:34:56.062   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 09:34:56.063  1513  2495 V NativeCrypto: Read error: ssl=0x9afebe00: I/O error during system call, Connection timed out
,08-30 09:34:56.064  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 09:34:56.064  1366  1366 D PanProfile: Bluetooth service disconnected
08-30 09:34:56.065  2697  2697 D BluetoothMapService: Received stop request...Stopping profile...
08-30 09:34:56.065  2697  2697 D BluetoothMapService: stop()
08-30 09:34:56.065  2697  2697 D BluetoothMapAppObserver: deinitObservers()
08-30 09:34:56.065   402   402 E Parcel  : Reading a NULL string not supported here.
08-30 09:34:56.065  2697  2697 D BluetoothMapAppObserver: removeReceiver()
08-30 09:34:56.068  1366  1366 D BluetoothMap: Proxy object disconnected
08-30 09:34:56.068  1366  1366 D MapProfile: Bluetooth service disconnected
08-30 09:34:56.069  2697  2697 V BluetoothAdapterState: isTurningOff()=true
08-30 09:34:56.069  2697  2697 V BluetoothAdapterState: isTurningOn()=false
08-30 09:34:56.069  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 09:34:56.069  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:34:56.069   871  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 09:34:56.070  2697  2697 V BluetoothAdapterState: isTurningOff()=true
08-30 09:34:56.070  2697  2697 V BluetoothAdapterState: isTurningOn()=false
08-30 09:34:56.070   871  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 09:34:56.070  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:34:56.070   871  1310 E native  : do suspend true
,08-30 09:34:56.070  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:34:56.070  2697  2697 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 09:34:56.070  2697  2697 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 09:34:56.071  2697  2697 V BluetoothAdapterState: isTurningOff()=true
08-30 09:34:56.071  2697  2697 V BluetoothAdapterState: isTurningOn()=false
08-30 09:34:56.071  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:34:56.071  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:34:56.071  2697  2697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 09:34:56.071  2697  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:34:56.071  2697  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 09:34:56.071  2697  2798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:34:56.072  2697  2798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:34:56.072  2697  2798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 09:34:56.072  2697  2798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:34:56.072  2697  2716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 09:34:56.072  2697  2716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 09:34:56.072  2697  2716 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 09:34:56.072  2697  2697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 09:34:56.072  2697  2697 V BluetoothAdapterState: isTurningOff()=true
08-30 09:34:56.072  2697  2697 V BluetoothAdapterState: isTurningOn()=false
08-30 09:34:56.072  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:34:56.072  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:34:56.073  2697  2697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 09:34:56.073  2697  2697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 09:34:56.073   871  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 09:34:56.074  2697  2697 D BluetoothMapService: MAP Service closeService in
08-30 09:34:56.075  2697  2697 V BluetoothAdapterState: isTurningOff()=true
08-30 09:34:56.075  2697  2697 V BluetoothAdapterState: isTurningOn()=false
08-30 09:34:56.075  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:34:56.075  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:34:56.076  2697  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 09:34:56.076  2697  2712 D BluetoothAdapterProperties: Setting state to 15
,08-30 09:34:56.077  2697  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 09:34:56.077  2697  2712 I BluetoothAdapterState: Entering BleOnState
08-30 09:34:56.077  1366  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:34:56.077  2697  2697 D BluetoothMapService: cleanup()
08-30 09:34:56.077  2697  2697 D BluetoothMapService: MAP Service closeService in
08-30 09:34:56.078  1366  2047 D BluetoothMap: onBluetoothStateChange: up=false
08-30 09:34:56.079  1366  1377 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 09:34:56.079   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 09:34:56.080  1366  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 09:34:56.080  1935  2367 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 09:34:56.081  1366  2047 D BluetoothPan: onBluetoothStateChange on: false
08-30 09:34:56.081   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:34:56.081   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:34:56.082  1366  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 09:34:56.082   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:34:56.082  2697  2712 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 09:34:56.082  2697  2712 D BluetoothAdapterProperties: Setting state to 16
08-30 09:34:56.082  2697  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 09:34:56.083  2697  2712 D BluetoothAdapterProperties: onBleDisable
08-30 09:34:56.083  2697  2712 I BluetoothAdapterState: Entering PendingCommandState
,08-30 09:34:56.084  2697  2713 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 09:34:56.084   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:34:56.085  2697  2798 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 09:34:56.085  2697  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:34:56.087  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:34:56.087  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:34:56.087  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.088  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:34:56.089   871  1886 D DhcpClient: Receive thread stopped
08-30 09:34:56.090  2697  2716 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:34:56.091  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.092   871  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:34:56.092  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:34:56.092  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.092  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:34:56.094  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:34:56.094  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:34:56.095  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.095  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:34:56.096  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.098  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.102  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:56.109  1513  2495 V NativeCrypto: SSL shutdown failed: ssl=0x9afebe00: I/O error during system call, Broken pipe
,08-30 09:34:56.111   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 09:34:56.114   871  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 09:34:56.115  2025  2323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 09:34:56.116  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:34:56.116  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:34:56.116  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.116  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:34:56.120  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:34:56.120  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:34:56.121  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.121  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:34:56.123  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.123   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:34:56.123  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:34:56.123  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:34:56.123  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:34:56.132  3924  3924 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 09:34:56.143  3924  3924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 09:34:56.146   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 09:34:56.146   871  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 09:34:56.146   871  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 09:34:56.147  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:34:56.148   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 09:34:56.150  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.152  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:34:56.153  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:34:56.164  3413  3413 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b59a0e5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 09:34:56.166   871   881 I ActivityManager: Start proc 3942:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 09:34:56.170   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb6e19a:true
,08-30 09:34:56.179  3924  3924 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 09:34:56.181  3924  3924 D BluetoothMap: Create BluetoothMap proxy object
,08-30 09:34:56.192  3924  3924 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 09:34:56.201  3942  3942 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-30 09:34:56.202   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-30 09:34:56.202   871  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 09:34:56.209  3924  3924 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:34:56.212   871  1387 I ActivityManager: Killing 3413:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 09:34:56.299  2697  2716 I bt_hci  : shut_down
,08-30 09:34:56.304  2697  2732 I bt_vendor: low_power_mode_cb
,08-30 09:34:56.308  2697  2732 D bt_hwcfg: hw_epilog_process
,08-30 09:34:56.332  2697  2732 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 09:34:56.332  2697  2732 I bt_vendor: epilog_cb
,08-30 09:34:56.333  2697  2732 I bt_hci  : epilog_finished_callback
,08-30 09:34:56.338  2697  2716 I bt_hci_h4: hal_close
,08-30 09:34:56.339  2697  2716 I bt_userial_vendor: device fd = 51 close
,08-30 09:34:56.368  3942  3942 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
,08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 09:34:56.368  3942  3942 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.368  3942  3942 D StrictMode: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 09:34:56.368  3942  3942 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 09:34:56.368  3942  3942 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 09:34:56.368  3942  3942 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.368  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 09:34:56.369  3942  3942 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 09:34:56.369  3942  3942 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 09:34:56.369  3942  3942 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 09:34:56.369  3942  3942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 09:34:56.374  3924  3924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 09:34:56.382  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 09:34:56.403  3924  3924 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:34:56.435   871  2010 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 09:34:56.484  2697  2713 D bt_stack_manager: event_shut_down_stack finished.
,08-30 09:34:56.485  2697  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 09:34:56.485  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 09:34:56.488  2697  2712 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 09:34:56.489  2697  2697 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 09:34:56.489  2697  2697 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 09:34:56.489  2697  2697 D BtGatt.GattService: stop()
08-30 09:34:56.489  2697  2697 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 09:34:56.496  2697  2697 V BluetoothAdapterState: isTurningOff()=false
,08-30 09:34:56.497  2697  2697 V BluetoothAdapterState: isTurningOn()=false
08-30 09:34:56.497  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 09:34:56.497  2697  2697 V BluetoothAdapterState: isBleTurningOff()=true
08-30 09:34:56.498  2697  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 09:34:56.498  2697  2712 D BluetoothAdapterProperties: Setting state to 10
,08-30 09:34:56.498  2697  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 09:34:56.500  1727  1727 D SystemUpdateService: onCreate
,08-30 09:34:56.500  2697  2712 I BluetoothAdapterState: Entering OffState
,08-30 09:34:56.501   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 09:34:56.504  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 09:34:56.531  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 09:34:56.537  2697  2697 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 09:34:56.537  2697  2697 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 09:34:56.537  2697  2713 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 09:34:56.537  2697  2697 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 09:34:56.540  2697  2713 D bt_stack_manager: event_clean_up_stack finished.
,08-30 09:34:56.543  1727  2456 I iu.UploadsManager: num queued entries: 0
,08-30 09:34:56.543  1727  2456 I iu.UploadsManager: num updated entries: 0
,08-30 09:34:56.549  1727  3977 I SystemUpdateService: active receiver: enabled
,08-30 09:34:56.551  2697  2697 I art     : System.exit called, status: 0
,08-30 09:34:56.551  2697  2697 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 09:34:56.563  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 09:34:56.567  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 09:34:56.569  1727  3977 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 09:34:56.570  1727  2456 I iu.SyncManager: NEXT; no task
,08-30 09:34:56.578  1727  3977 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 09:34:56.578  1727  3977 I SystemUpdateService: now status is 0 (complete)
08-30 09:34:56.578  1727  3977 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 09:34:56.578  1727  3977 I SystemUpdateService: file has been verified
08-30 09:34:56.578  1727  3977 I SystemUpdateService: OTA package size = 12249756
,08-30 09:34:56.600  1727  3977 I SystemUpdateService: showing system update notification
,08-30 09:34:56.611   871   881 I ActivityManager: Start proc 3980:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 09:34:56.620   871  1980 I ActivityManager: Process com.android.bluetooth (pid 2697) has died
,08-30 09:34:56.640  1727  1727 D SystemUpdateService: onDestroy
,08-30 09:34:56.661  3980  3980 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 09:34:56.665  3980  3980 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:34:56.680  3980  3980 D SprintDMHelper: simOperator: 
,08-30 09:34:56.680  3980  3980 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 09:34:56.718   871  1980 I ActivityManager: Start proc 3993:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 09:34:56.719   871  1980 I ActivityManager: Killing 1700:android.process.acore/u0a5 (adj 15): empty #17
,08-30 09:34:56.743  3942  3964 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 09:34:56.753   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4e87ee:true
,08-30 09:34:56.909  2416  4010 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 09:34:56.920   871  2010 I ActivityManager: Start proc 4011:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 09:34:56.958  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 09:34:57.014  4011  4011 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 09:34:57.014  4011  4011 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 09:34:57.014  4011  4011 I GAv4    :   adb logcat -s GAv4
,08-30 09:34:57.033  4011  4011 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 09:34:57.039  4011  4011 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 09:34:57.070  4011  4028 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 09:34:57.174  4011  4011 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 09:34:57.214  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 09:34:57.223  4011  4011 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6001-6004)
,08-30 09:34:57.223  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 09:34:57.233  4011  4011 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d4d8d55}
,08-30 09:34:57.234  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 09:34:57.234  4011  4011 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 09:34:57.247  4011  4011 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 09:34:57.249  4011  4011 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 09:34:57.263  4011  4011 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 09:34:57.279  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 09:34:57.280  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 09:34:57.280  4011  4011 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 09:34:57.280  4011  4011 I Adreno  : Build Date                       : 10/20/15
08-30 09:34:57.280  4011  4011 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 09:34:57.280  4011  4011 I Adreno  : Local Branch                     : M14
08-30 09:34:57.280  4011  4011 I Adreno  : Remote Branch                    : 
08-30 09:34:57.280  4011  4011 I Adreno  : Remote Branch                    : 
08-30 09:34:57.280  4011  4011 I Adreno  : Reconstruct Branch               : 
,08-30 09:34:57.346  4011  4011 I NSApplication: Starting up...
,08-30 09:34:57.360  4011  4057 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 09:34:57.395   871  1384 I ActivityManager: Start proc 4062:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 09:34:57.397   871  1384 I ActivityManager: Killing 3632:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 09:34:57.481  4062  4062 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 09:34:57.665   871  2010 I ActivityManager: Killing 3647:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 09:35:01.020   871  1980 D WifiService: setWifiEnabled: true pid=3824, uid=10000
08-30 09:35:01.021   871  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:35:01.036   871  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-30 09:35:01.042  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:01.042  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:01.043  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:01.043  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:01.046  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:01.046  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:01.046  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:01.046  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:01.048  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:01.048  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:01.048  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:01.048  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:01.067   871  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-30 09:35:01.068   871  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 09:35:01.069   871  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 09:35:01.070   871  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 09:35:01.071   871  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 09:35:01.071   871  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 09:35:01.071   871  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 09:35:01.084   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 09:35:01.084   871  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 09:35:01.085   372   869 D CommandListener: Setting iface cfg
,08-30 09:35:01.086   871  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
,08-30 09:35:01.087   871  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 09:35:01.095   871  1310 E native  : do suspend true
,08-30 09:35:01.103   871  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 09:35:01.103   871  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 09:35:01.110   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 09:35:01.983   871  1980 I ActivityManager: Killing 2198:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 09:35:02.499   871  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 09:35:04.123   871  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.34 rxSuccessRate=3.06 delta 1000 -> 1000
,08-30 09:35:04.131   871  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 09:35:04.132   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:35:04.153   871  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 09:35:04.193   871  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 09:35:04.195  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 09:35:04.645  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 09:35:04.688  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 09:35:04.689  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 09:35:04.695   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 09:35:04.715   871  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 09:35:04.716   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 09:35:04.716   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 09:35:04.750   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:35:04.768   372   869 D CommandListener: Setting iface cfg
,08-30 09:35:04.770   871  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 09:35:04.787   871  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 09:35:04.810   871  4087 D DhcpClient: Receive thread started
,08-30 09:35:04.907   871  1310 E native  : do suspend false
,08-30 09:35:04.934   871  1885 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 09:35:04.951   871  4087 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172639, domain null
,08-30 09:35:04.952   871  1885 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172639 seconds
,08-30 09:35:04.956   871  1885 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 09:35:04.970   871  4087 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 09:35:04.972   871  1885 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 09:35:04.977   372   869 D CommandListener: Setting iface cfg
,08-30 09:35:04.991   871  1885 D DhcpClient: Scheduling renewal in 86399s
,08-30 09:35:04.991   871  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 09:35:04.994   871  1310 E native  : do suspend true
,08-30 09:35:05.013   871  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 09:35:05.014   871  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 09:35:05.015   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 09:35:05.017   871  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 09:35:05.018   871  1312 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 09:35:05.061   871  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 09:35:05.061   871  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 09:35:05.063   871  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 09:35:05.065   871  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 09:35:05.067   871  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 09:35:05.078   871  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 09:35:05.086   871  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 09:35:05.086   871  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 09:35:05.087   871  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 09:35:05.088   871  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 09:35:05.088   871  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 09:35:05.088   871  1312 D ConnectivityService:    accepting network in place of null
,08-30 09:35:05.090   871  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 09:35:05.130   871  4086 D NetlinkSocketObserver: NeighborEvent{elapsedMs=183911, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 09:35:05.138   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:35:05.200   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:35:05.203   871  4085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 09:35:05.211   871  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 09:35:05.212   871  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:35:05.218   871   888 D Tethering: MasterInitialState.processMessage what=3
08-30 09:35:05.220   871  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 09:35:05.221  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:05.221  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:05.221  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:05.222  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:05.224  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:05.225  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:05.225  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:35:05.225  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:05.229  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:05.229  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:05.229  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:05.229  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:05.254  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 09:35:05.258  1727  1727 D SystemUpdateService: onCreate
,08-30 09:35:05.263  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 09:35:05.274   871  4085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 07:35:05 GMT], X-Android-Received-Millis=[1472542505274], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472542505243]}
,08-30 09:35:05.275   871  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 09:35:05.276   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 09:35:05.276   871  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 09:35:05.281   871  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 09:35:05.294  1727  4098 I SystemUpdateService: active receiver: enabled
,08-30 09:35:05.303  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 09:35:05.308  1727  2456 I iu.UploadsManager: num queued entries: 0
,08-30 09:35:05.308  1727  2456 I iu.UploadsManager: num updated entries: 0
,08-30 09:35:05.312  1727  4098 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 09:35:05.313  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 09:35:05.317  1727  4098 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 09:35:05.317  1727  4098 I SystemUpdateService: now status is 0 (complete)
,08-30 09:35:05.318  1727  4098 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 09:35:05.318  1727  4098 I SystemUpdateService: file has been verified
08-30 09:35:05.318  1727  4098 I SystemUpdateService: OTA package size = 12249756
,08-30 09:35:05.318  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 09:35:05.321  1727  2456 I iu.SyncManager: NEXT; no task
,08-30 09:35:05.324  3980  3980 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:35:05.329  1727  4102 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 09:35:05.329  1727  4102 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 09:35:05.332  1727  4102 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 09:35:05.346  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:35:05.349  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:35:05.355  3980  3980 D SprintDMHelper: simOperator: 
,08-30 09:35:05.355  3980  3980 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 09:35:05.406  1727  4098 I SystemUpdateService: showing system update notification
,08-30 09:35:05.452  1513  2463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 09:35:05.453  1513  2463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 09:35:05.453  1513  2463 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 09:35:05.453  1513  2463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 09:35:05.464  1727  1727 D SystemUpdateService: onDestroy
,08-30 09:35:05.499  1727  4102 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-30 09:35:05.514  2416  4105 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 09:35:05.976  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:35:06.027   871  1387 D WifiService: setWifiEnabled: false pid=3824, uid=10000
,08-30 09:35:06.027   871  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:35:06.055  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 09:35:06.056  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 09:35:06.057  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:35:06.057  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:35:06.065  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 09:35:06.076   871  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 09:35:06.076   871  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[],
,08-30 09:35:06.077   871  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 09:35:06.077   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:35:06.102   871  1310 E native  : do suspend true
,08-30 09:35:06.114  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 09:35:06.114  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 09:35:06.115  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-30 09:35:06.115   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:35:06.115   871  1885 D DhcpClient: Clearing IP address
,08-30 09:35:06.121   372   869 D CommandListener: Setting iface cfg
,08-30 09:35:06.123  1513  4110 V NativeCrypto: Read error: ssl=0x9a7da200: I/O error during system call, Connection timed out
08-30 09:35:06.126   871  4087 D DhcpClient: Receive thread stopped
,08-30 09:35:06.129   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 09:35:06.129   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 09:35:06.133   402   402 E Parcel  : Reading a NULL string not supported here.
,08-30 09:35:06.139  1513  4110 V NativeCrypto: SSL shutdown failed: ssl=0x9a7da200: I/O error during system call, Broken pipe
,08-30 09:35:06.140   871  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 09:35:06.143   871  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 09:35:06.142   871  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 09:35:06.144   871  1310 E native  : do suspend true
,08-30 09:35:06.177   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:35:06.204   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:35:06.205   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 09:35:06.205   871  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 09:35:06.205   871  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:35:06.207   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 09:35:06.212  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:06.212  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:06.212  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.213  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:06.214  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:06.214  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:06.214  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.214  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:06.215  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:06.215  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:06.215  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
08-30 09:35:06.216  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:06.217   871  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 09:35:06.240  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 09:35:06.240   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 09:35:06.243  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:06.243  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:06.243  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.243  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:06.245  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:06.246  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:06.246  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.246  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:06.247  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:06.247  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:06.247  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:06.247  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:06.249   871  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 09:35:06.250  1727  1727 D SystemUpdateService: onCreate
08-30 09:35:06.251  2025  2323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 09:35:06.255  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 09:35:06.269  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 09:35:06.271  1727  2456 I iu.UploadsManager: num queued entries: 0
08-30 09:35:06.277  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 09:35:06.279  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 09:35:06.283  3980  3980 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:35:06.287  1727  4120 I SystemUpdateService: active receiver: enabled
,08-30 09:35:06.288  1727  2456 I iu.UploadsManager: num updated entries: 0
08-30 09:35:06.288  3980  3980 D SprintDMHelper: simOperator: 
08-30 09:35:06.288  3980  3980 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 09:35:06.323   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-30 09:35:06.324  2416  4123 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 09:35:06.324   871  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 09:35:06.325   871  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 09:35:06.329  1727  4120 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 09:35:06.333  1727  2456 I iu.SyncManager: NEXT; no task
,08-30 09:35:06.334  1727  4120 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 09:35:06.334  1727  4120 I SystemUpdateService: now status is 0 (complete)
08-30 09:35:06.334  1727  4120 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 09:35:06.334  1727  4120 I SystemUpdateService: file has been verified
08-30 09:35:06.334  1727  4120 I SystemUpdateService: OTA package size = 12249756
,08-30 09:35:06.338  1727  4120 I SystemUpdateService: showing system update notification
,08-30 09:35:06.346  1727  1727 D SystemUpdateService: onDestroy
,08-30 09:35:06.432  1513  2091 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 09:35:11.075   871   888 I ActivityManager: Start proc 4128:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 09:35:11.204  4128  4128 D AdapterServiceConfig: Adding HeadsetService
,08-30 09:35:11.204  4128  4128 D AdapterServiceConfig: Adding A2dpService
08-30 09:35:11.204  4128  4128 D AdapterServiceConfig: Adding HidService
08-30 09:35:11.204  4128  4128 D AdapterServiceConfig: Adding HealthService
08-30 09:35:11.204  4128  4128 D AdapterServiceConfig: Adding PanService
08-30 09:35:11.205  4128  4128 D AdapterServiceConfig: Adding GattService
08-30 09:35:11.205  4128  4128 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 09:35:11.216  4128  4128 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 09:35:11.216   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@455c8be:true
,08-30 09:35:11.220  4128  4128 I bt_bluedroid: init
,08-30 09:35:11.221  4128  4140 I BluetoothAdapterState: Entering OffState
,08-30 09:35:11.223  4128  4141 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 09:35:11.223  4128  4141 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 09:35:11.223  4128  4141 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 09:35:11.223  4128  4141 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 09:35:11.224  4128  4128 I bt_bluedroid: get_profile_interface socket
,08-30 09:35:11.225  4128  4128 I bt_bluedroid: get_profile_interface sdp
08-30 09:35:11.226  4128  4144 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 09:35:11.227  4128  4144 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 09:35:11.228  4128  4139 I bt_bluedroid: config_hci_snoop_log
,08-30 09:35:11.230   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 09:35:11.234  4128  4140 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 09:35:11.235  4128  4140 D BluetoothAdapterProperties: Setting state to 14
,08-30 09:35:11.235  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 09:35:11.239  4128  4140 D BluetoothBondStateMachine: make
,08-30 09:35:11.242  4128  4145 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 09:35:11.250  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
08-30 09:35:11.251  4128  4128 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-30 09:35:11.255  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:11.256  4128  4128 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 09:35:11.256  4128  4128 D BtGatt.GattService: Received start request. Starting profile...
,08-30 09:35:11.256  4128  4128 D BtGatt.GattService: start()
08-30 09:35:11.256  4128  4128 I bt_bluedroid: get_profile_interface gatt
08-30 09:35:11.257  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:11.257  4128  4128 D BtGatt.AdvertiseManager: advertise manager created
,08-30 09:35:11.265  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-30 09:35:11.265  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-30 09:35:11.266  4128  4128 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 09:35:11.266  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:11.266  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 09:35:11.266  4128  4140 I bt_bluedroid: enable
08-30 09:35:11.266  4128  4141 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 09:35:11.267  4128  4141 I bt_hci  : start_up
,08-30 09:35:11.280  4128  4141 I bt_vendor: alloc value 0xb3a5c189
,08-30 09:35:11.280  4128  4141 I bt_vendor: init
08-30 09:35:11.280  4128  4141 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 09:35:11.281  4128  4141 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 09:35:11.391  4128  4141 D bt_hci  : start_up starting async portion
08-30 09:35:11.392  4128  4148 I bt_hci  : event_finish_startup
,08-30 09:35:11.393  4128  4148 I bt_hci_h4: hal_open
08-30 09:35:11.393  4128  4148 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 09:35:11.406  4128  4148 I bt_userial_vendor: device fd = 51 open
,08-30 09:35:11.433  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 09:35:11.464  4128  4148 D bt_hwcfg: Chipset BCM4354A2
08-30 09:35:11.465  4128  4148 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 09:35:11.465  4128  4148 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 09:35:12.135  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 09:35:12.137  4128  4148 D bt_hwcfg: Settlement delay -- 100 ms
08-30 09:35:12.137  4128  4148 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 09:35:12.254  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 09:35:12.255  4128  4148 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 09:35:12.284  4128  4148 I bt_hwcfg: vendor lib fwcfg completed
,08-30 09:35:12.284  4128  4148 I bt_vendor: firmware callback
,08-30 09:35:12.284  4128  4148 I bt_hci  : firmware_config_callback
,08-30 09:35:12.296  4128  4152 I bt_btu  : btu_task pending for preload complete event
08-30 09:35:12.296  4128  4152 I bt_btu_task: Bluetooth chip preload is complete
08-30 09:35:12.296  4128  4152 I bt_btu  : btu_task received preload complete event
,08-30 09:35:12.307  4128  4152 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 09:35:12.308  4128  4152 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 09:35:12.309  4128  4152 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 09:35:12.310  4128  4152 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 09:35:12.310  4128  4152 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 09:35:12.311  4128  4152 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 09:35:12.312  4128  4152 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 09:35:12.313  4128  4152 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 09:35:12.313  4128  4152 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 09:35:12.313  4128  4152 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 09:35:12.314  4128  4152 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 09:35:12.314  4128  4152 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 09:35:12.315  4128  4152 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 09:35:12.315  4128  4152 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 09:35:12.316  4128  4152 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 09:35:12.447  4128  4152 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,08-30 09:35:12.447  4128  4152 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,08-30 09:35:12.487  4128  4144 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 09:35:12.488  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 09:35:12.489  4128  4144 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 09:35:12.491  4128  4144 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 09:35:12.493  4128  4144 D BluetoothAdapterProperties: Scan Mode:20
,08-30 09:35:12.494  4128  4144 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 09:35:12.494  4128  4144 D bt_hci  : do_postload posting postload work item
,08-30 09:35:12.494  4128  4148 I bt_hci  : event_postload
08-30 09:35:12.494  4128  4148 I bt_vendor: sco_config_cb
,08-30 09:35:12.495  4128  4148 I bt_hci  : sco_config_callback postload finished.
08-30 09:35:12.497  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:12.497  4128  4144 D bt_bte_conf: Device ID record 1 : primary
08-30 09:35:12.498  4128  4144 D bt_bte_conf:   vendorId            = 000f
,08-30 09:35:12.498  4128  4144 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 09:35:12.498  4128  4144 D bt_bte_conf:   product             = 1200
08-30 09:35:12.498  4128  4144 D bt_bte_conf:   version             = 1436
08-30 09:35:12.499  4128  4144 D bt_bte_conf:   clientExecutableURL = 
,08-30 09:35:12.499  4128  4144 D bt_bte_conf:   serviceDescription  = 
08-30 09:35:12.499  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:12.499  4128  4144 D bt_bte_conf:   documentationURL    = 
,08-30 09:35:12.499  4128  4144 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 09:35:12.500  4128  4141 D bt_stack_manager: event_start_up_stack finished
08-30 09:35:12.501  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:12.501  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 09:35:12.502  4128  4148 I bt_vendor: low_power_mode_cb
,08-30 09:35:12.502  4128  4140 D BluetoothAdapterProperties: Setting state to 15
,08-30 09:35:12.502  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 09:35:12.503  4128  4140 I BluetoothAdapterState: Entering BleOnState
08-30 09:35:12.507  4128  4140 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 09:35:12.507  4128  4140 D BluetoothAdapterProperties: Setting state to 11
08-30 09:35:12.508  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 09:35:12.514  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:12.518  4128  4128 D HeadsetService: Received start request. Starting profile...
08-30 09:35:12.524  4128  4128 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 09:35:12.524  4128  4128 D HeadsetStateMachine: make
08-30 09:35:12.527  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:12.530  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:12.530  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
08-30 09:35:12.534  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:12.538  4128  4128 D HeadsetStateMachine: max_hf_connections = 1
,08-30 09:35:12.538  4128  4128 I bt_bluedroid: get_profile_interface handsfree
08-30 09:35:12.539  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 09:35:12.539  4128  4144 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 09:35:12.542  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:12.543  4128  4128 D A2dpService: Received start request. Starting profile...
,08-30 09:35:12.544  4128  4128 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 09:35:12.544  4128  4128 I bt_bluedroid: get_profile_interface avrcp
,08-30 09:35:12.552  4128  4128 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 09:35:12.552  4128  4128 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 09:35:12.552  4128  4128 D A2dpStateMachine: make
,08-30 09:35:12.553  4128  4128 I bt_bluedroid: get_profile_interface a2dp
,08-30 09:35:12.554  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 09:35:12.556  4128  4128 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 09:35:12.557  4128  4163 D A2dpStateMachine: Enter Disconnected: -2
08-30 09:35:12.557  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:12.559  4128  4128 D HidService: Received start request. Starting profile...
,08-30 09:35:12.559  4128  4128 I bt_bluedroid: get_profile_interface hidhost
08-30 09:35:12.559  4128  4128 D HidService: setHidService(): set to: null
08-30 09:35:12.559  4128  4144 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
08-30 09:35:12.559  3924  3924 D BluetoothInputDevice: Proxy object connected
08-30 09:35:12.559  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 09:35:12.560  4128  4128 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 09:35:12.560  3924  3924 D HidProfile: Bluetooth service connected
08-30 09:35:12.560  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:12.561  4128  4128 D HealthService: Received start request. Starting profile...
,08-30 09:35:12.563  4128  4128 I bt_bluedroid: get_profile_interface health
08-30 09:35:12.564  4128  4128 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 09:35:12.564  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:12.566  4128  4128 D PanService: Received start request. Starting profile...
08-30 09:35:12.566  4128  4128 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 09:35:12.566  4128  4128 I bt_bluedroid: get_profile_interface pan
08-30 09:35:12.566  3924  3924 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 09:35:12.567  4128  4144 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 09:35:12.567  3924  3924 D PanProfile: Bluetooth service connected
08-30 09:35:12.570  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:12.571  4128  4128 D BluetoothMapService: Received start request. Starting profile...
08-30 09:35:12.572  4128  4128 D BluetoothMapService: start()
,08-30 09:35:12.572  3924  3924 D BluetoothMap: Proxy object connected
08-30 09:35:12.573  3924  3924 D MapProfile: Bluetooth service connected
08-30 09:35:12.573  3924  3924 D BluetoothMap: getConnectedDevices()
08-30 09:35:12.574  3924  3924 D BluetoothMap: Bluetooth is Not enabled
,08-30 09:35:12.576  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 09:35:12.578  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 09:35:12.578  4128  4128 D BluetoothMapAppObserver: createReceiver()
,08-30 09:35:12.581  4128  4128 D BluetoothMapAppObserver: initObservers()
,08-30 09:35:12.582  4128  4128 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 09:35:12.605  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:12.605  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 09:35:12.605  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:12.605  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:12.605  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 09:35:12.609  4128  4159 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:12.609  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isTurningOn()=true
,08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:12.610  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:12.611  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:12.611  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 09:35:12.611  4128  4140 D BluetoothAdapterProperties: ScanMode =  20
,08-30 09:35:12.611  4128  4140 D BluetoothAdapterProperties: State =  11
08-30 09:35:12.611  4128  4140 D BluetoothAdapterProperties: Setting state to 12
08-30 09:35:12.611  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 09:35:12.612  4128  4140 I BluetoothAdapterState: Entering OnState
08-30 09:35:12.612  3924  3934 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 09:35:12.614  4128  4144 D BluetoothAdapterProperties: Scan Mode:21
08-30 09:35:12.614  4128  4144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 09:35:12.616  1366  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:12.617  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:12.617  3924  3935 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 09:35:12.617  1366  2047 D BluetoothMap: onBluetoothStateChange: up=true
08-30 09:35:12.620  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:12.621  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 09:35:12.622  4128  4128 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:12.626  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:12.626  1366  1366 D BluetoothMap: Proxy object connected
08-30 09:35:12.626  1366  1377 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 09:35:12.626  1366  1366 D MapProfile: Bluetooth service connected
08-30 09:35:12.627  1366  1366 D BluetoothMap: getConnectedDevices()
,08-30 09:35:12.628   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 09:35:12.629  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:35:12.629  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:12.629  1366  2047 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 09:35:12.631  3924  3934 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 09:35:12.632  1935  2075 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 09:35:12.632  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:35:12.632  1366  1385 D BluetoothPan: onBluetoothStateChange on: true
,08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:12.634  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:12.634  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 09:35:12.635  1366  1366 D PanProfile: Bluetooth service connected
08-30 09:35:12.635  4128  4128 D ObexServerSockets: Succeed to create listening sockets 
,08-30 09:35:12.635  4128  4128 D ObexServerSockets0: startAccept()
08-30 09:35:12.635  3924  3935 D BluetoothPan: onBluetoothStateChange on: true
08-30 09:35:12.635   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:12.635   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:12.635  4128  4128 D ObexServerSockets0: prepareForNewConnect()
08-30 09:35:12.636  1366  2047 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 09:35:12.636  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:12.638  1366  1366 D BluetoothInputDevice: Proxy object connected
08-30 09:35:12.638  1366  1366 D HidProfile: Bluetooth service connected
08-30 09:35:12.638   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:12.639  4128  4128 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 09:35:12.639  4128  4128 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 09:35:12.640   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 09:35:12.643  1366  1366 D BluetoothA2dp: Proxy object connected
08-30 09:35:12.643   871   871 D BluetoothA2dp: Proxy object connected
,08-30 09:35:12.645  4128  4168 D ObexServerSockets0: Accepting socket connection...
08-30 09:35:12.645  4128  4169 D ObexServerSockets0: Accepting socket connection...
08-30 09:35:12.649  4128  4128 D BluetoothMapService: onReceive
08-30 09:35:12.649  4128  4128 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:35:12.649  4128  4128 D BluetoothMapService: STATE_ON
08-30 09:35:12.649  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:12.650  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:12.651  3924  3924 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 09:35:12.652  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:12.656  3924  3924 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 09:35:12.662  3924  3924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 09:35:12.664  3924  3924 D BluetoothA2dp: Proxy object connected
,08-30 09:35:12.668  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 09:35:12.670  3924  3924 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:35:12.679  1366  1366 D BluetoothPbap: Proxy object connected
,08-30 09:35:12.679  1366  1366 D PbapServerProfile: Bluetooth service connected
08-30 09:35:12.679  3924  3924 D BluetoothPbap: Proxy object connected
,08-30 09:35:12.680  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 09:35:12.680  3924  3924 D PbapServerProfile: Bluetooth service connected
08-30 09:35:12.680  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-30 09:35:12.689  4128  4174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:35:12.702  4128  4178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:35:12.703  4128  4178 I BtOppRfcommListener: Accept thread started.
,08-30 09:35:12.718  1366  2047 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.718  1366  1366 D HeadsetProfile: Bluetooth service connected
08-30 09:35:12.718   871   871 D BluetoothHeadset: Proxy object connected
08-30 09:35:12.719  1935  2242 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.719   871   871 D BluetoothHeadset: Proxy object connected
08-30 09:35:12.719   871   871 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.732  1935  2367 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.736   871   888 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.736   871   888 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.739   871   888 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.760  3924  3935 D BluetoothHeadset: Proxy object connected
,08-30 09:35:12.766  3924  3924 D HeadsetProfile: Bluetooth service connected
,08-30 09:35:13.093   871  1312 D ConnectivityService: handlePromptUnvalidated 101
,08-30 09:35:16.044  4128  4140 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 09:35:16.044  4128  4140 D BluetoothAdapterProperties: Setting state to 13
08-30 09:35:16.044  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 09:35:16.046  4128  4140 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 09:35:16.053  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
,08-30 09:35:16.058  4128  4128 D BluetoothMapService: onReceive
,08-30 09:35:16.059  4128  4128 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 09:35:16.059  4128  4128 D BluetoothMapService: STATE_TURNING_OFF
,08-30 09:35:16.060  4128  4128 D BluetoothMapService: MAP Service closeService in
,08-30 09:35:16.060  4128  4128 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 09:35:16.061  4128  4128 D ObexServerSockets0: shutdown(block = true)
08-30 09:35:16.063  4128  4168 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 09:35:16.064  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:16.064  4128  4128 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:16.065  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:16.068  4128  4144 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:35:16.068  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:16.068  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:16.069  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 09:35:16.073  4128  4169 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 09:35:16.076  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:16.076  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:16.077  4128  4154 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 09:35:16.077  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:16.077  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:16.077  4128  4128 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 09:35:16.077  4128  4128 I BtOppRfcommListener: stopping Accept Thread
08-30 09:35:16.078  4128  4178 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 09:35:16.079  4128  4178 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 09:35:16.080  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:16.080  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:16.081  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 09:35:16.081  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:16.082  4128  4128 D HeadsetService: Received stop request...Stopping profile...
08-30 09:35:16.083  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.083  1366  1385 D BluetoothHeadset: Proxy object disconnected
08-30 09:35:16.084  1366  1366 D HeadsetProfile: Bluetooth service disconnected
,08-30 09:35:16.084   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 09:35:16.084  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.084  1935  1948 D BluetoothHeadset: Proxy object disconnected
08-30 09:35:16.084   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 09:35:16.084   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 09:35:16.085  3924  3934 D BluetoothHeadset: Proxy object disconnected
08-30 09:35:16.084  4128  4128 D A2dpService: Received stop request...Stopping profile...
08-30 09:35:16.085  4128  4163 D A2dpStateMachine: Exit Disconnected: -1
08-30 09:35:16.086  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:16.087   871   871 D BluetoothA2dp: Proxy object disconnected
08-30 09:35:16.087  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-30 09:35:16.088  4128  4128 D HidService: Received stop request...Stopping profile...
08-30 09:35:16.088  4128  4128 D HidService: Stopping Bluetooth HidService
08-30 09:35:16.088  3924  3924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 09:35:16.089  4128  4128 D HealthService: Received stop request...Stopping profile...
08-30 09:35:16.092  4128  4128 D PanService: Received stop request...Stopping profile...
,08-30 09:35:16.095  3924  3924 D HeadsetProfile: Bluetooth service disconnected
,08-30 09:35:16.095  3924  3924 D BluetoothA2dp: Proxy object disconnected
08-30 09:35:16.096  3924  3924 D BluetoothInputDevice: Proxy object disconnected
,08-30 09:35:16.096  3924  3924 D HidProfile: Bluetooth service disconnected
08-30 09:35:16.096  4128  4128 D BluetoothMapService: Received stop request...Stopping profile...
08-30 09:35:16.096  4128  4128 D BluetoothMapService: stop()
,08-30 09:35:16.097  4128  4128 D BluetoothMapAppObserver: deinitObservers()
,08-30 09:35:16.097  4128  4128 D BluetoothMapAppObserver: removeReceiver()
08-30 09:35:16.098  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-30 09:35:16.099  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-30 09:35:16.099  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:16.099  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:16.100  4128  4128 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 09:35:16.100  4128  4128 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 09:35:16.100  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 09:35:16.101  4128  4152 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:35:16.101  4128  4152 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:35:16.101  4128  4152 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 09:35:16.101  4128  4144 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 09:35:16.101  3924  3924 D DockEventReceiver: finishStartingService: stopping service
08-30 09:35:16.101  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-30 09:35:16.101  4128  4128 V BluetoothAdapterState: isTurningOn()=false
,08-30 09:35:16.101  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:16.101  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:16.103  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 09:35:16.103  4128  4152 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:35:16.103  4128  4128 V BluetoothAdapterState: isTurningOff()=true
,08-30 09:35:16.103  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-30 09:35:16.103  4128  4152 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:35:16.103  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:16.103  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:16.103  4128  4152 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:35:16.103  4128  4152 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 09:35:16.103  4128  4152 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 09:35:16.103  4128  4152 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 09:35:16.103  3924  3924 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 09:35:16.103  4128  4128 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 09:35:16.103  4128  4128 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 09:35:16.103  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 09:35:16.104  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-30 09:35:16.104  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-30 09:35:16.104  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:16.104  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:16.104  4128  4128 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 09:35:16.104  4128  4144 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 09:35:16.105  4128  4128 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 09:35:16.105  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-30 09:35:16.105  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-30 09:35:16.105  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:16.105  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:16.107  4128  4128 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 09:35:16.107  4128  4128 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 09:35:16.108  4128  4128 D BluetoothMapService: MAP Service closeService in
,08-30 09:35:16.108  4128  4128 V BluetoothAdapterState: isTurningOff()=true
,08-30 09:35:16.108  4128  4128 V BluetoothAdapterState: isTurningOn()=false
,08-30 09:35:16.108  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 09:35:16.108  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:16.109  4128  4128 D BluetoothMapService: cleanup()
08-30 09:35:16.109  4128  4128 D BluetoothMapService: MAP Service closeService in
,08-30 09:35:16.109  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 09:35:16.109  4128  4140 D BluetoothAdapterProperties: Setting state to 15
08-30 09:35:16.109  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 09:35:16.110  4128  4140 I BluetoothAdapterState: Entering BleOnState
08-30 09:35:16.112  3924  3935 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 09:35:16.113  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-30 09:35:16.113  1366  1366 D HidProfile: Bluetooth service disconnected
08-30 09:35:16.113  1366  2047 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:35:16.113  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 09:35:16.113  1366  1366 D PanProfile: Bluetooth service disconnected
08-30 09:35:16.114  3924  3934 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 09:35:16.114  3924  3935 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 09:35:16.114  1366  1366 D BluetoothMap: Proxy object disconnected
08-30 09:35:16.115  1366  1366 D MapProfile: Bluetooth service disconnected
08-30 09:35:16.115  1366  1377 D BluetoothMap: onBluetoothStateChange: up=false
08-30 09:35:16.116  1366  1366 D BluetoothPbap: Proxy object disconnected
08-30 09:35:16.116  1366  1366 D PbapServerProfile: Bluetooth service disconnected
,08-30 09:35:16.116  1366  2047 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 09:35:16.116  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:35:16.116   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 09:35:16.104  3924  3924 D PanProfile: Bluetooth service disconnected
08-30 09:35:16.117  3924  3924 D BluetoothMap: Proxy object disconnected
08-30 09:35:16.117  3924  3924 D MapProfile: Bluetooth service disconnected
08-30 09:35:16.118  3924  3935 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 09:35:16.119  1366  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 09:35:16.121  3924  3934 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 09:35:16.123  1935  1947 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 09:35:16.123  1366  1377 D BluetoothPan: onBluetoothStateChange on: false
08-30 09:35:16.125  3924  3935 D BluetoothPan: onBluetoothStateChange on: false
,08-30 09:35:16.125   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:35:16.125   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:35:16.125  1366  2047 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 09:35:16.126   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 09:35:16.126  4128  4140 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 09:35:16.126  4128  4140 D BluetoothAdapterProperties: Setting state to 16
08-30 09:35:16.126  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 09:35:16.129  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.130  4128  4140 D BluetoothAdapterProperties: onBleDisable
08-30 09:35:16.131  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:16.131  3924  3924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 09:35:16.132  4128  4141 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 09:35:16.133  4128  4152 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 09:35:16.133  4128  4152 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 09:35:16.133  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
08-30 09:35:16.134  4128  4144 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:35:16.134  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.136  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.138  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.139  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:35:16.140  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:16.147  3924  3924 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:35:16.336  4128  4144 I bt_hci  : shut_down
,08-30 09:35:16.337  4128  4148 D bt_hwcfg: hw_epilog_process
08-30 09:35:16.339  4128  4148 I bt_vendor: low_power_mode_cb
,08-30 09:35:16.366  4128  4148 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 09:35:16.366  4128  4148 I bt_vendor: epilog_cb
,08-30 09:35:16.367  4128  4148 I bt_hci  : epilog_finished_callback
,08-30 09:35:16.388  4128  4144 I bt_hci_h4: hal_close
08-30 09:35:16.390  4128  4144 I bt_userial_vendor: device fd = 51 close
,08-30 09:35:16.528  4128  4141 D bt_stack_manager: event_shut_down_stack finished.
,08-30 09:35:16.529  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 09:35:16.535  4128  4128 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 09:35:16.536  4128  4140 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 09:35:16.537  4128  4128 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 09:35:16.537  4128  4128 D BtGatt.GattService: stop()
,08-30 09:35:16.538  4128  4128 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 09:35:16.544  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:16.545  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-30 09:35:16.545  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:16.545  4128  4128 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 09:35:16.547  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 09:35:16.547  4128  4140 D BluetoothAdapterProperties: Setting state to 10
08-30 09:35:16.548  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 09:35:16.549  4128  4140 I BluetoothAdapterState: Entering OffState
,08-30 09:35:16.551   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 09:35:16.575  4128  4128 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 09:35:16.576  4128  4128 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 09:35:16.576  4128  4141 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 09:35:16.580  4128  4128 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 09:35:16.590  4128  4141 D bt_stack_manager: event_clean_up_stack finished.
,08-30 09:35:16.592  4128  4128 I art     : System.exit called, status: 0
,08-30 09:35:16.592  4128  4128 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 09:35:16.655   871  1980 I ActivityManager: Process com.android.bluetooth (pid 4128) has died
,08-30 09:35:21.041  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:35:21.041  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:21.048  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:35:21.049  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@161435e removed from the list
,08-30 09:35:21.049  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:21.049  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:21.050  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:21.057  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 09:35:21.057  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c3440c added. We now have 4 listener(s)
,08-30 09:35:21.058  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:35:21.060  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:35:21.060  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c3440c removed from the list
08-30 09:35:21.060  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:21.061  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:21.061  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:21.061  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 09:35:21.061  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327d155 added. We now have 4 listener(s)
08-30 09:35:21.061  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:35:26.072  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:26.125   871   888 I ActivityManager: Start proc 4189:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 09:35:26.274  4189  4189 D AdapterServiceConfig: Adding HeadsetService
08-30 09:35:26.275  4189  4189 D AdapterServiceConfig: Adding A2dpService
,08-30 09:35:26.275  4189  4189 D AdapterServiceConfig: Adding HidService
08-30 09:35:26.276  4189  4189 D AdapterServiceConfig: Adding HealthService
,08-30 09:35:26.276  4189  4189 D AdapterServiceConfig: Adding PanService
08-30 09:35:26.276  4189  4189 D AdapterServiceConfig: Adding GattService
08-30 09:35:26.276  4189  4189 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 09:35:26.292   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@414df83:true
08-30 09:35:26.292  4189  4189 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 09:35:26.299  4189  4189 I bt_bluedroid: init
08-30 09:35:26.299  4189  4201 I BluetoothAdapterState: Entering OffState
,08-30 09:35:26.305  4189  4202 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 09:35:26.306  4189  4202 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 09:35:26.306  4189  4202 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 09:35:26.307  4189  4202 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 09:35:26.309  4189  4189 I bt_bluedroid: get_profile_interface socket
,08-30 09:35:26.312  4189  4205 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 09:35:26.313  4189  4205 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 09:35:26.314  4189  4189 I bt_bluedroid: get_profile_interface sdp
,08-30 09:35:26.321  4189  4200 I bt_bluedroid: config_hci_snoop_log
,08-30 09:35:26.325   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 09:35:26.339  4189  4201 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 09:35:26.340  4189  4201 D BluetoothAdapterProperties: Setting state to 14
08-30 09:35:26.341  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 09:35:26.346  4189  4201 D BluetoothBondStateMachine: make
,08-30 09:35:26.352  4189  4206 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 09:35:26.361  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
,08-30 09:35:26.362  4189  4189 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-30 09:35:26.367  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:26.368  4189  4189 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 09:35:26.370  4189  4189 D BtGatt.GattService: Received start request. Starting profile...
08-30 09:35:26.370  4189  4189 D BtGatt.GattService: start()
08-30 09:35:26.370  4189  4189 I bt_bluedroid: get_profile_interface gatt
,08-30 09:35:26.372  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:26.372  4189  4189 D BtGatt.AdvertiseManager: advertise manager created
,08-30 09:35:26.389  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:26.389  4189  4189 V BluetoothAdapterState: isTurningOn()=false
,08-30 09:35:26.389  4189  4189 V BluetoothAdapterState: isBleTurningOn()=true
08-30 09:35:26.390  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:26.391  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 09:35:26.392  4189  4201 I bt_bluedroid: enable
08-30 09:35:26.392  4189  4202 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 09:35:26.393  4189  4202 I bt_hci  : start_up
,08-30 09:35:26.413  4189  4202 I bt_vendor: alloc value 0xb3a5c189
08-30 09:35:26.413  4189  4202 I bt_vendor: init
,08-30 09:35:26.414  4189  4202 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 09:35:26.414  4189  4202 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 09:35:26.525  4189  4202 D bt_hci  : start_up starting async portion
,08-30 09:35:26.526  4189  4209 I bt_hci  : event_finish_startup
08-30 09:35:26.526  4189  4209 I bt_hci_h4: hal_open
08-30 09:35:26.526  4189  4209 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 09:35:26.534  4189  4209 I bt_userial_vendor: device fd = 51 open
,08-30 09:35:26.568  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 09:35:26.599  4189  4209 D bt_hwcfg: Chipset BCM4354A2
,08-30 09:35:26.599  4189  4209 D bt_hwcfg: Target name = [BCM4354A2]
08-30 09:35:26.600  4189  4209 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 09:35:27.474  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 09:35:27.475  4189  4209 D bt_hwcfg: Settlement delay -- 100 ms
08-30 09:35:27.476  4189  4209 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 09:35:27.594  4189  4209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 09:35:27.595  4189  4209 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 09:35:27.622  4189  4209 I bt_hwcfg: vendor lib fwcfg completed
,08-30 09:35:27.623  4189  4209 I bt_vendor: firmware callback
08-30 09:35:27.623  4189  4209 I bt_hci  : firmware_config_callback
,08-30 09:35:27.636  4189  4211 I bt_btu  : btu_task pending for preload complete event
,08-30 09:35:27.637  4189  4211 I bt_btu_task: Bluetooth chip preload is complete
08-30 09:35:27.637  4189  4211 I bt_btu  : btu_task received preload complete event
,08-30 09:35:27.649  4189  4211 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 09:35:27.649  4189  4211 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 09:35:27.649  4189  4211 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 09:35:27.650  4189  4211 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 09:35:27.650  4189  4211 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 09:35:27.650  4189  4211 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 09:35:27.650  4189  4211 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 09:35:27.651  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 09:35:27.651  4189  4211 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 09:35:27.651  4189  4211 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 09:35:27.651  4189  4211 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 09:35:27.652  4189  4211 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 09:35:27.652  4189  4211 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 09:35:27.653  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 09:35:27.653  4189  4211 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 09:35:27.789  4189  4211 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
08-30 09:35:27.789  4189  4211 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,08-30 09:35:27.817  4189  4205 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 09:35:27.819  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 09:35:27.820  4189  4205 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 09:35:27.822  4189  4205 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 09:35:27.824  4189  4205 D BluetoothAdapterProperties: Scan Mode:20
08-30 09:35:27.824  4189  4205 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 09:35:27.824  4189  4205 D bt_hci  : do_postload posting postload work item
,08-30 09:35:27.824  4189  4209 I bt_hci  : event_postload
08-30 09:35:27.824  4189  4209 I bt_vendor: sco_config_cb
08-30 09:35:27.825  4189  4209 I bt_hci  : sco_config_callback postload finished.
08-30 09:35:27.825  4189  4205 D bt_bte_conf: Device ID record 1 : primary
,08-30 09:35:27.826  4189  4205 D bt_bte_conf:   vendorId            = 000f
08-30 09:35:27.826  4189  4205 D bt_bte_conf:   vendorIdSource      = 0001
08-30 09:35:27.826  4189  4205 D bt_bte_conf:   product             = 1200
08-30 09:35:27.826  4189  4205 D bt_bte_conf:   version             = 1436
08-30 09:35:27.826  4189  4205 D bt_bte_conf:   clientExecutableURL = 
,08-30 09:35:27.826  4189  4205 D bt_bte_conf:   serviceDescription  = 
08-30 09:35:27.826  4189  4205 D bt_bte_conf:   documentationURL    = 
08-30 09:35:27.826  4189  4205 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 09:35:27.827  4189  4202 D bt_stack_manager: event_start_up_stack finished
08-30 09:35:27.827  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 09:35:27.827  4189  4201 D BluetoothAdapterProperties: Setting state to 15
08-30 09:35:27.827  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 09:35:27.828  4189  4201 I BluetoothAdapterState: Entering BleOnState
08-30 09:35:27.829  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:27.834  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:27.835  4189  4209 I bt_vendor: low_power_mode_cb
,08-30 09:35:27.835  4189  4201 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 09:35:27.836  4189  4201 D BluetoothAdapterProperties: Setting state to 11
08-30 09:35:27.836  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 09:35:27.850  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:27.849  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:27.852  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:27.852  4189  4189 D HeadsetService: Received start request. Starting profile...
,08-30 09:35:27.857  4189  4189 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 09:35:27.857  4189  4189 D HeadsetStateMachine: make
,08-30 09:35:27.862  4189  4201 I BluetoothAdapterState: Entering PendingCommandState
,08-30 09:35:27.868  4189  4189 D HeadsetStateMachine: max_hf_connections = 1
08-30 09:35:27.868  4189  4189 I bt_bluedroid: get_profile_interface handsfree
,08-30 09:35:27.868  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 09:35:27.868  4189  4205 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 09:35:27.872  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:27.873  4189  4189 D A2dpService: Received start request. Starting profile...
,08-30 09:35:27.873  4189  4189 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 09:35:27.874  4189  4189 I bt_bluedroid: get_profile_interface avrcp
,08-30 09:35:27.880  4189  4189 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 09:35:27.881  4189  4189 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 09:35:27.881  4189  4189 D A2dpStateMachine: make
,08-30 09:35:27.883  4189  4189 I bt_bluedroid: get_profile_interface a2dp
,08-30 09:35:27.884  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 09:35:27.887  4189  4220 D A2dpStateMachine: Enter Disconnected: -2
,08-30 09:35:27.889  4189  4189 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 09:35:27.890  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 09:35:27.891  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:27.892  4189  4189 D HidService: Received start request. Starting profile...
,08-30 09:35:27.892  4189  4189 I bt_bluedroid: get_profile_interface hidhost
08-30 09:35:27.892  4189  4189 D HidService: setHidService(): set to: null
08-30 09:35:27.892  4189  4205 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
08-30 09:35:27.892  4189  4205 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 09:35:27.893  4189  4189 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 09:35:27.894  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:27.894  4189  4189 D HealthService: Received start request. Starting profile...
,08-30 09:35:27.896  4189  4189 I bt_bluedroid: get_profile_interface health
,08-30 09:35:27.897  4189  4189 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 09:35:27.897  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:27.898  4189  4189 D PanService: Received start request. Starting profile...
08-30 09:35:27.898  4189  4189 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 09:35:27.898  4189  4189 I bt_bluedroid: get_profile_interface pan
08-30 09:35:27.899  4189  4205 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 09:35:27.901  4189  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
08-30 09:35:27.902  4189  4189 D BluetoothMapService: Received start request. Starting profile...
08-30 09:35:27.902  4189  4189 D BluetoothMapService: start()
,08-30 09:35:27.905  4189  4189 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 09:35:27.906  4189  4189 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 09:35:27.906  4189  4189 D BluetoothMapAppObserver: createReceiver()
,08-30 09:35:27.907  4189  4189 D BluetoothMapAppObserver: initObservers()
08-30 09:35:27.908  4189  4189 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 09:35:27.918  4189  4189 V BluetoothAdapterState: isTurningOff()=false
,08-30 09:35:27.918  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:27.918  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:27.918  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:27.920  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:27.920  4189  4189 V BluetoothAdapterState: isTurningOn()=true
,08-30 09:35:27.920  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:27.920  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:27.921  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:27.921  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:27.921  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:27.921  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:27.921  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isTurningOn()=true
,08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isTurningOff()=false
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isTurningOn()=true
08-30 09:35:27.922  4189  4189 V BluetoothAdapterState: isBleTurningOn()=false
08-30 09:35:27.923  4189  4189 V BluetoothAdapterState: isBleTurningOff()=false
08-30 09:35:27.923  4189  4218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 09:35:27.923  4189  4201 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 09:35:27.923  4189  4201 D BluetoothAdapterProperties: ScanMode =  20
08-30 09:35:27.924  4189  4201 D BluetoothAdapterProperties: State =  11
,08-30 09:35:27.924  4189  4201 D BluetoothAdapterProperties: Setting state to 12
08-30 09:35:27.924  4189  4201 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 09:35:27.924  4189  4201 I BluetoothAdapterState: Entering OnState
08-30 09:35:27.925  3924  3934 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 09:35:27.928  4189  4205 D BluetoothAdapterProperties: Scan Mode:21
,08-30 09:35:27.928  4189  4205 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 09:35:27.929  1366  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:27.929  3924  3935 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 09:35:27.931  3924  3934 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 09:35:27.932  1366  2047 D BluetoothMap: onBluetoothStateChange: up=true
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:27.933  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:27.934  1366  1385 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 09:35:27.935  1366  1366 D BluetoothMap: Proxy object connected
08-30 09:35:27.935  1366  1366 D MapProfile: Bluetooth service connected
08-30 09:35:27.935  1366  1366 D BluetoothMap: getConnectedDevices()
08-30 09:35:27.935  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:27.936  4189  4189 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 09:35:27.936   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 09:35:27.936   871   871 D BluetoothA2dp: Proxy object connected
08-30 09:35:27.936  4189  4189 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 09:35:27.937  3924  3935 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:27.938  1366  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 09:35:27.938  4189  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:27.939  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 09:35:27.939  1366  1366 D BluetoothA2dp: Proxy object connected
08-30 09:35:27.940  3924  3934 D BluetoothMap: onBluetoothStateChange: up=true
08-30 09:35:27.940  4189  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:35:27.941  1935  2242 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:27.941  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 09:35:27.942  4189  4189 D ObexServerSockets: Succeed to create listening sockets 
08-30 09:35:27.942  4189  4189 D ObexServerSockets0: startAccept()
08-30 09:35:27.942  1366  1385 D BluetoothPan: onBluetoothStateChange on: true
08-30 09:35:27.942  4189  4189 D ObexServerSockets0: prepareForNewConnect()
08-30 09:35:27.943  3924  3935 D BluetoothPan: onBluetoothStateChange on: true
08-30 09:35:27.944  3924  3924 D BluetoothInputDevice: Proxy object connected
08-30 09:35:27.944  4189  4189 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 09:35:27.944  3924  3924 D HidProfile: Bluetooth service connected
08-30 09:35:27.944  4189  4189 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 09:35:27.944  4189  4228 D ObexServerSockets0: Accepting socket connection...
08-30 09:35:27.945  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 09:35:27.945  1366  1366 D PanProfile: Bluetooth service connected
,08-30 09:35:27.945   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:27.945   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:27.945  4189  4227 D ObexServerSockets0: Accepting socket connection...
08-30 09:35:27.945  1366  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 09:35:27.946   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 09:35:27.947  1366  1366 D BluetoothInputDevice: Proxy object connected
08-30 09:35:27.947  1366  1366 D HidProfile: Bluetooth service connected
08-30 09:35:27.947   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 09:35:27.948  4189  4189 D BluetoothMapService: onReceive
08-30 09:35:27.948  4189  4189 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 09:35:27.948  4189  4189 D BluetoothMapService: STATE_ON
08-30 09:35:27.950  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:27.950  3924  3924 D BluetoothA2dp: Proxy object connected
08-30 09:35:27.951  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:27.952  3924  3924 D BluetoothMap: Proxy object connected
08-30 09:35:27.952  3924  3924 D MapProfile: Bluetooth service connected
08-30 09:35:27.952  3924  3924 D BluetoothMap: getConnectedDevices()
08-30 09:35:27.953  3924  3924 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 09:35:27.953  3924  3924 D PanProfile: Bluetooth service connected
08-30 09:35:27.957  3924  3924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 09:35:27.967  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 09:35:27.968  3924  3924 D DockEventReceiver: finishStartingService: stopping service
,08-30 09:35:27.969  4189  4189 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 09:35:27.969  4189  4189 D ObexServerSockets0: prepareForNewConnect()
08-30 09:35:27.969  4189  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 09:35:27.971  3924  3924 D BluetoothPbap: Proxy object connected
08-30 09:35:27.971  3924  3924 D PbapServerProfile: Bluetooth service connected
,08-30 09:35:27.974  1366  1366 D BluetoothPbap: Proxy object connected
,08-30 09:35:27.974  1366  1366 D PbapServerProfile: Bluetooth service connected
,08-30 09:35:27.994  4189  4237 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:35:27.995  4189  4237 I BtOppRfcommListener: Accept thread started.
,08-30 09:35:28.031  1366  2047 D BluetoothHeadset: Proxy object connected
,08-30 09:35:28.031   871   871 D BluetoothHeadset: Proxy object connected
08-30 09:35:28.031  1366  1366 D HeadsetProfile: Bluetooth service connected
08-30 09:35:28.031  1935  2367 D BluetoothHeadset: Proxy object connected
08-30 09:35:28.032   871   871 D BluetoothHeadset: Proxy object connected
08-30 09:35:28.032   871   871 D BluetoothHeadset: Proxy object connected
08-30 09:35:28.032  3924  3935 D BluetoothHeadset: Proxy object connected
08-30 09:35:28.033  3924  3924 D HeadsetProfile: Bluetooth service connected
,08-30 09:35:28.038  3924  4182 D BluetoothHeadset: Proxy object connected
,08-30 09:35:28.038  3924  3924 D HeadsetProfile: Bluetooth service connected
,08-30 09:35:28.042  1935  1948 D BluetoothHeadset: Proxy object connected
,08-30 09:35:28.044   871   888 D BluetoothHeadset: Proxy object connected
,08-30 09:35:28.045   871   888 D BluetoothHeadset: Proxy object connected
,08-30 09:35:28.047   871   888 D BluetoothHeadset: Proxy object connected
,08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:31.094  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:31.100  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:31.102  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:35:31.102  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327d155 removed from the list
,08-30 09:35:31.103  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:35:31.103  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:31.103  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:31.106  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:31.106  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67a376a added. We now have 4 listener(s)
,08-30 09:35:31.107  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:35:31.111   871  1985 D WifiService: setWifiEnabled: false pid=3824, uid=10000
,08-30 09:35:31.111   871  1985 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:35:31.432  1871  1972 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 09:35:31.433  1871  1972 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 09:35:31.470  1513  1513 I ConfigService: onCreate
,08-30 09:35:36.126  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:36.127   871  1980 D WifiService: setWifiEnabled: true pid=3824, uid=10000
08-30 09:35:36.127   871  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 09:35:36.142   871  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:36.159  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:36.162  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 09:35:36.167  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 09:35:36.169  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 09:35:36.177   871  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-30 09:35:36.178   871  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 09:35:36.179   871  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 09:35:36.181   871  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 09:35:36.181   871  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 09:35:36.181   871  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 09:35:36.181   871  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 09:35:36.195   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 09:35:36.196   372   869 D CommandListener: Setting iface cfg
08-30 09:35:36.196   871  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 09:35:36.197   871  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-30 09:35:36.197   871  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 09:35:36.254   871  1310 E native  : do suspend true
,08-30 09:35:36.255   871  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 09:35:36.256   871  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 09:35:36.325   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 09:35:36.545  1513  1513 I ConfigService: onDestroy
,08-30 09:35:37.704   871  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 09:35:37.841   871  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.38 rxSuccessRate=7.56 delta 1000 -> 994
,08-30 09:35:37.844   871  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 09:35:37.844   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:35:37.864   871  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 09:35:37.916   871  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 09:35:37.921  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 09:35:38.431  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 09:35:38.484  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 09:35:38.485  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-30 09:35:38.491   871  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 09:35:38.504   871  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 09:35:38.504   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 09:35:38.505   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:35:38.534   871  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 09:35:38.552   372   869 D CommandListener: Setting iface cfg
,08-30 09:35:38.554   871  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 09:35:38.571   871  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 09:35:38.579   871  4247 D DhcpClient: Receive thread started
,08-30 09:35:38.678   871  1310 E native  : do suspend false
,08-30 09:35:38.708   871  1885 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 09:35:38.723   871  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172766, domain null
,08-30 09:35:38.725   871  1885 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172766 seconds
,08-30 09:35:38.728   871  1885 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 09:35:38.749   871  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 09:35:38.751   871  1885 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 09:35:38.756   372   869 D CommandListener: Setting iface cfg
,08-30 09:35:38.768   871  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-30 09:35:38.769   871  1885 D DhcpClient: Scheduling renewal in 86399s
,08-30 09:35:38.771   871  1310 E native  : do suspend true
,08-30 09:35:38.801   871  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 09:35:38.804   871  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 09:35:38.806   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 09:35:38.809   871  1312 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 09:35:38.819   871  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 09:35:38.859   871  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 09:35:38.860   871  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 09:35:38.861   871  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 09:35:38.863   871  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 09:35:38.865   871  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 09:35:38.873   871  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 09:35:38.883   871  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-30 09:35:38.883   871  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 09:35:38.883   871  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 09:35:38.883   871  1312 D ConnectivityService:    accepting network in place of null
08-30 09:35:38.883   871  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 09:35:38.884   871  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 09:35:38.885   871  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 09:35:38.914   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:35:38.946   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 09:35:38.947   871  4246 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217728, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 09:35:38.953   871  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 09:35:38.955   871  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:35:38.964   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 09:35:38.963   871  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:38.987  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:38.991  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:38.992  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:38.996  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 09:35:38.997  1727  1727 D SystemUpdateService: onCreate
,08-30 09:35:39.000  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:39.001  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 09:35:39.013   871  4245 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 09:35:39.024  1727  4256 I SystemUpdateService: active receiver: enabled
,08-30 09:35:39.026  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 09:35:39.033  1727  2456 I iu.UploadsManager: num queued entries: 0
,08-30 09:35:39.033  1727  2456 I iu.UploadsManager: num updated entries: 0
08-30 09:35:39.034  1727  2456 I iu.SyncManager: NEXT; no task
,08-30 09:35:39.038  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 09:35:39.040  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 09:35:39.042  3980  3980 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 09:35:39.046  1727  4258 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-30 09:35:39.046  1727  4258 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 09:35:39.048  1727  4258 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 09:35:39.050  3980  3980 D SprintDMHelper: simOperator: 
,08-30 09:35:39.050  3980  3980 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 09:35:39.053  1727  4256 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 09:35:39.062  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:35:39.067  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 09:35:39.069  1727  4256 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 09:35:39.069  1727  4256 I SystemUpdateService: now status is 0 (complete)
08-30 09:35:39.069  1727  4256 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 09:35:39.069  1727  4256 I SystemUpdateService: file has been verified
08-30 09:35:39.069  1727  4256 I SystemUpdateService: OTA package size = 12249756
,08-30 09:35:39.086   871  4245 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 07:35:39 GMT], X-Android-Received-Millis=[1472542539085], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472542539055]}
,08-30 09:35:39.086  1727  4256 I SystemUpdateService: showing system update notification
,08-30 09:35:39.099   871  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 09:35:39.100   871  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-30 09:35:39.101   871  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 09:35:39.105   871  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 09:35:39.131  1727  1727 D SystemUpdateService: onDestroy
,08-30 09:35:39.137  1513  3080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 09:35:39.137  1513  3080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 09:35:39.138  1513  3080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 09:35:39.138  1513  3080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 09:35:39.151  1727  4258 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-30 09:35:39.206  2416  4261 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:41.153  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:41.160  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:41.161  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:35:41.161  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67a376a removed from the list
,08-30 09:35:41.162  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:41.162  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:41.163  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:41.177  3824  4268 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-30 09:35:41.178  3824  4268 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 09:35:44.185  3824  4269 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 09:35:44.186  3824  4268 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 09:35:44.187  3824  4269 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 09:35:44.187  3824  4268 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 09:35:44.188  3824  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:35:44.188  3824  4268 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:35:44.189  3824  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:35:44.189  3824  4268 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:35:44.195  3824  4268 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 09:35:44.194  3824  4271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
08-30 09:35:44.195  3824  4269 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 09:35:44.199  3824  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Sender)
,08-30 09:35:44.202  3824  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
,08-30 09:35:44.204  3824  4273 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
,08-30 09:35:44.204  3824  4273 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 09:35:44.204  3824  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Receiver)
08-30 09:35:44.205  3824  4273 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 09:35:44.205  3824  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: OutgoingSocketThread/Receiver)
,08-30 09:35:44.206  3824  4274 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 09:35:44.206  3824  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 09:35:46.891   871  1312 D ConnectivityService: handlePromptUnvalidated 102
,08-30 09:35:47.184  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 09:35:47.187  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 09:35:47.196  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@26b4433 Bundle[{}]
,08-30 09:35:47.198  3824  3874 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 09:35:47.199  3824  3874 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 09:35:47.202  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 09:35:47.207  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 09:35:47.209  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 09:35:47.211  3824  3874 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 09:35:47.224  3824  3874 I System.out: Running OutgoingSocketThread
,08-30 09:35:47.227  3824  4275 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 09:35:47.227  3824  4275 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 09:35:50.237  3824  4276 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 09:35:50.237  3824  4276 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 09:35:50.238  3824  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:35:50.238  3824  4275 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 09:35:50.239  3824  4275 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 09:35:50.239  3824  4276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 09:35:50.239  3824  4275 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:35:50.242  3824  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Sender)
08-30 09:35:50.246  3824  4276 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 09:35:50.250  3824  4275 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:35:50.253  3824  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Sender)
,08-30 09:35:50.256  3824  4275 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 09:35:50.258  3824  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Receiver)
,08-30 09:35:50.260  3824  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: IncomingSocketThread/Receiver)
08-30 09:35:50.260  3824  4279 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 09:35:50.261  3824  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 09:35:50.260  3824  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: OutgoingSocketThread/Receiver)
08-30 09:35:50.263  3824  4281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: OutgoingSocketThread/Receiver)
08-30 09:35:50.263  3824  4281 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 09:35:50.264  3824  4281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 09:35:53.240  3824  3874 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,08-30 09:35:53.242  3824  3874 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 09:35:53.243  3824  3874 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,08-30 09:35:53.248  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:35:53.248  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8145b added. We now have 3 listener(s)
,08-30 09:35:53.250  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:35:53.250  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:53.250  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:35:53.251  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:53.251  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66694f8 added. We now have 4 listener(s)
08-30 09:35:53.251  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:35:53.251  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 09:35:53.256  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:53.269  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:53.273  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:53.273  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:53.274  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:35:53.274  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:35:53.274  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 09:35:53.274  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:53.274  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:53.274  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:53.274  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 09:35:53.274  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8145b removed from the list
08-30 09:35:53.274  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:53.274  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66694f8 removed from the list
,08-30 09:35:53.282  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:53.286  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:53.287  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:53.287  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:53.287  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:53.287  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:53.290  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:35:53.290  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:53.290  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:53.290  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66694f8 not in the list
08-30 09:35:53.290  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:53.290  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:53.292  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:53.292  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:53.292  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:53.292  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66694f8 not in the list
,08-30 09:35:53.292  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:53.292  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:53.293  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:53.293  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8145b not in the list
,08-30 09:35:53.293  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 09:35:53.293  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c6036 added. We now have 3 listener(s)
,08-30 09:35:53.295  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:35:53.295  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:53.295  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 09:35:53.296  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:53.296  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b37 added. We now have 4 listener(s)
08-30 09:35:53.296  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:35:53.296  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 09:35:53.299  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:53.312  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:53.315  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:53.315  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:53.315  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 09:35:53.315  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 09:35:53.315  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:35:53.315  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:53.315  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 09:35:53.319  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:53.333  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 09:35:53.333  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:53.333  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 09:35:53.341  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 09:35:53.342  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 09:35:53.342  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 09:35:53.351  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 09:35:53.352  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 09:35:53.352  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 09:35:53.354  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:35:53.360  4189  4216 D BtGatt.GattService: registerClient() - UUID=e445c88b-83e2-476f-ad1b-f6bbb22490f5
08-30 09:35:53.361  4189  4205 D BtGatt.GattService: onClientRegistered() - UUID=e445c88b-83e2-476f-ad1b-f6bbb22490f5, clientIf=5
,08-30 09:35:53.362  3824  3834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 09:35:53.364  4189  4225 D BtGatt.GattService: start scan with filters
,08-30 09:35:53.368  4189  4208 D BtGatt.ScanManager: handling starting scan
08-30 09:35:53.368  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 09:35:53.369  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 09:35:53.369  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 09:35:53.369  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 09:35:53.371  4189  4208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26b4433
,08-30 09:35:53.377  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 09:35:53.378  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 09:35:53.379  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 09:35:53.381  4189  4205 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 09:35:53.382  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:53.382  4189  4208 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 09:35:53.383  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-30 09:35:53.392  3824  3874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 09:35:53.392  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:35:53.393  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 09:35:53.393  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:53.394  4189  4208 D BtGatt.ScanManager: Starting BLE batch scan
08-30 09:35:53.394  4189  4208 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 09:35:53.392  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 09:35:53.395  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:53.396  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 09:35:53.396  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 09:35:53.396  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 09:35:53.396  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 09:35:53.397  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:35:53.399  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 09:35:53.399  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 09:35:53.399  3824  3874 D BluetoothAdapter: STATE_ON
08-30 09:35:53.400  4189  4199 D BtGatt.GattService: stopScan() - queue size =1
08-30 09:35:53.401  4189  4216 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 09:35:53.401  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:53.401  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 09:35:53.401  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 09:35:53.401  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 09:35:53.401  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 09:35:53.402  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:35:53.402  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 09:35:53.402  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 09:35:53.403  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:35:53.403  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:53.403  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:35:53.403  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:35:53.403  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:35:53.409  4189  4205 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 09:35:53.409  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:53.413  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 09:35:53.413  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:53.419  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 09:35:53.419  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:35:53.420  4189  4208 D BtGatt.ScanManager: stopping BLe Batch
,08-30 09:35:53.425  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 09:35:53.425  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:35:53.426  4189  4208 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:35:53.430  4189  4205 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 09:35:53.430  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:53.905  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:35:53.905  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:35:53.906  3824  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:35:56.404  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 09:35:56.405  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:35:56.405  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 09:35:56.406  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:56.407  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:56.407  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:56.407  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:35:56.408  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c6036 removed from the list
08-30 09:35:56.408  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:56.408  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b37 removed from the list
08-30 09:35:56.409  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:56.409  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:56.411  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:56.411  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:56.414  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:56.414  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:35:56.415  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:56.415  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b37 not in the list
08-30 09:35:56.415  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:56.416  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:56.419  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:56.419  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:56.419  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 09:35:56.420  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b37 not in the list
08-30 09:35:56.420  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 09:35:56.420  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:56.421  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:56.421  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c6036 not in the list
,08-30 09:35:56.423  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:35:56.423  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e330b10 added. We now have 3 listener(s)
,08-30 09:35:56.425  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:35:56.425  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:56.425  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:35:56.426  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:35:56.426  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77ac609 added. We now have 4 listener(s)
,08-30 09:35:56.426  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:35:56.426  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 09:35:56.429  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:56.437  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:56.441  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:56.441  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 09:35:56.442  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 09:35:56.444  3824  3874 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,08-30 09:35:56.444  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,08-30 09:35:56.444  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:35:56.444  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 09:35:56.445  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-30 09:35:56.445  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 09:35:56.445  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:56.447  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:56.448  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 09:35:56.448  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 09:35:56.448  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 09:35:56.449  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 09:35:56.450  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,08-30 09:35:56.451  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-30 09:35:56.451  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:56.451  3824  4282 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 09:35:56.451  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 09:35:56.454  3824  4282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 09:35:56.459  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 09:35:56.460  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 09:35:56.470  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 09:35:56.471  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 09:35:56.471  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 09:35:56.474  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 09:35:56.475  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 09:35:56.475  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-30 09:35:56.476  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 09:35:56.476  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 09:35:56.476  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 09:35:56.478  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:35:56.481  4189  4229 D BtGatt.GattService: registerClient() - UUID=4d79246d-b819-4c1f-a31c-7cf234560bc5
,08-30 09:35:56.481  4189  4205 D BtGatt.GattService: onClientRegistered() - UUID=4d79246d-b819-4c1f-a31c-7cf234560bc5, clientIf=5
,08-30 09:35:56.482  3824  3836 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 09:35:56.485  4189  4207 D BtGatt.AdvertiseManager: message : 0
,08-30 09:35:56.490  4189  4207 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 09:35:56.502  4189  4205 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 09:35:56.515  4189  4205 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 09:35:56.517  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 09:35:56.517  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 09:35:56.519  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 09:35:56.520  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 09:35:56.521  3824  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 09:35:56.521  3824  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 09:35:56.521  3824  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 09:35:56.521  3824  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 09:35:56.521  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 09:35:56.525  3824  3824 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 09:35:56.525  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 09:35:56.527  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 09:35:56.527  3824  3874 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:35:57.026  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 09:35:59.529  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:35:59.529  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-30 09:35:59.530  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 09:35:59.530  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 09:35:59.530  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 09:35:59.531  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 09:35:59.531  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 09:35:59.531  3824  4282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 09:35:59.532  3824  3874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 09:35:59.532  3824  4282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 09:35:59.532  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 09:35:59.532  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 09:35:59.532  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 09:35:59.533  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 09:35:59.533  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:35:59.533  3824  4282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 09:35:59.533  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 09:35:59.536  3824  3874 D BluetoothAdapter: STATE_ON
08-30 09:35:59.536  3824  3874 D BluetoothLeScanner: could not find callback wrapper
08-30 09:35:59.537  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:35:59.537  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 09:35:59.539  4189  4207 D BtGatt.AdvertiseManager: message : 1
08-30 09:35:59.541  4189  4207 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 09:35:59.551  4189  4205 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-30 09:35:59.552  4189  4205 D BtGatt.GattService: Client app is not null!
,08-30 09:35:59.553  4189  4199 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 09:35:59.553  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 09:35:59.553  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 09:35:59.554  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 09:35:59.554  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 09:35:59.554  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 09:35:59.557  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:35:59.557  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 09:35:59.558  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 09:35:59.559  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 09:35:59.561  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:59.562  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:35:59.562  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:59.562  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:35:59.562  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:35:59.562  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:35:59.562  3824  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 09:35:59.563  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e330b10 removed from the list
08-30 09:35:59.563  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:35:59.563  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:59.563  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77ac609 removed from the list
08-30 09:35:59.563  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:35:59.564  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:59.565  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:59.565  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:59.568  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:59.568  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:59.568  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:59.569  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77ac609 not in the list
08-30 09:35:59.569  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:35:59.569  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:35:59.571  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:35:59.571  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:35:59.571  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:35:59.572  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77ac609 not in the list
08-30 09:35:59.572  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:35:59.572  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:35:59.573  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:35:59.573  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e330b10 not in the list
,08-30 09:35:59.574  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 09:35:59.575  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c474f1a added. We now have 3 listener(s)
,08-30 09:35:59.580  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 09:35:59.581  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:35:59.581  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 09:35:59.582  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 09:35:59.582  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92ca4b added. We now have 4 listener(s)
08-30 09:35:59.582  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 09:35:59.583  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 09:35:59.588  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:35:59.596  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:35:59.599  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:35:59.599  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:35:59.599  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:35:59.599  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 09:35:59.600  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 09:35:59.600  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 09:35:59.600  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 09:35:59.603  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:59.605  3824  3874 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 09:35:59.606  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 09:35:59.607  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:35:59.612  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 09:35:59.613  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 09:35:59.613  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 09:35:59.620  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 09:35:59.620  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 09:35:59.620  3824  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 09:35:59.622  3824  3874 D BluetoothAdapter: STATE_ON
,08-30 09:35:59.627  4189  4199 D BtGatt.GattService: registerClient() - UUID=1746438c-bdf4-4b4f-b914-5cef1992cbb4
,08-30 09:35:59.628  4189  4205 D BtGatt.GattService: onClientRegistered() - UUID=1746438c-bdf4-4b4f-b914-5cef1992cbb4, clientIf=5
08-30 09:35:59.628  3824  3959 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 09:35:59.629  4189  4216 D BtGatt.GattService: start scan with filters
,08-30 09:35:59.636  4189  4208 D BtGatt.ScanManager: handling starting scan
,08-30 09:35:59.636  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 09:35:59.636  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 09:35:59.636  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 09:35:59.637  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 09:35:59.641  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 09:35:59.641  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 09:35:59.641  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 09:35:59.644  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 09:35:59.648  4189  4205 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 09:35:59.649  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:35:59.649  4189  4208 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 09:35:59.665  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 09:35:59.665  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:59.666  4189  4208 D BtGatt.ScanManager: Starting BLE batch scan
08-30 09:35:59.666  4189  4208 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 09:35:59.697  4189  4205 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 09:35:59.697  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:35:59.717  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 09:35:59.717  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:36:00.064  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:36:00.142  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 09:36:00.142  3824  3824 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 09:36:00.143  3824  3824 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 09:36:01.220  4189  4189 D BtGatt.ScanManager: awakened up at time 240002
,08-30 09:36:01.222  4189  4208 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:36:01.286  4189  4205 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-30 09:36:01.286  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:36:01.287  4189  4205 D BtGatt.GattService: current time is 240068315432
,08-30 09:36:01.287  4189  4205 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 53, 33, -121, 80, 73, -44, 1, 0, -109, 17, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -120, -110, -18, 2, 2, -29, 21, 63, -73, 62, -20, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -105, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 09:36:01.289  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 09:36:01.289  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 09:36:01.290  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 09:36:01.290  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -120, -110, -18, 2, 2, -29, 21, 63, -73, 62, -20, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-30 09:36:01.290  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 09:36:01.290  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 09:36:01.291  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 09:36:02.658  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:36:02.659  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:36:02.659  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 09:36:02.659  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.660  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 09:36:02.660  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 09:36:02.660  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 09:36:02.660  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 09:36:02.661  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 09:36:02.661  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 09:36:02.661  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-30 09:36:02.664  3824  3874 D BluetoothAdapter: STATE_ON
08-30 09:36:02.666  4189  4200 D BtGatt.GattService: stopScan() - queue size =1
08-30 09:36:02.668  4189  4225 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 09:36:02.670  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 09:36:02.670  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 09:36:02.671  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 09:36:02.671  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 09:36:02.671  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 09:36:02.675  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 09:36:02.676  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 09:36:02.676  3824  3874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 09:36:02.677  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 09:36:02.677  4189  4189 D BtGatt.ScanManager: awakened up at time 241459
,08-30 09:36:02.679  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:36:02.682  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:36:02.682  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 09:36:02.683  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 09:36:02.683  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:36:02.684  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:36:02.684  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:36:02.684  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:36:02.684  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c474f1a removed from the list
08-30 09:36:02.684  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.685  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92ca4b removed from the list
08-30 09:36:02.685  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 09:36:02.685  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.687  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:36:02.687  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:36:02.689  4189  4205 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 09:36:02.689  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:36:02.689  4189  4208 D BtGatt.ScanManager: stopping BLe Batch
08-30 09:36:02.689  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 09:36:02.689  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:36:02.689  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.690  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92ca4b not in the list
08-30 09:36:02.690  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.690  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:36:02.693  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 09:36:02.693  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:36:02.693  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.693  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92ca4b not in the list
08-30 09:36:02.693  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:36:02.693  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.693  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 09:36:02.693  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c474f1a not in the list
08-30 09:36:02.694  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 09:36:02.694  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4e2d4 added. We now have 3 listener(s)
,08-30 09:36:02.696  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 09:36:02.696  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 09:36:02.696  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 09:36:02.696  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 09:36:02.697  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9195c7d added. We now have 4 listener(s)
08-30 09:36:02.697  3824  3874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 09:36:02.697  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 09:36:02.699  4189  4205 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 09:36:02.699  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 09:36:02.699  4189  4208 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 09:36:02.700  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 09:36:02.705  3824  3874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 09:36:02.707  3824  3874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 09:36:02.707  3824  3874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 09:36:02.708  3824  3874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 09:36:02.708  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 09:36:02.708  3824  3874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 09:36:02.708  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:36:02.708  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.708  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 09:36:02.708  3824  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 09:36:02.708  3824  3874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4e2d4 removed from the list
08-30 09:36:02.708  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.709  3824  3874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9195c7d removed from the list
,08-30 09:36:02.710  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 09:36:02.711  4189  4205 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-30 09:36:02.711  4189  4205 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 09:36:02.712  4189  4205 D BtGatt.GattService: current time is 241493435746
08-30 09:36:02.712  4189  4205 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -94, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 09:36:02.712  4189  4205 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 09:36:02.713  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 09:36:02.713  3824  3874 D io.jxcore.node.ConnectivityMonitor: stop
08-30 09:36:02.713  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.714  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 09:36:02.714  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.715  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:36:02.715  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:36:02.715  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.715  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9195c7d not in the list
08-30 09:36:02.715  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:36:02.715  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.716  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 09:36:02.716  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 09:36:02.716  3824  3874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 09:36:02.716  3824  3874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9195c7d not in the list
08-30 09:36:02.716  3824  3874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 09:36:02.716  3824  3874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 09:36:02.716  3824  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 09:36:02.716  3824  3874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4e2d4 not in the list
08-30 09:36:02.717  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 09:36:02.718  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 09:36:02.718  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 09:36:02.718  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 09:36:02.718  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 09:36:02.718  3824  3874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 09:36:03.184  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 09:36:03.796   871  4246 D NetlinkSocketObserver: NeighborEvent{elapsedMs=242577, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 09:36:04.733  3824  4284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,08-30 09:36:06.731  3824  3874 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 461
08-30 09:36:06.731  3824  3874 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 461, name: My test thread name)
,08-30 09:36:06.738  3824  4285 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
,08-30 09:36:06.739  3824  4285 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: My test thread name)
08-30 09:36:06.739  3824  4285 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 09:36:06.743  3824  3874 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 09:36:06.751  3824  4284 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-30 09:36:06.751  3824  4286 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,08-30 09:36:06.753  3824  4286 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 466, thread name: My test thread name): Test exception.
08-30 09:36:06.754  3824  4286 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 09:36:06.761  3824  3874 I jxcore-log: Total number of executed tests:  82
08-30 09:36:06.761  3824  3874 I jxcore-log: 
,08-30 09:36:06.762  3824  3874 I jxcore-log: Number of passed tests:  82
08-30 09:36:06.762  3824  3874 I jxcore-log: 
,08-30 09:36:06.763  3824  3874 I jxcore-log: Number of failed tests:  0
08-30 09:36:06.763  3824  3874 I jxcore-log: 
,08-30 09:36:06.765  3824  3874 I jxcore-log: Number of ignored tests:  0
08-30 09:36:06.765  3824  3874 I jxcore-log: 
,08-30 09:36:06.766  3824  3874 I jxcore-log: Total duration:  111455
08-30 09:36:06.766  3824  3874 I jxcore-log: 
,08-30 09:36:06.771  3824  3874 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 09:36:06.771  3824  3874 I jxcore-log: 
,08-30 09:36:06.774  3824  3874 I jxcore-log: My device name is: motorola-Nexus 6
08-30 09:36:06.774  3824  3874 I jxcore-log: 
08-30 09:36:06.784  3824  3874 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 09:36:06.784  3824  3874 I jxcore-log: 
,08-30 09:36:06.792  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.792  3824  3874 I jxcore-log: 
,08-30 09:36:06.793  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.793  3824  3874 I jxcore-log: 
08-30 09:36:06.794  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.794  3824  3874 I jxcore-log: 
,08-30 09:36:06.797  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 09:36:06.797  3824  3874 I jxcore-log: 
,08-30 09:36:06.800  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.800  3824  3874 I jxcore-log: 
,08-30 09:36:06.803  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 09:36:06.803  3824  3874 I jxcore-log: 
08-30 09:36:06.806  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 09:36:06.806  3824  3874 I jxcore-log: 
08-30 09:36:06.807  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 09:36:06.807  3824  3874 I jxcore-log: 
08-30 09:36:06.807  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:36:06.807  3824  3874 I jxcore-log: 
,08-30 09:36:06.808  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.808  3824  3874 I jxcore-log: 
08-30 09:36:06.809  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 09:36:06.809  3824  3874 I jxcore-log: 
,08-30 09:36:06.810  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:36:06.810  3824  3874 I jxcore-log: 
08-30 09:36:06.811  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:36:06.811  3824  3874 I jxcore-log: 
,08-30 09:36:06.812  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.812  3824  3874 I jxcore-log: 
08-30 09:36:06.812  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.812  3824  3874 I jxcore-log: 
,08-30 09:36:06.813  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.813  3824  3874 I jxcore-log: 
,08-30 09:36:06.815  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.815  3824  3874 I jxcore-log: 
08-30 09:36:06.816  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.816  3824  3874 I jxcore-log: 
,08-30 09:36:06.817  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.817  3824  3874 I jxcore-log: 
,08-30 09:36:06.818  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.818  3824  3874 I jxcore-log: 
,08-30 09:36:06.819  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.819  3824  3874 I jxcore-log: 
08-30 09:36:06.819  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.819  3824  3874 I jxcore-log: 
08-30 09:36:06.821  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.821  3824  3874 I jxcore-log: 
08-30 09:36:06.822  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.822  3824  3874 I jxcore-log: 
08-30 09:36:06.822  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.822  3824  3874 I jxcore-log: 
08-30 09:36:06.823  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.823  3824  3874 I jxcore-log: 
08-30 09:36:06.827  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.827  3824  3874 I jxcore-log: 
08-30 09:36:06.828  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.828  3824  3874 I jxcore-log: 
08-30 09:36:06.830  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.830  3824  3874 I jxcore-log: 
08-30 09:36:06.830  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.830  3824  3874 I jxcore-log: 
08-30 09:36:06.831  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.831  3824  3874 I jxcore-log: 
08-30 09:36:06.832  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.832  3824  3874 I jxcore-log: 
08-30 09:36:06.833  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.833  3824  3874 I jxcore-log: 
08-30 09:36:06.833  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.833  3824  3874 I jxcore-log: 
08-30 09:36:06.834  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.834  3824  3874 I jxcore-log: 
08-30 09:36:06.834  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.834  3824  3874 I jxcore-log: 
08-30 09:36:06.835  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.835  3824  3874 I jxcore-log: 
08-30 09:36:06.835  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.835  3824  3874 I jxcore-log: 
08-30 09:36:06.836  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.836  3824  3874 I jxcore-log: 
08-30 09:36:06.836  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.836  3824  3874 I jxcore-log: 
08-30 09:36:06.837  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.837  3824  3874 I jxcore-log: 
08-30 09:36:06.838  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.838  3824  3874 I jxcore-log: 
08-30 09:36:06.838  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 09:36:06.838  3824  3874 I jxcore-log: 
08-30 09:36:06.839  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.839  3824  3874 I jxcore-log: 
,08-30 09:36:06.839  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 09:36:06.839  3824  3874 I jxcore-log: 
,08-30 09:36:06.840  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.840  3824  3874 I jxcore-log: 
,08-30 09:36:06.840  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.840  3824  3874 I jxcore-log: 
08-30 09:36:06.841  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.841  3824  3874 I jxcore-log: 
08-30 09:36:06.841  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.841  3824  3874 I jxcore-log: 
08-30 09:36:06.842  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.842  3824  3874 I jxcore-log: 
08-30 09:36:06.843  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:36:06.843  3824  3874 I jxcore-log: 
,08-30 09:36:06.843  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.843  3824  3874 I jxcore-log: 
08-30 09:36:06.844  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 09:36:06.844  3824  3874 I jxcore-log: 
08-30 09:36:06.844  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.844  3824  3874 I jxcore-log: 
08-30 09:36:06.845  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:36:06.845  3824  3874 I jxcore-log: 
08-30 09:36:06.845  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 09:36:06.845  3824  3874 I jxcore-log: 
,08-30 09:36:06.846  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 09:36:06.846  3824  3874 I jxcore-log: 
08-30 09:36:06.847  3824  3874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 09:36:06.847  3824  3874 I jxcore-log: 
,08-30 09:36:07.421  4288  4288 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 09:36:07.428  4288  4288 D AndroidRuntime: CheckJNI is OFF
,08-30 09:36:07.470  4288  4288 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 09:36:07.516  4288  4288 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 09:36:07.538  4288  4288 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 09:36:07.547   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 09:36:07.548   871   884 I ActivityManager: Killing 3824:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 09:36:07.654   871   894 W PackageSettings: Skipping PackageSetting{8b7b5d4 com.example.hello/10273} due to missing metadata
,08-30 09:36:07.659   871  1387 D GraphicsStats: Buffer count: 2
,08-30 09:36:07.660   871   881 I WindowState: WIN DEATH: Window{47c8276 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 09:36:07.660   871  1311 D WifiService: Client connection lost with reason: 4
,08-30 09:36:07.702   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 09:36:07.702   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 09:36:07.702   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-30 09:36:07.702   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949),
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 09:36:07.702   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:36:07.702   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:36:07.702   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 09:36:07.702   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 09:36:07.703   871   884 I ActivityManager:   Force finishing activity ActivityRecord{a44f69f u0 com.test.thalitest/.MainActivity t2}
08-30 09:36:07.704   871   894 I art     : Starting a blocking GC Explicit
,08-30 09:36:07.711   871  1388 W ActivityManager: Spurious death for ProcessRecord{c5f598b 0:com.test.thalitest/u0a0}, curProc for 3824: null
,08-30 09:36:07.751   871   894 I art     : Explicit concurrent mark sweep GC freed 17313(1148KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 725us total 44.966ms
,08-30 09:36:07.772   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 09:36:07.777  4288  4288 I art     : System.exit called, status: 0
,08-30 09:36:07.777  4288  4288 I AndroidRuntime: VM exiting with result code 0.
,08-30 09:36:07.777   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 09:36:07.793   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 09:36:07.800  4189  4189 D BluetoothMapAppObserver: onReceive
,08-30 09:36:07.800  4189  4189 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 09:36:07.800  2025  2290 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 09:36:07.803  3618  3618 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 09:36:07.805   871  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 09:36:07.814  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 09:36:07.829  1935  1935 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 09:36:07.830   871  2010 I ActivityManager: Start proc 4301:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 09:36:07.835  1871  4300 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 09:36:07.842  1871  4300 I Decoder : createOrResetDecoder
,08-30 09:36:07.877  1513  1513 I ConfigService: onCreate
,08-30 09:36:07.875  4301  4301 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 09:36:07.902   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 09:36:07.905   871  1984 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3824 uid 10000
,08-30 09:36:07.906  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-30 09:36:07.912  1871  4300 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 09:36:07.929   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 09:36:07.930   871   883 E PackageManager: Failed to write settings, restoring backup
08-30 09:36:07.930   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 09:36:07.930   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 09:36:07.930   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 09:36:07.930   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 09:36:07.930   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 09:36:07.930   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 09:36:07.930   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:36:07.930   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 09:36:07.935   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-30 09:36:07.935   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 09:36:07.935   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 09:36:07.935   871   884 E DropBoxManagerService: 	... 13 more
,08-30 09:36:07.938  1871  4300 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 09:36:07.940  1949  2042 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 09:36:07.941  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 09:36:07.941  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 09:36:07.944  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 09:36:07.944  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 09:36:07.946  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 09:36:07.946  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-30 09:36:07.948  1871  4300 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-30 09:36:07.948  1871  4300 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 09:36:07.948  1871  4300 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 09:36:07.949  1871  4300 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-30 09:36:07.949  1871  4300 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 09:36:07.949  1871  4300 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 09:36:07.952   871  1984 I ActivityManager: Start proc 4318:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 09:36:07.952  1949  2042 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 09:36:07.952  1949  2042 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1949
08-30 09:36:07.952  1949  2042 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 09:36:07.952  1949  2042 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 09:36:07.955   871  4323 E DropBoxManagerService: Can't write: system_app_crash
08-30 09:36:07.955   871  4323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 09:36:07.955   871  4323 E DropBoxManagerService: 	... 5 more
,08-30 09:36:07.955   871  1980 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 09:36:07.959  1949  2042 I Process : Sending signal. PID: 1949 SIG: 9
,08-30 09:36:07.971  4301  4301 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 09:36:07.986  4301  4333 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 09:36:07.987   871  2008 I ActivityManager: Start proc 4334:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver

```
