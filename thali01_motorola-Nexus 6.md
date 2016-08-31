#### Test 828946826925cd3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 17:06:48.225  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:06:48.238  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 17:06:48.242  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 17:06:48.322  1511  3093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 17:06:48.322  1511  3093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 17:06:48.322  1511  3093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 17:06:48.322  1511  3093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 17:06:48.371  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 17:06:48.372  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 17:06:48.376  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-31 17:06:48.817  3788  3788 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 17:06:48.822  3788  3788 D AndroidRuntime: CheckJNI is OFF
08-31 17:06:48.857  3788  3788 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 17:06:48.900  3788  3788 I Radio-JNI: register_android_hardware_Radio DONE
08-31 17:06:48.920  3788  3788 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 17:06:48.925   873  1988 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 17:06:48.967  2070  2449 W SearchService: Abort, client detached.
08-31 17:06:48.972  2070  2347 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@52cbeef
08-31 17:06:48.972  2070  2364 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-31 17:06:48.972  2070  2070 I HotwordDetector: Closing mic
08-31 17:06:48.973  3788  3788 D AndroidRuntime: Shutting down VM
08-31 17:06:48.994   873  1989 I ActivityManager: Start proc 3798:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 17:06:49.020   376  2366 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 17:06:49.022   376  2366 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 17:06:49.028   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 17:06:49.029  2070  2350 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-31 17:06:49.029  2070  2363 I MicroRecognitionRnrImpl: Detection finished
08-31 17:06:49.080  3798  3798 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 17:06:49.111  3798  3798 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 17:06:49.120  3798  3798 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1644-1648)
08-31 17:06:49.120  3798  3798 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:06:49.138  3798  3798 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bf458f7}
08-31 17:06:49.139  3798  3798 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:06:49.139  3798  3798 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 17:06:49.148  3798  3798 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 17:06:49.150  3798  3798 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 17:06:49.174  3798  3798 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 17:06:49.188  3798  3798 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 17:06:49.189  3798  3798 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 17:06:49.189  3798  3798 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 17:06:49.189  3798  3798 I Adreno  : Build Date                       : 10/20/15
08-31 17:06:49.189  3798  3798 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 17:06:49.189  3798  3798 I Adreno  : Local Branch                     : M14
08-31 17:06:49.189  3798  3798 I Adreno  : Remote Branch                    : 
08-31 17:06:49.189  3798  3798 I Adreno  : Remote Branch                    : 
08-31 17:06:49.189  3798  3798 I Adreno  : Reconstruct Branch               : 
,08-31 17:06:49.251   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fed6ded:true
,08-31 17:06:49.282  3798  3798 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 17:06:49.295  3798  3798 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 17:06:49.355  3798  3835 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 17:06:49.367  3798  3822 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 17:06:49.397  3798  3835 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 17:06:49.464   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +484ms
,08-31 17:06:49.470  1898  1898 I Keyboard.Facilitator: onFinishInput()
,08-31 17:06:49.525  3798  3798 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3798
,08-31 17:06:49.611  3798  3798 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 17:06:49.777  3798  3837 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1697908432
,08-31 17:06:49.789  3798  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 17:06:49.789  3798  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 17:06:49.789  3798  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 17:06:49.789  3798  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 17:06:49.789  3798  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 17:06:49.789  3798  3837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32e69a added. We now have 1 listener(s)
,08-31 17:06:49.796  3798  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 17:06:49.798  3798  3837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:06:49.799  3798  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 17:06:49.799  3798  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 17:06:49.803  3798  3837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4ac1 added. We now have 1 listener(s)
08-31 17:06:49.803  3798  3837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:06:49.809   873  1308 D WifiService: New client listening to asynchronous messages
,08-31 17:06:49.810  3798  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:06:49.810   873   883 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #17
08-31 17:06:49.810  3798  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 17:06:49.810  3798  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 17:06:49.810  3798  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 17:06:49.810  3798  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 17:06:49.849   873   883 I ActivityManager: Killing 3205:com.google.android.gm/u0a78 (adj 15): empty #18
,08-31 17:06:49.893  3798  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:49.895  3798  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-31 17:06:49.900  3798  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:49.900  3798  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:49.900  3798  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 17:06:49.900  3798  3837 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:49.901  3798  3837 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 17:06:49.996  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:49.999  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:50.002  3798  3798 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 17:06:50.047   873  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-31 17:06:50.681  3798  3847 W jxcore-log: Initializing JXcore engine
,08-31 17:06:50.681  3798  3847 W jxcore-log: JXcore engine is ready
,08-31 17:06:50.717  3847  3847 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8819 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 17:06:50.717  3847  3847 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10975]" dev="sockfs" ino=10975 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 17:06:50.717  3847  3847 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 17:06:50.717  3847  3847 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26781]" dev="sockfs" ino=26781 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 17:06:50.732  3798  3847 W jxcore-log: Starting JXcore engine
,08-31 17:06:50.810  3798  3847 W jxcore-log: Platform android
08-31 17:06:50.810  3798  3847 W jxcore-log: 
,08-31 17:06:50.811  3798  3847 W jxcore-log: Process ARCH arm
08-31 17:06:50.811  3798  3847 W jxcore-log: 
,08-31 17:06:51.026  3798  3847 I jxcore-log: JXcore Cordova bridge is ready!
08-31 17:06:51.026  3798  3847 I jxcore-log: 
08-31 17:06:51.027  3798  3847 W jxcore-log: JXcore engine is started
,08-31 17:06:51.034  3798  3837 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 17:06:51.039  3798  3798 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 17:06:54.063  3600  3854 I BooksSync: Starting books sync for 61035162, extras: ade
,08-31 17:06:54.074  3600  3855 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-31 17:06:54.084  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:06:54.086  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:06:54.120  1511  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 17:06:54.121  1511  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 17:06:54.121  1511  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 17:06:54.121  1511  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 17:06:54.164  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:06:54.165  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:06:54.190  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 17:06:54.190  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 17:06:54.190  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 17:06:54.190  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 17:06:54.205  3600  3855 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-31 17:06:54.206  3600  3854 E BooksSync: Soft error
08-31 17:06:54.206  3600  3854 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 17:06:54.206  3600  3854 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 17:06:54.206  3600  3854 E BooksSync: Sync error
08-31 17:06:54.206  3600  3854 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 17:06:54.206  3600  3854 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 17:06:54.206  3600  3854 I BooksSync: Finished books sync
,08-31 17:06:54.211   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125660, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 17:07:00.885  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 17:07:00.885  3798  3847 I jxcore-log: 
,08-31 17:07:00.888  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 17:07:00.888  3798  3847 I jxcore-log: 
,08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:00.901  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:00.908  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:00.910  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 17:07:00.910  3798  3847 I jxcore-log: 
,08-31 17:07:00.912  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 17:07:00.912  3798  3847 I jxcore-log: 
,08-31 17:07:01.413  3798  3847 D executeNativeTests: Running unit tests
,08-31 17:07:01.471  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 17:07:01.471  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db added. We now have 2 listener(s)
08-31 17:07:01.472  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:01.472  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:01.472  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:01.472  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:01.472  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 added. We now have 2 listener(s)
08-31 17:07:01.472  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:01.473  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:07:01.489  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:01.502  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:01.507  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:01.508  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:07:01.512  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 17:07:01.514  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 17:07:01.514  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:07:01.515  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.520  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.527  3798  3847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 17:07:01.529  3798  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 17:07:01.530  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 17:07:01.530  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 17:07:01.530  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 17:07:01.533  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:01.536  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-31 17:07:01.536  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.537  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 17:07:01.537  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.538  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:01.538  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 17:07:01.539  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db removed from the list
08-31 17:07:01.539  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:01.539  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 removed from the list
08-31 17:07:01.539  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:07:01.540  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.541  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:01.541  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.544  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:01.544  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.544  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.545  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
,08-31 17:07:01.549  3798  3847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 17:07:01.551  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:01.552  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.552  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.553  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.553  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.553  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.553  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
,08-31 17:07:01.554  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.554  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.554  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.554  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.554  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.555  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:01.555  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:01.558  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.558  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 17:07:01.558  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.558  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
,08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 17:07:01.574  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 17:07:01.575  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-31 17:07:01.576  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 17:07:01.576  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 17:07:01.576  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 17:07:01.576  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.576  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.576  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.576  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.576  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.576  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:01.576  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.576  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.577  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.577  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.577  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.577  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.577  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.577  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.578  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.578  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 17:07:01.578  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.578  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.579  3798  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 17:07:01.581  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:01.586  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:01.587  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:01.588  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:01.588  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:01.588  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 17:07:01.588  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:01.588  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:01.588  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:07:01.590  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.592  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 17:07:01.592  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 17:07:01.593  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.598  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:07:01.600  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 17:07:01.600  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:07:01.603  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 17:07:01.605  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 17:07:01.605  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 17:07:01.605  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 17:07:01.606  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 17:07:01.607  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:01.611  2674  2794 D BtGatt.GattService: registerClient() - UUID=32c85beb-7384-4c72-97a4-5711ff2ac30a
08-31 17:07:01.613  2674  2693 D BtGatt.GattService: onClientRegistered() - UUID=32c85beb-7384-4c72-97a4-5711ff2ac30a, clientIf=5
,08-31 17:07:01.614  3798  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 17:07:01.614  2674  2816 D BtGatt.GattService: start scan with filters
,08-31 17:07:01.617  2674  2696 D BtGatt.ScanManager: handling starting scan
,08-31 17:07:01.617  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 17:07:01.622  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:07:01.623  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:07:01.623  2674  2696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
08-31 17:07:01.623  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 17:07:01.627  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:07:01.628  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 17:07:01.628  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:07:01.630  2674  2693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 17:07:01.630  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.631  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 17:07:01.631  2674  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 17:07:01.634  3798  3847 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 17:07:01.637  2674  2693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 17:07:01.637  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:01.638  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:01.638  2674  2696 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:07:01.638  3798  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:07:01.638  2674  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 17:07:01.638  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.638  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 17:07:01.638  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:01.638  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:07:01.639  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 17:07:01.639  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 17:07:01.639  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 17:07:01.639  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 17:07:01.640  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:07:01.641  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 17:07:01.641  3798  3847 D BluetoothAdapter: STATE_ON
08-31 17:07:01.642  2674  2795 D BtGatt.GattService: stopScan() - queue size =1
08-31 17:07:01.643  2674  2794 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 17:07:01.643  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:07:01.643  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:07:01.644  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 17:07:01.644  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 17:07:01.644  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 17:07:01.645  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:07:01.645  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:07:01.646  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:07:01.646  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:07:01.646  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:01.648  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.648  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.648  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:01.648  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.648  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:01.648  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.648  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:07:01.648  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.648  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 17:07:01.649  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 17:07:01.649  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:01.649  3798  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 17:07:01.649  2674  2693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 17:07:01.649  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.650  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:01.655  2674  2693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 17:07:01.656  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:01.656  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:01.659  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:01.659  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:01.659  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 17:07:01.659  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:01.660  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:01.660  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:01.660  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:07:01.663  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 17:07:01.663  2674  2693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 17:07:01.663  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 17:07:01.664  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.663  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.664  2674  2696 D BtGatt.ScanManager: stopping BLe Batch
,08-31 17:07:01.667  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 17:07:01.667  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.668  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 17:07:01.668  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:07:01.671  2674  2693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 17:07:01.671  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.672  2674  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 17:07:01.672  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 17:07:01.672  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:07:01.672  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 17:07:01.673  3798  3847 D BluetoothAdapter: STATE_ON
08-31 17:07:01.676  2674  2794 D BtGatt.GattService: registerClient() - UUID=493dc83d-76cd-4644-9ba6-7dd41c8da42e
08-31 17:07:01.677  2674  2693 D BtGatt.GattService: onClientRegistered() - UUID=493dc83d-76cd-4644-9ba6-7dd41c8da42e, clientIf=5
08-31 17:07:01.677  2674  2693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 17:07:01.677  3798  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 17:07:01.677  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.678  2674  2795 D BtGatt.GattService: start scan with filters
,08-31 17:07:01.681  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 17:07:01.681  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 17:07:01.681  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:07:01.681  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 17:07:01.681  2674  2696 D BtGatt.ScanManager: handling starting scan
,08-31 17:07:01.684  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:07:01.684  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:07:01.685  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:07:01.686  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:07:01.687  2674  2693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 17:07:01.688  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:01.688  2674  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 17:07:01.689  3798  3847 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 17:07:01.691  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.692  3798  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:07:01.692  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.692  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 17:07:01.692  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.692  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 17:07:01.692  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:07:01.692  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:07:01.692  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:07:01.692  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 17:07:01.692  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:07:01.693  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 17:07:01.693  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:01.694  2674  2693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 17:07:01.694  2674  2816 D BtGatt.GattService: stopScan() - queue size =1
08-31 17:07:01.694  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.694  2674  2696 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:07:01.694  2674  2795 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 17:07:01.694  2674  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 17:07:01.695  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:01.695  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:07:01.695  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:07:01.695  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:07:01.696  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:07:01.696  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:01.697  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:07:01.697  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:07:01.697  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:07:01.697  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:01.698  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.698  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.698  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:01.698  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.698  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.699  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.699  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.699  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.699  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:01.699  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:01.699  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:01.699  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:01.699  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.700  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.700  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.700  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.700  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.701  3798  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 17:07:01.703  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:01.705  2674  2693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 17:07:01.705  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:01.708  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:01.710  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.710  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:07:01.711  2674  2693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 17:07:01.711  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:01.711  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:01.711  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:01.711  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:01.711  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:01.711  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:07:01.712  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.715  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.715  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 17:07:01.715  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:07:01.719  2674  2693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 17:07:01.720  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 17:07:01.720  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.720  2674  2696 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:07:01.720  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 17:07:01.720  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:07:01.724  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 17:07:01.724  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:07:01.724  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:07:01.725  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:01.727  2674  2693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 17:07:01.727  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.727  2674  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 17:07:01.728  2674  2816 D BtGatt.GattService: registerClient() - UUID=c4dbf8e2-28b3-4532-966d-8b37e9ac6235
,08-31 17:07:01.728  2674  2693 D BtGatt.GattService: onClientRegistered() - UUID=c4dbf8e2-28b3-4532-966d-8b37e9ac6235, clientIf=5
08-31 17:07:01.728  3798  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 17:07:01.729  2674  2685 D BtGatt.GattService: start scan with filters
,08-31 17:07:01.732  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 17:07:01.732  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:07:01.732  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:07:01.732  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:07:01.734  2674  2693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 17:07:01.734  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:01.736  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:07:01.736  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 17:07:01.736  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:07:01.737  2674  2696 D BtGatt.ScanManager: handling starting scan
,08-31 17:07:01.738  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:07:01.740  3798  3847 I io.jxcore.node.ConnectionHelper: start: OK
08-31 17:07:01.740  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.741  3798  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:07:01.741  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:07:01.741  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 17:07:01.741  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.741  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:07:01.742  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:07:01.742  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:07:01.742  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:07:01.742  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:07:01.742  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:07:01.742  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 17:07:01.743  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:01.743  2674  2693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 17:07:01.743  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.744  2674  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 17:07:01.744  2674  2816 D BtGatt.GattService: stopScan() - queue size =1
08-31 17:07:01.745  2674  2685 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 17:07:01.745  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:01.745  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 17:07:01.745  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:07:01.745  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:07:01.745  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 17:07:01.747  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:01.747  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:07:01.747  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:07:01.747  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:07:01.747  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:01.749  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:01.749  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.749  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:01.749  3798  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:07:01.749  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:07:01.749  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:07:01.749  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.749  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.749  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.749  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:01.749  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.750  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:01.750  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.750  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.750  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.750  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.750  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.750  2674  2693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 17:07:01.751  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.751  2674  2696 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:07:01.751  2674  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 17:07:01.752  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.752  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.752  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.752  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
,08-31 17:07:01.753  3798  3847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 17:07:01.754  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.754  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.754  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.754  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.754  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.754  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.754  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.754  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:01.754  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.754  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.754  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.755  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.755  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.755  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.756  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:01.756  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.759  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.759  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
,08-31 17:07:01.760  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 17:07:01.760  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.760  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.760  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:07:01.760  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.760  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.761  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.761  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.761  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.761  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.761  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.761  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:01.761  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.761  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.761  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.762  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.762  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.762  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:01.763  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.763  3798  3847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 17:07:01.763  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:01.764  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.764  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.764  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.764  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.764  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.764  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.764  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.764  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.764  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:07:01.764  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.764  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.764  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.765  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.766  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.766  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.766  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.766  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.766  2674  2693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 17:07:01.766  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:01.767  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 17:07:01.767  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:01.767  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.768  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.768  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.768  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.768  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.768  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.768  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.768  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.768  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.768  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.768  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:01.769  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.769  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.770  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.770  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.770  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.770  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.770  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:07:01.773  2674  2693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 17:07:01.773  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.773  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:07:01.773  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:07:01.774  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:07:01.775  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:07:01.775  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 17:07:01.775  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.775  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.775  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.775  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.776  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.776  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.776  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.776  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.776  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.776  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.776  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.776  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.776  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.776  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.779  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.779  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.779  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.779  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.779  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:07:01.780  3798  3847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 17:07:01.780  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 17:07:01.781  2674  2693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 17:07:01.781  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.782  2674  2696 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:07:01.783  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:07:01.783  3798  3847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 17:07:01.783  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 17:07:01.784  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 17:07:01.785  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 17:07:01.785  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 17:07:01.785  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 17:07:01.785  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 17:07:01.785  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 17:07:01.785  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 17:07:01.785  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 17:07:01.785  3798  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:07:01.786  3798  3847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 17:07:01.786  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:07:01.786  3798  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:07:01.786  3798  3847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 17:07:01.786  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:07:01.786  3798  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:07:01.786  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 17:07:01.788  2674  2693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 17:07:01.788  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.788  2674  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 17:07:01.789  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 17:07:01.790  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 17:07:01.790  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 17:07:01.791  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 17:07:01.791  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 17:07:01.791  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 17:07:01.792  3798  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:07:01.793  3798  3847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 17:07:01.793  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.793  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.793  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.793  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.793  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.794  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.794  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 17:07:01.794  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
,08-31 17:07:01.794  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.794  2674  2693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 17:07:01.794  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.794  2674  2693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:01.794  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.794  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.795  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.795  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.795  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.795  3798  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-31 17:07:01.795  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.796  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.796  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.796  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.796  3798  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-31 17:07:01.796  3798  3847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 17:07:01.797  3798  3860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:01.797  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.797  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.797  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.797  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.797  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.798  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.798  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.798  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.798  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.798  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.798  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.798  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.798  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.798  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.799  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.799  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.799  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.799  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.800  3798  3847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 17:07:01.800  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.800  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.800  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.801  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.801  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.801  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.801  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.801  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.801  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.801  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.801  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.801  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.801  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.801  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.802  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.802  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.802  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.802  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.803  3798  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 17:07:01.803  3798  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 17:07:01.803  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:07:01.803  3798  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 17:07:01.803  3798  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 17:07:01.803  3798  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 17:07:01.804  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:07:01.804  3798  3847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 17:07:01.804  3798  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 17:07:01.804  3798  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 17:07:01.804  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:07:01.804  3798  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 17:07:01.804  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.804  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.804  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.804  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.804  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.804  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.805  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.805  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.805  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.805  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.805  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.805  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.805  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.805  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.806  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.806  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.806  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.806  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.806  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.807  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.807  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.807  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.807  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.807  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.807  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.807  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.807  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.807  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.807  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.807  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.807  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.807  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.807  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.808  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.808  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.808  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.808  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.808  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.808  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.808  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.808  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.808  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
,08-31 17:07:01.808  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.808  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.808  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.809  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.809  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.809  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.809  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.809  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.810  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.811  3798  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 17:07:01.811  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:01.812  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 17:07:01.812  3798  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 17:07:01.812  3798  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 17:07:01.813  3798  3798 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 17:07:01.813  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 17:07:01.813  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:07:01.813  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.813  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 17:07:01.813  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 17:07:01.813  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 17:07:01.813  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.813  3798  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 17:07:01.814  3798  3798 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 17:07:01.814  3798  3862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:01.814  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.814  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.814  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:07:01.814  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:07:01.814  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:07:01.814  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.814  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.815  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:01.815  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:01.815  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:01.815  3798  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 17:07:01.815  3798  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 17:07:01.816  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:01.816  3798  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 17:07:01.816  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.816  3798  3798 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 17:07:01.816  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.816  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.816  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.816  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.816  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.816  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.817  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.817  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.817  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.817  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.817  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.817  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.817  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.817  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.818  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.818  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.818  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.818  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.819  3798  3847 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 17:07:01.820  3798  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 17:07:01.820  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:07:01.820  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:07:01.820  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.820  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.820  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.820  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.820  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.820  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.820  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.820  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.821  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.821  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.821  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.821  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.821  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.821  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.822  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.822  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.823  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.823  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.826  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.826  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.826  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.826  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.826  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.826  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.827  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.827  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.827  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.827  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.827  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.827  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.827  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.827  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.828  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.828  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.828  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.828  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.828  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:01.828  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:01.829  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:01.829  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:01.829  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.829  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.829  3798  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b19db not in the list
08-31 17:07:01.829  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.829  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.829  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:01.829  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.829  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.829  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:01.829  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:01.830  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:01.830  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:01.830  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:01.830  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cec78 not in the list
08-31 17:07:01.831  3798  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 17:07:01.831  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:07:01.831  3798  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 17:07:01.831  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:07:01.831  3798  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 17:07:01.831  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:07:01.833  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 17:07:01.833  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 17:07:01.834  3798  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 17:07:01.834  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 17:07:01.834  3798  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 17:07:01.834  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 17:07:01.834  3798  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 17:07:01.834  3798  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 17:07:01.835  3798  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 17:07:01.835  3798  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 17:07:01.835  3798  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 17:07:01.835  3798  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 17:07:01.835  3798  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 17:07:01.836  3798  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 17:07:01.836  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:01.836  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c6da9a added. We now have 2 listener(s)
08-31 17:07:01.837  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:01.839  3798  3847 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 17:07:01.839   873  2021 D WifiService: setWifiEnabled: true pid=3798, uid=10000
08-31 17:07:01.839   873  2021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 17:07:01.840  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:01.840  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@622fcb added. We now have 3 listener(s)
08-31 17:07:01.840  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:01.846  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:01.846  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66063a8 added. We now have 4 listener(s)
08-31 17:07:01.846  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:01.848  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:01.848  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@157cec1 added. We now have 5 listener(s)
08-31 17:07:01.848  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:01.851   873  1692 D WifiService: setWifiEnabled: false pid=3798, uid=10000
08-31 17:07:01.851   873  1692 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:01.855  2674  2689 D BluetoothAdapterState: Current state: ON, message: 23
08-31 17:07:01.855  2674  2689 D BluetoothAdapterProperties: Setting state to 13
08-31 17:07:01.855  2674  2689 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 17:07:01.856  2674  2689 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 17:07:01.857  2674  2689 I BluetoothAdapterState: Entering PendingCommandState
08-31 17:07:01.859  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:01.860  2674  2674 D BluetoothMapService: onReceive
,08-31 17:07:01.860  2674  2674 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:01.860  2674  2674 D BluetoothMapService: STATE_TURNING_OFF
08-31 17:07:01.860  2674  2674 D BluetoothMapService: MAP Service closeService in
08-31 17:07:01.860  2674  2674 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 17:07:01.860  2674  2674 D ObexServerSockets0: shutdown(block = true)
08-31 17:07:01.861  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 17:07:01.861  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 17:07:01.861  2674  2818 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 17:07:01.862  2674  2819 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 17:07:01.862  2674  2791 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 17:07:01.862  2674  2674 I BtOppRfcommListener: stopping Accept Thread
08-31 17:07:01.863  2674  3434 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:07:01.863  2674  3434 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 17:07:01.864  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 17:07:01.865   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 17:07:01.865   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 17:07:01.864  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:01.866   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 17:07:01.866   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:01.866  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:01.867  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:01.867  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.867  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:07:01.870  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.873  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.876  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:01.876  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:01.876  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:01.876  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:01.877   873  1864 D DhcpClient: Clearing IP address
08-31 17:07:01.878   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:07:01.881  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.883  1511  2432 V NativeCrypto: Read error: ssl=0xaecc6600: I/O error during system call, Connection timed out
,08-31 17:07:01.883   873   886 I ActivityManager: Start proc 3865:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-31 17:07:01.884   372   871 D CommandListener: Setting iface cfg
,08-31 17:07:01.885  2674  2693 D BluetoothAdapterProperties: Scan Mode:20
,08-31 17:07:01.885  2674  2689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 17:07:01.885  1511  2432 V NativeCrypto: SSL shutdown failed: ssl=0xaecc6600: I/O error during system call, Broken pipe
08-31 17:07:01.887   873  1386 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-31 17:07:01.888   873  1857 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-31 17:07:01.889  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.891  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.892  2674  2674 D HeadsetService: Received stop request...Stopping profile...
08-31 17:07:01.893   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 17:07:01.893   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-31 17:07:01.897   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-31 17:07:01.898   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-31 17:07:01.899   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 17:07:01.904  1367  2113 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:01.904   395   395 E Parcel  : Reading a NULL string not supported here.
08-31 17:07:01.904   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:01.904   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:01.904   873   873 D BluetoothHeadset: Proxy object disconnected
,08-31 17:07:01.904  1975  2296 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:01.904   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:07:01.906  2674  2674 D A2dpService: Received stop request...Stopping profile...
08-31 17:07:01.906  2674  2810 D A2dpStateMachine: Exit Disconnected: -1
08-31 17:07:01.907  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-31 17:07:01.908  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-31 17:07:01.909  2674  2674 D HidService: Received stop request...Stopping profile...
08-31 17:07:01.909  2674  2674 D HidService: Stopping Bluetooth HidService
08-31 17:07:01.909   873   873 D BluetoothA2dp: Proxy object disconnected
,08-31 17:07:01.912   873  1870 D DhcpClient: Receive thread stopped
08-31 17:07:01.913   873  1857 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-31 17:07:01.917  2674  2674 D HealthService: Received stop request...Stopping profile...
,08-31 17:07:01.918  2674  2674 D PanService: Received stop request...Stopping profile...
,08-31 17:07:01.918   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 17:07:01.919  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:01.919  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:01.920  2674  2674 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 17:07:01.920  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:01.920  2674  2674 D BluetoothMapService: stop()
08-31 17:07:01.920  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:01.920  2674  2674 D BluetoothMapAppObserver: deinitObservers()
08-31 17:07:01.920  2674  2674 D BluetoothMapAppObserver: removeReceiver()
08-31 17:07:01.921  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:01.921  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:01.921  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:01.921  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 17:07:01.922  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:01.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:01.922  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:01.922  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:01.922  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 17:07:01.923  2674  2693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 17:07:01.923  2674  2770 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:01.923  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:07:01.923  2674  2770 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:01.923  2674  2770 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:01.923  2674  2693 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 17:07:01.923  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:01.923  1869  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:01.923  2674  2674 V BluetoothAdapterState: isTurningOn()=false
,08-31 17:07:01.924  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 17:07:01.924  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:01.925  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 17:07:01.925  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:01.925  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 17:07:01.925  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 17:07:01.926  2674  2693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 17:07:01.926  2674  2770 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:01.926  2674  2693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 17:07:01.926  2674  2770 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:01.926  2674  2693 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 17:07:01.926  2674  2770 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:07:01.926  2674  2770 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:01.926  2674  2770 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 17:07:01.926  2674  2770 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:01.926  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:07:01.926   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 17:07:01.926  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:01.926  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:01.927  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:01.927  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:01.927  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 17:07:01.927  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 17:07:01.932  1367  1367 D BluetoothInputDevice: Proxy object disconnected
,08-31 17:07:01.932  1367  1367 D HidProfile: Bluetooth service disconnected
08-31 17:07:01.933  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 17:07:01.933  1367  1367 D PanProfile: Bluetooth service disconnected
08-31 17:07:01.933  1367  1367 D BluetoothMap: Proxy object disconnected
08-31 17:07:01.933  1367  1367 D MapProfile: Bluetooth service disconnected
08-31 17:07:01.936  2674  2674 D BluetoothMapService: MAP Service closeService in
08-31 17:07:01.936  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:01.936  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:01.936  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:01.936  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 17:07:01.936  2674  2689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 17:07:01.936  2674  2689 D BluetoothAdapterProperties: Setting state to 15
08-31 17:07:01.936  2674  2689 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 17:07:01.937  2674  2689 I BluetoothAdapterState: Entering BleOnState
08-31 17:07:01.937  1367  2113 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:01.937  2674  2674 D BluetoothMapService: cleanup()
08-31 17:07:01.937  2674  2674 D BluetoothMapService: MAP Service closeService in
,08-31 17:07:01.937  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 17:07:01.938   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:01.938  1367  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-31 17:07:01.939  1367  2113 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:01.939   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:01.939  1975  1986 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 17:07:01.940  1367  1379 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 17:07:01.944  1367  2113 D BluetoothPan: onBluetoothStateChange on: false
08-31 17:07:01.944   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:01.945   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:01.945  2674  2689 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 17:07:01.945  2674  2689 D BluetoothAdapterProperties: Setting state to 16
08-31 17:07:01.945  2674  2689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 17:07:01.946  2674  2689 D BluetoothAdapterProperties: onBleDisable
08-31 17:07:01.946  2674  2689 I BluetoothAdapterState: Entering PendingCommandState
08-31 17:07:01.946  2674  2690 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 17:07:01.948  2674  2770 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 17:07:01.948  2674  2770 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:01.948  3798  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-31 17:07:01.950  2674  2693 D BluetoothAdapterProperties: Scan Mode:20
,08-31 17:07:01.952  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.953  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.954  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.955  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.955   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:01.969  3865  3865 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-31 17:07:01.975   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:01.976   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 17:07:01.976   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:01.978   873   890 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:01.980  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.982  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.982  3380  3380 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c4c5f8e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-31 17:07:01.988  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:07:01.993  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:01.995   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a659e60:true
,08-31 17:07:02.006   873  1692 I ActivityManager: Start proc 3885:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 17:07:02.015  3865  3865 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 17:07:02.026   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-31 17:07:02.027   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 17:07:02.027   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 17:07:02.030  3865  3865 D BluetoothMap: Create BluetoothMap proxy object
,08-31 17:07:02.045  3865  3865 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 17:07:02.050  3885  3885 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 17:07:02.060  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:07:02.073   873  2135 I ActivityManager: Killing 3380:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 17:07:02.152  2674  2693 I bt_hci  : shut_down
,08-31 17:07:02.152  2674  2697 D bt_hwcfg: hw_epilog_process
,08-31 17:07:02.153  2674  2697 I bt_vendor: low_power_mode_cb
,08-31 17:07:02.176  2674  2697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 17:07:02.176  2674  2697 I bt_vendor: epilog_cb
08-31 17:07:02.177  2674  2697 I bt_hci  : epilog_finished_callback
,08-31 17:07:02.180  2674  2693 I bt_hci_h4: hal_close
,08-31 17:07:02.181  2674  2693 I bt_userial_vendor: device fd = 51 close
,08-31 17:07:02.259  3885  3885 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 17:07:02.259  3885  3885 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 17:07:02.259  3885  3885 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:02.259  3885  3885 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 17:07:02.259  388,5  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:02.259  3885  3885 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:0,7:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:02.259  3885  3885 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.259  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:02.260  3885  3885 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:02.260  3885  3885 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:02.260  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:02.289   873  2138 I ActivityManager: Start proc 3915:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-31 17:07:02.290   873  2138 I ActivityManager: Killing 3567:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-31 17:07:02.316  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:07:02.346  2674  2690 D bt_stack_manager: event_shut_down_stack finished.
,08-31 17:07:02.346  2674  2689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 17:07:02.352  2674  2674 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 17:07:02.352  2674  2674 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 17:07:02.352  2674  2674 D BtGatt.GattService: stop()
08-31 17:07:02.352  2674  2689 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-31 17:07:02.352  2674  2674 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 17:07:02.354  2674  2674 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:02.354  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:02.354  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:02.354  2674  2674 V BluetoothAdapterState: isBleTurningOff()=true
08-31 17:07:02.354  2674  2689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 17:07:02.355  2674  2689 D BluetoothAdapterProperties: Setting state to 10
08-31 17:07:02.355  2674  2689 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 17:07:02.356  2674  2689 I BluetoothAdapterState: Entering OffState
,08-31 17:07:02.357   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 17:07:02.361  3915  3915 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 17:07:02.368  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-31 17:07:02.368  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-31 17:07:02.368  2674  2674 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 17:07:02.370  2674  2690 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 17:07:02.372  2674  2690 D bt_stack_manager: event_clean_up_stack finished.
,08-31 17:07:02.373  2674  2674 I art     : System.exit called, status: 0
,08-31 17:07:02.374  2674  2674 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 17:07:02.421   873  2011 I ActivityManager: Process com.android.bluetooth (pid 2674) has died
,08-31 17:07:02.456  3915  3915 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 17:07:02.476   873  1385 I ActivityManager: Killing 3447:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 17:07:02.534  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:07:02.564   873  1386 I ActivityManager: Start proc 3944:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-31 17:07:02.568  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:07:02.634  3885  3910 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 17:07:02.675  3944  3944 D AdapterServiceConfig: Adding HeadsetService
08-31 17:07:02.676  3944  3944 D AdapterServiceConfig: Adding A2dpService
08-31 17:07:02.676  3944  3944 D AdapterServiceConfig: Adding HidService
08-31 17:07:02.676  3944  3944 D AdapterServiceConfig: Adding HealthService
08-31 17:07:02.676  3944  3944 D AdapterServiceConfig: Adding PanService
08-31 17:07:02.676  3944  3944 D AdapterServiceConfig: Adding GattService
08-31 17:07:02.677  3944  3944 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 17:07:02.680  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:02.697   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e31e7f2:true
,08-31 17:07:02.704  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 17:07:02.707  1698  1698 D SystemUpdateService: onCreate
,08-31 17:07:02.710  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 17:07:02.713  1698  3958 I SystemUpdateService: active receiver: enabled
,08-31 17:07:02.716  1698  3958 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 17:07:02.718  1698  3958 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 17:07:02.719  1698  3958 I SystemUpdateService: now status is 0 (complete)
08-31 17:07:02.719  1698  3958 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 17:07:02.719  1698  3958 I SystemUpdateService: file has been verified
08-31 17:07:02.719  1698  3958 I SystemUpdateService: OTA package size = 12249756
,08-31 17:07:02.720  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 17:07:02.721  1698  2408 I iu.UploadsManager: num queued entries: 0
08-31 17:07:02.722  1698  2408 I iu.UploadsManager: num updated entries: 0
,08-31 17:07:02.724  1698  2408 I iu.SyncManager: NEXT; no task
,08-31 17:07:02.724  1698  3958 I SystemUpdateService: showing system update notification
,08-31 17:07:02.742  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 17:07:02.743  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-31 17:07:02.743  1698  1698 D SystemUpdateService: onDestroy
,08-31 17:07:02.758   873  1989 I ActivityManager: Start proc 3960:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 17:07:02.785  3960  3960 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 17:07:02.788  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:02.797  3960  3960 D SprintDMHelper: simOperator: 
08-31 17:07:02.797  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 17:07:02.816   873  1386 I ActivityManager: Start proc 3972:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 17:07:02.817   873  1386 I ActivityManager: Killing 3496:android.process.acore/u0a5 (adj 15): empty #17
,08-31 17:07:02.995   873  1385 I ActivityManager: Start proc 3987:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 17:07:02.999   873  1385 I ActivityManager: Killing 3675:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 17:07:03.065  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 17:07:03.128  3987  3987 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 17:07:03.128  3987  3987 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 17:07:03.128  3987  3987 I GAv4    :   adb logcat -s GAv4
,08-31 17:07:03.148  3987  3987 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 17:07:03.155  3987  3987 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 17:07:03.180  3987  4004 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 17:07:03.304  3987  3987 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 17:07:03.342  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 17:07:03.354  3987  3987 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5879-5882)
,08-31 17:07:03.354  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 17:07:03.366  3987  3987 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a6abdbb}
08-31 17:07:03.367  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:07:03.367  3987  3987 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 17:07:03.376  3987  3987 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 17:07:03.377  3987  3987 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 17:07:03.397  3987  3987 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 17:07:03.412  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 17:07:03.412  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 17:07:03.413  3987  3987 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 17:07:03.413  3987  3987 I Adreno  : Build Date                       : 10/20/15
08-31 17:07:03.413  3987  3987 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 17:07:03.413  3987  3987 I Adreno  : Local Branch                     : M14
08-31 17:07:03.413  3987  3987 I Adreno  : Remote Branch                    : 
08-31 17:07:03.413  3987  3987 I Adreno  : Remote Branch                    : 
08-31 17:07:03.413  3987  3987 I Adreno  : Reconstruct Branch               : 
,08-31 17:07:03.487  3987  4033 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 17:07:03.495  3987  3987 I NSApplication: Starting up...
,08-31 17:07:03.541   873  2129 I ActivityManager: Start proc 4038:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 17:07:03.543   873  2129 I ActivityManager: Killing 3692:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 17:07:03.611  4038  4038 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 17:07:03.797   873  2136 I ActivityManager: Killing 2092:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 17:07:04.869   873  2136 D WifiService: setWifiEnabled: true pid=3798, uid=10000
,08-31 17:07:04.870   873  2136 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:04.884   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-31 17:07:04.893  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:04.893  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:04.893  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.894  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:04.897  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:04.897  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:04.897  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.898  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:04.938   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-31 17:07:04.941   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 17:07:04.943   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 17:07:04.946   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 17:07:04.946   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 17:07:04.946   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 17:07:04.946   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 17:07:04.968   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=13.12 delta 1000 -> 994
,08-31 17:07:04.968   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 17:07:04.971   372   871 D CommandListener: Setting iface cfg
,08-31 17:07:04.973   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
08-31 17:07:04.973   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 17:07:04.977   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-31 17:07:04.977   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:07:04.988   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 17:07:05.023   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 17:07:05.024   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 17:07:05.067   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 17:07:05.069  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 17:07:05.520  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 17:07:05.562  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 17:07:05.563  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 17:07:05.567   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 17:07:05.576   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 17:07:05.576   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:05.576   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 17:07:05.597   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:07:05.609   372   871 D CommandListener: Setting iface cfg
08-31 17:07:05.609   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-31 17:07:05.634   873  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 17:07:05.638   873  4061 D DhcpClient: Receive thread started
,08-31 17:07:05.642   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 17:07:05.732   873  1307 E native  : do suspend false
,08-31 17:07:05.756   873  1864 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 17:07:05.775   873  4061 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,08-31 17:07:05.776   873  1864 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,08-31 17:07:05.780   873  1864 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 17:07:05.796   873  4061 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 17:07:05.797   873  1864 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 17:07:05.802   372   871 D CommandListener: Setting iface cfg
,08-31 17:07:05.814   873  1864 D DhcpClient: Scheduling renewal in 86399s
,08-31 17:07:05.815   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 17:07:05.837   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 17:07:05.842   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 17:07:05.842   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 17:07:05.845   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 17:07:05.848   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 17:07:05.872   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 17:07:05.896   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 17:07:05.896   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-31 17:07:05.898   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-31 17:07:05.899   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 17:07:05.900   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 17:07:05.904   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:05.908   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-31 17:07:05.909   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-31 17:07:05.909   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:05.909   873  1309 D ConnectivityService:    accepting network in place of null
08-31 17:07:05.911   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 17:07:05.918   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 17:07:05.918   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 17:07:05.920   873  4060 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138448, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 17:07:05.933   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:05.952   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:05.958   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 17:07:05.959   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:05.961   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 17:07:05.962   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-31 17:07:05.976  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:05.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:05.977  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:05.977  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:05.979  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:05.979  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:05.979  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:05.980  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:05.982  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 17:07:05.984  1698  1698 D SystemUpdateService: onCreate
,08-31 17:07:05.987  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-31 17:07:05.988   873  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.198.142,2a00:1450:400d:807::200e
,08-31 17:07:05.989  1698  4071 I SystemUpdateService: active receiver: enabled
,08-31 17:07:05.994  1698  4071 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 17:07:06.000  1698  4071 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 17:07:06.000  1698  4071 I SystemUpdateService: now status is 0 (complete)
,08-31 17:07:06.000  1698  4071 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 17:07:06.001  1698  4071 I SystemUpdateService: file has been verified
,08-31 17:07:06.003  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 17:07:06.004  1698  2408 I iu.UploadsManager: num queued entries: 0
08-31 17:07:06.005  1698  2408 I iu.UploadsManager: num updated entries: 0
08-31 17:07:06.006  1698  4071 I SystemUpdateService: OTA package size = 12249756
08-31 17:07:06.006  1698  2408 I iu.SyncManager: NEXT; no task
,08-31 17:07:06.012  1698  4071 I SystemUpdateService: showing system update notification
08-31 17:07:06.014  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 17:07:06.015  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 17:07:06.017  1698  4075 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 17:07:06.017  1698  4075 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 17:07:06.017  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:06.018  1698  4075 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 17:07:06.021  3960  3960 D SprintDMHelper: simOperator: 
,08-31 17:07:06.021  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 17:07:06.029  1698  1698 D SystemUpdateService: onDestroy
,08-31 17:07:06.034  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:06.035  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:06.055   873  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 15:07:06 GMT], X-Android-Received-Millis=[1472656026055], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472656026030]}
,08-31 17:07:06.056   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 17:07:06.056   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-31 17:07:06.056   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 17:07:06.059   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 17:07:06.065  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 17:07:06.066  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 17:07:06.066  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 17:07:06.066  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 17:07:06.082  1698  4075 E MDM     : [172] SitrepService.a: Error sending sitrep.
,08-31 17:07:06.142  2246  4077 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 17:07:06.958   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 17:07:07.720   873  2137 I ActivityManager: Killing 3714:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 17:07:07.876   873  1989 D WifiService: setWifiEnabled: false pid=3798, uid=10000
,08-31 17:07:07.876   873  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:07.898  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 17:07:07.901   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 17:07:07.902   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 17:07:07.902   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 17:07:07.902   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:07:07.928   873  1864 D DhcpClient: Clearing IP address
,08-31 17:07:07.928   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:07:07.933   372   871 D CommandListener: Setting iface cfg
,08-31 17:07:07.936   873  4061 D DhcpClient: Receive thread stopped
,08-31 17:07:07.938  1511  4083 V NativeCrypto: Read error: ssl=0x9a974e00: I/O error during system call, Connection timed out
,08-31 17:07:07.940  1511  4083 V NativeCrypto: SSL shutdown failed: ssl=0x9a974e00: I/O error during system call, Broken pipe
,08-31 17:07:07.942   873  2011 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-31 17:07:07.942   873  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-31 17:07:07.942   873  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.198.142,2a00:1450:400d:807::200e
,08-31 17:07:07.948   873  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:807::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-31 17:07:07.949   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-31 17:07:07.950   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:07.952   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 17:07:07.959   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 17:07:07.959   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-31 17:07:07.960   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-31 17:07:07.961   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 17:07:07.963   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:07:07.969   395   395 E Parcel  : Reading a NULL string not supported here.
08-31 17:07:07.973   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:07.975  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:07.975  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:07.975  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:07.975  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:07.976  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:07.976  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:07.976  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:07.976  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:07.976   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 17:07:07.979  1869  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:07.984   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 17:07:08.014   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:08.032   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:08.033   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 17:07:08.033   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:08.039  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:08.039  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:08.039   873   890 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:08.040  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:08.040  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:08.045  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 17:07:08.049  1698  1698 D SystemUpdateService: onCreate
,08-31 17:07:08.051  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 17:07:08.059  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 17:07:08.061  1698  2408 I iu.UploadsManager: num queued entries: 0
,08-31 17:07:08.065  1698  4093 I SystemUpdateService: active receiver: enabled
,08-31 17:07:08.067  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 17:07:08.068  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-31 17:07:08.069  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:08.073  3960  3960 D SprintDMHelper: simOperator: 
,08-31 17:07:08.073  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 17:07:08.073  1698  2408 I iu.UploadsManager: num updated entries: 0
,08-31 17:07:08.102  1698  4093 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 17:07:08.103  1698  2408 I iu.SyncManager: NEXT; no task
,08-31 17:07:08.110  2246  4096 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 17:07:08.126  1698  4093 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-31 17:07:08.127  1698  4093 I SystemUpdateService: now status is 0 (complete)
,08-31 17:07:08.127  1698  4093 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 17:07:08.127  1698  4093 I SystemUpdateService: file has been verified
08-31 17:07:08.129  1698  4093 I SystemUpdateService: OTA package size = 12249756
,08-31 17:07:08.140   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-31 17:07:08.143  1698  4093 I SystemUpdateService: showing system update notification
,08-31 17:07:08.145   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 17:07:08.146   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 17:07:08.151  1698  1698 D SystemUpdateService: onDestroy
,08-31 17:07:10.936   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9f91e3:true
,08-31 17:07:10.936  3944  3944 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 17:07:10.941  3944  3944 I bt_bluedroid: init
,08-31 17:07:10.942  3944  4100 I BluetoothAdapterState: Entering OffState
,08-31 17:07:10.945  3944  4101 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 17:07:10.945  3944  4101 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 17:07:10.945  3944  4101 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 17:07:10.945  3944  4101 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 17:07:10.946  3944  3944 I bt_bluedroid: get_profile_interface socket
,08-31 17:07:10.949  3944  4104 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 17:07:10.950  3944  4104 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 17:07:10.950  3944  3944 I bt_bluedroid: get_profile_interface sdp
,08-31 17:07:10.958  3944  3956 I bt_bluedroid: config_hci_snoop_log
,08-31 17:07:10.962   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 17:07:10.974  3944  4100 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 17:07:10.975  3944  4100 D BluetoothAdapterProperties: Setting state to 14
08-31 17:07:10.975  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 17:07:10.981  3944  4100 D BluetoothBondStateMachine: make
,08-31 17:07:10.984  3944  4105 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 17:07:10.993  3944  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-31 17:07:10.994  3944  3944 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 17:07:11.002  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:11.006  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 17:07:11.007  3944  3944 D BtGatt.GattService: Received start request. Starting profile...
,08-31 17:07:11.008  3944  3944 D BtGatt.GattService: start()
,08-31 17:07:11.008  3944  3944 I bt_bluedroid: get_profile_interface gatt
,08-31 17:07:11.010  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:11.010  3944  3944 D BtGatt.AdvertiseManager: advertise manager created
,08-31 17:07:11.019  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:11.019  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:11.019  3944  3944 V BluetoothAdapterState: isBleTurningOn()=true
08-31 17:07:11.019  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:11.020  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 17:07:11.020  3944  4100 I bt_bluedroid: enable
08-31 17:07:11.021  3944  4101 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 17:07:11.021  3944  4101 I bt_hci  : start_up
,08-31 17:07:11.027  3944  4101 I bt_vendor: alloc value 0xb38b9189
08-31 17:07:11.027  3944  4101 I bt_vendor: init
08-31 17:07:11.027  3944  4101 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 17:07:11.027  3944  4101 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 17:07:11.132  3944  4101 D bt_hci  : start_up starting async portion
,08-31 17:07:11.133  3944  4108 I bt_hci  : event_finish_startup
08-31 17:07:11.133  3944  4108 I bt_hci_h4: hal_open
08-31 17:07:11.133  3944  4108 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 17:07:11.140  3944  4108 I bt_userial_vendor: device fd = 51 open
,08-31 17:07:11.175  3944  4108 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 17:07:11.208  3944  4108 D bt_hwcfg: Chipset BCM4354A2
08-31 17:07:11.208  3944  4108 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 17:07:11.209  3944  4108 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 17:07:11.877  3944  4108 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 17:07:11.879  3944  4108 D bt_hwcfg: Settlement delay -- 100 ms
08-31 17:07:11.879  3944  4108 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 17:07:11.995  3944  4108 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 17:07:11.997  3944  4108 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 17:07:12.026  3944  4108 I bt_hwcfg: vendor lib fwcfg completed
,08-31 17:07:12.027  3944  4108 I bt_vendor: firmware callback
08-31 17:07:12.027  3944  4108 I bt_hci  : firmware_config_callback
,08-31 17:07:12.038  3944  4110 I bt_btu  : btu_task pending for preload complete event
,08-31 17:07:12.039  3944  4110 I bt_btu_task: Bluetooth chip preload is complete
08-31 17:07:12.039  3944  4110 I bt_btu  : btu_task received preload complete event
,08-31 17:07:12.049  3944  4110 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 17:07:12.049  3944  4110 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 17:07:12.049  3944  4110 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 17:07:12.050  3944  4110 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 17:07:12.050  3944  4110 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 17:07:12.050  3944  4110 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 17:07:12.050  3944  4110 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 17:07:12.051  3944  4110 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 17:07:12.051  3944  4110 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 17:07:12.051  3944  4110 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 17:07:12.051  3944  4110 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 17:07:12.052  3944  4110 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 17:07:12.052  3944  4110 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 17:07:12.052  3944  4110 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 17:07:12.052  3944  4110 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 17:07:12.188  3944  4110 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3836d9d
,08-31 17:07:12.189  3944  4110 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3836d9d 
,08-31 17:07:12.212  3944  4104 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 17:07:12.213  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 17:07:12.214  3944  4104 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 17:07:12.217  3944  4104 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 17:07:12.220  3944  4104 D BluetoothAdapterProperties: Scan Mode:20
,08-31 17:07:12.224  3944  4104 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 17:07:12.226  3944  4104 D bt_hci  : do_postload posting postload work item
,08-31 17:07:12.227  3944  4108 I bt_hci  : event_postload
,08-31 17:07:12.227  3944  4108 I bt_vendor: sco_config_cb
,08-31 17:07:12.227  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:12.227  3944  4108 I bt_hci  : sco_config_callback postload finished.
08-31 17:07:12.230  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:12.231  3944  4104 D bt_bte_conf: Device ID record 1 : primary
,08-31 17:07:12.231  3944  4104 D bt_bte_conf:   vendorId            = 000f
08-31 17:07:12.231  3944  4104 D bt_bte_conf:   vendorIdSource      = 0001
08-31 17:07:12.231  3944  4104 D bt_bte_conf:   product             = 1200
08-31 17:07:12.231  3944  4104 D bt_bte_conf:   version             = 1436
08-31 17:07:12.231  3944  4104 D bt_bte_conf:   clientExecutableURL = 
08-31 17:07:12.231  3944  4104 D bt_bte_conf:   serviceDescription  = 
08-31 17:07:12.231  3944  4104 D bt_bte_conf:   documentationURL    = 
08-31 17:07:12.232  3944  4104 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 17:07:12.232  3944  4101 D bt_stack_manager: event_start_up_stack finished
08-31 17:07:12.232  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 17:07:12.232  3944  4100 D BluetoothAdapterProperties: Setting state to 15
08-31 17:07:12.232  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 17:07:12.233  3944  4100 I BluetoothAdapterState: Entering BleOnState
08-31 17:07:12.236  3944  4100 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 17:07:12.236  3944  4100 D BluetoothAdapterProperties: Setting state to 11
08-31 17:07:12.236  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 17:07:12.236  3944  4108 I bt_vendor: low_power_mode_cb
,08-31 17:07:12.248  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:12.249  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:12.250  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:12.252  3944  3944 D HeadsetService: Received start request. Starting profile...
08-31 17:07:12.256  3944  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-31 17:07:12.258  3944  3944 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 17:07:12.259  3944  3944 D HeadsetStateMachine: make
,08-31 17:07:12.266  3944  3944 D HeadsetStateMachine: max_hf_connections = 1
,08-31 17:07:12.266  3944  3944 I bt_bluedroid: get_profile_interface handsfree
,08-31 17:07:12.267  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 17:07:12.267  3944  4104 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-31 17:07:12.272  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:12.272  3944  3944 D A2dpService: Received start request. Starting profile...
08-31 17:07:12.273  3944  3944 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 17:07:12.273  3944  3944 I bt_bluedroid: get_profile_interface avrcp
,08-31 17:07:12.280  3944  3944 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 17:07:12.280  3944  3944 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:07:12.281  3944  3944 D A2dpStateMachine: make
,08-31 17:07:12.283  3944  3944 I bt_bluedroid: get_profile_interface a2dp
,08-31 17:07:12.283  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-31 17:07:12.284  3944  4118 D A2dpStateMachine: Enter Disconnected: -2
08-31 17:07:12.285  3944  3944 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 17:07:12.286  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
08-31 17:07:12.287  3865  3865 D BluetoothInputDevice: Proxy object connected
08-31 17:07:12.287  3944  3944 D HidService: Received start request. Starting profile...
08-31 17:07:12.288  3944  3944 I bt_bluedroid: get_profile_interface hidhost
08-31 17:07:12.288  3944  3944 D HidService: setHidService(): set to: null
,08-31 17:07:12.288  3944  4104 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38183e5
08-31 17:07:12.288  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 17:07:12.288  3944  3944 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 17:07:12.288  3865  3865 D HidProfile: Bluetooth service connected
08-31 17:07:12.289  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:12.290  3944  3944 D HealthService: Received start request. Starting profile...
08-31 17:07:12.291  3944  3944 I bt_bluedroid: get_profile_interface health
,08-31 17:07:12.292  3944  3944 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 17:07:12.293  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:12.294  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:12.295  3865  3865 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 17:07:12.295  3944  3944 D PanService: Received start request. Starting profile...
08-31 17:07:12.295  3944  3944 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 17:07:12.295  3944  3944 I bt_bluedroid: get_profile_interface pan
08-31 17:07:12.295  3865  3865 D PanProfile: Bluetooth service connected
,08-31 17:07:12.296  3944  4104 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 17:07:12.297  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
08-31 17:07:12.298  3944  3944 D BluetoothMapService: Received start request. Starting profile...
08-31 17:07:12.298  3944  3944 D BluetoothMapService: start()
08-31 17:07:12.301  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 17:07:12.301  3865  3865 D BluetoothMap: Proxy object connected
08-31 17:07:12.301  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 17:07:12.301  3944  3944 D BluetoothMapAppObserver: createReceiver()
08-31 17:07:12.303  3944  3944 D BluetoothMapAppObserver: initObservers()
08-31 17:07:12.303  3944  3944 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 17:07:12.305  3865  3865 D MapProfile: Bluetooth service connected
,08-31 17:07:12.305  3865  3865 D BluetoothMap: getConnectedDevices()
,08-31 17:07:12.306  3865  3865 D BluetoothMap: Bluetooth is Not enabled
,08-31 17:07:12.310  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:12.310  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:12.310  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:12.310  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 17:07:12.311  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:12.311  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:12.311  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:12.311  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:12.312  3944  4116 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 17:07:12.312  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:12.314  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:12.315  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:12.315  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 17:07:12.315  3944  4100 D BluetoothAdapterProperties: ScanMode =  20
,08-31 17:07:12.315  3944  4100 D BluetoothAdapterProperties: State =  11
08-31 17:07:12.317  3944  4100 D BluetoothAdapterProperties: Setting state to 12
08-31 17:07:12.317  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 17:07:12.318  3944  4100 I BluetoothAdapterState: Entering OnState
08-31 17:07:12.318  3865  3877 D BluetoothPan: onBluetoothStateChange on: true
,08-31 17:07:12.318  3944  4104 D BluetoothAdapterProperties: Scan Mode:21
,08-31 17:07:12.318  3944  4104 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:12.319  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:12.320  1367  2113 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 17:07:12.322  1367  1367 D BluetoothInputDevice: Proxy object connected
08-31 17:07:12.322  1367  1367 D HidProfile: Bluetooth service connected
,08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:12.322  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:12.323   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:12.323  1367  1379 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 17:07:12.324  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:12.325  3865  3878 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 17:07:12.325  1367  2113 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 17:07:12.326  1367  1367 D BluetoothMap: Proxy object connected
08-31 17:07:12.326  1367  1367 D MapProfile: Bluetooth service connected
,08-31 17:07:12.326  1367  1367 D BluetoothMap: getConnectedDevices()
08-31 17:07:12.327   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:12.327  1975  1986 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:12.327  1367  1378 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:12.328  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:12.328  1367  1367 D BluetoothA2dp: Proxy object connected
,08-31 17:07:12.329  3865  3877 D BluetoothMap: onBluetoothStateChange: up=true
08-31 17:07:12.329  3865  3878 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 17:07:12.330  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 17:07:12.330  1367  1379 D BluetoothPan: onBluetoothStateChange on: true
08-31 17:07:12.330  3944  3944 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 17:07:12.330  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:12.331  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:12.332  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 17:07:12.332  1367  1367 D PanProfile: Bluetooth service connected
08-31 17:07:12.332   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:12.332   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:12.332   873   873 D BluetoothA2dp: Proxy object connected
08-31 17:07:12.335  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:12.336  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:12.337  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:12.338  3865  3865 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 17:07:12.338  3944  3944 D ObexServerSockets: Succeed to create listening sockets 
08-31 17:07:12.338  3944  3944 D ObexServerSockets0: startAccept()
08-31 17:07:12.338  3944  3944 D ObexServerSockets0: prepareForNewConnect()
08-31 17:07:12.339   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 17:07:12.340  3944  3944 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 17:07:12.340  3944  3944 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 17:07:12.341  3944  3944 D BluetoothMapService: onReceive
08-31 17:07:12.341  3944  4126 D ObexServerSockets0: Accepting socket connection...
08-31 17:07:12.341  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:12.341  3944  3944 D BluetoothMapService: STATE_ON
08-31 17:07:12.342  3944  4127 D ObexServerSockets0: Accepting socket connection...
08-31 17:07:12.342  3865  3865 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 17:07:12.352  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:07:12.356  3865  3865 D BluetoothA2dp: Proxy object connected
,08-31 17:07:12.360  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:12.363  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:07:12.368  1367  1367 D BluetoothPbap: Proxy object connected
08-31 17:07:12.368  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-31 17:07:12.368  3865  3865 D BluetoothPbap: Proxy object connected
,08-31 17:07:12.369  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 17:07:12.369  3865  3865 D PbapServerProfile: Bluetooth service connected
08-31 17:07:12.369  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-31 17:07:12.382  3944  4131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:12.391  3944  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:12.392  3944  4135 I BtOppRfcommListener: Accept thread started.
,08-31 17:07:12.420  1367  2113 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.421  1367  1367 D HeadsetProfile: Bluetooth service connected
08-31 17:07:12.421   873   873 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.421   873   873 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.421   873   873 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.421  1975  2296 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.423   873   890 D BluetoothHeadset: Proxy object connected
08-31 17:07:12.427   873   890 D BluetoothHeadset: Proxy object connected
08-31 17:07:12.427  1975  2168 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.432   873   890 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.445  3865  3878 D BluetoothHeadset: Proxy object connected
,08-31 17:07:12.446  3865  3865 D HeadsetProfile: Bluetooth service connected
,08-31 17:07:13.896  3944  4100 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 17:07:13.896  3944  4100 D BluetoothAdapterProperties: Setting state to 13
08-31 17:07:13.897  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 17:07:13.899  3944  4100 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 17:07:13.901  3944  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-31 17:07:13.912   873  1309 D ConnectivityService: handlePromptUnvalidated 101
08-31 17:07:13.912  3944  3944 D BluetoothMapService: onReceive
08-31 17:07:13.912  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:13.913  3944  3944 D BluetoothMapService: STATE_TURNING_OFF
08-31 17:07:13.913  3944  3944 D BluetoothMapService: MAP Service closeService in
08-31 17:07:13.914  3944  3944 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 17:07:13.914  3944  3944 D ObexServerSockets0: shutdown(block = true)
08-31 17:07:13.915  3944  4126 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 17:07:13.920  3944  4104 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:07:13.921  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 17:07:13.922  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 17:07:13.922  3944  4127 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 17:07:13.922  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:13.922  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:13.923  3944  4112 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 17:07:13.923  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 17:07:13.927  3944  3944 D HeadsetService: Received stop request...Stopping profile...
08-31 17:07:13.927  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 17:07:13.929  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:13.929  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:13.931  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:13.931  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:13.933  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:13.933  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:13.934  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:13.935  1367  1379 D BluetoothHeadset: Proxy object disconnected
,08-31 17:07:13.936  3865  3877 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:13.936  3944  3944 I BtOppRfcommListener: stopping Accept Thread
,08-31 17:07:13.936   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:13.936   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:13.936   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:13.936  3944  4135 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 17:07:13.936  1975  1990 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:13.936  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:13.936  3944  4135 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 17:07:13.941  3944  3944 D A2dpService: Received stop request...Stopping profile...
08-31 17:07:13.941  3944  4118 D A2dpStateMachine: Exit Disconnected: -1
,08-31 17:07:13.942   873   873 D BluetoothA2dp: Proxy object disconnected
08-31 17:07:13.943  3944  3944 D HidService: Received stop request...Stopping profile...
,08-31 17:07:13.943  3944  3944 D HidService: Stopping Bluetooth HidService
,08-31 17:07:13.945  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-31 17:07:13.945  3944  3944 D HealthService: Received stop request...Stopping profile...
08-31 17:07:13.946  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-31 17:07:13.946  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-31 17:07:13.946  1367  1367 D HidProfile: Bluetooth service disconnected
,08-31 17:07:13.947  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:13.948  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-31 17:07:13.948  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:13.948  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 17:07:13.949  3865  3865 D DockEventReceiver: finishStartingService: stopping service
08-31 17:07:13.949  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 17:07:13.949  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 17:07:13.950  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-31 17:07:13.950  3944  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:13.950  3944  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:13.950  3944  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 17:07:13.950  3944  4104 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-31 17:07:13.950  3944  3944 D PanService: Received stop request...Stopping profile...
08-31 17:07:13.950  3865  3865 D HeadsetProfile: Bluetooth service disconnected
08-31 17:07:13.951  3865  3865 D BluetoothA2dp: Proxy object disconnected
08-31 17:07:13.951  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 17:07:13.951  1367  1367 D PanProfile: Bluetooth service disconnected
08-31 17:07:13.952  3865  3865 D BluetoothInputDevice: Proxy object disconnected
,08-31 17:07:13.952  3865  3865 D HidProfile: Bluetooth service disconnected
08-31 17:07:13.953  3944  3944 D BluetoothMapService: Received stop request...Stopping profile...
08-31 17:07:13.953  3944  3944 D BluetoothMapService: stop()
08-31 17:07:13.955  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 17:07:13.956  3865  3865 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 17:07:13.956  3865  3865 D PanProfile: Bluetooth service disconnected
08-31 17:07:13.957  3944  3944 D BluetoothMapAppObserver: deinitObservers()
08-31 17:07:13.957  3944  3944 D BluetoothMapAppObserver: removeReceiver()
,08-31 17:07:13.959  3865  3865 D BluetoothMap: Proxy object disconnected
08-31 17:07:13.959  3865  3865 D MapProfile: Bluetooth service disconnected
08-31 17:07:13.959  1367  1367 D BluetoothMap: Proxy object disconnected
08-31 17:07:13.959  1367  1367 D MapProfile: Bluetooth service disconnected
08-31 17:07:13.960  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:13.961  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:13.961  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:13.961  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:13.962  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 17:07:13.962  3944  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:13.962  3944  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 17:07:13.962  3944  4110 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:07:13.962  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:13.962  3944  4110 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:13.962  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-31 17:07:13.962  3944  4110 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:07:13.962  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:13.962  3944  4110 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:13.962  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:13.962  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 17:07:13.963  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 17:07:13.963  3944  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 17:07:13.963  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:13.963  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:13.963  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:13.963  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:13.963  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 17:07:13.963  3944  4104 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 17:07:13.964  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:07:13.964  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:13.964  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:13.964  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:13.964  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:13.965  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 17:07:13.965  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 17:07:13.967  1367  1367 D BluetoothPbap: Proxy object disconnected
08-31 17:07:13.967  1367  1367 D PbapServerProfile: Bluetooth service disconnected
,08-31 17:07:13.968  3865  3865 D BluetoothPbap: Proxy object disconnected
,08-31 17:07:13.968  3865  3865 D PbapServerProfile: Bluetooth service disconnected
,08-31 17:07:13.969  3944  3944 D BluetoothMapService: MAP Service closeService in
08-31 17:07:13.969  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-31 17:07:13.969  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-31 17:07:13.969  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:13.969  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:13.970  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 17:07:13.970  3944  4100 D BluetoothAdapterProperties: Setting state to 15
08-31 17:07:13.970  3944  3944 D BluetoothMapService: cleanup()
,08-31 17:07:13.970  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 17:07:13.970  3944  3944 D BluetoothMapService: MAP Service closeService in
08-31 17:07:13.970  3944  4100 I BluetoothAdapterState: Entering BleOnState
08-31 17:07:13.971  3865  3878 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:13.973  3865  3877 D BluetoothPan: onBluetoothStateChange on: false
08-31 17:07:13.974  1367  2113 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:13.974  1367  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 17:07:13.975   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 17:07:13.975  3865  3878 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:13.975  1367  1379 D BluetoothMap: onBluetoothStateChange: up=false
08-31 17:07:13.975  3865  3877 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 17:07:13.976  1367  2113 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:13.976   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:13.976  1975  1986 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:13.977  1367  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 17:07:13.977  3865  3878 D BluetoothMap: onBluetoothStateChange: up=false
08-31 17:07:13.978  3865  3877 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 17:07:13.978  1367  1379 D BluetoothPan: onBluetoothStateChange on: false
08-31 17:07:13.979   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:13.979   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:13.979  3944  4100 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-31 17:07:13.979  3944  4100 D BluetoothAdapterProperties: Setting state to 16
08-31 17:07:13.979  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 17:07:13.980  3944  4100 D BluetoothAdapterProperties: onBleDisable
08-31 17:07:13.980  3944  4100 I BluetoothAdapterState: Entering PendingCommandState
08-31 17:07:13.980  3944  4101 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-31 17:07:13.982  3944  4110 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 17:07:13.982  3944  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 17:07:13.982  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:13.982  3944  4104 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:07:13.983  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:13.985  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 17:07:13.985  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:13.987  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:13.989  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 17:07:13.989  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:07:14.182  3944  4104 I bt_hci  : shut_down
,08-31 17:07:14.183  3944  4108 D bt_hwcfg: hw_epilog_process
,08-31 17:07:14.185  3944  4108 I bt_vendor: low_power_mode_cb
,08-31 17:07:14.207  3944  4108 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 17:07:14.207  3944  4108 I bt_vendor: epilog_cb
08-31 17:07:14.208  3944  4108 I bt_hci  : epilog_finished_callback
,08-31 17:07:14.218  3944  4104 I bt_hci_h4: hal_close
,08-31 17:07:14.220  3944  4104 I bt_userial_vendor: device fd = 51 close
,08-31 17:07:14.334  3944  4101 D bt_stack_manager: event_shut_down_stack finished.
,08-31 17:07:14.336  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 17:07:14.342  3944  4100 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-31 17:07:14.342  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 17:07:14.343  3944  3944 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 17:07:14.344  3944  3944 D BtGatt.GattService: stop()
08-31 17:07:14.344  3944  3944 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 17:07:14.350  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:14.351  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:14.351  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:14.351  3944  3944 V BluetoothAdapterState: isBleTurningOff()=true
,08-31 17:07:14.352  3944  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 17:07:14.353  3944  4100 D BluetoothAdapterProperties: Setting state to 10
08-31 17:07:14.353  3944  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 17:07:14.354  3944  4100 I BluetoothAdapterState: Entering OffState
08-31 17:07:14.356   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 17:07:14.379  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 17:07:14.380  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 17:07:14.380  3944  4101 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 17:07:14.389  3944  3944 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 17:07:14.390  3944  4101 D bt_stack_manager: event_clean_up_stack finished.
,08-31 17:07:14.392  3944  3944 I art     : System.exit called, status: 0
,08-31 17:07:14.393  3944  3944 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 17:07:14.450   873  2023 I ActivityManager: Process com.android.bluetooth (pid 3944) has died
,08-31 17:07:16.891  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:07:16.892  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:17.243  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:17.261  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:17.267  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:17.349  1511  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 17:07:17.350  1511  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 17:07:17.350  1511  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 17:07:17.350  1511  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 17:07:17.407  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 17:07:17.408  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 17:07:17.409  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-31 17:07:17.666   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-31 17:07:17.673  1898  1898 I Keyboard.Facilitator: onFinishInput()
,08-31 17:07:17.682   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 17:07:17.682   873   893 I Adreno  : Build Date                       : 10/20/15
08-31 17:07:17.682   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 17:07:17.682   873   893 I Adreno  : Local Branch                     : M14
08-31 17:07:17.682   873   893 I Adreno  : Remote Branch                    : 
08-31 17:07:17.682   873   893 I Adreno  : Remote Branch                    : 
08-31 17:07:17.682   873   893 I Adreno  : Reconstruct Branch               : 
,08-31 17:07:17.731   280   369 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (324 us)
,08-31 17:07:18.387  3798  3798 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 17:07:18.387  3798  3798 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 17:07:18.447  3798  3798 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34cc585 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b61fda7, 16908290=android.view.AbsSavedState$1@b61fda7}, android:focusedViewId=100}]}]
,08-31 17:07:18.447  3798  3798 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-31 17:07:18.447  3798  3798 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 17:07:18.447  3798  3798 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-31 17:07:18.446   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-31 17:07:18.455   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-31 17:07:18.458   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-31 17:07:18.461   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-31 17:07:18.462   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-31 17:07:18.692   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-31 17:07:18.696   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-31 17:07:18.702   873  1336 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,08-31 17:07:18.708   873   893 I DreamManagerService: Entering dreamland.
,08-31 17:07:18.710   873   893 I PowerManagerService: Dozing...
,08-31 17:07:18.711   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-31 17:07:18.786   376  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-31 17:07:18.786   376  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-31 17:07:18.801   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 17:07:18.813   873  1307 E native  : do suspend false
,08-31 17:07:18.820  1963  4146 D NfcService: Discovery configuration equal, not updating.
,08-31 17:07:18.863   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 17:07:18.867   873  1307 E native  : do suspend true
,08-31 17:07:18.920   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-31 17:07:18.920   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-31 17:07:19.900  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:19.900  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2c1254 added. We now have 6 listener(s)
08-31 17:07:19.900  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:19.905  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:19.906  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35195fd added. We now have 7 listener(s)
08-31 17:07:19.906  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:19.909  3798  3847 I System.out: IsBluetoothEnabled
,08-31 17:07:19.921  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:19.968   873   890 I ActivityManager: Start proc 4152:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 17:07:20.090  4152  4152 D AdapterServiceConfig: Adding HeadsetService
08-31 17:07:20.090  4152  4152 D AdapterServiceConfig: Adding A2dpService
08-31 17:07:20.091  4152  4152 D AdapterServiceConfig: Adding HidService
08-31 17:07:20.092  4152  4152 D AdapterServiceConfig: Adding HealthService
,08-31 17:07:20.092  4152  4152 D AdapterServiceConfig: Adding PanService
08-31 17:07:20.093  4152  4152 D AdapterServiceConfig: Adding GattService
,08-31 17:07:20.095  4152  4152 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 17:07:20.114   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c40985:true
08-31 17:07:20.114  4152  4152 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 17:07:20.119  4152  4152 I bt_bluedroid: init
,08-31 17:07:20.120  4152  4164 I BluetoothAdapterState: Entering OffState
,08-31 17:07:20.126  4152  4165 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 17:07:20.126  4152  4165 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 17:07:20.126  4152  4165 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 17:07:20.127  4152  4165 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 17:07:20.128  4152  4152 I bt_bluedroid: get_profile_interface socket
,08-31 17:07:20.131  4152  4152 I bt_bluedroid: get_profile_interface sdp
,08-31 17:07:20.137  4152  4168 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 17:07:20.140  4152  4163 I bt_bluedroid: config_hci_snoop_log
,08-31 17:07:20.141  4152  4168 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 17:07:20.144   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 17:07:20.156  4152  4164 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 17:07:20.157  4152  4164 D BluetoothAdapterProperties: Setting state to 14
08-31 17:07:20.157  4152  4164 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 17:07:20.162  4152  4164 D BluetoothBondStateMachine: make
,08-31 17:07:20.168  4152  4169 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 17:07:20.180  4152  4164 I BluetoothAdapterState: Entering PendingCommandState
08-31 17:07:20.181  4152  4152 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 17:07:20.184  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:20.185  4152  4152 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 17:07:20.186  4152  4152 D BtGatt.GattService: Received start request. Starting profile...
08-31 17:07:20.186  4152  4152 D BtGatt.GattService: start()
08-31 17:07:20.186  4152  4152 I bt_bluedroid: get_profile_interface gatt
08-31 17:07:20.187  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
08-31 17:07:20.187  4152  4152 D BtGatt.AdvertiseManager: advertise manager created
,08-31 17:07:20.197  4152  4152 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:20.197  4152  4152 V BluetoothAdapterState: isTurningOn()=false
08-31 17:07:20.197  4152  4152 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 17:07:20.198  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:20.198  4152  4164 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 17:07:20.199  4152  4164 I bt_bluedroid: enable
,08-31 17:07:20.199  4152  4165 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 17:07:20.200  4152  4165 I bt_hci  : start_up
,08-31 17:07:20.207  4152  4165 I bt_vendor: alloc value 0xb3a39189
,08-31 17:07:20.207  4152  4165 I bt_vendor: init
08-31 17:07:20.207  4152  4165 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 17:07:20.207  4152  4165 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 17:07:20.313  4152  4165 D bt_hci  : start_up starting async portion
,08-31 17:07:20.314  4152  4172 I bt_hci  : event_finish_startup
,08-31 17:07:20.314  4152  4172 I bt_hci_h4: hal_open
,08-31 17:07:20.315  4152  4172 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 17:07:20.328  4152  4172 I bt_userial_vendor: device fd = 51 open
,08-31 17:07:20.356  4152  4172 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 17:07:20.387  4152  4172 D bt_hwcfg: Chipset BCM4354A2
,08-31 17:07:20.388  4152  4172 D bt_hwcfg: Target name = [BCM4354A2]
08-31 17:07:20.388  4152  4172 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 17:07:21.053  4152  4172 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 17:07:21.055  4152  4172 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 17:07:21.055  4152  4172 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 17:07:21.172  4152  4172 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 17:07:21.173  4152  4172 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 17:07:21.203  4152  4172 I bt_hwcfg: vendor lib fwcfg completed
,08-31 17:07:21.203  4152  4172 I bt_vendor: firmware callback
08-31 17:07:21.203  4152  4172 I bt_hci  : firmware_config_callback
,08-31 17:07:21.214  4152  4174 I bt_btu  : btu_task pending for preload complete event
,08-31 17:07:21.215  4152  4174 I bt_btu_task: Bluetooth chip preload is complete
,08-31 17:07:21.215  4152  4174 I bt_btu  : btu_task received preload complete event
,08-31 17:07:21.228  4152  4174 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 17:07:21.228  4152  4174 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 17:07:21.228  4152  4174 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 17:07:21.229  4152  4174 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 17:07:21.229  4152  4174 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 17:07:21.229  4152  4174 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 17:07:21.229  4152  4174 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 17:07:21.230  4152  4174 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 17:07:21.231  4152  4174 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 17:07:21.232  4152  4174 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 17:07:21.232  4152  4174 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 17:07:21.233  4152  4174 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 17:07:21.233  4152  4174 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 17:07:21.233  4152  4174 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 17:07:21.233  4152  4174 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 17:07:21.367  4152  4174 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b6d9d
,08-31 17:07:21.368  4152  4174 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b6d9d 
,08-31 17:07:21.379  4152  4168 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 17:07:21.380  4152  4168 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 17:07:21.381  4152  4168 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 17:07:21.384  4152  4168 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 17:07:21.387  4152  4168 D BluetoothAdapterProperties: Scan Mode:20
,08-31 17:07:21.387  4152  4168 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:21.387  4152  4168 D bt_hci  : do_postload posting postload work item
,08-31 17:07:21.388  4152  4172 I bt_hci  : event_postload
,08-31 17:07:21.388  4152  4172 I bt_vendor: sco_config_cb
,08-31 17:07:21.388  4152  4172 I bt_hci  : sco_config_callback postload finished.
08-31 17:07:21.392  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.393  4152  4168 D bt_bte_conf: Device ID record 1 : primary
08-31 17:07:21.393  4152  4168 D bt_bte_conf:   vendorId            = 000f
08-31 17:07:21.393  4152  4168 D bt_bte_conf:   vendorIdSource      = 0001
08-31 17:07:21.394  4152  4168 D bt_bte_conf:   product             = 1200
08-31 17:07:21.394  4152  4168 D bt_bte_conf:   version             = 1436
08-31 17:07:21.394  4152  4168 D bt_bte_conf:   clientExecutableURL = 
08-31 17:07:21.394  4152  4168 D bt_bte_conf:   serviceDescription  = 
08-31 17:07:21.394  4152  4168 D bt_bte_conf:   documentationURL    = 
08-31 17:07:21.395  4152  4172 I bt_vendor: low_power_mode_cb
08-31 17:07:21.395  4152  4168 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 17:07:21.395  4152  4165 D bt_stack_manager: event_start_up_stack finished
08-31 17:07:21.396  4152  4164 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 17:07:21.397  4152  4164 D BluetoothAdapterProperties: Setting state to 15
08-31 17:07:21.397  4152  4164 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 17:07:21.398  4152  4164 I BluetoothAdapterState: Entering BleOnState
08-31 17:07:21.405  4152  4164 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 17:07:21.406  4152  4164 D BluetoothAdapterProperties: Setting state to 11
,08-31 17:07:21.406  4152  4164 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 17:07:21.416  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.422  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:21.424  4152  4152 D HeadsetService: Received start request. Starting profile...
,08-31 17:07:21.429  4152  4152 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 17:07:21.430  4152  4152 D HeadsetStateMachine: make
,08-31 17:07:21.435  4152  4164 I BluetoothAdapterState: Entering PendingCommandState
,08-31 17:07:21.437  4152  4152 D HeadsetStateMachine: max_hf_connections = 1
,08-31 17:07:21.437  4152  4152 I bt_bluedroid: get_profile_interface handsfree
,08-31 17:07:21.437  4152  4168 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 17:07:21.437  4152  4168 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 17:07:21.442  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:21.443  4152  4152 D A2dpService: Received start request. Starting profile...
,08-31 17:07:21.443  4152  4152 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 17:07:21.444  4152  4152 I bt_bluedroid: get_profile_interface avrcp
,08-31 17:07:21.449  4152  4152 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 17:07:21.450  4152  4152 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:07:21.450  4152  4152 D A2dpStateMachine: make
,08-31 17:07:21.451  4152  4152 I bt_bluedroid: get_profile_interface a2dp
,08-31 17:07:21.452  4152  4168 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-31 17:07:21.453  4152  4183 D A2dpStateMachine: Enter Disconnected: -2
08-31 17:07:21.453  4152  4152 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 17:07:21.454  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:21.455  4152  4152 D HidService: Received start request. Starting profile...
08-31 17:07:21.455  4152  4152 I bt_bluedroid: get_profile_interface hidhost
,08-31 17:07:21.455  4152  4168 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39983e5
08-31 17:07:21.455  4152  4168 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 17:07:21.455  4152  4152 D HidService: setHidService(): set to: null
08-31 17:07:21.456  4152  4152 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 17:07:21.456  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
08-31 17:07:21.457  4152  4152 D HealthService: Received start request. Starting profile...
08-31 17:07:21.458  4152  4152 I bt_bluedroid: get_profile_interface health
08-31 17:07:21.460  4152  4152 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 17:07:21.461  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
08-31 17:07:21.461  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:21.462  4152  4152 D PanService: Received start request. Starting profile...
08-31 17:07:21.462  4152  4152 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 17:07:21.462  4152  4152 I bt_bluedroid: get_profile_interface pan
,08-31 17:07:21.463  4152  4168 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 17:07:21.466  4152  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:21.467  4152  4152 D BluetoothMapService: Received start request. Starting profile...
08-31 17:07:21.467  4152  4152 D BluetoothMapService: start()
,08-31 17:07:21.469  4152  4152 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
08-31 17:07:21.470  4152  4152 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 17:07:21.470  4152  4152 D BluetoothMapAppObserver: createReceiver()
,08-31 17:07:21.471  4152  4152 D BluetoothMapAppObserver: initObservers()
,08-31 17:07:21.471  4152  4152 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 17:07:21.477  4152  4181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 17:07:21.478  4152  4152 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:21.478  4152  4152 V BluetoothAdapterState: isTurningOn()=true
,08-31 17:07:21.478  4152  4152 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 17:07:21.478  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:21.479  4152  4152 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:21.479  4152  4152 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:21.479  4152  4152 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:21.480  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:21.482  4152  4152 V BluetoothAdapterState: isTurningOff()=false
,08-31 17:07:21.482  4152  4152 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:21.483  4152  4152 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:21.483  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:21.483  4152  4152 V BluetoothAdapterState: isTurningOff()=false
08-31 17:07:21.483  4152  4152 V BluetoothAdapterState: isTurningOn()=true
08-31 17:07:21.483  4152  4152 V BluetoothAdapterState: isBleTurningOn()=false
08-31 17:07:21.483  4152  4152 V BluetoothAdapterState: isBleTurningOff()=false
08-31 17:07:21.483  4152  4164 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 17:07:21.483  4152  4164 D BluetoothAdapterProperties: ScanMode =  20
08-31 17:07:21.483  4152  4164 D BluetoothAdapterProperties: State =  11
08-31 17:07:21.485  4152  4168 D BluetoothAdapterProperties: Scan Mode:21
,08-31 17:07:21.485  4152  4168 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:21.485  4152  4164 D BluetoothAdapterProperties: Setting state to 12
08-31 17:07:21.485  4152  4164 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 17:07:21.486  3865  3877 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:21.486  4152  4164 I BluetoothAdapterState: Entering OnState
,08-31 17:07:21.487  3865  3878 D BluetoothPan: onBluetoothStateChange on: true
,08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:21.488  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:21.490  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:21.491  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:21.492  3865  3865 D BluetoothA2dp: Proxy object connected
08-31 17:07:21.492  1367  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 17:07:21.494   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:21.494  3865  3878 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:21.494  1367  1379 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 17:07:21.494  1367  1367 D BluetoothInputDevice: Proxy object connected
08-31 17:07:21.495  1367  1367 D HidProfile: Bluetooth service connected
,08-31 17:07:21.497  4152  4152 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 17:07:21.497  3865  3877 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 17:07:21.497  4152  4152 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 17:07:21.499  4152  4152 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:21.499  1367  1378 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:21.501  1367  1367 D BluetoothA2dp: Proxy object connected
08-31 17:07:21.501   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:21.501  4152  4152 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:21.502  3865  3865 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 17:07:21.502  3865  3865 D PanProfile: Bluetooth service connected
08-31 17:07:21.502  3865  3865 D BluetoothInputDevice: Proxy object connected
08-31 17:07:21.502  1975  1990 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:21.502  3865  3865 D HidProfile: Bluetooth service connected
08-31 17:07:21.502  1367  1379 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 17:07:21.503  4152  4152 D ObexServerSockets: Succeed to create listening sockets 
,08-31 17:07:21.503  4152  4152 D ObexServerSockets0: startAccept()
08-31 17:07:21.503  4152  4152 D ObexServerSockets0: prepareForNewConnect()
08-31 17:07:21.504  3865  3878 D BluetoothMap: onBluetoothStateChange: up=true
08-31 17:07:21.505  4152  4152 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 17:07:21.505  4152  4152 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 17:07:21.506  4152  4191 D ObexServerSockets0: Accepting socket connection...
,08-31 17:07:21.506  3865  3877 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 17:07:21.506  1367  1367 D BluetoothMap: Proxy object connected
08-31 17:07:21.506  1367  1367 D MapProfile: Bluetooth service connected
08-31 17:07:21.506  1367  1367 D BluetoothMap: getConnectedDevices()
,08-31 17:07:21.507  4152  4192 D ObexServerSockets0: Accepting socket connection...
,08-31 17:07:21.508  1367  1378 D BluetoothPan: onBluetoothStateChange on: true
,08-31 17:07:21.508  3865  3865 D BluetoothMap: Proxy object connected
,08-31 17:07:21.508  3865  3865 D MapProfile: Bluetooth service connected
08-31 17:07:21.508  3865  3865 D BluetoothMap: getConnectedDevices()
08-31 17:07:21.509  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 17:07:21.509  1367  1367 D PanProfile: Bluetooth service connected
08-31 17:07:21.509   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:21.509   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:21.510   873   873 D BluetoothA2dp: Proxy object connected
08-31 17:07:21.511  4152  4152 D BluetoothMapService: onReceive
,08-31 17:07:21.511  4152  4152 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:21.511  4152  4152 D BluetoothMapService: STATE_ON
08-31 17:07:21.512   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 17:07:21.513  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:21.516  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:07:21.521  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:21.528  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:07:21.529  3865  3865 D BluetoothPbap: Proxy object connected
,08-31 17:07:21.529  3865  3865 D PbapServerProfile: Bluetooth service connected
,08-31 17:07:21.534  1367  1367 D BluetoothPbap: Proxy object connected
,08-31 17:07:21.535  1367  1367 D PbapServerProfile: Bluetooth service connected
08-31 17:07:21.537  4152  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:21.544  4152  4152 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 17:07:21.544  4152  4152 D ObexServerSockets0: prepareForNewConnect()
,08-31 17:07:21.548  4152  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:21.549  4152  4200 I BtOppRfcommListener: Accept thread started.
,08-31 17:07:21.593  1367  2113 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.593  1367  1367 D HeadsetProfile: Bluetooth service connected
08-31 17:07:21.594  3865  3877 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.594   873   873 D BluetoothHeadset: Proxy object connected
08-31 17:07:21.594   873   873 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.594   873   873 D BluetoothHeadset: Proxy object connected
08-31 17:07:21.594  3865  3865 D HeadsetProfile: Bluetooth service connected
08-31 17:07:21.594  1975  1986 D BluetoothHeadset: Proxy object connected
08-31 17:07:21.594   873   890 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.595  3865  4188 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.597  3865  3865 D HeadsetProfile: Bluetooth service connected
,08-31 17:07:21.602   873   890 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.603  1975  2296 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.609   873   890 D BluetoothHeadset: Proxy object connected
,08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:21.946  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:21.953  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:21.956  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.957  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@41e22f2 added. We now have 8 listener(s)
,08-31 17:07:21.957  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:21.962   873  2021 D WifiService: setWifiEnabled: false pid=3798, uid=10000
,08-31 17:07:21.963   873  2021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:21.975  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:21.976   873  1386 D WifiService: setWifiEnabled: true pid=3798, uid=10000
08-31 17:07:21.976   873  1386 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:21.988   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:22.006  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:22.011   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-31 17:07:22.012   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 17:07:22.013   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 17:07:22.014   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 17:07:22.014   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 17:07:22.014   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 17:07:22.014   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:22.015  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:22.018  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:22.021  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:22.022  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 17:07:22.023  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 17:07:22.025  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34cc585 Bundle[{}]
08-31 17:07:22.026  3798  3847 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 17:07:22.026  3798  3847 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 17:07:22.027  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 17:07:22.028  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 17:07:22.028  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 17:07:22.029  3798  3847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 17:07:22.030   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 17:07:22.030   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
08-31 17:07:22.030   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-31 17:07:22.031   372   871 D CommandListener: Setting iface cfg
,08-31 17:07:22.031   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
08-31 17:07:22.031   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 17:07:22.035  3798  3847 I System.out: Running OutgoingSocketThread
,08-31 17:07:22.037  3798  4206 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
08-31 17:07:22.038  3798  4206 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40515
08-31 17:07:22.038  3798  4206 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 17:07:22.041   873  1307 E native  : do suspend true
,08-31 17:07:22.047   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 17:07:22.047   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 17:07:22.053   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 17:07:22.053   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:07:22.067   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 17:07:22.111   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 17:07:22.114  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 17:07:22.544  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 17:07:22.589  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 17:07:22.592  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 17:07:22.599   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 17:07:22.614   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 17:07:22.616   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 17:07:22.616   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:07:22.638   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:07:22.651   372   871 D CommandListener: Setting iface cfg
08-31 17:07:22.652   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 17:07:22.666   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 17:07:22.680   873  4210 D DhcpClient: Receive thread started
,08-31 17:07:22.768   873  1307 E native  : do suspend false
,08-31 17:07:22.792   873  1864 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 17:07:22.816   873  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-31 17:07:22.819   873  1864 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-31 17:07:22.824   873  1864 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 17:07:22.837   873  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 17:07:22.838   873  1864 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 17:07:22.846   372   871 D CommandListener: Setting iface cfg
,08-31 17:07:22.857   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 17:07:22.858   873  1307 E native  : do suspend true
,08-31 17:07:22.859   873  1864 D DhcpClient: Scheduling renewal in 86399s
,08-31 17:07:22.874   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 17:07:22.875   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-31 17:07:22.876   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 17:07:22.878   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-31 17:07:22.885   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 17:07:22.936   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 17:07:22.937   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 17:07:22.939   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 17:07:22.941   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-31 17:07:22.943   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 17:07:22.960   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 17:07:22.966   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-31 17:07:22.966   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-31 17:07:22.966   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:22.966   873  1309 D ConnectivityService:    accepting network in place of null
,08-31 17:07:22.967   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 17:07:22.968   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 17:07:22.968   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 17:07:22.985   873  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155512, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 17:07:23.019   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 17:07:23.038  3798  3847 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-31 17:07:23.039  3798  3847 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-31 17:07:23.047  3798  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-31 17:07:23.049  3798  3847 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 17:07:23.050  3798  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-31 17:07:23.056  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 17:07:23.057  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a6cd43 added. We now have 2 listener(s)
,08-31 17:07:23.062  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:23.063  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 17:07:23.063  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 17:07:23.064  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:23.064  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@661ffc0 added. We now have 9 listener(s)
,08-31 17:07:23.064  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:23.066  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:07:23.069  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.069   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 17:07:23.073   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 17:07:23.073   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:23.076   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:23.081   873   890 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:23.084   873  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:805::200e
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:23.084  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:23.086  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.087  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:23.087  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.087  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d677c3e added. We now have 3 listener(s)
08-31 17:07:23.090  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 17:07:23.090  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.090  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.090  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:23.090  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2defa9f added. We now have 10 listener(s)
08-31 17:07:23.090  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.090  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:23.090  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:23.090  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:07:23.090  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:23.091  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.091  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.091  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:23.091  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 17:07:23.091  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a6cd43 removed from the list
08-31 17:07:23.091  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.091  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@661ffc0 removed from the list
08-31 17:07:23.093  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.093  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:23.093  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.095  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.095  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.096  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:23.096  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.096  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.096  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@661ffc0 not in the list
08-31 17:07:23.097  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.097  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.098  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.098  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:23.098  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:23.098  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:23.098  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2defa9f removed from the list
08-31 17:07:23.098  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.098  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.099  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:23.099  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.099  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d677c3e removed from the list
08-31 17:07:23.099  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.099  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4757ec added. We now have 2 listener(s)
08-31 17:07:23.101  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.101  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 17:07:23.101  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 17:07:23.101  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.101  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:23.102  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab287b5 added. We now have 9 listener(s)
08-31 17:07:23.102  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.102  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:07:23.104  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.107  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:23.108  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:23.110  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:23.110  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:23.110  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.110  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@742a1bb added. We now have 3 listener(s)
,08-31 17:07:23.112  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:23.112  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.112  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.112  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:23.112  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64806d8 added. We now have 10 listener(s)
08-31 17:07:23.112  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:23.112  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.112  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:23.113  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:23.113  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:23.113  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.113  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:07:23.114  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.116  1698  1698 D SystemUpdateService: onCreate
,08-31 17:07:23.117  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 17:07:23.117  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:07:23.120  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 17:07:23.121  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:07:23.121  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 17:07:23.121  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:07:23.126  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 17:07:23.126  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:07:23.126  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 17:07:23.127  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:23.130  4152  4180 D BtGatt.GattService: registerClient() - UUID=5a03ae2c-4fab-4b31-9b62-684d2f7ba2df
,08-31 17:07:23.130  4152  4168 D BtGatt.GattService: onClientRegistered() - UUID=5a03ae2c-4fab-4b31-9b62-684d2f7ba2df, clientIf=5
,08-31 17:07:23.131  3798  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 17:07:23.132  4152  4189 D BtGatt.GattService: start scan with filters
,08-31 17:07:23.135  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 17:07:23.135  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:07:23.135  4152  4171 D BtGatt.ScanManager: handling starting scan
,08-31 17:07:23.135  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:07:23.135  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:07:23.137  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:07:23.137  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 17:07:23.137  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:07:23.138  4152  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64995c9
,08-31 17:07:23.139  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 17:07:23.140  4152  4168 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 17:07:23.140  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.140  4152  4171 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 17:07:23.140  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 17:07:23.141  3798  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 17:07:23.142  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:23.142  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 17:07:23.142  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.142  4152  4168 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 17:07:23.142  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.142  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:07:23.142  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:07:23.142  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:07:23.142  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:07:23.142  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:07:23.142  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:07:23.142  4152  4171 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:07:23.142  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:07:23.143  4152  4171 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 17:07:23.143  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:23.145  4152  4168 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 17:07:23.145  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.145  4152  4180 D BtGatt.GattService: stopScan() - queue size =1
08-31 17:07:23.145  4152  4189 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 17:07:23.146  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:23.146  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 17:07:23.146  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:07:23.146  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:07:23.146  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 17:07:23.146  4152  4168 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 17:07:23.146  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.147  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:23.147  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:07:23.147  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:07:23.147  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 17:07:23.148  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:23.148  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:23.149  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:23.149  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:07:23.149  4152  4168 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 17:07:23.150  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.150  4152  4171 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:07:23.150  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:23.150  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:23.151  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:23.151  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 17:07:23.151  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.151  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:23.151  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.151  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4757ec removed from the list
08-31 17:07:23.151  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.151  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab287b5 removed from the list
,08-31 17:07:23.151  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:23.151  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:23.153  4152  4168 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 17:07:23.153  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.154  4152  4171 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 17:07:23.154  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.155  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:23.155  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:23.156  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.156  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:23.156  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab287b5 not in the list
08-31 17:07:23.156  4152  4168 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 17:07:23.156  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.156  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.156  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:23.157  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.157  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:23.157  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.157  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64806d8 removed from the list
08-31 17:07:23.157  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.157  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.157  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.157  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.157  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@742a1bb removed from the list
08-31 17:07:23.158  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.158  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a2b884 added. We now have 2 listener(s)
,08-31 17:07:23.159  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 17:07:23.159  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.159  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.159  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:23.159   873  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 15:07:23 GMT], X-Android-Received-Millis=[1472656043157], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472656043126]}
,08-31 17:07:23.159  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@498f86d added. We now have 9 listener(s)
,08-31 17:07:23.160  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.160  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:07:23.160   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 17:07:23.160   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-31 17:07:23.160   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:23.161   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 17:07:23.162  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.163  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 17:07:23.165  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:23.166  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:23.168  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:23.168  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.168  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:23.168  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 17:07:23.168  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b058d33 added. We now have 3 listener(s)
,08-31 17:07:23.170  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:23.170  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.170  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.170  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:23.170  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad4d8f0 added. We now have 10 listener(s)
,08-31 17:07:23.170  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.170  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:23.171  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:23.171  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.171  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:23.171  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:23.171  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:23.171  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:07:23.173  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.174  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 17:07:23.174  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:07:23.175  3960  3960 D SprintDMHelper: simOperator: 
,08-31 17:07:23.175  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
08-31 17:07:23.177  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 17:07:23.178  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 17:07:23.178  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:07:23.181  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 17:07:23.181  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:07:23.181  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-31 17:07:23.182  3798  3847 D BluetoothAdapter: STATE_ON
08-31 17:07:23.184  4152  4204 D BtGatt.GattService: registerClient() - UUID=3b0d3419-d9b5-4d29-a57a-bb787bfd818e
,08-31 17:07:23.184  4152  4168 D BtGatt.GattService: onClientRegistered() - UUID=3b0d3419-d9b5-4d29-a57a-bb787bfd818e, clientIf=5
08-31 17:07:23.184  3798  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 17:07:23.184  4152  4163 D BtGatt.GattService: start scan with filters
,08-31 17:07:23.187  4152  4171 D BtGatt.ScanManager: handling starting scan
,08-31 17:07:23.187  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 17:07:23.187  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:07:23.188  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 17:07:23.188  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 17:07:23.189  4152  4168 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 17:07:23.189  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.189  4152  4171 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 17:07:23.190  4152  4168 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 17:07:23.190  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.191  4152  4171 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 17:07:23.191  4152  4171 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 17:07:23.192  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:07:23.192  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:07:23.193  4152  4168 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 17:07:23.193  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.193  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:07:23.195  4152  4168 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 17:07:23.195  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.197  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:07:23.200  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 17:07:23.200  3798  3847 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 17:07:23.200  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:23.200  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:07:23.200  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:07:23.201  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.201  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.201  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:07:23.201  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.201  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a2b884 removed from the list
,08-31 17:07:23.201  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.201  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@498f86d removed from the list
,08-31 17:07:23.201  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:23.201  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:23.202  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.202  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 17:07:23.202  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.202  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:23.203  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:23.203  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.203  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:23.203  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@498f86d not in the list
08-31 17:07:23.203  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:07:23.203  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:07:23.203  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:07:23.204  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:07:23.204  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 17:07:23.204  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:23.205  4152  4163 D BtGatt.GattService: stopScan() - queue size =1
08-31 17:07:23.205  4152  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 17:07:23.206  4152  4168 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 17:07:23.206  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:23.206  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.206  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:07:23.206  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:07:23.206  4152  4171 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:07:23.206  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:07:23.206  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:07:23.207  1698  4222 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 17:07:23.207  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:23.207  1698  4222 W BaseAppContext: Using Auth Proxy for data requests.
08-31 17:07:23.207  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:07:23.207  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:07:23.207  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 17:07:23.208  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.208  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.208  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:23.209  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.209  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:23.209  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:23.209  4152  4168 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 17:07:23.209  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:23.208  1698  4222 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
08-31 17:07:23.209  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.209  4152  4171 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 17:07:23.209  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad4d8f0 removed from the list
08-31 17:07:23.209  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.209  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.209  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.210  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.210  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b058d33 removed from the list
,08-31 17:07:23.210  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.210  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc6941c added. We now have 2 listener(s)
08-31 17:07:23.211  4152  4168 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-31 17:07:23.211  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.211  4152  4168 D BtGatt.GattService: current time is 155739955991
08-31 17:07:23.212  4152  4168 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-31 17:07:23.213  4152  4168 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-31 17:07:23.208  1698  4219 I SystemUpdateService: active receiver: enabled
,08-31 17:07:23.214  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 17:07:23.214  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 17:07:23.214  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.215  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:23.215  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e55c825 added. We now have 9 listener(s)
08-31 17:07:23.215  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:23.215  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:07:23.216  1698  2408 I iu.UploadsManager: num queued entries: 0
08-31 17:07:23.217  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.219  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:23.221  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:23.222  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:07:23.224  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:23.224  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:23.224  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.224  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db6fab added. We now have 3 listener(s)
,08-31 17:07:23.226  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.228  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:23.228  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.228  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.228  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:23.228  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:23.228  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b6d608 added. We now have 10 listener(s)
,08-31 17:07:23.228  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.229  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:23.229  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:23.229  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:23.229  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.229  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:07:23.231  3798  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 17:07:23.231  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:07:23.234  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:07:23.235  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 17:07:23.235  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:07:23.237  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 17:07:23.237  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:07:23.237  1698  2408 I iu.UploadsManager: num updated entries: 0
08-31 17:07:23.237  3798  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:07:23.238  3798  3847 D BluetoothAdapter: STATE_ON
,08-31 17:07:23.240  4152  4204 D BtGatt.GattService: registerClient() - UUID=9cff9699-34e2-4086-8e14-d9a0dd1e6214
,08-31 17:07:23.240  4152  4168 D BtGatt.GattService: onClientRegistered() - UUID=9cff9699-34e2-4086-8e14-d9a0dd1e6214, clientIf=5
08-31 17:07:23.240  3798  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 17:07:23.240  4152  4180 D BtGatt.GattService: start scan with filters
,08-31 17:07:23.244  1698  4219 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 17:07:23.245  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 17:07:23.245  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:07:23.245  4152  4171 D BtGatt.ScanManager: handling starting scan
08-31 17:07:23.245  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 17:07:23.245  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:07:23.249  1698  2408 I iu.SyncManager: NEXT; no task
,08-31 17:07:23.250  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:07:23.250  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:07:23.250  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:07:23.254  1698  4219 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 17:07:23.254  1698  4219 I SystemUpdateService: now status is 0 (complete)
,08-31 17:07:23.254  1698  4219 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 17:07:23.254  1698  4219 I SystemUpdateService: file has been verified
,08-31 17:07:23.254  1698  4219 I SystemUpdateService: OTA package size = 12249756
08-31 17:07:23.255  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 17:07:23.256  4152  4168 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 17:07:23.256  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.256  4152  4171 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 17:07:23.259  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:23.260  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:07:23.260  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:07:23.260  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.260  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.260  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:07:23.260  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 17:07:23.260  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc6941c removed from the list
08-31 17:07:23.260  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.260  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e55c825 removed from the list
08-31 17:07:23.260  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:23.260  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:23.261  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.261  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 17:07:23.261  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.261  1698  4219 I SystemUpdateService: showing system update notification
,08-31 17:07:23.261  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:23.263  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:23.263  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.263  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.264  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e55c825 not in the list
,08-31 17:07:23.264  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:07:23.264  4152  4168 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 17:07:23.264  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:07:23.264  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.264  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:07:23.264  4152  4171 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:07:23.264  4152  4171 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 17:07:23.264  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:07:23.264  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:07:23.265  3798  3847 D BluetoothAdapter: STATE_ON
08-31 17:07:23.266  4152  4163 D BtGatt.GattService: stopScan() - queue size =1
,08-31 17:07:23.267  4152  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 17:07:23.267  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:23.267  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:07:23.267  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 17:07:23.268  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:07:23.268  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:07:23.269  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:07:23.269  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:07:23.269  3798  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:07:23.269  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 17:07:23.270  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:23.271  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 17:07:23.272  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:07:23.272  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:07:23.272  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.272  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:23.272  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:23.272  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b6d608 removed from the list
08-31 17:07:23.272  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:23.272  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.273  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.273  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.273  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db6fab removed from the list
,08-31 17:07:23.274  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.274  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce74ab4 added. We now have 2 listener(s)
,08-31 17:07:23.275  4152  4168 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 17:07:23.275  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.277  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:23.277  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.278  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.278  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:23.278  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@275d6dd added. We now have 9 listener(s)
08-31 17:07:23.278  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:23.279  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:07:23.280  4152  4168 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 17:07:23.280  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.283  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:23.284  1511  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 17:07:23.284  1511  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 17:07:23.284  1511  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 17:07:23.284  1511  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 17:07:23.286  4152  4168 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:23.286  3798  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:23.286  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.286  4152  4171 D BtGatt.ScanManager: stopping BLe Batch
,08-31 17:07:23.288  3798  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:07:23.289  3798  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:07:23.289  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:23.289  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4c2923 added. We now have 3 listener(s)
,08-31 17:07:23.292  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.294  4152  4168 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 17:07:23.294  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 17:07:23.294  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:23.294  4152  4171 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 17:07:23.295  1698  1698 D SystemUpdateService: onDestroy
,08-31 17:07:23.297  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 17:07:23.297  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:23.297  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:23.298  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:23.298  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8085e20 added. We now have 10 listener(s)
,08-31 17:07:23.298  3798  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:23.298  3798  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:07:23.298  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:07:23.298  3798  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:07:23.299  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 17:07:23.299  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.299  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:23.299  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.299  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce74ab4 removed from the list
08-31 17:07:23.299  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 17:07:23.299  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@275d6dd removed from the list
08-31 17:07:23.299  3798  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:07:23.299  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.299  4152  4168 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 17:07:23.300  4152  4168 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 17:07:23.300  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:07:23.300  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.300  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:07:23.300  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.301  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:07:23.301  3798  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@275d6dd not in the list
08-31 17:07:23.301  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.301  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:23.301  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:23.302  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:23.302  3798  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 17:07:23.302  3798  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8085e20 removed from the list
08-31 17:07:23.302  3798  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 17:07:23.302  3798  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:23.302  3798  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:23.302  3798  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:23.302  3798  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4c2923 removed from the list
08-31 17:07:23.303  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 17:07:23.303  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 17:07:23.303  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 17:07:23.303  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:23.303  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 17:07:23.303  3798  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:23.309  3798  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
08-31 17:07:23.309  3798  4230 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-31 17:07:23.309  3798  4230 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 17:07:23.311  3798  4231 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,08-31 17:07:23.311  1698  4222 E MDM     : [177] SitrepService.a: Error sending sitrep.
08-31 17:07:23.311  3798  4231 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-31 17:07:23.311  3798  4231 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 17:07:23.312  3798  3847 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-31 17:07:23.313  3798  3847 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-31 17:07:23.313  3798  3847 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-31 17:07:23.313  3798  3847 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-31 17:07:23.313  3798  3847 D com.test.thalitest.ThaliTestRunner: Total duration: 21843 ms
,08-31 17:07:23.315  3798  3847 I jxcore-log: *Native tests were executed*
08-31 17:07:23.315  3798  3847 I jxcore-log: 
08-31 17:07:23.315  3798  3847 I jxcore-log: Total number of executed tests:  80
08-31 17:07:23.315  3798  3847 I jxcore-log: 
,08-31 17:07:23.315  3798  3847 I jxcore-log: Number of passed tests:  80
08-31 17:07:23.315  3798  3847 I jxcore-log: 
08-31 17:07:23.315  3798  3847 I jxcore-log: Number of failed tests:  0
08-31 17:07:23.315  3798  3847 I jxcore-log: 
,08-31 17:07:23.315  3798  3847 I jxcore-log: Number of ignored tests:  0
08-31 17:07:23.315  3798  3847 I jxcore-log: 
,08-31 17:07:23.316  3798  3847 I jxcore-log: Total duration:  21843
08-31 17:07:23.316  3798  3847 I jxcore-log: 
08-31 17:07:23.316  3798  3847 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 17:07:23.316  3798  3847 I jxcore-log: 
,08-31 17:07:23.321  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.321  3798  3847 I jxcore-log: 
08-31 17:07:23.323  3798  3798 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 17:07:23.324  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.324  3798  3847 I jxcore-log: 
08-31 17:07:23.325  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.325  3798  3847 I jxcore-log: 
08-31 17:07:23.326  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.326  3798  3847 I jxcore-log: 
08-31 17:07:23.326  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.326  3798  3847 I jxcore-log: 
08-31 17:07:23.327  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.327  3798  3847 I jxcore-log: 
08-31 17:07:23.329  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.329  3798  3847 I jxcore-log: 
08-31 17:07:23.331  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.331  3798  3847 I jxcore-log: 
08-31 17:07:23.331  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.331  3798  3847 I jxcore-log: 
08-31 17:07:23.332  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:07:23.332  3798  3847 I jxcore-log: 
08-31 17:07:23.333  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:07:23.333  3798  3847 I jxcore-log: 
,08-31 17:07:23.334  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:07:23.334  3798  3847 I jxcore-log: 
08-31 17:07:23.334  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.334  3798  3847 I jxcore-log: 
,08-31 17:07:23.335  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.335  3798  3847 I jxcore-log: 
,08-31 17:07:23.336  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.336  3798  3847 I jxcore-log: 
08-31 17:07:23.336  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.336  3798  3847 I jxcore-log: 
,08-31 17:07:23.337  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.337  3798  3847 I jxcore-log: 
08-31 17:07:23.338  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.338  3798  3847 I jxcore-log: 
,08-31 17:07:23.338  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.338  3798  3847 I jxcore-log: 
,08-31 17:07:23.339  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.339  3798  3847 I jxcore-log: 
,08-31 17:07:23.339  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.339  3798  3847 I jxcore-log: 
08-31 17:07:23.340  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:23.340  3798  3847 I jxcore-log: 
08-31 17:07:23.341  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:07:23.341  3798  3847 I jxcore-log: 
,08-31 17:07:23.341  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:07:23.341  3798  3847 I jxcore-log: 
08-31 17:07:23.342  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.342  3798  3847 I jxcore-log: 
,08-31 17:07:23.342  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.342  3798  3847 I jxcore-log: 
08-31 17:07:23.343  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.343  3798  3847 I jxcore-log: 
,08-31 17:07:23.343  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.343  3798  3847 I jxcore-log: 
,08-31 17:07:23.344  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.344  3798  3847 I jxcore-log: 
,08-31 17:07:23.345  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:23.345  3798  3847 I jxcore-log: 
,08-31 17:07:23.369  2246  4226 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 17:07:23.649  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:07:23.653  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:07:23.653  3798  3847 I jxcore-log: 
,08-31 17:07:23.709  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:07:23.712  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:07:23.712  3798  3847 I jxcore-log: 
,08-31 17:07:23.772  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:07:23.774  3798  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:07:23.774  3798  3847 I jxcore-log: 
,08-31 17:07:24.015  4233  4233 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 17:07:24.020  4233  4233 D AndroidRuntime: CheckJNI is OFF
,08-31 17:07:24.062  4233  4233 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 17:07:24.073   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-31 17:07:24.110  4233  4233 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 17:07:24.132  4233  4233 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 17:07:24.145   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 17:07:24.145   873   886 I ActivityManager: Killing 3798:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 17:07:24.250   873   896 W PackageSettings: Skipping PackageSetting{b880d52 com.example.hello/10273} due to missing metadata
,08-31 17:07:24.259   873   884 I WindowState: WIN DEATH: Window{492ac5d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 17:07:24.259   873  2023 D GraphicsStats: Buffer count: 2
,08-31 17:07:24.260   873  1308 D WifiService: Client connection lost with reason: 4
,08-31 17:07:24.293   873   896 I art     : Starting a blocking GC Explicit
,08-31 17:07:24.301   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 17:07:24.303   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 17:07:24.304   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-31 17:07:24.304   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 17:07:24.304   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.304   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.304   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 17:07:24.304   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 17:07:24.308   873   886 I ActivityManager:   Force finishing activity ActivityRecord{141921a u0 com.test.thalitest/.MainActivity t2}
,08-31 17:07:24.318   873   883 W ActivityManager: Spurious death for ProcessRecord{b649676 0:com.test.thalitest/u0a0}, curProc for 3798: null
,08-31 17:07:24.353   873   896 I art     : Explicit concurrent mark sweep GC freed 54370(3MB) AllocSpace objects, 9(228KB) LOS objects, 33% free, 29MB/43MB, paused 913us total 59.113ms
,08-31 17:07:24.377   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 17:07:24.381  4233  4233 I art     : System.exit called, status: 0
,08-31 17:07:24.381  4233  4233 I AndroidRuntime: VM exiting with result code 0.
,08-31 17:07:24.382   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 17:07:24.400   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 17:07:24.404  4152  4152 D BluetoothMapAppObserver: onReceive
,08-31 17:07:24.404  4152  4152 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-31 17:07:24.404  1898  1898 I Keyboard.Facilitator: resetDictionaries() : en_US
08-31 17:07:24.405  1869  2281 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 17:07:24.406  3661  3661 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 17:07:24.418   873  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 17:07:24.430  1898  4244 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 17:07:24.438  1869  2658 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-31 17:07:24.443   873  1385 I ActivityManager: Start proc 4247:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 17:07:24.458  1975  1975 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 17:07:24.464  1898  4244 I Decoder : createOrResetDecoder
,08-31 17:07:24.483  1511  1511 I ConfigService: onCreate
,08-31 17:07:24.503  4247  4247 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 17:07:24.504   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
08-31 17:07:24.506  1898  4244 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 17:07:24.519   873  1386 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3798 uid 10000
,08-31 17:07:24.520  1898  1898 I Keyboard.Facilitator: onFinishInput()
,08-31 17:07:24.532  1993  2105 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 17:07:24.533   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-31 17:07:24.533   873   885 E PackageManager: Failed to write settings, restoring backup
08-31 17:07:24.533   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 17:07:24.533   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 17:07:24.533   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 17:07:24.533   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 17:07:24.533   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 17:07:24.533   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.533   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.533   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 17:07:24.543  1898  4244 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 17:07:24.545  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 17:07:24.545  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 17:07:24.548   873  2011 I ActivityManager: Start proc 4262:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-31 17:07:24.549  1993  2105 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 17:07:24.549  1993  2105 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1993
08-31 17:07:24.549  1993  2105 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.549  1993  2105 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 17:07:24.549  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 17:07:24.549  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 17:07:24.549  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-31 17:07:24.549  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 17:07:24.550  1898  4244 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 17:07:24.550  1898  4244 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 17:07:24.550  1898  4244 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 17:07:24.550  1898  4244 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 17:07:24.550  1898  4244 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 17:07:24.551  1898  4244 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-31 17:07:24.551   873  2134 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 17:07:24.557   873  4267 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:07:24.557   873  4267 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.557   873  4267 E DropBoxManagerService: 	... 5 more
08-31 17:07:24.557   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-31 17:07:24.557   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 17:07:24.557   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.557   873   886 E DropBoxManagerService: 	... 13 more
,08-31 17:07:24.560  1993  2105 I Process : Sending signal. PID: 1993 SIG: 9
,08-31 17:07:24.582  4247  4247 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 17:07:24.598  4247  4278 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 17:07:24.604   873  2138 I ActivityManager: Start proc 4279:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver,
,08-31 17:07:24.607   873  1385 D GraphicsStats: Buffer count: 1
08-31 17:07:24.607   873  2136 I WindowState: WIN DEATH: Window{7e45d65 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 17:07:24.631  4247  4269 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.631  4247  4269 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.632  4247  4269 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 17:07:24.632   873  1988 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1993) has died
,08-31 17:07:24.634   873  1988 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-31 17:07:24.636   873  1988 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 17:07:24.654   873   884 I ActivityManager: Start proc 4292:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 17:07:24.667  4279  4279 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 17:07:24.691  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 17:07:24.691  1511  1511 D AndroidRuntime: Shutting down VM
,08-31 17:07:24.692  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-31 17:07:24.692  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-31 17:07:24.692  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
,08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 17:07:24.692  1511  1511 E AndroidRuntime: 	... 8 more
08-31 17:07:24.694   873  4307 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:07:24.694   873  4307 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.694   873  4307 E DropBoxManagerService: 	... 5 more
,08-31 17:07:24.695  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
,08-31 17:07:24.702  4292  4292 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.702  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 17:07:24.703  4292  4292 D AndroidRuntime: Shutting down VM
,08-31 17:07:24.709  4292  4292 E AndroidRuntime: FATAL EXCEPTION: main
08-31 17:07:24.709  4292  4292 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4292
08-31 17:07:24.709  4292  4292 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 17:07:24.709  4292  4292 E AndroidRuntime: 	... 10 more
08-31 17:07:24.710   873  2138 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 17:07:24.711  4292  4292 I Process : Sending signal. PID: 4292 SIG: 9
,08-31 17:07:24.715   873  4309 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:07:24.715   873  4309 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.715   873  4309 E DropBoxManagerService: 	... 5 more
,08-31 17:07:24.735  4247  4269 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-31 17:07:24.739  4247  4278 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.739  4247  4278 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 17:07:24.740  4247  4278 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 17:07:24.740  4247  4278 E AndroidRuntime: Process: android.process.acore, PID: 4247
08-31 17:07:24.740  4247  4278 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.740  4247  4278 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 17:07:24.741  4247  4269 I Process : Sending signal. PID: 4247 SIG: 9
,08-31 17:07:24.749   873  1308 D WifiService: Client connection lost with reason: 4
,08-31 17:07:24.755   873  1386 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4292) has died
,08-31 17:07:24.756   873  1386 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 17:07:24.759   278   278 E lowmemorykiller: Error writing /proc/4247/oom_score_adj; errno=22
,08-31 17:07:24.761   873  2129 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
,08-31 17:07:24.761   873  2129 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-31 17:07:24.761   873  2129 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-31 17:07:24.761   873  2129 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-31 17:07:24.761   873  2129 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,08-31 17:07:24.762   278   278 E lowmemorykiller: Error writing /proc/4247/oom_score_adj; errno=22
,08-31 17:07:24.774   873   886 I ActivityManager: Start proc 4311:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 17:07:24.779   873  4317 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:07:24.779   873  4317 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.779   873  4317 E DropBoxManagerService: 	... 5 more
,08-31 17:07:24.784  1698  1698 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-31 17:07:24.799   873  2021 I ActivityManager: Start proc 4325:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-31 17:07:24.806   873  2136 I ActivityManager: Process android.process.acore (pid 4247) has died
,08-31 17:07:24.807   873  2136 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40954ms
,08-31 17:07:24.838  4311  4311 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.838  4311  4311 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 17:07:24.838  4311  4311 D AndroidRuntime: Shutting down VM
08-31 17:07:24.840  4325  4325 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm,
,08-31 17:07:24.849  4311  4311 E AndroidRuntime: FATAL EXCEPTION: main
08-31 17:07:24.849  4311  4311 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4311
08-31 17:07:24.849  4311  4311 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 17:07:24.849  4311  4311 E AndroidRuntime: 	... 10 more
,08-31 17:07:24.851   873  1386 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 17:07:24.851  4311  4311 I Process : Sending signal. PID: 4311 SIG: 9
08-31 17:07:24.852   873  4339 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:07:24.852   873  4339 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.852   873  4339 E DropBoxManagerService: 	... 5 more
08-31 17:07:24.852  4325  4325 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 17:07:24.852  4325  4325 I MultiDex: install
08-31 17:07:24.852  4325  4325 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 17:07:24.856  4325  4325 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-31 17:07:24.860  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 17:07:24.860  4325  4325 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-31 17:07:24.860  1698  1698 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 17:07:24.862  4325  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.862  4325  4325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:24.862  4325  4325 D AndroidRuntime: Shutting down VM
,08-31 17:07:24.863  4325  4325 E AndroidRuntime: FATAL EXCEPTION: main
08-31 17:07:24.863  4325  4325 E AndroidRuntime: Process: com.google.process.gapps, PID: 4325
08-31 17:07:24.863  4325  4325 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-31 17:07:24.863  4325  4325 E AndroidRuntime: 	... 10 more
,08-31 17:07:24.865  4325  4325 I Process : Sending signal. PID: 4325 SIG: 9
08-31 17:07:24.866   873  4340 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:07:24.866   873  4340 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 17:07:24.866   873  4340 E DropBoxManagerService: 	... 5 more
,08-31 17:07:24.873  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 17:07:24.873  1698  1698 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 17:07:24.878   873  1989 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,08-31 17:07:24.878   873  1989 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-31 17:07:24.878   873  1989 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-31 17:07:24.878   873  1989 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 17:07:24.879  1698  4342 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 17:07:24.893   873  1989 I ActivityManager: Start proc 4344:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-31 17:07:24.894   873  2129 W ActivityManager: Spurious death for ProcessRecord{3f3ba5 4344:com.google.android.googlequicksearchbox/u0a28}, curProc for 4311: null
,08-31 17:07:24.895  2070  4341 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-31 17:07:24.896   873  1988 I ActivityManager: Process com.google.process.gapps (pid 4325) has died
08-31 17:07:24.896   873  1988 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ce74ab4 u0 com.google.android.gms/.auth.GetToken}
,08-31 17:07:24.896   873  1988 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ae31d4f u0 com.google.android.gms/.config.ConfigService}
08-31 17:07:24.896   873  1988 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{40813e1 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-31 17:07:24.897   873  1988 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{30ed441 u0 com.google.android.gms/.gcm.GcmService}
,08-31 17:07:24.900  1698  4342 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-31 17:07:24.900  1698  4342 E AndroidRuntime: Process: com.google.android.gms, PID: 1698
08-31 17:07:24.900  1698  4342 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 17:07:24.900  1698  4342 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-31 17:07:24.908   873  1988 I ActivityManager: Start proc 4356:com.google.process.gapps/u0a11 for restart com.google.process.gapps

```
