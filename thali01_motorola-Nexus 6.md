#### Test 83627337e0b549f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-14 09:27:57.993  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:27:58.004  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-14 09:27:58.005  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-14 09:27:58.030  1501  2419 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-14 09:27:58.030  1501  2419 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-14 09:27:58.030  1501  2419 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 09:27:58.030  1501  2419 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-14 09:27:58.051  3522  3522 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-14 09:27:58.051  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-14 09:27:58.052  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-14 09:27:58.636  3770  3770 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 09:27:58.640  3770  3770 D AndroidRuntime: CheckJNI is OFF
09-14 09:27:58.677  3770  3770 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 09:27:58.721  3770  3770 I Radio-JNI: register_android_hardware_Radio DONE
09-14 09:27:58.741  3770  3770 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-14 09:27:58.745   872  1392 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-14 09:27:58.788  2054  2066 W SearchService: Abort, client detached.
09-14 09:27:58.800  2054  2361 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@227d02a
09-14 09:27:58.800  2054  2054 I HotwordDetector: Closing mic
09-14 09:27:58.804  3770  3770 D AndroidRuntime: Shutting down VM
09-14 09:27:58.816   872  1996 I ActivityManager: Start proc 3780:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-14 09:27:58.870   375  2371 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-14 09:27:58.871   375  2371 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-14 09:27:58.877   375  1281 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-14 09:27:58.878  2054  2368 I MicroRecognitionRnrImpl: Detection finished
09-14 09:27:58.879  2054  2364 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-14 09:27:58.891  3780  3780 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-14 09:27:58.917  3780  3780 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-14 09:27:58.924  3780  3780 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9764-9766)
09-14 09:27:58.925  3780  3780 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 09:27:58.937  3780  3780 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c9d970f}
09-14 09:27:58.938  3780  3780 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 09:27:58.938  3780  3780 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-14 09:27:58.943  3780  3780 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-14 09:27:58.944  3780  3780 E SysUtils: ApplicationContext is null in ApplicationStatus
09-14 09:27:58.957  3780  3780 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-14 09:27:58.966  3780  3780 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 09:27:58.966  3780  3780 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 09:27:58.966  3780  3780 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-14 09:27:58.966  3780  3780 I Adreno  : Build Date                       : 10/20/15
09-14 09:27:58.966  3780  3780 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 09:27:58.966  3780  3780 I Adreno  : Local Branch                     : M14
09-14 09:27:58.966  3780  3780 I Adreno  : Remote Branch                    : 
09-14 09:27:58.966  3780  3780 I Adreno  : Remote Branch                    : 
09-14 09:27:58.966  3780  3780 I Adreno  : Reconstruct Branch               : 
,09-14 09:27:59.049   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f24c7d:true
,09-14 09:27:59.103  3780  3780 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-14 09:27:59.119  3780  3780 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-14 09:27:59.233  3780  3818 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 09:27:59.246  3780  3805 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-14 09:27:59.292  3780  3818 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 09:27:59.344   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +540ms
,09-14 09:27:59.348  1895  1895 I Keyboard.Facilitator: onFinishInput()
,09-14 09:27:59.434  3780  3780 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3780
,09-14 09:27:59.610  3780  3780 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 09:27:59.623   872  2214 I ActivityManager: Killing 3005:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-14 09:27:59.677   872  2214 I ActivityManager: Killing 3105:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-14 09:27:59.793  3780  3820 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1697777360
,09-14 09:27:59.800  3780  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 09:27:59.800  3780  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 09:27:59.800  3780  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 09:27:59.800  3780  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 09:27:59.800  3780  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-14 09:27:59.800  3780  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@430c92 added. We now have 1 listener(s)
,09-14 09:27:59.803  3780  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-14 09:27:59.805  3780  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:27:59.806  3780  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:27:59.806  3780  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-14 09:27:59.811  3780  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f14319 added. We now have 1 listener(s)
09-14 09:27:59.811  3780  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 09:27:59.817   872  1311 D WifiService: New client listening to asynchronous messages
,09-14 09:27:59.820  3780  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 09:27:59.820  3780  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-14 09:27:59.821  3780  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-14 09:27:59.821  3780  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-14 09:27:59.821  3780  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-14 09:27:59.826  3780  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:27:59.827  3780  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-14 09:27:59.835  3780  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:27:59.836  3780  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:27:59.836  3780  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 09:27:59.836  3780  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:27:59.837  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:27:59.842  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:27:59.844  3780  3820 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 09:27:59.873  3780  3780 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 09:28:00.698  3780  3829 W jxcore-log: Initializing JXcore engine
,09-14 09:28:00.699  3780  3829 W jxcore-log: JXcore engine is ready
,09-14 09:28:00.736  3829  3829 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-14 09:28:00.736  3829  3829 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12674]" dev="sockfs" ino=12674 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-14 09:28:00.736  3829  3829 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-14 09:28:00.736  3829  3829 W Thread-321: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26800]" dev="sockfs" ino=26800 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 09:28:00.751  3780  3829 W jxcore-log: Starting JXcore engine
,09-14 09:28:00.834  3780  3829 W jxcore-log: Platform android
09-14 09:28:00.834  3780  3829 W jxcore-log: 
,09-14 09:28:00.834  3780  3829 W jxcore-log: Process ARCH arm
09-14 09:28:00.834  3780  3829 W jxcore-log: 
,09-14 09:28:01.126  3780  3829 I jxcore-log: JXcore Cordova bridge is ready!
09-14 09:28:01.126  3780  3829 I jxcore-log: 
,09-14 09:28:01.126  3780  3829 W jxcore-log: JXcore engine is started
,09-14 09:28:01.135  3780  3820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-14 09:28:01.139  3780  3780 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 09:28:02.404   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 09:28:02.678   872  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-14 09:28:05.429   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 09:28:07.905  3587  3838 I BooksSync: Starting books sync for 61035162, extras: ade
,09-14 09:28:07.942  3587  3839 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-14 09:28:07.956  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:07.959  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:07.991  1501  2419 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 09:28:07.991  1501  2419 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-14 09:28:07.991  1501  2419 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 09:28:07.991  1501  2419 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 09:28:08.033  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:08.036  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:08.078  1501  2289 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 09:28:08.078  1501  2289 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-14 09:28:08.078  1501  2289 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 09:28:08.079  1501  2289 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 09:28:08.112  3587  3839 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-14 09:28:08.114  3587  3838 E BooksSync: Soft error
09-14 09:28:08.114  3587  3838 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 09:28:08.114  3587  3838 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 09:28:08.117  3587  3838 E BooksSync: Sync error
09-14 09:28:08.117  3587  3838 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 09:28:08.117  3587  3838 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 09:28:08.117  3587  3838 I BooksSync: Finished books sync
,09-14 09:28:08.128   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128673, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-14 09:28:08.459   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 09:28:11.189  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 09:28:11.189  3780  3829 I jxcore-log: 
,09-14 09:28:11.192  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 09:28:11.192  3780  3829 I jxcore-log: 
,09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:11.205  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:11.209  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:11.211  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 09:28:11.211  3780  3829 I jxcore-log: 
,09-14 09:28:11.213  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 09:28:11.213  3780  3829 I jxcore-log: 
,09-14 09:28:11.719  3780  3829 I jxcore-log: Unit Test app is loaded
09-14 09:28:11.719  3780  3829 I jxcore-log: 
,09-14 09:28:11.725  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:28:11.725  3780  3829 I jxcore-log: 
,09-14 09:28:11.731  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 09:28:11.731  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efc6fdf added. We now have 2 listener(s)
09-14 09:28:11.732  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:28:11.732  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:28:11.732  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:28:11.733  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:28:11.733  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10bc42c added. We now have 2 listener(s)
09-14 09:28:11.733  3780  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:28:11.734  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 09:28:11.738  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:11.747  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:11.750  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:11.750  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:28:11.752  3780  3829 D ExecuteNativeTests: Running unit tests
,09-14 09:28:11.753  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:11.762  3780  3829 D BluetoothAdapter: enable(): BT is already enabled..!
,09-14 09:28:11.763   872  2008 D WifiService: setWifiEnabled: true pid=3780, uid=10000
09-14 09:28:11.763   872  2008 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:11.765  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:11.765  3780  3780 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-14 09:28:11.767  3780  3829 I System.out: Running UT
,09-14 09:28:14.531   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 09:28:18.422  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:18.439  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:18.446  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:18.514  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-14 09:28:18.514  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-14 09:28:18.514  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 09:28:18.515  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 09:28:18.560  3522  3522 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-14 09:28:18.561  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-14 09:28:18.562  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.,
,09-14 09:28:21.861  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 09:28:21.861  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a added. We now have 3 listener(s)
,09-14 09:28:21.862  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:28:21.862  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 09:28:21.862  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:28:21.862  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:28:21.862  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb added. We now have 3 listener(s)
09-14 09:28:21.862  3780  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:28:21.863  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 09:28:21.866  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:21.890  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:21.894  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:21.894  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:28:21.899  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:21.901  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:21.902  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-14 09:28:21.902  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 09:28:21.902  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 09:28:21.902  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 09:28:21.904  3780  3829 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-14 09:28:21.904  3780  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-14 09:28:21.905  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 09:28:21.905  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-14 09:28:21.905  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:28:21.905  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:28:21.906  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:21.906  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:21.906  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:28:21.906  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 09:28:21.906  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a removed from the list
09-14 09:28:21.906  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:21.906  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb removed from the list
09-14 09:28:21.906  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:21.906  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:21.910  3780  3829 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-14 09:28:21.911  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:21.911  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:21.911  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:21.911  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:21.911  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:21.911  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:21.911  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:21.911  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:21.911  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:21.928  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-14 09:28:21.928  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-14 09:28:21.929  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 09:28:21.930  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-14 09:28:21.931  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 09:28:21.931  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:21.931  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:21.931  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:21.931  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
,09-14 09:28:21.931  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:21.931  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:21.931  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:21.931  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:21.931  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:21.932  3780  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-14 09:28:21.934  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:21.939  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:28:21.941  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:21.941  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:28:21.942  3780  3829 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-14 09:28:21.942  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-14 09:28:21.942  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:21.942  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 09:28:21.942  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:28:21.942  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:21.944  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:21.946  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 09:28:21.946  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 09:28:21.946  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:21.946  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:28:21.947  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:21.947  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 09:28:21.952  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:21.956  3780  3846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:21.957  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 09:28:21.957  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 09:28:21.958  3780  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 09:28:21.959  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:28:21.959  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-14 09:28:21.963  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 09:28:21.965  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 09:28:21.965  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:28:21.969  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-14 09:28:21.969  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:28:21.969  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-14 09:28:21.970  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:21.970  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:21.970  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
09-14 09:28:21.971  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:21.979  2665  2677 D BtGatt.GattService: registerClient() - UUID=6c0046dc-2702-4bc7-a6d0-29c00df6eeb0
,09-14 09:28:21.980  2665  2700 D BtGatt.GattService: onClientRegistered() - UUID=6c0046dc-2702-4bc7-a6d0-29c00df6eeb0, clientIf=5
,09-14 09:28:21.981  3780  3790 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 09:28:21.987  2665  2702 D BtGatt.AdvertiseManager: message : 0
,09-14 09:28:21.992  2665  2702 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 09:28:22.022  2665  2700 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 09:28:22.034  2665  2700 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 09:28:22.036  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-14 09:28:22.036  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 09:28:22.038  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:22.042  3780  3829 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 09:28:22.042  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:22.043  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 09:28:22.043  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-14 09:28:22.043  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 09:28:22.044  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-14 09:28:22.044  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 09:28:22.052  3780  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:22.052  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:22.548  3780  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 09:28:22.549  3780  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-14 09:28:22.549  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-14 09:28:22.550  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 09:28:22.550  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:28:22.550  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-14 09:28:22.551  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 09:28:22.552  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 09:28:22.552  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:22.553  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-14 09:28:22.552  3780  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 09:28:22.554  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 09:28:22.554  3780  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 09:28:22.554  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-14 09:28:22.554  3780  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 09:28:22.554  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 09:28:22.555  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 09:28:22.556  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 09:28:22.559  3780  3829 D BluetoothAdapter: STATE_ON
09-14 09:28:22.560  3780  3829 D BluetoothLeScanner: could not find callback wrapper
09-14 09:28:22.560  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-14 09:28:22.561  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-14 09:28:22.564  2665  2702 D BtGatt.AdvertiseManager: message : 1
09-14 09:28:22.566  2665  2702 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 09:28:22.586  2665  2700 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-14 09:28:22.587  2665  2700 D BtGatt.GattService: Client app is not null!
,09-14 09:28:22.589  2665  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 09:28:22.590  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 09:28:22.590  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-14 09:28:22.590  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-14 09:28:22.590  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 09:28:22.591  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-14 09:28:22.593  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 09:28:22.593  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 09:28:22.594  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 09:28:22.596  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:22.600  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 09:28:22.601  3780  3780 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 09:28:22.602  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-14 09:28:22.603  3780  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 09:28:22.603  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 09:28:22.603  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 09:28:22.604  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 09:28:22.608  3780  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-14 09:28:22.608  3780  3829 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-14 09:28:22.608  3780  3829 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-14 09:28:22.609  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-14 09:28:22.609  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:22.609  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 09:28:22.610  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:28:22.610  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:22.611  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:22.612  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-14 09:28:22.612  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-14 09:28:22.613  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-14 09:28:22.613  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:22.613  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:28:22.613  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:22.613  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 09:28:22.617  3780  3849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:22.620  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 09:28:22.620  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 09:28:22.621  3780  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-14 09:28:22.628  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 09:28:22.629  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 09:28:22.629  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:28:22.634  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-14 09:28:22.634  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:28:22.635  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-14 09:28:22.635  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,09-14 09:28:22.636  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:22.636  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-14 09:28:22.637  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:22.642  2665  2778 D BtGatt.GattService: registerClient() - UUID=7049e743-703a-473b-b852-ffc08deef851
09-14 09:28:22.642  2665  2700 D BtGatt.GattService: onClientRegistered() - UUID=7049e743-703a-473b-b852-ffc08deef851, clientIf=5
,09-14 09:28:22.643  3780  3792 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 09:28:22.644  2665  2702 D BtGatt.AdvertiseManager: message : 0
09-14 09:28:22.649  2665  2702 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 09:28:22.682  2665  2700 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 09:28:22.706  2665  2700 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 09:28:22.709  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-14 09:28:22.709  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 09:28:22.714  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:22.718  3780  3829 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 09:28:22.718  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-14 09:28:22.719  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-14 09:28:22.719  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 09:28:22.720  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-14 09:28:22.720  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-14 09:28:22.720  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 09:28:22.735  3780  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:22.735  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:23.227  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:23.227  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-14 09:28:23.227  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:28:23.228  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-14 09:28:23.228  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 09:28:23.229  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:23.228  3780  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 09:28:23.229  3780  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-14 09:28:23.230  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:23.230  3780  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-14 09:28:23.230  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:23.230  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 09:28:23.237  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 09:28:23.240  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 09:28:23.240  3780  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 09:28:23.240  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 09:28:23.240  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-14 09:28:23.240  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 09:28:23.243  3780  3829 D BluetoothAdapter: STATE_ON
09-14 09:28:23.244  3780  3829 D BluetoothLeScanner: could not find callback wrapper
,09-14 09:28:23.244  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 09:28:23.244  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-14 09:28:23.247  2665  2702 D BtGatt.AdvertiseManager: message : 1
,09-14 09:28:23.248  2665  2702 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 09:28:23.257  2665  2700 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-14 09:28:23.257  2665  2700 D BtGatt.GattService: Client app is not null!
,09-14 09:28:23.259  2665  2788 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 09:28:23.262  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 09:28:23.262  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-14 09:28:23.262  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-14 09:28:23.263  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 09:28:23.263  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-14 09:28:23.266  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 09:28:23.266  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 09:28:23.267  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 09:28:23.268  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:23.271  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 09:28:23.272  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 09:28:23.272  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 09:28:23.273  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:23.273  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:23.273  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:23.276  3780  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-14 09:28:23.282  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:23.294  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:23.300  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:23.300  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:28:23.302  3780  3829 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-14 09:28:23.302  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-14 09:28:23.302  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-14 09:28:23.302  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 09:28:23.302  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:28:23.302  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:23.303  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:23.305  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-14 09:28:23.305  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 09:28:23.305  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:23.305  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:28:23.305  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:23.306  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:28:23.306  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:23.318  3780  3851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:23.321  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:28:23.322  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-14 09:28:23.323  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 09:28:23.323  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 09:28:23.324  3780  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-14 09:28:23.328  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 09:28:23.329  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 09:28:23.329  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:28:23.334  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-14 09:28:23.334  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 09:28:23.334  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-14 09:28:23.334  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:23.334  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:23.335  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-14 09:28:23.336  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:23.339  2665  2778 D BtGatt.GattService: registerClient() - UUID=dc349233-9bc4-42f9-8404-6ad9f7210d57
09-14 09:28:23.340  2665  2700 D BtGatt.GattService: onClientRegistered() - UUID=dc349233-9bc4-42f9-8404-6ad9f7210d57, clientIf=5
,09-14 09:28:23.340  3780  3790 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 09:28:23.343  2665  2702 D BtGatt.AdvertiseManager: message : 0
,09-14 09:28:23.349  2665  2702 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 09:28:23.387  2665  2700 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 09:28:23.410  2665  2700 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 09:28:23.412  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-14 09:28:23.413  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 09:28:23.422  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:23.426  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-14 09:28:23.427  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-14 09:28:23.428  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-14 09:28:23.428  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 09:28:23.428  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 09:28:23.428  3780  3829 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 09:28:23.429  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 09:28:23.440  3780  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:23.441  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:23.619   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 09:28:23.934  3780  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 09:28:23.935  3780  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-14 09:28:23.935  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-14 09:28:23.936  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 09:28:23.936  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:28:23.936  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-14 09:28:23.936  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-14 09:28:23.939  3780  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-14 09:28:23.939  3780  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 09:28:23.939  3780  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-14 09:28:23.939  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 09:28:23.940  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:23.940  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 09:28:23.941  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 09:28:23.942  3780  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 09:28:23.942  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 09:28:23.942  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 09:28:23.942  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-14 09:28:23.942  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 09:28:23.946  3780  3829 D BluetoothAdapter: STATE_ON
09-14 09:28:23.947  3780  3829 D BluetoothLeScanner: could not find callback wrapper
09-14 09:28:23.948  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 09:28:23.948  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-14 09:28:23.952  2665  2702 D BtGatt.AdvertiseManager: message : 1
09-14 09:28:23.953  2665  2702 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 09:28:23.971  2665  2700 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-14 09:28:23.971  2665  2700 D BtGatt.GattService: Client app is not null!
,09-14 09:28:23.973  2665  2677 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 09:28:23.973  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 09:28:23.974  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-14 09:28:23.974  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 09:28:23.974  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-14 09:28:23.974  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-14 09:28:23.975  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-14 09:28:23.976  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 09:28:23.976  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:28:23.976  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:23.979  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 09:28:23.979  3780  3780 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 09:28:23.980  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-14 09:28:23.980  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 09:28:23.981  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:23.981  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 09:28:23.981  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:23.982  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-14 09:28:23.982  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
,09-14 09:28:23.982  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 09:28:23.982  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:23.984  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
,09-14 09:28:23.984  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:23.984  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:23.985  3780  3829 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-14 09:28:23.986  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:23.986  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:23.986  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:23.986  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:23.986  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:23.986  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
,09-14 09:28:23.986  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:23.986  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:23.986  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:23.987  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-14 09:28:23.987  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:23.988  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:23.988  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:23.988  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:23.988  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:23.988  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
,09-14 09:28:23.988  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:23.988  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:23.988  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-14 09:28:23.989  3780  3829 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-14 09:28:23.989  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:23.989  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:23.989  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:23.989  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list,
09-14 09:28:23.989  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:23.989  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:23.989  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:23.989  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:23.990  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:23.990  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-14 09:28:23.990  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:23.990  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:23.990  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:23.991  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
,09-14 09:28:23.991  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:23.991  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
,09-14 09:28:23.991  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:23.991  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:23.991  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:23.992  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-14 09:28:23.994  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 09:28:23.994  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:28:23.994  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 09:28:23.994  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:28:23.994  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-14 09:28:23.994  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 09:28:23.995  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:28:23.995  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 09:28:23.995  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:23.995  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:23.995  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:23.995  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
,09-14 09:28:23.995  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:23.995  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
,09-14 09:28:23.995  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:23.995  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:23.995  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:23.996  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-14 09:28:23.996  3780  3829 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-14 09:28:23.997  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-14 09:28:24.000  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-14 09:28:24.001  3780  3829 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-14 09:28:24.001  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-14 09:28:24.002  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 09:28:24.003  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 09:28:24.004  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-14 09:28:24.004  3780  3829 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 09:28:24.005  3780  3829 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-14 09:28:24.005  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:28:24.005  3780  3829 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 09:28:24.005  3780  3829 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-14 09:28:24.005  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:28:24.005  3780  3829 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 09:28:24.005  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-14 09:28:24.010  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-14 09:28:24.011  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-14 09:28:24.011  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-14 09:28:24.012  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-14 09:28:24.012  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-14 09:28:24.012  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-14 09:28:24.012  3780  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 09:28:24.012  3780  3829 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-14 09:28:24.014  3780  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 422)
09-14 09:28:24.015  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.015  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.015  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.016  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-14 09:28:24.017  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.017  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.018  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.018  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.018  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.018  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.018  3780  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:28:24.020  3780  3829 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-14 09:28:24.021  3780  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 422
09-14 09:28:24.021  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.021  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.021  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.021  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.022  3780  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 422)
09-14 09:28:24.022  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.023  3780  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 422)
09-14 09:28:24.023  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.023  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.023  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.023  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.024  3780  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-14 09:28:24.024  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.024  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.024  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.024  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.024  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.024  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.024  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.024  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.024  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.022  3780  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 422)
09-14 09:28:24.025  3780  3829 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-14 09:28:24.025  3780  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-14 09:28:24.025  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 09:28:24.025  3780  3829 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-14 09:28:24.025  3780  3829 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 09:28:24.025  3780  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-14 09:28:24.026  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 09:28:24.026  3780  3829 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-14 09:28:24.026  3780  3829 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 09:28:24.026  3780  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 09:28:24.026  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 09:28:24.026  3780  3829 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-14 09:28:24.026  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.026  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.026  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.026  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.026  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.026  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.026  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.026  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.026  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.027  3780  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-14 09:28:24.029  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:24.035  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:28:24.040  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:24.040  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 09:28:24.040  3780  3829 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-14 09:28:24.041  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-14 09:28:24.041  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:24.041  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 09:28:24.041  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:28:24.041  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:24.043  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:28:24.044  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:28:24.046  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:24.047  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 09:28:24.047  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 09:28:24.047  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 09:28:24.047  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:24.047  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:28:24.047  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:24.048  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:28:24.050  3780  3857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:28:24.055  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 09:28:24.056  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 09:28:24.056  3780  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 09:28:24.065  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 09:28:24.066  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 09:28:24.067  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 09:28:24.071  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 09:28:24.072  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 09:28:24.072  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
,09-14 09:28:24.073  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:24.073  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:24.073  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-14 09:28:24.075  3780  3829 D BluetoothAdapter: STATE_ON
09-14 09:28:24.080  2665  2788 D BtGatt.GattService: registerClient() - UUID=854db003-3f94-4f16-bc05-5d97521fafa2
09-14 09:28:24.080  2665  2700 D BtGatt.GattService: onClientRegistered() - UUID=854db003-3f94-4f16-bc05-5d97521fafa2, clientIf=5
09-14 09:28:24.080  3780  3790 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-14 09:28:24.082  2665  2702 D BtGatt.AdvertiseManager: message : 0
09-14 09:28:24.091  2665  2702 D BtGatt.AdvertiseManager: starting multi advertising
09-14 09:28:24.111  2665  2700 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 09:28:24.117  2665  2700 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 09:28:24.117  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-14 09:28:24.118  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 09:28:24.123  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:24.125  3780  3829 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 09:28:24.125  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:24.126  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 09:28:24.126  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-14 09:28:24.126  3780  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 09:28:24.126  3780  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 09:28:24.126  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 09:28:24.128  3780  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-14 09:28:24.128  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:24.630  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-14 09:28:24.630  3780  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 09:28:24.630  3780  3780 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 09:28:24.631  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.631  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:28:24.631  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:28:24.632  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 09:28:24.632  3780  3780 D AndroidRuntime: Shutting down VM
09-14 09:28:24.632  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 09:28:24.633  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:24.633  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.634  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:24.634  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 09:28:24.634  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
--------- beginning of crash
09-14 09:28:24.634  3780  3780 E AndroidRuntime: FATAL EXCEPTION: main
09-14 09:28:24.634  3780  3780 E AndroidRuntime: Process: com.test.thalitest, PID: 3780
09-14 09:28:24.634  3780  3780 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper$2.onFinish(ConnectionHelper.java:487)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at android.os.CountDownTimer$1.handleMessage(CountDownTimer.java:127)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 09:28:24.634  3780  3780 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 09:28:24.634  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 09:28:24.635  3780  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 09:28:24.635  3780  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-14 09:28:24.636  3780  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 09:28:24.640  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 09:28:24.645   872  2004 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-14 09:28:24.646  3780  3829 D BluetoothAdapter: STATE_ON
09-14 09:28:24.652  3780  3829 D BluetoothLeScanner: could not find callback wrapper
09-14 09:28:24.652  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 09:28:24.652  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-14 09:28:24.654  2665  2702 D BtGatt.AdvertiseManager: message : 1
,09-14 09:28:24.655   281  3825 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (210 us)
,09-14 09:28:24.655  2665  2702 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 09:28:24.725   872  3860 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 09:28:24.736  2665  2700 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-14 09:28:24.736  2665  2700 D BtGatt.GattService: Client app is not null!
,09-14 09:28:24.737  2665  2677 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 09:28:24.738  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 09:28:24.738  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-14 09:28:24.738  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 09:28:24.738  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 09:28:24.739  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-14 09:28:24.740  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 09:28:24.740  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-14 09:28:24.740  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:28:24.741  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:24.742  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.742  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.742  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:24.746  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.746  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.746  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.746  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.746  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.746  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.746  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.746  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.746  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:24.749  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:28:24.750  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:24.750  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:24.751  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 09:28:24.751  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 09:28:24.751  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:24.751  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 09:28:24.752  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.752  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:28:24.752  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:28:24.752  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 09:28:24.752  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.752  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:24.752  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.752  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.753  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 09:28:24.753  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 09:28:24.753  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 09:28:24.753  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.753  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.754  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 09:28:24.754  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.754  3780  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 09:28:24.754  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:24.754  3780  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 09:28:24.754  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.754  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.756  3780  3829 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-14 09:28:24.756  3780  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 09:28:24.756  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-14 09:28:24.757  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 09:28:24.757  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-14 09:28:24.757  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.757  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.757  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.757  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.757  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.757  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
,09-14 09:28:24.757  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:24.757  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.757  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.762  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:24.762  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.762  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.762  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
09-14 09:28:24.762  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.762  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.762  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:24.762  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.762  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.763  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:24.763  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.763  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:24.764  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4a43a not in the list
,09-14 09:28:24.764  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:24.764  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80fc8eb not in the list
09-14 09:28:24.764  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:24.764  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:24.764  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:24.766  3780  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-14 09:28:24.766  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 09:28:24.767  3780  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-14 09:28:24.767  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 09:28:24.767  3780  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-14 09:28:24.767  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-14 09:28:24.769  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-14 09:28:24.769  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-14 09:28:24.770  3780  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-14 09:28:24.770  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 09:28:24.770  3780  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-14 09:28:24.770  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 09:28:24.770  3780  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-14 09:28:24.770  3780  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-14 09:28:24.771  3780  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-14 09:28:24.771  3780  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-14 09:28:24.772  3780  3829 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-14 09:28:24.772  3780  3829 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-14 09:28:24.773  3780  3829 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-14 09:28:24.773  3780  3829 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-14 09:28:24.775  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 09:28:24.775  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbe178 added. We now have 3 listener(s)
,09-14 09:28:24.777  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 09:28:24.777  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:28:24.777  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:28:24.777  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 09:28:24.777  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51c051 added. We now have 3 listener(s)
,09-14 09:28:24.777  3780  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:28:24.778  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 09:28:24.780   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{d41b742 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{675a24 3780 com.test.thalitest/10000/u0 remote:10142b7}: process crashing
,09-14 09:28:24.780   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{9dd5353 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{675a24 3780 com.test.thalitest/10000/u0 remote:10142b7}: process crashing
09-14 09:28:24.781  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:24.786   872  3860 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-14 09:28:24.786   872  3860 I Adreno  : Build Date                       : 10/20/15
09-14 09:28:24.786   872  3860 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 09:28:24.786   872  3860 I Adreno  : Local Branch                     : M14
09-14 09:28:24.786   872  3860 I Adreno  : Remote Branch                    : 
09-14 09:28:24.786   872  3860 I Adreno  : Remote Branch                    : 
09-14 09:28:24.786   872  3860 I Adreno  : Reconstruct Branch               : 
,09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:24.787  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:24.789  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:24.789  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:28:24.790  3780  3829 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 09:28:24.791   872   882 D WifiService: setWifiEnabled: true pid=3780, uid=10000,
09-14 09:28:24.791   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:24.793   872  3860 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 09:28:24.800   872  2079 D WifiService: setWifiEnabled: false pid=3780, uid=10000
,09-14 09:28:24.801   872  2079 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:24.807   872   881 I art     : Background partial concurrent mark sweep GC freed 30877(2MB) AllocSpace objects, 13(336KB) LOS objects, 33% free, 29MB/44MB, paused 1.461ms total 136.373ms
,09-14 09:28:24.813  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 09:28:24.816   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-14 09:28:24.816   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 09:28:24.816   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 09:28:24.816   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:24.823   872  2115 D DhcpClient: Clearing IP address
,09-14 09:28:24.823   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-14 09:28:24.826   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:24.826   872  2121 D DhcpClient: Receive thread stopped
,09-14 09:28:24.828  1501  2537 V NativeCrypto: Read error: ssl=0x9b6d7600: I/O error during system call, Connection timed out
09-14 09:28:24.829  1501  2537 V NativeCrypto: SSL shutdown failed: ssl=0x9b6d7600: I/O error during system call, Broken pipe
09-14 09:28:24.831   872  2009 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-14 09:28:24.831   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
09-14 09:28:24.831   872  2108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-14 09:28:24.832   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED,
09-14 09:28:24.832   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-14 09:28:24.834   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 09:28:24.835   394   394 E Parcel  : Reading a NULL string not supported here.
,09-14 09:28:24.839   872  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-14 09:28:24.840   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-14 09:28:24.846   872  2108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-14 09:28:24.866   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 09:28:24.895   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 09:28:24.896   872  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-14 09:28:24.896   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:28:24.899   872   889 D Tethering: MasterInitialState.processMessage what=3
09-14 09:28:24.899   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7d1f490 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
09-14 09:28:24.899   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7d1f490 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
09-14 09:28:24.899   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7d1f490 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{675a24 3780 com.test.thalitest/10000/u0 remote:10142b7}: process crashing
09-14 09:28:24.901   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-14 09:28:24.902   872  1996 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{4493189 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
,09-14 09:28:24.902   872  1996 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{4493189 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
09-14 09:28:24.902   872  1996 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{4493189 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{675a24 3780 com.test.thalitest/10000/u0 remote:10142b7}: process crashing
09-14 09:28:24.906   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 09:28:24.908  1867  2304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 09:28:24.913  3430  3430 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@54d0663 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-14 09:28:24.921  1708  1708 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-14 09:28:24.930  1708  1708 D SystemUpdateService: onCreate
,09-14 09:28:24.933  1708  1708 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-14 09:28:24.948  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 09:28:24.950   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-14 09:28:24.951   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 09:28:24.953  1708  2515 I iu.UploadsManager: num queued entries: 0
,09-14 09:28:24.956  1708  2515 I iu.UploadsManager: num updated entries: 0
09-14 09:28:24.957  1708  2515 I iu.SyncManager: NEXT; no task
09-14 09:28:24.958  1708  3878 I SystemUpdateService: active receiver: enabled
,09-14 09:28:24.959  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 09:28:24.960  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-14 09:28:24.972   872  2008 I ActivityManager: Start proc 3881:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-14 09:28:24.975  1708  3878 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-14 09:28:24.977  1708  3878 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-14 09:28:24.977  1708  3878 I SystemUpdateService: now status is 0 (complete)
09-14 09:28:24.977  1708  3878 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-14 09:28:24.977  1708  3878 I SystemUpdateService: file has been verified
09-14 09:28:24.977  1708  3878 I SystemUpdateService: OTA package size = 12249756
,09-14 09:28:24.985  1708  3878 I SystemUpdateService: showing system update notification
,09-14 09:28:25.020  3881  3881 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-14 09:28:25.023  3881  3881 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:28:25.031  3881  3881 D SprintDMHelper: simOperator: 
,09-14 09:28:25.031  3881  3881 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 09:28:25.044   872  2211 I ActivityManager: Start proc 3893:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-14 09:28:25.053  1708  1708 D SystemUpdateService: onDestroy
,09-14 09:28:25.055   872  2215 I ActivityManager: Killing 3227:com.google.android.gm/u0a78 (adj 15): empty #17
,09-14 09:28:25.174   872  1400 I ActivityManager: Start proc 3909:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-14 09:28:25.177   872  2006 I ActivityManager: Killing 3430:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-14 09:28:25.186   872   885 W ActivityManager: Activity pause timeout for ActivityRecord{ab6676a u0 com.test.thalitest/.MainActivity t4 f}
,09-14 09:28:25.226   872   885 I ActivityManager: Killing 2808:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-14 09:28:25.300  3909  3909 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:28:25.312  3780  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:28:25.316  3780  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:28:25.328   872  2009 D WifiService: setWifiEnabled: true pid=3780, uid=10000
,09-14 09:28:25.328   872  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:25.343   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{576ee3e u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
,09-14 09:28:25.343   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{576ee3e u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
09-14 09:28:25.343   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{576ee3e u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{675a24 3780 com.test.thalitest/10000/u0 remote:10142b7}: process crashing
09-14 09:28:25.346   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-14 09:28:25.359   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-14 09:28:25.360   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-14 09:28:25.360   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-14 09:28:25.361   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-14 09:28:25.361   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-14 09:28:25.361   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-14 09:28:25.361   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 09:28:25.375   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-14 09:28:25.375   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=20.00 rxSuccessRate=34.75 delta 1000 -> 994
,09-14 09:28:25.377   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:25.378   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-14 09:28:25.378   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 09:28:25.381   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-14 09:28:25.381   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 09:28:25.382   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
09-14 09:28:25.382   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-14 09:28:25.390   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-14 09:28:25.398  3909  3909 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-14 09:28:25.398  3909  3909 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-14 09:28:25.398  3909  3909 I GAv4    :   adb logcat -s GAv4
,09-14 09:28:25.415  3909  3909 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-14 09:28:25.424  3909  3909 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-14 09:28:25.450   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-14 09:28:25.453  3909  3931 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-14 09:28:25.544  1982  2254 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,09-14 09:28:25.580  3909  3909 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-14 09:28:25.625  3909  3909 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-14 09:28:25.641  3909  3909 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6479-6482)
09-14 09:28:25.641  3909  3909 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-14 09:28:25.656  3909  3909 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cbc4e53}
09-14 09:28:25.657  3909  3909 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 09:28:25.657  3909  3909 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-14 09:28:25.667  3909  3909 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-14 09:28:25.671  3909  3909 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-14 09:28:25.692  3909  3909 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-14 09:28:25.708  3909  3909 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 09:28:25.708  3909  3909 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 09:28:25.708  3909  3909 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-14 09:28:25.708  3909  3909 I Adreno  : Build Date                       : 10/20/15
09-14 09:28:25.708  3909  3909 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 09:28:25.708  3909  3909 I Adreno  : Local Branch                     : M14
09-14 09:28:25.708  3909  3909 I Adreno  : Remote Branch                    : 
09-14 09:28:25.708  3909  3909 I Adreno  : Remote Branch                    : 
09-14 09:28:25.708  3909  3909 I Adreno  : Reconstruct Branch               : 
,09-14 09:28:25.784  3909  3909 I NSApplication: Starting up...
,09-14 09:28:25.792  3909  3960 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-14 09:28:25.823   872  1682 I ActivityManager: Start proc 3965:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-14 09:28:25.824   872  1682 I ActivityManager: Killing 1684:android.process.acore/u0a5 (adj 15): empty #17
,09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:28:25.884  3780  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:28:25.886  3780  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:28:25.902  2665  2696 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 09:28:25.902  2665  2696 D BluetoothAdapterProperties: Setting state to 13
,09-14 09:28:25.902  2665  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-14 09:28:25.903  2665  2696 D BluetoothAdapterProperties: onBluetoothDisable()
,09-14 09:28:25.903  2665  2696 I BluetoothAdapterState: Entering PendingCommandState
,09-14 09:28:25.908   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{98abe7f u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:25.908  2665  2700 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:28:25.912  2665  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 09:28:25.915  2665  2665 D HeadsetService: Received stop request...Stopping profile...
,09-14 09:28:25.917  1961  1989 D BluetoothHeadset: Proxy object disconnected
,09-14 09:28:25.918   872   872 D BluetoothHeadset: Proxy object disconnected
09-14 09:28:25.918   872   872 D BluetoothHeadset: Proxy object disconnected
09-14 09:28:25.918   872   872 D BluetoothHeadset: Proxy object disconnected
,09-14 09:28:25.918  1357  2331 D BluetoothHeadset: Proxy object disconnected
09-14 09:28:25.918  2665  2665 D A2dpService: Received stop request...Stopping profile...
09-14 09:28:25.918  1357  1357 D HeadsetProfile: Bluetooth service disconnected
,09-14 09:28:25.919  2665  2780 D A2dpStateMachine: Exit Disconnected: -1
,09-14 09:28:25.920  1357  1357 D BluetoothA2dp: Proxy object disconnected
,09-14 09:28:25.920   872   872 D BluetoothA2dp: Proxy object disconnected
,09-14 09:28:25.922  2665  2665 D HidService: Received stop request...Stopping profile...
,09-14 09:28:25.922  2665  2665 D HidService: Stopping Bluetooth HidService
,09-14 09:28:25.923  1357  1357 D BluetoothInputDevice: Proxy object disconnected
09-14 09:28:25.923  2665  2665 D HealthService: Received stop request...Stopping profile...
,09-14 09:28:25.923  1357  1357 D HidProfile: Bluetooth service disconnected
09-14 09:28:25.925  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:25.925  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:25.925  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 09:28:25.925  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 09:28:25.928  2665  2665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 09:28:25.929  2665  2665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-14 09:28:25.929  2665  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-14 09:28:25.929  2665  2665 D PanService: Received stop request...Stopping profile...
09-14 09:28:25.929  2665  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 09:28:25.929  2665  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:25.929  2665  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:25.929  2665  2700 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 09:28:25.931  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:25.931  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:25.931  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:25.931  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:25.932  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-14 09:28:25.932  1357  1357 D PanProfile: Bluetooth service disconnected
09-14 09:28:25.932  2665  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 09:28:25.933  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:25.933  2665  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:25.933  2665  2736 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:28:25.933  2665  2736 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:28:25.933  2665  2736 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-14 09:28:25.933  2665  2736 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:28:25.933  2665  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-14 09:28:25.933  2665  2665 V BluetoothAdapterState: isTurningOn()=false
,09-14 09:28:25.934  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:25.934  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:25.934  2665  2665 D BluetoothMapService: Received stop request...Stopping profile...
,09-14 09:28:25.934  2665  2665 D BluetoothMapService: stop()
09-14 09:28:25.935  2665  2665 D BluetoothMapAppObserver: deinitObservers()
09-14 09:28:25.935  2665  2665 D BluetoothMapAppObserver: removeReceiver()
,09-14 09:28:25.936  1357  1357 D BluetoothMap: Proxy object disconnected
09-14 09:28:25.936  1357  1357 D MapProfile: Bluetooth service disconnected
,09-14 09:28:25.937  2665  2665 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 09:28:25.937  2665  2665 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 09:28:25.938  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:25.938  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:25.938  2665  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 09:28:25.938  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:25.938  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:25.938  2665  2665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 09:28:25.939  2665  2700 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 09:28:25.939  2665  2665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-14 09:28:25.939  2665  2665 V BluetoothAdapterState: isTurningOff()=true
,09-14 09:28:25.939  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:25.939  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:25.939  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:25.940  2665  2665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 09:28:25.940  2665  2665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-14 09:28:25.941  2665  2665 D BluetoothMapService: MAP Service closeService in
09-14 09:28:25.941  2665  2665 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 09:28:25.941  2665  2665 D ObexServerSockets0: shutdown(block = true)
,09-14 09:28:25.941  2665  2789 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 09:28:25.942  2665  2665 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 09:28:25.942  2665  2790 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 09:28:25.942  2665  2774 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 09:28:25.942  2665  2665 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-14 09:28:25.942  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:25.942  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:25.943  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:25.943  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:25.943  2665  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 09:28:25.943  2665  2696 D BluetoothAdapterProperties: Setting state to 15
,09-14 09:28:25.943  2665  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 09:28:25.943  2665  2696 I BluetoothAdapterState: Entering BleOnState
09-14 09:28:25.944  2665  2665 D BluetoothMapService: cleanup()
09-14 09:28:25.944  2665  2665 D BluetoothMapService: MAP Service closeService in
,09-14 09:28:25.949  3965  3965 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-14 09:28:25.955   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 09:28:25.956  1357  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 09:28:25.956   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{b57fe4c u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:25.957  2665  2665 I BtOppRfcommListener: stopping Accept Thread
09-14 09:28:25.957  1961  2089 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:25.957  2665  3443 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 09:28:25.957  2665  3443 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 09:28:25.958   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:25.958  1357  1368 D BluetoothPan: onBluetoothStateChange on: false
,09-14 09:28:25.959   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 09:28:25.960  1357  2112 D BluetoothMap: onBluetoothStateChange: up=false
,09-14 09:28:25.962  1357  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-14 09:28:25.962  1357  2331 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 09:28:25.963  1357  2112 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 09:28:25.964   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:25.965  2665  2696 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 09:28:25.965  2665  2696 D BluetoothAdapterProperties: Setting state to 16
,09-14 09:28:25.965  2665  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-14 09:28:25.966  2665  2696 D BluetoothAdapterProperties: onBleDisable
,09-14 09:28:25.966   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{eba9e95 u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:25.966  2665  2696 I BluetoothAdapterState: Entering PendingCommandState
09-14 09:28:25.966  2665  2697 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-14 09:28:25.967   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{e051baa u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:25.967  2665  2700 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:28:25.968  2665  2736 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 09:28:25.968  2665  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 09:28:26.170  2665  2700 I bt_hci  : shut_down
,09-14 09:28:26.170  2665  2704 D bt_hwcfg: hw_epilog_process
,09-14 09:28:26.172  2665  2704 I bt_vendor: low_power_mode_cb
,09-14 09:28:26.192  2665  2704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 09:28:26.193  2665  2704 I bt_vendor: epilog_cb
09-14 09:28:26.193  2665  2704 I bt_hci  : epilog_finished_callback
,09-14 09:28:26.196  2665  2700 I bt_hci_h4: hal_close
,09-14 09:28:26.197  2665  2700 I bt_userial_vendor: device fd = 51 close
,09-14 09:28:26.302  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 09:28:26.327  2665  2697 D bt_stack_manager: event_shut_down_stack finished.
,09-14 09:28:26.328  2665  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 09:28:26.331  2665  2665 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 09:28:26.331  2665  2696 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-14 09:28:26.332  2665  2665 D BtGatt.GattService: Received stop request...Stopping profile...
09-14 09:28:26.332  2665  2665 D BtGatt.GattService: stop()
,09-14 09:28:26.332  2665  2665 D BtGatt.AdvertiseManager: advertise clients cleared
,09-14 09:28:26.334  2665  2665 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:26.335  2665  2665 V BluetoothAdapterState: isTurningOn()=false
,09-14 09:28:26.335  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:26.335  2665  2665 V BluetoothAdapterState: isBleTurningOff()=true
,09-14 09:28:26.336  2665  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-14 09:28:26.336  2665  2696 D BluetoothAdapterProperties: Setting state to 10
09-14 09:28:26.336  2665  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 09:28:26.336  2665  2696 I BluetoothAdapterState: Entering OffState
,09-14 09:28:26.338   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-14 09:28:26.348  2665  2665 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 09:28:26.348  2665  2665 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 09:28:26.348  2665  2665 I BluetoothServiceJni: cleanupNative: return from cleanup
09-14 09:28:26.348  2665  2697 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 09:28:26.352  2665  2697 D bt_stack_manager: event_clean_up_stack finished.
,09-14 09:28:26.354  2665  2665 I art     : System.exit called, status: 0
,09-14 09:28:26.354  2665  2665 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 09:28:26.412   872  1996 I ActivityManager: Process com.android.bluetooth (pid 2665) has died
,09-14 09:28:26.413   872  1996 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,09-14 09:28:26.439  3780  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:28:26.439  3780  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 09:28:26.440  3780  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:28:26.440  3780  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:28:26.480   872   889 I ActivityManager: Start proc 3983:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 09:28:26.602  3983  3983 D AdapterServiceConfig: Adding HeadsetService
,09-14 09:28:26.604  3983  3983 D AdapterServiceConfig: Adding A2dpService
09-14 09:28:26.604  3983  3983 D AdapterServiceConfig: Adding HidService
,09-14 09:28:26.605  3983  3983 D AdapterServiceConfig: Adding HealthService
09-14 09:28:26.605  3983  3983 D AdapterServiceConfig: Adding PanService
09-14 09:28:26.605  3983  3983 D AdapterServiceConfig: Adding GattService
09-14 09:28:26.605  3983  3983 D AdapterServiceConfig: Adding BluetoothMapService
,09-14 09:28:26.641   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d00f49:true
,09-14 09:28:26.642  3983  3983 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 09:28:26.651  3983  3983 I bt_bluedroid: init
09-14 09:28:26.651  3983  3995 I BluetoothAdapterState: Entering OffState
,09-14 09:28:26.655  3983  3996 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-14 09:28:26.656  3983  3996 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 09:28:26.656  3983  3996 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 09:28:26.656  3983  3996 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-14 09:28:26.657  3983  3983 I bt_bluedroid: get_profile_interface socket
,09-14 09:28:26.661  3983  3999 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-14 09:28:26.662  3983  3983 I bt_bluedroid: get_profile_interface sdp
09-14 09:28:26.663  3983  3999 D BluetoothAdapterProperties: Name is: Nexus 6
,09-14 09:28:26.667  3983  3994 I bt_bluedroid: config_hci_snoop_log
,09-14 09:28:26.670   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-14 09:28:26.675  3983  3995 D BluetoothAdapterState: Current state: OFF, message: 0
,09-14 09:28:26.676  3983  3995 D BluetoothAdapterProperties: Setting state to 14
09-14 09:28:26.676  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 09:28:26.679  3983  3995 D BluetoothBondStateMachine: make
,09-14 09:28:26.684  3983  4000 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 09:28:26.688  3983  3995 I BluetoothAdapterState: Entering PendingCommandState
,09-14 09:28:26.689  3983  3983 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 09:28:26.694  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:26.694  3983  3983 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 09:28:26.696  3983  3983 D BtGatt.GattService: Received start request. Starting profile...
09-14 09:28:26.696  3983  3983 D BtGatt.GattService: start()
,09-14 09:28:26.696  3983  3983 I bt_bluedroid: get_profile_interface gatt
,09-14 09:28:26.698  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:26.699  3983  3983 D BtGatt.AdvertiseManager: advertise manager created
,09-14 09:28:26.710  3983  3983 V BluetoothAdapterState: isTurningOff()=false
,09-14 09:28:26.710  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:26.710  3983  3983 V BluetoothAdapterState: isBleTurningOn()=true
,09-14 09:28:26.711  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:26.712  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 09:28:26.713  3983  3995 I bt_bluedroid: enable
,09-14 09:28:26.713  3983  3996 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-14 09:28:26.713  3983  3996 I bt_hci  : start_up
,09-14 09:28:26.724  3983  3996 I bt_vendor: alloc value 0xb3a7b189
,09-14 09:28:26.724  3983  3996 I bt_vendor: init
09-14 09:28:26.724  3983  3996 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 09:28:26.724  3983  3996 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 09:28:26.834  3983  3996 D bt_hci  : start_up starting async portion
,09-14 09:28:26.835  3983  4003 I bt_hci  : event_finish_startup
09-14 09:28:26.835  3983  4003 I bt_hci_h4: hal_open
09-14 09:28:26.836  3983  4003 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-14 09:28:26.846  3983  4003 I bt_userial_vendor: device fd = 51 open
,09-14 09:28:26.875  3983  4003 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 09:28:26.907  3983  4003 D bt_hwcfg: Chipset BCM4354A2
09-14 09:28:26.908  3983  4003 D bt_hwcfg: Target name = [BCM4354A2]
,09-14 09:28:26.908  3983  4003 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-14 09:28:27.003  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-14 09:28:27.555  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-14 09:28:27.583  3983  4003 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 09:28:27.584  3983  4003 D bt_hwcfg: Settlement delay -- 100 ms
09-14 09:28:27.601  3983  4003 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 09:28:27.718  3983  4003 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 09:28:27.719  3983  4003 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-14 09:28:27.744  3983  4003 I bt_hwcfg: vendor lib fwcfg completed
09-14 09:28:27.745  3983  4003 I bt_vendor: firmware callback
,09-14 09:28:27.745  3983  4003 I bt_hci  : firmware_config_callback
,09-14 09:28:27.757  3983  4005 I bt_btu  : btu_task pending for preload complete event
,09-14 09:28:27.757  3983  4005 I bt_btu_task: Bluetooth chip preload is complete
,09-14 09:28:27.757  3983  4005 I bt_btu  : btu_task received preload complete event
,09-14 09:28:27.765  3983  4005 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 09:28:27.765  3983  4005 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-14 09:28:27.765  3983  4005 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 09:28:27.766  3983  4005 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 09:28:27.766  3983  4005 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 09:28:27.766  3983  4005 I         : BTE_InitTraceLevels -- TRC_A2D
,09-14 09:28:27.766  3983  4005 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-14 09:28:27.766  3983  4005 I         : BTE_InitTraceLevels -- TRC_BTM
,09-14 09:28:27.767  3983  4005 I         : BTE_InitTraceLevels -- TRC_GAP
,09-14 09:28:27.767  3983  4005 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 09:28:27.767  3983  4005 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 09:28:27.767  3983  4005 I         : BTE_InitTraceLevels -- TRC_GATT
,09-14 09:28:27.767  3983  4005 I         : BTE_InitTraceLevels -- TRC_SMP
,09-14 09:28:27.768  3983  4005 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-14 09:28:27.768  3983  4005 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 09:28:27.778  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 09:28:27.806  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-14 09:28:27.806  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-14 09:28:27.812   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 09:28:27.822   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-14 09:28:27.823   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-14 09:28:27.823   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:27.849   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:27.867   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:27.868   872  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-14 09:28:27.885   872  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-14 09:28:27.887   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 09:28:27.899  3983  4005 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f8d9d
,09-14 09:28:27.900  3983  4005 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f8d9d 
,09-14 09:28:27.907  3983  3999 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 09:28:27.909  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 09:28:27.910  3983  3999 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-14 09:28:27.911  3983  3999 D BluetoothAdapterProperties: Name is: Nexus 6
,09-14 09:28:27.914   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{a6408fe u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:27.914  3983  3999 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:28:27.914  3983  3999 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 09:28:27.915  3983  3999 D bt_hci  : do_postload posting postload work item
09-14 09:28:27.915  3983  4003 I bt_hci  : event_postload
09-14 09:28:27.915  3983  4003 I bt_vendor: sco_config_cb
,09-14 09:28:27.916  3983  4003 I bt_hci  : sco_config_callback postload finished.
,09-14 09:28:27.917  3983  3999 D bt_bte_conf: Device ID record 1 : primary
,09-14 09:28:27.917   872  4009 D DhcpClient: Receive thread started
09-14 09:28:27.917  3983  3999 D bt_bte_conf:   vendorId            = 000f
09-14 09:28:27.917  3983  3999 D bt_bte_conf:   vendorIdSource      = 0001
09-14 09:28:27.918  3983  3999 D bt_bte_conf:   product             = 1200
09-14 09:28:27.918  3983  3999 D bt_bte_conf:   version             = 1436
,09-14 09:28:27.918  3983  3999 D bt_bte_conf:   clientExecutableURL = 
09-14 09:28:27.918  3983  3999 D bt_bte_conf:   serviceDescription  = 
09-14 09:28:27.918  3983  3999 D bt_bte_conf:   documentationURL    = 
,09-14 09:28:27.919  3983  3999 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 09:28:27.919  3983  3996 D bt_stack_manager: event_start_up_stack finished
09-14 09:28:27.920  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 09:28:27.920  3983  3995 D BluetoothAdapterProperties: Setting state to 15
09-14 09:28:27.920  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-14 09:28:27.921  3983  3995 I BluetoothAdapterState: Entering BleOnState
,09-14 09:28:27.924  3983  4003 I bt_vendor: low_power_mode_cb
,09-14 09:28:27.924  3983  3995 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 09:28:27.925  3983  3995 D BluetoothAdapterProperties: Setting state to 11
,09-14 09:28:27.925  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-14 09:28:27.928   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{a5f0b75 u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:27.929  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:27.929  3983  3983 D HeadsetService: Received start request. Starting profile...
,09-14 09:28:27.932  3983  3983 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-14 09:28:27.932  3983  3983 D HeadsetStateMachine: make
,09-14 09:28:27.939  3983  3995 I BluetoothAdapterState: Entering PendingCommandState
,09-14 09:28:27.941  3983  3983 D HeadsetStateMachine: max_hf_connections = 1
,09-14 09:28:27.941  3983  3983 I bt_bluedroid: get_profile_interface handsfree
,09-14 09:28:27.941  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-14 09:28:27.942  3983  3999 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-14 09:28:27.947  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:27.949  3983  3983 D A2dpService: Received start request. Starting profile...
,09-14 09:28:27.949  3983  3983 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-14 09:28:27.951  3983  3983 I bt_bluedroid: get_profile_interface avrcp
,09-14 09:28:27.956  3983  3983 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 09:28:27.956  3983  3983 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 09:28:27.956  3983  3983 D A2dpStateMachine: make
,09-14 09:28:27.957  3983  3983 I bt_bluedroid: get_profile_interface a2dp
,09-14 09:28:27.958  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 09:28:27.959  3983  4017 D A2dpStateMachine: Enter Disconnected: -2
09-14 09:28:27.959  3983  3983 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 09:28:27.960  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:27.961  3983  3983 D HidService: Received start request. Starting profile...
09-14 09:28:27.961  3983  3983 I bt_bluedroid: get_profile_interface hidhost
09-14 09:28:27.961  3983  3983 D HidService: setHidService(): set to: null
,09-14 09:28:27.961  3983  3999 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39da3e5
09-14 09:28:27.962  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 09:28:27.962  3983  3983 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-14 09:28:27.962  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:27.963  3983  3983 D HealthService: Received start request. Starting profile...
,09-14 09:28:27.964  3983  3983 I bt_bluedroid: get_profile_interface health
,09-14 09:28:27.964  3983  3983 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-14 09:28:27.965  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:27.967  3983  3983 V BluetoothAdapterState: isTurningOff()=false
,09-14 09:28:27.967  3983  3983 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:27.967  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:27.967  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 09:28:27.968  3983  3983 D PanService: Received start request. Starting profile...
09-14 09:28:27.968  3983  3983 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 09:28:27.969  3983  3983 I bt_bluedroid: get_profile_interface pan
09-14 09:28:27.969  3983  3999 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 09:28:27.972  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:27.973  3983  3983 D BluetoothMapService: Received start request. Starting profile...
09-14 09:28:27.973  3983  3983 D BluetoothMapService: start()
,09-14 09:28:27.975  3983  3983 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-14 09:28:27.976  3983  3983 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 09:28:27.976  3983  3983 D BluetoothMapAppObserver: createReceiver()
,09-14 09:28:27.977  3983  3983 D BluetoothMapAppObserver: initObservers()
09-14 09:28:27.977  3983  3983 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:27.983  3983  4015 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:27.983  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:27.984  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:27.984  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 09:28:27.984  3983  3995 D BluetoothAdapterProperties: ScanMode =  20
09-14 09:28:27.985  3983  3995 D BluetoothAdapterProperties: State =  11
09-14 09:28:27.986  3983  3999 D BluetoothAdapterProperties: Scan Mode:21
09-14 09:28:27.986  3983  3999 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 09:28:27.986  3983  3995 D BluetoothAdapterProperties: Setting state to 12
,09-14 09:28:27.986  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 09:28:27.986   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{2682cc8 u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:27.986   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:28:27.987  3983  3995 I BluetoothAdapterState: Entering OnState
09-14 09:28:27.987  1357  2112 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 09:28:27.989  1961  1989 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 09:28:27.990   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 09:28:27.990  1357  1374 D BluetoothPan: onBluetoothStateChange on: true
,09-14 09:28:27.993   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 09:28:27.993  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 09:28:27.993  1357  1357 D PanProfile: Bluetooth service connected
,09-14 09:28:27.994  1357  2331 D BluetoothMap: onBluetoothStateChange: up=true
,09-14 09:28:27.994   872   872 D BluetoothA2dp: Proxy object connected
,09-14 09:28:27.996  1357  2112 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 09:28:27.997  1357  1357 D BluetoothMap: Proxy object connected
09-14 09:28:27.997  1357  1357 D MapProfile: Bluetooth service connected
09-14 09:28:27.997  1357  1357 D BluetoothMap: getConnectedDevices()
09-14 09:28:27.998  1357  1357 D BluetoothA2dp: Proxy object connected
09-14 09:28:27.998  1357  1368 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 09:28:27.999   872  1310 E native  : do suspend false
09-14 09:28:28.000  1357  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-14 09:28:28.001   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 09:28:28.002  1357  1357 D BluetoothInputDevice: Proxy object connected
,09-14 09:28:28.002  1357  1357 D HidProfile: Bluetooth service connected
,09-14 09:28:28.002   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-14 09:28:28.002   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{fb6855 u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:28.003  3983  3983 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 09:28:28.004  3983  3983 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 09:28:28.006  3983  3983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:28.008  3983  3983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:28:28.009  3983  3983 D ObexServerSockets: Succeed to create listening sockets 
09-14 09:28:28.009  3983  3983 D ObexServerSockets0: startAccept()
09-14 09:28:28.009  3983  3983 D ObexServerSockets0: prepareForNewConnect()
,09-14 09:28:28.011  3983  3983 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 09:28:28.011  3983  3983 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-14 09:28:28.012  3983  3983 D BluetoothMapService: onReceive
,09-14 09:28:28.012  3983  3983 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:28:28.012  3983  3983 D BluetoothMapService: STATE_ON
09-14 09:28:28.012  3983  4022 D ObexServerSockets0: Accepting socket connection...
09-14 09:28:28.012   872  2115 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 09:28:28.013  3983  4023 D ObexServerSockets0: Accepting socket connection...
,09-14 09:28:28.026   872  4009 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172674, domain null
,09-14 09:28:28.026   872  2115 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172674 seconds
09-14 09:28:28.027   872  2115 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-14 09:28:28.032  3983  3983 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 09:28:28.032  3983  3983 D ObexServerSockets0: prepareForNewConnect()
,09-14 09:28:28.039   872  4009 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-14 09:28:28.039   872  2115 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-14 09:28:28.040   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:28.044   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 09:28:28.046   872  2115 D DhcpClient: Scheduling renewal in 86399s
,09-14 09:28:28.055   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 09:28:28.057   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 09:28:28.057   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 09:28:28.058   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-14 09:28:28.062   872  1312 D ConnectivityService: Adding iface wlan0 to network 101
,09-14 09:28:28.063   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 09:28:28.095  1961  2089 D BluetoothHeadset: Proxy object connected
,09-14 09:28:28.095   872   872 D BluetoothHeadset: Proxy object connected
09-14 09:28:28.096   872   872 D BluetoothHeadset: Proxy object connected
09-14 09:28:28.096   872   872 D BluetoothHeadset: Proxy object connected
,09-14 09:28:28.097  1357  2331 D BluetoothHeadset: Proxy object connected
,09-14 09:28:28.098  1357  1357 D HeadsetProfile: Bluetooth service connected
,09-14 09:28:28.102   872   889 D BluetoothHeadset: Proxy object connected
,09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:28:28.104  3780  3982 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:28:28.108  3780  3982 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:28:28.111  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 09:28:28.111  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:28.116   872  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-14 09:28:28.116   872  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-14 09:28:28.118   872  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-14 09:28:28.119   872  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-14 09:28:28.121   872  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-14 09:28:28.133   872  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 09:28:28.138   872  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-14 09:28:28.138   872  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-14 09:28:28.138   872  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-14 09:28:28.138   872  1312 D ConnectivityService:    accepting network in place of null
,09-14 09:28:28.139   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-14 09:28:28.139   872  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-14 09:28:28.139   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 09:28:28.143  3983  3995 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 09:28:28.143  3983  3995 D BluetoothAdapterProperties: Setting state to 13
09-14 09:28:28.143  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-14 09:28:28.144  3983  3995 D BluetoothAdapterProperties: onBluetoothDisable()
,09-14 09:28:28.146  3983  3995 I BluetoothAdapterState: Entering PendingCommandState
,09-14 09:28:28.148   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7d734d1 u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:28.148  3983  3999 D BluetoothAdapterProperties: Scan Mode:20
,09-14 09:28:28.149  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 09:28:28.149   872  4008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148991, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 09:28:28.152  3983  3983 D HeadsetService: Received stop request...Stopping profile...
,09-14 09:28:28.156  1961  1989 D BluetoothHeadset: Proxy object disconnected
,09-14 09:28:28.156   872   872 D BluetoothHeadset: Proxy object disconnected
,09-14 09:28:28.156   872   872 D BluetoothHeadset: Proxy object disconnected
09-14 09:28:28.157  3983  3983 D A2dpService: Received stop request...Stopping profile...
09-14 09:28:28.157   872   872 D BluetoothHeadset: Proxy object disconnected
09-14 09:28:28.157  3983  4017 D A2dpStateMachine: Exit Disconnected: -1
09-14 09:28:28.157  1357  1374 D BluetoothHeadset: Proxy object disconnected
09-14 09:28:28.157  1357  1357 D HeadsetProfile: Bluetooth service disconnected
09-14 09:28:28.158   872   872 D BluetoothA2dp: Proxy object disconnected
09-14 09:28:28.158  1357  1357 D BluetoothA2dp: Proxy object disconnected
09-14 09:28:28.158  3983  3983 D HidService: Received stop request...Stopping profile...
09-14 09:28:28.158  3983  3983 D HidService: Stopping Bluetooth HidService
,09-14 09:28:28.159  1357  1357 D BluetoothInputDevice: Proxy object disconnected
,09-14 09:28:28.159  1357  1357 D HidProfile: Bluetooth service disconnected
09-14 09:28:28.160  3983  3983 D HealthService: Received stop request...Stopping profile...
09-14 09:28:28.161  3983  3983 D PanService: Received stop request...Stopping profile...
,09-14 09:28:28.162  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 09:28:28.162  1357  1357 D PanProfile: Bluetooth service disconnected
09-14 09:28:28.162  3983  3983 D BluetoothMapService: Received stop request...Stopping profile...
09-14 09:28:28.162  3983  3983 D BluetoothMapService: stop()
09-14 09:28:28.163  3983  3983 D BluetoothMapAppObserver: deinitObservers()
09-14 09:28:28.163  3983  3983 D BluetoothMapAppObserver: removeReceiver()
,09-14 09:28:28.164  3983  3983 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:28.163  1357  1357 D BluetoothMap: Proxy object disconnected
,09-14 09:28:28.164  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.164  1357  1357 D MapProfile: Bluetooth service disconnected
,09-14 09:28:28.164  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.164  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:28.165  3983  3983 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 09:28:28.165  3983  3983 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 09:28:28.165  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-14 09:28:28.165  3983  4005 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:28.165  3983  4005 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 09:28:28.165  3983  4005 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 09:28:28.165  3983  3999 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
09-14 09:28:28.165  3983  3983 V BluetoothAdapterState: isTurningOff()=true,
09-14 09:28:28.165  3983  3983 V BluetoothAdapterState: isTurningOn()=false,
09-14 09:28:28.165  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.165  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 09:28:28.166  3983  4005 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:28.166  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-14 09:28:28.166  3983  4005 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:28.167  3983  4005 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:28:28.167  3983  4005 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:28:28.167  3983  4005 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 09:28:28.167  3983  4005 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 09:28:28.167  3983  3983 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:28.167  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.167  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.167  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:28.167  3983  3983 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 09:28:28.167  3983  3999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 09:28:28.167  3983  3983 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 09:28:28.168  3983  3983 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:28.168  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.168  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.168  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:28.168  3983  3983 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 09:28:28.168  3983  3999 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 09:28:28.168  3983  3983 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 09:28:28.169  3983  3983 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:28.169  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.169  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.169  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:28.169  3983  3983 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 09:28:28.169  3983  3983 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 09:28:28.170  3983  3983 D BluetoothMapService: MAP Service closeService in
09-14 09:28:28.170  3983  3983 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 09:28:28.170  3983  3983 D ObexServerSockets0: shutdown(block = true)
09-14 09:28:28.170  3983  4022 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 09:28:28.171  3983  3983 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 09:28:28.171  3983  3983 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 09:28:28.171  3983  4010 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 09:28:28.172  3983  4023 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 09:28:28.172  3983  3983 V BluetoothAdapterState: isTurningOff()=true
09-14 09:28:28.172  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.172  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.172  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:28.172  3983  3983 D BluetoothMapService: cleanup()
09-14 09:28:28.172  3983  3983 D BluetoothMapService: MAP Service closeService in
09-14 09:28:28.173  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 09:28:28.173  3983  3995 D BluetoothAdapterProperties: Setting state to 15
09-14 09:28:28.173  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 09:28:28.173  3983  3995 I BluetoothAdapterState: Entering BleOnState
09-14 09:28:28.180   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 09:28:28.194   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:28.194  1357  1368 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:28.194  1961  2089 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:28.195   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:28.195   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{35f5b36 u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:28.195  1357  2112 D BluetoothPan: onBluetoothStateChange on: false
09-14 09:28:28.195   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 09:28:28.195  1357  1374 D BluetoothMap: onBluetoothStateChange: up=false
09-14 09:28:28.196  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 09:28:28.196  1357  1374 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 09:28:28.197  1357  2112 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 09:28:28.197   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 09:28:28.197  3983  3995 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 09:28:28.197  3983  3995 D BluetoothAdapterProperties: Setting state to 16
09-14 09:28:28.197  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-14 09:28:28.198   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{f287a37 u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:28.199  3983  3995 D BluetoothAdapterProperties: onBleDisable
09-14 09:28:28.199  3983  3995 I BluetoothAdapterState: Entering PendingCommandState
09-14 09:28:28.199  3983  3996 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 09:28:28.199   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{702fba4 u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:28.200  3983  3999 D BluetoothAdapterProperties: Scan Mode:20
09-14 09:28:28.200  3983  4005 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 09:28:28.200  3983  4005 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 09:28:28.215   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 09:28:28.220   872  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-14 09:28:28.220   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 09:28:28.225   872  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-14 09:28:28.228   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-14 09:28:28.230   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{9c94d0d u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
,09-14 09:28:28.230   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{9c94d0d u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
,09-14 09:28:28.275   872  4007 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-14 09:28:28.337   872  4007 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:28:28 GMT], X-Android-Received-Millis=[1473838108336], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473838108315]}
,09-14 09:28:28.338   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 09:28:28.339   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-14 09:28:28.339   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 09:28:28.345   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 09:28:28.370  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:28.373  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:28.399  3983  3999 I bt_hci  : shut_down
,09-14 09:28:28.400  3983  4003 D bt_hwcfg: hw_epilog_process
,09-14 09:28:28.401  3983  4003 I bt_vendor: low_power_mode_cb
,09-14 09:28:28.405  1501  2289 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 09:28:28.405  1501  2289 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-14 09:28:28.405  1501  2289 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 09:28:28.405  1501  2289 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 09:28:28.424  3021  4040 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-14 09:28:28.424  3021  4040 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jdm.a(PG:82)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jcs.o(PG:406)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jcn.a(PG:1379)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jcs.i(PG:143)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at blb.a(PG:3937)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at czp.a(PG:18188)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at czp.a(PG:9081)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at czq.run(PG:1686)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 09:28:28.424  3021  4040 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jdj.a(PG:4091)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jdj.a(PG:1125)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jdm.a(PG:77)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	... 12 more
09-14 09:28:28.424  3021  4040 E HttpOperation: Caused by: faj: BadAuthentication
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at fal.a(PG:38)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	at jdj.a(PG:4089)
09-14 09:28:28.424  3021  4040 E HttpOperation: 	... 14 more
,09-14 09:28:28.426  3983  4003 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 09:28:28.426  3983  4003 I bt_vendor: epilog_cb
09-14 09:28:28.426  3983  4003 I bt_hci  : epilog_finished_callback
,09-14 09:28:28.427  3983  3999 I bt_hci_h4: hal_close
,09-14 09:28:28.427  3983  3999 I bt_userial_vendor: device fd = 51 close
,09-14 09:28:28.488  1501  2022 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 09:28:28.488  1501  2022 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-14 09:28:28.489  1501  2022 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 09:28:28.489  1501  2022 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 09:28:28.517  3021  4040 E HttpOperation: [getmobileexperiments] Unexpected exception
09-14 09:28:28.517  3021  4040 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jdm.a(PG:82)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jcs.o(PG:406)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jcn.a(PG:1379)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jcs.i(PG:143)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at hec.a(PG:42)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at hee.a(PG:102)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at czr.a(PG:65)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at kka.a(PG:108)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at czp.a(PG:19176)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at czp.a(PG:9081)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at czq.run(PG:1686)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 09:28:28.517  3021  4040 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jdj.a(PG:4091)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jdj.a(PG:1125)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jdm.a(PG:77)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	... 15 more
09-14 09:28:28.517  3021  4040 E HttpOperation: Caused by: faj: BadAuthentication
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at fal.a(PG:38)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	at jdj.a(PG:4089)
09-14 09:28:28.517  3021  4040 E HttpOperation: 	... 17 more
,09-14 09:28:28.518  3021  4040 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-14 09:28:28.518  3021  4040 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jdm.a(PG:82)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jcs.o(PG:406)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jcn.a(PG:1379)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jcs.i(PG:143)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at hec.a(PG:42)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at hee.a(PG:102)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at czr.a(PG:65)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at kka.a(PG:108)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at czp.a(PG:19176)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at czp.a(PG:9081)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at czq.run(PG:1686)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jdj.a(PG:4091)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jdj.a(PG:1125)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jdm.a(PG:77)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	... 15 more
09-14 09:28:28.518  3021  4040 E ExperimentLoader: Caused by: faj: BadAuthentication
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at fal.a(PG:38)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	at jdj.a(PG:4089)
09-14 09:28:28.518  3021  4040 E ExperimentLoader: 	... 17 more
,09-14 09:28:28.547  3983  3996 D bt_stack_manager: event_shut_down_stack finished.
,09-14 09:28:28.547  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 09:28:28.552  3983  3983 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 09:28:28.553  3983  3983 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 09:28:28.553  3983  3983 D BtGatt.GattService: stop()
09-14 09:28:28.553  3983  3983 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 09:28:28.553  3983  3995 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 09:28:28.554  3983  3983 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:28.554  3983  3983 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.554  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:28.555  3983  3983 V BluetoothAdapterState: isBleTurningOff()=true
09-14 09:28:28.555  3983  3995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 09:28:28.555  3983  3995 D BluetoothAdapterProperties: Setting state to 10
09-14 09:28:28.555  3983  3995 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-14 09:28:28.557  3983  3995 I BluetoothAdapterState: Entering OffState
,09-14 09:28:28.558   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-14 09:28:28.565  3983  3983 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 09:28:28.566  3983  3983 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-14 09:28:28.567  3983  3983 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-14 09:28:28.567  3983  3996 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 09:28:28.575  3983  3996 D bt_stack_manager: event_clean_up_stack finished.
,09-14 09:28:28.576  3983  3983 I art     : System.exit called, status: 0
,09-14 09:28:28.576  3983  3983 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 09:28:28.629   872  2211 I ActivityManager: Process com.android.bluetooth (pid 3983) has died
,09-14 09:28:28.662   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129845, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-14 09:28:28.683  3780  4029 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:28.684  3780  4029 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 09:28:28.684  3780  4029 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 09:28:28.684  3780  4029 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:28.688  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:28.712   872   889 I ActivityManager: Start proc 4046:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 09:28:28.784  4046  4046 D AdapterServiceConfig: Adding HeadsetService
,09-14 09:28:28.784  4046  4046 D AdapterServiceConfig: Adding A2dpService
09-14 09:28:28.785  4046  4046 D AdapterServiceConfig: Adding HidService
,09-14 09:28:28.785  4046  4046 D AdapterServiceConfig: Adding HealthService
,09-14 09:28:28.785  4046  4046 D AdapterServiceConfig: Adding PanService
,09-14 09:28:28.785  4046  4046 D AdapterServiceConfig: Adding GattService,
,09-14 09:28:28.786  4046  4046 D AdapterServiceConfig: Adding BluetoothMapService
,09-14 09:28:28.797   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4b6fb1:true
,09-14 09:28:28.798  4046  4046 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 09:28:28.805  4046  4058 I BluetoothAdapterState: Entering OffState
,09-14 09:28:28.806  4046  4046 I bt_bluedroid: init
,09-14 09:28:28.808  4046  4059 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-14 09:28:28.809  4046  4059 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-14 09:28:28.809  4046  4059 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 09:28:28.809  4046  4059 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-14 09:28:28.810  4046  4046 I bt_bluedroid: get_profile_interface socket
,09-14 09:28:28.815  4046  4046 I bt_bluedroid: get_profile_interface sdp
,09-14 09:28:28.815  4046  4062 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-14 09:28:28.819  4046  4062 D BluetoothAdapterProperties: Name is: Nexus 6
,09-14 09:28:28.821  4046  4056 I bt_bluedroid: config_hci_snoop_log
,09-14 09:28:28.822   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-14 09:28:28.827  4046  4058 D BluetoothAdapterState: Current state: OFF, message: 0
09-14 09:28:28.827  4046  4058 D BluetoothAdapterProperties: Setting state to 14
09-14 09:28:28.827  4046  4058 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-14 09:28:28.829  4046  4058 D BluetoothBondStateMachine: make
,09-14 09:28:28.832  4046  4063 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 09:28:28.835  4046  4058 I BluetoothAdapterState: Entering PendingCommandState
,09-14 09:28:28.838  4046  4046 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 09:28:28.846  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:28.847  4046  4046 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 09:28:28.848  4046  4046 D BtGatt.GattService: Received start request. Starting profile...,
,09-14 09:28:28.848  4046  4046 D BtGatt.GattService: start()
09-14 09:28:28.848  4046  4046 I bt_bluedroid: get_profile_interface gatt
09-14 09:28:28.849  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:28.850  4046  4046 D BtGatt.AdvertiseManager: advertise manager created
,09-14 09:28:28.857  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-14 09:28:28.858  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-14 09:28:28.858  4046  4046 V BluetoothAdapterState: isBleTurningOn()=true
09-14 09:28:28.858  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 09:28:28.858  4046  4058 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 09:28:28.861  4046  4058 I bt_bluedroid: enable
,09-14 09:28:28.861  4046  4059 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-14 09:28:28.862  4046  4059 I bt_hci  : start_up
,09-14 09:28:28.868  4046  4059 I bt_vendor: alloc value 0xb3a7b189
,09-14 09:28:28.868  4046  4059 I bt_vendor: init
,09-14 09:28:28.868  4046  4059 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 09:28:28.868  4046  4059 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 09:28:28.976  4046  4059 D bt_hci  : start_up starting async portion
,09-14 09:28:28.976  4046  4066 I bt_hci  : event_finish_startup
09-14 09:28:28.977  4046  4066 I bt_hci_h4: hal_open
,09-14 09:28:28.979  4046  4066 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-14 09:28:28.988  4046  4066 I bt_userial_vendor: device fd = 51 open
,09-14 09:28:29.019  4046  4066 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 09:28:29.051  4046  4066 D bt_hwcfg: Chipset BCM4354A2
09-14 09:28:29.051  4046  4066 D bt_hwcfg: Target name = [BCM4354A2]
,09-14 09:28:29.052  4046  4066 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-14 09:28:29.221   872  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-14 09:28:29.240  4046  4058 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-14 09:28:29.378   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-14 09:28:29.706  4046  4066 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 09:28:29.707  4046  4066 D bt_hwcfg: Settlement delay -- 100 ms
09-14 09:28:29.707  4046  4066 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 09:28:29.781  4046  4058 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-14 09:28:29.826  4046  4066 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 09:28:29.827  4046  4066 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-14 09:28:29.857  4046  4066 I bt_hwcfg: vendor lib fwcfg completed
,09-14 09:28:29.857  4046  4066 I bt_vendor: firmware callback
,09-14 09:28:29.857  4046  4066 I bt_hci  : firmware_config_callback
,09-14 09:28:29.872  4046  4070 I bt_btu  : btu_task pending for preload complete event
,09-14 09:28:29.872  4046  4070 I bt_btu_task: Bluetooth chip preload is complete
,09-14 09:28:29.873  4046  4070 I bt_btu  : btu_task received preload complete event
,09-14 09:28:29.882  4046  4070 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 09:28:29.882  4046  4070 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-14 09:28:29.883  4046  4070 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-14 09:28:29.883  4046  4070 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-14 09:28:29.883  4046  4070 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-14 09:28:29.883  4046  4070 I         : BTE_InitTraceLevels -- TRC_A2D
,09-14 09:28:29.884  4046  4070 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-14 09:28:29.884  4046  4070 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 09:28:29.884  4046  4070 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 09:28:29.884  4046  4070 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 09:28:29.884  4046  4070 I         : BTE_InitTraceLevels -- TRC_SDP
,09-14 09:28:29.885  4046  4070 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 09:28:29.885  4046  4070 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 09:28:29.885  4046  4070 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 09:28:29.885  4046  4070 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 09:28:30.019  4046  4070 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f8d9d
,09-14 09:28:30.019  4046  4070 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f8d9d 
,09-14 09:28:30.030  4046  4062 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 09:28:30.031  4046  4062 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 09:28:30.032  4046  4062 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-14 09:28:30.035  4046  4062 D BluetoothAdapterProperties: Name is: Nexus 6
09-14 09:28:30.038  4046  4062 D BluetoothAdapterProperties: Scan Mode:20
,09-14 09:28:30.038  4046  4062 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 09:28:30.039  4046  4062 D bt_hci  : do_postload posting postload work item,
09-14 09:28:30.039  4046  4066 I bt_hci  : event_postload
09-14 09:28:30.040  4046  4066 I bt_vendor: sco_config_cb
,09-14 09:28:30.040  4046  4066 I bt_hci  : sco_config_callback postload finished.
09-14 09:28:30.038   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{969e79c u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:30.043  4046  4062 D bt_bte_conf: Device ID record 1 : primary
09-14 09:28:30.043  4046  4062 D bt_bte_conf:   vendorId            = 000f
,09-14 09:28:30.043  4046  4062 D bt_bte_conf:   vendorIdSource      = 0001
09-14 09:28:30.043  4046  4062 D bt_bte_conf:   product             = 1200,
09-14 09:28:30.044  4046  4062 D bt_bte_conf:   version             = 1436
09-14 09:28:30.044  4046  4062 D bt_bte_conf:   clientExecutableURL = 
,09-14 09:28:30.044  4046  4062 D bt_bte_conf:   serviceDescription  = 
,09-14 09:28:30.045  4046  4066 I bt_vendor: low_power_mode_cb
,09-14 09:28:30.045  4046  4062 D bt_bte_conf:   documentationURL    = 
09-14 09:28:30.046  4046  4062 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 09:28:30.047  4046  4059 D bt_stack_manager: event_start_up_stack finished
,09-14 09:28:30.048  4046  4058 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 09:28:30.048  4046  4058 D BluetoothAdapterProperties: Setting state to 15,
,09-14 09:28:30.048  4046  4058 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-14 09:28:30.049  4046  4058 I BluetoothAdapterState: Entering BleOnState
,09-14 09:28:30.055  4046  4058 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-14 09:28:30.055  4046  4058 D BluetoothAdapterProperties: Setting state to 11
09-14 09:28:30.056  4046  4058 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 09:28:30.060   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{e57ed7a u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:30.064  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:30.064  4046  4046 D HeadsetService: Received start request. Starting profile...
,09-14 09:28:30.068  4046  4046 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-14 09:28:30.068  4046  4046 D HeadsetStateMachine: make
09-14 09:28:30.075  4046  4058 I BluetoothAdapterState: Entering PendingCommandState
,09-14 09:28:30.106   872   886 W Looper  : Ignoring unexpected epoll events 0x1 on fd 147 that is no longer registered.
09-14 09:28:30.106   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-14 09:28:30.107  4046  4046 D HeadsetStateMachine: max_hf_connections = 1
,09-14 09:28:30.108  4046  4046 I bt_bluedroid: get_profile_interface handsfree
,09-14 09:28:30.108  4046  4062 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-14 09:28:30.108  4046  4062 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-14 09:28:30.112   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-14 09:28:30.115   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-14 09:28:30.115   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-14 09:28:30.116   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-14 09:28:30.117  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:30.118  4046  4046 D A2dpService: Received start request. Starting profile...
,09-14 09:28:30.120  4046  4046 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-14 09:28:30.120  4046  4046 I bt_bluedroid: get_profile_interface avrcp
09-14 09:28:30.127  4046  4046 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-14 09:28:30.127  4046  4046 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-14 09:28:30.127  4046  4046 D A2dpStateMachine: make
,09-14 09:28:30.130  4046  4046 I bt_bluedroid: get_profile_interface a2dp
,09-14 09:28:30.130  4046  4062 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 09:28:30.132  4046  4080 D A2dpStateMachine: Enter Disconnected: -2
,09-14 09:28:30.133  4046  4046 I BluetoothHidServiceJni: classInitNative: succeeds
09-14 09:28:30.133  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:30.134  4046  4046 D HidService: Received start request. Starting profile...
09-14 09:28:30.134  4046  4046 I bt_bluedroid: get_profile_interface hidhost
09-14 09:28:30.134  4046  4046 D HidService: setHidService(): set to: null
,09-14 09:28:30.134  4046  4062 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39da3e5
09-14 09:28:30.134  4046  4062 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 09:28:30.134  4046  4046 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 09:28:30.135  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:30.135  4046  4046 D HealthService: Received start request. Starting profile...
,09-14 09:28:30.136  4046  4046 I bt_bluedroid: get_profile_interface health
,09-14 09:28:30.137  4046  4046 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-14 09:28:30.137  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:30.138  4046  4046 D PanService: Received start request. Starting profile...
,09-14 09:28:30.138  4046  4046 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 09:28:30.138  4046  4046 I bt_bluedroid: get_profile_interface pan
09-14 09:28:30.138  4046  4062 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-14 09:28:30.140  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
,09-14 09:28:30.140  4046  4046 D BluetoothMapService: Received start request. Starting profile...
09-14 09:28:30.140  4046  4046 D BluetoothMapService: start()
,09-14 09:28:30.145  4046  4046 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-14 09:28:30.146  4046  4046 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 09:28:30.146  4046  4046 D BluetoothMapAppObserver: createReceiver()
,09-14 09:28:30.147  4046  4046 D BluetoothMapAppObserver: initObservers()
09-14 09:28:30.147  4046  4046 D BluetoothMapAppObserver: getEnabledAccountItems()
09-14 09:28:30.153  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:30.153  4046  4046 V BluetoothAdapterState: isTurningOn()=true
,09-14 09:28:30.153  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 09:28:30.153  4046  4077 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-14 09:28:30.153  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:30.154  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-14 09:28:30.155  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-14 09:28:30.155  4046  4058 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-14 09:28:30.155  4046  4058 D BluetoothAdapterProperties: ScanMode =  20
09-14 09:28:30.156  4046  4058 D BluetoothAdapterProperties: State =  11
09-14 09:28:30.158  4046  4062 D BluetoothAdapterProperties: Scan Mode:21
09-14 09:28:30.158   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{cfe2df6 u0 android.bluetooth.adapter.action.SCAN_MODE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
,09-14 09:28:30.158  4046  4058 D BluetoothAdapterProperties: Setting state to 12
,09-14 09:28:30.158  4046  4062 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 09:28:30.158  4046  4058 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 09:28:30.158   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:28:30.158  4046  4058 I BluetoothAdapterState: Entering OnState
09-14 09:28:30.158  1357  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:28:30.159  1961  1986 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:28:30.159   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 09:28:30.159  1357  1368 D BluetoothPan: onBluetoothStateChange on: true
,09-14 09:28:30.160   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 09:28:30.161  1357  2331 D BluetoothMap: onBluetoothStateChange: up=true
,09-14 09:28:30.161  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 09:28:30.162   872   872 D BluetoothA2dp: Proxy object connected
09-14 09:28:30.162  1357  1357 D PanProfile: Bluetooth service connected
09-14 09:28:30.163  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 09:28:30.164  1357  1357 D BluetoothMap: Proxy object connected
09-14 09:28:30.164  1357  1357 D MapProfile: Bluetooth service connected
09-14 09:28:30.164  1357  1357 D BluetoothMap: getConnectedDevices()
09-14 09:28:30.164  1357  1374 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 09:28:30.165  1357  1357 D BluetoothA2dp: Proxy object connected
09-14 09:28:30.165  1357  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 09:28:30.166   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 09:28:30.167   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{840e90b u-1 android.bluetooth.adapter.action.STATE_CHANGED} to ReceiverList{8935021 3780 com.test.thalitest/10000/u0 remote:efd8e88}: process crashing
09-14 09:28:30.167   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 09:28:30.168  1357  1357 D BluetoothInputDevice: Proxy object connected
09-14 09:28:30.168  1357  1357 D HidProfile: Bluetooth service connected
09-14 09:28:30.168  4046  4046 D BluetoothMapService: onReceive
09-14 09:28:30.168  4046  4046 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 09:28:30.168  4046  4046 D BluetoothMapService: STATE_ON
,09-14 09:28:30.171  4046  4046 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 09:28:30.171  4046  4046 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-14 09:28:30.172  4046  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:30.174  4046  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:30.175  4046  4046 D ObexServerSockets: Succeed to create listening sockets 
,09-14 09:28:30.175  4046  4046 D ObexServerSockets0: startAccept()
09-14 09:28:30.175  4046  4046 D ObexServerSockets0: prepareForNewConnect()
,09-14 09:28:30.176  4046  4046 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-14 09:28:30.176  4046  4046 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 09:28:30.177  4046  4087 D ObexServerSockets0: Accepting socket connection...
09-14 09:28:30.177  4046  4088 D ObexServerSockets0: Accepting socket connection...
,09-14 09:28:30.189  4046  4046 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 09:28:30.189  4046  4046 D ObexServerSockets0: prepareForNewConnect()
,09-14 09:28:30.261  1961  1989 D BluetoothHeadset: Proxy object connected
,09-14 09:28:30.262   872   872 D BluetoothHeadset: Proxy object connected
09-14 09:28:30.263   872   872 D BluetoothHeadset: Proxy object connected
,09-14 09:28:30.263   872   872 D BluetoothHeadset: Proxy object connected
09-14 09:28:30.264  1357  2112 D BluetoothHeadset: Proxy object connected
,09-14 09:28:30.266  1357  1357 D HeadsetProfile: Bluetooth service connected
09-14 09:28:30.266   872   889 D BluetoothHeadset: Proxy object connected
,09-14 09:28:30.336   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-14 09:28:30.337   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-14 09:28:30.341   872  1337 D SurfaceControl: Excessive delay in setPowerMode(): 225ms
,09-14 09:28:30.344   872   892 I DreamManagerService: Entering dreamland.
,09-14 09:28:30.345   872   892 I PowerManagerService: Dozing...
,09-14 09:28:30.347   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-14 09:28:30.398  3780  4045 I art     : Waiting for a blocking GC DisableMovingGc
,09-14 09:28:30.405  3780  4045 I art     : WaitForGcToComplete blocked for 6.949ms for cause DisableMovingGc
,09-14 09:28:30.405  3780  4045 I art     : Starting a blocking GC DisableMovingGc
,09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:30.409  3780  4045 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:30.412  3780  4045 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:30.416  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:28:30.417   872  2214 D WifiService: setWifiEnabled: false pid=3780, uid=10000
,09-14 09:28:30.417   872  2214 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:28:30.418   375  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-14 09:28:30.418   375  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-14 09:28:30.426   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 09:28:30.432   872  2079 D WifiService: setWifiEnabled: false pid=3780, uid=10000
,09-14 09:28:30.432   872  2079 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:30.433   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 09:28:30.435   872  1310 E native  : do suspend false
,09-14 09:28:30.446  1954  4092 D NfcService: Discovery configuration equal, not updating.
,09-14 09:28:30.449   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 09:28:30.460  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 09:28:30.461   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-14 09:28:30.461   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 09:28:30.462   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 09:28:30.462   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:30.474   872  2115 D DhcpClient: Clearing IP address
,09-14 09:28:30.474   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-14 09:28:30.477   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:30.489   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 09:28:30.489   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-14 09:28:30.493   394   394 E Parcel  : Reading a NULL string not supported here.
,09-14 09:28:30.494   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-14 09:28:30.495   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 09:28:30.496   371   871 D CommandListener: Clearing all IP addresses on wlan0
09-14 09:28:30.498   872  4009 D DhcpClient: Receive thread stopped
,09-14 09:28:30.501   872  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-14 09:28:30.505   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 09:28:30.509   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{ae87e7e u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
,09-14 09:28:30.510   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{ae87e7e u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
09-14 09:28:30.512  1867  2304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-14 09:28:30.516   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 09:28:30.521   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-14 09:28:30.536   872  1310 E native  : do suspend true
,09-14 09:28:30.545   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 09:28:30.551   375  1319 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-14 09:28:30.552   375  1319 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-14 09:28:30.573   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 09:28:30.574   872  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 09:28:30.574   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:28:30.578   872   889 D Tethering: MasterInitialState.processMessage what=3,
09-14 09:28:30.578   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{efc6fdf u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
09-14 09:28:30.578   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{efc6fdf u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
,09-14 09:28:30.648   371   871 E Netd    : netlink response contains error (No such file or directory)
09-14 09:28:30.649   872  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:28:30.981  3780  4090 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:28:30.983  3780  4090 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:28:30.985  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 09:28:30.985   872   883 D WifiService: setWifiEnabled: true pid=3780, uid=10000
,09-14 09:28:30.985   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 09:28:30.989   872  2009 D WifiService: setWifiEnabled: true pid=3780, uid=10000
,09-14 09:28:30.989   872  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:30.994   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-14 09:28:31.000   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{10bc42c u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
,09-14 09:28:31.000   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{10bc42c u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
,09-14 09:28:31.020   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-14 09:28:31.021   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-14 09:28:31.022   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-14 09:28:31.023   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-14 09:28:31.023   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-14 09:28:31.024   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-14 09:28:31.024   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 09:28:31.036   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-14 09:28:31.037   371   871 D CommandListener: Setting iface cfg
09-14 09:28:31.037   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-14 09:28:31.038   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 09:28:31.041   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-14 09:28:31.041   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-14 09:28:31.045   872  1310 E native  : do suspend true
,09-14 09:28:31.068   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 09:28:31.542  3780  4105 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 09:28:31.550  3780  4105 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 09:28:31.553  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 09:28:31.553  3780  3829 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 09:28:31.554   872  2215 D WifiService: setWifiEnabled: true pid=3780, uid=10000
09-14 09:28:31.554   872  2215 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 09:28:31.560  3780  4106 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-14 09:28:31.560  3780  4106 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 09:28:31.922   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-14 09:28:32.026   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=2.94 rxSuccessRate=4.72 delta 1000 -> 1000
,09-14 09:28:32.029   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-14 09:28:32.030   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:32.047   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-14 09:28:32.101   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-14 09:28:32.106  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 09:28:32.109  3780  4106 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-14 09:28:32.110  3780  4106 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-14 09:28:32.110  3780  4106 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 09:28:32.110  3780  4106 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 09:28:32.111  3780  4106 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-14 09:28:32.111  3780  4108 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-14 09:28:32.112  3780  4108 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-14 09:28:32.112  3780  4108 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:28:32.112  3780  4108 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:28:32.112  3780  4108 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-14 09:28:32.113  3780  4112 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 485, name: OutgoingSocketThread/Receiver)
09-14 09:28:32.114  3780  4112 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 485, thread name: OutgoingSocketThread/Receiver)
09-14 09:28:32.114  3780  4112 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 09:28:32.114  3780  4112 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 485, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-14 09:28:32.116  3780  4113 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: IncomingSocketThread/Sender)
09-14 09:28:32.117  3780  4111 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 484, name: OutgoingSocketThread/Sender)
09-14 09:28:32.118  3780  4114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: IncomingSocketThread/Receiver)
09-14 09:28:32.119  3780  4114 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 487, thread name: IncomingSocketThread/Receiver)
09-14 09:28:32.119  3780  4114 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 09:28:32.119  3780  4114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-14 09:28:32.654  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-14 09:28:32.658  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-14 09:28:32.664  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@54bd05d Bundle[{}]
,09-14 09:28:32.664  3780  3829 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 09:28:32.665  3780  3829 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-14 09:28:32.666  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-14 09:28:32.666  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-14 09:28:32.667  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-14 09:28:32.668  3780  3829 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-14 09:28:32.675  3780  4115 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-14 09:28:32.675  3780  4115 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 09:28:32.853  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 09:28:32.909  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 09:28:32.911  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-14 09:28:32.921   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 09:28:32.937   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-14 09:28:32.937   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-14 09:28:32.937   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:32.954   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 09:28:32.966   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:32.967   872  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-14 09:28:32.974   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 09:28:33.020   872  4119 D DhcpClient: Receive thread started
,09-14 09:28:33.106   872  1310 E native  : do suspend false
,09-14 09:28:33.127   872  2115 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 09:28:33.142   872  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172795, domain null
,09-14 09:28:33.143   872  2115 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172795 seconds
,09-14 09:28:33.146   872  2115 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-14 09:28:33.169   872  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-14 09:28:33.170   872  2115 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-14 09:28:33.175   371   871 D CommandListener: Setting iface cfg
,09-14 09:28:33.186   872  2115 D DhcpClient: Scheduling renewal in 86399s
,09-14 09:28:33.187   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 09:28:33.192   872  1310 E native  : do suspend true
,09-14 09:28:33.215   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 09:28:33.217   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 09:28:33.218   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-14 09:28:33.220   872  1312 D ConnectivityService: Adding iface wlan0 to network 102
,09-14 09:28:33.224  3780  4120 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-14 09:28:33.224  3780  4120 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-14 09:28:33.224  3780  4120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:28:33.224  3780  4120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:28:33.225  3780  4120 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-14 09:28:33.229  3780  4124 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: IncomingSocketThread/Receiver)
,09-14 09:28:33.231  3780  4124 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 499, thread name: IncomingSocketThread/Receiver)
,09-14 09:28:33.231  3780  4124 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-14 09:28:33.234   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-14 09:28:33.238  3780  4123 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 498, name: IncomingSocketThread/Sender)
09-14 09:28:33.231  3780  4124 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-14 09:28:33.287   872  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-14 09:28:33.287   872  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-14 09:28:33.289   872  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-14 09:28:33.291   872  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-14 09:28:33.294  3780  4115 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-14 09:28:33.294  3780  4115 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-14 09:28:33.295  3780  4115 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:28:33.296  3780  4115 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 09:28:33.297  3780  4115 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-14 09:28:33.299   872  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-14 09:28:33.303  3780  4127 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: OutgoingSocketThread/Receiver)
,09-14 09:28:33.309  3780  4127 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 501, thread name: OutgoingSocketThread/Receiver)
09-14 09:28:33.309  3780  4127 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 09:28:33.309  3780  4127 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 501, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-14 09:28:33.311   872  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 09:28:33.311  3780  4126 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: OutgoingSocketThread/Sender)
,09-14 09:28:33.316   872  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-14 09:28:33.316   872  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-14 09:28:33.316   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-14 09:28:33.317   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 09:28:33.317   872  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-14 09:28:33.317   872  1312 D ConnectivityService:    accepting network in place of null
,09-14 09:28:33.319   872  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 09:28:33.346   872  4118 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 09:28:33.358   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 09:28:33.409   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 09:28:33.414   872  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-14 09:28:33.414   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 09:28:33.416   872  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-14 09:28:33.417   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{e64fe73 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{674927a 3780 com.test.thalitest/10000/u0 remote:1156ea5}: process crashing
09-14 09:28:33.418   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{e64fe73 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{3edaa0b 3780 com.test.thalitest/10000/u0 remote:46d5da}: process crashing
09-14 09:28:33.418   872   889 D Tethering: MasterInitialState.processMessage what=3
09-14 09:28:33.428   872  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-14 09:28:33.493   872  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 07:28:33 GMT], X-Android-Received-Millis=[1473838113492], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473838113467]}
,09-14 09:28:33.496   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-14 09:28:33.497   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-14 09:28:33.497   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 09:28:33.505   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 09:28:33.772  3780  3829 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 510)
,09-14 09:28:33.776  3780  3829 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-14 09:28:33.776  3780  3829 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 511)
,09-14 09:28:33.779  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 09:28:33.779  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@856b1b7 added. We now have 4 listener(s)
,09-14 09:28:33.782  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:28:33.782  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 09:28:33.782  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 09:28:33.782  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 09:28:33.782  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1999d24 added. We now have 4 listener(s)
09-14 09:28:33.782  3780  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 09:28:33.783  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 09:28:33.787  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:33.787   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{a9e905c u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{d6f832e 3780 com.test.thalitest/10000/u0 remote:71fa1a9}: process crashing
09-14 09:28:33.787   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{8a7af65 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{d6f832e 3780 com.test.thalitest/10000/u0 remote:71fa1a9}: process crashing
,09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 09:28:33.794  3780  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 09:28:33.796  3780  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 09:28:33.797  3780  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 09:28:33.802  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:33.802  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:33.802  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:33.802  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 09:28:33.802  3780  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@856b1b7 removed from the list
09-14 09:28:33.802  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:33.802  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1999d24 removed from the list
09-14 09:28:33.802  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:33.802  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:33.805  3780  3829 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-14 09:28:33.805  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-14 09:28:33.805  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-14 09:28:33.805  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-14 09:28:33.805  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 09:28:33.806  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:33.811  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:33.811  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-14 09:28:33.812  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-14 09:28:33.812  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:33.812  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:28:33.812  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:33.812  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 09:28:33.815   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{be8dce1 u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{80fc8eb 3780 com.test.thalitest/10000/u0 remote:3f4a43a}: process crashing
,09-14 09:28:33.815   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{c78ca06 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{80fc8eb 3780 com.test.thalitest/10000/u0 remote:3f4a43a}: process crashing
09-14 09:28:33.817  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 09:28:33.818  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 09:28:33.823  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 09:28:33.824  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 09:28:33.824  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:28:33.826  3780  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 09:28:33.831  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 09:28:33.833  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 09:28:33.833  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-14 09:28:33.833  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-14 09:28:33.834  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:33.834  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-14 09:28:33.834  3780  4134 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 09:28:33.835  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:33.842  4046  4057 D BtGatt.GattService: registerClient() - UUID=90e2bfb1-a430-4cf0-9e7b-173a0c0c9b9e
,09-14 09:28:33.844  4046  4062 D BtGatt.GattService: onClientRegistered() - UUID=90e2bfb1-a430-4cf0-9e7b-173a0c0c9b9e, clientIf=5
,09-14 09:28:33.845  3780  3792 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 09:28:33.850  4046  4064 D BtGatt.AdvertiseManager: message : 0
,09-14 09:28:33.854  4046  4064 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 09:28:33.872  4046  4062 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 09:28:33.886  4046  4062 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 09:28:33.888  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-14 09:28:33.889  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 09:28:33.891  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:34.416   872  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-14 09:28:35.258   872   885 W ActivityManager: Activity destroy timeout for ActivityRecord{ab6676a u0 com.test.thalitest/.MainActivity t4 f}
,09-14 09:28:36.141   872  1312 D ConnectivityService: handlePromptUnvalidated 101
,09-14 09:28:36.452  1867  2664 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-14 09:28:38.825  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:38.840  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:38.845  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 09:28:38.900  1501  2022 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-14 09:28:38.901  1501  2022 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-14 09:28:38.901  1501  2022 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 09:28:38.901  1501  2022 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-14 09:28:38.942  3522  3522 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-14 09:28:38.942  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-14 09:28:38.943  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-14 09:28:39.229  3780  4135 E io.jxcore.node.StartStopOperationHandlerTest: Discovery manager didn't start after 5s!
,09-14 09:28:40.458   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
,09-14 09:28:41.322   872  1312 D ConnectivityService: handlePromptUnvalidated 102
,09-14 09:28:42.272  3780  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 09:28:42.272  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 09:28:42.273  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 09:28:42.273  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:28:42.273  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:28:42.274  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 09:28:42.275  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:28:42.276  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:42.276  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 09:28:42.276  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:28:42.277  3780  4134 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-14 09:28:42.282  3780  4134 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 09:28:42.283  3780  4134 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-14 09:28:42.287  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:42.297  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:42.297  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:42.297  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 09:28:42.297  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@856b1b7 not in the list
09-14 09:28:42.297  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:42.297  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1999d24 not in the list
09-14 09:28:42.297  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:42.297  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:42.297  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:42.300  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 09:28:42.301  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 09:28:42.302  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 09:28:42.302  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 09:28:42.302  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 09:28:42.302  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 09:28:42.306   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{1999d24 u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{b0dc0b6 3780 com.test.thalitest/10000/u0 remote:51c051}: process crashing
09-14 09:28:42.307   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{a21108d u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{b0dc0b6 3780 com.test.thalitest/10000/u0 remote:51c051}: process crashing
,09-14 09:28:42.309  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 09:28:42.315  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-14 09:28:42.323  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-14 09:28:42.323  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 09:28:42.323  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 09:28:42.325  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-14 09:28:42.327  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:42.333  4046  4057 D BtGatt.GattService: registerClient() - UUID=cfa251ef-a87a-4036-ae13-3b74a78eb86f
09-14 09:28:42.334  4046  4062 D BtGatt.GattService: onClientRegistered() - UUID=cfa251ef-a87a-4036-ae13-3b74a78eb86f, clientIf=6
09-14 09:28:42.335  3780  3790 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-14 09:28:42.336  4046  4086 D BtGatt.GattService: start scan with filters
,09-14 09:28:42.343  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 09:28:42.343  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 09:28:42.343  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING, ADVERTISING]
09-14 09:28:42.344  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING, ADVERTISING]
,09-14 09:28:42.344  4046  4065 D BtGatt.ScanManager: handling starting scan
09-14 09:28:42.348  4046  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a12321
09-14 09:28:42.348  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,09-14 09:28:42.348  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 09:28:42.350  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:42.360  4046  4062 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-14 09:28:42.360  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-14 09:28:42.362  4046  4065 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 09:28:42.380  4046  4062 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-14 09:28:42.380  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-14 09:28:42.382  4046  4065 D BtGatt.ScanManager: Starting BLE batch scan
,09-14 09:28:42.382  4046  4065 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-14 09:28:42.418  4046  4062 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-14 09:28:42.418  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-14 09:28:42.440  4046  4062 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-14 09:28:42.441  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-14 09:28:42.687   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 16 -> obsolete
,09-14 09:28:45.392  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
09-14 09:28:45.393  3780  3829 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 09:28:45.393  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 09:28:45.393  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:45.394  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:28:45.394  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@856b1b7 not in the list
09-14 09:28:45.394  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:45.395  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 09:28:45.395  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 09:28:45.395  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-14 09:28:45.396  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 09:28:45.396  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 09:28:45.401  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:45.406  4046  4057 D BtGatt.GattService: stopScan() - queue size =1
,09-14 09:28:45.408  4046  4086 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-14 09:28:45.414  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 09:28:45.414  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 09:28:45.415  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 09:28:45.415  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,09-14 09:28:45.417  4046  4062 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-14 09:28:45.417  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-14 09:28:45.418  4046  4065 D BtGatt.ScanManager: stopping BLe Batch
09-14 09:28:45.416  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,09-14 09:28:45.427  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 09:28:45.427  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-14 09:28:45.428  4046  4064 D BtGatt.AdvertiseManager: message : 1
,09-14 09:28:45.429  4046  4064 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 09:28:45.434  4046  4062 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-14 09:28:45.434  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-14 09:28:45.435  4046  4065 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-14 09:28:45.448  4046  4062 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-14 09:28:45.448  4046  4062 D BtGatt.GattService: Client app is not null!
,09-14 09:28:45.450  4046  4056 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 09:28:45.451  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 09:28:45.451  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
09-14 09:28:45.451  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 09:28:45.451  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 09:28:45.451  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-14 09:28:45.453  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 09:28:45.453  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 09:28:45.453  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 09:28:45.454  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:45.456  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1999d24 not in the list
09-14 09:28:45.456  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:45.456  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:45.457  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 09:28:45.459  3780  3829 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-14 09:28:45.459  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-14 09:28:45.462  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:45.463  3780  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-14 09:28:45.463  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-14 09:28:45.463  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:45.464  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 09:28:45.465  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 09:28:45.466  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-14 09:28:45.466  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 09:28:45.466  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 09:28:45.466  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 09:28:45.466  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 09:28:45.470   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{31b2889 u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{29ab253 3780 com.test.thalitest/10000/u0 remote:d2d3242}: process crashing
09-14 09:28:45.471   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{be0308e u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{29ab253 3780 com.test.thalitest/10000/u0 remote:d2d3242}: process crashing
,09-14 09:28:45.473  3780  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 09:28:45.473  3780  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 09:28:45.480  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 09:28:45.481  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 09:28:45.481  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 09:28:45.487  3780  4139 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 09:28:45.487  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-14 09:28:45.488  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 09:28:45.488  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-14 09:28:45.488  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-14 09:28:45.488  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 09:28:45.488  3780  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-14 09:28:45.489  3780  4139 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 09:28:45.489  3780  3829 D BluetoothAdapter: STATE_ON
,09-14 09:28:45.493  4046  4086 D BtGatt.GattService: registerClient() - UUID=22e3f0fa-b4f9-4f08-96d5-1cd6d5a2f3f0
,09-14 09:28:45.493  4046  4062 D BtGatt.GattService: onClientRegistered() - UUID=22e3f0fa-b4f9-4f08-96d5-1cd6d5a2f3f0, clientIf=5
09-14 09:28:45.494  3780  3868 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-14 09:28:45.495  4046  4064 D BtGatt.AdvertiseManager: message : 0
,09-14 09:28:45.498  4046  4064 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 09:28:45.505  4046  4062 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
09-14 09:28:45.505  4046  4062 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-14 09:28:45.506  4046  4062 D BtGatt.GattService: current time is 166347523975
,09-14 09:28:45.507  4046  4062 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 87, 45, 110, 28, -13, -4, 1, -128, -61, 41, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0, 35, 97, 126, -92, 22, -56, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 09:28:45.508  4046  4062 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 09:28:45.509  4046  4062 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
09-14 09:28:45.509  4046  4062 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 09:28:45.509  4046  4062 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 09:28:45.509  4046  4062 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 09:28:45.509  4046  4062 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-14 09:28:45.517  4046  4062 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 09:28:45.524  4046  4062 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 09:28:45.524  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-14 09:28:45.525  3780  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 09:28:45.527  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 09:28:48.124   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 16 -> obsolete
,09-14 09:28:50.931  3780  4140 E io.jxcore.node.StartStopOperationHandlerTest: Discovery manager didn't start after 5s!
,09-14 09:28:53.977  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:53.977  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 09:28:53.977  3780  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 09:28:53.978  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-14 09:28:53.984  3780  4139 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 09:28:53.984  3780  4139 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-14 09:28:53.984  3780  4139 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-14 09:28:53.989  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:53.990  3780  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 09:28:53.994  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@856b1b7 not in the list
09-14 09:28:53.994  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 09:28:53.994  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1999d24 not in the list
09-14 09:28:53.994  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:53.995  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:53.995  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 09:28:53.997  3780  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 09:28:53.997  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 09:28:53.997  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:28:53.997  3780  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@856b1b7 not in the list
09-14 09:28:53.997  3780  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 09:28:53.997  3780  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1999d24 not in the list
,09-14 09:28:53.997  3780  3829 D io.jxcore.node.ConnectivityMonitor: stop
09-14 09:28:53.998  3780  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 09:28:53.998  3780  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 09:28:53.998  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-14 09:28:53.999  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 09:28:53.999  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-14 09:28:53.999  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 09:28:54.000  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 09:28:54.001  3780  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 09:28:54.009  3780  4142 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 531, name: My test thread name)
,09-14 09:28:56.048  3780  3829 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 531
09-14 09:28:56.049  3780  3829 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 531, name: My test thread name)
,09-14 09:28:56.057  3780  4143 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 532, name: My test thread name)
09-14 09:28:56.057  3780  4143 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 532, thread name: My test thread name)
,09-14 09:28:56.058  3780  4143 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 532, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-14 09:28:56.066  3780  3829 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 09:28:56.072  3780  4144 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 536, name: My test thread name)
09-14 09:28:56.072  3780  4144 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 536, thread name: My test thread name): Test exception.
09-14 09:28:56.073  3780  4144 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 536, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-14 09:28:56.074  3780  3829 E com.test.thalitest.ThaliTestRunner: testExecuteStopOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-14 09:28:56.074  3780  3829 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-14 09:28:56.074  3780  3829 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-14 09:28:56.074  3780  3829 E com.test.thalitest.ThaliTestRunner:      but: was <Stop operation: Should start/stop everything>
,09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mCurrentOperation should be null
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner:      but: was <Stop operation: Should start/stop everything>
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStopOperation(StartStopOperationHandlerTest.java:241)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-14 09:28:56.076  3,780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:77)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:81)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: testExecuteStartOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-14 09:28:56.076  3780  3829 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should start/stop everything>
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mCurrentOperation should be null
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should start/stop everything>
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStartOperation(StartStopOperationHandlerTest.java:194)
0,9-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-14 09:28:56.078  3780  3829 E com.tes,t.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:77)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:81)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:56.078  3780  3829 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-14 09:28:56.082  3780  3829 I jxcore-log: Total number of executed tests:  82
09-14 09:28:56.082  3780  3829 I jxcore-log: 
09-14 09:28:56.082  3780  3829 I jxcore-log: Number of passed tests:  80
09-14 09:28:56.082  3780  3829 I jxcore-log: 
09-14 09:28:56.082  3780  3829 I jxcore-log: Number of failed tests:  2
09-14 09:28:56.082  3780  3829 I jxcore-log: 
09-14 09:28:56.084  3780  3829 I jxcore-log: Number of ignored tests:  0
09-14 09:28:56.084  3780  3829 I jxcore-log: 
,09-14 09:28:56.085  3780  3829 I jxcore-log: Total duration:  34215
09-14 09:28:56.085  3780  3829 I jxcore-log: 
09-14 09:28:56.086  3780  3829 I jxcore-log: Failed to execute UT.
09-14 09:28:56.086  3780  3829 I jxcore-log: 
09-14 09:28:56.087  3780  3829 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-14 09:28:56.087  3780  3829 I jxcore-log: 
,09-14 09:28:56.091  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:28:56.091  3780  3829 I jxcore-log: 
09-14 09:28:56.092  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:28:56.092  3780  3829 I jxcore-log: 
09-14 09:28:56.093  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:28:56.093  3780  3829 I jxcore-log: 
09-14 09:28:56.094  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 09:28:56.094  3780  3829 I jxcore-log: 
09-14 09:28:56.096  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 09:28:56.096  3780  3829 I jxcore-log: 
09-14 09:28:56.098  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:28:56.098  3780  3829 I jxcore-log: 
,09-14 09:28:56.100  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 09:28:56.100  3780  3829 I jxcore-log: 
,09-14 09:28:56.101  3780  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 09:28:56.101  3780  3829 I jxcore-log: 
,09-14 09:28:56.158  3780  4142 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 531, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-14 09:28:56.717  4145  4145 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-14 09:28:56.722  4145  4145 D AndroidRuntime: CheckJNI is OFF
,09-14 09:28:56.757  4145  4145 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-14 09:28:56.798  4145  4145 I Radio-JNI: register_android_hardware_Radio DONE
,09-14 09:28:56.817  4145  4145 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-14 09:28:56.839   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-14 09:28:56.840   872   885 I ActivityManager: Killing 3780:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-14 09:28:56.932   872  2214 D GraphicsStats: Buffer count: 3
,09-14 09:28:56.942   872  1311 D WifiService: Client connection lost with reason: 4
09-14 09:28:56.932  4046  4076 D BtGatt.GattService: Binder is dead - unregistering client (5)!
,09-14 09:28:56.959   872   895 W PackageSettings: Skipping PackageSetting{cab364a com.example.hello/10273} due to missing metadata
,09-14 09:28:56.970   872   886 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,09-14 09:28:56.976   872  1400 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3780 uid 10000
,09-14 09:28:56.978  1895  1895 I Keyboard.Facilitator: onFinishInput()
,09-14 09:28:57.016  4046  4064 D BtGatt.AdvertiseManager: message : 1
,09-14 09:28:57.016  4046  4064 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 09:28:57.017  4046  4064 D BtGatt.AdvertiseManager: app died - unregistering client : 5
09-14 09:28:57.018  4046  4064 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 09:28:57.019   872   895 I art     : Starting a blocking GC Explicit
,09-14 09:28:57.025  4046  4062 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=255, status=0
,09-14 09:28:57.025  4046  4062 E BtGatt.ContextMap: Context not found for ID 255
,09-14 09:28:57.042   872   885 I ActivityManager: Start proc 4154:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-14 09:28:57.043   872   882 W ActivityManager: Spurious death for ProcessRecord{fb2c79a 0:com.test.thalitest/u0a0}, curProc for 3780: null
,09-14 09:28:57.075  4154  4154 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-14 09:28:57.093   872   895 I art     : Explicit concurrent mark sweep GC freed 75765(4MB) AllocSpace objects, 17(524KB) LOS objects, 33% free, 29MB/44MB, paused 1.471ms total 72.326ms
,09-14 09:28:57.116   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-14 09:28:57.118  4145  4145 I art     : System.exit called, status: 0
,09-14 09:28:57.119  4145  4145 I AndroidRuntime: VM exiting with result code 0.
,09-14 09:28:57.125   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-14 09:28:57.143  1895  1895 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-14 09:28:57.146  4046  4046 D BluetoothMapAppObserver: onReceive
,09-14 09:28:57.146  4046  4046 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-14 09:28:57.146   872  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-14 09:28:57.147  1867  2239 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-14 09:28:57.170  1895  4178 I Keyboard.Facilitator.DecoderInitializer: run()
,09-14 09:28:57.186  1961  1961 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-14 09:28:57.216   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-14 09:28:57.219  4154  4154 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-14 09:28:57.222  1895  4178 I Decoder : createOrResetDecoder
,09-14 09:28:57.238  1501  1501 I ConfigService: onCreate
,09-14 09:28:57.259   872  2214 I ActivityManager: Start proc 4187:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-14 09:28:57.263   872  1392 I ActivityManager: Killing 3661:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-14 09:28:57.275  1895  4178 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-14 09:28:57.302  1895  4178 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-14 09:28:57.305  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-14 09:28:57.305  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-14 09:28:57.307  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-14 09:28:57.307  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-14 09:28:57.309  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-14 09:28:57.309  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-14 09:28:57.309  1895  4178 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-14 09:28:57.309  1895  4178 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-14 09:28:57.309  1895  4178 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-14 09:28:57.310  1895  4178 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-14 09:28:57.310  1895  4178 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-14 09:28:57.310  1895  4178 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-14 09:28:57.332  4187  4187 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-14 09:28:57.342  4187  4187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 09:28:57.346   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d001b4e:true
,09-14 09:28:57.353  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 09:28:57.355  1357  1357 D BluetoothPbap: Proxy object connected
,09-14 09:28:57.355  1357  1357 D PbapServerProfile: Bluetooth service connected
09-14 09:28:57.356  1357  1357 D BluetoothPbap: Proxy object disconnected
,09-14 09:28:57.356  1357  1357 D PbapServerProfile: Bluetooth service disconnected
,09-14 09:28:57.358  4046  4200 E BluetoothPbapService: Error to create listening socket after 10 try
,09-14 09:28:57.385   872  2009 I ActivityManager: Start proc 4201:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-14 09:28:57.390  4187  4187 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-14 09:28:57.407  4187  4187 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-14 09:28:57.414  1982  2087 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-14 09:28:57.414   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-14 09:28:57.415   872   884 E PackageManager: Failed to write settings, restoring backup
09-14 09:28:57.415   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-14 09:28:57.415   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-14 09:28:57.415   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-14 09:28:57.415   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-14 09:28:57.415   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-14 09:28:57.415   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 09:28:57.415   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:57.415   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-14 09:28:57.420   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-14 09:28:57.420   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-14 09:28:57.420   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 09:28:57.420   872   885 E DropBoxManagerService: 	... 13 more
,09-14 09:28:57.425  4201  4201 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-14 09:28:57.428   872  2008 I ActivityManager: Start proc 4213:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-14 09:28:57.429  1982  2087 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-14 09:28:57.429  1982  2087 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1982
09-14 09:28:57.429  1982  2087 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:57.429  1982  2087 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 09:28:57.430   872  2079 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-14 09:28:57.433   872  4219 E DropBoxManagerService: Can't write: system_app_crash
09-14 09:28:57.433   872  4219 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 09:28:57.433   872  4219 E DropBoxManagerService: 	... 5 more
,09-14 09:28:57.433  1982  2087 I Process : Sending signal. PID: 1982 SIG: 9
,09-14 09:28:57.452  4187  4187 D LocalBluetoothProfileManager: Adding local MAP profile
,09-14 09:28:57.452  4187  4187 D BluetoothMap: Create BluetoothMap proxy object
,09-14 09:28:57.459  4187  4187 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-14 09:28:57.481  4187  4187 D DockEventReceiver: finishStartingService: stopping service
,09-14 09:28:57.484  4187  4187 D BluetoothA2dp: Proxy object connected
,09-14 09:28:57.487  4187  4187 D BluetoothInputDevice: Proxy object connected
,09-14 09:28:57.488  4187  4187 D HidProfile: Bluetooth service connected
,09-14 09:28:57.490  4187  4187 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 09:28:57.490  4187  4187 D PanProfile: Bluetooth service connected
09-14 09:28:57.491  4187  4187 D BluetoothMap: Proxy object connected
09-14 09:28:57.491  4187  4187 D MapProfile: Bluetooth service connected
09-14 09:28:57.491  4187  4187 D BluetoothMap: getConnectedDevices()
,09-14 09:28:57.495   872  1392 I ActivityManager: Killing 3677:com.android.musicfx/u0a18 (adj 15): empty #17
,09-14 09:28:57.514   872  2079 D GraphicsStats: Buffer count: 2
,09-14 09:28:57.514   872  2216 I WindowState: WIN DEATH: Window{848feb u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-14 09:28:57.519  4187  4198 D BluetoothHeadset: Proxy object connected
09-14 09:28:57.520  4187  4187 D HeadsetProfile: Bluetooth service connected
,09-14 09:28:57.544   872  2079 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1982) has died
,09-14 09:28:57.544   872  2079 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-14 09:28:57.546   872  2079 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-14 09:28:57.561   872   885 I ActivityManager: Start proc 4236:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-14 09:28:57.622  4236  4236 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 09:28:57.622  4236  4236 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 09:28:57.622  4236  4236 D AndroidRuntime: Shutting down VM
,09-14 09:28:57.628  4236  4236 E AndroidRuntime: FATAL EXCEPTION: main
09-14 09:28:57.628  4236  4236 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4236
09-14 09:28:57.628  4236  4236 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-14 09:28:57.628  4236  4236 E AndroidRuntime: 	... 10 more
09-14 09:28:57.630   872  2214 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-14 09:28:57.631  4236  4236 I Process : Sending signal. PID: 4236 SIG: 9
09-14 09:28:57.631   872  4249 E DropBoxManagerService: Can't write: system_app_crash
09-14 09:28:57.631   872  4249 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 09:28:57.631   872  4249 E DropBoxManagerService: 	... 5 more
09-14 09:28:57.659   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
