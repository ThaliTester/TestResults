#### Test 817387969f35825_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 20:32:32.573   873  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:32:34.445  3822  3822 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 20:32:34.450  3822  3822 D AndroidRuntime: CheckJNI is OFF
08-24 20:32:34.487  3822  3822 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 20:32:34.542  3822  3822 I Radio-JNI: register_android_hardware_Radio DONE
08-24 20:32:34.561  3822  3822 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 20:32:34.568   873  1958 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 20:32:34.608  1995  2011 W SearchService: Abort, client detached.
08-24 20:32:34.611  1995  1995 I HotwordDetector: Closing mic
08-24 20:32:34.612  1995  2334 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@df0cd1d
08-24 20:32:34.613  1995  2346 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 20:32:34.615  3822  3822 D AndroidRuntime: Shutting down VM
08-24 20:32:34.629   873  2014 I ActivityManager: Start proc 3831:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 20:32:34.673   374  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 20:32:34.675   374  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 20:32:34.686   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 20:32:34.689  1995  2345 I MicroRecognitionRnrImpl: Detection finished
08-24 20:32:34.690  1995  2339 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 20:32:34.722  3831  3831 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 20:32:34.750  3831  3831 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 20:32:34.758  3831  3831 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1060-1062)
08-24 20:32:34.758  3831  3831 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 20:32:34.775  3831  3831 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {87bff56}
08-24 20:32:34.776  3831  3831 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 20:32:34.776  3831  3831 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 20:32:34.785  3831  3831 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 20:32:34.787  3831  3831 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 20:32:34.808  3831  3831 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 20:32:34.818  3831  3831 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 20:32:34.818  3831  3831 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 20:32:34.818  3831  3831 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 20:32:34.818  3831  3831 I Adreno  : Build Date                       : 10/20/15
08-24 20:32:34.818  3831  3831 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 20:32:34.818  3831  3831 I Adreno  : Local Branch                     : M14
08-24 20:32:34.818  3831  3831 I Adreno  : Remote Branch                    : 
08-24 20:32:34.818  3831  3831 I Adreno  : Remote Branch                    : 
08-24 20:32:34.818  3831  3831 I Adreno  : Reconstruct Branch               : 
,08-24 20:32:34.876   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d10552c:true
,08-24 20:32:34.960  3831  3831 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 20:32:34.989  3831  3831 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 20:32:35.057  3831  3871 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 20:32:35.069  3831  3856 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 20:32:35.115  3831  3871 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 20:32:35.186   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +570ms
,08-24 20:32:35.191  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-24 20:32:35.257  3831  3831 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3831
,08-24 20:32:35.364  3831  3831 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 20:32:35.454   873  1967 I ActivityManager: Killing 3054:com.google.android.talk/u0a61 (adj 15): empty #17
,08-24 20:32:35.496   873  1967 I ActivityManager: Killing 2979:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-24 20:32:35.607  3831  3873 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1683293904
,08-24 20:32:35.612  3831  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 20:32:35.612  3831  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 20:32:35.612  3831  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 20:32:35.612  3831  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 20:32:35.612  3831  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 20:32:35.612  3831  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f686925 added. We now have 1 listener(s)
08-24 20:32:35.615  3831  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-24 20:32:35.615  3831  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 20:32:35.616  3831  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:32:35.616  3831  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 20:32:35.620  3831  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55b72a1 added. We now have 1 listener(s)
,08-24 20:32:35.620  3831  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 20:32:35.623   873  1315 D WifiService: New client listening to asynchronous messages
,08-24 20:32:35.627  3831  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:32:35.627  3831  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 20:32:35.627  3831  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 20:32:35.627  3831  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-24 20:32:35.627  3831  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 20:32:35.631  3831  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:32:35.631  3831  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-24 20:32:35.636  3831  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:32:35.636  3831  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:32:35.636  3831  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 20:32:35.636  3831  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:32:35.639  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:32:35.641  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:32:35.644  3831  3873 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 20:32:35.826  3831  3831 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 20:32:36.322   873  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 20:32:36.618  3831  3881 W jxcore-log: Initializing JXcore engine
,08-24 20:32:36.619  3831  3881 W jxcore-log: JXcore engine is ready
,08-24 20:32:36.657  3881  3881 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 20:32:36.657  3881  3881 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13070]" dev="sockfs" ino=13070 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 20:32:36.657  3881  3881 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 20:32:36.657  3881  3881 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25041]" dev="sockfs" ino=25041 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 20:32:36.672  3831  3881 W jxcore-log: Starting JXcore engine
,08-24 20:32:36.797  3831  3881 W jxcore-log: Platform android
08-24 20:32:36.797  3831  3881 W jxcore-log: 
08-24 20:32:36.797  3831  3881 W jxcore-log: Process ARCH arm
08-24 20:32:36.797  3831  3881 W jxcore-log: 
,08-24 20:32:37.121  3831  3881 I jxcore-log: JXcore Cordova bridge is ready!
08-24 20:32:37.121  3831  3881 I jxcore-log: 
,08-24 20:32:37.122  3831  3881 W jxcore-log: JXcore engine is started
,08-24 20:32:37.127  3831  3873 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 20:32:37.132  3831  3831 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 20:32:41.863  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:32:41.865  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:32:41.906  1526  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 20:32:41.906  1526  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 20:32:41.906  1526  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:32:41.906  1526  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:32:41.945  3556  3889 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 20:32:41.945  3556  3889 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at blb.a(PG:3937)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at czp.a(PG:18188)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:32:41.945  3556  3889 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	... 12 more
08-24 20:32:41.945  3556  3889 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at fal.a(PG:38)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:32:41.945  3556  3889 E HttpOperation: 	... 14 more
,08-24 20:32:41.973   873  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:32:42.022  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 20:32:42.022  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 20:32:42.022  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:32:42.022  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:32:42.038  3556  3889 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 20:32:42.038  3556  3889 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at hec.a(PG:42)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at hee.a(PG:102)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at czr.a(PG:65)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at kka.a(PG:108)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at czp.a(PG:19176)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:32:42.038  3556  3889 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	... 15 more
08-24 20:32:42.038  3556  3889 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at fal.a(PG:38)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:32:42.038  3556  3889 E HttpOperation: 	... 17 more
,08-24 20:32:42.038  3556  3889 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 20:32:42.038  3556  3889 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at hec.a(PG:42)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at hee.a(PG:102)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at czr.a(PG:65)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at kka.a(PG:108)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	... 15 more
08-24 20:32:42.038  3556  3889 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at fal.a(PG:38)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 20:32:42.038  3556  3889 E ExperimentLoader: 	... 17 more
,08-24 20:32:42.149   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 127034, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:32:42.266  3610  3891 V KeepSync: Connecting to GoogleApiClient
,08-24 20:32:42.267   873  1404 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 20:32:42.376  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 20:32:42.377  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 20:32:42.377  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:32:42.377  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:32:42.413  1752  3892 V BaseAuthAsyncOperation: access token request failed
,08-24 20:32:42.414  3610  3891 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 20:32:42.536  1526  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 20:32:42.537  1526  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 20:32:42.537  1526  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:32:42.537  1526  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:32:42.558  3610  3891 E KeepSync: IOException
08-24 20:32:42.558  3610  3891 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 20:32:42.558  3610  3891 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:32:42.558  3610  3891 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 20:32:42.558  3610  3891 E KeepSync: 	... 10 more
,08-24 20:32:42.558  3610  3891 W KeepSync: Sync result 2
08-24 20:32:42.567   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127959, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:32:44.852  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:32:44.869  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 20:32:44.869  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 20:32:44.869  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:32:44.869  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:32:44.883  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 20:32:44.884  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 20:32:44.884  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-24 20:32:53.720  3831  3881 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 20:32:53.720  3831  3881 I jxcore-log: 
,08-24 20:32:53.722  3831  3881 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 20:32:53.722  3831  3881 I jxcore-log: 
,08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:32:53.732  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:32:53.738  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:32:53.740  3831  3881 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 20:32:53.740  3831  3881 I jxcore-log: 
,08-24 20:32:53.743  3831  3881 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 20:32:53.743  3831  3881 I jxcore-log: 
,08-24 20:32:54.172  3831  3881 I jxcore-log: Running unit tests
08-24 20:32:54.172  3831  3881 I jxcore-log: 
,08-24 20:32:54.173  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 20:32:54.173  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff5429 added. We now have 2 listener(s)
,08-24 20:32:54.174  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 20:32:54.174  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:32:54.174  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 20:32:54.174  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:32:54.174  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1183ae added. We now have 2 listener(s)
,08-24 20:32:54.174  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:32:54.175  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:32:54.180  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:32:54.200  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:32:54.206  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:32:54.206  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:32:54.207  3831  3881 D ExecuteNativeTests: Running unit tests
,08-24 20:32:54.214  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:32:54.222  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:32:54.295  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 20:32:54.296  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c added. We now have 3 listener(s)
,08-24 20:32:54.297  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 20:32:54.297  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:32:54.297  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 20:32:54.297  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:32:54.297  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 added. We now have 3 listener(s)
,08-24 20:32:54.297  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:32:54.297  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:32:54.299  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:32:54.327  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:32:54.330  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 20:32:54.330  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 20:32:54.333  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 20:32:54.334  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 20:32:54.334  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 20:32:54.334  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 20:32:54.336  3831  3881 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 20:32:54.337  3831  3881 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 20:32:54.337  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 20:32:54.337  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 20:32:54.337  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 20:32:54.337  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 20:32:54.337  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:32:54.338  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 20:32:54.338  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:32:54.338  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:32:54.338  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:54.338  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 20:32:54.338  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 20:32:54.338  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c removed from the list
,08-24 20:32:54.339  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:32:54.339  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 removed from the list
,08-24 20:32:54.340  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:32:54.345  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:32:54.347  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:32:54.349  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:32:54.350  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:54.350  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:32:54.351  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:32:54.351  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:32:54.351  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:32:54.352  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:32:54.354  3831  3881 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 20:32:54.355  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:32:54.355  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:32:54.355  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:32:54.355  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:32:54.355  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:54.355  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:32:54.355  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:32:54.355  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:32:54.355  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:32:54.356  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:32:54.356  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:54.356  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:32:54.356  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:32:54.356  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:32:54.357  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:32:54.357  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:32:54.357  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:32:54.357  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 20:32:54.362  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 20:32:54.363  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-24 20:32:54.364  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 20:32:54.364  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 20:32:54.364  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 20:32:54.364  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 20:32:54.364  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:32:54.364  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:32:54.364  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:32:54.364  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:32:54.364  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:32:54.364  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:32:54.364  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:32:54.364  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:32:54.364  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:32:54.364  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:32:54.364  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:54.364  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:32:54.365  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:54.365  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:32:54.366  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:32:54.366  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:32:54.366  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:32:54.366  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:32:54.367  3831  3881 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 20:32:54.368  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:32:54.373  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:32:54.377  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:32:54.377  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:32:54.377  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 20:32:54.377  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 20:32:54.377  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 20:32:54.377  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:32:54.377  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 20:32:54.383  3831  3881 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 20:32:54.383  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 20:32:54.384  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:32:54.387  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:32:54.392  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 20:32:54.393  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 20:32:54.393  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 20:32:54.398  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-24 20:32:54.402  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-24 20:32:54.402  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 20:32:54.402  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 20:32:54.403  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 20:32:54.404  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:32:54.408  2612  2624 D BtGatt.GattService: registerClient() - UUID=8890976e-7a2d-490e-a1d4-6704ba028d41
,08-24 20:32:54.408  2612  2647 D BtGatt.GattService: onClientRegistered() - UUID=8890976e-7a2d-490e-a1d4-6704ba028d41, clientIf=5
,08-24 20:32:54.409  3831  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 20:32:54.410  2612  2734 D BtGatt.GattService: start scan with filters
,08-24 20:32:54.413  2612  2652 D BtGatt.ScanManager: handling starting scan
,08-24 20:32:54.414  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 20:32:54.415  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 20:32:54.415  2612  2652 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:32:54.415  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 20:32:54.417  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 20:32:54.423  2612  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 20:32:54.423  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:54.423  2612  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 20:32:54.427  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 20:32:54.428  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 20:32:54.428  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 20:32:54.429  2612  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 20:32:54.429  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:32:54.429  2612  2652 D BtGatt.ScanManager: Starting BLE batch scan
08-24 20:32:54.430  2612  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 20:32:54.433  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 20:32:54.436  3831  3881 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 20:32:54.441  2612  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 20:32:54.441  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:54.446  2612  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 20:32:54.446  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:54.930  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-24 20:32:54.930  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 20:32:54.931  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 20:32:55.953  2612  2612 D BtGatt.ScanManager: awakened up at time 142258
,08-24 20:32:55.957  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:32:56.000  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-24 20:32:56.000  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:56.001  2612  2647 D BtGatt.GattService: current time is 142305789352
08-24 20:32:56.002  2612  2647 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -93, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -66, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-24 20:32:56.006  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-24 20:32:56.008  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-24 20:32:56.009  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-24 20:32:56.010  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-24 20:32:56.010  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-24 20:32:57.504  2612  2612 D BtGatt.ScanManager: awakened up at time 143808
,08-24 20:32:57.507  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:32:57.517  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 20:32:57.517  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:59.019  2612  2612 D BtGatt.ScanManager: awakened up at time 145324
,08-24 20:32:59.022  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:32:59.072  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-24 20:32:59.073  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:32:59.073  2612  2647 D BtGatt.GattService: current time is 145377893760
,08-24 20:32:59.076  2612  2647 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -88, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -88, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -96, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-24 20:32:59.077  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-24 20:32:59.078  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-24 20:32:59.079  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-24 20:32:59.080  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-24 20:32:59.081  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-24 20:32:59.446  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:32:59.446  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 20:32:59.447  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 20:32:59.447  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:32:59.447  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-24 20:32:59.448  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 20:32:59.448  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 20:32:59.448  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 20:32:59.448  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 20:32:59.450  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 20:32:59.451  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 20:32:59.453  3831  3881 D BluetoothAdapter: STATE_ON
08-24 20:32:59.455  2612  2725 D BtGatt.GattService: stopScan() - queue size =1
08-24 20:32:59.458  2612  2626 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 20:32:59.460  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 20:32:59.460  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 20:32:59.461  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 20:32:59.461  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 20:32:59.461  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 20:32:59.464  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:32:59.465  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 20:32:59.465  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 20:32:59.466  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 20:32:59.467  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 20:32:59.470  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 20:32:59.470  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 20:32:59.470  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 20:32:59.471  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:32:59.471  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:32:59.471  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:32:59.471  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:32:59.471  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:32:59.471  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:32:59.471  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:32:59.471  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:32:59.476  2612  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 20:32:59.477  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:59.477  2612  2652 D BtGatt.ScanManager: stopping BLe Batch
,08-24 20:32:59.493  2612  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 20:32:59.493  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:59.494  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:32:59.508  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 20:32:59.510  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:32:59.971  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 20:33:03.691   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-24 20:33:03.706  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-24 20:33:03.727   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 20:33:03.727   873   893 I Adreno  : Build Date                       : 10/20/15
08-24 20:33:03.727   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 20:33:03.727   873   893 I Adreno  : Local Branch                     : M14
08-24 20:33:03.727   873   893 I Adreno  : Remote Branch                    : 
08-24 20:33:03.727   873   893 I Adreno  : Remote Branch                    : 
08-24 20:33:03.727   873   893 I Adreno  : Reconstruct Branch               : 
,08-24 20:33:03.746   279  1306 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (218 us)
,08-24 20:33:04.349  3831  3831 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 20:33:04.350  3831  3831 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 20:33:04.393   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-24 20:33:04.397  3831  3831 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a5fb05c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@446d837, 16908290=android.view.AbsSavedState$1@446d837}, android:focusedViewId=100}]}]
08-24 20:33:04.398  3831  3831 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 20:33:04.398  3831  3831 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 20:33:04.398  3831  3831 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 20:33:04.412   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-24 20:33:04.416   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-24 20:33:04.416   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-24 20:33:04.417   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-24 20:33:04.428   873   882 I art     : Background partial concurrent mark sweep GC freed 44556(2MB) AllocSpace objects, 14(344KB) LOS objects, 33% free, 29MB/43MB, paused 8.691ms total 97.196ms
,08-24 20:33:04.473  3831  3881 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 20:33:04.477  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:04.490  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:33:04.496  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:33:04.497  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:33:04.497  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 20:33:04.498  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 20:33:04.498  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 20:33:04.498  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:33:04.499  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 20:33:04.504  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:04.509  3831  3881 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 20:33:04.510  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 20:33:04.515  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:04.524  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 20:33:04.525  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 20:33:04.526  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 20:33:04.532  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 20:33:04.533  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 20:33:04.533  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 20:33:04.534  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:33:04.539  2612  2626 D BtGatt.GattService: registerClient() - UUID=24babfee-55ff-4139-a8e5-f548a83111d4
,08-24 20:33:04.540  2612  2647 D BtGatt.GattService: onClientRegistered() - UUID=24babfee-55ff-4139-a8e5-f548a83111d4, clientIf=5
,08-24 20:33:04.541  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 20:33:04.541  2612  2725 D BtGatt.GattService: start scan with filters
,08-24 20:33:04.547  2612  2652 D BtGatt.ScanManager: handling starting scan
08-24 20:33:04.547  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 20:33:04.547  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 20:33:04.549  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 20:33:04.549  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 20:33:04.557  2612  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 20:33:04.557  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.557  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 20:33:04.557  2612  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 20:33:04.557  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 20:33:04.557  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 20:33:04.564  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 20:33:04.568  3831  3881 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 20:33:04.573  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:04.573  2612  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 20:33:04.573  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:33:04.573  2612  2652 D BtGatt.ScanManager: Starting BLE batch scan
08-24 20:33:04.573  2612  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 20:33:04.573  3831  3881 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 20:33:04.574  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:04.574  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 20:33:04.574  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:04.574  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-24 20:33:04.574  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 20:33:04.574  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 20:33:04.574  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 20:33:04.574  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 20:33:04.575  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 20:33:04.575  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 20:33:04.576  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:33:04.577  2612  2624 D BtGatt.GattService: stopScan() - queue size =1
08-24 20:33:04.577  2612  2627 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 20:33:04.578  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 20:33:04.578  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 20:33:04.578  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 20:33:04.578  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 20:33:04.578  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 20:33:04.580  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:33:04.580  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 20:33:04.581  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 20:33:04.581  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 20:33:04.582  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 20:33:04.585  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 20:33:04.585  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:33:04.585  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 20:33:04.585  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:33:04.585  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:04.586  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:33:04.586  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
,08-24 20:33:04.586  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:04.586  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:04.587  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:04.587  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:04.588  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:04.589  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:04.591  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:04.591  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:04.591  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:04.591  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:04.593  3831  3881 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 20:33:04.595  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:04.604  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:33:04.605  2612  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 20:33:04.605  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.607  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:33:04.608  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:33:04.609  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 20:33:04.609  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 20:33:04.609  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 20:33:04.610  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:33:04.610  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 20:33:04.611  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:04.613  3831  3881 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 20:33:04.613  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 20:33:04.616  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:04.616  2612  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 20:33:04.617  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.618  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 20:33:04.619  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 20:33:04.619  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 20:33:04.623  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 20:33:04.623  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 20:33:04.623  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 20:33:04.624  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:33:04.626  2612  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 20:33:04.626  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.627  2612  2652 D BtGatt.ScanManager: stopping BLe Batch
08-24 20:33:04.627  2612  2626 D BtGatt.GattService: registerClient() - UUID=3e32addf-71aa-4fff-bc1f-e413b07c1640
08-24 20:33:04.628  2612  2647 D BtGatt.GattService: onClientRegistered() - UUID=3e32addf-71aa-4fff-bc1f-e413b07c1640, clientIf=5
08-24 20:33:04.628  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 20:33:04.629  2612  2734 D BtGatt.GattService: start scan with filters
,08-24 20:33:04.633  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 20:33:04.633  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 20:33:04.633  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 20:33:04.633  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 20:33:04.635  2612  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 20:33:04.636  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:33:04.636  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:33:04.636  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 20:33:04.637  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 20:33:04.637  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 20:33:04.638  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 20:33:04.643  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 20:33:04.643  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.643  3831  3881 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 20:33:04.645  2612  2652 D BtGatt.ScanManager: handling starting scan
,08-24 20:33:04.647   279   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 20:33:04.649   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-24 20:33:04.649   873  1341 D SurfaceControl: Excessive delay in setPowerMode(): 233ms
,08-24 20:33:04.655   873   893 I DreamManagerService: Entering dreamland.
08-24 20:33:04.655   873   893 I PowerManagerService: Dozing...
,08-24 20:33:04.656   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-24 20:33:04.657  2612  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 20:33:04.657  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:33:04.657  2612  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 20:33:04.664  2612  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 20:33:04.664  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.664  2612  2652 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 20:33:04.665  2612  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 20:33:04.676  2612  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 20:33:04.676  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.683  2612  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 20:33:04.683  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:04.703   374  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-24 20:33:04.703   374  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-24 20:33:04.711   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:33:04.717   873  1314 E native  : do suspend false
,08-24 20:33:04.720  1919  3903 D NfcService: Discovery configuration equal, not updating.
,08-24 20:33:04.733   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 20:33:04.756   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:33:04.761   873  1314 E native  : do suspend true
,08-24 20:33:04.837   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-24 20:33:04.837   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-24 20:33:05.138  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-24 20:33:05.138  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 20:33:05.138  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 20:33:05.214   873  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-24 20:33:05.232  2612  2612 D BtGatt.ScanManager: awakened up at time 151537
,08-24 20:33:05.234  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:33:05.264  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-24 20:33:05.264  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:05.264  2612  2647 D BtGatt.GattService: current time is 151569125575
,08-24 20:33:05.265  2612  2647 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-24 20:33:05.265  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-24 20:33:05.265  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84],
08-24 20:33:05.266  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
,08-24 20:33:05.420  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:05.434  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:05.440  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:05.509  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 20:33:05.509  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 20:33:05.510  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:33:05.510  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:05.567  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 20:33:05.568  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 20:33:05.572  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-24 20:33:06.768  2612  2612 D BtGatt.ScanManager: awakened up at time 153073
,08-24 20:33:06.771  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:33:06.825  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-24 20:33:06.825  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:06.825  2612  2647 D BtGatt.GattService: current time is 153130213017
,08-24 20:33:06.827  2612  2647 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -94, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -89, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-24 20:33:06.827  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-24 20:33:06.828  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-24 20:33:06.829  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-24 20:33:06.830  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-24 20:33:06.831  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-24 20:33:06.832  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-24 20:33:08.326  2612  2612 D BtGatt.ScanManager: awakened up at time 154630
,08-24 20:33:08.328  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:33:08.339  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 20:33:08.339  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:09.643  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:09.644  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:09.644  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 20:33:09.645  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:09.645  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-24 20:33:09.645  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 20:33:09.645  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 20:33:09.646  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 20:33:09.646  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 20:33:09.646  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 20:33:09.647  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 20:33:09.649  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:33:09.651  2612  2734 D BtGatt.GattService: stopScan() - queue size =1
,08-24 20:33:09.654  2612  2624 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 20:33:09.656  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 20:33:09.656  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 20:33:09.656  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 20:33:09.657  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 20:33:09.657  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 20:33:09.661  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 20:33:09.661  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-24 20:33:09.662  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 20:33:09.662  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-24 20:33:09.664  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 20:33:09.665  2612  2612 D BtGatt.ScanManager: awakened up at time 155970
08-24 20:33:09.667  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 20:33:09.667  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 20:33:09.667  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:33:09.674  2612  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 20:33:09.674  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:09.674  2612  2652 D BtGatt.ScanManager: stopping BLe Batch
,08-24 20:33:09.686  2612  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 20:33:09.686  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:09.686  2612  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:33:09.707  2612  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-24 20:33:09.707  2612  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:33:09.707  2612  2647 D BtGatt.GattService: current time is 156012172759
,08-24 20:33:09.708  2612  2647 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -89, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -93, -68, -21, 13, -88, 81, 1, -128, -106, 7, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -92, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -97, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-24 20:33:09.708  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-24 20:33:09.708  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
08-24 20:33:09.708  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-24 20:33:09.709  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-24 20:33:09.709  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-24 20:33:09.709  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-24 20:33:09.709  2612  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-24 20:33:10.169  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 20:33:10.169  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:10.170  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 20:33:11.587  2169  2677 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 20:33:14.668  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:14.668  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.669  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:14.669  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.669  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:14.670  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:33:14.670  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
,08-24 20:33:14.670  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.671  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.671  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.671  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.673  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.673  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.677  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:14.677  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:33:14.677  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:14.678  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.680  3831  3881 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 20:33:14.682  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:14.682  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.682  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:14.683  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.683  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.683  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.684  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.684  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.684  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.685  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:14.685  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:14.685  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.686  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.686  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.688  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:33:14.688  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:14.688  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.688  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.689  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 20:33:14.689  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.689  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.689  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:14.689  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.689  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.690  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.690  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.690  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.690  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:14.690  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.690  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.690  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.690  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.690  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.692  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:14.692  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:14.692  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.692  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.693  3831  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-24 20:33:14.693  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.693  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.693  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:14.693  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:33:14.693  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.693  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.693  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.694  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.694  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.694  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.694  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:14.694  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.694  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.694  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.695  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:14.695  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:33:14.695  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.696  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.696  3831  3881 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 20:33:14.696  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:14.696  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.697  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:14.697  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.697  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:14.697  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.697  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.697  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.697  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.697  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.697  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:14.697  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.697  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.697  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.698  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:14.699  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:33:14.699  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.699  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:14.699  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 20:33:14.700  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 20:33:14.700  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 20:33:14.700  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 20:33:14.700  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 20:33:14.700  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 20:33:14.700  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 20:33:14.700  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 20:33:14.700  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 20:33:14.700  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.701  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.701  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:14.701  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.701  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.701  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.701  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.701  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.701  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.701  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.701  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.701  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.702  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.702  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.703  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:14.703  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:14.703  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:14.704  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.705  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 20:33:14.705  3831  3881 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 20:33:14.705  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 20:33:14.709  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 20:33:14.709  3831  3881 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 20:33:14.709  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 20:33:14.709  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 20:33:14.709  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 20:33:14.710  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-24 20:33:14.711  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 20:33:14.712  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 20:33:14.712  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 20:33:14.712  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-24 20:33:14.712  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 20:33:14.712  3831  3881 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-24 20:33:14.712  3831  3881 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 20:33:14.713  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 20:33:14.713  3831  3881 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-24 20:33:14.713  3831  3881 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 20:33:14.713  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 20:33:14.713  3831  3881 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 20:33:14.713  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-24 20:33:14.715  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 20:33:14.716  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 20:33:14.716  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 20:33:14.717  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 20:33:14.717  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-24 20:33:14.717  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 20:33:14.717  3831  3881 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 20:33:14.718  3831  3881 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 20:33:14.718  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.719  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 20:33:14.719  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:14.719  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:33:14.719  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.719  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.719  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-24 20:33:14.720  3831  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-24 20:33:14.721  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.721  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:14.721  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.721  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.721  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:14.721  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.721  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.722  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.723  3831  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-24 20:33:14.723  3831  3908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 20:33:14.723  3831  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-24 20:33:14.724  3831  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
,08-24 20:33:14.725  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:33:14.725  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:33:14.725  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-24 20:33:14.726  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:14.727  3831  3881 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 20:33:14.728  3831  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-24 20:33:14.729  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.729  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.730  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:14.730  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.730  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.730  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.730  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.730  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.730  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:14.730  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.730  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.730  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.730  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.730  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.732  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:33:14.732  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:14.732  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.732  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.733  3831  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 20:33:14.734  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.734  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.734  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:14.734  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.734  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.734  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.734  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.734  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.734  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:14.734  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.734  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.734  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.734  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.734  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.735  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:33:14.735  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:14.735  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.735  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.736  3831  3881 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 20:33:14.736  3831  3881 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 20:33:14.736  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-24 20:33:14.736  3831  3881 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 20:33:14.736  3831  3881 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 20:33:14.736  3831  3881 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 20:33:14.736  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 20:33:14.737  3831  3881 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-24 20:33:14.737  3831  3881 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 20:33:14.737  3831  3881 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 20:33:14.737  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 20:33:14.737  3831  3881 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 20:33:14.737  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:14.737  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:14.737  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:14.737  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.737  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.737  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.737  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:14.737  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.737  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:14.738  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.738  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.738  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.738  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.738  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.739  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:33:14.739  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:14.739  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.739  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.739  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:14.739  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.739  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:14.739  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
,08-24 20:33:14.739  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:14.739  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:14.739  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:14.740  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:14.740  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:14.976  3784  3910 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 20:33:15.026  3784  3911 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 20:33:15.036  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:15.039  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:15.068  1526  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 20:33:15.069  1526  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:33:15.069  1526  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:33:15.069  1526  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:15.101  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:15.104  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:15.157  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 20:33:15.157  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 20:33:15.158  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:33:15.160  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:15.205  3784  3911 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 20:33:15.210  3784  3910 E BooksSync: Soft error
08-24 20:33:15.210  3784  3910 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:33:15.210  3784  3910 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 20:33:15.211  3784  3910 E BooksSync: Sync error
08-24 20:33:15.211  3784  3910 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:33:15.211  3784  3910 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 20:33:15.212  3784  3910 I BooksSync: Finished books sync
,08-24 20:33:15.227   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161150, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:33:16.337   873  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-24 20:33:16.626   873  1845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=162930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:33:19.740  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.741  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.741  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:19.742  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.742  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:19.742  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:19.743  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:19.743  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 20:33:19.744  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 20:33:19.744  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:19.744  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:19.744  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.745  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
,08-24 20:33:19.745  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:19.746  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:19.746  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:19.746  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:19.746  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.747  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.747  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.750  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:19.751  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:33:19.751  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.751  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.756  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 20:33:19.757  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:33:19.761  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-24 20:33:19.763  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-24 20:33:19.763  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 20:33:19.764  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 20:33:19.764  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 20:33:19.764  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 20:33:19.765  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:33:19.765  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 20:33:19.765  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 20:33:19.765  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 20:33:19.766  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.766  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 20:33:19.766  3831  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 20:33:19.766  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:19.766  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 20:33:19.766  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.766  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 20:33:19.767  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 20:33:19.767  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 20:33:19.767  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.767  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.770  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 20:33:19.770  3831  3912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 20:33:19.770  3831  3912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 20:33:19.770  3831  3912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 20:33:19.770  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.770  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 20:33:19.771  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:19.771  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 20:33:19.771  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 20:33:19.771  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:19.771  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:33:19.771  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:19.771  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:19.772  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.772  3831  3831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-24 20:33:19.772  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:19.772  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.772  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.772  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:19.773  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.773  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.773  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.773  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.775  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:19.775  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:19.775  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.776  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.777  3831  3881 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 20:33:19.777  3831  3881 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-24 20:33:19.778  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 20:33:19.778  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 20:33:19.778  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 20:33:19.778  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:19.778  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:19.779  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:19.779  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:33:19.779  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.779  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.779  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:19.779  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:19.779  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.779  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:19.779  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:19.779  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.780  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.780  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.783  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:33:19.783  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:19.784  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.784  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.789  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:33:19.789  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:19.789  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:19.789  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:19.789  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.789  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:19.789  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:19.790  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.790  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.790  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:19.790  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.791  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.791  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.791  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:19.793  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:19.793  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:19.793  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.793  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:19.795  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 20:33:19.795  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:33:19.795  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:33:19.796  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:33:19.796  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.796  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.796  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a1d0c not in the list
08-24 20:33:19.796  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.796  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
08-24 20:33:19.796  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:19.796  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.796  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.796  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:19.797  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:19.798  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:33:19.798  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:33:19.798  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:19.799  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f03655 not in the list
,08-24 20:33:19.801  3831  3881 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-24 20:33:19.801  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 20:33:19.802  3831  3881 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 20:33:19.802  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 20:33:19.802  3831  3881 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 20:33:19.802  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-24 20:33:19.811  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-24 20:33:19.812  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-24 20:33:19.814  3831  3881 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 20:33:19.814  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-24 20:33:19.814  3831  3881 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 20:33:19.814  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 20:33:19.815  3831  3881 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 20:33:19.815  3831  3881 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-24 20:33:19.816  3831  3881 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-24 20:33:19.817  3831  3881 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-24 20:33:19.818  3831  3881 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-24 20:33:19.818  3831  3881 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 20:33:19.819  3831  3881 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-24 20:33:19.819  3831  3881 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 20:33:19.821  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 20:33:19.821  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c54e13c added. We now have 3 listener(s)
08-24 20:33:19.821  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:33:19.823  3831  3881 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 20:33:19.823   873   884 D WifiService: setWifiEnabled: true pid=3831, uid=10000
,08-24 20:33:19.823   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 20:33:19.855  2612  2717 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-24 20:33:19.855  2612  2722 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-24 20:33:20.272  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 20:33:24.830  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 20:33:24.830  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2c5ec5 added. We now have 4 listener(s)
,08-24 20:33:24.831  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:33:24.848  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:24.849  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2c5ec5 removed from the list
,08-24 20:33:24.849  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:24.849  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:24.850  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:24.853  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 20:33:24.853  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@222901a added. We now have 4 listener(s)
,08-24 20:33:24.853  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:33:24.858  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:24.858  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@222901a removed from the list
08-24 20:33:24.859  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:24.859  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:24.859  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:24.864  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 20:33:24.864  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebb774b added. We now have 4 listener(s),
08-24 20:33:24.865  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 20:33:24.872   873  2014 D WifiService: setWifiEnabled: false pid=3831, uid=10000
08-24 20:33:24.872   873  2014 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 20:33:24.885  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:33:24.888  2612  2642 D BluetoothAdapterState: Current state: ON, message: 23
,08-24 20:33:24.888  2612  2642 D BluetoothAdapterProperties: Setting state to 13
08-24 20:33:24.889  2612  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 20:33:24.890  2612  2642 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 20:33:24.894  2612  2642 I BluetoothAdapterState: Entering PendingCommandState
,08-24 20:33:24.894  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:24.894  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 20:33:24.896  2612  2647 D BluetoothAdapterProperties: Scan Mode:20
08-24 20:33:24.896  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:24.896  2612  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 20:33:24.896  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:33:24.897  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 20:33:24.898  2612  2612 D BluetoothMapService: onReceive
08-24 20:33:24.899  2612  2612 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 20:33:24.899  2612  2612 D BluetoothMapService: STATE_TURNING_OFF
,08-24 20:33:24.900  2612  2612 D BluetoothMapService: MAP Service closeService in
,08-24 20:33:24.900  2612  2612 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 20:33:24.903  2612  2612 D ObexServerSockets0: shutdown(block = true)
08-24 20:33:24.905  2612  2736 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-24 20:33:24.907  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.909  2612  2612 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 20:33:24.909  2612  2722 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 20:33:24.909  2612  2737 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-24 20:33:24.909  2612  2612 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 20:33:24.909  2612  2612 I BtOppRfcommListener: stopping Accept Thread
08-24 20:33:24.910  2612  3428 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 20:33:24.911  2612  3428 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 20:33:24.913  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:24.920  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:24.920  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 20:33:24.921  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 20:33:24.921  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:24.921  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:33:24.923   873   886 I ActivityManager: Start proc 3916:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-24 20:33:24.924   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 20:33:24.924   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 20:33:24.925   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 20:33:24.925   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 20:33:24.926  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:24.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 20:33:24.927  2612  2612 D HeadsetService: Received stop request...Stopping profile...
08-24 20:33:24.927  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:24.927  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:33:24.930   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:24.930  1932  2056 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:24.931   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 20:33:24.931  1359  1380 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:24.932   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 20:33:24.932  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.934  2612  2612 D A2dpService: Received stop request...Stopping profile...
,08-24 20:33:24.934  2612  2728 D A2dpStateMachine: Exit Disconnected: -1
,08-24 20:33:24.935  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.935  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-24 20:33:24.936  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-24 20:33:24.936   873   873 D BluetoothA2dp: Proxy object disconnected
08-24 20:33:24.936  2612  2612 D HidService: Received stop request...Stopping profile...
08-24 20:33:24.936  2612  2612 D HidService: Stopping Bluetooth HidService
08-24 20:33:24.937  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.937  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-24 20:33:24.938  1359  1359 D HidProfile: Bluetooth service disconnected
08-24 20:33:24.939  2612  2612 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:24.939  2612  2612 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:24.939  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:24.939  2612  2612 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:24.940  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.942  2612  2612 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 20:33:24.942  2612  2612 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 20:33:24.943  2612  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-24 20:33:24.943  2612  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:24.943  2612  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:24.943  2612  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:24.943  2612  2647 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-24 20:33:24.944   873  1314 E native  : do suspend true
08-24 20:33:24.946  2612  2612 D HealthService: Received stop request...Stopping profile...
08-24 20:33:24.948  2612  2612 D PanService: Received stop request...Stopping profile...
08-24 20:33:24.948  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 20:33:24.949  1359  1359 D PanProfile: Bluetooth service disconnected
08-24 20:33:24.949  2612  2612 D BluetoothMapService: Received stop request...Stopping profile...
08-24 20:33:24.949  2612  2612 D BluetoothMapService: stop()
,08-24 20:33:24.950  2612  2612 D BluetoothMapAppObserver: deinitObservers()
,08-24 20:33:24.950  2612  2612 D BluetoothMapAppObserver: removeReceiver()
08-24 20:33:24.951  1359  1359 D BluetoothMap: Proxy object disconnected
08-24 20:33:24.951  1359  1359 D MapProfile: Bluetooth service disconnected
08-24 20:33:24.952  2612  2612 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:24.952  2612  2612 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:24.952  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:24.952  2612  2612 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:24.953  2612  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:24.954  2612  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 20:33:24.954  2612  2717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 20:33:24.954  2612  2717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 20:33:24.954  2612  2717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 20:33:24.954  2612  2717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 20:33:24.954  2612  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 20:33:24.955  2612  2612 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:24.955  2612  2612 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:24.955  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:24.955  2612  2612 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:24.955  2612  2612 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 20:33:24.955  2612  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 20:33:24.956  2612  2612 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-24 20:33:24.956  2612  2612 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:24.956  2612  2612 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:24.956  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:24.956  2612  2612 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:24.956  2612  2612 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 20:33:24.956  2612  2647 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 20:33:24.956   873  1849 D DhcpClient: Clearing IP address
,08-24 20:33:24.957  2612  2612 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-24 20:33:24.957   370   871 D CommandListener: Clearing all IP addresses on wlan0
08-24 20:33:24.957  2612  2612 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:24.957  2612  2612 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:24.958  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:24.958  2612  2612 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:24.959  2612  2612 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 20:33:24.960  2612  2612 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 20:33:24.960   370   871 D CommandListener: Setting iface cfg
,08-24 20:33:24.960  2612  2612 D BluetoothMapService: MAP Service closeService in
08-24 20:33:24.961  2612  2612 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:24.961  2612  2612 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:24.961  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:24.961  2612  2612 V BluetoothAdapterState: isBleTurningOff()=false,
08-24 20:33:24.961  2612  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 20:33:24.961  2612  2642 D BluetoothAdapterProperties: Setting state to 15
08-24 20:33:24.961  2612  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-24 20:33:24.962   873  1866 D DhcpClient: Receive thread stopped
08-24 20:33:24.962  1359  1380 D BluetoothMap: onBluetoothStateChange: up=false
08-24 20:33:24.962   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:24.963  2612  2642 I BluetoothAdapterState: Entering BleOnState
,08-24 20:33:24.963  1932  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:24.963   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:24.963   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 20:33:24.963   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-24 20:33:24.963  1359  2027 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 20:33:24.964  1359  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:24.964  1359  1380 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 20:33:24.965  1359  2027 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 20:33:24.965  1359  1372 D BluetoothPan: onBluetoothStateChange on: false
08-24 20:33:24.966  2612  2642 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 20:33:24.966  2612  2642 D BluetoothAdapterProperties: Setting state to 16,
08-24 20:33:24.966  2612  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-24 20:33:24.966  2612  2642 D BluetoothAdapterProperties: onBleDisable
08-24 20:33:24.967  2612  2642 I BluetoothAdapterState: Entering PendingCommandState
08-24 20:33:24.967  2612  2643 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-24 20:33:24.968  2612  2717 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-24 20:33:24.968  2612  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:24.969  2612  2647 D BluetoothAdapterProperties: Scan Mode:20
,08-24 20:33:24.970  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.971  2612  2612 D BluetoothMapService: cleanup()
08-24 20:33:24.971  2612  2612 D BluetoothMapService: MAP Service closeService in
,08-24 20:33:24.972  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.974  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.976  1526  2195 V NativeCrypto: Read error: ssl=0x9b430600: I/O error during system call, Connection timed out
08-24 20:33:24.976  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:24.978   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
08-24 20:33:24.978  1526  2195 V NativeCrypto: SSL shutdown failed: ssl=0x9b430600: I/O error during system call, Broken pipe
08-24 20:33:24.978   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 20:33:24.978   873  1314 E native  : do suspend true
,08-24 20:33:24.979  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:24.981   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 20:33:24.981   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-24 20:33:24.983   395   395 E Parcel  : Reading a NULL string not supported here.
08-24 20:33:24.983  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:24.983  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:33:24.984  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:24.984  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:24.985   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-24 20:33:25.003  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-24 20:33:25.011   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:33:25.019  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 20:33:25.024  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 20:33:25.036   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf0f3c:true
,08-24 20:33:25.038   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:33:25.038   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-24 20:33:25.039   873  1972 I ActivityManager: Start proc 3932:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-24 20:33:25.039   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-24 20:33:25.039   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:33:25.042   873   890 D Tethering: MasterInitialState.processMessage what=3
08-24 20:33:25.044   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 20:33:25.046  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:25.046  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:25.047  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.047  3417  3417 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@71c3afa and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-24 20:33:25.047  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:25.049  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:25.049  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:25.049  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.049  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:25.051  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:25.051  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:25.063   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 20:33:25.065  2169  2335 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 20:33:25.066  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:25.066  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:25.066  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.066  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:25.068   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 20:33:25.068  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:25.068  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:25.068  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.069  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:25.071  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:25.071  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:25.071  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:25.072  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:25.074  3916  3916 D LocalBluetoothProfileManager: Adding local MAP profile
08-24 20:33:25.075  3916  3916 D BluetoothMap: Create BluetoothMap proxy object
,08-24 20:33:25.088  3916  3916 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-24 20:33:25.093  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-24 20:33:25.101  3916  3916 D DockEventReceiver: finishStartingService: stopping service
08-24 20:33:25.105   370   871 E Netd    : netlink response contains error (No such file or directory)
08-24 20:33:25.109   873   884 I ActivityManager: Killing 3245:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-24 20:33:25.169  2612  2647 I bt_hci  : shut_down
,08-24 20:33:25.173  2612  2653 I bt_vendor: low_power_mode_cb
,08-24 20:33:25.178  2612  2653 D bt_hwcfg: hw_epilog_process
,08-24 20:33:25.191  2612  2653 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 20:33:25.192  2612  2653 I bt_vendor: epilog_cb
08-24 20:33:25.192  2612  2653 I bt_hci  : epilog_finished_callback
,08-24 20:33:25.195  2612  2647 I bt_hci_h4: hal_close
,08-24 20:33:25.195  2612  2647 I bt_userial_vendor: device fd = 51 close
,08-24 20:33:25.284  3932  3932 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.284  3932  3932 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.284  3932  3932 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.284  3932  3932 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.284  3932  3932 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.k.d(PG:583)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.284  3932  3932 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.284  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.285  3932  3932 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.285  3932  3932 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:33:25.285  3932  3932 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:33:25.298  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 20:33:25.309  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 20:33:25.312  3916  3916 D DockEventReceiver: finishStartingService: stopping service
08-24 20:33:25.321   873  2036 I ActivityManager: Killing 3417:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 20:33:25.395  2612  2643 D bt_stack_manager: event_shut_down_stack finished.
,08-24 20:33:25.396  2612  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 20:33:25.405  2612  2642 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-24 20:33:25.405  2612  2612 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 20:33:25.407  2612  2612 D BtGatt.GattService: Received stop request...Stopping profile...
,08-24 20:33:25.407  2612  2612 D BtGatt.GattService: stop()
08-24 20:33:25.407  2612  2612 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 20:33:25.434   873  2036 I ActivityManager: Start proc 3967:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-24 20:33:25.437  2612  2612 V BluetoothAdapterState: isTurningOff()=false
,08-24 20:33:25.437  2612  2612 V BluetoothAdapterState: isTurningOn()=false
,08-24 20:33:25.437  2612  2612 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:25.437  2612  2612 V BluetoothAdapterState: isBleTurningOff()=true
,08-24 20:33:25.438  2612  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25,
08-24 20:33:25.438  2612  2642 D BluetoothAdapterProperties: Setting state to 10
,08-24 20:33:25.439  2612  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 20:33:25.442  2612  2642 I BluetoothAdapterState: Entering OffState
,08-24 20:33:25.442   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 20:33:25.452  2612  2612 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 20:33:25.452  2612  2612 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 20:33:25.453  2612  2612 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 20:33:25.454  2612  2643 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-24 20:33:25.456  2612  2643 D bt_stack_manager: event_clean_up_stack finished.
,08-24 20:33:25.461  2612  2612 I art     : System.exit called, status: 0
08-24 20:33:25.461  2612  2612 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 20:33:25.498  3967  3967 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-24 20:33:25.512   873  1418 I ActivityManager: Process com.android.bluetooth (pid 2612) has died
,08-24 20:33:25.741  3967  3987 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-24 20:33:25.746  3967  3987 I Babel_SMS: MmsConfig.loadMmsSettings
,08-24 20:33:25.747  3967  3987 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-24 20:33:25.747  3967  3987 I Babel_SMS: MmsConfig.loadFromDatabase
,08-24 20:33:25.792  3967  3987 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-24 20:33:25.792  3967  3987 I Babel_SMS: MmsConfig.loadFromResources
,08-24 20:33:25.794  3967  3987 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-24 20:33:25.795  3967  3987 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-24 20:33:25.819  3932  3963 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 20:33:25.852  3967  3967 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 20:33:25.854  3967  3967 I Babel_Crash: startup - clean
,08-24 20:33:25.881  3967  3967 I Babel_telephony: TeleModule.launchCompleted
,08-24 20:33:25.903   873  1418 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-24 20:33:25.912  3967  3967 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-24 20:33:25.926  3967  3967 W Babel   : BAM#gBA: invalid account id: -1
,08-24 20:33:25.926  3967  3967 W Babel   : BAM#gBA: invalid account id: -1
08-24 20:33:25.926  3967  3967 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-24 20:33:25.929  3967  3993 I Babel   : deleted: false for 0
,08-24 20:33:25.935   873  1972 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-24 20:33:25.954  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 20:33:25.957  1752  1752 D SystemUpdateService: onCreate
,08-24 20:33:25.976  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 20:33:25.992  1752  3995 I SystemUpdateService: active receiver: enabled
,08-24 20:33:25.995   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@576bd59:true
,08-24 20:33:26.001  1752  3995 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 20:33:26.002  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 20:33:26.005  1752  2418 I iu.UploadsManager: num queued entries: 0
08-24 20:33:26.006  1752  3995 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 20:33:26.007  1752  2418 I iu.UploadsManager: num updated entries: 0
,08-24 20:33:26.007  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 20:33:26.008  1752  2418 I iu.SyncManager: NEXT; no task
08-24 20:33:26.008  1752  3995 I SystemUpdateService: now status is 0 (complete)
,08-24 20:33:26.009  1752  3995 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 20:33:26.009  1752  3995 I SystemUpdateService: file has been verified
08-24 20:33:26.009  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-24 20:33:26.010  1752  3995 I SystemUpdateService: OTA package size = 12249756
08-24 20:33:26.013  1752  3995 I SystemUpdateService: showing system update notification
,08-24 20:33:26.025   873   883 I ActivityManager: Start proc 3997:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-24 20:33:26.042  3967  3967 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 20:33:26.045  1752  1752 D SystemUpdateService: onDestroy
,08-24 20:33:26.067  3997  3997 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-24 20:33:26.077  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:33:26.094  3997  3997 D SprintDMHelper: simOperator: 
08-24 20:33:26.094  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 20:33:26.110   873  1958 I ActivityManager: Start proc 4009:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-24 20:33:26.119  3967  3967 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 20:33:26.132  3967  3967 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 20:33:26.134  3967  3967 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 20:33:26.147  3967  3967 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 20:33:26.152  3967  3967 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 20:33:26.156   873  2014 I ActivityManager: Killing 3577:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 20:33:26.227  3967  3967 I vclib   : onServiceConnected
,08-24 20:33:26.311   873  1404 I ActivityManager: Start proc 4024:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-24 20:33:26.315  3967  4023 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-24 20:33:26.322   873  1967 I ActivityManager: Killing 3465:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-24 20:33:26.388  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-24 20:33:26.450  4024  4024 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 20:33:26.450  4024  4024 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 20:33:26.450  4024  4024 I GAv4    :   adb logcat -s GAv4
,08-24 20:33:26.470  4024  4024 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 20:33:26.476  4024  4024 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 20:33:26.509  4024  4041 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 20:33:26.622  4024  4024 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-24 20:33:26.665  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 20:33:26.674  4024  4024 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2974-2978)
,08-24 20:33:26.674  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 20:33:26.687  4024  4024 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {87956aa}
08-24 20:33:26.688  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 20:33:26.688  4024  4024 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 20:33:26.697  4024  4024 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-24 20:33:26.698  4024  4024 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 20:33:26.715  4024  4024 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 20:33:26.728  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 20:33:26.728  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 20:33:26.728  4024  4024 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 20:33:26.728  4024  4024 I Adreno  : Build Date                       : 10/20/15
08-24 20:33:26.728  4024  4024 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 20:33:26.728  4024  4024 I Adreno  : Local Branch                     : M14
08-24 20:33:26.728  4024  4024 I Adreno  : Remote Branch                    : 
08-24 20:33:26.728  4024  4024 I Adreno  : Remote Branch                    : 
08-24 20:33:26.728  4024  4024 I Adreno  : Reconstruct Branch               : 
,08-24 20:33:26.793  4024  4024 I NSApplication: Starting up...
,08-24 20:33:26.806  4024  4070 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 20:33:26.842   873  1967 I ActivityManager: Start proc 4075:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-24 20:33:26.844   873  1967 I ActivityManager: Killing 3500:android.process.acore/u0a5 (adj 15): empty #17
,08-24 20:33:26.934  4075  4075 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-24 20:33:27.120   873  1967 I ActivityManager: Killing 3687:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-24 20:33:27.252   873  1972 I ActivityManager: Start proc 4089:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-24 20:33:27.324  4089  4089 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-24 20:33:27.383  4089  4089 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-24 20:33:27.458   873  1972 I ActivityManager: Killing 3702:com.android.musicfx/u0a18 (adj 15): empty #17
,08-24 20:33:29.904   873  1967 D WifiService: setWifiEnabled: true pid=3831, uid=10000
,08-24 20:33:29.904   873  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 20:33:29.917   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-24 20:33:29.926  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:29.926  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:29.926  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:29.926  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:33:29.927  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:29.927  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:29.927  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:29.928  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:29.931  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:29.931  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:29.931  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:29.931  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:33:29.956   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-24 20:33:29.957   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-24 20:33:29.958   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-24 20:33:29.959   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-24 20:33:29.959   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-24 20:33:29.959   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-24 20:33:29.959   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 20:33:29.970   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 20:33:29.971   370   871 D CommandListener: Setting iface cfg
,08-24 20:33:29.971   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 20:33:29.972   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
08-24 20:33:29.972   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 20:33:29.981   873  1314 E native  : do suspend true
,08-24 20:33:29.981   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 20:33:29.987   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 20:33:29.998   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:33:30.907   873  2001 I ActivityManager: Killing 2244:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-24 20:33:31.286   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 20:33:31.374   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.12 rxSuccessRate=7.19 delta 1000 -> 994
,08-24 20:33:31.379   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 20:33:31.380   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 20:33:31.395   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 20:33:31.445   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 20:33:31.450  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 20:33:31.873  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 20:33:31.902  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:31.911  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 20:33:31.912  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 20:33:31.912  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:31.918  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:31.919   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:33:31.926   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 20:33:31.926   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 20:33:31.926   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 20:33:31.945   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 20:33:31.955   370   871 D CommandListener: Setting iface cfg
,08-24 20:33:31.958   873  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-24 20:33:31.964   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 20:33:31.978  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 20:33:31.978  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 20:33:31.978  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:33:31.979  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 20:33:31.979   873  4124 D DhcpClient: Receive thread started
,08-24 20:33:32.000  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 20:33:32.000  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 20:33:32.001  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-24 20:33:32.061   873  1314 E native  : do suspend false
,08-24 20:33:32.084   873  1849 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 20:33:32.103   873  4124 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172644, domain null
,08-24 20:33:32.105   873  1849 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172644 seconds
,08-24 20:33:32.108   873  1849 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 20:33:32.123   873  4124 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 20:33:32.124   873  1849 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 20:33:32.129   370   871 D CommandListener: Setting iface cfg
,08-24 20:33:32.142   873  1849 D DhcpClient: Scheduling renewal in 86399s
,08-24 20:33:32.142   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 20:33:32.147   873  1314 E native  : do suspend true
,08-24 20:33:32.168   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 20:33:32.170   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 20:33:32.171   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 20:33:32.174   873  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-24 20:33:32.175   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 20:33:32.224   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 20:33:32.224   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 20:33:32.226   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-24 20:33:32.227   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-24 20:33:32.229   873  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-24 20:33:32.241   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 20:33:32.247   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-24 20:33:32.247   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-24 20:33:32.247   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 20:33:32.248   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 20:33:32.248   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-24 20:33:32.248   873  1316 D ConnectivityService:    accepting network in place of null
,08-24 20:33:32.250   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 20:33:32.257   873  4123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=178561, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 20:33:32.280   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:33:32.313   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:33:32.322   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 20:33:32.323   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:33:32.332   873  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:80f::200e
,08-24 20:33:32.332   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 20:33:32.340   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-24 20:33:32.343  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:32.343  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:33:32.343  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:32.343  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:32.347  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:32.347  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 20:33:32.347  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:32.347  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:32.350  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:33:32.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:33:32.350  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:32.350  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:33:32.369  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 20:33:32.379  1752  1752 D SystemUpdateService: onCreate
,08-24 20:33:32.392  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 20:33:32.414   873  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 18:33:32 GMT], X-Android-Received-Millis=[1472063612414], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472063612382]}
,08-24 20:33:32.415   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 20:33:32.416   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-24 20:33:32.416   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 20:33:32.426   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 20:33:32.435  1752  4134 I SystemUpdateService: active receiver: enabled
,08-24 20:33:32.467  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:32.477  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 20:33:32.480  1752  2418 I iu.UploadsManager: num queued entries: 0
08-24 20:33:32.480  1752  2418 I iu.UploadsManager: num updated entries: 0
,08-24 20:33:32.492  1752  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 20:33:32.497  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 20:33:32.504  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 20:33:32.514  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:33:32.519  1752  4138 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 20:33:32.519  1752  4138 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 20:33:32.520  1752  4138 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 20:33:32.525  3997  3997 D SprintDMHelper: simOperator: 
,08-24 20:33:32.525  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 20:33:32.531  1752  4134 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 20:33:32.554  1752  2418 I iu.SyncManager: NEXT; no task
,08-24 20:33:32.550  1752  4134 I SystemUpdateService: now status is 0 (complete)
,08-24 20:33:32.554  1752  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 20:33:32.554  1752  4134 I SystemUpdateService: file has been verified
,08-24 20:33:32.555  1752  4134 I SystemUpdateService: OTA package size = 12249756
,08-24 20:33:32.606  1752  4134 I SystemUpdateService: showing system update notification
,08-24 20:33:32.671  1526  4148 I VacuumService: Vacuum at: now=1472063612671 tag=VacuumService
,08-24 20:33:32.708  3967  4143 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 20:33:32.765  1752  1752 D SystemUpdateService: onDestroy
,08-24 20:33:32.806  1526  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 20:33:32.807  1526  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-24 20:33:32.807  1526  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:33:32.807  1526  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:32.875  1526  4149 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-24 20:33:32.877  1526  4149 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 20:33:32.930  1526  4149 W Uploader:  no longer exists, so no auth token.
,08-24 20:33:32.958  1752  4138 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-24 20:33:33.322   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 20:33:34.048  1526  4149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 20:33:34.048  1526  4149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 20:33:34.048  1526  4149 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:33:34.048  1526  4149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:34.062  1526  4149 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 20:33:34.062  1526  4149 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 20:33:34.062  1526  4149 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 20:33:34.331  1526  4149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 20:33:34.331  1526  4149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 20:33:34.331  1526  4149 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:33:34.331  1526  4149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:34.355  1526  4149 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 20:33:34.355  1526  4149 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 20:33:34.355  1526  4149 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 20:33:34.910   873   884 D WifiService: setWifiEnabled: false pid=3831, uid=10000
,08-24 20:33:34.911   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 20:33:34.928  1526  4149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 20:33:34.928  1526  4149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 20:33:34.928  1526  4149 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:33:34.928  1526  4149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:34.936  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 20:33:34.938   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 20:33:34.939   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-24 20:33:34.939   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 20:33:34.939   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 20:33:34.954   873  1314 E native  : do suspend true
,08-24 20:33:34.955  1526  4149 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 20:33:34.955  1526  4149 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 20:33:34.955  1526  4149 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 20:33:34.960   873  1849 D DhcpClient: Clearing IP address
,08-24 20:33:34.960   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-24 20:33:34.965  1526  4146 V NativeCrypto: Read error: ssl=0x9ad2b600: I/O error during system call, Connection timed out
,08-24 20:33:34.966  1526  4146 V NativeCrypto: SSL shutdown failed: ssl=0x9ad2b600: I/O error during system call, Broken pipe
08-24 20:33:34.966   370   871 D CommandListener: Setting iface cfg
08-24 20:33:34.967   873  4124 D DhcpClient: Receive thread stopped
,08-24 20:33:34.969   873  1967 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-24 20:33:34.969   873  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-24 20:33:34.971   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 20:33:34.971   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-24 20:33:34.973   395   395 E Parcel  : Reading a NULL string not supported here.
,08-24 20:33:34.977   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
08-24 20:33:34.978   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 20:33:34.978   873  1314 E native  : do suspend true
08-24 20:33:34.979   873  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-24 20:33:34.988   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-24 20:33:34.990   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-24 20:33:34.990   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 20:33:35.005   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:33:35.006  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:35.006  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:35.007  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:35.007  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:33:35.008  2169  2335 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 20:33:35.008  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:35.008  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:35.008  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:35.008  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:35.009  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:35.009  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:35.009  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:35.009  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:35.011   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 20:33:35.016  1526  4149 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-24 20:33:35.021   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:33:35.049   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:33:35.051   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 20:33:35.051   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 20:33:35.054   873   890 D Tethering: MasterInitialState.processMessage what=3
08-24 20:33:35.059  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:35.060  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:35.062  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:35.099  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 20:33:35.103  1752  1752 D SystemUpdateService: onCreate
,08-24 20:33:35.105  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 20:33:35.113  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 20:33:35.115  1752  2418 I iu.UploadsManager: num queued entries: 0
08-24 20:33:35.115  1752  2418 I iu.UploadsManager: num updated entries: 0
,08-24 20:33:35.120  1752  2418 I iu.SyncManager: NEXT; no task
,08-24 20:33:35.121  1752  4174 I SystemUpdateService: active receiver: enabled
,08-24 20:33:35.124  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 20:33:35.125  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 20:33:35.128  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:33:35.133  1752  4174 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 20:33:35.134  1752  4174 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 20:33:35.135  1752  4174 I SystemUpdateService: now status is 0 (complete)
,08-24 20:33:35.135  1752  4174 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 20:33:35.135  1752  4174 I SystemUpdateService: file has been verified
08-24 20:33:35.135  1752  4174 I SystemUpdateService: OTA package size = 12249756
,08-24 20:33:35.136  3997  3997 D SprintDMHelper: simOperator: 
,08-24 20:33:35.136  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 20:33:35.159   370   871 E Netd    : netlink response contains error (No such file or directory)
,08-24 20:33:35.160   873  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 20:33:35.160   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 20:33:35.164  3967  4177 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 20:33:35.173  1752  4174 I SystemUpdateService: showing system update notification
,08-24 20:33:35.197  1752  1752 D SystemUpdateService: onDestroy
,08-24 20:33:39.969   873   890 I ActivityManager: Start proc 4183:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 20:33:40.103  4183  4183 D AdapterServiceConfig: Adding HeadsetService
,08-24 20:33:40.104  4183  4183 D AdapterServiceConfig: Adding A2dpService
08-24 20:33:40.104  4183  4183 D AdapterServiceConfig: Adding HidService
08-24 20:33:40.104  4183  4183 D AdapterServiceConfig: Adding HealthService
08-24 20:33:40.105  4183  4183 D AdapterServiceConfig: Adding PanService
,08-24 20:33:40.105  4183  4183 D AdapterServiceConfig: Adding GattService
08-24 20:33:40.105  4183  4183 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 20:33:40.120  4183  4183 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 20:33:40.120   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb4aa49:true
,08-24 20:33:40.126  4183  4183 I bt_bluedroid: init
,08-24 20:33:40.126  4183  4195 I BluetoothAdapterState: Entering OffState
,08-24 20:33:40.131  4183  4196 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 20:33:40.131  4183  4196 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-24 20:33:40.132  4183  4196 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-24 20:33:40.132  4183  4196 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 20:33:40.134  4183  4183 I bt_bluedroid: get_profile_interface socket
,08-24 20:33:40.136  4183  4183 I bt_bluedroid: get_profile_interface sdp
,08-24 20:33:40.141  4183  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-24 20:33:40.141  4183  4194 I bt_bluedroid: config_hci_snoop_log
,08-24 20:33:40.143  4183  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 20:33:40.144   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 20:33:40.156  4183  4195 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 20:33:40.157  4183  4195 D BluetoothAdapterProperties: Setting state to 14
08-24 20:33:40.157  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 20:33:40.161  4183  4195 D BluetoothBondStateMachine: make
,08-24 20:33:40.166  4183  4200 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 20:33:40.172  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-24 20:33:40.173  4183  4183 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 20:33:40.179  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:40.180  4183  4183 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 20:33:40.182  4183  4183 D BtGatt.GattService: Received start request. Starting profile...
,08-24 20:33:40.182  4183  4183 D BtGatt.GattService: start()
08-24 20:33:40.182  4183  4183 I bt_bluedroid: get_profile_interface gatt
08-24 20:33:40.184  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:40.184  4183  4183 D BtGatt.AdvertiseManager: advertise manager created
,08-24 20:33:40.198  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:40.198  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:40.198  4183  4183 V BluetoothAdapterState: isBleTurningOn()=true
,08-24 20:33:40.198  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:40.199  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-24 20:33:40.200  4183  4195 I bt_bluedroid: enable
08-24 20:33:40.200  4183  4196 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-24 20:33:40.202  4183  4196 I bt_hci  : start_up
,08-24 20:33:40.222  4183  4196 I bt_vendor: alloc value 0xb39ba189
08-24 20:33:40.222  4183  4196 I bt_vendor: init
08-24 20:33:40.222  4183  4196 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 20:33:40.223  4183  4196 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 20:33:40.251   873  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-24 20:33:40.331  4183  4196 D bt_hci  : start_up starting async portion
,08-24 20:33:40.332  4183  4203 I bt_hci  : event_finish_startup
08-24 20:33:40.332  4183  4203 I bt_hci_h4: hal_open
,08-24 20:33:40.333  4183  4203 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 20:33:40.341  4183  4203 I bt_userial_vendor: device fd = 51 open
,08-24 20:33:40.373  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 20:33:40.405  4183  4203 D bt_hwcfg: Chipset BCM4354A2
,08-24 20:33:40.405  4183  4203 D bt_hwcfg: Target name = [BCM4354A2]
08-24 20:33:40.406  4183  4203 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 20:33:41.068  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 20:33:41.069  4183  4203 D bt_hwcfg: Settlement delay -- 100 ms
,08-24 20:33:41.069  4183  4203 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 20:33:41.186  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 20:33:41.187  4183  4203 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 20:33:41.217  4183  4203 I bt_hwcfg: vendor lib fwcfg completed
,08-24 20:33:41.217  4183  4203 I bt_vendor: firmware callback
08-24 20:33:41.217  4183  4203 I bt_hci  : firmware_config_callback
,08-24 20:33:41.230  4183  4205 I bt_btu  : btu_task pending for preload complete event
,08-24 20:33:41.230  4183  4205 I bt_btu_task: Bluetooth chip preload is complete
,08-24 20:33:41.231  4183  4205 I bt_btu  : btu_task received preload complete event
,08-24 20:33:41.240  4183  4205 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 20:33:41.241  4183  4205 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 20:33:41.241  4183  4205 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 20:33:41.241  4183  4205 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 20:33:41.242  4183  4205 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 20:33:41.242  4183  4205 I         : BTE_InitTraceLevels -- TRC_A2D
,08-24 20:33:41.242  4183  4205 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 20:33:41.243  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 20:33:41.243  4183  4205 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 20:33:41.244  4183  4205 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 20:33:41.244  4183  4205 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 20:33:41.244  4183  4205 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 20:33:41.244  4183  4205 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 20:33:41.245  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-24 20:33:41.245  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 20:33:41.383  4183  4205 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3937d9d
,08-24 20:33:41.383  4183  4205 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3937d9d 
,08-24 20:33:41.396  4183  4199 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 20:33:41.398  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 20:33:41.398  4183  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-24 20:33:41.402  4183  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 20:33:41.405  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-24 20:33:41.406  4183  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 20:33:41.406  4183  4199 D bt_hci  : do_postload posting postload work item
08-24 20:33:41.406  4183  4203 I bt_hci  : event_postload
08-24 20:33:41.407  4183  4203 I bt_vendor: sco_config_cb
08-24 20:33:41.407  4183  4203 I bt_hci  : sco_config_callback postload finished.
,08-24 20:33:41.407  4183  4199 D bt_bte_conf: Device ID record 1 : primary
08-24 20:33:41.407  4183  4199 D bt_bte_conf:   vendorId            = 000f
08-24 20:33:41.407  4183  4199 D bt_bte_conf:   vendorIdSource      = 0001
08-24 20:33:41.407  4183  4199 D bt_bte_conf:   product             = 1200
,08-24 20:33:41.407  4183  4199 D bt_bte_conf:   version             = 1436
08-24 20:33:41.407  4183  4199 D bt_bte_conf:   clientExecutableURL = 
08-24 20:33:41.407  4183  4199 D bt_bte_conf:   serviceDescription  = 
,08-24 20:33:41.407  4183  4199 D bt_bte_conf:   documentationURL    = 
,08-24 20:33:41.408  4183  4199 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 20:33:41.408  4183  4196 D bt_stack_manager: event_start_up_stack finished
,08-24 20:33:41.408  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-24 20:33:41.409  4183  4195 D BluetoothAdapterProperties: Setting state to 15
,08-24 20:33:41.409  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 20:33:41.410  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:41.412  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:41.416  4183  4195 I BluetoothAdapterState: Entering BleOnState
08-24 20:33:41.421  4183  4203 I bt_vendor: low_power_mode_cb
08-24 20:33:41.422  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:41.423  4183  4195 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-24 20:33:41.423  4183  4195 D BluetoothAdapterProperties: Setting state to 11,
08-24 20:33:41.423  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 20:33:41.430  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:41.431  4183  4183 D HeadsetService: Received start request. Starting profile...
08-24 20:33:41.433  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:41.436  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:41.437  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:41.440  4183  4183 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 20:33:41.440  4183  4183 D HeadsetStateMachine: make
08-24 20:33:41.443  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-24 20:33:41.450  4183  4183 D HeadsetStateMachine: max_hf_connections = 1
,08-24 20:33:41.450  4183  4183 I bt_bluedroid: get_profile_interface handsfree
,08-24 20:33:41.450  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 20:33:41.451  4183  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-24 20:33:41.455  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 20:33:41.455  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:41.456  4183  4183 D A2dpService: Received start request. Starting profile...
,08-24 20:33:41.457  4183  4183 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 20:33:41.457  4183  4183 I bt_bluedroid: get_profile_interface avrcp
,08-24 20:33:41.463  4183  4183 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 20:33:41.463  4183  4183 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 20:33:41.463  4183  4183 D A2dpStateMachine: make
,08-24 20:33:41.464  4183  4183 I bt_bluedroid: get_profile_interface a2dp
08-24 20:33:41.465  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048,
08-24 20:33:41.466  4183  4215 D A2dpStateMachine: Enter Disconnected: -2
,08-24 20:33:41.467  4183  4183 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 20:33:41.467  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:41.469  4183  4183 D HidService: Received start request. Starting profile...
,08-24 20:33:41.470  4183  4183 I bt_bluedroid: get_profile_interface hidhost
08-24 20:33:41.470  4183  4183 D HidService: setHidService(): set to: null
08-24 20:33:41.469  3916  3916 D BluetoothInputDevice: Proxy object connected
08-24 20:33:41.470  4183  4199 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39193e5
08-24 20:33:41.470  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 20:33:41.471  4183  4183 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 20:33:41.471  3916  3916 D HidProfile: Bluetooth service connected
08-24 20:33:41.471  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:41.472  4183  4183 D HealthService: Received start request. Starting profile...
,08-24 20:33:41.473  4183  4183 I bt_bluedroid: get_profile_interface health
08-24 20:33:41.474  4183  4183 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 20:33:41.475  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:41.476  4183  4183 D PanService: Received start request. Starting profile...
,08-24 20:33:41.476  3916  3916 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 20:33:41.476  4183  4183 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 20:33:41.476  4183  4183 I bt_bluedroid: get_profile_interface pan
,08-24 20:33:41.477  3916  3916 D PanProfile: Bluetooth service connected
08-24 20:33:41.477  4183  4199 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 20:33:41.479  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:41.481  4183  4183 D BluetoothMapService: Received start request. Starting profile...
08-24 20:33:41.481  4183  4183 D BluetoothMapService: start()
08-24 20:33:41.481  3916  3916 D BluetoothMap: Proxy object connected
,08-24 20:33:41.481  3916  3916 D MapProfile: Bluetooth service connected
08-24 20:33:41.481  3916  3916 D BluetoothMap: getConnectedDevices()
,08-24 20:33:41.482  3916  3916 D BluetoothMap: Bluetooth is Not enabled
08-24 20:33:41.483  4183  4183 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-24 20:33:41.484  4183  4183 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-24 20:33:41.484  4183  4183 D BluetoothMapAppObserver: createReceiver()
08-24 20:33:41.485  4183  4183 D BluetoothMapAppObserver: initObservers()
,08-24 20:33:41.485  4183  4183 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 20:33:41.493  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-24 20:33:41.493  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:41.493  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:41.494  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:41.496  4183  4213 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 20:33:41.496  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:41.497  4183  4183 V BluetoothAdapterState: isTurningOn()=true
,08-24 20:33:41.497  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:41.497  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:41.498  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:41.498  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:41.498  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:41.498  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:41.498  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:41.498  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:41.499  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:41.499  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:41.500  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:41.500  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:41.500  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:41.500  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:41.500  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:41.500  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:41.501  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:41.501  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:41.501  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-24 20:33:41.501  4183  4195 D BluetoothAdapterProperties: ScanMode =  20
08-24 20:33:41.501  4183  4195 D BluetoothAdapterProperties: State =  11
,08-24 20:33:41.502  4183  4195 D BluetoothAdapterProperties: Setting state to 12
08-24 20:33:41.502  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 20:33:41.502  1359  1380 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 20:33:41.503  4183  4199 D BluetoothAdapterProperties: Scan Mode:21
08-24 20:33:41.503  4183  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 20:33:41.504  4183  4195 I BluetoothAdapterState: Entering OnState
,08-24 20:33:41.505   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:41.505  1359  1359 D BluetoothMap: Proxy object connected
08-24 20:33:41.505  1359  1359 D MapProfile: Bluetooth service connected
08-24 20:33:41.505  3916  3927 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 20:33:41.505  1359  1359 D BluetoothMap: getConnectedDevices()
,08-24 20:33:41.506  3916  3926 D BluetoothPan: onBluetoothStateChange on: true
,08-24 20:33:41.507  1932  1946 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:41.507   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 20:33:41.507   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 20:33:41.508   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 20:33:41.508  1359  2027 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:41.509  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:41.509   873   873 D BluetoothA2dp: Proxy object connected
,08-24 20:33:41.510  1359  1359 D BluetoothInputDevice: Proxy object connected
08-24 20:33:41.511  1359  1359 D HidProfile: Bluetooth service connected
08-24 20:33:41.511  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:33:41.511  3916  3927 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 20:33:41.512  1359  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:41.513  3916  3926 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 20:33:41.514  4183  4183 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:41.515  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:41.515  4183  4183 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 20:33:41.516  1359  2027 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 20:33:41.517  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:33:41.517  4183  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 20:33:41.518  1359  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 20:33:41.519  1359  1359 D BluetoothA2dp: Proxy object connected
,08-24 20:33:41.520  1359  2027 D BluetoothPan: onBluetoothStateChange on: true
,08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:41.521  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:41.522  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 20:33:41.522  1359  1359 D PanProfile: Bluetooth service connected
08-24 20:33:41.523   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 20:33:41.523  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:41.526  4183  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 20:33:41.526  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:41.527  4183  4183 D ObexServerSockets: Succeed to create listening sockets 
08-24 20:33:41.527  4183  4183 D ObexServerSockets0: startAccept()
08-24 20:33:41.527  4183  4183 D ObexServerSockets0: prepareForNewConnect()
08-24 20:33:41.528  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:41.529  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:41.530  4183  4183 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-24 20:33:41.530  4183  4183 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 20:33:41.530  3916  3916 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 20:33:41.531  4183  4183 D BluetoothMapService: onReceive
,08-24 20:33:41.531  4183  4183 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 20:33:41.531  4183  4221 D ObexServerSockets0: Accepting socket connection...
08-24 20:33:41.531  4183  4183 D BluetoothMapService: STATE_ON
08-24 20:33:41.531  4183  4222 D ObexServerSockets0: Accepting socket connection...
08-24 20:33:41.535  3916  3916 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-24 20:33:41.543  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 20:33:41.545  3916  3916 D BluetoothA2dp: Proxy object connected
,08-24 20:33:41.550  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 20:33:41.550  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,08-24 20:33:41.560  1359  1359 D BluetoothPbap: Proxy object connected
,08-24 20:33:41.561  3916  3916 D BluetoothPbap: Proxy object connected
08-24 20:33:41.561  1359  1359 D PbapServerProfile: Bluetooth service connected
08-24 20:33:41.561  3916  3916 D PbapServerProfile: Bluetooth service connected
08-24 20:33:41.561  4183  4183 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 20:33:41.561  4183  4183 D ObexServerSockets0: prepareForNewConnect()
,08-24 20:33:41.569  4183  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 20:33:41.588  4183  4230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 20:33:41.589  4183  4230 I BtOppRfcommListener: Accept thread started.
,08-24 20:33:41.607   873   873 D BluetoothHeadset: Proxy object connected
,08-24 20:33:41.607  1932  2056 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.607  1932  1953 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.608   873   890 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.608   873   873 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.608   873   890 D BluetoothHeadset: Proxy object connected
,08-24 20:33:41.608  1359  1380 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.608   873   873 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.608  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-24 20:33:41.613  1359  1372 D BluetoothHeadset: Proxy object connected
,08-24 20:33:41.613  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-24 20:33:41.638  3916  3927 D BluetoothHeadset: Proxy object connected
08-24 20:33:41.639  3916  3916 D HeadsetProfile: Bluetooth service connected
,08-24 20:33:44.937  4183  4195 D BluetoothAdapterState: Current state: ON, message: 23
08-24 20:33:44.937  4183  4195 D BluetoothAdapterProperties: Setting state to 13
08-24 20:33:44.937  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-24 20:33:44.939  4183  4195 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 20:33:44.942  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-24 20:33:44.950  4183  4183 D BluetoothMapService: onReceive
,08-24 20:33:44.951  4183  4183 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 20:33:44.951  4183  4183 D BluetoothMapService: STATE_TURNING_OFF
08-24 20:33:44.952  4183  4183 D BluetoothMapService: MAP Service closeService in
,08-24 20:33:44.952  4183  4183 D BluetoothMapMasInstance0: MAP Service shutdown
,08-24 20:33:44.952  4183  4183 D ObexServerSockets0: shutdown(block = true)
08-24 20:33:44.953  4183  4221 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 20:33:44.954  4183  4183 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 20:33:44.954  4183  4183 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 20:33:44.954  4183  4222 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-24 20:33:44.955  4183  4207 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 20:33:44.959  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:44.959  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:44.958  4183  4183 I BtOppRfcommListener: stopping Accept Thread
,08-24 20:33:44.961  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:44.961  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:44.963  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-24 20:33:44.963  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 20:33:44.964  4183  4230 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 20:33:44.964  4183  4230 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 20:33:44.964  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:44.965  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:44.965  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:44.966  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:44.968  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:44.968  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:44.970  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 20:33:44.970  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:44.971  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:44.972  4183  4183 D HeadsetService: Received stop request...Stopping profile...
08-24 20:33:44.973  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:44.974   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 20:33:44.975  1932  1946 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:44.975  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:44.975  3916  3926 D BluetoothHeadset: Proxy object disconnected
,08-24 20:33:44.975  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 20:33:44.975   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:44.976  1359  2027 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:44.976  1359  1359 D HeadsetProfile: Bluetooth service disconnected,
08-24 20:33:44.976   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 20:33:44.978  4183  4183 D A2dpService: Received stop request...Stopping profile...
08-24 20:33:44.978  4183  4215 D A2dpStateMachine: Exit Disconnected: -1
08-24 20:33:44.980   873   873 D BluetoothA2dp: Proxy object disconnected
,08-24 20:33:44.980  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-24 20:33:44.980  4183  4183 D HidService: Received stop request...Stopping profile...
08-24 20:33:44.981  4183  4183 D HidService: Stopping Bluetooth HidService
,08-24 20:33:44.982  3916  3916 D HeadsetProfile: Bluetooth service disconnected
,08-24 20:33:44.982  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-24 20:33:44.982  1359  1359 D HidProfile: Bluetooth service disconnected
08-24 20:33:44.982  4183  4183 D HealthService: Received stop request...Stopping profile...
,08-24 20:33:44.984  4183  4183 D PanService: Received stop request...Stopping profile...
,08-24 20:33:44.985  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 20:33:44.985  1359  1359 D PanProfile: Bluetooth service disconnected
08-24 20:33:44.986  4183  4183 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 20:33:44.986  4183  4183 D BluetoothMapService: stop()
08-24 20:33:44.986  4183  4183 D BluetoothMapAppObserver: deinitObservers()
,08-24 20:33:44.986  4183  4183 D BluetoothMapAppObserver: removeReceiver()
08-24 20:33:44.987  3916  3916 D DockEventReceiver: finishStartingService: stopping service
08-24 20:33:44.988  1359  1359 D BluetoothMap: Proxy object disconnected
08-24 20:33:44.988  1359  1359 D MapProfile: Bluetooth service disconnected
,08-24 20:33:44.988  4183  4183 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:44.988  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:44.988  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:44.988  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:44.988  3916  3916 D BluetoothA2dp: Proxy object disconnected
08-24 20:33:44.988  3916  3916 D BluetoothInputDevice: Proxy object disconnected
,08-24 20:33:44.988  3916  3916 D HidProfile: Bluetooth service disconnected
08-24 20:33:44.989  3916  3916 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 20:33:44.989  3916  3916 D PanProfile: Bluetooth service disconnected
08-24 20:33:44.989  4183  4183 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 20:33:44.989  4183  4183 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 20:33:44.990  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 20:33:44.990  4183  4183 V BluetoothAdapterState: isTurningOff()=true
08-24 20:33:44.990  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:44.990  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:44.990  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 20:33:44.990  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:44.990  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:44.990  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 20:33:44.991  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-24 20:33:44.991  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:44.991  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:44.991  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:44.991  4183  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-24 20:33:44.991  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:44.992  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:44.992  3916  3916 D BluetoothMap: Proxy object disconnected
,08-24 20:33:44.992  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 20:33:44.992  3916  3916 D MapProfile: Bluetooth service disconnected
08-24 20:33:44.992  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-24 20:33:44.992  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 20:33:44.992  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 20:33:44.992  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 20:33:44.993  4183  4183 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-24 20:33:44.993  4183  4183 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 20:33:44.993  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-24 20:33:44.993  4183  4183 V BluetoothAdapterState: isTurningOn()=false
,08-24 20:33:44.993  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:44.993  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:44.993  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 20:33:44.993  4183  4183 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 20:33:44.994  4183  4199 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-24 20:33:44.994  4183  4183 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 20:33:44.994  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-24 20:33:44.994  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:44.994  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:44.994  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:44.995  4183  4183 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-24 20:33:44.995  4183  4183 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 20:33:44.996  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 20:33:44.996  4183  4183 D BluetoothMapService: MAP Service closeService in
08-24 20:33:44.996  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-24 20:33:44.996  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:44.996  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:44.996  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:44.997  4183  4183 D BluetoothMapService: cleanup()
08-24 20:33:44.997  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 20:33:44.997  4183  4183 D BluetoothMapService: MAP Service closeService in
08-24 20:33:44.997  4183  4195 D BluetoothAdapterProperties: Setting state to 15
,08-24 20:33:44.997  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 20:33:45.000  1359  1359 D BluetoothPbap: Proxy object disconnected
,08-24 20:33:45.000  1359  1359 D PbapServerProfile: Bluetooth service disconnected
,08-24 20:33:45.002  1359  1372 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 20:33:45.007   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:45.008  3916  3927 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:44.999  4183  4195 I BluetoothAdapterState: Entering BleOnState
08-24 20:33:45.008  3916  3926 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 20:33:45.012  3916  3916 D BluetoothPbap: Proxy object disconnected
08-24 20:33:45.012  3916  3916 D PbapServerProfile: Bluetooth service disconnected
,08-24 20:33:45.012  3916  3927 D BluetoothPan: onBluetoothStateChange on: false
,08-24 20:33:45.013  1932  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 20:33:45.013   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 20:33:45.013   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 20:33:45.013   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 20:33:45.013  1359  1380 D BluetoothInputDevice: onBluetoothStateChange: up=false,
08-24 20:33:45.014  3916  3926 D BluetoothMap: onBluetoothStateChange: up=false
08-24 20:33:45.014  1359  2027 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 20:33:45.015  3916  3927 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 20:33:45.015  1359  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 20:33:45.016  3916  3926 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 20:33:45.016  1359  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 20:33:45.017  1359  2027 D BluetoothPan: onBluetoothStateChange on: false
,08-24 20:33:45.017  4183  4195 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-24 20:33:45.017  4183  4195 D BluetoothAdapterProperties: Setting state to 16
08-24 20:33:45.017  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 20:33:45.018  4183  4195 D BluetoothAdapterProperties: onBleDisable,
08-24 20:33:45.018  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
08-24 20:33:45.019  4183  4196 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 20:33:45.021  4183  4205 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-24 20:33:45.021  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:45.021  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 20:33:45.021  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-24 20:33:45.026  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:45.027  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:45.028  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:45.028  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 20:33:45.029  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:45.030  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:45.032  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 20:33:45.034  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,08-24 20:33:45.225  4183  4199 I bt_hci  : shut_down
,08-24 20:33:45.226  4183  4203 D bt_hwcfg: hw_epilog_process
,08-24 20:33:45.239  4183  4203 I bt_vendor: low_power_mode_cb
,08-24 20:33:45.260  4183  4203 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 20:33:45.260  4183  4203 I bt_vendor: epilog_cb
08-24 20:33:45.260  4183  4203 I bt_hci  : epilog_finished_callback
,08-24 20:33:45.266  4183  4199 I bt_hci_h4: hal_close
,08-24 20:33:45.267  4183  4199 I bt_userial_vendor: device fd = 51 close
,08-24 20:33:45.387  4183  4196 D bt_stack_manager: event_shut_down_stack finished.
,08-24 20:33:45.389  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 20:33:45.397  4183  4183 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 20:33:45.398  4183  4195 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-24 20:33:45.399  4183  4183 D BtGatt.GattService: Received stop request...Stopping profile...
,08-24 20:33:45.399  4183  4183 D BtGatt.GattService: stop()
,08-24 20:33:45.399  4183  4183 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 20:33:45.404  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-24 20:33:45.404  4183  4183 V BluetoothAdapterState: isTurningOn()=false
,08-24 20:33:45.405  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 20:33:45.405  4183  4183 V BluetoothAdapterState: isBleTurningOff()=true
08-24 20:33:45.406  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-24 20:33:45.407  4183  4195 D BluetoothAdapterProperties: Setting state to 10
08-24 20:33:45.407  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 20:33:45.410  4183  4195 I BluetoothAdapterState: Entering OffState
08-24 20:33:45.411   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 20:33:45.434  4183  4183 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-24 20:33:45.434  4183  4183 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 20:33:45.435  4183  4196 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-24 20:33:45.439  4183  4196 D bt_stack_manager: event_clean_up_stack finished.
,08-24 20:33:45.440  4183  4183 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 20:33:45.444  4183  4183 I art     : System.exit called, status: 0
08-24 20:33:45.444  4183  4183 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 20:33:45.489   873  1958 I ActivityManager: Process com.android.bluetooth (pid 4183) has died
,08-24 20:33:49.933  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:49.933  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:33:49.940  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:49.940  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebb774b removed from the list
,08-24 20:33:49.940  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:49.941  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:33:49.941  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:49.944  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 20:33:49.945  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f92241 added. We now have 4 listener(s)
08-24 20:33:49.945  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:33:49.948  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:33:49.949  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f92241 removed from the list
08-24 20:33:49.949  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:33:49.949  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:49.950  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:33:49.953  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:33:49.954  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc993e6 added. We now have 4 listener(s)
,08-24 20:33:49.955  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:33:54.948  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:54.963  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:54.971  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:54.979  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:33:55.021   873   890 I ActivityManager: Start proc 4244:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 20:33:55.091  1526  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 20:33:55.091  1526  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 20:33:55.091  1526  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:33:55.091  1526  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:33:55.124  4244  4244 D AdapterServiceConfig: Adding HeadsetService
,08-24 20:33:55.124  4244  4244 D AdapterServiceConfig: Adding A2dpService
,08-24 20:33:55.124  4244  4244 D AdapterServiceConfig: Adding HidService
,08-24 20:33:55.125  4244  4244 D AdapterServiceConfig: Adding HealthService
,08-24 20:33:55.125  4244  4244 D AdapterServiceConfig: Adding PanService
,08-24 20:33:55.125  4244  4244 D AdapterServiceConfig: Adding GattService
,08-24 20:33:55.126  4244  4244 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 20:33:55.131  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 20:33:55.131  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 20:33:55.132  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-24 20:33:55.140   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56f0cd4:true
08-24 20:33:55.140  4244  4244 D BluetoothAdapterState: make() - Creating AdapterState
08-24 20:33:55.144  4244  4244 I bt_bluedroid: init
08-24 20:33:55.144  4244  4256 I BluetoothAdapterState: Entering OffState
,08-24 20:33:55.147  4244  4257 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 20:33:55.147  4244  4257 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 20:33:55.147  4244  4257 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-24 20:33:55.147  4244  4257 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 20:33:55.148  4244  4244 I bt_bluedroid: get_profile_interface socket
08-24 20:33:55.149  4244  4244 I bt_bluedroid: get_profile_interface sdp
,08-24 20:33:55.152  4244  4255 I bt_bluedroid: config_hci_snoop_log
,08-24 20:33:55.152  4244  4260 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-24 20:33:55.153   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 20:33:55.154  4244  4260 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 20:33:55.157  4244  4256 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 20:33:55.157  4244  4256 D BluetoothAdapterProperties: Setting state to 14
08-24 20:33:55.157  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 20:33:55.159  4244  4256 D BluetoothBondStateMachine: make
,08-24 20:33:55.161  4244  4261 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 20:33:55.164  4244  4244 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 20:33:55.165  4244  4256 I BluetoothAdapterState: Entering PendingCommandState
,08-24 20:33:55.166  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:55.167  4244  4244 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 20:33:55.167  4244  4244 D BtGatt.GattService: Received start request. Starting profile...
08-24 20:33:55.167  4244  4244 D BtGatt.GattService: start()
08-24 20:33:55.167  4244  4244 I bt_bluedroid: get_profile_interface gatt
,08-24 20:33:55.169  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:55.169  4244  4244 D BtGatt.AdvertiseManager: advertise manager created
,08-24 20:33:55.174  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:55.175  4244  4244 V BluetoothAdapterState: isTurningOn()=false
08-24 20:33:55.175  4244  4244 V BluetoothAdapterState: isBleTurningOn()=true
,08-24 20:33:55.175  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:55.175  4244  4256 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 20:33:55.175  4244  4256 I bt_bluedroid: enable
08-24 20:33:55.175  4244  4257 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 20:33:55.176  4244  4257 I bt_hci  : start_up
,08-24 20:33:55.182  4244  4257 I bt_vendor: alloc value 0xb39ba189
08-24 20:33:55.182  4244  4257 I bt_vendor: init
08-24 20:33:55.182  4244  4257 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-24 20:33:55.182  4244  4257 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 20:33:55.291  4244  4257 D bt_hci  : start_up starting async portion
,08-24 20:33:55.292  4244  4264 I bt_hci  : event_finish_startup
,08-24 20:33:55.292  4244  4264 I bt_hci_h4: hal_open
08-24 20:33:55.293  4244  4264 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 20:33:55.301  4244  4264 I bt_userial_vendor: device fd = 51 open
,08-24 20:33:55.334  4244  4264 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 20:33:55.366  4244  4264 D bt_hwcfg: Chipset BCM4354A2
08-24 20:33:55.366  4244  4264 D bt_hwcfg: Target name = [BCM4354A2]
,08-24 20:33:55.367  4244  4264 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 20:33:56.025  4244  4264 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 20:33:56.026  4244  4264 D bt_hwcfg: Settlement delay -- 100 ms
,08-24 20:33:56.026  4244  4264 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 20:33:56.143  4244  4264 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-24 20:33:56.144  4244  4264 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 20:33:56.174  4244  4264 I bt_hwcfg: vendor lib fwcfg completed
,08-24 20:33:56.174  4244  4264 I bt_vendor: firmware callback
,08-24 20:33:56.174  4244  4264 I bt_hci  : firmware_config_callback
,08-24 20:33:56.187  4244  4266 I bt_btu  : btu_task pending for preload complete event
,08-24 20:33:56.188  4244  4266 I bt_btu_task: Bluetooth chip preload is complete
,08-24 20:33:56.188  4244  4266 I bt_btu  : btu_task received preload complete event
,08-24 20:33:56.199  4244  4266 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 20:33:56.199  4244  4266 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 20:33:56.200  4244  4266 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-24 20:33:56.200  4244  4266 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 20:33:56.200  4244  4266 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 20:33:56.200  4244  4266 I         : BTE_InitTraceLevels -- TRC_A2D
,08-24 20:33:56.201  4244  4266 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-24 20:33:56.201  4244  4266 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 20:33:56.201  4244  4266 I         : BTE_InitTraceLevels -- TRC_GAP
,08-24 20:33:56.201  4244  4266 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 20:33:56.201  4244  4266 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 20:33:56.202  4244  4266 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 20:33:56.202  4244  4266 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 20:33:56.202  4244  4266 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 20:33:56.203  4244  4266 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 20:33:56.335  4244  4266 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3937d9d
,08-24 20:33:56.336  4244  4266 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3937d9d 
,08-24 20:33:56.358  4244  4260 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 20:33:56.360  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 20:33:56.361  4244  4260 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 20:33:56.366  4244  4260 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 20:33:56.369  4244  4260 D BluetoothAdapterProperties: Scan Mode:20
,08-24 20:33:56.371  4244  4260 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 20:33:56.374  4244  4260 D bt_hci  : do_postload posting postload work item
,08-24 20:33:56.376  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:56.376  4244  4264 I bt_hci  : event_postload
08-24 20:33:56.376  4244  4264 I bt_vendor: sco_config_cb
08-24 20:33:56.376  4244  4264 I bt_hci  : sco_config_callback postload finished.
,08-24 20:33:56.380  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:56.381  4244  4260 D bt_bte_conf: Device ID record 1 : primary
08-24 20:33:56.381  4244  4260 D bt_bte_conf:   vendorId            = 000f
08-24 20:33:56.381  4244  4260 D bt_bte_conf:   vendorIdSource      = 0001
08-24 20:33:56.381  4244  4260 D bt_bte_conf:   product             = 1200
08-24 20:33:56.382  4244  4264 I bt_vendor: low_power_mode_cb
08-24 20:33:56.382  4244  4260 D bt_bte_conf:   version             = 1436
08-24 20:33:56.382  4244  4260 D bt_bte_conf:   clientExecutableURL = 
,08-24 20:33:56.383  4244  4260 D bt_bte_conf:   serviceDescription  = 
08-24 20:33:56.383  4244  4260 D bt_bte_conf:   documentationURL    = 
,08-24 20:33:56.384  4244  4260 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 20:33:56.385  4244  4257 D bt_stack_manager: event_start_up_stack finished
,08-24 20:33:56.387  4244  4256 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 20:33:56.387  4244  4256 D BluetoothAdapterProperties: Setting state to 15
08-24 20:33:56.387  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 20:33:56.388  4244  4256 I BluetoothAdapterState: Entering BleOnState
,08-24 20:33:56.393  4244  4256 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 20:33:56.393  4244  4256 D BluetoothAdapterProperties: Setting state to 11
08-24 20:33:56.393  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 20:33:56.398  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:56.401  4244  4244 D HeadsetService: Received start request. Starting profile...
,08-24 20:33:56.405  4244  4244 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 20:33:56.405  4244  4244 D HeadsetStateMachine: make
,08-24 20:33:56.412  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:56.415  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:56.427  4244  4244 D HeadsetStateMachine: max_hf_connections = 1
,08-24 20:33:56.427  4244  4244 I bt_bluedroid: get_profile_interface handsfree
08-24 20:33:56.427  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 20:33:56.427  4244  4260 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-24 20:33:56.428  4244  4256 I BluetoothAdapterState: Entering PendingCommandState
,08-24 20:33:56.433  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:56.433  4244  4244 D A2dpService: Received start request. Starting profile...
,08-24 20:33:56.434  4244  4244 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 20:33:56.435  4244  4244 I bt_bluedroid: get_profile_interface avrcp
,08-24 20:33:56.444  4244  4244 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 20:33:56.444  4244  4244 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-24 20:33:56.444  4244  4244 D A2dpStateMachine: make
,08-24 20:33:56.446  4244  4244 I bt_bluedroid: get_profile_interface a2dp
,08-24 20:33:56.446  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 20:33:56.450  4244  4275 D A2dpStateMachine: Enter Disconnected: -2
,08-24 20:33:56.451  4244  4244 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 20:33:56.452  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:56.453  4244  4244 D HidService: Received start request. Starting profile...
,08-24 20:33:56.453  4244  4244 I bt_bluedroid: get_profile_interface hidhost
,08-24 20:33:56.454  4244  4244 D HidService: setHidService(): set to: null
,08-24 20:33:56.454  4244  4260 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39193e5
,08-24 20:33:56.454  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-24 20:33:56.456  4244  4244 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 20:33:56.456  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:56.457  4244  4244 D HealthService: Received start request. Starting profile...
,08-24 20:33:56.459  4244  4244 I bt_bluedroid: get_profile_interface health
,08-24 20:33:56.462  4244  4244 I BluetoothPanServiceJni: classInitNative(L105): succeeds,
,08-24 20:33:56.462  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 20:33:56.463  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:33:56.463  4244  4244 D PanService: Received start request. Starting profile...
,08-24 20:33:56.464  4244  4244 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 20:33:56.464  4244  4244 I bt_bluedroid: get_profile_interface pan
08-24 20:33:56.464  4244  4260 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 20:33:56.469  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
08-24 20:33:56.470  4244  4244 D BluetoothMapService: Received start request. Starting profile...
08-24 20:33:56.471  4244  4244 D BluetoothMapService: start()
,08-24 20:33:56.474  4244  4244 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-24 20:33:56.475  4244  4244 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 20:33:56.475  4244  4244 D BluetoothMapAppObserver: createReceiver()
08-24 20:33:56.477  4244  4244 D BluetoothMapAppObserver: initObservers()
08-24 20:33:56.477  4244  4244 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 20:33:56.486  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-24 20:33:56.486  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:56.486  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:56.486  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:56.488  4244  4272 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isTurningOn()=true
,08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:56.488  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false,
08-24 20:33:56.489  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-24 20:33:56.489  4244  4244 V BluetoothAdapterState: isTurningOn()=true
,08-24 20:33:56.489  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:56.489  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-24 20:33:56.491  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 20:33:56.492  4244  4256 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 20:33:56.492  4244  4256 D BluetoothAdapterProperties: ScanMode =  20
08-24 20:33:56.492  4244  4256 D BluetoothAdapterProperties: State =  11
,08-24 20:33:56.492  4244  4256 D BluetoothAdapterProperties: Setting state to 12
,08-24 20:33:56.493  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 20:33:56.493  1359  2027 D BluetoothMap: onBluetoothStateChange: up=true
08-24 20:33:56.494  4244  4260 D BluetoothAdapterProperties: Scan Mode:21
,08-24 20:33:56.494  4244  4260 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 20:33:56.494  4244  4256 I BluetoothAdapterState: Entering OnState
,08-24 20:33:56.497  1359  1359 D BluetoothMap: Proxy object connected
08-24 20:33:56.497  1359  1359 D MapProfile: Bluetooth service connected
08-24 20:33:56.497   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:56.497  1359  1359 D BluetoothMap: getConnectedDevices()
,08-24 20:33:56.497  3916  4237 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:56.498  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 20:33:56.498  3916  3926 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 20:33:56.499  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:56.501  3916  3927 D BluetoothPan: onBluetoothStateChange on: true
,08-24 20:33:56.503  1932  2056 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:56.503  3916  3916 D BluetoothInputDevice: Proxy object connected
,08-24 20:33:56.503  3916  3916 D HidProfile: Bluetooth service connected
08-24 20:33:56.503   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 20:33:56.503   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:56.504  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:56.504   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 20:33:56.504  1359  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 20:33:56.505   873   873 D BluetoothA2dp: Proxy object connected
,08-24 20:33:56.505  1359  1359 D BluetoothInputDevice: Proxy object connected
08-24 20:33:56.505  1359  1359 D HidProfile: Bluetooth service connected
08-24 20:33:56.506  3916  3926 D BluetoothMap: onBluetoothStateChange: up=true
08-24 20:33:56.506  4244  4244 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 20:33:56.507  4244  4244 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 20:33:56.507  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 20:33:56.508  1359  2027 D BluetoothHeadset: onBluetoothStateChange: up=true,
08-24 20:33:56.508  3916  4237 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 20:33:56.508  4244  4244 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 20:33:56.510  1359  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 20:33:56.511  3916  3927 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 20:33:56.511  4244  4244 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 20:33:56.512  4244  4244 D ObexServerSockets: Succeed to create listening sockets 
08-24 20:33:56.513  4244  4244 D ObexServerSockets0: startAccept()
08-24 20:33:56.513  4244  4244 D ObexServerSockets0: prepareForNewConnect()
,08-24 20:33:56.516  1359  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 20:33:56.517  4244  4282 D ObexServerSockets0: Accepting socket connection...
,08-24 20:33:56.517  4244  4244 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-24 20:33:56.517  4244  4244 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-24 20:33:56.518  1359  1359 D BluetoothA2dp: Proxy object connected
08-24 20:33:56.518  1359  1372 D BluetoothPan: onBluetoothStateChange on: true
08-24 20:33:56.518  4244  4283 D ObexServerSockets0: Accepting socket connection...
08-24 20:33:56.520  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 20:33:56.520  1359  1359 D PanProfile: Bluetooth service connected
08-24 20:33:56.520  3916  3916 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 20:33:56.520  3916  3916 D PanProfile: Bluetooth service connected
08-24 20:33:56.520  3916  3916 D BluetoothMap: Proxy object connected
,08-24 20:33:56.520  3916  3916 D MapProfile: Bluetooth service connected
08-24 20:33:56.520  3916  3916 D BluetoothMap: getConnectedDevices()
08-24 20:33:56.521   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 20:33:56.523  4244  4244 D BluetoothMapService: onReceive
08-24 20:33:56.523  4244  4244 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 20:33:56.523  4244  4244 D BluetoothMapService: STATE_ON
08-24 20:33:56.523  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:33:56.523  3916  3916 D BluetoothA2dp: Proxy object connected
08-24 20:33:56.525  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:33:56.528  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 20:33:56.536  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 20:33:56.537  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,08-24 20:33:56.550  1359  1359 D BluetoothPbap: Proxy object connected
,08-24 20:33:56.550  1359  1359 D PbapServerProfile: Bluetooth service connected
08-24 20:33:56.550  3916  3916 D BluetoothPbap: Proxy object connected
08-24 20:33:56.550  3916  3916 D PbapServerProfile: Bluetooth service connected
,08-24 20:33:56.554  4244  4244 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 20:33:56.554  4244  4244 D ObexServerSockets0: prepareForNewConnect()
,08-24 20:33:56.560  4244  4287 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 20:33:56.571  4244  4291 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 20:33:56.572  4244  4291 I BtOppRfcommListener: Accept thread started.
,08-24 20:33:56.598   873   873 D BluetoothHeadset: Proxy object connected
,08-24 20:33:56.599  3916  3927 D BluetoothHeadset: Proxy object connected
,08-24 20:33:56.599  1932  2205 D BluetoothHeadset: Proxy object connected
08-24 20:33:56.599  3916  3916 D HeadsetProfile: Bluetooth service connected
,08-24 20:33:56.600  3916  4237 D BluetoothHeadset: Proxy object connected
08-24 20:33:56.600   873   873 D BluetoothHeadset: Proxy object connected
,08-24 20:33:56.601  1359  2027 D BluetoothHeadset: Proxy object connected
,08-24 20:33:56.601   873   873 D BluetoothHeadset: Proxy object connected
08-24 20:33:56.601  1359  1359 D HeadsetProfile: Bluetooth service connected
08-24 20:33:56.602  3916  3916 D HeadsetProfile: Bluetooth service connected
08-24 20:33:56.603  1932  1946 D BluetoothHeadset: Proxy object connected
08-24 20:33:56.603   873   890 D BluetoothHeadset: Proxy object connected
08-24 20:33:56.603   873   890 D BluetoothHeadset: Proxy object connected
,08-24 20:33:56.608  1359  1380 D BluetoothHeadset: Proxy object connected
,08-24 20:33:56.608  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:33:59.988  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:33:59.995  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:33:59.996  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:33:59.997  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc993e6 removed from the list
08-24 20:33:59.997  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 20:33:59.997  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:33:59.997  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:00.003  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 20:34:00.004  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c83d27 added. We now have 4 listener(s)
08-24 20:34:00.004  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:34:00.008   873  1958 D WifiService: setWifiEnabled: false pid=3831, uid=10000
,08-24 20:34:00.008   873  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 20:34:03.747  1870  1905 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-24 20:34:03.747  1870  1905 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-24 20:34:03.780  1526  1526 I ConfigService: onCreate
,08-24 20:34:05.021  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:34:05.022   873  1404 D WifiService: setWifiEnabled: true pid=3831, uid=10000
,08-24 20:34:05.022   873  1404 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 20:34:05.035   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:34:05.053  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:34:05.060  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 20:34:05.064  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 20:34:05.066  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 20:34:05.072   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-24 20:34:05.073   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 20:34:05.073   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-24 20:34:05.074   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-24 20:34:05.075   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-24 20:34:05.075   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 20:34:05.075   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 20:34:05.090   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 20:34:05.091   370   871 D CommandListener: Setting iface cfg
,08-24 20:34:05.091   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 20:34:05.091   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-24 20:34:05.092   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 20:34:05.146   873  1314 E native  : do suspend true
,08-24 20:34:05.159   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 20:34:05.160   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 20:34:05.179   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:34:06.488   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 20:34:06.631   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.56 rxSuccessRate=9.69 delta 1000 -> 994
,08-24 20:34:06.634   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 20:34:06.634   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 20:34:06.653   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 20:34:06.706   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 20:34:06.711  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 20:34:07.152  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 20:34:07.201  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 20:34:07.203  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 20:34:07.208   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 20:34:07.221   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 20:34:07.221   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 20:34:07.222   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 20:34:07.240   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 20:34:07.257   370   871 D CommandListener: Setting iface cfg
,08-24 20:34:07.258   873  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,08-24 20:34:07.276   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 20:34:07.300   873  4300 D DhcpClient: Receive thread started
,08-24 20:34:07.395   873  1314 E native  : do suspend false
,08-24 20:34:07.423   873  1849 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 20:34:07.436   873  4300 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null,
08-24 20:34:07.438   873  1849 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-24 20:34:07.441   873  1849 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 20:34:07.459   873  4300 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 20:34:07.461   873  1849 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 20:34:07.466   370   871 D CommandListener: Setting iface cfg
,08-24 20:34:07.477   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-24 20:34:07.478   873  1849 D DhcpClient: Scheduling renewal in 86399s
,08-24 20:34:07.480   873  1314 E native  : do suspend true
,08-24 20:34:07.510   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 20:34:07.513   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
08-24 20:34:07.514   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 20:34:07.517   873  1316 D ConnectivityService: Adding iface wlan0 to network 102
08-24 20:34:07.518   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 20:34:07.579   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 20:34:07.580   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-24 20:34:07.582   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-24 20:34:07.584   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-24 20:34:07.587   873  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-24 20:34:07.604   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 20:34:07.610   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-24 20:34:07.610   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-24 20:34:07.610   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-24 20:34:07.610   873  1316 D ConnectivityService:    accepting network in place of null
,08-24 20:34:07.611   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 20:34:07.612   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 20:34:07.613   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 20:34:07.627   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 20:34:07.650   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:34:07.701   873  4298 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.142,2a00:1450:4001:81a::200e
,08-24 20:34:07.719   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 20:34:07.732   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-24 20:34:07.732   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:34:07.741   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 20:34:07.745   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:34:07.758  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:34:07.761  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:34:07.766  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:34:07.769  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:34:07.774  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 20:34:07.780  1752  1752 D SystemUpdateService: onCreate
,08-24 20:34:07.785  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 20:34:07.806  1752  4309 I SystemUpdateService: active receiver: enabled
,08-24 20:34:07.810  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 20:34:07.814  1752  2418 I iu.UploadsManager: num queued entries: 0
,08-24 20:34:07.818  1752  4309 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 20:34:07.819  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 20:34:07.820  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 20:34:07.823  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 20:34:07.824  1752  4311 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-24 20:34:07.824  1752  4311 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 20:34:07.826  1752  4311 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 20:34:07.829  3997  3997 D SprintDMHelper: simOperator: 
08-24 20:34:07.829  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-24 20:34:07.829  1752  2418 I iu.UploadsManager: num updated entries: 0
,08-24 20:34:07.832  1752  4309 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 20:34:07.832  1752  4309 I SystemUpdateService: now status is 0 (complete)
,08-24 20:34:07.832  1752  4309 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 20:34:07.832  1752  4309 I SystemUpdateService: file has been verified
08-24 20:34:07.833  1752  4309 I SystemUpdateService: OTA package size = 12249756
08-24 20:34:07.834  1752  2418 I iu.SyncManager: NEXT; no task
,08-24 20:34:07.836   873  4298 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 18:34:07 GMT], X-Android-Received-Millis=[1472063647836], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472063647807]}
08-24 20:34:07.836  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 20:34:07.838  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:34:07.842   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 20:34:07.842   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-24 20:34:07.842   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 20:34:07.845   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 20:34:07.865  1752  4309 I SystemUpdateService: showing system update notification
,08-24 20:34:07.929  1752  1752 D SystemUpdateService: onDestroy
,08-24 20:34:07.949  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 20:34:07.949  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 20:34:07.949  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:34:07.949  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:34:07.974  3967  4315 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 20:34:07.982  1752  4311 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-24 20:34:08.731   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-24 20:34:08.853  1526  1526 I ConfigService: onDestroy
,08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:34:10.046  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:34:10.053  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:10.054  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:10.055  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c83d27 removed from the list
08-24 20:34:10.055  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:34:10.055  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:10.055  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:34:10.067  3831  4322 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-24 20:34:10.067  3831  4322 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 20:34:13.077  3831  4323 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-24 20:34:13.078  3831  4322 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-24 20:34:13.078  3831  4323 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-24 20:34:13.079  3831  4322 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-24 20:34:13.080  3831  4322 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 20:34:13.080  3831  4323 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 20:34:13.082  3831  4322 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-24 20:34:13.082  3831  4323 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-24 20:34:13.087  3831  4323 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-24 20:34:13.087  3831  4322 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-24 20:34:13.087  3831  4325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Sender)
,08-24 20:34:13.094  3831  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Sender)
,08-24 20:34:13.096  3831  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Receiver)
08-24 20:34:13.097  3831  4328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: OutgoingSocketThread/Receiver)
,08-24 20:34:13.098  3831  4328 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-24 20:34:13.098  3831  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Receiver)
08-24 20:34:13.098  3831  4328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-24 20:34:13.099  3831  4327 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: IncomingSocketThread/Receiver)
08-24 20:34:13.100  3831  4327 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-24 20:34:13.100  3831  4327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-24 20:34:15.618   873  1316 D ConnectivityService: handlePromptUnvalidated 102,
,08-24 20:34:16.076  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
08-24 20:34:16.077  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 20:34:16.085  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a5fb05c Bundle[{}],
08-24 20:34:16.085  3831  3881 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 20:34:16.085  3831  3881 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 20:34:16.086  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 20:34:16.086  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 20:34:16.087  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 20:34:16.087  3831  3881 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 20:34:16.091  3831  3881 I System.out: Running OutgoingSocketThread
,08-24 20:34:16.095  3831  4329 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-24 20:34:16.095  3831  4329 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 20:34:19.104  3831  4330 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-24 20:34:19.104  3831  4330 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-24 20:34:19.105  3831  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 20:34:19.106  3831  4329 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-24 20:34:19.106  3831  4329 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-24 20:34:19.106  3831  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 20:34:19.106  3831  4329 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-24 20:34:19.107  3831  4330 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-24 20:34:19.108  3831  4329 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-24 20:34:19.110  3831  4329 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-24 20:34:19.116  3831  4333 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: IncomingSocketThread/Receiver)
,08-24 20:34:19.117  3831  4333 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: IncomingSocketThread/Receiver)
,08-24 20:34:19.118  3831  4333 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-24 20:34:19.118  3831  4333 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-24 20:34:19.119  3831  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: IncomingSocketThread/Sender)
,08-24 20:34:19.123  3831  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: OutgoingSocketThread/Receiver)
08-24 20:34:19.125  3831  4335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: OutgoingSocketThread/Receiver)
08-24 20:34:19.126  3831  4335 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-24 20:34:19.126  3831  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-24 20:34:19.127  3831  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Sender)
,08-24 20:34:22.106  3831  3881 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-24 20:34:22.109  3831  3881 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 20:34:22.109  3831  3881 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,08-24 20:34:22.115  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 20:34:22.115  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90e1bd4 added. We now have 3 listener(s)
08-24 20:34:22.117  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 20:34:22.117  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:34:22.117  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 20:34:22.117  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:34:22.117  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174a17d added. We now have 4 listener(s)
08-24 20:34:22.117  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 20:34:22.118  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:34:22.122  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:34:22.135  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:34:22.138  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:34:22.139  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 20:34:22.140  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:34:22.140  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:34:22.140  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:34:22.140  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:34:22.141  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:22.141  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:34:22.141  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 20:34:22.141  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90e1bd4 removed from the list
08-24 20:34:22.142  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:22.142  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174a17d removed from the list
,08-24 20:34:22.147  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:34:22.151  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:34:22.152  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:34:22.152  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:22.154  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:34:22.154  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:34:22.157  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:34:22.158  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:34:22.158  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:22.158  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174a17d not in the list
08-24 20:34:22.158  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:34:22.159  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:22.161  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:34:22.162  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:34:22.162  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:22.162  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174a17d not in the list
08-24 20:34:22.163  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:34:22.163  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:22.163  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:22.163  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90e1bd4 not in the list
08-24 20:34:22.165  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 20:34:22.166  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f184c3 added. We now have 3 listener(s)
,08-24 20:34:22.172  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 20:34:22.172  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:34:22.173  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 20:34:22.173  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:34:22.173  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1b2140 added. We now have 4 listener(s)
08-24 20:34:22.174  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:34:22.175  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:34:22.182  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:34:22.194  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:34:22.200  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:34:22.201  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:34:22.202  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 20:34:22.202  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 20:34:22.202  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 20:34:22.203  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:34:22.203  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 20:34:22.208  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:34:22.214  3831  3881 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 20:34:22.215  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 20:34:22.216  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:34:22.231  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 20:34:22.234  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 20:34:22.235  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 20:34:22.248  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 20:34:22.248  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 20:34:22.248  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 20:34:22.250  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:34:22.260  4244  4281 D BtGatt.GattService: registerClient() - UUID=18e3bcd1-c3ec-4608-a785-9b8e2680f650
,08-24 20:34:22.263  4244  4260 D BtGatt.GattService: onClientRegistered() - UUID=18e3bcd1-c3ec-4608-a785-9b8e2680f650, clientIf=5
08-24 20:34:22.264  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 20:34:22.268  4244  4273 D BtGatt.GattService: start scan with filters
,08-24 20:34:22.282  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 20:34:22.282  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 20:34:22.283  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 20:34:22.283  4244  4263 D BtGatt.ScanManager: handling starting scan
08-24 20:34:22.283  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 20:34:22.289  4244  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@668b130
,08-24 20:34:22.297  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 20:34:22.299  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 20:34:22.299  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 20:34:22.306  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 20:34:22.310  4244  4260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 20:34:22.310  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:34:22.312  4244  4263 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 20:34:22.320  3831  3881 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 20:34:22.320  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-24 20:34:22.320  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 20:34:22.321  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:34:22.321  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-24 20:34:22.321  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 20:34:22.322  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 20:34:22.322  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 20:34:22.322  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 20:34:22.323  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 20:34:22.324  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 20:34:22.327  3831  3881 D BluetoothAdapter: STATE_ON
08-24 20:34:22.330  4244  4273 D BtGatt.GattService: stopScan() - queue size =1
08-24 20:34:22.333  4244  4254 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 20:34:22.335  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 20:34:22.334  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 20:34:22.335  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:34:22.336  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 20:34:22.336  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 20:34:22.336  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 20:34:22.337  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 20:34:22.337  4244  4263 D BtGatt.ScanManager: Starting BLE batch scan
08-24 20:34:22.337  4244  4263 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 20:34:22.341  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:34:22.341  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 20:34:22.341  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 20:34:22.342  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 20:34:22.343  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:34:22.347  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 20:34:22.347  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 20:34:22.347  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 20:34:22.363  4244  4260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 20:34:22.363  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:34:22.374  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 20:34:22.374  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:34:22.391  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 20:34:22.391  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:34:22.392  4244  4263 D BtGatt.ScanManager: stopping BLe Batch,
,08-24 20:34:22.411  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 20:34:22.411  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 20:34:22.412  4244  4263 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 20:34:22.430  4244  4260 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 20:34:22.430  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 20:34:22.849  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 20:34:22.849  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:34:22.850  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 20:34:25.349  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:34:25.349  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 20:34:25.349  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 20:34:25.351  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:34:25.351  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:25.351  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:34:25.351  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 20:34:25.352  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f184c3 removed from the list
,08-24 20:34:25.352  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:25.352  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1b2140 removed from the list
08-24 20:34:25.353  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:34:25.353  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:34:25.355  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:25.355  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:25.358  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:34:25.358  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:34:25.359  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:25.359  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1b2140 not in the list
08-24 20:34:25.360  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:34:25.360  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 20:34:25.363  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:34:25.363  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:34:25.364  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 20:34:25.364  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1b2140 not in the list
08-24 20:34:25.364  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 20:34:25.364  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:25.365  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:25.365  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f184c3 not in the list
08-24 20:34:25.367  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 20:34:25.367  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb8335 added. We now have 3 listener(s)
08-24 20:34:25.369  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 20:34:25.369  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:34:25.369  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 20:34:25.369  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:34:25.369  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf33ca added. We now have 4 listener(s)
,08-24 20:34:25.369  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 20:34:25.370  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:34:25.373  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 20:34:25.379  3831  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 20:34:25.382  3831  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 20:34:25.382  3831  3881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 20:34:25.383  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-24 20:34:25.384  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 20:34:25.385  3831  3881 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-24 20:34:25.385  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-24 20:34:25.387  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 20:34:25.390  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-24 20:34:25.390  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-24 20:34:25.390  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 20:34:25.391  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:34:25.392  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-24 20:34:25.392  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 20:34:25.392  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 20:34:25.392  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 20:34:25.394  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 20:34:25.394  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-24 20:34:25.394  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 20:34:25.395  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 20:34:25.400  3831  4336 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 20:34:25.404  3831  4336 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-24 20:34:25.405  3831  3881 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 20:34:25.405  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 20:34:25.412  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 20:34:25.413  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 20:34:25.413  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 20:34:25.416  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-24 20:34:25.416  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 20:34:25.416  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-24 20:34:25.418  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-24 20:34:25.418  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-24 20:34:25.418  3831  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-24 20:34:25.419  3831  3881 D BluetoothAdapter: STATE_ON
,08-24 20:34:25.422  4244  4255 D BtGatt.GattService: registerClient() - UUID=6663474c-8638-46f0-a6b9-f4e3dafb456a
,08-24 20:34:25.423  4244  4260 D BtGatt.GattService: onClientRegistered() - UUID=6663474c-8638-46f0-a6b9-f4e3dafb456a, clientIf=5
08-24 20:34:25.423  3831  3991 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
08-24 20:34:25.425  4244  4262 D BtGatt.AdvertiseManager: message : 0
,08-24 20:34:25.429  4244  4262 D BtGatt.AdvertiseManager: starting multi advertising
,08-24 20:34:25.441  4244  4260 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-24 20:34:25.450  4244  4260 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-24 20:34:25.451  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-24 20:34:25.452  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 20:34:25.454  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 20:34:25.455  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-24 20:34:25.456  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-24 20:34:25.456  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-24 20:34:25.456  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-24 20:34:25.456  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-24 20:34:25.456  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-24 20:34:25.459  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 20:34:25.460  3831  3831 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-24 20:34:25.460  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-24 20:34:25.961  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-24 20:34:25.962  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 20:34:25.962  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 20:34:28.460  3831  3881 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 20:34:28.460  3831  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-24 20:34:28.461  3831  3881 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 20:34:28.461  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-24 20:34:28.461  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-24 20:34:28.462  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-24 20:34:28.463  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-24 20:34:28.463  3831  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-24 20:34:28.463  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 20:34:28.463  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 20:34:28.464  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 20:34:28.464  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 20:34:28.464  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 20:34:28.464  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 20:34:28.465  3831  4336 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-24 20:34:28.466  3831  4336 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 20:34:28.466  3831  4336 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 20:34:28.467  3831  3881 D BluetoothAdapter: STATE_ON
08-24 20:34:28.467  3831  3881 D BluetoothLeScanner: could not find callback wrapper
08-24 20:34:28.468  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 20:34:28.468  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-24 20:34:28.470  4244  4262 D BtGatt.AdvertiseManager: message : 1
08-24 20:34:28.472  4244  4262 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-24 20:34:28.483  4244  4260 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-24 20:34:28.483  4244  4260 D BtGatt.GattService: Client app is not null!
,08-24 20:34:28.484  4244  4273 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 20:34:28.485  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 20:34:28.486  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-24 20:34:28.486  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-24 20:34:28.486  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-24 20:34:28.486  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-24 20:34:28.488  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 20:34:28.488  3831  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 20:34:28.489  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 20:34:28.490  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 20:34:28.492  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 20:34:28.492  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:34:28.492  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 20:34:28.492  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:28.492  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 20:34:28.493  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 20:34:28.493  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb8335 removed from the list
08-24 20:34:28.493  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:28.494  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf33ca removed from the list
08-24 20:34:28.494  3831  3881 D io.jxcore.node.ConnectivityMonitor: stop
08-24 20:34:28.494  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:28.494  3831  3831 D AndroidRuntime: Shutting down VM
,08-24 20:34:28.495  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:28.496  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
--------- beginning of crash
08-24 20:34:28.497  3831  3831 E AndroidRuntime: FATAL EXCEPTION: main
08-24 20:34:28.497  3831  3831 E AndroidRuntime: Process: com.test.thalitest, PID: 3831
08-24 20:34:28.497  3831  3831 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:34:28.497  3831  3831 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 20:34:28.498  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 20:34:28.498  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 20:34:28.498  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:28.498  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf33ca not in the list
08-24 20:34:28.498  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 20:34:28.498  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:28.501  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 20:34:28.501  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 20:34:28.501  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 20:34:28.502  3831  3881 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf33ca not in the list
08-24 20:34:28.502  3831  3881 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 20:34:28.502  3831  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 20:34:28.503  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 20:34:28.503   873  1972 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-24 20:34:28.503  3831  3881 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb8335 not in the list
,08-24 20:34:28.505  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 20:34:28.505  3831  3881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba4be17 added. We now have 3 listener(s)
,08-24 20:34:28.511  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 20:34:28.512  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 20:34:28.512  3831  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 20:34:28.512  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 20:34:28.513  3831  3881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da2204 added. We now have 4 listener(s)
08-24 20:34:28.513  3831  3881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 20:34:28.514   873  1972 I ActivityManager: Killing 3653:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-24 20:34:28.514  3831  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 20:34:28.551  3831  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 20:34:28.551   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7e04142 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{f1c5424 3831 com.test.thalitest/10000/u0 remote:9e5e4b7}: process crashing
08-24 20:34:28.552   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{96a1553 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{f1c5424 3831 com.test.thalitest/10000/u0 remote:9e5e4b7}: process crashing
08-24 20:34:28.554  3831  3831 I Process : Sending signal. PID: 3831 SIG: 9
,08-24 20:34:28.694   873  2036 D GraphicsStats: Buffer count: 2
,08-24 20:34:28.694   873  2036 I WindowState: WIN DEATH: Window{d69615c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 20:34:28.696   873  1315 D WifiService: Client connection lost with reason: 4
,08-24 20:34:28.732   873  1418 I ActivityManager: Process com.test.thalitest (pid 3831) has died
,08-24 20:34:28.798   873   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3831 uid 10000
,08-24 20:34:28.802  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-24 20:34:42.452  1526  2174 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 20:34:42.780   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=249084, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:34:43.434  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:34:43.439  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:34:43.487  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 20:34:43.487  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 20:34:43.487  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:34:43.487  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:34:43.517  3556  4341 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 20:34:43.517  3556  4341 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at blb.a(PG:3937)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at czp.a(PG:18188)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:34:43.517  3556  4341 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	... 12 more
08-24 20:34:43.517  3556  4341 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at fal.a(PG:38)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:34:43.517  3556  4341 E HttpOperation: 	... 14 more
,08-24 20:34:43.568  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 20:34:43.568  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 20:34:43.568  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:34:43.568  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:34:43.594  3556  4341 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 20:34:43.594  3556  4341 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at hec.a(PG:42)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at hee.a(PG:102)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at czr.a(PG:65)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at kka.a(PG:108)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at czp.a(PG:19176)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:34:43.594  3556  4341 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	... 15 more
08-24 20:34:43.594  3556  4341 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at fal.a(PG:38)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:34:43.594  3556  4341 E HttpOperation: 	... 17 more
,08-24 20:34:43.595  3556  4341 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 20:34:43.595  3556  4341 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at hec.a(PG:42)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at hee.a(PG:102)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at czr.a(PG:65)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at kka.a(PG:108)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
,08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	... 15 more
08-24 20:34:43.595  3556  4341 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at fal.a(PG:38)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 20:34:43.595  3556  4341 E ExperimentLoader: 	... 17 more
,08-24 20:34:43.809   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 249393, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:35:01.776   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268079, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:35:13.975  3610  4344 V KeepSync: Connecting to GoogleApiClient
08-24 20:35:13.975   873  1967 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 20:35:14.056  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:35:14.061  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:35:14.120  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 20:35:14.121  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 20:35:14.121  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:35:14.121  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:14.159  1752  4345 V BaseAuthAsyncOperation: access token request failed
,08-24 20:35:14.161  3610  4344 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 20:35:14.243  1526  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 20:35:14.243  1526  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 20:35:14.243  1526  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:35:14.243  1526  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:14.271  3610  4344 E KeepSync: IOException
08-24 20:35:14.271  3610  4344 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 20:35:14.271  3610  4344 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:35:14.271  3610  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 20:35:14.271  3610  4344 E KeepSync: 	... 10 more
08-24 20:35:14.271  3610  4344 W KeepSync: Sync result 2
,08-24 20:35:14.281   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 251267, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:35:28.846  1870  1905 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-24 20:35:28.846  1870  1905 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-24 20:35:28.900  1526  1526 I ConfigService: onCreate
,08-24 20:35:33.976  1526  1526 I ConfigService: onDestroy
,08-24 20:35:36.466   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:35:44.509  3784  4353 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 20:35:44.621  3784  4355 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 20:35:44.631  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:35:44.632  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 20:35:44.656  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 20:35:44.656  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:35:44.656  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:35:44.656  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:44.673  1526  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 20:35:44.673  1526  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 20:35:44.673  1526  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:35:44.673  1526  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:44.686  3556  4354 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 20:35:44.686  3556  4354 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at blb.a(PG:3937)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at czp.a(PG:18188)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:35:44.686  3556  4354 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	... 12 more
08-24 20:35:44.686  3556  4354 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at fal.a(PG:38)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:35:44.686  3556  4354 E HttpOperation: 	... 14 more
,08-24 20:35:44.755  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 20:35:44.756  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:35:44.756  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:35:44.756  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:44.782  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 20:35:44.782  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 20:35:44.782  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:35:44.782  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:44.805  3784  4355 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 20:35:44.806  3784  4353 E BooksSync: Soft error
08-24 20:35:44.806  3784  4353 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:35:44.806  3784  4353 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 20:35:44.806  3784  4353 E BooksSync: Sync error
08-24 20:35:44.806  3784  4353 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:35:44.806  3784  4353 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 20:35:44.806  3784  4353 I BooksSync: Finished books sync
,08-24 20:35:44.817  3556  4354 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 20:35:44.817  3556  4354 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at hec.a(PG:42)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at hee.a(PG:102)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at czr.a(PG:65)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at kka.a(PG:108)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at czp.a(PG:19176)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:35:44.817  3556  4354 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	... 15 more
08-24 20:35:44.817  3556  4354 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at fal.a(PG:38)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:35:44.817  3556  4354 E HttpOperation: 	... 17 more
,08-24 20:35:44.817  3556  4354 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
08-24 20:35:44.817  3556  4354 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at hec.a(PG:42)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at hee.a(PG:102)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at czr.a(PG:65)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at kka.a(PG:108)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	... 15 more
08-24 20:35:44.817  3556  4354 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at fal.a(PG:38)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 20:35:44.817  3556  4354 E ExperimentLoader: 	... 17 more
,08-24 20:35:44.825   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288259, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:35:44.900  3610  4357 V KeepSync: Connecting to GoogleApiClient
08-24 20:35:44.901   873  1404 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 20:35:44.965  1526  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 20:35:44.966  1526  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 20:35:44.966  1526  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:35:44.966  1526  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 20:35:44.969   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 282539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:35:44.989  1752  4358 V BaseAuthAsyncOperation: access token request failed
,08-24 20:35:44.990  3610  4357 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 20:35:45.069  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 20:35:45.070  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 20:35:45.070  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:35:45.070  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:35:45.106  3610  4357 E KeepSync: IOException
08-24 20:35:45.106  3610  4357 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 20:35:45.106  3610  4357 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:35:45.106  3610  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 20:35:45.106  3610  4357 E KeepSync: 	... 10 more
,08-24 20:35:45.106  3610  4357 W KeepSync: Sync result 2
,08-24 20:35:45.127   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 310948, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:36:03.109   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329413, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:36:16.873  3784  4361 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 20:36:16.894  3784  4362 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 20:36:16.914  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:16.922  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:16.976  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 20:36:16.976  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:36:16.976  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:36:16.976  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:36:17.027  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:17.029  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:17.059  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:17.104  1526  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 20:36:17.104  1526  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 20:36:17.104  1526  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:36:17.104  1526  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:36:17.119  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-24 20:36:17.119  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-24 20:36:17.119  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:36:17.120  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:36:17.121  3784  4362 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:36:17.122  3784  4361 E BooksSync: Soft error
08-24 20:36:17.122  3784  4361 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:36:17.122  3784  4361 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 20:36:17.122  3784  4361 E BooksSync: Sync error
08-24 20:36:17.122  3784  4361 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:36:17.122  3784  4361 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 20:36:17.123  3784  4361 I BooksSync: Finished books sync
,08-24 20:36:17.136   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 343010, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:36:17.153  1526  1537 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 20:36:17.153  1526  1537 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 20:36:17.153  1526  1537 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 20:36:17.153  1526  1537 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-24 20:36:17.153  1526  1537 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-24 20:36:17.153  1526  1537 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-24 20:36:17.153  1526  1537 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 20:36:17.159  3518  3547 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 20:36:17.159  3518  3547 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-24 20:36:17.159  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-24 20:36:17.159  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-24 20:36:17.159  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-24 20:36:17.159  3518  3547 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-24 20:36:17.159  3518  3547 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 20:36:47.317  3610  4367 V KeepSync: Connecting to GoogleApiClient
08-24 20:36:47.318   873  2037 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 20:36:47.386  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:47.389  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:36:47.442  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-24 20:36:47.442  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 20:36:47.443  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:36:47.443  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:36:47.488  1752  4368 V BaseAuthAsyncOperation: access token request failed
,08-24 20:36:47.489  3610  4367 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 20:36:47.601  1526  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 20:36:47.602  1526  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 20:36:47.602  1526  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:36:47.602  1526  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:36:47.641  3610  4367 E KeepSync: IOException
08-24 20:36:47.641  3610  4367 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 20:36:47.641  3610  4367 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:36:47.641  3610  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 20:36:47.641  3610  4367 E KeepSync: 	... 10 more
,08-24 20:36:47.642  3610  4367 W KeepSync: Sync result 2
,08-24 20:36:47.657   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 372157, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:36:52.626   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=378930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:37:18.061  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:37:18.067  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:37:18.128  1526  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 20:37:18.128  1526  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 20:37:18.128  1526  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:37:18.128  1526  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:37:18.166  3556  4372 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 20:37:18.166  3556  4372 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at blb.a(PG:3937)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at czp.a(PG:18188)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:37:18.166  3556  4372 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	... 12 more
08-24 20:37:18.166  3556  4372 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at fal.a(PG:38)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:37:18.166  3556  4372 E HttpOperation: 	... 14 more
,08-24 20:37:18.275  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 20:37:18.275  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 20:37:18.276  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:37:18.276  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:37:18.305  3556  4372 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 20:37:18.305  3556  4372 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jcs.i(PG:143),
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at hec.a(PG:42)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at hee.a(PG:102)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at czr.a(PG:65)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at kka.a(PG:108)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at czp.a(PG:19176)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
,08-24 20:37:18.305  3556  4372 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:37:18.305  3556  4372 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	... 15 more
08-24 20:37:18.305  3556  4372 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at fal.a(PG:38)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:37:18.305  3556  4372 E HttpOperation: 	... 17 more
,08-24 20:37:18.305  3556  4372 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 20:37:18.305  3556  4372 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at hec.a(PG:42)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at hee.a(PG:102)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at czr.a(PG:65)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at kka.a(PG:108)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	... 15 more
08-24 20:37:18.305  3556  4372 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at fal.a(PG:38)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 20:37:18.305  3556  4372 E ExperimentLoader: 	... 17 more
,08-24 20:37:18.450   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 376126, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:37:37.520   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:37:48.838  3784  4377 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 20:37:48.853  3784  4378 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 20:37:48.880  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:37:48.885  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:37:48.908  1526  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 20:37:48.908  1526  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:37:48.909  1526  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:37:48.909  1526  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:37:48.935  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:37:48.936  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:37:48.958  1526  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 20:37:48.958  1526  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:37:48.958  1526  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 20:37:48.958  1526  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:37:48.970  3784  4378 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 20:37:48.971  3784  4377 E BooksSync: Soft error
08-24 20:37:48.971  3784  4377 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:37:48.971  3784  4377 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 20:37:48.971  3784  4377 E BooksSync: Sync error
08-24 20:37:48.971  3784  4377 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:37:48.971  3784  4377 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 20:37:48.971  3784  4377 I BooksSync: Finished books sync
,08-24 20:37:48.976   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 407203, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:38:12.203   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=458506, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:38:47.519  1526  2174 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 20:38:49.221  3610  4381 V KeepSync: Connecting to GoogleApiClient
,08-24 20:38:49.221   873  2001 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 20:38:49.265  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:38:49.270  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:38:49.308  1526  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 20:38:49.308  1526  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 20:38:49.309  1526  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:38:49.309  1526  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:38:49.335  1752  4382 V BaseAuthAsyncOperation: access token request failed
,08-24 20:38:49.336  3610  4381 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 20:38:49.415  1526  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 20:38:49.415  1526  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 20:38:49.415  1526  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:38:49.415  1526  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:38:49.440  3610  4381 E KeepSync: IOException
08-24 20:38:49.440  3610  4381 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 20:38:49.440  3610  4381 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 20:38:49.440  3610  4381 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 20:38:49.440  3610  4381 E KeepSync: 	... 10 more
,08-24 20:38:49.440  3610  4381 W KeepSync: Sync result 2
,08-24 20:38:49.450   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 495415, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:39:12.857   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=519161, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:39:28.540  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:39:28.546  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:39:28.597  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 20:39:28.597  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 20:39:28.597  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:39:28.597  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:39:28.626  3556  4385 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 20:39:28.626  3556  4385 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:39:28.626  3556  4385 E HttpOperation: ,	at jcs.i(PG:143)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at blb.a(PG:3937)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at czp.a(PG:18188)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:39:28.626  3556  4385 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	... 12 more
08-24 20:39:28.626  3556  4385 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at fal.a(PG:38)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:39:28.626  3556  4385 E HttpOperation: 	... 14 more
,08-24 20:39:28.698  1526  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 20:39:28.698  1526  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 20:39:28.698  1526  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:39:28.698  1526  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:39:28.745  3556  4385 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 20:39:28.745  3556  4385 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jdm.a(PG:82)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jcs.o(PG:406)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jcn.a(PG:1379)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jcs.i(PG:143)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at hec.a(PG:42)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at hee.a(PG:102)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at czr.a(PG:65)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at kka.a(PG:108)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at czp.a(PG:19176)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at czp.a(PG:9081)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at czq.run(PG:1686)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:39:28.745  3556  4385 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jdj.a(PG:4091)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jdj.a(PG:1125)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jdm.a(PG:77)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	... 15 more
08-24 20:39:28.745  3556  4385 E HttpOperation: Caused by: faj: BadAuthentication
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at fal.a(PG:38)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	at jdj.a(PG:4089)
08-24 20:39:28.745  3556  4385 E HttpOperation: 	... 17 more
08-24 20:39:28.746  3556  4385 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 20:39:28.746  3556  4385 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at hec.a(PG:42)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at hee.a(PG:102)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at czr.a(PG:65)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at kka.a(PG:108)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	... 15 more
08-24 20:39:28.746  3556  4385 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at fal.a(PG:38)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 20:39:28.746  3556  4385 E ExperimentLoader: 	... 17 more
,08-24 20:39:28.834   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 534458, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:39:47.561   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=553865, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:39:58.937  3784  4388 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 20:39:58.970  3784  4389 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 20:39:58.985  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:39:58.988  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:39:59.021  1526  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 20:39:59.021  1526  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 20:39:59.021  1526  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:39:59.021  1526  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:39:59.049  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:39:59.052  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 20:39:59.083  1526  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 20:39:59.083  1526  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 20:39:59.083  1526  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 20:39:59.084  1526  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 20:39:59.108  3784  4389 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 20:39:59.109  3784  4388 E BooksSync: Soft error
08-24 20:39:59.109  3784  4388 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:39:59.109  3784  4388 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 20:39:59.109  3784  4388 E BooksSync: Sync error
08-24 20:39:59.109  3784  4388 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 20:39:59.109  3784  4388 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 20:39:59.109  3784  4388 I BooksSync: Finished books sync
,08-24 20:39:59.120   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 562805, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 20:40:11.241   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=577545, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:40:45.908   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=612212, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:41:22.989   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=649293, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 20:41:57.695   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=683999, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:50:07.938  1752  4424 I EventLogService: Opted in for usage reporting
,08-24 20:50:07.939  1752  4424 I EventLogService: Aggregate from 1472062807803 (log), 1472062807803 (data)
,08-24 20:50:07.986  1752  4424 W EventLogAggregator: Unknown tag: snet_gcore
,08-24 20:50:07.986  1752  4424 W EventLogAggregator: Unknown tag: snet_launch_service
,08-24 20:50:08.114  1752  4424 I ServiceDumpSys: dumping service [account]
,08-24 20:50:12.906   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1179210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 20:50:19.960   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1186263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 20:50:52.466   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-24 20:56:05.508  4442  4442 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 20:56:05.513  4442  4442 D AndroidRuntime: CheckJNI is OFF
08-24 20:56:05.549  4442  4442 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 20:56:05.589  4442  4442 I Radio-JNI: register_android_hardware_Radio DONE
08-24 20:56:05.610  4442  4442 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 20:56:05.622   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-24 20:56:05.759   873   896 W PackageSettings: Skipping PackageSetting{c50e3bd com.example.hello/10273} due to missing metadata
08-24 20:56:05.786   873   896 I art     : Starting a blocking GC Explicit
08-24 20:56:05.836   873   896 I art     : Explicit concurrent mark sweep GC freed 47155(2MB) AllocSpace objects, 11(220KB) LOS objects, 33% free, 29MB/43MB, paused 673us total 49.742ms
08-24 20:56:05.861   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-24 20:56:05.865  4442  4442 I art     : System.exit called, status: 0
08-24 20:56:05.865  4442  4442 I AndroidRuntime: VM exiting with result code 0.
08-24 20:56:05.924   873   896 I ActivityManager: Start proc 4455:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-24 20:56:05.927   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-24 20:56:05.954  4244  4244 D BluetoothMapAppObserver: onReceive
08-24 20:56:05.954  4244  4244 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-24 20:56:05.963   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 20:56:05.966  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 20:56:05.970  2169  2305 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 20:56:05.971  3673  3673 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-24 20:56:05.974  1870  4469 I Keyboard.Facilitator.DecoderInitializer: run()
08-24 20:56:05.980  1870  4469 I Decoder : createOrResetDecoder
08-24 20:56:06.003   873  1312 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-24 20:56:06.034  1932  1932 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 20:56:06.037   873  1404 I ActivityManager: Start proc 4472:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-24 20:56:06.045  1526  1526 I ConfigService: onCreate
08-24 20:56:06.058   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 20:56:06.082  1526  4483 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 20:56:06.082  1526  4483 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 20:56:06.084  1526  4483 W SQLiteOpenHelper: Opened config.db in read-only mode
08-24 20:56:06.090  1945  2026 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-24 20:56:06.090   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-24 20:56:06.091   873   885 E PackageManager: Failed to write settings, restoring backup
08-24 20:56:06.091   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 20:56:06.091   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 20:56:06.091   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 20:56:06.091   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 20:56:06.091   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 20:56:06.091   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:56:06.091   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.091   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 20:56:06.094   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-24 20:56:06.094   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 20:56:06.094   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 20:56:06.094   873   886 E DropBoxManagerService: 	... 13 more
08-24 20:56:06.095  4472  4472 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-24 20:56:06.110   873  1967 I ActivityManager: Start proc 4485:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-24 20:56:06.111  1945  2026 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 20:56:06.111  1945  2026 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1945
08-24 20:56:06.111  1945  2026 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.111  1945  2026 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 20:56:06.113   873  2036 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 20:56:06.116   873  4494 E DropBoxManagerService: Can't write: system_app_crash
08-24 20:56:06.116   873  4494 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 20:56:06.116   873  4494 E DropBoxManagerService: 	... 5 more
08-24 20:56:06.117  1945  2026 I Process : Sending signal. PID: 1945 SIG: 9
08-24 20:56:06.126  1870  4469 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-24 20:56:06.169  1870  4469 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-24 20:56:06.170  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 20:56:06.170  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-24 20:56:06.172  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 20:56:06.172  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-24 20:56:06.173  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 20:56:06.173  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 20:56:06.174  1870  4469 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 20:56:06.174  1870  4469 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-24 20:56:06.174  1870  4469 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 20:56:06.174  1870  4469 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 20:56:06.174  1870  4469 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 20:56:06.174  1870  4469 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-24 20:56:06.181   873  1972 D GraphicsStats: Buffer count: 1
08-24 20:56:06.181   873  1404 I WindowState: WIN DEATH: Window{c71e6ea u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-24 20:56:06.192   873  1967 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1945) has died
08-24 20:56:06.192   873  1967 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-24 20:56:06.194   873  1967 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.209  4472  4500 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.209  4472  4500 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 20:56:06.215   873   886 I ActivityManager: Start proc 4503:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 20:56:06.224  4472  4472 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-24 20:56:06.234  4472  4516 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 20:56:06.242   873  2001 I ActivityManager: Start proc 4517:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:56:06.275  4503  4503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:56:06.276  4503  4503 D AndroidRuntime: Shutting down VM
08-24 20:56:06.283  4503  4503 E AndroidRuntime: FATAL EXCEPTION: main
08-24 20:56:06.283  4503  4503 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4503
08-24 20:56:06.283  4503  4503 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 20:56:06.283  4503  4503 E AndroidRuntime: 	... 10 more
08-24 20:56:06.285   873  2037 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 20:56:06.286  4503  4503 I Process : Sending signal. PID: 4503 SIG: 9
08-24 20:56:06.289   873  4530 E DropBoxManagerService: Can't write: system_app_crash
08-24 20:56:06.289   873  4530 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 20:56:06.289   873  4530 E DropBoxManagerService: 	... 5 more
08-24 20:56:06.306  1752  4529 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 20:56:06.307  1752  4529 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-24 20:56:06.309  4517  4517 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-24 20:56:06.311   873  1972 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4503) has died
08-24 20:56:06.313   873  1972 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-24 20:56:06.327   873   886 I ActivityManager: Start proc 4531:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 20:56:06.329  1752  4529 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 20:56:06.330  1752  4529 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-24 20:56:06.351  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-24 20:56:06.354  1526  1526 D AndroidRuntime: Shutting down VM
08-24 20:56:06.355  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
08-24 20:56:06.355  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
08-24 20:56:06.355  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 20:56:06.355  1526  1526 E AndroidRuntime: 	... 8 more
08-24 20:56:06.358   873  2037 I ActivityManager: Killing 3725:com.google.android.apps.docs/u0a46 (adj 15): empty #17

```
