#### Test 83627337381d561_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 11:37:00.120   874  1891 D NetlinkSocketObserver: NeighborEvent{elapsedMs=112904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
--------- beginning of system
09-07 11:37:00.226   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:02.082  3806  3806 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 11:37:02.087  3806  3806 D AndroidRuntime: CheckJNI is OFF
09-07 11:37:02.125  3806  3806 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 11:37:02.170  3806  3806 I Radio-JNI: register_android_hardware_Radio DONE
09-07 11:37:02.190  3806  3806 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 11:37:02.195   874  1981 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 11:37:02.253  3806  3806 D AndroidRuntime: Shutting down VM
09-07 11:37:02.254  2060  2089 W SearchService: Abort, client detached.
09-07 11:37:02.269  2060  2336 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@64f9b47
09-07 11:37:02.269  2060  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 11:37:02.270  2060  2060 I HotwordDetector: Closing mic
09-07 11:37:02.289   874   884 I ActivityManager: Start proc 3815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 11:37:02.341   376  2345 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 11:37:02.344   376  2345 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 11:37:02.351   376  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 11:37:02.355  2060  2339 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 11:37:02.358  2060  2342 I MicroRecognitionRnrImpl: Detection finished
09-07 11:37:02.370  3815  3815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 11:37:02.394  3815  3815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 11:37:02.407  3815  3815 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 5181-5190)
09-07 11:37:02.407  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 11:37:02.423  3815  3815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10dc0d6}
09-07 11:37:02.423  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 11:37:02.423  3815  3815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 11:37:02.429  3815  3815 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 11:37:02.430  3815  3815 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 11:37:02.450  3815  3815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 11:37:02.459  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 11:37:02.459  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 11:37:02.459  3815  3815 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 11:37:02.459  3815  3815 I Adreno  : Build Date                       : 10/20/15
09-07 11:37:02.459  3815  3815 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 11:37:02.459  3815  3815 I Adreno  : Local Branch                     : M14
09-07 11:37:02.459  3815  3815 I Adreno  : Remote Branch                    : 
09-07 11:37:02.459  3815  3815 I Adreno  : Remote Branch                    : 
09-07 11:37:02.459  3815  3815 I Adreno  : Reconstruct Branch               : 
,09-07 11:37:02.553   874   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb6a514:true
,09-07 11:37:02.612  3815  3815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 11:37:02.631  3815  3815 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 11:37:02.725  3815  3854 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 11:37:02.745  3815  3840 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 11:37:02.785  3815  3854 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 11:37:02.898   874   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +634ms
,09-07 11:37:02.903  1886  1886 I Keyboard.Facilitator: onFinishInput()
,09-07 11:37:02.965  3815  3815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3815
,09-07 11:37:03.115   874  1978 I ActivityManager: Killing 2295:com.google.android.talk/u0a61 (adj 15): empty #17
,09-07 11:37:03.169  3815  3815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 11:37:03.199   874  1978 I ActivityManager: Killing 2982:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-07 11:37:03.248   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:03.278  3815  3856 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1682245328
,09-07 11:37:03.288  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 11:37:03.288  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 11:37:03.288  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 11:37:03.288  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 11:37:03.288  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 11:37:03.289  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dafc47a added. We now have 1 listener(s)
,09-07 11:37:03.299  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 11:37:03.300  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 11:37:03.301  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 11:37:03.301  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 11:37:03.304  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 11:37:03.305  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@825aa21 added. We now have 1 listener(s)
09-07 11:37:03.305  3815  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:37:03.307   874  1305 D WifiService: New client listening to asynchronous messages
,09-07 11:37:03.308  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 11:37:03.308  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 11:37:03.308  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 11:37:03.308  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 11:37:03.308  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 11:37:03.311  3815  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:03.311  3815  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 11:37:03.315  3815  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:03.315  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:03.315  3815  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-07 11:37:03.315  3815  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:03.316  3815  3856 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 11:37:03.460  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:03.465  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:03.471  3815  3815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 11:37:04.203  3815  3865 W jxcore-log: Initializing JXcore engine
,09-07 11:37:04.203  3815  3865 W jxcore-log: JXcore engine is ready
,09-07 11:37:04.242  3865  3865 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-07 11:37:04.242  3865  3865 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9647]" dev="sockfs" ino=9647 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 11:37:04.242  3865  3865 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 11:37:04.242  3865  3865 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26779]" dev="sockfs" ino=26779 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 11:37:04.255  3815  3865 W jxcore-log: Starting JXcore engine
,09-07 11:37:04.338  3815  3865 W jxcore-log: Platform android
09-07 11:37:04.338  3815  3865 W jxcore-log: 
,09-07 11:37:04.339  3815  3865 W jxcore-log: Process ARCH arm
09-07 11:37:04.339  3815  3865 W jxcore-log: 
,09-07 11:37:04.609  3815  3865 I jxcore-log: JXcore Cordova bridge is ready!
09-07 11:37:04.609  3815  3865 I jxcore-log: 
,09-07 11:37:04.610  3815  3865 W jxcore-log: JXcore engine is started
,09-07 11:37:04.617  3815  3856 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 11:37:04.621  3815  3815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 11:37:09.624   874  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 11:37:14.443  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:14.449  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:14.508  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 11:37:14.508  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 11:37:14.508  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 11:37:14.508  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:14.556  3564  3877 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 11:37:14.556  3564  3877 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jdm.a(PG:82)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jcs.o(PG:406)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jcn.a(PG:1379)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jcs.i(PG:143)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at blb.a(PG:3937)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at czp.a(PG:18188)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at czp.a(PG:9081)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at czq.run(PG:1686)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 11:37:14.556  3564  3877 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jdj.a(PG:4091)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jdj.a(PG:1125)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jdm.a(PG:77)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	... 12 more
09-07 11:37:14.556  3564  3877 E HttpOperation: Caused by: faj: BadAuthentication
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at fal.a(PG:38)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	at jdj.a(PG:4089)
09-07 11:37:14.556  3564  3877 E HttpOperation: 	... 14 more
,09-07 11:37:14.651  1501  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 11:37:14.651  1501  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 11:37:14.651  1501  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 11:37:14.651  1501  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 11:37:14.653  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 11:37:14.653  3815  3865 I jxcore-log: 
,09-07 11:37:14.656  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 11:37:14.656  3815  3865 I jxcore-log: 
,09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:14.660  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:14.664  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:14.666  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 11:37:14.666  3815  3865 I jxcore-log: 
09-07 11:37:14.667  3564  3877 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 11:37:14.667  3564  3877 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jdm.a(PG:82)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jcs.o(PG:406)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jcn.a(PG:1379)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jcs.i(PG:143)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at hec.a(PG:42)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at hee.a(PG:102)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at czr.a(PG:65)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at kka.a(PG:108)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at czp.a(PG:19176)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at czp.a(PG:9081)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at czq.run(PG:1686)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 11:37:14.667  3564  3877 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jdj.a(PG:4091)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jdj.a(PG:1125)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jdm.a(PG:77)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	... 15 more
09-07 11:37:14.667  3564  3877 E HttpOperation: Caused by: faj: BadAuthentication
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at fal.a(PG:38)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	at jdj.a(PG:4089)
09-07 11:37:14.667  3564  3877 E HttpOperation: 	... 17 more
09-07 11:37:14.668  3564  3877 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 11:37:14.668  3564  3877 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at hec.a(PG:42)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at hee.a(PG:102)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at czr.a(PG:65)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at kka.a(PG:108)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 11,:37:14.668  3564  3877 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	... 15 more
09-07 11:37:14.668  3564  3877 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at fal.a(PG:38)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 11:37:14.668  3564  3877 E ExperimentLoader: 	... 17 more
09-07 11:37:14.668  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 11:37:14.668  3815  3865 I jxcore-log: 
,09-07 11:37:14.784   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126580, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-07 11:37:15.175  3815  3865 I jxcore-log: Unit Test app is loaded
09-07 11:37:15.175  3815  3865 I jxcore-log: 
,09-07 11:37:15.180  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:37:15.180  3815  3865 I jxcore-log: 
,09-07 11:37:15.185  3815  3865 D executeNativeTests: Running unit tests
,09-07 11:37:15.206  3815  3815 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-07 11:37:15.245  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:37:15.246  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca added. We now have 2 listener(s)
,09-07 11:37:15.247  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 11:37:15.247  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 11:37:15.247  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:15.247  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:37:15.247  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b added. We now have 2 listener(s)
09-07 11:37:15.247  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 11:37:15.247  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 11:37:15.250  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:15.270  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:15.276  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:15.276  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:37:15.300  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:15.302  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 11:37:15.302  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:15.303  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 11:37:15.304  3815  3865 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 11:37:15.304  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 11:37:15.304  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 11:37:15.305  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:15.305  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 11:37:15.305  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:15.305  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:15.305  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:15.306  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 11:37:15.306  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca removed from the list
,09-07 11:37:15.306  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:15.306  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b removed from the list
09-07 11:37:15.306  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:15.306  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:15.306  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:15.309  3815  3865 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 11:37:15.309  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:15.309  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:15.309  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:15.309  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:15.309  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:15.309  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:15.309  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:15.309  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:15.309  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:15.314  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-07 11:37:15.315  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:15.316  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:15.316  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:15.316  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:15.316  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
,09-07 11:37:15.316  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:15.316  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:15.316  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:15.316  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:15.316  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:15.317  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 11:37:15.319  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:15.327  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:15.329  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:15.329  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:15.330  3815  3865 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-07 11:37:15.330  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-07 11:37:15.330  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:15.330  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:15.330  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:15.330  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:15.331  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 11:37:15.331  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:37:15.331  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:15.332  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 11:37:15.332  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:15.332  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:15.332  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-07 11:37:15.332  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:15.335  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 11:37:15.335  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:15.335  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:37:15.335  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:37:15.339  3815  3879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:15.340  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:37:15.341  3815  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 11:37:15.341  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:37:15.341  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:15.343  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 11:37:15.343  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 11:37:15.344  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-07 11:37:15.344  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:15.344  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 11:37:15.344  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 11:37:15.345  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:15.350  2686  2698 D BtGatt.GattService: registerClient() - UUID=c28102c4-bf15-4a2e-90e5-cc9e2f2ecc47
,09-07 11:37:15.351  2686  2706 D BtGatt.GattService: onClientRegistered() - UUID=c28102c4-bf15-4a2e-90e5-cc9e2f2ecc47, clientIf=5
09-07 11:37:15.351  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 11:37:15.353  2686  2709 D BtGatt.AdvertiseManager: message : 0
,09-07 11:37:15.358  2686  2709 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:37:15.379  2686  2706 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 11:37:15.389  2686  2706 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 11:37:15.390  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:37:15.390  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:37:15.391  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:37:15.393  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 11:37:15.393  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:15.394  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:15.394  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:37:15.394  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:15.394  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:37:15.394  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:37:15.398  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:15.399  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:15.900  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 11:37:15.901  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:15.901  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:21.395   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:21.399  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 11:37:21.400  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 11:37:21.400  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 11:37:21.403  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:21.403  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 11:37:21.404  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 11:37:21.410  3815  3879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 11:37:21.411  3815  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 11:37:21.411  3815  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 11:37:21.413  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:37:21.413  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:21.414  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:21.414  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:21.414  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 11:37:21.415  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:21.415  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:21.415  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:21.417  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 11:37:21.418  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:21.419  3815  3865 D BluetoothLeScanner: could not find callback wrapper
,09-07 11:37:21.419  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:21.419  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-07 11:37:21.420  2686  2709 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:21.421  2686  2709 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 11:37:21.427  2686  2706 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 11:37:21.427  2686  2706 D BtGatt.GattService: Client app is not null!
,09-07 11:37:21.428  2686  2697 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 11:37:21.429  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 11:37:21.429  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:37:21.429  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 11:37:21.429  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:37:21.429  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 11:37:21.430  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:21.430  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:21.431  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:37:21.431  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:21.434  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 11:37:21.434  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 11:37:21.434  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 11:37:21.434  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:21.434  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:21.935  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:37:24.425   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:24.438  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 11:37:24.438  3815  3865 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-07 11:37:24.439  3815  3865 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-07 11:37:24.439  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-07 11:37:24.440  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 11:37:24.442  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:24.442  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 11:37:24.442  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:24.448  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 11:37:24.450  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 11:37:24.451  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 11:37:24.452  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 11:37:24.452  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 11:37:24.453  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:24.453  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:24.453  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:37:24.454  3815  3883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:24.461  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 11:37:24.462  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:37:24.462  3815  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 11:37:24.467  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:37:24.469  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 11:37:24.469  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:24.471  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 11:37:24.471  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 11:37:24.472  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61,
09-07 11:37:24.472  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 11:37:24.472  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:24.472  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:37:24.473  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:24.475  2686  2827 D BtGatt.GattService: registerClient() - UUID=416d1d90-da64-4cdb-a530-9de052961d45
,09-07 11:37:24.475  2686  2706 D BtGatt.GattService: onClientRegistered() - UUID=416d1d90-da64-4cdb-a530-9de052961d45, clientIf=5
09-07 11:37:24.477  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 11:37:24.478  2686  2709 D BtGatt.AdvertiseManager: message : 0
,09-07 11:37:24.480  2686  2709 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:37:24.489  2686  2706 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 11:37:24.501  2686  2706 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 11:37:24.502  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:37:24.502  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:37:24.504  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:37:24.505  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 11:37:24.505  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:24.506  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 11:37:24.506  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:24.506  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:37:24.506  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:24.506  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:37:24.508  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:24.508  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:25.010  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 11:37:25.010  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:25.010  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:30.471   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:30.511  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:30.511  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:30.511  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 11:37:30.511  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 11:37:30.512  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 11:37:30.512  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 11:37:30.513  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:30.513  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:30.513  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 11:37:30.514  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:30.514  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:30.514  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:30.514  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:37:30.515  3815  3883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 11:37:30.516  3815  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:30.516  3815  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:30.517  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.517  3815  3865 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:30.517  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:30.518  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-07 11:37:30.520  2686  2709 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:30.521  2686  2709 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 11:37:30.540  2686  2706 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 11:37:30.541  2686  2706 D BtGatt.GattService: Client app is not null!
,09-07 11:37:30.544  2686  2818 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 11:37:30.544  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 11:37:30.544  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 11:37:30.544  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:37:30.544  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 11:37:30.545  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 11:37:30.547  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-07 11:37:30.547  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:30.547  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-07 11:37:30.547  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:30.549  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:30.550  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:30.550  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:30.550  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:30.550  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:30.550  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:30.550  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:30.551  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 11:37:30.553  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:30.563  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:30.566  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:30.566  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:37:30.566  3815  3865 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-07 11:37:30.566  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-07 11:37:30.567  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 11:37:30.567  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:30.567  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:30.567  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:30.568  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 11:37:30.569  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:30.569  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 11:37:30.569  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:30.569  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:37:30.569  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:30.570  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:30.570  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:30.570  3815  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:30.571  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:30.572  3815  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 11:37:30.572  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:37:30.573  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:37:30.573  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:37:30.578  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-07 11:37:30.578  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:37:30.578  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:30.580  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 11:37:30.581  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 11:37:30.581  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-07 11:37:30.581  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:30.581  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:30.581  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:37:30.582  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:30.584  2686  2828 D BtGatt.GattService: registerClient() - UUID=09e250d0-74a6-4bea-958e-da54b5d46b53
,09-07 11:37:30.585  2686  2706 D BtGatt.GattService: onClientRegistered() - UUID=09e250d0-74a6-4bea-958e-da54b5d46b53, clientIf=5
,09-07 11:37:30.586  3815  3825 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 11:37:30.587  2686  2709 D BtGatt.AdvertiseManager: message : 0
,09-07 11:37:30.590  2686  2709 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:37:30.604  2686  2706 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 11:37:30.612  2686  2706 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 11:37:30.613  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 11:37:30.613  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:37:30.615  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:37:30.616  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK,
09-07 11:37:30.616  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 11:37:30.617  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:30.617  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 11:37:30.617  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:30.617  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:37:30.618  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:37:30.621  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 11:37:30.622  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:31.122  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 11:37:31.122  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:31.122  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:33.501   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:36.619  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 11:37:36.620  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 11:37:36.620  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 11:37:36.620  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 11:37:36.621  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:36.621  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 11:37:36.622  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:37:36.622  3815  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:36.622  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 11:37:36.622  3815  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 11:37:36.622  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 11:37:36.623  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:36.623  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 11:37:36.623  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:36.623  3815  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:36.623  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 11:37:36.624  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 11:37:36.626  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:36.627  3815  3865 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:36.627  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 11:37:36.627  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:37:36.630  2686  2709 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:36.631  2686  2709 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 11:37:36.640  2686  2706 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 11:37:36.640  2686  2706 D BtGatt.GattService: Client app is not null!
,09-07 11:37:36.641  2686  2827 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 11:37:36.642  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 11:37:36.642  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 11:37:36.642  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:37:36.642  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 11:37:36.642  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 11:37:36.644  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:36.644  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 11:37:36.645  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:37:36.646  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:36.649  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 11:37:36.649  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 11:37:36.650  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:36.650  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 11:37:36.651  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:36.651  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:37.152  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:37:37.316   874   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 11:37:37.326  1886  1886 I Keyboard.Facilitator: onFinishInput()
,09-07 11:37:37.336   874   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 11:37:37.336   874   896 I Adreno  : Build Date                       : 10/20/15
09-07 11:37:37.336   874   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 11:37:37.336   874   896 I Adreno  : Local Branch                     : M14
09-07 11:37:37.336   874   896 I Adreno  : Remote Branch                    : 
09-07 11:37:37.336   874   896 I Adreno  : Remote Branch                    : 
09-07 11:37:37.336   874   896 I Adreno  : Reconstruct Branch               : 
,09-07 11:37:37.356   280  2319 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (202 us)
,09-07 11:37:37.958  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 11:37:37.958  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 11:37:37.995   874   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 11:37:37.998  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f6d3ddc Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@181fa9c, 16908290=android.view.AbsSavedState$1@181fa9c}, android:focusedViewId=100}]}]
,09-07 11:37:37.998  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-07 11:37:37.999  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 11:37:37.999  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-07 11:37:38.007   874   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-07 11:37:38.015   874   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-07 11:37:38.015   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-07 11:37:38.016   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 11:37:38.245   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 11:37:38.248   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-07 11:37:38.250   874  1331 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,09-07 11:37:38.258   874   896 I DreamManagerService: Entering dreamland.
,09-07 11:37:38.259   874   896 I PowerManagerService: Dozing...
09-07 11:37:38.261   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 11:37:38.355   376  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-07 11:37:38.355   376  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 11:37:38.367   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:37:38.383  1965  3894 D NfcService: Discovery configuration equal, not updating.
,09-07 11:37:38.389   874  1304 E native  : do suspend false
,09-07 11:37:38.409   874  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 11:37:38.429   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:37:38.440   874  1304 E native  : do suspend true
,09-07 11:37:38.481   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 11:37:38.481   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 11:37:38.874   874  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-07 11:37:39.655  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.655  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:39.655  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:39.656  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.656  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:39.658  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:39.658  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.658  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.665  3815  3865 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 11:37:39.669  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.669  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:39.669  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.670  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.670  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:39.671  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:39.672  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.672  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:39.672  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.674  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 11:37:39.674  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.675  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.675  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.675  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.675  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:39.675  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:39.675  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.676  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.676  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.677  3815  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 11:37:39.677  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.677  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:39.677  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.677  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
,09-07 11:37:39.677  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:39.678  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:39.678  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.678  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.678  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.679  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 11:37:39.679  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:39.679  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.679  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.679  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
,09-07 11:37:39.679  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:39.680  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:39.680  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.680  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.680  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.680  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:39.681  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:39.681  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:39.681  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:39.681  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:39.681  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:39.681  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:39.681  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.681  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.682  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.682  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:39.682  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:39.682  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.682  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.682  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.683  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 11:37:39.684  3815  3865 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 11:37:39.684  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:39.690  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:39.690  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 11:37:39.690  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:37:39.691  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:39.691  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:39.691  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 11:37:39.691  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:39.691  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:37:39.691  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:37:39.692  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:39.692  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 11:37:39.692  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:39.692  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:39.692  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 11:37:39.694  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:39.695  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:37:39.695  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:37:39.696  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:39.696  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:39.696  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 11:37:39.696  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-07 11:37:39.696  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:37:39.696  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 11:37:39.697  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:37:39.698  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:37:39.698  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:39.698  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-07 11:37:39.698  3815  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:39.698  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 11:37:39.699  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:39.699  3815  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:39.699  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 11:37:39.699  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:39.699  3815  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-07 11:37:39.699  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:39.708  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-07 11:37:39.709  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-07 11:37:39.709  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 11:37:39.711  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 11:37:39.711  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-07 11:37:39.712  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-07 11:37:39.712  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 11:37:39.713  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 11:37:39.714  3815  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 430)
09-07 11:37:39.715  3815  3898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 11:37:39.717  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.718  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.718  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.719  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-07 11:37:39.720  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.720  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:39.720  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:39.720  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.720  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.720  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.722  3815  3865 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 11:37:39.723  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:39.723  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.723  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.723  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.723  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:39.723  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:39.724  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.724  3815  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 430
09-07 11:37:39.724  3815  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 430)
,09-07 11:37:39.725  2686  2815 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: -1
,09-07 11:37:39.725  3815  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 430)
09-07 11:37:39.725  3815  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 430)
09-07 11:37:39.724  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.726  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.728  3815  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-07 11:37:39.728  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.728  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.729  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.729  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.729  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:39.730  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:39.730  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:39.730  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.730  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.732  3815  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-07 11:37:39.732  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-07 11:37:39.733  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:39.733  3815  3865 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 11:37:39.733  3815  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-07 11:37:39.734  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 11:37:39.734  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 11:37:39.734  3815  3865 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 11:37:39.734  3815  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:39.735  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-07 11:37:39.735  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 11:37:39.735  3815  3865 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 11:37:39.735  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:39.736  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.736  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:39.736  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:39.736  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:39.736  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:39.737  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:39.737  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:39.737  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:39.737  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 11:37:39.739  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:39.743  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:39.745  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:39.745  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:37:39.746  3815  3865 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-07 11:37:39.746  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-07 11:37:39.746  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:39.746  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:37:39.747  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:39.747  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:39.747  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:39.747  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 11:37:39.748  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 11:37:39.748  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 11:37:39.748  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 11:37:39.749  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:37:39.749  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:39.749  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:37:39.749  3815  3900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:39.749  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:39.750  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:37:39.752  3815  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 11:37:39.752  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 11:37:39.753  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 11:37:39.756  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 11:37:39.756  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 11:37:39.756  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:39.758  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 11:37:39.758  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 11:37:39.758  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-07 11:37:39.758  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:39.759  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 11:37:39.759  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 11:37:39.759  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:39.761  2686  2697 D BtGatt.GattService: registerClient() - UUID=880ac796-fd6a-409e-8acb-bc51a596e413
,09-07 11:37:39.761  2686  2706 D BtGatt.GattService: onClientRegistered() - UUID=880ac796-fd6a-409e-8acb-bc51a596e413, clientIf=5
09-07 11:37:39.762  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 11:37:39.762  2686  2709 D BtGatt.AdvertiseManager: message : 0
,09-07 11:37:39.764  2686  2709 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 11:37:39.774  2686  2706 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 11:37:39.782  2686  2706 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 11:37:39.783  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 11:37:39.783  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 11:37:39.785  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 11:37:39.786  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 11:37:39.786  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:37:39.787  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 11:37:39.787  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 11:37:39.787  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 11:37:39.787  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 11:37:39.787  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 11:37:39.790  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:39.790  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 11:37:40.291  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 11:37:40.292  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:37:40.292  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 11:37:43.508  1856  2652 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 11:37:44.857  2686  2799 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-07 11:37:44.857  2686  2799 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-07 11:37:45.009  3057  3903 V KeepSync: Connecting to GoogleApiClient
,09-07 11:37:45.010   874  1683 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 11:37:45.074  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:45.078  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:45.118  1501  2027 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 11:37:45.118  1501  2027 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 11:37:45.118  1501  2027 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 11:37:45.119  1501  2027 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:45.156  1707  3904 V BaseAuthAsyncOperation: access token request failed
,09-07 11:37:45.160  3057  3903 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 11:37:45.273  1501  2273 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 11:37:45.274  1501  2273 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 11:37:45.274  1501  2273 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 11:37:45.275  1501  2273 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:45.317  3057  3903 E KeepSync: IOException
09-07 11:37:45.317  3057  3903 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 11:37:45.317  3057  3903 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 11:37:45.317  3057  3903 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 11:37:45.317  3057  3903 E KeepSync: 	... 10 more
,09-07 11:37:45.318  3057  3903 W KeepSync: Sync result 2
,09-07 11:37:45.326   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130318, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 11:37:45.791  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:45.791  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:45.792  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 11:37:45.792  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:45.793  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 11:37:45.793  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:45.793  3815  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 11:37:45.794  3815  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 11:37:45.794  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:45.794  3815  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 11:37:45.795  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:45.795  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:45.795  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:45.796  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:45.796  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:37:45.796  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:37:45.798  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 11:37:45.800  3815  3865 D BluetoothAdapter: STATE_ON
,09-07 11:37:45.801  3815  3865 D BluetoothLeScanner: could not find callback wrapper
09-07 11:37:45.801  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 11:37:45.802  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 11:37:45.804  2686  2709 D BtGatt.AdvertiseManager: message : 1
09-07 11:37:45.806  2686  2709 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 11:37:45.822  2686  2706 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 11:37:45.822  2686  2706 D BtGatt.GattService: Client app is not null!
,09-07 11:37:45.824  2686  2698 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 11:37:45.825  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 11:37:45.825  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 11:37:45.826  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 11:37:45.826  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 11:37:45.826  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 11:37:45.828  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:37:45.828  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 11:37:45.828  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:45.829  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:37:45.832  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:45.832  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:45.832  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:45.833  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 11:37:45.833  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:45.834  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:46.334  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:37:48.838  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:48.839  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:48.839  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:48.840  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:48.840  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:48.840  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:48.840  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:48.841  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:48.841  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:48.846  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:37:48.846  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:48.849  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 11:37:48.850  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 11:37:48.850  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 11:37:48.851  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 11:37:48.851  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 11:37:48.851  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 11:37:48.853  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:48.853  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:37:48.853  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 11:37:48.853  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 11:37:48.854  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:48.854  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 11:37:48.854  3815  3906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 11:37:48.854  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
,09-07 11:37:48.855  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:37:48.855  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:48.855  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:37:48.857  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 11:37:48.857  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 11:37:48.857  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:48.858  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:48.859  3815  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 11:37:48.859  3815  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 11:37:48.859  3815  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 11:37:48.860  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:48.861  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:48.861  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:48.861  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-07 11:37:48.861  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:48.861  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:48.861  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:37:48.861  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 11:37:48.862  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:37:48.862  3815  3865 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 11:37:48.863  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 11:37:48.863  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:48.865  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 11:37:48.865  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:48.865  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:48.865  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:48.866  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:48.866  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:48.866  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
09-07 11:37:48.866  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:48.866  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:48.866  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:48.875  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:48.875  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:48.876  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 11:37:48.876  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
,09-07 11:37:48.876  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:48.877  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:48.877  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:48.877  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:48.877  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:48.880  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:48.880  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:48.880  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:48.881  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73188ca not in the list
09-07 11:37:48.881  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:48.881  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e00fa3b not in the list
,09-07 11:37:48.881  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:48.882  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:48.882  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:48.885  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-07 11:37:48.885  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:48.885  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-07 11:37:48.886  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:48.886  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 11:37:48.886  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 11:37:48.894  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 11:37:48.894  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-07 11:37:48.896  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-07 11:37:48.896  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 11:37:48.896  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 11:37:48.897  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 11:37:48.897  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 11:37:48.897  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-07 11:37:48.899  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-07 11:37:48.900  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 11:37:48.900  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-07 11:37:48.900  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 11:37:48.901  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 11:37:48.901  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-07 11:37:48.902  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:37:48.902  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83b2e21 added. We now have 2 listener(s)
,09-07 11:37:48.904  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 11:37:48.904  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:37:48.904  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:48.904  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:37:48.904  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c6e246 added. We now have 2 listener(s)
09-07 11:37:48.904  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:37:48.905  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 11:37:48.910  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:48.915  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:48.917  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:48.917  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:37:48.918  3815  3865 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 11:37:48.919   874  2116 D WifiService: setWifiEnabled: true pid=3815, uid=10000
09-07 11:37:48.919   874  2116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 11:37:48.923  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:48.926  3815  3865 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 11:37:48.927   874  1370 D WifiService: setWifiEnabled: false pid=3815, uid=10000
09-07 11:37:48.927   874  1370 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 11:37:48.927  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:48.948  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 11:37:48.952   874  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 11:37:48.953   874  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-07 11:37:48.953   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 11:37:48.953   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 11:37:48.962   874  1304 E native  : do suspend true
,09-07 11:37:48.975   874  1901 D DhcpClient: Clearing IP address
,09-07 11:37:48.975   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:37:48.979   372   872 D CommandListener: Setting iface cfg
,09-07 11:37:48.982  1501  2496 V NativeCrypto: Read error: ssl=0x9b36e400: I/O error during system call, Connection timed out
,09-07 11:37:48.986   874  1905 D DhcpClient: Receive thread stopped
,09-07 11:37:48.988   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 11:37:48.988   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 11:37:48.996   472   472 E Parcel  : Reading a NULL string not supported here.
09-07 11:37:49.001   874  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-07 11:37:49.002   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 11:37:49.002   874  1304 E native  : do suspend true
09-07 11:37:49.001   874  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-07 11:37:49.015  1501  2496 V NativeCrypto: SSL shutdown failed: ssl=0x9b36e400: I/O error during system call, Broken pipe
,09-07 11:37:49.039   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:37:49.053   874   887 I ActivityManager: Start proc 3913:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-07 11:37:49.074   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:37:49.075   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:37:49.075   874  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 11:37:49.076   874  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:49.080   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 11:37:49.084   874   893 D Tethering: MasterInitialState.processMessage what=3
,09-07 11:37:49.087  3414  3414 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dafc47a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:49.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:49.088  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-07 11:37:49.090  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:49.094  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:49.096  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:49.097   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:37:49.101   874  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:49.103  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:49.105  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:49.106  1856  2311 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:49.108  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:49.110  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:49.117  3913  3913 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-07 11:37:49.170   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 11:37:49.172   874  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 11:37:49.259  3913  3935 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-07 11:37:49.259  3913  3935 I Babel_SMS: MmsConfig.loadMmsSettings
,09-07 11:37:49.264  3913  3935 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-07 11:37:49.264  3913  3935 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 11:37:49.295  3913  3935 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-07 11:37:49.295  3913  3935 I Babel_SMS: MmsConfig.loadFromResources
,09-07 11:37:49.299  3913  3935 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-07 11:37:49.301  3913  3935 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-07 11:37:49.341  3913  3913 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:37:49.345  3913  3913 I Babel_Crash: startup - clean
,09-07 11:37:49.363  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:37:49.374  3913  3913 I Babel_telephony: TeleModule.launchCompleted
,09-07 11:37:49.388   874  1930 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-07 11:37:49.401  3913  3913 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-07 11:37:49.408  3913  3913 W Babel   : BAM#gBA: invalid account id: -1
,09-07 11:37:49.409  3913  3913 W Babel   : BAM#gBA: invalid account id: -1
,09-07 11:37:49.409  3913  3913 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-07 11:37:49.413  3913  3940 I Babel   : deleted: false for 0
,09-07 11:37:49.424   874  1978 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-07 11:37:49.444  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 11:37:49.449  1707  1707 D SystemUpdateService: onCreate
,09-07 11:37:49.452  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 11:37:49.469  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 11:37:49.482  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 11:37:49.483  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 11:37:49.505   874  1930 I ActivityManager: Start proc 3944:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-07 11:37:49.509  1707  2458 I iu.UploadsManager: num queued entries: 0
,09-07 11:37:49.510  1707  3942 I SystemUpdateService: active receiver: enabled
,09-07 11:37:49.531  1707  2458 I iu.UploadsManager: num updated entries: 0
09-07 11:37:49.532  1707  2458 I iu.SyncManager: NEXT; no task
,09-07 11:37:49.541  3913  3913 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:49.546  1707  3942 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 11:37:49.577  1707  3942 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-07 11:37:49.577  1707  3942 I SystemUpdateService: now status is 0 (complete)
,09-07 11:37:49.577  1707  3942 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 11:37:49.577  1707  3942 I SystemUpdateService: file has been verified
09-07 11:37:49.577  1707  3942 I SystemUpdateService: OTA package size = 12249756
,09-07 11:37:49.585  3944  3944 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 11:37:49.596  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:49.616  3944  3944 D SprintDMHelper: simOperator: 
09-07 11:37:49.616  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 11:37:49.621  3913  3913 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 11:37:49.630  1707  3942 I SystemUpdateService: showing system update notification
,09-07 11:37:49.637  3913  3913 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:49.643  3913  3913 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:49.652  3913  3913 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:49.653   874  2014 I ActivityManager: Start proc 3956:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 11:37:49.663  3913  3913 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 11:37:49.666   874  1930 I ActivityManager: Killing 3252:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-07 11:37:49.712  3913  3913 I vclib   : onServiceConnected
,09-07 11:37:49.769  1707  1707 D SystemUpdateService: onDestroy
,09-07 11:37:49.772   874   884 I ActivityManager: Killing 3579:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-07 11:37:49.875   874  1684 I ActivityManager: Start proc 3972:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 11:37:49.879  3913  3971 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-07 11:37:49.882   874  2014 I ActivityManager: Killing 3414:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 11:37:49.950  3972  3972 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 11:37:50.010  3972  3972 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 11:37:50.010  3972  3972 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 11:37:50.010  3972  3972 I GAv4    :   adb logcat -s GAv4
,09-07 11:37:50.027  3972  3972 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 11:37:50.035  3972  3972 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 11:37:50.066  3972  3989 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 11:37:50.169  3972  3972 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 11:37:50.222  3972  3972 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 11:37:50.235  3972  3972 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3012-3018)
,09-07 11:37:50.235  3972  3972 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 11:37:50.245  3972  3972 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dc2402a}
,09-07 11:37:50.245  3972  3972 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 11:37:50.246  3972  3972 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 11:37:50.255  3972  3972 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 11:37:50.257  3972  3972 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 11:37:50.277  3972  3972 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 11:37:50.293  3972  3972 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 11:37:50.293  3972  3972 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 11:37:50.293  3972  3972 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 11:37:50.293  3972  3972 I Adreno  : Build Date                       : 10/20/15
09-07 11:37:50.293  3972  3972 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 11:37:50.293  3972  3972 I Adreno  : Local Branch                     : M14
09-07 11:37:50.293  3972  3972 I Adreno  : Remote Branch                    : 
09-07 11:37:50.293  3972  3972 I Adreno  : Remote Branch                    : 
09-07 11:37:50.293  3972  3972 I Adreno  : Reconstruct Branch               : 
,09-07 11:37:50.356  3972  3972 I NSApplication: Starting up...
,09-07 11:37:50.369  3972  4018 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 11:37:50.398   874   884 I ActivityManager: Start proc 4023:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 11:37:50.399   874   884 I ActivityManager: Killing 3468:com.android.providers.calendar/u0a3 (adj 15): empty #17
09-07 11:37:50.400   278   278 E lowmemorykiller: Error writing /proc/3468/oom_score_adj; errno=22
,09-07 11:37:50.469  4023  4023 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 11:37:50.647   874  2014 I ActivityManager: Killing 3507:android.process.acore/u0a5 (adj 15): empty #17
,09-07 11:37:50.745   874  1684 I ActivityManager: Start proc 4037:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 11:37:50.791  4037  4037 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 11:37:50.835  4037  4037 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 11:37:50.891   874  2029 I ActivityManager: Killing 3672:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 11:37:54.941  3815  3865 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-07 11:37:54.945   874  2029 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,09-07 11:37:54.946   874  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 11:37:54.964   874  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:54.978  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:54.984  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:54.985  2686  2702 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 11:37:54.986  2686  2702 D BluetoothAdapterProperties: Setting state to 13
09-07 11:37:54.986  2686  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 11:37:54.986  2686  2702 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 11:37:54.988  2686  2702 I BluetoothAdapterState: Entering PendingCommandState
,09-07 11:37:54.989  2686  2686 D BluetoothMapService: onReceive
,09-07 11:37:54.989  2686  2686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 11:37:54.990  2686  2686 D BluetoothMapService: STATE_TURNING_OFF
,09-07 11:37:54.990  2686  2686 D BluetoothMapService: MAP Service closeService in
09-07 11:37:54.990  2686  2686 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 11:37:54.990  2686  2686 D ObexServerSockets0: shutdown(block = true)
09-07 11:37:54.991  2686  2686 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 11:37:54.991  2686  2686 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 11:37:54.991  2686  2829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 11:37:54.992  2686  2706 D BluetoothAdapterProperties: Scan Mode:20
,09-07 11:37:54.992  2686  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 11:37:54.992  2686  2830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-07 11:37:54.992  2686  2815 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 11:37:54.994  2686  2686 D HeadsetService: Received stop request...Stopping profile...
09-07 11:37:54.995   874  1304 D WifiConfigStore: loaded 0 passpoint configs
09-07 11:37:54.996   874  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 11:37:54.996  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:54.996  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:37:54.996  2686  2686 I BtOppRfcommListener: stopping Accept Thread
09-07 11:37:54.996  2686  3446 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 11:37:54.996   874  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 11:37:54.997   874  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 11:37:54.998   874  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 11:37:54.998   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 11:37:54.998   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-07 11:37:54.998  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:54.998  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:37:54.998  2686  3446 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 11:37:54.998   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 11:37:54.999  1980  2150 D BluetoothHeadset: Proxy object disconnected
,09-07 11:37:55.000   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 11:37:55.000   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 11:37:55.000  1362  2124 D BluetoothHeadset: Proxy object disconnected
09-07 11:37:55.001  2686  2686 D A2dpService: Received stop request...Stopping profile...
,09-07 11:37:55.001  2686  2822 D A2dpStateMachine: Exit Disconnected: -1
09-07 11:37:55.001  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:37:55.001  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:37:55.002  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:37:55.002  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:37:55.002   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 11:37:55.003  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:55.003  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-07 11:37:55.003  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.003  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:55.004  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:55.006  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:55.007  2686  2686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 11:37:55.008  2686  2799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:55.008  2686  2799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:55.008  2686  2799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:55.008  2686  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-07 11:37:55.007  2686  2686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 11:37:55.008  2686  2702 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
09-07 11:37:55.008  2686  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 11:37:55.008  2686  2706 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 11:37:55.008  2686  2686 D HidService: Received stop request...Stopping profile...
09-07 11:37:55.009  2686  2686 D HidService: Stopping Bluetooth HidService
09-07 11:37:55.009  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:55.010  2686  2686 D HealthService: Received stop request...Stopping profile...
09-07 11:37:55.011  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:55.011  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-07 11:37:55.012  1362  1362 D BluetoothA2dp: Proxy object disconnected
,09-07 11:37:55.012  1362  1362 D BluetoothInputDevice: Proxy object disconnected
09-07 11:37:55.012  1362  1362 D HidProfile: Bluetooth service disconnected
09-07 11:37:55.014  2686  2686 D PanService: Received stop request...Stopping profile...
09-07 11:37:55.015   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-07 11:37:55.016   372   872 D CommandListener: Setting iface cfg
09-07 11:37:55.016  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:55.017  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:55.017  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.017  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:55.017   874  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.62 rxSuccessRate=10.00 delta 1000 -> 994
09-07 11:37:55.017   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 11:37:55.017  2686  2686 D BluetoothMapService: Received stop request...Stopping profile...
09-07 11:37:55.017  2686  2686 D BluetoothMapService: stop()
09-07 11:37:55.018   874  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 11:37:55.018   874  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 11:37:55.018  2686  2686 D BluetoothMapAppObserver: deinitObservers()
09-07 11:37:55.018  2686  2686 D BluetoothMapAppObserver: removeReceiver()
09-07 11:37:55.022  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:55.022  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:55.022  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.022  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:55.022  2686  2686 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 11:37:55.022  2686  2686 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 11:37:55.023  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:55.023  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:55.023  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.023  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:55.023  2686  2686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 11:37:55.023  2686  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 11:37:55.023  2686  2799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:55.023  2686  2799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 11:37:55.023  2686  2799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 11:37:55.023  2686  2799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 11:37:55.023  2686  2799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 11:37:55.023  2686  2799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 11:37:55.024  2686  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 11:37:55.024  2686  2686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 11:37:55.024  2686  2706 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 11:37:55.024  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:55.024  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:55.024  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.024  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 11:37:55.024  2686  2686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 11:37:55.024  2686  2686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 11:37:55.025  2686  2686 D BluetoothMapService: MAP Service closeService in
09-07 11:37:55.025  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-07 11:37:55.025  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-07 11:37:55.025  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.025  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-07 11:37:55.026  2686  2686 D BluetoothMapService: cleanup()
,09-07 11:37:55.026  2686  2686 D BluetoothMapService: MAP Service closeService in
09-07 11:37:55.026  2686  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 11:37:55.026  2686  2702 D BluetoothAdapterProperties: Setting state to 15
09-07 11:37:55.026  2686  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 11:37:55.027  1362  2124 D BluetoothMap: onBluetoothStateChange: up=false
09-07 11:37:55.027  2686  2702 I BluetoothAdapterState: Entering BleOnState
,09-07 11:37:55.027  2686  2702 D BluetoothAdapterState: Current state: BLE ON, message: 0
09-07 11:37:55.027  1362  1376 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 11:37:55.030   874  1304 E native  : do suspend true
09-07 11:37:55.030  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 11:37:55.030  1362  1362 D PanProfile: Bluetooth service disconnected
,09-07 11:37:55.044   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 11:37:55.044   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 11:37:55.044   874  2115 I ActivityManager: Start proc 4074:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-07 11:37:55.046  1362  2124 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 11:37:55.047   874   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 11:37:55.047   874   893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 11:37:55.047   874   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 11:37:55.047  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 11:37:55.047   874   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 11:37:55.047  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 11:37:55.048  1362  2124 D BluetoothPan: onBluetoothStateChange on: false
,09-07 11:37:55.049  1980  1996 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 11:37:55.049  2686  2702 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-07 11:37:55.050  2686  2702 D BluetoothAdapterProperties: Setting state to 16
09-07 11:37:55.050  2686  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 11:37:55.050  2686  2702 D BluetoothAdapterProperties: onBleDisable
09-07 11:37:55.050  2686  2702 I BluetoothAdapterState: Entering PendingCommandState
09-07 11:37:55.051  2686  2703 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 11:37:55.051  2686  2706 D BluetoothAdapterProperties: Scan Mode:20
09-07 11:37:55.052  2686  2799 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 11:37:55.052  2686  2799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 11:37:55.053  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:55.054  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:55.054   874  1303 D WifiNative-HAL: p2pGetDeviceAddress
09-07 11:37:55.055   874  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-07 11:37:55.057  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:55.058  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:55.064   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 11:37:55.088  4074  4074 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 11:37:55.094   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 11:37:55.096  1455  1455 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 11:37:55.101  4074  4074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 11:37:55.108  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 11:37:55.112   874   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bfa88a8:true
,09-07 11:37:55.125   874  2002 I ActivityManager: Start proc 4086:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-07 11:37:55.135  4074  4074 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 11:37:55.138  4074  4074 D BluetoothMap: Create BluetoothMap proxy object
,09-07 11:37:55.143  4074  4074 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 11:37:55.150  4074  4074 D DockEventReceiver: finishStartingService: stopping service
,09-07 11:37:55.152   874  1683 I ActivityManager: Killing 3689:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 11:37:55.172  4086  4086 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 11:37:55.255  2686  2706 I bt_hci  : shut_down
,09-07 11:37:55.255  2686  2712 D bt_hwcfg: hw_epilog_process
,09-07 11:37:55.267  2686  2712 I bt_vendor: low_power_mode_cb
,09-07 11:37:55.286  2686  2712 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 11:37:55.287  2686  2712 I bt_vendor: epilog_cb
,09-07 11:37:55.287  2686  2712 I bt_hci  : epilog_finished_callback
,09-07 11:37:55.293  2686  2706 I bt_hci_h4: hal_close
,09-07 11:37:55.294  2686  2706 I bt_userial_vendor: device fd = 51 close
,09-07 11:37:55.379  4086  4086 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 11:37:55.379  4086  4086 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 11:37:55.379  4086  4086 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 11:37:55.379  4086  4086 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:37:55.379  4086  4086 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:37:55.379  4086  4086 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.379  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:37:55.380  4086  4086 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:37:55.380  4086  4086 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:37:55.380  4086  4086 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:37:55.387  4074  4074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 11:37:55.400  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 11:37:55.406  4074  4074 D DockEventReceiver: finishStartingService: stopping service
09-07 11:37:55.421   874  1981 I ActivityManager: Killing 2083:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 11:37:55.480  2686  2703 D bt_stack_manager: event_shut_down_stack finished.
09-07 11:37:55.481  2686  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 11:37:55.485  2686  2702 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 11:37:55.485  2686  2686 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 11:37:55.487  2686  2686 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 11:37:55.487  2686  2686 D BtGatt.GattService: stop()
,09-07 11:37:55.487  2686  2686 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 11:37:55.491  2686  2686 V BluetoothAdapterState: isTurningOff()=false
,09-07 11:37:55.491  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-07 11:37:55.491  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-07 11:37:55.491  2686  2686 V BluetoothAdapterState: isBleTurningOff()=true
09-07 11:37:55.492  2686  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 11:37:55.493  2686  2702 D BluetoothAdapterProperties: Setting state to 10
,09-07 11:37:55.493  2686  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 11:37:55.494  2686  2702 I BluetoothAdapterState: Entering OffState
,09-07 11:37:55.511  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:55.513  4074  4074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 11:37:55.514  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:55.517  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 11:37:55.518  1455  1455 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 11:37:55.531  4074  4074 D DockEventReceiver: finishStartingService: stopping service
,09-07 11:37:55.558  1455  1455 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 11:37:55.560  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 11:37:55.561   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:37:55.573   874  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 11:37:55.574   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 11:37:55.574   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 11:37:55.589   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 11:37:55.599   372   872 D CommandListener: Setting iface cfg
,09-07 11:37:55.601   874  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 11:37:55.618   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 11:37:55.640  4086  4110 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 11:37:55.646   874  4122 D DhcpClient: Receive thread started
,09-07 11:37:55.661   874   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f0164d9:true
,09-07 11:37:55.728   874  1304 E native  : do suspend false
,09-07 11:37:55.739   874  1901 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 11:37:55.755   874  4122 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172654, domain null
,09-07 11:37:55.755   874  1901 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172654 seconds
,09-07 11:37:55.758   874  1901 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 11:37:55.770   874  4122 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 11:37:55.770   874  1901 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 11:37:55.774   372   872 D CommandListener: Setting iface cfg
,09-07 11:37:55.778   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 11:37:55.783   874  1304 E native  : do suspend true
,09-07 11:37:55.784   874  1901 D DhcpClient: Scheduling renewal in 86399s
,09-07 11:37:55.793   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 11:37:55.794   874  1304 D WifiConfigStore: No blacklist allowed without epno enabled
09-07 11:37:55.794   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 11:37:55.800   874  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 11:37:55.800   874  1306 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 11:37:55.851   874  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 11:37:55.852   874  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 11:37:55.854   874  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 11:37:55.856   874  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 11:37:55.858   874  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 11:37:55.866   874  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 11:37:55.871   874  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 11:37:55.871   874  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 11:37:55.871   874  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 11:37:55.871   874  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 11:37:55.872   874  1306 D ConnectivityService:    accepting network in place of null
09-07 11:37:55.872   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 11:37:55.872   874  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 11:37:55.897   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:37:55.915   874  4120 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168698, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 11:37:55.922   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:37:55.927   874  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 11:37:55.927   874  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:55.930   874  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 11:37:55.933   874   893 D Tethering: MasterInitialState.processMessage what=3
,09-07 11:37:55.946  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:55.947  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:55.949  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:55.949  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:55.953  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:55.953  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:55.953  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:37:55.953  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:37:55.957  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 11:37:55.963  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 11:37:55.966  1707  1707 D SystemUpdateService: onCreate
,09-07 11:37:55.970  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 11:37:55.972  3772  4134 I BooksSync: Starting books sync for 61035162, extras: ade
09-07 11:37:55.973  1707  4135 I SystemUpdateService: active receiver: enabled
,09-07 11:37:55.977  1707  4135 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 11:37:55.980  1707  4135 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 11:37:55.980  1707  4135 I SystemUpdateService: now status is 0 (complete)
,09-07 11:37:55.980  1707  4135 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 11:37:55.980  1707  4135 I SystemUpdateService: file has been verified
09-07 11:37:55.980  1707  4135 I SystemUpdateService: OTA package size = 12249756
,09-07 11:37:55.982  1707  4135 I SystemUpdateService: showing system update notification
,09-07 11:37:55.994  1707  1707 D SystemUpdateService: onDestroy
,09-07 11:37:55.995  3772  4137 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 11:37:55.996  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:56.000   874  4118 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-07 11:37:56.007  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:56.009  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:37:56.015  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 11:37:56.017  1707  2458 I iu.UploadsManager: num queued entries: 0
,09-07 11:37:56.018  1707  2458 I iu.UploadsManager: num updated entries: 0
,09-07 11:37:56.020  1707  2458 I iu.SyncManager: NEXT; no task
,09-07 11:37:56.025  1707  4140 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 11:37:56.025  1707  4140 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 11:37:56.027  1707  4140 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 11:37:56.027  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 11:37:56.029  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 11:37:56.031  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:37:56.034  3944  3944 D SprintDMHelper: simOperator: 
,09-07 11:37:56.034  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 11:37:56.057   874  4118 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 09:37:56 GMT], X-Android-Received-Millis=[1473241076056], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473241076035]}
,09-07 11:37:56.059   874  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 11:37:56.059   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-07 11:37:56.059   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 11:37:56.060   874  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 11:37:56.098  1501  4145 I VacuumService: Vacuum at: now=1473241076098 tag=VacuumService
,09-07 11:37:56.102  1501  2027 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 11:37:56.102  1501  2027 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 11:37:56.102  1501  2027 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 11:37:56.102  1501  2027 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:56.162  1501  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 11:37:56.169  1501  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 11:37:56.169  1501  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 11:37:56.169  1501  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:56.178  1501  2160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 11:37:56.178  1501  2160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 11:37:56.178  1501  2160 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 11:37:56.178  1501  2160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:56.189  3772  4137 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 11:37:56.191  3772  4134 E BooksSync: Soft error
09-07 11:37:56.191  3772  4134 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 11:37:56.191  3772  4134 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 11:37:56.191  3772  4134 E BooksSync: Sync error
09-07 11:37:56.191  3772  4134 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 11:37:56.191  3772  4134 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 11:37:56.191  3772  4134 I BooksSync: Finished books sync
,09-07 11:37:56.193  1707  4140 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-07 11:37:56.195  3913  4142 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 11:37:56.197   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162279, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 11:37:56.214  1501  4146 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-07 11:37:56.216  1501  4146 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 11:37:56.247  1501  4146 W Uploader:  no longer exists, so no auth token.
,09-07 11:37:56.928   874  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 11:37:57.740  1501  4146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 11:37:57.740  1501  4146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-07 11:37:57.741  1501  4146 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 11:37:57.741  1501  4146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:57.786  1501  4146 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 11:37:57.786  1501  4146 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 11:37:57.786  1501  4146 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 11:37:58.211  1501  4146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 11:37:58.212  1501  4146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 11:37:58.212  1501  4146 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 11:37:58.213  1501  4146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:58.265  1501  4146 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 11:37:58.265  1501  4146 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 11:37:58.265  1501  4146 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 11:37:58.460  1501  4146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 11:37:58.461  1501  4146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 11:37:58.461  1501  4146 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 11:37:58.462  1501  4146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:37:58.516  1501  4146 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 11:37:58.516  1501  4146 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 11:37:58.516  1501  4146 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 11:38:01.027  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:38:01.038   874  2116 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,09-07 11:38:01.039   874  2116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 11:38:01.075  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 11:38:01.081   874  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 11:38:01.081   874  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-07 11:38:01.081   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 11:38:01.081   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 11:38:01.099   874  1304 E native  : do suspend true
,09-07 11:38:01.113   874  1901 D DhcpClient: Clearing IP address
,09-07 11:38:01.113   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 11:38:01.126   372   872 D CommandListener: Setting iface cfg
,09-07 11:38:01.127  1501  4155 V NativeCrypto: Read error: ssl=0x9b3b6a00: I/O error during system call, Connection timed out
,09-07 11:38:01.131   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 11:38:01.131   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-07 11:38:01.139   472   472 E Parcel  : Reading a NULL string not supported here.
,09-07 11:38:01.145   874  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 11:38:01.147   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 11:38:01.147   874  1304 E native  : do suspend true
,09-07 11:38:01.148   874  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 11:38:01.148  1501  4155 V NativeCrypto: SSL shutdown failed: ssl=0x9b3b6a00: I/O error during system call, Broken pipe
,09-07 11:38:01.154   874  4122 D DhcpClient: Receive thread stopped,
,09-07 11:38:01.188   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:38:01.220   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:38:01.220   372   872 D CommandListener: Clearing all IP addresses on wlan0,
,09-07 11:38:01.222   874  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 11:38:01.222   874  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:38:01.227   874   893 D Tethering: MasterInitialState.processMessage what=3
09-07 11:38:01.238  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:38:01.238  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:38:01.238   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 11:38:01.241  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:01.241  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:38:01.260   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:38:01.262  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-07 11:38:01.263  1856  2311 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:38:01.264  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:38:01.264  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:38:01.265  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:01.265  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:38:01.267   874  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 11:38:01.268  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:38:01.268  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:38:01.269  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:01.269  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:38:01.271  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 11:38:01.271  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:38:01.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 11:38:01.273  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:01.273  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 11:38:01.277  1707  1707 D SystemUpdateService: onCreate
,09-07 11:38:01.282  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 11:38:01.293  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 11:38:01.295  1707  2458 I iu.UploadsManager: num queued entries: 0
,09-07 11:38:01.295  1707  2458 I iu.UploadsManager: num updated entries: 0
,09-07 11:38:01.299  1707  4170 I SystemUpdateService: active receiver: enabled
,09-07 11:38:01.301  1707  2458 I iu.SyncManager: NEXT; no task
,09-07 11:38:01.302  1707  4170 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 11:38:01.304  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 11:38:01.305  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 11:38:01.308  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:38:01.312  3944  3944 D SprintDMHelper: simOperator: ,
09-07 11:38:01.312  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 11:38:01.322  1707  4170 I SystemUpdateService: network: null; metered: false; mobile allowed: true,
09-07 11:38:01.322  1707  4170 I SystemUpdateService: now status is 0 (complete)
09-07 11:38:01.322  1707  4170 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 11:38:01.336  3913  4173 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 11:38:01.323  1707  4170 I SystemUpdateService: file has been verified
,09-07 11:38:01.346  1707  4170 I SystemUpdateService: OTA package size = 12249756
,09-07 11:38:01.353   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 11:38:01.354   874  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 11:38:01.358  1707  4170 I SystemUpdateService: showing system update notification
,09-07 11:38:01.367  1707  1707 D SystemUpdateService: onDestroy
,09-07 11:38:03.874   874  1306 D ConnectivityService: handlePromptUnvalidated 101
,09-07 11:38:04.057  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:38:04.058   874  2116 D WifiService: setWifiEnabled: true pid=3815, uid=10000
09-07 11:38:04.059   874  2116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 11:38:04.070   874  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-07 11:38:04.080  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:38:04.080  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:38:04.082  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:04.083  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:38:04.089  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 11:38:04.090  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 11:38:04.092  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:04.092  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 11:38:04.100   874  1304 D WifiConfigStore: loaded 0 passpoint configs
,09-07 11:38:04.101   874  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 11:38:04.103   874  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 11:38:04.104   874  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 11:38:04.104   874  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 11:38:04.104   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 11:38:04.105   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 11:38:04.124   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-07 11:38:04.126   372   872 D CommandListener: Setting iface cfg
09-07 11:38:04.126   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 11:38:04.126   874  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-07 11:38:04.126   874  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 11:38:04.140   874  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 11:38:04.140   874  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 11:38:04.144   874  1304 E native  : do suspend true
,09-07 11:38:04.175   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:38:05.447   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 11:38:05.514   874  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.75 rxSuccessRate=7.56 delta 1000 -> 994
,09-07 11:38:05.516   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 11:38:05.516   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 11:38:05.532   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 11:38:05.595   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 11:38:05.597  1455  1455 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 11:38:06.145  1455  1455 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 11:38:06.201  1455  1455 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 11:38:06.202  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 11:38:06.209   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 11:38:06.229   874  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 11:38:06.230   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 11:38:06.230   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 11:38:06.257   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 11:38:06.280   372   872 D CommandListener: Setting iface cfg
,09-07 11:38:06.286   874  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 11:38:06.292   874  4184 D DhcpClient: Receive thread started
,09-07 11:38:06.301   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 11:38:06.397   874  1304 E native  : do suspend false
,09-07 11:38:06.419   874  1901 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 11:38:06.442   874  4184 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172789, domain null
,09-07 11:38:06.444   874  1901 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172789 seconds
,09-07 11:38:06.447   874  1901 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 11:38:06.460   874  4184 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 11:38:06.461   874  1901 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 11:38:06.466   372   872 D CommandListener: Setting iface cfg
,09-07 11:38:06.478   874  1901 D DhcpClient: Scheduling renewal in 86399s
,09-07 11:38:06.478   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 11:38:06.482   874  1304 E native  : do suspend true
,09-07 11:38:06.508   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 11:38:06.511   874  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 11:38:06.512   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 11:38:06.515   874  1306 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 11:38:06.517   874  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 11:38:06.573   874  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 11:38:06.573   874  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-07 11:38:06.577   874  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 11:38:06.579   874  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 11:38:06.581   874  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 11:38:06.595   874  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 11:38:06.605   874  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-07 11:38:06.606   874  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 11:38:06.606   874  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-07 11:38:06.608   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 11:38:06.608   874  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 11:38:06.609   874  1306 D ConnectivityService:    accepting network in place of null
,09-07 11:38:06.611   874  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 11:38:06.643   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:38:06.658   874  4183 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 11:38:06.692   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 11:38:06.704   874  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-07 11:38:06.704   874  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:38:06.709   874  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-07 11:38:06.712   874   893 D Tethering: MasterInitialState.processMessage what=3
09-07 11:38:06.718  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:38:06.718  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:38:06.719  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:06.719  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:38:06.725  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:38:06.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:38:06.727  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:06.727  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:38:06.736  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 11:38:06.748  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 11:38:06.752  1707  1707 D SystemUpdateService: onCreate
,09-07 11:38:06.757  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 11:38:06.780  1707  4193 I SystemUpdateService: active receiver: enabled
,09-07 11:38:06.784  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 11:38:06.788  1707  2458 I iu.UploadsManager: num queued entries: 0
,09-07 11:38:06.788  1707  2458 I iu.UploadsManager: num updated entries: 0
,09-07 11:38:06.792  1707  4193 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 11:38:06.799  1707  2458 I iu.SyncManager: NEXT; no task
,09-07 11:38:06.799  1707  4193 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 11:38:06.799  1707  4193 I SystemUpdateService: now status is 0 (complete)
09-07 11:38:06.800  1707  4193 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 11:38:06.800  1707  4193 I SystemUpdateService: file has been verified
,09-07 11:38:06.802  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 11:38:06.804  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 11:38:06.805  1707  4193 I SystemUpdateService: OTA package size = 12249756
,09-07 11:38:06.808  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 11:38:06.812  1707  4195 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 11:38:06.812  1707  4195 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 11:38:06.815  3944  3944 D SprintDMHelper: simOperator: 
09-07 11:38:06.815  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 11:38:06.816  1707  4195 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 11:38:06.820  1707  4193 I SystemUpdateService: showing system update notification
,09-07 11:38:06.830  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:38:06.832  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 11:38:06.843   874  4182 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-07 11:38:06.905  1501  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 11:38:06.905  1501  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 11:38:06.905  1501  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 11:38:06.905  1501  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 11:38:06.913  1707  1707 D SystemUpdateService: onDestroy
,09-07 11:38:06.927   874  4182 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 09:38:06 GMT], X-Android-Received-Millis=[1473241086926], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473241086895]}
,09-07 11:38:06.928   874  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 11:38:06.929   874  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-07 11:38:06.930   874  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 11:38:06.934   874  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 11:38:06.942  1707  4195 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-07 11:38:07.014  3913  4198 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 11:38:07.076  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:38:07.090  3815  4205 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-07 11:38:07.090  3815  4205 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 11:38:07.700   874  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-07 11:38:10.108  3815  4207 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-07 11:38:10.109  3815  4205 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-07 11:38:10.109  3815  4207 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-07 11:38:10.109  3815  4205 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 11:38:10.111  3815  4207 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:38:10.112  3815  4205 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:38:10.112  3815  4207 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:38:10.114  3815  4205 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:38:10.116  3815  4210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: IncomingSocketThread/Sender)
,09-07 11:38:10.116  3815  4207 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 11:38:10.119  3815  4211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: OutgoingSocketThread/Sender)
09-07 11:38:10.122  3815  4205 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 11:38:10.122  3815  4212 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 493, name: IncomingSocketThread/Receiver)
09-07 11:38:10.124  3815  4212 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 493, thread name: IncomingSocketThread/Receiver)
,09-07 11:38:10.124  3815  4212 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 11:38:10.125  3815  4212 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 493, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-07 11:38:10.125  3815  4213 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 494, name: OutgoingSocketThread/Receiver)
,09-07 11:38:10.127  3815  4213 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 494, thread name: OutgoingSocketThread/Receiver)
09-07 11:38:10.127  3815  4213 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 11:38:10.128  3815  4213 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 494, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 11:38:13.114  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 11:38:13.116  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 11:38:13.124  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f6d3ddc Bundle[{}]
,09-07 11:38:13.125  3815  3865 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 11:38:13.125  3815  3865 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 11:38:13.126  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 11:38:13.126  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 11:38:13.127  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 11:38:13.127  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 11:38:13.136  3815  4215 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 11:38:13.137  3815  4215 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 11:38:13.153  3815  4217 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-07 11:38:13.153  3815  4217 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 11:38:13.153  3815  4215 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-07 11:38:13.154  3815  4217 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:38:13.154  3815  4215 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 11:38:13.154  3815  4215 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 11:38:13.154  3815  4217 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:38:13.158  3815  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 505, name: IncomingSocketThread/Sender)
,09-07 11:38:13.158  3815  4217 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 11:38:13.158  3815  4215 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:38:13.161  3815  4221 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 506, name: OutgoingSocketThread/Sender)
,09-07 11:38:13.162  3815  4222 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 507, name: IncomingSocketThread/Receiver)
,09-07 11:38:13.163  3815  4222 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 507, thread name: IncomingSocketThread/Receiver)
,09-07 11:38:13.163  3815  4222 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-07 11:38:13.163  3815  4222 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 507, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-07 11:38:13.163  3815  4215 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 11:38:13.168  3815  4223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 508, name: OutgoingSocketThread/Receiver)
09-07 11:38:13.169  3815  4223 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 508, thread name: OutgoingSocketThread/Receiver)
,09-07 11:38:13.169  3815  4223 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-07 11:38:13.169  3815  4223 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 508, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 11:38:14.613   874  1306 D ConnectivityService: handlePromptUnvalidated 102
,09-07 11:38:16.164  3815  3865 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 517)
,09-07 11:38:16.166  3815  3865 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 11:38:16.167  3815  3865 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 518)
,09-07 11:38:16.172  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:38:16.173  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90134 added. We now have 3 listener(s)
,09-07 11:38:16.174  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 11:38:16.174  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 11:38:16.175  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 11:38:16.175  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 11:38:16.175  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b5d added. We now have 3 listener(s)
09-07 11:38:16.175  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 11:38:16.175  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 11:38:16.183  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:38:16.191  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:38:16.192  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:38:16.194  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:16.195  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 11:38:16.197  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:38:16.207  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 11:38:16.210  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:38:16.213  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:38:16.214  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:16.214  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 11:38:16.214  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 11:38:16.215  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90134 removed from the list
,09-07 11:38:16.215  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:16.215  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b5d removed from the list
09-07 11:38:16.216  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:38:16.216  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:16.216  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:16.218  3815  3865 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-07 11:38:16.219  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-07 11:38:16.219  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 11:38:16.219  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 11:38:16.219  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:38:16.219  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:38:16.221  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 11:38:16.222  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-07 11:38:16.222  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-07 11:38:16.224  3815  3865 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
,09-07 11:38:16.225  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 11:38:16.225  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:38:16.225  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:38:16.231  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 11:38:16.233  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 11:38:16.234  3815  3865 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 11:38:16.236  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 11:38:16.236  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:16.237  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:38:16.237  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 11:38:16.237  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 11:38:16.238  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:38:16.238  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90134 not in the list
,09-07 11:38:16.238  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:16.238  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:38:16.238  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:38:16.238  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 11:38:16.239  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:38:16.240  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:16.243  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:38:16.244  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b5d not in the list
,09-07 11:38:16.244  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:16.244  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:16.244  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:38:16.244  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:38:16.244  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:16.245  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:16.247  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 11:38:16.248  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:38:16.249  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:38:16.249  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 11:38:16.249  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:38:16.249  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:38:16.255  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 11:38:16.258  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 11:38:16.258  3815  3865 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:38:16.258  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 11:38:16.760  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:38:16.760  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 11:38:19.259  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 11:38:19.262  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:38:19.262  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:19.262  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 11:38:19.263  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90134 not in the list
09-07 11:38:19.263  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:19.263  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:38:19.264  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:38:19.264  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:38:19.265  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:38:19.267  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:19.271  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:38:19.272  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b5d not in the list
,09-07 11:38:19.272  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:19.272  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:38:19.272  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:19.272  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:38:19.273  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:38:19.272  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:19.275  3815  3865 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-07 11:38:19.276  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-07 11:38:19.280  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 11:38:19.280  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 11:38:19.280  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 11:38:19.281  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:38:19.283  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-07 11:38:19.285  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 11:38:19.286  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 11:38:19.287  3815  3865 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
,09-07 11:38:19.287  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 11:38:19.287  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:38:19.288  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:38:19.300  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 11:38:19.303  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 11:38:19.303  3815  3865 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 11:38:19.305  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 11:38:19.305  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:38:19.306  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 11:38:19.306  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 11:38:19.306  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 11:38:19.307  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90134 not in the list
09-07 11:38:19.307  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 11:38:19.307  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:38:19.307  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 11:38:19.307  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 11:38:19.308  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 11:38:19.308  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:38:19.309  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:19.312  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 11:38:19.312  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b5d not in the list
09-07 11:38:19.312  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:19.312  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:38:19.313  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 11:38:19.313  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:19.313  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 11:38:19.313  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 11:38:19.316  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:38:19.317  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:19.317  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:19.317  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90134 not in the list
09-07 11:38:19.317  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:38:19.317  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8b5d not in the list
09-07 11:38:19.317  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:38:19.317  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:38:19.317  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:38:19.318  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 11:38:19.318  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 11:38:19.318  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 11:38:19.318  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 11:38:19.319  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 11:38:19.319  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 11:38:19.327  3815  4224 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 536, name: My test thread name)
,09-07 11:38:19.814  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 11:38:21.325  3815  3865 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 536
09-07 11:38:21.326  3815  3865 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 536, name: My test thread name)
,09-07 11:38:21.332  3815  4225 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 537, name: My test thread name)
,09-07 11:38:21.333  3815  4225 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 537, thread name: My test thread name)
09-07 11:38:21.333  3815  4225 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 537, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-07 11:38:21.338  3815  3865 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 11:38:21.347  3815  4226 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 541, name: My test thread name)
,09-07 11:38:21.347  3815  4226 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 541, thread name: My test thread name): Test exception.
09-07 11:38:21.348  3815  4226 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 541, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-07 11:38:21.350  3815  3865 E com.test.thalitest.ThaliTestRunner: Proper state of WIFI is set when switched off
09-07 11:38:21.350  3815  3865 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-07 11:38:21.350  3815  3865 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner: Returns proper state of BT when switched on
09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-07 11:38:21.351  3815  3865 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should affect listening to advertisements only>
,09-07 11:38:21.352  3815  3865 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 11:38:21.352  3815  3865 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
09-07 11:38:21.352  3815  3865 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 77
09-07 11:38:21.353  3815  3865 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  5
09-07 11:38:21.353  3815  3865 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-07 11:38:21.353  3815  3865 D com.test.thalitest.ThaliTestRunner: Total duration: 66106 ms
,09-07 11:38:21.358  3815  3865 I jxcore-log: Total number of executed tests:  82
09-07 11:38:21.358  3815  3865 I jxcore-log: 
09-07 11:38:21.359  3815  3865 I jxcore-log: Number of passed tests:  77
09-07 11:38:21.359  3815  3865 I jxcore-log: 
,09-07 11:38:21.360  3815  3865 I jxcore-log: Number of failed tests:  5
09-07 11:38:21.360  3815  3865 I jxcore-log: 
,09-07 11:38:21.362  3815  3865 I jxcore-log: Number of ignored tests:  0
09-07 11:38:21.362  3815  3865 I jxcore-log: 
09-07 11:38:21.363  3815  3865 I jxcore-log: Total duration:  66106
09-07 11:38:21.363  3815  3865 I jxcore-log: 
,09-07 11:38:21.368  3815  3865 I jxcore-log: Failed to execute UT.
09-07 11:38:21.368  3815  3865 I jxcore-log: 
,09-07 11:38:21.369  3815  3865 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-07 11:38:21.369  3815  3865 I jxcore-log: 
,09-07 11:38:21.380  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.380  3815  3865 I jxcore-log: 
09-07 11:38:21.385  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.385  3815  3865 I jxcore-log: 
09-07 11:38:21.386  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.386  3815  3865 I jxcore-log: 
09-07 11:38:21.387  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.387  3815  3865 I jxcore-log: 
,09-07 11:38:21.388  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.388  3815  3865 I jxcore-log: 
,09-07 11:38:21.391  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.391  3815  3865 I jxcore-log: 
,09-07 11:38:21.392  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.392  3815  3865 I jxcore-log: 
09-07 11:38:21.393  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.393  3815  3865 I jxcore-log: 
,09-07 11:38:21.394  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.394  3815  3865 I jxcore-log: 
,09-07 11:38:21.395  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 11:38:21.395  3815  3865 I jxcore-log: 
09-07 11:38:21.396  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.396  3815  3865 I jxcore-log: 
09-07 11:38:21.397  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.397  3815  3865 I jxcore-log: 
,09-07 11:38:21.397  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.397  3815  3865 I jxcore-log: 
09-07 11:38:21.398  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.398  3815  3865 I jxcore-log: 
,09-07 11:38:21.399  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.399  3815  3865 I jxcore-log: 
09-07 11:38:21.400  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.400  3815  3865 I jxcore-log: 
,09-07 11:38:21.401  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.401  3815  3865 I jxcore-log: 
,09-07 11:38:21.402  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.402  3815  3865 I jxcore-log: 
,09-07 11:38:21.403  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.403  3815  3865 I jxcore-log: 
09-07 11:38:21.404  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.404  3815  3865 I jxcore-log: 
,09-07 11:38:21.404  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.404  3815  3865 I jxcore-log: 
09-07 11:38:21.405  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.405  3815  3865 I jxcore-log: 
,09-07 11:38:21.406  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.406  3815  3865 I jxcore-log: 
09-07 11:38:21.407  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.407  3815  3865 I jxcore-log: 
,09-07 11:38:21.407  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.407  3815  3865 I jxcore-log: 
,09-07 11:38:21.408  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 11:38:21.408  3815  3865 I jxcore-log: 
,09-07 11:38:21.409  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.409  3815  3865 I jxcore-log: 
,09-07 11:38:21.410  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 11:38:21.410  3815  3865 I jxcore-log: 
09-07 11:38:21.411  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.411  3815  3865 I jxcore-log: 
,09-07 11:38:21.411  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.411  3815  3865 I jxcore-log: 
,09-07 11:38:21.412  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:38:21.412  3815  3865 I jxcore-log: 
,09-07 11:38:21.413  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.413  3815  3865 I jxcore-log: 
09-07 11:38:21.413  3815  4224 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 536, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
09-07 11:38:21.414  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 11:38:21.414  3815  3865 I jxcore-log: 
,09-07 11:38:22.012  4227  4227 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-07 11:38:22.017  4227  4227 D AndroidRuntime: CheckJNI is OFF
,09-07 11:38:22.060  4227  4227 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-07 11:38:22.109  4227  4227 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 11:38:22.133  4227  4227 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 11:38:22.145   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-07 11:38:22.145   874   887 I ActivityManager: Killing 3815:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-07 11:38:22.259   874  1305 D WifiService: Client connection lost with reason: 4
,09-07 11:38:22.259   874  1370 I WindowState: WIN DEATH: Window{b577b44 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 11:38:22.260   874  1981 D GraphicsStats: Buffer count: 2
,09-07 11:38:22.312   874   899 W PackageSettings: Skipping PackageSetting{32ad33d com.example.hello/10273} due to missing metadata
,09-07 11:38:22.348   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-07 11:38:22.348   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-07 11:38:22.350   874   899 I art     : Starting a blocking GC Explicit
,09-07 11:38:22.353   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-07 11:38:22.353   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 11:38:22.353   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.353   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.353   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 11:38:22.353   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-07 11:38:22.355   874   887 I ActivityManager:   Force finishing activity ActivityRecord{a58ce95 u0 com.test.thalitest/.MainActivity t4}
,09-07 11:38:22.375   874  1981 W ActivityManager: Spurious death for ProcessRecord{f7ae191 0:com.test.thalitest/u0a0}, curProc for 3815: null
,09-07 11:38:22.392   874   899 I art     : Explicit concurrent mark sweep GC freed 17991(1160KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 839us total 41.363ms
,09-07 11:38:22.430   874   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 11:38:22.432  4227  4227 I art     : System.exit called, status: 0
,09-07 11:38:22.432  4227  4227 I AndroidRuntime: VM exiting with result code 0.
,09-07 11:38:22.439   874   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-07 11:38:22.458   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-07 11:38:22.469   874  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 11:38:22.469  1856  2275 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 11:38:22.471  1886  1886 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-07 11:38:22.473  3658  3658 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-07 11:38:22.478  1886  4239 I Keyboard.Facilitator.DecoderInitializer: run()
,09-07 11:38:22.480  1886  4239 I Decoder : createOrResetDecoder
,09-07 11:38:22.518  1980  1980 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-07 11:38:22.525   874  2033 I ActivityManager: Start proc 4241:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 11:38:22.542  1501  1501 I ConfigService: onCreate
,09-07 11:38:22.558  4241  4241 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 11:38:22.562  1501  4253 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 11:38:22.562  1501  4253 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 11:38:22.562  1501  4253 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-07 11:38:22.574  1501  4253 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-07 11:38:22.581   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 11:38:22.586  1886  4239 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-07 11:38:22.587   874  2029 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3815 uid 10000
09-07 11:38:22.588  1886  1886 I Keyboard.Facilitator: onFinishInput()
,09-07 11:38:22.621  4241  4241 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 11:38:22.623  1997  2126 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-07 11:38:22.623   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-07 11:38:22.624   874   886 E PackageManager: Failed to write settings, restoring backup
09-07 11:38:22.624   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 11:38:22.624   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 11:38:22.624   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 11:38:22.624   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 11:38:22.624   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 11:38:22.624   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.624   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.624   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 11:38:22.628   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-07 11:38:22.628   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 11:38:22.628   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:38:22.628   874   887 E DropBoxManagerService: 	... 13 more
,09-07 11:38:22.635   874  2014 I ActivityManager: Start proc 4257:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-07 11:38:22.635  1997  2126 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 11:38:22.635  1997  2126 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1997
09-07 11:38:22.635  1997  2126 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.635  1997  2126 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 11:38:22.637   874  2002 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 11:38:22.640   874  4263 E DropBoxManagerService: Can't write: system_app_crash
09-07 11:38:22.640   874  4263 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:38:22.640   874  4263 E DropBoxManagerService: 	... 5 more
,09-07 11:38:22.653  1997  2126 I Process : Sending signal. PID: 1997 SIG: 9
,09-07 11:38:22.683  1886  4239 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-07 11:38:22.684  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 11:38:22.685  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 11:38:22.686  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 11:38:22.686  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 11:38:22.687  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 11:38:22.687  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 11:38:22.688  1886  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-07 11:38:22.688  1886  4239 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 11:38:22.691   874  1684 I ActivityManager: Start proc 4272:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-07 11:38:22.709  1886  4239 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-07 11:38:22.710  1886  4239 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-07 11:38:22.710  1886  4239 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-07 11:38:22.711  1886  4239 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-07 11:38:22.715  4241  4271 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 11:38:22.731  4272  4272 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-07 11:38:22.757   874  1683 D GraphicsStats: Buffer count: 1
,09-07 11:38:22.757   874  2116 I WindowState: WIN DEATH: Window{20373d4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-07 11:38:22.769   874  1370 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1997) has died
,09-07 11:38:22.770   874  1370 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-07 11:38:22.772   874  1370 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-07 11:38:22.781  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-07 11:38:22.782  1501  1501 D AndroidRuntime: Shutting down VM
,09-07 11:38:22.783  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
09-07 11:38:22.783  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
09-07 11:38:22.783  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 11:38:22.783  1501  1501 E AndroidRuntime: 	... 8 more
,09-07 11:38:22.789   874   887 I ActivityManager: Start proc 4290:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 11:38:22.794  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
,09-07 11:38:22.795   874  4296 E DropBoxManagerService: Can't write: system_app_crash
09-07 11:38:22.795   874  4296 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:38:22.795   874  4296 E DropBoxManagerService: 	... 5 more
,09-07 11:38:22.828   874  2002 I ActivityManager: Killing 3718:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 11:38:22.838  4290  4290 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:38:22.838  4290  4290 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:38:22.839  4290  4290 D AndroidRuntime: Shutting down VM
,09-07 11:38:22.844  4241  4255 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.844  4241  4255 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.844  4241  4255 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 11:38:22.862  4241  4255 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-07 11:38:22.866  4241  4271 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.866  4241  4271 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 11:38:22.867  4241  4271 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 11:38:22.867  4241  4271 E AndroidRuntime: Process: android.process.acore, PID: 4241
09-07 11:38:22.867  4241  4271 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.867  4241  4271 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 11:38:22.868  4241  4255 I Process : Sending signal. PID: 4241 SIG: 9
,09-07 11:38:22.871   874  1305 D WifiService: Client connection lost with reason: 4
,09-07 11:38:22.873  1707  4288 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@5368b91
,09-07 11:38:22.878   874   885 I ActivityManager: Process com.google.process.gapps (pid 1501) early provider death
,09-07 11:38:22.879   874   885 I ActivityManager: Process com.google.process.gapps (pid 1501) has died
,09-07 11:38:22.880   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-07 11:38:22.880   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-07 11:38:22.880   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
,09-07 11:38:22.895   874  1683 I ActivityManager: Start proc 4303:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
09-07 11:38:22.896   874  2116 W ActivityManager: Spurious death for ProcessRecord{a4984c8 0:com.google.process.gapps/u0a11}, curProc for 1501: null
09-07 11:38:22.899   278   278 E lowmemorykiller: Error writing /proc/4241/oom_score_adj; errno=22
09-07 11:38:22.900   278   278 E lowmemorykiller: Error writing /proc/4241/oom_score_adj; errno=22
,09-07 11:38:22.904  4290  4290 E AndroidRuntime: FATAL EXCEPTION: main
09-07 11:38:22.904  4290  4290 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4290
09-07 11:38:22.904  4290  4290 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 11:38:22.904  4290  4290 E AndroidRuntime: 	... 10 more
,09-07 11:38:22.907   874  1370 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 11:38:22.907   874  4315 E DropBoxManagerService: Can't write: system_app_crash
09-07 11:38:22.907   874  4315 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:38:22.907   874  4315 E DropBoxManagerService: 	... 5 more
09-07 11:38:22.908  4290  4290 I Process : Sending signal. PID: 4290 SIG: 9
,09-07 11:38:22.909   874  4316 E DropBoxManagerService: Can't write: system_app_crash
09-07 11:38:22.909   874  4316 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 11:38:22.909   874  4316 E DropBoxManagerService: 	... 5 more
09-07 11:38:22.912  1707  1707 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-07 11:38:22.931   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
