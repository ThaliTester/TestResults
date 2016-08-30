#### Test 828653623f51f5b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-30 13:28:53.076  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 13:28:53.087  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 13:28:53.089  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 13:28:53.129  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 13:28:53.129  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 13:28:53.129  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:28:53.129  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 13:28:53.154  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 13:28:53.154  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 13:28:53.155  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 13:28:53.692  3790  3790 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 13:28:53.697  3790  3790 D AndroidRuntime: CheckJNI is OFF
08-30 13:28:53.740  3790  3790 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 13:28:53.790  3790  3790 I Radio-JNI: register_android_hardware_Radio DONE
08-30 13:28:53.812  3790  3790 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 13:28:53.816   873  2137 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 13:28:53.848  2044  2061 W SearchService: Abort, client detached.
08-30 13:28:53.860  2044  2044 I HotwordDetector: Closing mic
08-30 13:28:53.860  2044  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a8708b8
08-30 13:28:53.861  2044  2357 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 13:28:53.864  3790  3790 D AndroidRuntime: Shutting down VM
08-30 13:28:53.880   873  2074 I ActivityManager: Start proc 3799:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 13:28:53.909   377  2359 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 13:28:53.911   377  2359 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 13:28:53.918   377  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 13:28:53.920  2044  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 13:28:53.922  2044  2356 I MicroRecognitionRnrImpl: Detection finished
08-30 13:28:53.949  3799  3799 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 13:28:53.979  3799  3799 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 13:28:53.987  3799  3799 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1608-1610)
08-30 13:28:53.987  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 13:28:54.000  3799  3799 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f872a0}
08-30 13:28:54.001  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 13:28:54.002  3799  3799 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 13:28:54.010  3799  3799 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 13:28:54.012  3799  3799 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 13:28:54.040  3799  3799 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 13:28:54.049  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 13:28:54.049  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 13:28:54.049  3799  3799 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 13:28:54.049  3799  3799 I Adreno  : Build Date                       : 10/20/15
08-30 13:28:54.049  3799  3799 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 13:28:54.049  3799  3799 I Adreno  : Local Branch                     : M14
08-30 13:28:54.049  3799  3799 I Adreno  : Remote Branch                    : 
08-30 13:28:54.049  3799  3799 I Adreno  : Remote Branch                    : 
08-30 13:28:54.049  3799  3799 I Adreno  : Reconstruct Branch               : 
08-30 13:28:54.104   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6168c3:true
,08-30 13:28:54.155  3799  3799 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 13:28:54.169   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 13:28:54.172  3799  3799 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 13:28:54.246  3799  3837 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 13:28:54.260  3799  3824 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 13:28:54.310  3799  3837 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 13:28:54.368   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +502ms
,08-30 13:28:54.373  1889  1889 I Keyboard.Facilitator: onFinishInput()
,08-30 13:28:54.423  3799  3799 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3799
,08-30 13:28:54.450   873  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 13:28:54.510  3799  3799 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 13:28:54.669   873   884 I ActivityManager: Killing 2982:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 13:28:54.700   873   884 I ActivityManager: Killing 3205:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 13:28:54.705  3799  3839 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1695614672
,08-30 13:28:54.710  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 13:28:54.710  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 13:28:54.710  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 13:28:54.710  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 13:28:54.710  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 13:28:54.711  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aeafeb7 added. We now have 1 listener(s)
08-30 13:28:54.714  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 13:28:54.715  3799  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:28:54.715  3799  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:28:54.716  3799  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 13:28:54.719  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193a342 added. We now have 1 listener(s)
08-30 13:28:54.719  3799  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:28:54.723   873  1315 D WifiService: New client listening to asynchronous messages
,08-30 13:28:54.724  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:28:54.724  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 13:28:54.724  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 13:28:54.724  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 13:28:54.724  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 13:28:54.729  3799  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:28:54.729  3799  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 13:28:54.735  3799  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:28:54.736  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 13:28:54.736  3799  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 13:28:54.736  3799  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:28:54.736  3799  3839 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 13:28:54.738  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:28:54.740  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:28:54.764  3799  3799 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 13:28:55.610  3799  3848 W jxcore-log: Initializing JXcore engine
,08-30 13:28:55.611  3799  3848 W jxcore-log: JXcore engine is ready
,08-30 13:28:55.646  3848  3848 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 13:28:55.646  3848  3848 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11934]" dev="sockfs" ino=11934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 13:28:55.646  3848  3848 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 13:28:55.646  3848  3848 W Thread-329: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[23472]" dev="sockfs" ino=23472 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 13:28:55.665  3799  3848 W jxcore-log: Starting JXcore engine
,08-30 13:28:55.748  3799  3848 W jxcore-log: Platform android
08-30 13:28:55.748  3799  3848 W jxcore-log: 
,08-30 13:28:55.749  3799  3848 W jxcore-log: Process ARCH arm
08-30 13:28:55.749  3799  3848 W jxcore-log: 
,08-30 13:28:55.978  3799  3848 I jxcore-log: JXcore Cordova bridge is ready!
08-30 13:28:55.978  3799  3848 I jxcore-log: 
,08-30 13:28:55.978  3799  3848 W jxcore-log: JXcore engine is started
,08-30 13:28:55.987  3799  3839 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 13:28:55.992  3799  3799 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 13:28:57.193   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 13:28:58.211  3610  3850 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 13:28:58.262  3610  3851 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 13:28:58.275  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:28:58.279  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:28:58.313  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:28:58.314  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 13:28:58.314  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:28:58.314  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:28:58.338  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:28:58.340  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:28:58.357  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:28:58.357  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:28:58.358  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:28:58.358  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:28:58.375  3610  3851 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 13:28:58.375  3610  3850 E BooksSync: Soft error
08-30 13:28:58.375  3610  3850 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:28:58.375  3610  3850 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:28:58.376  3610  3850 E BooksSync: Sync error
08-30 13:28:58.376  3610  3850 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:28:58.376  3610  3850 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:28:58.376  3610  3850 I BooksSync: Finished books sync
,08-30 13:28:58.379   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125770, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:29:10.329  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 13:29:10.329  3799  3848 I jxcore-log: 
,08-30 13:29:10.332  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 13:29:10.332  3799  3848 I jxcore-log: 
,08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:10.345  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:10.351  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:10.353  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 13:29:10.353  3799  3848 I jxcore-log: 
,08-30 13:29:10.355  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 13:29:10.355  3799  3848 I jxcore-log: 
,08-30 13:29:10.716  3799  3848 I jxcore-log: Running unit tests
08-30 13:29:10.716  3799  3848 I jxcore-log: 
,08-30 13:29:10.716  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:29:10.716  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@583c1d3 added. We now have 2 listener(s)
08-30 13:29:10.718  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:29:10.718  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:29:10.718  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:29:10.718  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:29:10.718  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5a0110 added. We now have 2 listener(s)
08-30 13:29:10.718  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:29:10.719  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:29:10.729  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:10.748  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:10.754  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:10.754  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:29:10.754  3799  3848 D executeNativeTests: Running unit tests
,08-30 13:29:10.761  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:10.764  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:10.843  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:29:10.843  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe added. We now have 3 listener(s)
,08-30 13:29:10.844  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 13:29:10.844  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 13:29:10.844  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 13:29:10.844  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:29:10.844  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f added. We now have 3 listener(s)
08-30 13:29:10.844  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:29:10.845  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 13:29:10.847  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:10.855  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:10.863  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:10.864  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:29:10.866  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 13:29:10.868  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 13:29:10.868  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 13:29:10.868  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 13:29:10.868  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:10.869  3799  3848 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 13:29:10.869  3799  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 13:29:10.869  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 13:29:10.870  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 13:29:10.870  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 13:29:10.870  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 13:29:10.870  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:10.870  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:10.871  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:10.871  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:10.871  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.871  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:29:10.871  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 13:29:10.871  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe removed from the list
08-30 13:29:10.871  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:10.871  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f removed from the list
08-30 13:29:10.873  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:10.873  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:10.873  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.877  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:10.878  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.880  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:10.881  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:10.881  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:10.881  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:10.886  3799  3848 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 13:29:10.888  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:10.889  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:10.889  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:10.890  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:10.890  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.890  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.890  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:10.891  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:10.891  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:10.891  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:10.891  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.891  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.892  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.892  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.897  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:10.897  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:10.897  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:10.897  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 13:29:10.903  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 13:29:10.904  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 13:29:10.905  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 13:29:10.905  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 13:29:10.905  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 13:29:10.905  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 13:29:10.905  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:10.905  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:10.905  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:10.905  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:10.905  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.905  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.905  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:10.905  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:10.906  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:10.906  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:10.906  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.906  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.906  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:10.906  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:10.907  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:10.907  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:10.907  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:10.907  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:10.908  3799  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 13:29:10.909  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:10.915  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 13:29:10.918  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:10.918  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:29:10.918  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:29:10.918  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 13:29:10.919  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 13:29:10.919  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:29:10.919  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 13:29:10.920  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:10.922  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:10.923  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 13:29:10.923  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 13:29:10.928  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 13:29:10.930  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 13:29:10.930  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 13:29:10.933  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 13:29:10.935  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 13:29:10.936  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 13:29:10.936  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 13:29:10.937  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 13:29:10.938  3799  3848 D BluetoothAdapter: STATE_ON
08-30 13:29:10.943  2691  2828 D BtGatt.GattService: registerClient() - UUID=1323021d-29d3-46ef-a5a0-c1d1db429af8
08-30 13:29:10.944  2691  2713 D BtGatt.GattService: onClientRegistered() - UUID=1323021d-29d3-46ef-a5a0-c1d1db429af8, clientIf=5
08-30 13:29:10.945  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 13:29:10.946  2691  2827 D BtGatt.GattService: start scan with filters
08-30 13:29:10.949  2691  2716 D BtGatt.ScanManager: handling starting scan
08-30 13:29:10.949  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 13:29:10.950  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 13:29:10.950  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 13:29:10.950  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 13:29:10.950  2691  2716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:10.953  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:29:10.954  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 13:29:10.954  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:29:10.957  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:29:10.958  2691  2713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 13:29:10.958  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:10.958  2691  2716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:29:10.962  3799  3848 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 13:29:10.964  2691  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 13:29:10.964  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:10.964  2691  2716 D BtGatt.ScanManager: Starting BLE batch scan
08-30 13:29:10.964  2691  2716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 13:29:10.975  2691  2713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 13:29:10.975  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:10.981  2691  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 13:29:10.981  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:11.456  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 13:29:11.456  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:29:11.457  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:29:12.485  2691  2691 D BtGatt.ScanManager: awakened up at time 140108
,08-30 13:29:12.490  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:12.523  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 13:29:12.523  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:12.524  2691  2713 D BtGatt.GattService: current time is 140148122929
08-30 13:29:12.524  2691  2713 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -90, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -94, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -66, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 13:29:12.526  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 13:29:12.527  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 13:29:12.527  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 13:29:12.527  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 13:29:12.528  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-30 13:29:12.528  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 13:29:14.031  2691  2691 D BtGatt.ScanManager: awakened up at time 141655
,08-30 13:29:14.033  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:14.097  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-30 13:29:14.097  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:14.097  2691  2713 D BtGatt.GattService: current time is 141721884596
,08-30 13:29:14.098  2691  2713 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -93, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 13:29:14.099  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-30 13:29:14.100  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 13:29:14.100  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-30 13:29:14.101  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 13:29:14.270  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:14.284  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:14.288  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:14.339  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 13:29:14.339  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 13:29:14.340  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:29:14.340  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:14.377  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 13:29:14.378  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 13:29:14.379  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 13:29:15.602  2691  2691 D BtGatt.ScanManager: awakened up at time 143226
,08-30 13:29:15.605  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:15.616  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 13:29:15.616  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:15.972  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:29:15.972  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:15.973  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 13:29:15.973  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:15.973  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 13:29:15.974  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 13:29:15.974  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 13:29:15.974  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 13:29:15.975  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:29:15.976  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 13:29:15.977  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 13:29:15.979  3799  3848 D BluetoothAdapter: STATE_ON
08-30 13:29:15.982  2691  2827 D BtGatt.GattService: stopScan() - queue size =1
,08-30 13:29:15.984  2691  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 13:29:15.985  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 13:29:15.986  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 13:29:15.986  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 13:29:15.987  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:29:15.987  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 13:29:15.990  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:29:15.992  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 13:29:15.992  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 13:29:15.993  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 13:29:15.995  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:29:15.998  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:15.998  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:29:15.998  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:15.998  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:29:15.998  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:29:15.999  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:29:15.999  2691  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 13:29:15.999  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:15.999  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:15.999  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:16.000  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:16.000  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:16.000  2691  2716 D BtGatt.ScanManager: stopping BLe Batch
08-30 13:29:16.000  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:16.013  2691  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 13:29:16.014  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:16.014  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:16.029  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 13:29:16.029  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:16.500  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:29:21.002  3799  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 13:29:21.010  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:21.024  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:21.031  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:21.032  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:29:21.033  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 13:29:21.033  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 13:29:21.034  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 13:29:21.034  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 13:29:21.034  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 13:29:21.041  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:21.049  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 13:29:21.049  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:29:21.050  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:21.064  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:29:21.066  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 13:29:21.066  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:29:21.072  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 13:29:21.072  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 13:29:21.072  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 13:29:21.074  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:29:21.078  2691  2820 D BtGatt.GattService: registerClient() - UUID=b8403f49-a42f-4ff7-99dd-a5185e6c8206
,08-30 13:29:21.079  2691  2713 D BtGatt.GattService: onClientRegistered() - UUID=b8403f49-a42f-4ff7-99dd-a5185e6c8206, clientIf=5
,08-30 13:29:21.080  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 13:29:21.081  2691  2703 D BtGatt.GattService: start scan with filters
,08-30 13:29:21.085  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 13:29:21.085  2691  2716 D BtGatt.ScanManager: handling starting scan
08-30 13:29:21.085  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 13:29:21.086  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 13:29:21.086  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 13:29:21.090  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:29:21.090  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 13:29:21.090  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 13:29:21.091  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:29:21.094  2691  2713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 13:29:21.094  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.095  3799  3848 I io.jxcore.node.ConnectionHelper: start: OK
08-30 13:29:21.095  2691  2716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:29:21.102  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:29:21.102  3799  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 13:29:21.102  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:21.102  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:29:21.102  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:21.102  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 13:29:21.102  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 13:29:21.102  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 13:29:21.103  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 13:29:21.103  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:29:21.103  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 13:29:21.103  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 13:29:21.105  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:29:21.106  2691  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 13:29:21.106  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:21.107  2691  2827 D BtGatt.GattService: stopScan() - queue size =1
08-30 13:29:21.107  2691  2716 D BtGatt.ScanManager: Starting BLE batch scan
08-30 13:29:21.107  2691  2716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 13:29:21.109  2691  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:29:21.110  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 13:29:21.111  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 13:29:21.111  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 13:29:21.111  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:29:21.112  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 13:29:21.114  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:29:21.115  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 13:29:21.116  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 13:29:21.120  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 13:29:21.121  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:29:21.123  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:29:21.123  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:21.123  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:29:21.123  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:29:21.123  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:21.124  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:21.124  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:29:21.124  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:21.124  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:21.124  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:21.124  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:29:21.125  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:21.125  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:21.126  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:21.126  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:29:21.126  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:21.127  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:21.127  3799  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 13:29:21.129  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:29:21.134  2691  2713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 13:29:21.134  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:21.141  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:21.146  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:21.146  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:29:21.148  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 13:29:21.149  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 13:29:21.150  2691  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 13:29:21.150  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.151  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 13:29:21.151  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:21.151  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:29:21.151  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:29:21.156  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:21.159  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 13:29:21.159  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:29:21.166  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:29:21.167  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 13:29:21.167  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:29:21.168  2691  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 13:29:21.168  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.168  2691  2716 D BtGatt.ScanManager: stopping BLe Batch
,08-30 13:29:21.172  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 13:29:21.172  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 13:29:21.172  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 13:29:21.173  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:29:21.177  2691  2827 D BtGatt.GattService: registerClient() - UUID=d173790b-8f90-4dee-92fa-c30ef66061ab
,08-30 13:29:21.177  2691  2713 D BtGatt.GattService: onClientRegistered() - UUID=d173790b-8f90-4dee-92fa-c30ef66061ab, clientIf=5
,08-30 13:29:21.178  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 13:29:21.178  2691  2828 D BtGatt.GattService: start scan with filters
,08-30 13:29:21.184  2691  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 13:29:21.184  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 13:29:21.185  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:21.185  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 13:29:21.185  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 13:29:21.185  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 13:29:21.186  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:21.194  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 13:29:21.194  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:29:21.194  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 13:29:21.196  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 13:29:21.196  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.199  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:29:21.199  2691  2716 D BtGatt.ScanManager: handling starting scan
,08-30 13:29:21.207  3799  3848 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 13:29:21.209  2691  2713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 13:29:21.209  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.209  2691  2716 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:29:21.218  2691  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 13:29:21.218  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.218  2691  2716 D BtGatt.ScanManager: Starting BLE batch scan
08-30 13:29:21.218  2691  2716 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 13:29:21.232  2691  2713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 13:29:21.232  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.239  2691  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 13:29:21.239  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:21.391   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 13:29:21.695  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 13:29:21.696  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:29:21.696  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:29:22.389   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 13:29:22.399  1889  1889 I Keyboard.Facilitator: onFinishInput()
,08-30 13:29:22.407   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 13:29:22.407   873   893 I Adreno  : Build Date                       : 10/20/15
08-30 13:29:22.407   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 13:29:22.407   873   893 I Adreno  : Local Branch                     : M14
08-30 13:29:22.407   873   893 I Adreno  : Remote Branch                    : 
08-30 13:29:22.407   873   893 I Adreno  : Remote Branch                    : 
08-30 13:29:22.407   873   893 I Adreno  : Reconstruct Branch               : 
,08-30 13:29:22.443   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (200 us)
,08-30 13:29:22.749  2691  2691 D BtGatt.ScanManager: awakened up at time 150373
,08-30 13:29:22.757  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:22.790  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 13:29:22.790  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:22.791  2691  2713 D BtGatt.GattService: current time is 150415294472
08-30 13:29:22.793  2691  2713 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -88, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -94, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 13:29:22.795  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 13:29:22.797  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 13:29:22.801  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 13:29:22.802  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 13:29:22.804  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 13:29:22.806  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 13:29:23.071  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 13:29:23.071  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 13:29:23.109  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9668ef6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@47b4770, 16908290=android.view.AbsSavedState$1@47b4770}, android:focusedViewId=100}]}]
,08-30 13:29:23.109   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
08-30 13:29:23.109  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 13:29:23.109  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 13:29:23.109  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 13:29:23.121   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 13:29:23.125   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 13:29:23.125   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-30 13:29:23.125   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 13:29:23.158   873   882 I art     : Background partial concurrent mark sweep GC freed 24658(1646KB) AllocSpace objects, 7(176KB) LOS objects, 33% free, 29MB/43MB, paused 1.395ms total 119.461ms
,08-30 13:29:23.353   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 13:29:23.358   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 13:29:23.364   873  1340 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-30 13:29:23.369   873   893 I DreamManagerService: Entering dreamland.
,08-30 13:29:23.372   873   893 I PowerManagerService: Dozing...
,08-30 13:29:23.373   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 13:29:23.420   377  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 13:29:23.420   377  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 13:29:23.426  2691  2691 D BtGatt.ScanManager: awakened up at time 151050
,08-30 13:29:23.427  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:23.437   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:29:23.446  1964  3866 D NfcService: Discovery configuration equal, not updating.
,08-30 13:29:23.448  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-30 13:29:23.448  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:23.448  2691  2713 D BtGatt.GattService: current time is 151072459069
08-30 13:29:23.448  2691  2713 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 13:29:23.449  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 13:29:23.449  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-30 13:29:23.450  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 13:29:23.450  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 13:29:23.457   873  1314 E native  : do suspend false
,08-30 13:29:23.478   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 13:29:23.491   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:29:23.496   873  1314 E native  : do suspend true
,08-30 13:29:23.559   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-30 13:29:23.559   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 13:29:23.944   873  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 13:29:24.954  2691  2691 D BtGatt.ScanManager: awakened up at time 152578
,08-30 13:29:24.956  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:29:24.987  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-30 13:29:24.988  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:24.988  2691  2713 D BtGatt.GattService: current time is 152612535932
08-30 13:29:24.989  2691  2713 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 13:29:24.991  2691  2713 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 13:29:26.207  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:26.207  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:26.207  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:29:26.207  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:26.207  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 13:29:26.207  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 13:29:26.207  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 13:29:26.207  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 13:29:26.208  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:29:26.208  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 13:29:26.208  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 13:29:26.210  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:29:26.211  2691  2827 D BtGatt.GattService: stopScan() - queue size =1
,08-30 13:29:26.213  2691  2820 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:29:26.215  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 13:29:26.215  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 13:29:26.215  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 13:29:26.216  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:29:26.216  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 13:29:26.216  2691  2691 D BtGatt.ScanManager: awakened up at time 153840
08-30 13:29:26.218  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:29:26.219  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 13:29:26.219  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 13:29:26.219  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 13:29:26.223  2691  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 13:29:26.224  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:26.224  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:29:26.224  2691  2716 D BtGatt.ScanManager: stopping BLe Batch,
08-30 13:29:26.230  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:29:26.230  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:29:26.231  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:29:26.237  2691  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 13:29:26.237  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:29:26.238  2691  2716 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-30 13:29:26.252  2691  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 13:29:26.252  2691  2713 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:29:26.732  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:29:26.733  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:26.733  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:29:28.007  1902  2655 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 13:29:28.527  3024  3871 V KeepSync: Connecting to GoogleApiClient
,08-30 13:29:28.527   873  2074 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 13:29:28.580  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:28.582  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:28.623  1502  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 13:29:28.623  1502  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 13:29:28.623  1502  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:28.623  1502  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:28.660  1722  3874 V BaseAuthAsyncOperation: access token request failed
,08-30 13:29:28.661  3024  3871 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 13:29:28.667  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:29:28.667  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 13:29:28.668  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:29:28.668  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:28.688  3555  3873 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 13:29:28.688  3555  3873 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at blb.a(PG:3937)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at czp.a(PG:18188)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:29:28.688  3555  3873 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	... 12 more
08-30 13:29:28.688  3555  3873 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at fal.a(PG:38)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:29:28.688  3555  3873 E HttpOperation: 	... 14 more
,08-30 13:29:28.737  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-30 13:29:28.737  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 13:29:28.737  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:28.737  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:28.745  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 13:29:28.745  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 13:29:28.745  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:28.745  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:28.753  3555  3873 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 13:29:28.753  3555  3873 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at hec.a(PG:42)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at hee.a(PG:102)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at czr.a(PG:65)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at kka.a(PG:108)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at czp.a(PG:19176)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:29:28.753  3555  3873 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	... 15 more
08-30 13:29:28.753  3555  3873 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at fal.a(PG:38)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:29:28.753  3555  3873 E HttpOperation: 	... 17 more
08-30 13:29:28.753  3555  3873 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 13:29:28.753  3555  3873 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at hec.a(PG:42)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at hee.a(PG:102)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at czr.a(PG:65)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at kka.a(PG:108)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
,08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	... 15 more
08-30 13:29:28.753  3555  3873 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at fal.a(PG:38)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 13:29:28.753  3555  3873 E ExperimentLoader: 	... 17 more
,08-30 13:29:28.775  3024  3871 E KeepSync: IOException
08-30 13:29:28.775  3024  3871 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 13:29:28.775  3024  3871 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:29:28.775  3024  3871 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 13:29:28.775  3024  3871 E KeepSync: 	... 10 more
,08-30 13:29:28.775  3024  3871 W KeepSync: Sync result 2
,08-30 13:29:28.791   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126236, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:29:28.855   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126726, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:29:31.232  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:29:31.233  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:31.233  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 13:29:31.234  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.235  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.235  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:29:31.235  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.236  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.236  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.236  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.237  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.238  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.239  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.242  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:31.242  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:29:31.243  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.243  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:31.245  3799  3848 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 13:29:31.248  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:29:31.248  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:31.249  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 13:29:31.251  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:29:31.251  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.251  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.251  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:31.251  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.251  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.251  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:29:31.251  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.251  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.251  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.251  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.253  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:29:31.253  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:31.253  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:31.253  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.254  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 13:29:31.254  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.254  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:31.255  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:31.255  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:29:31.255  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.255  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:31.255  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:31.255  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.255  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:31.255  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.255  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.256  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.256  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.256  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:31.257  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:29:31.257  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:31.257  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.257  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:31.258  3799  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 13:29:31.258  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.258  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:31.258  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:31.258  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.258  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.258  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.259  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.259  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.259  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.259  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:29:31.259  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.259  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.259  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.259  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.260  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:31.260  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:31.260  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:31.261  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.261  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 13:29:31.261  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.261  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:31.262  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:31.262  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.262  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.262  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.262  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.262  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.262  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:31.262  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.263  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.263  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.263  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.263  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:31.264  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:31.264  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:31.264  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.264  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:31.265  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 13:29:31.265  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 13:29:31.265  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 13:29:31.266  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 13:29:31.266  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 13:29:31.266  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 13:29:31.266  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 13:29:31.266  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 13:29:31.266  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 13:29:31.266  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:29:31.266  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:31.266  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 13:29:31.267  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.267  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.267  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.267  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:31.267  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:31.267  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.267  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 13:29:31.267  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.267  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.268  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-30 13:29:31.268  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:31.269  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:29:31.269  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:29:31.269  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:31.269  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.270  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-30 13:29:31.271  3799  3848 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 13:29:31.271  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 13:29:31.274  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 13:29:31.274  3799  3848 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-30 13:29:31.274  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 13:29:31.275  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 13:29:31.276  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 13:29:31.277  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 13:29:31.277  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 13:29:31.278  3799  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 13:29:31.278  3799  3848 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 13:29:31.278  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 13:29:31.278  3799  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 13:29:31.278  3799  3848 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 13:29:31.278  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 13:29:31.278  3799  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 13:29:31.278  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 13:29:31.281  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 13:29:31.282  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 13:29:31.283  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 13:29:31.283  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 13:29:31.283  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 13:29:31.284  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 13:29:31.284  3799  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 13:29:31.284  3799  3848 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 13:29:31.285  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.285  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:31.285  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:31.285  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.285  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.286  3799  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-30 13:29:31.287  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.287  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 13:29:31.288  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.288  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.288  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:31.288  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.288  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.289  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.289  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.289  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.289  3799  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-30 13:29:31.291  3799  3876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 13:29:31.291  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:31.291  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:29:31.291  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.292  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.293  3799  3848 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 13:29:31.293  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.293  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:31.293  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:31.294  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.294  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.294  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.294  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:31.294  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.294  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.294  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.294  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.294  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.294  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.294  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.296  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:31.297  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:29:31.297  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.298  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.304  3799  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 13:29:31.305  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.305  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:31.305  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:31.305  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.305  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.305  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:31.306  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.306  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.306  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.306  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.306  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.306  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.306  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.306  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.307  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:29:31.308  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:31.308  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.308  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.309  3799  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 13:29:31.309  3799  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 13:29:31.309  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 13:29:31.310  3799  3848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 13:29:31.310  3799  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 13:29:31.310  3799  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-30 13:29:31.310  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 13:29:31.310  3799  3848 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 13:29:31.310  3799  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 13:29:31.310  3799  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 13:29:31.310  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 13:29:31.310  3799  3848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 13:29:31.311  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:31.311  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:31.311  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 13:29:31.311  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.311  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.311  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.311  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.311  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.311  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.311  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.312  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.312  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.312  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:31.312  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.313  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:31.313  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:31.313  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:31.313  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.314  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:31.314  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.314  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:31.314  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:31.314  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:31.314  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:31.314  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:31.314  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:31.314  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:34.464   873  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 13:29:34.529  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:34.688  1502  3879 I VacuumService: Vacuum at: now=1472556574688 tag=VacuumService
,08-30 13:29:34.867  1502  3880 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 13:29:34.870  1502  3880 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 13:29:34.929  1502  3880 W Uploader:  no longer exists, so no auth token.
08-30 13:29:34.930  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:34.940  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:34.941  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:34.980  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 13:29:34.980  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 13:29:34.980  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:34.980  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:34.999  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 13:29:34.999  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 13:29:34.999  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 13:29:36.315  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:36.316  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:36.316  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:29:36.316  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:36.316  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.317  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:36.317  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:29:36.318  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:36.318  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:36.319  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:29:36.319  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:36.320  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.320  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:36.320  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:36.321  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.321  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:36.321  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.321  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.322  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:36.322  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.326  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:36.326  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:36.326  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.327  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.331  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 13:29:36.333  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:29:36.334  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 13:29:36.335  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 13:29:36.335  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 13:29:36.336  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 13:29:36.336  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 13:29:36.336  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 13:29:36.336  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:36.336  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 13:29:36.336  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 13:29:36.337  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 13:29:36.337  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.337  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 13:29:36.337  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 13:29:36.337  3799  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 13:29:36.339  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:36.339  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.339  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 13:29:36.339  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 13:29:36.339  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 13:29:36.339  3799  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 13:29:36.342  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.343  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.344  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:29:36.344  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:29:36.344  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:29:36.344  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 13:29:36.344  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:29:36.345  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:36.345  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:36.345  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:29:36.345  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:36.345  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:36.345  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:36.345  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.345  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
,08-30 13:29:36.346  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.346  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:36.346  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:36.346  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.346  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.346  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:36.346  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.347  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:36.347  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:29:36.347  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.347  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
,08-30 13:29:36.349  3799  3848 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 13:29:36.349  3799  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 13:29:36.349  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 13:29:36.350  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 13:29:36.350  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 13:29:36.350  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:36.350  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:36.350  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:36.350  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:36.350  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.351  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.351  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:36.351  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.351  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.351  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:36.351  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.351  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.351  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.351  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.353  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:36.353  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:36.353  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.353  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.358  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:36.358  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:36.358  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:29:36.358  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:36.359  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:29:36.359  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.359  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:36.359  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.359  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.359  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:36.359  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.359  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.359  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.359  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.360  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:29:36.360  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:36.360  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.361  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.362  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 13:29:36.362  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:29:36.362  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 13:29:36.362  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:29:36.362  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.362  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.362  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d22ebe not in the list
08-30 13:29:36.362  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.363  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.363  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:36.363  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.363  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:36.363  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:36.363  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:29:36.364  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:29:36.364  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:29:36.364  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:29:36.364  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2affb1f not in the list
08-30 13:29:36.365  3799  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 13:29:36.365  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 13:29:36.366  3799  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 13:29:36.366  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 13:29:36.366  3799  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-30 13:29:36.366  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 13:29:36.369  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 13:29:36.369  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 13:29:36.370  3799  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 13:29:36.370  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 13:29:36.370  3799  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 13:29:36.370  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 13:29:36.370  3799  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 13:29:36.370  3799  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-30 13:29:36.371  3799  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 13:29:36.371  3799  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 13:29:36.372  3799  3848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 13:29:36.372  3799  3848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 13:29:36.372  3799  3848 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-30 13:29:36.372  3799  3848 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 13:29:36.373  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 13:29:36.373  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@845c36e added. We now have 3 listener(s)
08-30 13:29:36.373  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:29:36.375  3799  3848 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 13:29:36.375   873  2137 D WifiService: setWifiEnabled: true pid=3799, uid=10000
08-30 13:29:36.375   873  2137 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 13:29:36.426  2691  2800 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 13:29:36.427  2691  2816 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-30 13:29:36.428  3799  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,08-30 13:29:36.845  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:29:40.000   873  1864 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:29:41.059  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:41.061  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:41.098  1502  3880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 13:29:41.098  1502  3880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 13:29:41.098  1502  3880 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:41.098  1502  3880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:41.117  1502  3880 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 13:29:41.117  1502  3880 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 13:29:41.117  1502  3880 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 13:29:41.382  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:29:41.383  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c53ea0f added. We now have 4 listener(s)
,08-30 13:29:41.383  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:29:41.402  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:41.403  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c53ea0f removed from the list
08-30 13:29:41.403  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:29:41.404  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:41.404  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:41.406  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:29:41.406  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a56a9c added. We now have 4 listener(s)
08-30 13:29:41.407  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:29:41.410  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:29:41.410  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a56a9c removed from the list
,08-30 13:29:41.410  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:29:41.411  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:29:41.411  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:29:41.413  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:29:41.413  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8921ca5 added. We now have 4 listener(s)
,08-30 13:29:41.413  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:29:41.419   873  1395 D WifiService: setWifiEnabled: false pid=3799, uid=10000
,08-30 13:29:41.419   873  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 13:29:41.428  2691  2708 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 13:29:41.428  2691  2708 D BluetoothAdapterProperties: Setting state to 13
08-30 13:29:41.428  2691  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 13:29:41.429  2691  2708 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 13:29:41.432  2691  2708 I BluetoothAdapterState: Entering PendingCommandState
08-30 13:29:41.433  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:29:41.442  2691  2691 D BluetoothMapService: onReceive
08-30 13:29:41.442  2691  2691 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 13:29:41.442  2691  2691 D BluetoothMapService: STATE_TURNING_OFF
08-30 13:29:41.442  2691  2691 D BluetoothMapService: MAP Service closeService in
08-30 13:29:41.442  2691  2691 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 13:29:41.442  2691  2691 D ObexServerSockets0: shutdown(block = true)
08-30 13:29:41.443  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 13:29:41.443  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 13:29:41.443  2691  2816 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 13:29:41.444  2691  2829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 13:29:41.444  2691  2830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 13:29:41.447  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 13:29:41.451   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state,
,08-30 13:29:41.451   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 13:29:41.451   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 13:29:41.451   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 13:29:41.452  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:41.452  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 13:29:41.452  2691  2691 I BtOppRfcommListener: stopping Accept Thread
08-30 13:29:41.453  2691  3418 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 13:29:41.453  2691  3418 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 13:29:41.454  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.454  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:41.455  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:29:41.458   873  1314 E native  : do suspend true
,08-30 13:29:41.458  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.460  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.461   873   886 I ActivityManager: Start proc 3896:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 13:29:41.461  2691  2713 D BluetoothAdapterProperties: Scan Mode:20
08-30 13:29:41.462  2691  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 13:29:41.464  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:41.464  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 13:29:41.465  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:41.465  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:41.467   873  1866 D DhcpClient: Clearing IP address
,08-30 13:29:41.467   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 13:29:41.470  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:41.470  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:41.471  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.471  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:41.471  2691  2691 D HeadsetService: Received stop request...Stopping profile...
,08-30 13:29:41.473   373   871 D CommandListener: Setting iface cfg
,08-30 13:29:41.473  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:41.474   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 13:29:41.474   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 13:29:41.474   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 13:29:41.475  1370  2077 D BluetoothHeadset: Proxy object disconnected
08-30 13:29:41.475  1370  1370 D HeadsetProfile: Bluetooth service disconnected
08-30 13:29:41.475  1977  2122 D BluetoothHeadset: Proxy object disconnected
,08-30 13:29:41.476   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 13:29:41.476   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 13:29:41.476  2691  2691 D A2dpService: Received stop request...Stopping profile...
08-30 13:29:41.476  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.476  2691  2822 D A2dpStateMachine: Exit Disconnected: -1
,08-30 13:29:41.478   873   873 D BluetoothA2dp: Proxy object disconnected
08-30 13:29:41.479  2691  2691 D HidService: Received stop request...Stopping profile...
,08-30 13:29:41.479  2691  2691 D HidService: Stopping Bluetooth HidService
08-30 13:29:41.479  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:41.479  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-30 13:29:41.480   396   396 E Parcel  : Reading a NULL string not supported here.
,08-30 13:29:41.481  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:41.481  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:41.482   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-30 13:29:41.483   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 13:29:41.483   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 13:29:41.483   873  1314 E native  : do suspend true
,08-30 13:29:41.484  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-30 13:29:41.484  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-30 13:29:41.484  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:41.484  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:41.485  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:41.486  2691  2691 D HealthService: Received stop request...Stopping profile...
08-30 13:29:41.486  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.486  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:41.487  2691  2691 D PanService: Received stop request...Stopping profile...
08-30 13:29:41.489  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 13:29:41.489  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 13:29:41.489  2691  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:29:41.490  2691  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:29:41.490  2691  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:29:41.489  2691  2713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 13:29:41.491  2691  2713 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-30 13:29:41.489   873  1868 D DhcpClient: Receive thread stopped
,08-30 13:29:41.491  2691  2691 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 13:29:41.493  2691  2691 D BluetoothMapService: stop()
08-30 13:29:41.493  2691  2691 D BluetoothMapAppObserver: deinitObservers()
08-30 13:29:41.493  2691  2691 D BluetoothMapAppObserver: removeReceiver()
08-30 13:29:41.495  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-30 13:29:41.495  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-30 13:29:41.495  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:41.495  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:41.496  2691  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:29:41.496  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-30 13:29:41.496  2691  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 13:29:41.496  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-30 13:29:41.496  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:41.496  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:29:41.496  2691  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 13:29:41.497  2691  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 13:29:41.497  2691  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 13:29:41.497  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 13:29:41.497  2691  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 13:29:41.497  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 13:29:41.497  2691  2713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 13:29:41.497  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-30 13:29:41.497  2691  2691 V BluetoothAdapterState: isTurningOn()=false
,08-30 13:29:41.497  2691  2713 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 13:29:41.497  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 13:29:41.497  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:41.497  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 13:29:41.497  2691  2713 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-30 13:29:41.498  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 13:29:41.498  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-30 13:29:41.498  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-30 13:29:41.498  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:41.498  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:41.498  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 13:29:41.499  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 13:29:41.499  2691  2691 D BluetoothMapService: MAP Service closeService in
08-30 13:29:41.499  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-30 13:29:41.499  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-30 13:29:41.500  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:41.500  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:41.500  2691  2691 D BluetoothMapService: cleanup()
08-30 13:29:41.500  2691  2691 D BluetoothMapService: MAP Service closeService in
08-30 13:29:41.500  2691  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 13:29:41.500  2691  2708 D BluetoothAdapterProperties: Setting state to 15
,08-30 13:29:41.500  2691  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 13:29:41.501  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-30 13:29:41.501  2691  2708 I BluetoothAdapterState: Entering BleOnState
08-30 13:29:41.501  1370  1370 D HidProfile: Bluetooth service disconnected
08-30 13:29:41.501  1370  2077 D BluetoothMap: onBluetoothStateChange: up=false
08-30 13:29:41.501   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:29:41.502  1370  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 13:29:41.502   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 13:29:41.502  1977  2124 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:29:41.503  1370  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 13:29:41.503  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 13:29:41.503  1370  1370 D PanProfile: Bluetooth service disconnected
08-30 13:29:41.504   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:29:41.504  1370  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 13:29:41.504   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:29:41.504  1370  2077 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 13:29:41.505  1370  1382 D BluetoothPan: onBluetoothStateChange on: false
08-30 13:29:41.506  2691  2708 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 13:29:41.506  2691  2708 D BluetoothAdapterProperties: Setting state to 16
,08-30 13:29:41.506  2691  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 13:29:41.509  2691  2708 D BluetoothAdapterProperties: onBleDisable
08-30 13:29:41.509  2691  2708 I BluetoothAdapterState: Entering PendingCommandState
08-30 13:29:41.510  2691  2709 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 13:29:41.511  2691  2800 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 13:29:41.511  2691  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:29:41.511  2691  2713 D BluetoothAdapterProperties: Scan Mode:20
,08-30 13:29:41.513  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.513  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:41.514  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.514  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:41.515  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.515  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:29:41.517  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:41.518  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.519  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:41.520  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:41.509  1502  2453 V NativeCrypto: Read error: ssl=0x9b04b000: I/O error during system call, Connection timed out
,08-30 13:29:41.528   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 13:29:41.529  1502  2453 V NativeCrypto: SSL shutdown failed: ssl=0x9b04b000: I/O error during system call, Broken pipe
,08-30 13:29:41.547  1502  3880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 13:29:41.547  1502  3880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 13:29:41.548  1502  3880 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:41.548  1502  3880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:41.551  3896  3896 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 13:29:41.553   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:29:41.554   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-30 13:29:41.554   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:29:41.556   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 13:29:41.557   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 13:29:41.561  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.562  3403  3403 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8346624 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 13:29:41.563  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.566  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:41.573  1502  3880 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 13:29:41.573  1502  3880 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 13:29:41.573  1502  3880 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 13:29:41.593  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 13:29:41.600  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 13:29:41.605   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4183bdc:true
,08-30 13:29:41.618   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 13:29:41.625   873  1395 I ActivityManager: Start proc 3916:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 13:29:41.627   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 13:29:41.632  1502  3880 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.208.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-30 13:29:41.639   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 13:29:41.642  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.642  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:29:41.642   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 13:29:41.643  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:41.643  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:41.645  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.645  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:41.645  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.646  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:41.646  1902  2313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 13:29:41.649  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:41.649  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:41.649  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:41.649  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:41.665  3916  3916 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 13:29:41.669  3896  3896 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 13:29:41.678  3896  3896 D BluetoothMap: Create BluetoothMap proxy object
,08-30 13:29:41.689  3896  3896 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 13:29:41.709  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-30 13:29:41.712  2691  2713 I bt_hci  : shut_down
,08-30 13:29:41.713  2691  2717 D bt_hwcfg: hw_epilog_process
,08-30 13:29:41.717   873  1694 I ActivityManager: Killing 3403:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 13:29:41.833  2691  2717 I bt_vendor: low_power_mode_cb
,08-30 13:29:41.859  2691  2717 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 13:29:41.859  2691  2717 I bt_vendor: epilog_cb
,08-30 13:29:41.859  2691  2717 I bt_hci  : epilog_finished_callback
,08-30 13:29:41.866  2691  2713 I bt_hci_h4: hal_close
,08-30 13:29:41.867  2691  2713 I bt_userial_vendor: device fd = 51 close
,08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.927  3916  3916 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.927  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.928  3916  3916 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 13:29:41.928  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 13:29:41.962  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 13:29:41.972  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 13:29:41.986  3896  3896 D DockEventReceiver: finishStartingService: stopping service
08-30 13:29:41.993  2691  2709 D bt_stack_manager: event_shut_down_stack finished.
08-30 13:29:41.994  2691  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 13:29:41.997  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 13:29:42.001  2691  2691 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 13:29:42.001  2691  2691 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 13:29:42.001  2691  2691 D BtGatt.GattService: stop()
08-30 13:29:42.002  2691  2691 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 13:29:42.003  2691  2708 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 13:29:42.005  1722  1722 D SystemUpdateService: onCreate
08-30 13:29:42.007  2691  2691 V BluetoothAdapterState: isTurningOff()=false
08-30 13:29:42.007  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-30 13:29:42.008  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:42.008  2691  2691 V BluetoothAdapterState: isBleTurningOff()=true
08-30 13:29:42.008  2691  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 13:29:42.009  2691  2708 D BluetoothAdapterProperties: Setting state to 10
08-30 13:29:42.009  2691  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 13:29:42.010  2691  2708 I BluetoothAdapterState: Entering OffState
,08-30 13:29:42.011   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 13:29:42.011  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 13:29:42.040  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 13:29:42.040  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 13:29:42.040  2691  2691 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 13:29:42.041  2691  2709 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 13:29:42.044  2691  2709 D bt_stack_manager: event_clean_up_stack finished.
,08-30 13:29:42.037  1722  3948 I SystemUpdateService: active receiver: enabled
,08-30 13:29:42.046  2691  2691 I art     : System.exit called, status: 0
,08-30 13:29:42.046  2691  2691 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 13:29:42.059  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 13:29:42.061  1722  2408 I iu.UploadsManager: num queued entries: 0
,08-30 13:29:42.061  1722  2408 I iu.UploadsManager: num updated entries: 0
,08-30 13:29:42.066  1722  2408 I iu.SyncManager: NEXT; no task
,08-30 13:29:42.068  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 13:29:42.071  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 13:29:42.079  1722  3948 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 13:29:42.089  1722  3948 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 13:29:42.089  1722  3948 I SystemUpdateService: now status is 0 (complete)
08-30 13:29:42.090  1722  3948 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 13:29:42.090  1722  3948 I SystemUpdateService: file has been verified
08-30 13:29:42.090  1722  3948 I SystemUpdateService: OTA package size = 12249756
,08-30 13:29:42.095  1722  3948 I SystemUpdateService: showing system update notification
,08-30 13:29:42.102   873  1399 I ActivityManager: Start proc 3951:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 13:29:42.123   873  1696 I ActivityManager: Process com.android.bluetooth (pid 2691) has died
,08-30 13:29:42.154  3951  3951 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 13:29:42.160  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:29:42.172  3951  3951 D SprintDMHelper: simOperator: 
,08-30 13:29:42.172  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 13:29:42.192   873  2136 I ActivityManager: Start proc 3965:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 13:29:42.193   873  2136 I ActivityManager: Killing 3570:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 13:29:42.214  3916  3942 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 13:29:42.224   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c31a4b:true
,08-30 13:29:42.240  1722  1722 D SystemUpdateService: onDestroy
,08-30 13:29:42.327  2246  3980 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 13:29:42.330   873  2074 I ActivityManager: Start proc 3981:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 13:29:42.338   873  2074 I ActivityManager: Killing 3452:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 13:29:42.396  3981  3981 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 13:29:42.446  3981  3981 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 13:29:42.446  3981  3981 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 13:29:42.446  3981  3981 I GAv4    :   adb logcat -s GAv4
,08-30 13:29:42.464  3981  3981 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 13:29:42.470  3981  3981 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 13:29:42.496  3981  3998 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 13:29:42.609  3981  3981 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 13:29:42.654  3981  3981 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 13:29:42.667  3981  3981 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 288-290)
08-30 13:29:42.667  3981  3981 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 13:29:42.676  3981  3981 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a8fa054}
,08-30 13:29:42.677  3981  3981 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 13:29:42.678  3981  3981 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 13:29:42.686  3981  3981 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 13:29:42.688  3981  3981 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 13:29:42.705  3981  3981 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 13:29:42.717  3981  3981 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 13:29:42.718  3981  3981 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 13:29:42.718  3981  3981 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 13:29:42.718  3981  3981 I Adreno  : Build Date                       : 10/20/15
08-30 13:29:42.718  3981  3981 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 13:29:42.718  3981  3981 I Adreno  : Local Branch                     : M14
08-30 13:29:42.718  3981  3981 I Adreno  : Remote Branch                    : 
08-30 13:29:42.718  3981  3981 I Adreno  : Remote Branch                    : 
08-30 13:29:42.718  3981  3981 I Adreno  : Reconstruct Branch               : 
,08-30 13:29:42.780  3981  3981 I NSApplication: Starting up...
,08-30 13:29:42.787  3981  4027 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 13:29:42.821   873   884 I ActivityManager: Start proc 4032:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 13:29:42.823   873   884 I ActivityManager: Killing 3499:android.process.acore/u0a5 (adj 15): empty #17
,08-30 13:29:42.898  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 13:29:43.093   873  1395 I ActivityManager: Killing 3685:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 13:29:43.180   873  2137 I ActivityManager: Start proc 4046:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 13:29:43.220  4046  4046 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 13:29:43.269  4046  4046 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 13:29:43.289   873  1695 I ActivityManager: Killing 3702:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 13:29:46.459   873  2137 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,08-30 13:29:46.459   873  2137 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 13:29:46.473   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-30 13:29:46.479  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:46.479  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:46.480  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:46.480  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:46.483  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:46.483  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:46.483  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:46.484  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:46.486  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:46.486  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:46.486  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
,08-30 13:29:46.486  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:46.516   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-30 13:29:46.517   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 13:29:46.519   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 13:29:46.520   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 13:29:46.521   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 13:29:46.521   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 13:29:46.521   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 13:29:46.546   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 13:29:46.548   373   871 D CommandListener: Setting iface cfg
,08-30 13:29:46.548   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 13:29:46.549   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 13:29:46.549   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 13:29:46.561   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 13:29:46.561   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 13:29:46.566   873  1314 E native  : do suspend true
,08-30 13:29:46.613   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:29:47.414   873  2135 I ActivityManager: Killing 2083:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 13:29:47.982   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 13:29:48.011   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.19 rxSuccessRate=6.12 delta 1000 -> 1000
,08-30 13:29:48.012   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 13:29:48.012   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:29:48.030   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 13:29:48.079   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 13:29:48.081  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 13:29:48.521  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 13:29:48.561  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 13:29:48.561  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 13:29:48.570   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:29:48.578   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 13:29:48.578   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:29:48.579   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 13:29:48.602   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:29:48.616   373   871 D CommandListener: Setting iface cfg
08-30 13:29:48.617   873  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 13:29:48.625   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 13:29:48.685   873  4083 D DhcpClient: Receive thread started
,08-30 13:29:48.783   873  1314 E native  : do suspend false
,08-30 13:29:48.808   873  1866 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 13:29:48.829   873  4083 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172646, domain null
,08-30 13:29:48.830   873  1866 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172646 seconds
,08-30 13:29:48.833   873  1866 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 13:29:48.854   873  4083 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 13:29:48.855   873  1866 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 13:29:48.861   373   871 D CommandListener: Setting iface cfg
,08-30 13:29:48.872   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 13:29:48.872   873  1866 D DhcpClient: Scheduling renewal in 86399s
,08-30 13:29:48.876   873  1314 E native  : do suspend true
,08-30 13:29:48.912   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 13:29:48.916   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 13:29:48.918   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 13:29:48.921   873  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 13:29:48.936   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 13:29:48.977   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 13:29:48.977   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 13:29:48.979   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 13:29:48.982   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 13:29:48.985   873  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 13:29:49.005   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 13:29:49.018   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 13:29:49.019   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-30 13:29:49.020   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 13:29:49.021   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-30 13:29:49.021   873  1316 D ConnectivityService:    accepting network in place of null
,08-30 13:29:49.021   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 13:29:49.023   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 13:29:49.066   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:29:49.118   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:29:49.127   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 13:29:49.127   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:29:49.139   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 13:29:49.134   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 13:29:49.147  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:49.147  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 13:29:49.148  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:49.148  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:49.153  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:49.153  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:49.153  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:49.153  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:49.156  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:29:49.156  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:29:49.156  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:49.156  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:29:49.167  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 13:29:49.176  1722  1722 D SystemUpdateService: onCreate
,08-30 13:29:49.180  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 13:29:49.204  1722  4093 I SystemUpdateService: active receiver: enabled
,08-30 13:29:49.210  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 13:29:49.213  1722  2408 I iu.UploadsManager: num queued entries: 0
,08-30 13:29:49.213  1722  2408 I iu.UploadsManager: num updated entries: 0
,08-30 13:29:49.217  1722  4093 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 13:29:49.222  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 13:29:49.223  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 13:29:49.225  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:29:49.233  1722  4097 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 13:29:49.234  1722  4097 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 13:29:49.235  1722  4097 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:29:49.237  1722  4093 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 13:29:49.237  1722  4093 I SystemUpdateService: now status is 0 (complete)
08-30 13:29:49.237  1722  4093 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 13:29:49.237  1722  4093 I SystemUpdateService: file has been verified
08-30 13:29:49.239  1722  4093 I SystemUpdateService: OTA package size = 12249756
08-30 13:29:49.240  3951  3951 D SprintDMHelper: simOperator: 
,08-30 13:29:49.240  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 13:29:49.259  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:49.240  1722  2408 I iu.SyncManager: NEXT; no task
,08-30 13:29:49.269  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:49.290  1722  4093 I SystemUpdateService: showing system update notification
,08-30 13:29:49.369  1722  1722 D SystemUpdateService: onDestroy
,08-30 13:29:49.380  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 13:29:49.380  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 13:29:49.380  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:49.381  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:49.396  1722  4097 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-30 13:29:49.705   873  4082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177328, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 13:29:50.127   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 13:29:50.391   873  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 13:29:50.485  2246  4100 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 13:29:50.518   873  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 11:29:50 GMT], X-Android-Received-Millis=[1472556590517], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472556590481]}
,08-30 13:29:50.519   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 13:29:50.520   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 13:29:50.520   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 13:29:50.525   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 13:29:51.466   873  1395 D WifiService: setWifiEnabled: false pid=3799, uid=10000
08-30 13:29:51.466   873  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 13:29:51.501  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 13:29:51.508   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 13:29:51.508   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 13:29:51.509   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 13:29:51.510   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:29:51.550   873  1314 E native  : do suspend true
,08-30 13:29:51.561   873  1866 D DhcpClient: Clearing IP address
,08-30 13:29:51.562   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 13:29:51.572  1502  4105 V NativeCrypto: Read error: ssl=0x9b1ae200: I/O error during system call, Connection timed out
,08-30 13:29:51.572   373   871 D CommandListener: Setting iface cfg
,08-30 13:29:51.574   873  4083 D DhcpClient: Receive thread stopped
,08-30 13:29:51.575  1502  4105 V NativeCrypto: SSL shutdown failed: ssl=0x9b1ae200: I/O error during system call, Broken pipe
,08-30 13:29:51.582   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 13:29:51.582   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 13:29:51.590   396   396 E Parcel  : Reading a NULL string not supported here.
08-30 13:29:51.590   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 13:29:51.591   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 13:29:51.592   873  1314 E native  : do suspend true
08-30 13:29:51.603   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 13:29:51.633   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:29:51.658   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:29:51.658   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 13:29:51.660   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 13:29:51.661   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:29:51.665   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 13:29:51.672   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 13:29:51.681  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:51.681  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:29:51.681  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.681  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:51.683  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:51.683  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:51.683  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.683  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:51.684  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:51.684  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:51.684  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.685  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:51.690  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 13:29:51.695   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:29:51.698  1902  2313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 13:29:51.698  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:51.698  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:51.699  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.699  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:51.699  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:51.700  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.700  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:51.700  1722  1722 D SystemUpdateService: onCreate
,08-30 13:29:51.700   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 13:29:51.700  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:51.700  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:51.701  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:29:51.701  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:29:51.706  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 13:29:51.715  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 13:29:51.721  1722  2408 I iu.UploadsManager: num queued entries: 0
,08-30 13:29:51.721  1722  2408 I iu.UploadsManager: num updated entries: 0
,08-30 13:29:51.723  1722  4114 I SystemUpdateService: active receiver: enabled
,08-30 13:29:51.724  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 13:29:51.725  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 13:29:51.727  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:29:51.731  3951  3951 D SprintDMHelper: simOperator: 
,08-30 13:29:51.731  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 13:29:51.740  1722  4114 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 13:29:51.753   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 13:29:51.754   873  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 13:29:51.758  2246  4119 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 13:29:51.722  1722  2408 I iu.SyncManager: NEXT; no task
,08-30 13:29:51.763  1722  4114 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 13:29:51.763  1722  4114 I SystemUpdateService: now status is 0 (complete)
08-30 13:29:51.763  1722  4114 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 13:29:51.763  1722  4114 I SystemUpdateService: file has been verified
08-30 13:29:51.763  1722  4114 I SystemUpdateService: OTA package size = 12249756
,08-30 13:29:51.775  1722  4114 I SystemUpdateService: showing system update notification
,08-30 13:29:51.785  1722  1722 D SystemUpdateService: onDestroy
,08-30 13:29:55.301  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:55.313  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:55.317  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:29:55.366  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 13:29:55.366  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 13:29:55.367  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:29:55.368  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:29:55.420  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 13:29:55.425  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 13:29:55.426  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 13:29:56.526   873   890 I ActivityManager: Start proc 4124:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 13:29:56.658  4124  4124 D AdapterServiceConfig: Adding HeadsetService
,08-30 13:29:56.659  4124  4124 D AdapterServiceConfig: Adding A2dpService
08-30 13:29:56.659  4124  4124 D AdapterServiceConfig: Adding HidService
08-30 13:29:56.659  4124  4124 D AdapterServiceConfig: Adding HealthService
08-30 13:29:56.660  4124  4124 D AdapterServiceConfig: Adding PanService
08-30 13:29:56.660  4124  4124 D AdapterServiceConfig: Adding GattService
08-30 13:29:56.660  4124  4124 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 13:29:56.676  4124  4124 D BluetoothAdapterState: make() - Creating AdapterState
08-30 13:29:56.676   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b08de:true
,08-30 13:29:56.681  4124  4124 I bt_bluedroid: init
,08-30 13:29:56.682  4124  4136 I BluetoothAdapterState: Entering OffState
,08-30 13:29:56.687  4124  4137 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 13:29:56.688  4124  4137 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 13:29:56.688  4124  4137 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 13:29:56.689  4124  4137 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 13:29:56.690  4124  4124 I bt_bluedroid: get_profile_interface socket
,08-30 13:29:56.693  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 13:29:56.695  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 13:29:56.695  4124  4124 I bt_bluedroid: get_profile_interface sdp
,08-30 13:29:56.714  4124  4135 I bt_bluedroid: config_hci_snoop_log
,08-30 13:29:56.718   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 13:29:56.728  4124  4136 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 13:29:56.728  4124  4136 D BluetoothAdapterProperties: Setting state to 14
,08-30 13:29:56.729  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 13:29:56.733  4124  4136 D BluetoothBondStateMachine: make
,08-30 13:29:56.737  4124  4141 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 13:29:56.740  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-30 13:29:56.742  4124  4124 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 13:29:56.745  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:56.746  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 13:29:56.746  4124  4124 D BtGatt.GattService: Received start request. Starting profile...
,08-30 13:29:56.746  4124  4124 D BtGatt.GattService: start()
,08-30 13:29:56.746  4124  4124 I bt_bluedroid: get_profile_interface gatt
,08-30 13:29:56.747  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:56.747  4124  4124 D BtGatt.AdvertiseManager: advertise manager created
,08-30 13:29:56.756  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:29:56.756  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-30 13:29:56.757  4124  4124 V BluetoothAdapterState: isBleTurningOn()=true
08-30 13:29:56.757  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:29:56.757  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 13:29:56.758  4124  4136 I bt_bluedroid: enable
08-30 13:29:56.758  4124  4137 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 13:29:56.759  4124  4137 I bt_hci  : start_up
,08-30 13:29:56.777  4124  4137 I bt_vendor: alloc value 0xb3a15189
,08-30 13:29:56.777  4124  4137 I bt_vendor: init
08-30 13:29:56.777  4124  4137 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 13:29:56.777  4124  4137 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 13:29:56.884  4124  4137 D bt_hci  : start_up starting async portion,
,08-30 13:29:56.885  4124  4144 I bt_hci  : event_finish_startup
08-30 13:29:56.885  4124  4144 I bt_hci_h4: hal_open
08-30 13:29:56.885  4124  4144 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 13:29:56.897  4124  4144 I bt_userial_vendor: device fd = 51 open
,08-30 13:29:56.926  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 13:29:56.958  4124  4144 D bt_hwcfg: Chipset BCM4354A2
08-30 13:29:56.959  4124  4144 D bt_hwcfg: Target name = [BCM4354A2],
08-30 13:29:56.959  4124  4144 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 13:29:57.024   873  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-30 13:29:57.227  1502  2067 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 13:29:57.630  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 13:29:57.631  4124  4144 D bt_hwcfg: Settlement delay -- 100 ms
08-30 13:29:57.631  4124  4144 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 13:29:57.747  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 13:29:57.748  4124  4144 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 13:29:57.775  4124  4144 I bt_hwcfg: vendor lib fwcfg completed
08-30 13:29:57.775  4124  4144 I bt_vendor: firmware callback
08-30 13:29:57.775  4124  4144 I bt_hci  : firmware_config_callback
,08-30 13:29:57.787  4124  4146 I bt_btu  : btu_task pending for preload complete event
08-30 13:29:57.787  4124  4146 I bt_btu_task: Bluetooth chip preload is complete
,08-30 13:29:57.788  4124  4146 I bt_btu  : btu_task received preload complete event
,08-30 13:29:57.799  4124  4146 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 13:29:57.799  4124  4146 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 13:29:57.799  4124  4146 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 13:29:57.800  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 13:29:57.800  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 13:29:57.800  4124  4146 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 13:29:57.801  4124  4146 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 13:29:57.801  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 13:29:57.801  4124  4146 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 13:29:57.802  4124  4146 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 13:29:57.802  4124  4146 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 13:29:57.803  4124  4146 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 13:29:57.803  4124  4146 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 13:29:57.804  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 13:29:57.804  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 13:29:57.938  4124  4146 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3992d9d
,08-30 13:29:57.938  4124  4146 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3992d9d 
,08-30 13:29:57.964  4124  4140 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 13:29:57.966  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-30 13:29:57.966  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 13:29:57.968  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 13:29:57.969  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
08-30 13:29:57.970  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 13:29:57.970  4124  4140 D bt_hci  : do_postload posting postload work item
08-30 13:29:57.970  4124  4144 I bt_hci  : event_postload
08-30 13:29:57.971  4124  4144 I bt_vendor: sco_config_cb
08-30 13:29:57.971  4124  4144 I bt_hci  : sco_config_callback postload finished.
,08-30 13:29:57.971  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:57.974  4124  4140 D bt_bte_conf: Device ID record 1 : primary
,08-30 13:29:57.974  4124  4140 D bt_bte_conf:   vendorId            = 000f
08-30 13:29:57.974  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:57.974  4124  4140 D bt_bte_conf:   vendorIdSource      = 0001
08-30 13:29:57.975  4124  4140 D bt_bte_conf:   product             = 1200
08-30 13:29:57.975  4124  4140 D bt_bte_conf:   version             = 1436
08-30 13:29:57.975  4124  4140 D bt_bte_conf:   clientExecutableURL = 
,08-30 13:29:57.976  4124  4140 D bt_bte_conf:   serviceDescription  = 
08-30 13:29:57.976  4124  4140 D bt_bte_conf:   documentationURL    = 
08-30 13:29:57.977  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:57.978  4124  4140 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 13:29:57.978  4124  4137 D bt_stack_manager: event_start_up_stack finished
08-30 13:29:57.979  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 13:29:57.981  4124  4136 D BluetoothAdapterProperties: Setting state to 15
08-30 13:29:57.981  4124  4144 I bt_vendor: low_power_mode_cb
08-30 13:29:57.981  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 13:29:57.982  4124  4136 I BluetoothAdapterState: Entering BleOnState
,08-30 13:29:57.987  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 13:29:57.987  4124  4136 D BluetoothAdapterProperties: Setting state to 11
,08-30 13:29:57.987  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 13:29:57.993  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:57.997  4124  4124 D HeadsetService: Received start request. Starting profile...
,08-30 13:29:58.004  4124  4124 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 13:29:58.005  4124  4124 D HeadsetStateMachine: make
08-30 13:29:58.005  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:58.007  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:29:58.010  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:58.016  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-30 13:29:58.020  4124  4124 D HeadsetStateMachine: max_hf_connections = 1
,08-30 13:29:58.020  4124  4124 I bt_bluedroid: get_profile_interface handsfree
08-30 13:29:58.020  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 13:29:58.020  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 13:29:58.027  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:58.027  4124  4124 D A2dpService: Received start request. Starting profile...
08-30 13:29:58.028  4124  4124 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 13:29:58.029  4124  4124 I bt_bluedroid: get_profile_interface avrcp
,08-30 13:29:58.035  4124  4124 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 13:29:58.035  4124  4124 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 13:29:58.035  4124  4124 D A2dpStateMachine: make
,08-30 13:29:58.036  4124  4124 I bt_bluedroid: get_profile_interface a2dp
08-30 13:29:58.037  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 13:29:58.039  4124  4156 D A2dpStateMachine: Enter Disconnected: -2
,08-30 13:29:58.040  4124  4124 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 13:29:58.042  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:58.043  4124  4124 D HidService: Received start request. Starting profile...
08-30 13:29:58.044  4124  4124 I bt_bluedroid: get_profile_interface hidhost
,08-30 13:29:58.044  4124  4140 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39743e5
08-30 13:29:58.044  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 13:29:58.044  4124  4124 D HidService: setHidService(): set to: null
08-30 13:29:58.044  3896  3896 D BluetoothInputDevice: Proxy object connected
08-30 13:29:58.044  4124  4124 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 13:29:58.045  3896  3896 D HidProfile: Bluetooth service connected
08-30 13:29:58.045  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:58.046  4124  4124 D HealthService: Received start request. Starting profile...
,08-30 13:29:58.048  4124  4124 I bt_bluedroid: get_profile_interface health
,08-30 13:29:58.050  4124  4124 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 13:29:58.051  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:29:58.052  4124  4124 D PanService: Received start request. Starting profile...
08-30 13:29:58.052  4124  4124 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 13:29:58.052  4124  4124 I bt_bluedroid: get_profile_interface pan
08-30 13:29:58.053  4124  4140 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 13:29:58.057  3896  3896 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 13:29:58.057  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 13:29:58.058  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:29:58.059  3896  3896 D PanProfile: Bluetooth service connected
08-30 13:29:58.059  4124  4124 D BluetoothMapService: Received start request. Starting profile...
,08-30 13:29:58.059  4124  4124 D BluetoothMapService: start()
08-30 13:29:58.059  3896  3896 D BluetoothMap: Proxy object connected
08-30 13:29:58.060  3896  3896 D MapProfile: Bluetooth service connected
08-30 13:29:58.060  3896  3896 D BluetoothMap: getConnectedDevices()
08-30 13:29:58.061  3896  3896 D BluetoothMap: Bluetooth is Not enabled
,08-30 13:29:58.062  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 13:29:58.063  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 13:29:58.063  4124  4124 D BluetoothMapAppObserver: createReceiver()
08-30 13:29:58.064  4124  4124 D BluetoothMapAppObserver: initObservers()
,08-30 13:29:58.064  4124  4124 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 13:29:58.073  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:29:58.073  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-30 13:29:58.073  4124  4152 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 13:29:58.073  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:58.073  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:29:58.075  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:58.076  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:29:58.077  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-30 13:29:58.077  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,08-30 13:29:58.077  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:29:58.077  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:29:58.077  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 13:29:58.078  4124  4136 D BluetoothAdapterProperties: ScanMode =  20
08-30 13:29:58.078  4124  4136 D BluetoothAdapterProperties: State =  11
,08-30 13:29:58.078  4124  4136 D BluetoothAdapterProperties: Setting state to 12
08-30 13:29:58.078  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 13:29:58.079  1370  2077 D BluetoothMap: onBluetoothStateChange: up=true
08-30 13:29:58.080  4124  4140 D BluetoothAdapterProperties: Scan Mode:21
,08-30 13:29:58.080  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 13:29:58.080  4124  4136 I BluetoothAdapterState: Entering OnState
08-30 13:29:58.081  1370  1370 D BluetoothMap: Proxy object connected
,08-30 13:29:58.082  1370  1370 D MapProfile: Bluetooth service connected
08-30 13:29:58.082  1370  1370 D BluetoothMap: getConnectedDevices()
,08-30 13:29:58.082   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:29:58.083  3896  3907 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 13:29:58.083  3896  3909 D BluetoothPan: onBluetoothStateChange on: true
08-30 13:29:58.084  1370  1388 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:58.085  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:29:58.086   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 13:29:58.087  1977  2124 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:29:58.087   873   873 D BluetoothA2dp: Proxy object connected
08-30 13:29:58.088  3896  3907 D BluetoothMap: onBluetoothStateChange: up=true
08-30 13:29:58.088  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:58.088  1370  2077 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 13:29:58.089  1370  1370 D BluetoothA2dp: Proxy object connected
08-30 13:29:58.091   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:29:58.091  1370  1382 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:29:58.092   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 13:29:58.092  1370  1370 D BluetoothInputDevice: Proxy object connected
08-30 13:29:58.092  1370  1370 D HidProfile: Bluetooth service connected
08-30 13:29:58.092  1370  1388 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 13:29:58.092  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 13:29:58.093  4124  4124 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:58.094  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:29:58.095  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:29:58.097  1370  2077 D BluetoothPan: onBluetoothStateChange on: true
08-30 13:29:58.098  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:58.098  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 13:29:58.099  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 13:29:58.099  1370  1370 D PanProfile: Bluetooth service connected
08-30 13:29:58.100  3896  3909 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 13:29:58.100  4124  4124 D ObexServerSockets: Succeed to create listening sockets 
08-30 13:29:58.101  4124  4124 D ObexServerSockets0: startAccept()
,08-30 13:29:58.101  4124  4124 D ObexServerSockets0: prepareForNewConnect()
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:29:58.102  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:29:58.104   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 13:29:58.104  4124  4124 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 13:29:58.104  4124  4124 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 13:29:58.105  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:29:58.105  4124  4124 D BluetoothMapService: onReceive
08-30 13:29:58.105  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 13:29:58.106  4124  4124 D BluetoothMapService: STATE_ON
08-30 13:29:58.106  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:58.107  4124  4164 D ObexServerSockets0: Accepting socket connection...
08-30 13:29:58.108  4124  4163 D ObexServerSockets0: Accepting socket connection...
08-30 13:29:58.108  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:58.109  3896  3896 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 13:29:58.109  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:29:58.113  3896  3896 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 13:29:58.118  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 13:29:58.120  3896  3896 D BluetoothA2dp: Proxy object connected
,08-30 13:29:58.123  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 13:29:58.131  1370  1370 D BluetoothPbap: Proxy object connected
,08-30 13:29:58.131  1370  1370 D PbapServerProfile: Bluetooth service connected
08-30 13:29:58.131  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 13:29:58.131  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,08-30 13:29:58.134  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-30 13:29:58.135  3896  3896 D BluetoothPbap: Proxy object connected
,08-30 13:29:58.136  3896  3896 D PbapServerProfile: Bluetooth service connected
,08-30 13:29:58.140  4124  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:29:58.155  4124  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:29:58.157  4124  4172 I BtOppRfcommListener: Accept thread started.
,08-30 13:29:58.184   873   873 D BluetoothHeadset: Proxy object connected
08-30 13:29:58.184   873   873 D BluetoothHeadset: Proxy object connected
08-30 13:29:58.185   873   873 D BluetoothHeadset: Proxy object connected
,08-30 13:29:58.185  1370  2077 D BluetoothHeadset: Proxy object connected
08-30 13:29:58.185  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-30 13:29:58.186  1977  1989 D BluetoothHeadset: Proxy object connected
,08-30 13:29:58.188  1977  2122 D BluetoothHeadset: Proxy object connected
,08-30 13:29:58.191   873   890 D BluetoothHeadset: Proxy object connected
,08-30 13:29:58.192  1370  1388 D BluetoothHeadset: Proxy object connected
08-30 13:29:58.192   873   890 D BluetoothHeadset: Proxy object connected
08-30 13:29:58.192  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-30 13:29:58.216  3896  3907 D BluetoothHeadset: Proxy object connected
08-30 13:29:58.217  3896  3896 D HeadsetProfile: Bluetooth service connected
,08-30 13:30:01.483  4124  4136 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 13:30:01.484  4124  4136 D BluetoothAdapterProperties: Setting state to 13
08-30 13:30:01.484  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 13:30:01.486  4124  4136 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 13:30:01.491  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-30 13:30:01.502  4124  4124 D BluetoothMapService: onReceive
08-30 13:30:01.502  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 13:30:01.502  4124  4124 D BluetoothMapService: STATE_TURNING_OFF
08-30 13:30:01.503  4124  4124 D BluetoothMapService: MAP Service closeService in
08-30 13:30:01.503  4124  4124 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 13:30:01.503  4124  4124 D ObexServerSockets0: shutdown(block = true)
08-30 13:30:01.504  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 13:30:01.504  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 13:30:01.505  4124  4148 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 13:30:01.505  4124  4164 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 13:30:01.505  4124  4163 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 13:30:01.505  4124  4124 I BtOppRfcommListener: stopping Accept Thread
08-30 13:30:01.506  4124  4172 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 13:30:01.507  4124  4172 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 13:30:01.508  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:01.508  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:30:01.511  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:30:01.512  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:30:01.515  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 13:30:01.515  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
08-30 13:30:01.516  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 13:30:01.517  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:01.517  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:30:01.518  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 13:30:01.518  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:30:01.523  4124  4124 D HeadsetService: Received stop request...Stopping profile...
08-30 13:30:01.524  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:01.524  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:30:01.525  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 13:30:01.525  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:30:01.525   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 13:30:01.526   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 13:30:01.526  3896  3907 D BluetoothHeadset: Proxy object disconnected
,08-30 13:30:01.526   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 13:30:01.528  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.528  1370  1382 D BluetoothHeadset: Proxy object disconnected
,08-30 13:30:01.530  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:01.530  1370  1370 D HeadsetProfile: Bluetooth service disconnected
,08-30 13:30:01.530  1977  1988 D BluetoothHeadset: Proxy object disconnected
08-30 13:30:01.531  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-30 13:30:01.531  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-30 13:30:01.531  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:01.531  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:01.532  4124  4124 D A2dpService: Received stop request...Stopping profile...
08-30 13:30:01.532  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.532  4124  4156 D A2dpStateMachine: Exit Disconnected: -1
08-30 13:30:01.534   873   873 D BluetoothA2dp: Proxy object disconnected
,08-30 13:30:01.534  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-30 13:30:01.534  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 13:30:01.537  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 13:30:01.537  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 13:30:01.537  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:30:01.537  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:30:01.537  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:30:01.537  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 13:30:01.538  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 13:30:01.540  1370  1370 D BluetoothPbap: Proxy object disconnected
,08-30 13:30:01.540  1370  1370 D PbapServerProfile: Bluetooth service disconnected
08-30 13:30:01.540  3896  3896 D DockEventReceiver: finishStartingService: stopping service
08-30 13:30:01.540  4124  4124 D HidService: Received stop request...Stopping profile...
08-30 13:30:01.540  4124  4124 D HidService: Stopping Bluetooth HidService
08-30 13:30:01.541  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-30 13:30:01.541  1370  1370 D HidProfile: Bluetooth service disconnected
08-30 13:30:01.541  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-30 13:30:01.541  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-30 13:30:01.541  3896  3896 D HeadsetProfile: Bluetooth service disconnected
08-30 13:30:01.541  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 13:30:01.541  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:01.541  3896  3896 D BluetoothA2dp: Proxy object disconnected
,08-30 13:30:01.542  3896  3896 D BluetoothPbap: Proxy object disconnected
,08-30 13:30:01.542  3896  3896 D PbapServerProfile: Bluetooth service disconnected
08-30 13:30:01.542  3896  3896 D BluetoothInputDevice: Proxy object disconnected
08-30 13:30:01.542  3896  3896 D HidProfile: Bluetooth service disconnected
08-30 13:30:01.544  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 13:30:01.544  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:30:01.544  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 13:30:01.544  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 13:30:01.544  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 13:30:01.544  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 13:30:01.544  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 13:30:01.545  4124  4124 D HealthService: Received stop request...Stopping profile...
,08-30 13:30:01.549  4124  4124 D PanService: Received stop request...Stopping profile...
08-30 13:30:01.550  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 13:30:01.550  1370  1370 D PanProfile: Bluetooth service disconnected
08-30 13:30:01.551  4124  4124 D BluetoothMapService: Received stop request...Stopping profile...
08-30 13:30:01.551  4124  4124 D BluetoothMapService: stop()
08-30 13:30:01.551  3896  3896 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 13:30:01.551  4124  4124 D BluetoothMapAppObserver: deinitObservers()
08-30 13:30:01.551  3896  3896 D PanProfile: Bluetooth service disconnected
08-30 13:30:01.551  4124  4124 D BluetoothMapAppObserver: removeReceiver()
08-30 13:30:01.553  3896  3896 D BluetoothMap: Proxy object disconnected
08-30 13:30:01.553  3896  3896 D MapProfile: Bluetooth service disconnected
,08-30 13:30:01.553  1370  1370 D BluetoothMap: Proxy object disconnected
08-30 13:30:01.553  1370  1370 D MapProfile: Bluetooth service disconnected
08-30 13:30:01.553  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-30 13:30:01.553  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-30 13:30:01.553  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 13:30:01.553  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:01.553  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 13:30:01.554  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 13:30:01.554  4124  4124 V BluetoothAdapterState: isTurningOff()=true
,08-30 13:30:01.554  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-30 13:30:01.554  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:01.554  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:01.554  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 13:30:01.554  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 13:30:01.555  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 13:30:01.555  4124  4140 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 13:30:01.555  4124  4124 V BluetoothAdapterState: isTurningOff()=true
,08-30 13:30:01.555  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-30 13:30:01.555  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:01.555  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:01.555  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 13:30:01.555  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 13:30:01.556  4124  4124 D BluetoothMapService: MAP Service closeService in
08-30 13:30:01.556  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-30 13:30:01.556  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-30 13:30:01.557  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:01.557  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:30:01.557  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 13:30:01.557  4124  4136 D BluetoothAdapterProperties: Setting state to 15
08-30 13:30:01.557  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 13:30:01.558  4124  4124 D BluetoothMapService: cleanup()
,08-30 13:30:01.558  1370  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-30 13:30:01.558  4124  4124 D BluetoothMapService: MAP Service closeService in
08-30 13:30:01.558  4124  4136 I BluetoothAdapterState: Entering BleOnState
08-30 13:30:01.558   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:30:01.558  3896  3909 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 13:30:01.559  3896  3907 D BluetoothPan: onBluetoothStateChange on: false
08-30 13:30:01.560  1370  1382 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 13:30:01.560   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 13:30:01.560  3896  3909 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:30:01.561  1977  2124 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:30:01.561  3896  3907 D BluetoothMap: onBluetoothStateChange: up=false
08-30 13:30:01.562  1370  2077 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 13:30:01.562  3896  3909 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 13:30:01.563   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:30:01.563  1370  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 13:30:01.563   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 13:30:01.563  1370  1382 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 13:30:01.564  1370  2077 D BluetoothPan: onBluetoothStateChange on: false
08-30 13:30:01.564  3896  3907 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 13:30:01.565  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 13:30:01.565  4124  4136 D BluetoothAdapterProperties: Setting state to 16
08-30 13:30:01.565  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 13:30:01.566  4124  4136 D BluetoothAdapterProperties: onBleDisable
08-30 13:30:01.566  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
08-30 13:30:01.567  4124  4137 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 13:30:01.568  4124  4146 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 13:30:01.568  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 13:30:01.568  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.569  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.569  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
08-30 13:30:01.570  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 13:30:01.571  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.573  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.575  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:01.575  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 13:30:01.576  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:01.584  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-30 13:30:01.773  4124  4140 I bt_hci  : shut_down
,08-30 13:30:01.775  4124  4144 D bt_hwcfg: hw_epilog_process
,08-30 13:30:01.776  4124  4144 I bt_vendor: low_power_mode_cb
,08-30 13:30:01.805  4124  4144 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 13:30:01.806  4124  4144 I bt_vendor: epilog_cb
08-30 13:30:01.806  4124  4144 I bt_hci  : epilog_finished_callback
,08-30 13:30:01.816  4124  4140 I bt_hci_h4: hal_close
,08-30 13:30:01.818  4124  4140 I bt_userial_vendor: device fd = 51 close
,08-30 13:30:01.942  4124  4137 D bt_stack_manager: event_shut_down_stack finished.
,08-30 13:30:01.944  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 13:30:01.951  4124  4136 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 13:30:01.951  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 13:30:01.953  4124  4124 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 13:30:01.953  4124  4124 D BtGatt.GattService: stop()
08-30 13:30:01.953  4124  4124 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 13:30:01.958  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:30:01.959  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-30 13:30:01.959  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:01.959  4124  4124 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 13:30:01.963  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 13:30:01.963  4124  4136 D BluetoothAdapterProperties: Setting state to 10
08-30 13:30:01.964  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 13:30:01.966  4124  4136 I BluetoothAdapterState: Entering OffState
,08-30 13:30:01.968   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 13:30:01.994  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 13:30:01.995  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 13:30:01.995  4124  4137 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 13:30:02.004  4124  4137 D bt_stack_manager: event_clean_up_stack finished.
08-30 13:30:02.004  4124  4124 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 13:30:02.011  4124  4124 I art     : System.exit called, status: 0
08-30 13:30:02.011  4124  4124 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 13:30:02.084   873  2005 I ActivityManager: Process com.android.bluetooth (pid 4124) has died
,08-30 13:30:06.480  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:06.481  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:06.485  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:06.485  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8921ca5 removed from the list
,08-30 13:30:06.486  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:06.486  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:06.486  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:06.489  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:30:06.490  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76f182b added. We now have 4 listener(s)
08-30 13:30:06.490  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:30:06.492  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:06.492  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76f182b removed from the list
,08-30 13:30:06.492  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:06.493  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:06.493  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:06.495  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:30:06.496  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fec9488 added. We now have 4 listener(s)
08-30 13:30:06.496  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:30:11.509  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:11.561   873   890 I ActivityManager: Start proc 4182:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 13:30:11.714  4182  4182 D AdapterServiceConfig: Adding HeadsetService
08-30 13:30:11.715  4182  4182 D AdapterServiceConfig: Adding A2dpService
08-30 13:30:11.715  4182  4182 D AdapterServiceConfig: Adding HidService
08-30 13:30:11.715  4182  4182 D AdapterServiceConfig: Adding HealthService
08-30 13:30:11.715  4182  4182 D AdapterServiceConfig: Adding PanService
08-30 13:30:11.716  4182  4182 D AdapterServiceConfig: Adding GattService
08-30 13:30:11.716  4182  4182 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 13:30:11.731  4182  4182 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 13:30:11.731   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b53f323:true
,08-30 13:30:11.738  4182  4182 I bt_bluedroid: init
,08-30 13:30:11.739  4182  4194 I BluetoothAdapterState: Entering OffState
,08-30 13:30:11.745  4182  4195 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 13:30:11.746  4182  4195 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 13:30:11.746  4182  4195 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 13:30:11.746  4182  4195 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 13:30:11.749  4182  4182 I bt_bluedroid: get_profile_interface socket
,08-30 13:30:11.752  4182  4182 I bt_bluedroid: get_profile_interface sdp
,08-30 13:30:11.755  4182  4198 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 13:30:11.758  4182  4198 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 13:30:11.759  4182  4193 I bt_bluedroid: config_hci_snoop_log
,08-30 13:30:11.762   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 13:30:11.774  4182  4194 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 13:30:11.775  4182  4194 D BluetoothAdapterProperties: Setting state to 14
,08-30 13:30:11.775  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 13:30:11.779  4182  4194 D BluetoothBondStateMachine: make
,08-30 13:30:11.783  4182  4199 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 13:30:11.792  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,08-30 13:30:11.793  4182  4182 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 13:30:11.804  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:30:11.807  4182  4182 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 13:30:11.809  4182  4182 D BtGatt.GattService: Received start request. Starting profile...
,08-30 13:30:11.809  4182  4182 D BtGatt.GattService: start()
08-30 13:30:11.809  4182  4182 I bt_bluedroid: get_profile_interface gatt
,08-30 13:30:11.812  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:30:11.812  4182  4182 D BtGatt.AdvertiseManager: advertise manager created
,08-30 13:30:11.826  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-30 13:30:11.826  4182  4182 V BluetoothAdapterState: isTurningOn()=false
,08-30 13:30:11.826  4182  4182 V BluetoothAdapterState: isBleTurningOn()=true
08-30 13:30:11.826  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:30:11.828  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 13:30:11.829  4182  4194 I bt_bluedroid: enable
08-30 13:30:11.829  4182  4195 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 13:30:11.830  4182  4195 I bt_hci  : start_up
,08-30 13:30:11.851  4182  4195 I bt_vendor: alloc value 0xb3a15189
,08-30 13:30:11.851  4182  4195 I bt_vendor: init
08-30 13:30:11.852  4182  4195 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 13:30:11.852  4182  4195 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 13:30:11.962  4182  4195 D bt_hci  : start_up starting async portion
,08-30 13:30:11.962  4182  4202 I bt_hci  : event_finish_startup
08-30 13:30:11.963  4182  4202 I bt_hci_h4: hal_open
08-30 13:30:11.963  4182  4202 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 13:30:11.973  4182  4202 I bt_userial_vendor: device fd = 51 open
,08-30 13:30:12.005  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 13:30:12.036  4182  4202 D bt_hwcfg: Chipset BCM4354A2
,08-30 13:30:12.036  4182  4202 D bt_hwcfg: Target name = [BCM4354A2]
08-30 13:30:12.037  4182  4202 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 13:30:12.922  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 13:30:12.923  4182  4202 D bt_hwcfg: Settlement delay -- 100 ms
08-30 13:30:12.924  4182  4202 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 13:30:13.042  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 13:30:13.044  4182  4202 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 13:30:13.072  4182  4202 I bt_hwcfg: vendor lib fwcfg completed
,08-30 13:30:13.072  4182  4202 I bt_vendor: firmware callback
08-30 13:30:13.072  4182  4202 I bt_hci  : firmware_config_callback
,08-30 13:30:13.085  4182  4204 I bt_btu  : btu_task pending for preload complete event
,08-30 13:30:13.086  4182  4204 I bt_btu_task: Bluetooth chip preload is complete
08-30 13:30:13.086  4182  4204 I bt_btu  : btu_task received preload complete event
,08-30 13:30:13.097  4182  4204 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 13:30:13.098  4182  4204 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 13:30:13.098  4182  4204 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 13:30:13.098  4182  4204 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 13:30:13.098  4182  4204 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 13:30:13.099  4182  4204 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 13:30:13.099  4182  4204 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 13:30:13.099  4182  4204 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 13:30:13.100  4182  4204 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 13:30:13.100  4182  4204 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 13:30:13.100  4182  4204 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 13:30:13.100  4182  4204 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 13:30:13.101  4182  4204 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 13:30:13.101  4182  4204 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 13:30:13.101  4182  4204 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 13:30:13.254  4182  4204 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3992d9d
08-30 13:30:13.254  4182  4204 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3992d9d 
,08-30 13:30:13.267  4182  4198 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 13:30:13.269  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 13:30:13.270  4182  4198 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 13:30:13.277  4182  4198 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 13:30:13.285  4182  4198 D BluetoothAdapterProperties: Scan Mode:20
,08-30 13:30:13.291  4182  4198 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 13:30:13.291  4182  4198 D bt_hci  : do_postload posting postload work item
,08-30 13:30:13.292  4182  4202 I bt_hci  : event_postload
08-30 13:30:13.292  4182  4202 I bt_vendor: sco_config_cb
08-30 13:30:13.292  4182  4202 I bt_hci  : sco_config_callback postload finished.
08-30 13:30:13.293  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:13.296  4182  4198 D bt_bte_conf: Device ID record 1 : primary
08-30 13:30:13.296  4182  4198 D bt_bte_conf:   vendorId            = 000f
08-30 13:30:13.296  4182  4202 I bt_vendor: low_power_mode_cb
08-30 13:30:13.296  4182  4198 D bt_bte_conf:   vendorIdSource      = 0001
08-30 13:30:13.297  4182  4198 D bt_bte_conf:   product             = 1200
08-30 13:30:13.297  4182  4198 D bt_bte_conf:   version             = 1436
,08-30 13:30:13.297  4182  4198 D bt_bte_conf:   clientExecutableURL = 
,08-30 13:30:13.297  4182  4198 D bt_bte_conf:   serviceDescription  = 
,08-30 13:30:13.297  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:13.299  4182  4198 D bt_bte_conf:   documentationURL    = 
,08-30 13:30:13.300  4182  4198 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 13:30:13.301  4182  4195 D bt_stack_manager: event_start_up_stack finished
08-30 13:30:13.302  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 13:30:13.303  4182  4194 D BluetoothAdapterProperties: Setting state to 15
08-30 13:30:13.303  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 13:30:13.305  4182  4194 I BluetoothAdapterState: Entering BleOnState
,08-30 13:30:13.308  4182  4194 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 13:30:13.308  4182  4194 D BluetoothAdapterProperties: Setting state to 11
08-30 13:30:13.308  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 13:30:13.313  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:30:13.314  4182  4182 D HeadsetService: Received start request. Starting profile...
,08-30 13:30:13.317  4182  4182 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 13:30:13.317  4182  4182 D HeadsetStateMachine: make
08-30 13:30:13.320  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:13.322  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:13.332  4182  4182 D HeadsetStateMachine: max_hf_connections = 1
08-30 13:30:13.332  4182  4182 I bt_bluedroid: get_profile_interface handsfree
,08-30 13:30:13.333  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 13:30:13.334  4182  4198 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-30 13:30:13.336  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
08-30 13:30:13.340  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:30:13.342  4182  4182 D A2dpService: Received start request. Starting profile...
08-30 13:30:13.343  4182  4182 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 13:30:13.344  4182  4182 I bt_bluedroid: get_profile_interface avrcp
,08-30 13:30:13.352  4182  4182 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 13:30:13.352  4182  4182 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 13:30:13.352  4182  4182 D A2dpStateMachine: make
08-30 13:30:13.354  4182  4182 I bt_bluedroid: get_profile_interface a2dp
,08-30 13:30:13.355  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 13:30:13.358  4182  4213 D A2dpStateMachine: Enter Disconnected: -2
,08-30 13:30:13.360  4182  4182 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 13:30:13.361  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:30:13.362  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 13:30:13.362  4182  4182 D HidService: Received start request. Starting profile...
,08-30 13:30:13.362  4182  4182 I bt_bluedroid: get_profile_interface hidhost
08-30 13:30:13.362  4182  4182 D HidService: setHidService(): set to: null
08-30 13:30:13.362  4182  4198 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39743e5
08-30 13:30:13.362  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 13:30:13.363  4182  4182 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 13:30:13.363  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:30:13.364  4182  4182 D HealthService: Received start request. Starting profile...
08-30 13:30:13.365  4182  4182 I bt_bluedroid: get_profile_interface health
,08-30 13:30:13.366  4182  4182 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 13:30:13.367  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:30:13.368  4182  4182 D PanService: Received start request. Starting profile...
08-30 13:30:13.368  4182  4182 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 13:30:13.368  4182  4182 I bt_bluedroid: get_profile_interface pan
,08-30 13:30:13.368  4182  4198 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 13:30:13.371  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
,08-30 13:30:13.372  4182  4182 D BluetoothMapService: Received start request. Starting profile...
08-30 13:30:13.372  4182  4182 D BluetoothMapService: start()
,08-30 13:30:13.377  4182  4182 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 13:30:13.379  4182  4182 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 13:30:13.379  4182  4182 D BluetoothMapAppObserver: createReceiver()
,08-30 13:30:13.381  4182  4182 D BluetoothMapAppObserver: initObservers()
,08-30 13:30:13.381  4182  4182 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 13:30:13.390  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:30:13.390  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-30 13:30:13.390  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:13.390  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:13.390  4182  4210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 13:30:13.391  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-30 13:30:13.391  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isTurningOn()=true
,08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-30 13:30:13.392  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-30 13:30:13.393  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 13:30:13.394  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 13:30:13.394  4182  4194 D BluetoothAdapterProperties: ScanMode =  20
08-30 13:30:13.394  4182  4194 D BluetoothAdapterProperties: State =  11
,08-30 13:30:13.394  4182  4194 D BluetoothAdapterProperties: Setting state to 12
08-30 13:30:13.394  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 13:30:13.395  4182  4194 I BluetoothAdapterState: Entering OnState
08-30 13:30:13.396  1370  1388 D BluetoothMap: onBluetoothStateChange: up=true
08-30 13:30:13.397  4182  4198 D BluetoothAdapterProperties: Scan Mode:21
08-30 13:30:13.397  4182  4198 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 13:30:13.398   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:30:13.399  3896  3909 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 13:30:13.399  1370  1370 D BluetoothMap: Proxy object connected
08-30 13:30:13.399  1370  1370 D MapProfile: Bluetooth service connected
08-30 13:30:13.399  1370  1370 D BluetoothMap: getConnectedDevices()
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:13.401  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 13:30:13.402  3896  3907 D BluetoothPan: onBluetoothStateChange on: true
08-30 13:30:13.403  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:30:13.405  1370  2077 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:13.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:30:13.407   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 13:30:13.408   873   873 D BluetoothA2dp: Proxy object connected
,08-30 13:30:13.408  1370  1370 D BluetoothA2dp: Proxy object connected
08-30 13:30:13.408  3896  3907 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:30:13.409  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:30:13.409  1977  2122 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:30:13.409  4182  4182 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 13:30:13.410  3896  3909 D BluetoothMap: onBluetoothStateChange: up=true
08-30 13:30:13.410  4182  4182 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 13:30:13.411  4182  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:30:13.412  3896  3896 D BluetoothInputDevice: Proxy object connected
08-30 13:30:13.412  1370  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 13:30:13.413  3896  3896 D HidProfile: Bluetooth service connected
08-30 13:30:13.413  4182  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 13:30:13.414  1370  1370 D BluetoothInputDevice: Proxy object connected
,08-30 13:30:13.414  1370  1370 D HidProfile: Bluetooth service connected
08-30 13:30:13.414  3896  3907 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 13:30:13.414  4182  4182 D ObexServerSockets: Succeed to create listening sockets 
08-30 13:30:13.414  4182  4182 D ObexServerSockets0: startAccept()
08-30 13:30:13.415  4182  4182 D ObexServerSockets0: prepareForNewConnect()
,08-30 13:30:13.416   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 13:30:13.416  1370  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 13:30:13.417   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 13:30:13.417  1370  2077 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 13:30:13.417  4182  4182 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 13:30:13.417  4182  4182 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 13:30:13.418  4182  4220 D ObexServerSockets0: Accepting socket connection...
08-30 13:30:13.418  4182  4221 D ObexServerSockets0: Accepting socket connection...
,08-30 13:30:13.419  3896  3896 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 13:30:13.419  3896  3896 D PanProfile: Bluetooth service connected
08-30 13:30:13.420  3896  3896 D BluetoothMap: Proxy object connected
,08-30 13:30:13.420  3896  3896 D MapProfile: Bluetooth service connected
08-30 13:30:13.420  3896  3896 D BluetoothMap: getConnectedDevices()
08-30 13:30:13.420  1370  1382 D BluetoothPan: onBluetoothStateChange on: true
,08-30 13:30:13.422  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 13:30:13.422  1370  1370 D PanProfile: Bluetooth service connected
08-30 13:30:13.422  3896  4219 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 13:30:13.422  3896  3896 D BluetoothA2dp: Proxy object connected
,08-30 13:30:13.425   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 13:30:13.426  4182  4182 D BluetoothMapService: onReceive
,08-30 13:30:13.426  4182  4182 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 13:30:13.426  4182  4182 D BluetoothMapService: STATE_ON
08-30 13:30:13.427  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:13.428  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:13.431  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 13:30:13.437  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 13:30:13.437  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-30 13:30:13.445  3896  3896 D BluetoothPbap: Proxy object connected
,08-30 13:30:13.445  3896  3896 D PbapServerProfile: Bluetooth service connected
,08-30 13:30:13.448  1370  1370 D BluetoothPbap: Proxy object connected
,08-30 13:30:13.448  1370  1370 D PbapServerProfile: Bluetooth service connected
,08-30 13:30:13.450  4182  4182 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 13:30:13.450  4182  4182 D ObexServerSockets0: prepareForNewConnect()
,08-30 13:30:13.453  4182  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:30:13.469  4182  4230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 13:30:13.470  4182  4230 I BtOppRfcommListener: Accept thread started.
,08-30 13:30:13.501   873   873 D BluetoothHeadset: Proxy object connected
,08-30 13:30:13.501   873   873 D BluetoothHeadset: Proxy object connected
08-30 13:30:13.501  3896  3907 D BluetoothHeadset: Proxy object connected,
08-30 13:30:13.501  3896  3896 D HeadsetProfile: Bluetooth service connected
08-30 13:30:13.501   873   873 D BluetoothHeadset: Proxy object connected
08-30 13:30:13.502  1370  2077 D BluetoothHeadset: Proxy object connected,
08-30 13:30:13.502  1370  1370 D HeadsetProfile: Bluetooth service connected
08-30 13:30:13.502  1977  1988 D BluetoothHeadset: Proxy object connected
,08-30 13:30:13.510  3896  4219 D BluetoothHeadset: Proxy object connected
,08-30 13:30:13.510  3896  3896 D HeadsetProfile: Bluetooth service connected
08-30 13:30:13.511  1977  2124 D BluetoothHeadset: Proxy object connected
,08-30 13:30:13.516   873   890 D BluetoothHeadset: Proxy object connected
,08-30 13:30:13.517  1370  1382 D BluetoothHeadset: Proxy object connected
08-30 13:30:13.517  1370  1370 D HeadsetProfile: Bluetooth service connected
08-30 13:30:13.518   873   890 D BluetoothHeadset: Proxy object connected
,08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:16.529  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:30:16.537  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:30:16.538  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:16.538  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fec9488 removed from the list
,08-30 13:30:16.538  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:16.539  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:16.539  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:16.541  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 13:30:16.542  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@62cde21 added. We now have 4 listener(s)
08-30 13:30:16.542  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:30:16.546   873  2136 D WifiService: setWifiEnabled: false pid=3799, uid=10000
08-30 13:30:16.546   873  2136 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 13:30:21.562  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:21.564   873   883 D WifiService: setWifiEnabled: true pid=3799, uid=10000
08-30 13:30:21.564   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 13:30:21.580   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:21.594  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:30:21.600  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 13:30:21.601   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-30 13:30:21.603   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 13:30:21.604   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 13:30:21.606   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 13:30:21.606   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 13:30:21.607   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 13:30:21.607   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 13:30:21.614  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 13:30:21.622  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 13:30:21.625   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 13:30:21.625   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 13:30:21.628   373   871 D CommandListener: Setting iface cfg
,08-30 13:30:21.679   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,08-30 13:30:21.679   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 13:30:21.687   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
08-30 13:30:21.688   873  1314 E native  : do suspend true
,08-30 13:30:21.689   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 13:30:21.750   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:30:22.440  1889  1935 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 13:30:22.441  1889  1935 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 13:30:22.490  1502  1502 I ConfigService: onCreate
,08-30 13:30:23.141   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 13:30:23.264   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.00 rxSuccessRate=7.69 delta 1000 -> 994
,08-30 13:30:23.265   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 13:30:23.265   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:30:23.284   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 13:30:23.334   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 13:30:23.336  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 13:30:24.012  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 13:30:24.133  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 13:30:24.136  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 13:30:24.145   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:30:24.162   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 13:30:24.163   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 13:30:24.164   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:30:24.200   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 13:30:24.217   373   871 D CommandListener: Setting iface cfg
08-30 13:30:24.218   873  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 13:30:24.233   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 13:30:24.270   873  4241 D DhcpClient: Receive thread started
,08-30 13:30:24.364   873  1314 E native  : do suspend false
,08-30 13:30:24.389   873  1866 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 13:30:24.423   873  4241 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-30 13:30:24.424   873  1866 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-30 13:30:24.428   873  1866 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 13:30:24.454   873  4241 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 13:30:24.455   873  1866 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 13:30:24.461   373   871 D CommandListener: Setting iface cfg
,08-30 13:30:24.472   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 13:30:24.474   873  1866 D DhcpClient: Scheduling renewal in 86399s
,08-30 13:30:24.474   873  1314 E native  : do suspend true
,08-30 13:30:24.500   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 13:30:24.500   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 13:30:24.501   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 13:30:24.503   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 13:30:24.504   873  1316 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 13:30:24.550   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 13:30:24.550   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 13:30:24.554   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 13:30:24.557   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 13:30:24.561   873  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 13:30:24.573   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:30:24.580   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 13:30:24.580   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 13:30:24.580   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 13:30:24.581   873  1316 D ConnectivityService:    accepting network in place of null
,08-30 13:30:24.581   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 13:30:24.582   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 13:30:24.582   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 13:30:24.630   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:30:24.664   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 13:30:24.675   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 13:30:24.676   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:30:24.691   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 13:30:24.696   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:24.706  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:24.712  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:24.719  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:24.722  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:24.722  1722  1722 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 13:30:24.740  1722  1722 D SystemUpdateService: onCreate
,08-30 13:30:24.745  1722  1722 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 13:30:24.775  1722  4250 I SystemUpdateService: active receiver: enabled
,08-30 13:30:24.778  1722  4250 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 13:30:24.783  1722  4250 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 13:30:24.783  1722  4250 I SystemUpdateService: now status is 0 (complete)
,08-30 13:30:24.783  1722  4250 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 13:30:24.783  1722  4250 I SystemUpdateService: file has been verified
08-30 13:30:24.783  1722  4250 I SystemUpdateService: OTA package size = 12249756
,08-30 13:30:24.789  1722  1722 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 13:30:24.800  1722  4253 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 13:30:24.800  1722  4253 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 13:30:24.801  1722  4253 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:30:24.811  1722  2408 I iu.UploadsManager: num queued entries: 0
,08-30 13:30:24.817  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:30:24.819  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:30:24.823  1722  4250 I SystemUpdateService: showing system update notification
,08-30 13:30:24.832  1722  1722 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 13:30:24.833  1722  1722 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 13:30:24.834  3951  3951 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 13:30:24.839  3951  3951 D SprintDMHelper: simOperator: 
,08-30 13:30:24.839  3951  3951 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 13:30:24.850  1722  2408 I iu.UploadsManager: num updated entries: 0
,08-30 13:30:24.885  1722  2408 I iu.SyncManager: NEXT; no task
,08-30 13:30:24.897  1722  1722 D SystemUpdateService: onDestroy
,08-30 13:30:24.932   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212556, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 13:30:24.944  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 13:30:24.944  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 13:30:24.944  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:30:24.944  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:30:24.968  1722  4253 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-30 13:30:25.043   873  4239 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 13:30:25.194  2246  4255 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 13:30:25.305   873  4239 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 11:30:25 GMT], X-Android-Received-Millis=[1472556625303], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472556625197]}
08-30 13:30:25.308   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 13:30:25.310   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 13:30:25.311   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:30:25.316   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 13:30:25.674   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:26.590  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:26.597  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:26.598  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:26.599  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@62cde21 removed from the list
08-30 13:30:26.599  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:26.600  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:26.600  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:26.612  3799  4263 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 13:30:26.612  3799  4263 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 13:30:27.578  1502  1502 I ConfigService: onDestroy
,08-30 13:30:29.619  3799  4265 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-30 13:30:29.620  3799  4263 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 13:30:29.620  3799  4265 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 13:30:29.621  3799  4263 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 13:30:29.621  3799  4265 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:29.621  3799  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:29.623  3799  4265 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:29.623  3799  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 13:30:29.627  3799  4265 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 13:30:29.627  3799  4263 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 13:30:29.628  3799  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Sender)
,08-30 13:30:29.630  3799  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: IncomingSocketThread/Receiver)
08-30 13:30:29.632  3799  4269 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: IncomingSocketThread/Receiver)
,08-30 13:30:29.633  3799  4269 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 13:30:29.633  3799  4269 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 13:30:29.634  3799  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
,08-30 13:30:29.637  3799  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
,08-30 13:30:29.639  3799  4270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver)
,08-30 13:30:29.640  3799  4270 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 13:30:29.640  3799  4270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 13:30:32.587   873  1316 D ConnectivityService: handlePromptUnvalidated 102
,08-30 13:30:32.619  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 13:30:32.621  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 13:30:32.628  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9668ef6 Bundle[{}]
,08-30 13:30:32.629  3799  3848 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 13:30:32.629  3799  3848 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 13:30:32.630  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 13:30:32.630  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 13:30:32.631  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 13:30:32.631  3799  3848 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 13:30:32.635  3799  3848 I System.out: Running OutgoingSocketThread
,08-30 13:30:32.639  3799  4271 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 13:30:32.639  3799  4271 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 13:30:35.648  3799  4272 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 13:30:35.648  3799  4272 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 13:30:35.648  3799  4272 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:35.649  3799  4271 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 13:30:35.649  3799  4271 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 13:30:35.650  3799  4271 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:35.650  3799  4272 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 13:30:35.652  3799  4271 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:35.657  3799  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Sender)
,08-30 13:30:35.658  3799  4272 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 13:30:35.659  3799  4271 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 13:30:35.662  3799  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Sender)
,08-30 13:30:35.665  3799  4277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Receiver)
08-30 13:30:35.667  3799  4277 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: OutgoingSocketThread/Receiver)
08-30 13:30:35.668  3799  4277 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-30 13:30:35.668  3799  4276 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
08-30 13:30:35.668  3799  4277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 13:30:35.670  3799  4276 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
08-30 13:30:35.670  3799  4276 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 13:30:35.671  3799  4276 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 13:30:38.650  3799  3848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448),
08-30 13:30:38.653  3799  3848 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 13:30:38.653  3799  3848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-30 13:30:38.659  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:30:38.659  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4ed246 added. We now have 3 listener(s)
,08-30 13:30:38.661  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:30:38.661  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 13:30:38.661  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:30:38.661  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:30:38.662  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc50c07 added. We now have 4 listener(s)
08-30 13:30:38.662  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:30:38.662  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 13:30:38.667  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:38.688  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:38.695  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:38.695  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:30:38.699  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:30:38.699  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:38.699  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:30:38.699  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 13:30:38.700  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:30:38.700  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:38.700  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:30:38.700  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 13:30:38.700  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4ed246 removed from the list
08-30 13:30:38.700  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:38.701  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc50c07 removed from the list
,08-30 13:30:38.701  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:38.701  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:30:38.701  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:38.702  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:38.702  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:38.705  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:30:38.705  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:30:38.705  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:38.706  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc50c07 not in the list
,08-30 13:30:38.706  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:38.706  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:38.709  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:30:38.709  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:30:38.709  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:38.709  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc50c07 not in the list
08-30 13:30:38.710  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:30:38.710  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:38.710  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:38.710  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4ed246 not in the list
08-30 13:30:38.712  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:30:38.712  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4583b5d added. We now have 3 listener(s)
,08-30 13:30:38.718  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:30:38.719  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:30:38.719  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 13:30:38.720  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:30:38.720  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295ccd2 added. We now have 4 listener(s)
,08-30 13:30:38.720  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:30:38.722  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:30:38.727  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:38.735  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:38.739  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:38.739  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:30:38.740  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:30:38.741  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 13:30:38.741  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 13:30:38.742  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:38.742  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:30:38.743  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:38.746  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:38.748  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 13:30:38.748  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:30:38.753  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:30:38.754  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 13:30:38.755  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:30:38.760  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 13:30:38.760  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 13:30:38.760  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 13:30:38.760  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:30:38.766  4182  4193 D BtGatt.GattService: registerClient() - UUID=bd9460aa-b28a-44be-9e7f-c7059603a847
,08-30 13:30:38.767  4182  4198 D BtGatt.GattService: onClientRegistered() - UUID=bd9460aa-b28a-44be-9e7f-c7059603a847, clientIf=5
,08-30 13:30:38.768  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 13:30:38.769  4182  4211 D BtGatt.GattService: start scan with filters
,08-30 13:30:38.774  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 13:30:38.774  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 13:30:38.774  4182  4201 D BtGatt.ScanManager: handling starting scan
08-30 13:30:38.774  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 13:30:38.774  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 13:30:38.777  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:30:38.777  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 13:30:38.777  4182  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43afa2a
08-30 13:30:38.778  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 13:30:38.779  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:30:38.782  3799  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 13:30:38.782  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:30:38.783  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:30:38.783  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:38.783  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 13:30:38.783  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 13:30:38.783  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 13:30:38.783  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 13:30:38.783  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:30:38.784  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 13:30:38.784  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 13:30:38.784  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:30:38.785  4182  4193 D BtGatt.GattService: stopScan() - queue size =1
08-30 13:30:38.786  4182  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 13:30:38.786  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 13:30:38.786  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 13:30:38.787  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 13:30:38.787  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:30:38.787  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 13:30:38.788  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:30:38.788  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 13:30:38.788  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 13:30:38.788  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 13:30:38.789  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:30:38.791  4182  4198 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 13:30:38.790  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:30:38.791  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:30:38.791  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:30:38.791  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:30:38.792  4182  4201 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:30:38.809  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-30 13:30:38.809  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:30:38.810  4182  4201 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 13:30:38.810  4182  4201 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 13:30:38.844  4182  4198 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 13:30:38.844  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:38.865  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 13:30:38.866  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:38.894  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 13:30:38.895  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:30:38.895  4182  4201 D BtGatt.ScanManager: stopping BLe Batch
,08-30 13:30:38.918  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 13:30:38.918  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:38.919  4182  4201 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:30:38.942  4182  4198 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 13:30:38.943  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:39.292  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:30:39.292  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 13:30:39.292  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:30:41.791  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:30:41.791  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:30:41.792  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:30:41.792  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:30:41.792  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:41.793  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:30:41.793  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 13:30:41.793  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4583b5d removed from the list
,08-30 13:30:41.794  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:41.794  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295ccd2 removed from the list
,08-30 13:30:41.794  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:41.795  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:41.796  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:41.797  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:41.800  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:30:41.800  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:30:41.800  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:41.801  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295ccd2 not in the list
08-30 13:30:41.801  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:41.801  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:41.805  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:30:41.805  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:30:41.805  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:41.806  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295ccd2 not in the list
08-30 13:30:41.806  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:30:41.806  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:41.806  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:41.807  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4583b5d not in the list
08-30 13:30:41.809  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 13:30:41.809  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30974ff added. We now have 3 listener(s)
08-30 13:30:41.812  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:30:41.812  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 13:30:41.812  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:30:41.813  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 13:30:41.813  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e6b2cc added. We now have 4 listener(s)
08-30 13:30:41.813  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:30:41.814  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:30:41.816  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:41.824  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:41.834  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:41.834  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:30:41.834  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 13:30:41.835  3799  3848 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-30 13:30:41.835  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-30 13:30:41.837  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 13:30:41.837  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:41.837  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 13:30:41.838  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 13:30:41.838  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:41.839  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 13:30:41.840  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 13:30:41.840  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 13:30:41.840  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 13:30:41.841  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-30 13:30:41.841  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:41.841  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:30:41.842  3799  4278 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 13:30:41.844  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:41.844  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 13:30:41.846  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 13:30:41.846  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 13:30:41.847  3799  4278 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 13:30:41.851  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:30:41.852  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 13:30:41.852  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:30:41.857  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 13:30:41.857  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:30:41.857  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-30 13:30:41.859  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 13:30:41.859  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 13:30:41.859  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 13:30:41.860  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:30:41.864  4182  4193 D BtGatt.GattService: registerClient() - UUID=d5850d47-da0f-4275-80ea-ef9d90ec7f87
,08-30 13:30:41.865  4182  4198 D BtGatt.GattService: onClientRegistered() - UUID=d5850d47-da0f-4275-80ea-ef9d90ec7f87, clientIf=5
,08-30 13:30:41.865  3799  3809 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 13:30:41.868  4182  4200 D BtGatt.AdvertiseManager: message : 0
,08-30 13:30:41.872  4182  4200 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 13:30:41.886  4182  4198 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 13:30:41.896  4182  4198 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 13:30:41.897  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 13:30:41.898  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 13:30:41.900  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:30:41.902  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 13:30:41.902  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 13:30:41.902  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 13:30:41.903  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 13:30:41.903  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 13:30:41.903  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 13:30:41.906  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 13:30:41.906  3799  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 13:30:41.906  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 13:30:42.408  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 13:30:42.408  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 13:30:42.408  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:30:44.907  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:30:44.908  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-30 13:30:44.908  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 13:30:44.909  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 13:30:44.909  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 13:30:44.909  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 13:30:44.912  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 13:30:44.912  3799  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 13:30:44.913  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 13:30:44.913  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 13:30:44.913  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 13:30:44.913  3799  4278 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 13:30:44.913  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 13:30:44.914  3799  4278 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 13:30:44.914  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 13:30:44.914  3799  4278 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 13:30:44.914  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 13:30:44.917  3799  3848 D BluetoothAdapter: STATE_ON
08-30 13:30:44.917  3799  3848 D BluetoothLeScanner: could not find callback wrapper
,08-30 13:30:44.917  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 13:30:44.918  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 13:30:44.920  4182  4200 D BtGatt.AdvertiseManager: message : 1
,08-30 13:30:44.922  4182  4200 D BtGatt.AdvertiseManager: stop advertise for client 5
08-30 13:30:44.932  4182  4198 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-30 13:30:44.932  4182  4198 D BtGatt.GattService: Client app is not null!
,08-30 13:30:44.934  4182  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:30:44.935  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 13:30:44.935  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 13:30:44.936  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 13:30:44.936  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-30 13:30:44.936  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 13:30:44.939  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:30:44.939  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 13:30:44.939  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 13:30:44.940  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:30:44.943  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:30:44.943  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:44.944  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 13:30:44.944  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 13:30:44.944  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 13:30:44.944  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30974ff removed from the list
08-30 13:30:44.944  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:30:44.944  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:44.945  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 13:30:44.945  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e6b2cc removed from the list
,08-30 13:30:44.945  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 13:30:44.945  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-30 13:30:44.945  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:44.946  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:44.947  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:44.949  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:30:44.949  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:30:44.950  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:44.950  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e6b2cc not in the list
08-30 13:30:44.950  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:44.950  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:44.953  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:30:44.953  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:30:44.953  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:44.954  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e6b2cc not in the list
08-30 13:30:44.954  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:30:44.954  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:44.954  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 13:30:44.955  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30974ff not in the list
08-30 13:30:44.956  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 13:30:44.957  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5389191 added. We now have 3 listener(s)
,08-30 13:30:44.962  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 13:30:44.963  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 13:30:44.963  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 13:30:44.964  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 13:30:44.964  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9658f6 added. We now have 4 listener(s)
08-30 13:30:44.964  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 13:30:44.965  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 13:30:44.971  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:44.978  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:44.981  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:44.981  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 13:30:44.982  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:30:44.982  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 13:30:44.982  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 13:30:44.982  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:30:44.982  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 13:30:44.985  3799  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 13:30:44.986  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 13:30:44.987  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:44.990  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 13:30:44.991  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 13:30:44.991  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 13:30:44.993  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 13:30:44.996  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 13:30:44.996  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 13:30:44.996  3799  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 13:30:44.997  3799  3848 D BluetoothAdapter: STATE_ON
,08-30 13:30:45.000  4182  4211 D BtGatt.GattService: registerClient() - UUID=ea894eb9-06de-417d-825c-e1fa7930a7e9
,08-30 13:30:45.001  4182  4198 D BtGatt.GattService: onClientRegistered() - UUID=ea894eb9-06de-417d-825c-e1fa7930a7e9, clientIf=5
08-30 13:30:45.001  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 13:30:45.002  4182  4192 D BtGatt.GattService: start scan with filters
,08-30 13:30:45.005  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 13:30:45.005  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 13:30:45.005  4182  4201 D BtGatt.ScanManager: handling starting scan
08-30 13:30:45.005  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 13:30:45.006  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 13:30:45.012  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:30:45.012  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 13:30:45.013  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 13:30:45.014  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 13:30:45.018  4182  4198 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 13:30:45.018  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 13:30:45.019  4182  4201 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 13:30:45.031  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 13:30:45.031  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:45.032  4182  4201 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 13:30:45.032  4182  4201 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-30 13:30:45.048  4182  4198 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 13:30:45.048  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:45.057  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 13:30:45.057  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:45.445  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:30:45.513  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 13:30:45.513  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 13:30:45.514  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 13:30:46.565  4182  4182 D BtGatt.ScanManager: awakened up at time 234189
,08-30 13:30:46.567  4182  4201 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:30:46.594  4182  4198 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-30 13:30:46.595  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:46.595  4182  4198 D BtGatt.GattService: current time is 234219461519
,08-30 13:30:46.597  4182  4198 D BtGatt.GattService: Batch record : [-84, 20, 17, 3, -40, 112, 1, -128, -89, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 53, 33, -121, 80, 73, -44, 1, 0, -104, 25, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -115, -55, -18, 2, 2, -29, 21, 63, 47, -55, -100, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 13:30:46.600  4182  4198 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58]
,08-30 13:30:46.602  4182  4198 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74],
08-30 13:30:46.603  4182  4198 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -115, -55, -18, 2, 2, -29, 21, 63, 47, -55, -100, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0],
,08-30 13:30:46.604  4182  4198 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-30 13:30:46.604  4182  4198 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-30 13:30:46.605  4182  4198 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-30 13:30:46.606  4182  4198 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 13:30:46.609  3799  3799 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 60:83:34:25:D7:C6 1], added - the peer count is 1
,08-30 13:30:46.610  3799  3799 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 60:83:34:25:D7:C6 1], Bluetooth address: 60:83:34:25:D7:C6, device name: '', device address: '',
,08-30 13:30:48.026  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:30:48.027  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:30:48.027  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 13:30:48.027  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:48.028  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 13:30:48.028  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 13:30:48.028  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 13:30:48.028  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 13:30:48.029  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 13:30:48.029  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-30 13:30:48.029  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 13:30:48.032  3799  3848 D BluetoothAdapter: STATE_ON
08-30 13:30:48.034  4182  4218 D BtGatt.GattService: stopScan() - queue size =1
,08-30 13:30:48.038  4182  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 13:30:48.039  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 13:30:48.039  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 13:30:48.039  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 13:30:48.039  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 13:30:48.040  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 13:30:48.043  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:30:48.043  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 13:30:48.043  3799  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 13:30:48.044  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 13:30:48.045  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:30:48.045  3799  3848 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-30 13:30:48.045  4182  4182 D BtGatt.ScanManager: awakened up at time 235669
,08-30 13:30:48.048  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:30:48.048  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 13:30:48.048  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 13:30:48.049  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:30:48.049  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:48.049  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:30:48.050  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
,08-30 13:30:48.050  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5389191 removed from the list
,08-30 13:30:48.050  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:48.050  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9658f6 removed from the list
,08-30 13:30:48.050  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:30:48.050  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.051  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:48.052  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.054  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:30:48.054  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:30:48.054  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:48.054  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9658f6 not in the list
,08-30 13:30:48.054  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:48.055  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.057  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:30:48.057  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:30:48.058  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:48.058  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 13:30:48.059  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:48.059  4182  4201 D BtGatt.ScanManager: stopping BLe Batch
,08-30 13:30:48.060  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9658f6 not in the list
,08-30 13:30:48.060  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:30:48.060  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:48.061  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.061  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5389191 not in the list,
08-30 13:30:48.063  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 13:30:48.063  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dff3dd0 added. We now have 3 listener(s)
,08-30 13:30:48.071  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 13:30:48.071  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 13:30:48.071  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:48.071  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 13:30:48.072  4182  4201 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 13:30:48.072  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 13:30:48.072  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 13:30:48.073  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@962e1c9 added. We now have 4 listener(s)
08-30 13:30:48.073  3799  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 13:30:48.074  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 13:30:48.081  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 13:30:48.083  4182  4198 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 13:30:48.084  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 13:30:48.089  3799  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 13:30:48.091  3799  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 13:30:48.092  3799  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 13:30:48.093  3799  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 13:30:48.093  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:30:48.093  3799  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 13:30:48.094  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 13:30:48.094  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:48.094  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 13:30:48.094  3799  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 13:30:48.095  3799  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dff3dd0 removed from the list
08-30 13:30:48.095  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:48.095  3799  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@962e1c9 removed from the list
08-30 13:30:48.095  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:48.095  3799  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 13:30:48.096  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.097  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:48.097  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.099  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 13:30:48.099  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 13:30:48.100  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 13:30:48.100  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 13:30:48.100  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@962e1c9 not in the list
,08-30 13:30:48.100  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 13:30:48.100  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.102  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 13:30:48.102  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 13:30:48.102  3799  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 13:30:48.103  3799  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@962e1c9 not in the list
08-30 13:30:48.103  3799  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 13:30:48.103  3799  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 13:30:48.103  3799  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 13:30:48.104  3799  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dff3dd0 not in the list
,08-30 13:30:48.106  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-30 13:30:48.106  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 13:30:48.107  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 13:30:48.107  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 13:30:48.107  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-30 13:30:48.108  3799  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 13:30:48.550  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 13:30:50.129  3799  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,08-30 13:30:52.127  3799  3848 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 458
,08-30 13:30:52.127  3799  3848 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 458, name: My test thread name)
,08-30 13:30:52.134  3799  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,08-30 13:30:52.135  3799  4281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: My test thread name)
08-30 13:30:52.135  3799  4281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 13:30:52.139  3799  3848 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 13:30:52.148  3799  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-30 13:30:52.149  3799  4282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,08-30 13:30:52.150  3799  4282 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 463, thread name: My test thread name): Test exception.
08-30 13:30:52.150  3799  4282 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 13:30:52.158  3799  3848 I jxcore-log: Total number of executed tests:  82
08-30 13:30:52.158  3799  3848 I jxcore-log: 
,08-30 13:30:52.159  3799  3848 I jxcore-log: Number of passed tests:  82
08-30 13:30:52.159  3799  3848 I jxcore-log: 
08-30 13:30:52.160  3799  3848 I jxcore-log: Number of failed tests:  0
08-30 13:30:52.160  3799  3848 I jxcore-log: 
,08-30 13:30:52.160  3799  3848 I jxcore-log: Number of ignored tests:  0
08-30 13:30:52.160  3799  3848 I jxcore-log: 
08-30 13:30:52.161  3799  3848 I jxcore-log: Total duration:  101311
08-30 13:30:52.161  3799  3848 I jxcore-log: 
,08-30 13:30:52.171  3799  3848 I jxcore-log: Unit Test app is loaded
08-30 13:30:52.171  3799  3848 I jxcore-log: 
,08-30 13:30:52.193  3799  3799 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 13:30:52.195  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.195  3799  3848 I jxcore-log: 
,08-30 13:30:52.208  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.208  3799  3848 I jxcore-log: 
,08-30 13:30:52.209  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.209  3799  3848 I jxcore-log: 
,08-30 13:30:52.211  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.211  3799  3848 I jxcore-log: 
,08-30 13:30:52.213  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 13:30:52.213  3799  3848 I jxcore-log: 
,08-30 13:30:52.216  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:30:52.216  3799  3848 I jxcore-log: 
,08-30 13:30:52.218  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.218  3799  3848 I jxcore-log: 
08-30 13:30:52.220  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.220  3799  3848 I jxcore-log: 
,08-30 13:30:52.221  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 13:30:52.221  3799  3848 I jxcore-log: 
,08-30 13:30:52.222  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:30:52.222  3799  3848 I jxcore-log: 
08-30 13:30:52.224  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:30:52.224  3799  3848 I jxcore-log: 
,08-30 13:30:52.225  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.225  3799  3848 I jxcore-log: 
,08-30 13:30:52.226  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.226  3799  3848 I jxcore-log: 
08-30 13:30:52.227  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.227  3799  3848 I jxcore-log: 
08-30 13:30:52.228  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.228  3799  3848 I jxcore-log: 
,08-30 13:30:52.229  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.229  3799  3848 I jxcore-log: 
,08-30 13:30:52.232  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.232  3799  3848 I jxcore-log: 
,08-30 13:30:52.234  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.234  3799  3848 I jxcore-log: 
,08-30 13:30:52.235  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.235  3799  3848 I jxcore-log: 
,08-30 13:30:52.236  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.236  3799  3848 I jxcore-log: 
,08-30 13:30:52.238  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.238  3799  3848 I jxcore-log: 
08-30 13:30:52.238  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.238  3799  3848 I jxcore-log: 
08-30 13:30:52.239  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.239  3799  3848 I jxcore-log: 
,08-30 13:30:52.240  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.240  3799  3848 I jxcore-log: 
08-30 13:30:52.241  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.241  3799  3848 I jxcore-log: 
08-30 13:30:52.241  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.241  3799  3848 I jxcore-log: 
,08-30 13:30:52.242  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.242  3799  3848 I jxcore-log: 
08-30 13:30:52.243  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.243  3799  3848 I jxcore-log: 
,08-30 13:30:52.244  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.244  3799  3848 I jxcore-log: 
08-30 13:30:52.246  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.246  3799  3848 I jxcore-log: 
,08-30 13:30:52.248  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.248  3799  3848 I jxcore-log: 
08-30 13:30:52.251  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.251  3799  3848 I jxcore-log: 
,08-30 13:30:52.253  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.253  3799  3848 I jxcore-log: 
,08-30 13:30:52.255  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.255  3799  3848 I jxcore-log: 
,08-30 13:30:52.257  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.257  3799  3848 I jxcore-log: 
,08-30 13:30:52.259  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.259  3799  3848 I jxcore-log: 
,08-30 13:30:52.261  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.261  3799  3848 I jxcore-log: 
,08-30 13:30:52.263  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.263  3799  3848 I jxcore-log: 
,08-30 13:30:52.265  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.265  3799  3848 I jxcore-log: 
,08-30 13:30:52.267  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.267  3799  3848 I jxcore-log: 
,08-30 13:30:52.269  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 13:30:52.269  3799  3848 I jxcore-log: 
,08-30 13:30:52.270  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.270  3799  3848 I jxcore-log: 
08-30 13:30:52.271  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 13:30:52.271  3799  3848 I jxcore-log: 
,08-30 13:30:52.271  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.271  3799  3848 I jxcore-log: 
08-30 13:30:52.272  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.272  3799  3848 I jxcore-log: 
08-30 13:30:52.272  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.272  3799  3848 I jxcore-log: 
,08-30 13:30:52.273  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.273  3799  3848 I jxcore-log: 
08-30 13:30:52.274  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.274  3799  3848 I jxcore-log: 
08-30 13:30:52.274  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:30:52.274  3799  3848 I jxcore-log: 
,08-30 13:30:52.275  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.275  3799  3848 I jxcore-log: 
08-30 13:30:52.276  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 13:30:52.276  3799  3848 I jxcore-log: 
,08-30 13:30:52.276  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.276  3799  3848 I jxcore-log: 
08-30 13:30:52.277  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:30:52.277  3799  3848 I jxcore-log: 
,08-30 13:30:52.277  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 13:30:52.277  3799  3848 I jxcore-log: 
,08-30 13:30:52.279  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 13:30:52.279  3799  3848 I jxcore-log: 
08-30 13:30:52.279  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 13:30:52.279  3799  3848 I jxcore-log: 
,08-30 13:30:52.280  3799  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 13:30:52.280  3799  3848 I jxcore-log: 
,08-30 13:30:52.283  3799  3848 I jxcore-log: My device name is: motorola-Nexus 6
08-30 13:30:52.283  3799  3848 I jxcore-log: 
,08-30 13:30:54.808  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 13:30:54.808  3799  3848 I jxcore-log: 
,08-30 13:30:55.273  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 13:30:55.273  3799  3848 I jxcore-log: 
,08-30 13:30:55.298  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 13:30:55.298  3799  3848 I jxcore-log: 
,08-30 13:30:56.480   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:30:56.711  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 13:30:56.711  3799  3848 I jxcore-log: 
,08-30 13:30:56.951  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-30 13:30:56.951  3799  3848 I jxcore-log: 
,08-30 13:30:56.957  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-30 13:30:56.957  3799  3848 I jxcore-log: 
,08-30 13:30:56.963  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
08-30 13:30:56.963  3799  3848 I jxcore-log: 
,08-30 13:30:57.051  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-30 13:30:57.051  3799  3848 I jxcore-log: 
,08-30 13:30:57.071  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-30 13:30:57.071  3799  3848 I jxcore-log: 
,08-30 13:30:57.077  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
08-30 13:30:57.077  3799  3848 I jxcore-log: 
,08-30 13:30:58.075  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
08-30 13:30:58.075  3799  3848 I jxcore-log: 
,08-30 13:30:58.251  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-30 13:30:58.251  3799  3848 I jxcore-log: 
,08-30 13:30:58.589  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-30 13:30:58.589  3799  3848 I jxcore-log: 
,08-30 13:30:58.602  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-30 13:30:58.602  3799  3848 I jxcore-log: 
,08-30 13:30:58.612  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-30 13:30:58.612  3799  3848 I jxcore-log: 
,08-30 13:30:58.619  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-30 13:30:58.619  3799  3848 I jxcore-log: 
,08-30 13:30:58.660  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-30 13:30:58.660  3799  3848 I jxcore-log: 
,08-30 13:30:58.709  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-30 13:30:58.709  3799  3848 I jxcore-log: 
,08-30 13:30:58.716  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-30 13:30:58.716  3799  3848 I jxcore-log: 
,08-30 13:30:58.724  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-30 13:30:58.724  3799  3848 I jxcore-log: 
,08-30 13:30:58.745  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-30 13:30:58.745  3799  3848 I jxcore-log: 
,08-30 13:30:58.751  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-30 13:30:58.751  3799  3848 I jxcore-log: 
,08-30 13:30:58.757  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-30 13:30:58.757  3799  3848 I jxcore-log: 
,08-30 13:30:58.774  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-30 13:30:58.774  3799  3848 I jxcore-log: 
,08-30 13:30:58.801  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-30 13:30:58.801  3799  3848 I jxcore-log: 
,08-30 13:30:58.812  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-30 13:30:58.812  3799  3848 I jxcore-log: 
,08-30 13:30:58.826  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-30 13:30:58.826  3799  3848 I jxcore-log: 
,08-30 13:30:58.838  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-30 13:30:58.838  3799  3848 I jxcore-log: 
,08-30 13:30:58.854  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-30 13:30:58.854  3799  3848 I jxcore-log: 
,08-30 13:30:58.882  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-30 13:30:58.882  3799  3848 I jxcore-log: 
,08-30 13:30:58.889  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-30 13:30:58.889  3799  3848 I jxcore-log: 
,08-30 13:30:58.930  3799  3848 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-30 13:30:58.930  3799  3848 I jxcore-log: 
,08-30 13:30:58.941  3799  3848 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-30 13:30:58.942  3799  3848 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-30 13:30:58.942  3799  3848 I jxcore-log: 
,08-30 13:30:59.154  3610  4284 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 13:30:59.181  3610  4285 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 13:30:59.200  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:30:59.202  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:30:59.245  1502  3090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:30:59.245  1502  3090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 13:30:59.246  1502  3090 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:30:59.246  1502  3090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:30:59.286  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:30:59.288  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:30:59.325  1502  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:30:59.325  1502  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 13:30:59.325  1502  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:30:59.325  1502  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:30:59.355  3610  4285 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 13:30:59.356  3610  4284 E BooksSync: Soft error
08-30 13:30:59.356  3610  4284 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:30:59.356  3610  4284 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 13:30:59.357  3610  4284 E BooksSync: Sync error
08-30 13:30:59.357  3610  4284 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:30:59.357  3610  4284 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 13:30:59.357  3610  4284 I BooksSync: Finished books sync
,08-30 13:30:59.369   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246751, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:31:04.000   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=251623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:31:29.680  3610  4287 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 13:31:29.722  3610  4288 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 13:31:29.746  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:31:29.753  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:31:29.807  1502  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:31:29.807  1502  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:31:29.808  1502  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:31:29.808  1502  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:31:29.862  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:31:29.865  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:31:29.916  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:31:29.916  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:31:29.916  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:31:29.916  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:31:29.950  3610  4288 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 13:31:29.951  3610  4287 E BooksSync: Soft error
08-30 13:31:29.951  3610  4287 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:31:29.951  3610  4287 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:31:29.951  3610  4287 E BooksSync: Sync error
08-30 13:31:29.951  3610  4287 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:31:29.951  3610  4287 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:31:29.951  3610  4287 I BooksSync: Finished books sync
,08-30 13:31:29.971   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277104, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:31:33.989  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:31:33.992  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:31:34.043  4046  4290 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:31:34.093  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-30 13:31:34.093  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 13:31:34.093  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:31:34.093  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:31:34.119  4046  4290 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 13:31:34.120  4046  4290 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 13:31:34.347   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=281970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:31:40.947   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=288571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:32:00.487  3024  4296 V KeepSync: Connecting to GoogleApiClient
,08-30 13:32:00.487   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 13:32:00.513  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:00.526  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:00.602  1502  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:32:00.602  1502  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 13:32:00.602  1502  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:32:00.603  1502  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:00.622  3555  4298 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 13:32:00.622  3555  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at blb.a(PG:3937)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at czp.a(PG:18188)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:32:00.622  3555  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	... 12 more
08-30 13:32:00.622  3555  4298 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at fal.a(PG:38)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:32:00.622  3555  4298 E HttpOperation: 	... 14 more
,08-30 13:32:00.732  1502  3090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:32:00.733  1502  3090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 13:32:00.733  1502  3090 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:32:00.733  1502  3090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:00.733  1502  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 13:32:00.733  1502  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 13:32:00.733  1502  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:32:00.733  1502  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:00.758  3555  4298 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 13:32:00.758  3555  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at hec.a(PG:42)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at hee.a(PG:102)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at czr.a(PG:65)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at kka.a(PG:108)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at czp.a(PG:19176)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at czq.run(PG:1686),
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:32:00.758  3555  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	... 15 more
08-30 13:32:00.758  3555  4298 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at fal.a(PG:38)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:32:00.758  3555  4298 E HttpOperation: 	... 17 more
,08-30 13:32:00.758  3555  4298 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 13:32:00.758  3555  4298 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at hec.a(PG:42)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at hee.a(PG:102)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at czr.a(PG:65)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at kka.a(PG:108)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	... 15 more
08-30 13:32:00.758  3555  4298 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at fal.a(PG:38)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 13:32:00.758  3555  4298 E ExperimentLoader: 	... 17 more
,08-30 13:32:00.762  1722  4299 V BaseAuthAsyncOperation: access token request failed
,08-30 13:32:00.765  3024  4296 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 13:32:00.881   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 279767, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:32:00.900  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 13:32:00.900  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 13:32:00.900  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:32:00.901  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:00.926  3024  4296 E KeepSync: IOException
08-30 13:32:00.926  3024  4296 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 13:32:00.926  3024  4296 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:32:00.926  3024  4296 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 13:32:00.926  3024  4296 E KeepSync: 	... 10 more
,08-30 13:32:00.926  3024  4296 W KeepSync: Sync result 2
,08-30 13:32:00.932   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 279175, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:32:04.254  4046  4304 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:32:04.285  1502  4302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 13:32:04.285  1502  4302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-30 13:32:04.285  1502  4302 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:32:04.286  1502  4302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 13:32:04.307  4046  4304 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 13:32:11.253   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=318877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:32:16.707   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:32:31.043  3610  4306 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 13:32:31.072  3610  4307 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 13:32:31.084  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:31.087  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:31.120  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:32:31.120  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:32:31.120  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:32:31.120  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:31.146  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:31.149  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:31.185  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:32:31.186  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:32:31.186  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:32:31.186  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:31.209  3610  4307 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 13:32:31.211  3610  4306 E BooksSync: Soft error
08-30 13:32:31.211  3610  4306 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:32:31.211  3610  4306 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:32:31.211  3610  4306 E BooksSync: Sync error
08-30 13:32:31.211  3610  4306 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:32:31.211  3610  4306 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 13:32:31.211  3610  4306 I BooksSync: Finished books sync
,08-30 13:32:31.221   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 337816, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:32:34.426  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:34.441  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 13:32:34.444  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:32:34.511  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-30 13:32:34.511  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-30 13:32:34.512  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:32:34.512  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:32:34.564  1502  2006 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 13:32:34.564  1502  2006 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 13:32:34.564  1502  2006 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 13:32:34.564  1502  2006 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-30 13:32:34.564  1502  2006 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-30 13:32:34.564  1502  2006 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-30 13:32:34.564  1502  2006 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 13:32:34.581  3518  3547 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 13:32:34.581  3518  3547 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-30 13:32:34.581  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-30 13:32:34.581  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-30 13:32:34.581  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-30 13:32:34.581  3518  3547 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-30 13:32:34.581  3518  3547 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 13:33:01.589  3024  4313 V KeepSync: Connecting to GoogleApiClient
,08-30 13:33:01.589   873  2135 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 13:33:01.645  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:33:01.646  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:33:01.674  1502  2006 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 13:33:01.674  1502  2006 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 13:33:01.674  1502  2006 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:33:01.675  1502  2006 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:33:01.710  1722  4315 V BaseAuthAsyncOperation: access token request failed
,08-30 13:33:01.714  3024  4313 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 13:33:01.751  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:33:01.752  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 13:33:01.752  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:33:01.752  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:33:01.793  3555  4314 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 13:33:01.793  3555  4314 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at blb.a(PG:3937)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at czp.a(PG:18188)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:33:01.793  3555  4314 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	... 12 more
08-30 13:33:01.793  3555  4314 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at fal.a(PG:38)
08-30 13:33:01.793  3555  4314 E HttpOperation: 	at jdj.a(PG:4089)
,08-30 13:33:01.793  3555  4314 E HttpOperation: 	... 14 more
,08-30 13:33:01.868  1502  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:33:01.868  1502  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 13:33:01.869  1502  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:33:01.869  1502  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:33:01.894  3555  4314 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 13:33:01.894  3555  4314 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at hec.a(PG:42)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at hee.a(PG:102)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at czr.a(PG:65)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at kka.a(PG:108)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at czp.a(PG:19176)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:33:01.894  3555  4314 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	... 15 more
08-30 13:33:01.894  3555  4314 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at fal.a(PG:38)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:33:01.894  3555  4314 E HttpOperation: 	... 17 more
,08-30 13:33:01.895  3555  4314 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 13:33:01.895  3555  4314 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at hec.a(PG:42)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at hee.a(PG:102)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at czr.a(PG:65)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at kka.a(PG:108)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	... 15 more
08-30 13:33:01.895  3555  4314 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at fal.a(PG:38)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 13:33:01.895  3555  4314 E ExperimentLoader: 	... 17 more
,08-30 13:33:01.982  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 13:33:01.983  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 13:33:01.983  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:33:01.983  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:33:02.011   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 340843, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:33:02.016  3024  4313 E KeepSync: IOException
08-30 13:33:02.016  3024  4313 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 13:33:02.016  3024  4313 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:33:02.016  3024  4313 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 13:33:02.016  3024  4313 E KeepSync: 	... 10 more
,08-30 13:33:02.016  3024  4313 W KeepSync: Sync result 2
,08-30 13:33:02.030   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 339442, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:33:04.412  4046  4317 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:33:04.466  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 13:33:04.467  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 13:33:04.467  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:33:04.467  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:33:04.501  4046  4317 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 13:33:04.502  4046  4317 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 13:33:06.026   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=373650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:33:12.907   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:33:43.520   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:33:49.040   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=416664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:34:04.172  3024  4321 V KeepSync: Connecting to GoogleApiClient
,08-30 13:34:04.173   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 13:34:04.237  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:34:04.244  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:34:04.275  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 13:34:04.275  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 13:34:04.276  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:34:04.276  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:34:04.295  1722  4322 V BaseAuthAsyncOperation: access token request failed
,08-30 13:34:04.296  3024  4321 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 13:34:04.335  1502  3090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 13:34:04.335  1502  3090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 13:34:04.335  1502  3090 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:34:04.335  1502  3090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:34:04.349  3024  4321 E KeepSync: IOException
08-30 13:34:04.349  3024  4321 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 13:34:04.349  3024  4321 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:34:04.349  3024  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 13:34:04.349  3024  4321 E KeepSync: 	... 10 more
,08-30 13:34:04.350  3024  4321 W KeepSync: Sync result 2
,08-30 13:34:04.365   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 431425, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:34:19.360   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=446984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:34:24.693   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=452317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:34:34.503  3610  4326 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 13:34:34.603  3610  4328 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 13:34:34.617  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:34:34.622  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:34:34.657  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:34:34.657  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 13:34:34.657  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:34:34.657  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:34:34.694  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:34:34.697  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:34:34.768  1502  4302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:34:34.768  1502  4302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 13:34:34.768  1502  4302 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:34:34.768  1502  4302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:34:34.769  1502  3090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 13:34:34.769  1502  3090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 13:34:34.770  1502  3090 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:34:34.770  1502  3090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:34:34.789  3555  4327 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 13:34:34.789  3555  4327 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at blb.a(PG:3937)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at czp.a(PG:18188)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:34:34.789  3555  4327 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	... 12 more
08-30 13:34:34.789  3555  4327 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at fal.a(PG:38)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:34:34.789  3555  4327 E HttpOperation: 	... 14 more
,08-30 13:34:34.808  3610  4328 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 13:34:34.808  3610  4326 E BooksSync: Soft error
08-30 13:34:34.808  3610  4326 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:34:34.808  3610  4326 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 13:34:34.809  3610  4326 E BooksSync: Sync error
08-30 13:34:34.809  3610  4326 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 13:34:34.809  3610  4326 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 13:34:34.809  3610  4326 I BooksSync: Finished books sync
,08-30 13:34:34.831   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 459286, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:34:34.856  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:34:34.856  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 13:34:34.856  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:34:34.856  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:34:34.870  3555  4327 E HttpOperation: [getmobileexperiments] Unexpected exception,
08-30 13:34:34.870  3555  4327 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at hec.a(PG:42)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at hee.a(PG:102)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at czr.a(PG:65)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at kka.a(PG:108)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at czp.a(PG:19176)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:34:34.870  3555  4327 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	... 15 more
08-30 13:34:34.870  3555  4327 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at fal.a(PG:38)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:34:34.870  3555  4327 E HttpOperation: 	... 17 more
08-30 13:34:34.870  3555  4327 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 13:34:34.870  3555  4327 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at hec.a(PG:42)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at hee.a(PG:102)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at czr.a(PG:65)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at kka.a(PG:108)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 13:34:34.8,70  3555  4327 E ExperimentLoader: 	... 15 more
08-30 13:34:34.870  3555  4327 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at fal.a(PG:38)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 13:34:34.870  3555  4327 E ExperimentLoader: 	... 17 more
,08-30 13:34:35.010   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 434311, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:34:55.094   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=482717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:35:00.574   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=488197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:35:01.792  1502  2067 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 13:35:04.675  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
08-30 13:35:04.677  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:35:04.691  4046  4331 V GoogleAuthProtoRequest: [349] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:35:04.717  1502  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-30 13:35:04.717  1502  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 13:35:04.717  1502  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:35:04.717  1502  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:35:04.738  4046  4331 W ExperimentUpdateService: [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 13:35:04.739  4046  4331 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 13:35:30.934   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:35:36.014   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=523637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:36:06.667   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=554291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:36:08.087  3024  4335 V KeepSync: Connecting to GoogleApiClient
08-30 13:36:08.087   873  2074 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 13:36:08.145  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:36:08.148  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:36:08.189  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 13:36:08.189  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 13:36:08.190  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:36:08.190  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:36:08.218  1722  4336 V BaseAuthAsyncOperation: access token request failed
,08-30 13:36:08.220  3024  4335 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 13:36:08.289  1502  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 13:36:08.289  1502  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 13:36:08.289  1502  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:36:08.289  1502  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:36:08.309  3024  4335 E KeepSync: IOException
08-30 13:36:08.309  3024  4335 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 13:36:08.309  3024  4335 E KeepSync: 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 13:36:08.309  3024  4335 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 13:36:08.309  3024  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 13:36:08.309  3024  4335 E KeepSync: 	... 10 more
08-30 13:36:08.309  3024  4335 W KeepSync: Sync result 2
,08-30 13:36:08.324   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 555529, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:36:12.000   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=559623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:36:42.827   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:36:44.687  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:36:44.689  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:36:44.726  1502  4302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:36:44.727  1502  4302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 13:36:44.727  1502  4302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:36:44.727  1502  4302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:36:44.756  3555  4339 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 13:36:44.756  3555  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at blb.a(PG:3937)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at czp.a(PG:18188)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:36:44.756  3555  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	... 12 more
08-30 13:36:44.756  3555  4339 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at fal.a(PG:38)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:36:44.756  3555  4339 E HttpOperation: 	... 14 more
,08-30 13:36:44.825  1502  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 13:36:44.825  1502  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 13:36:44.825  1502  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:36:44.825  1502  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:36:44.847  3555  4339 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 13:36:44.847  3555  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jdm.a(PG:82)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jcs.o(PG:406)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jcn.a(PG:1379)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jcs.i(PG:143)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at hec.a(PG:42)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at hee.a(PG:102)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at czr.a(PG:65)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at kka.a(PG:108)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at czp.a(PG:19176)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at czp.a(PG:9081)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at czq.run(PG:1686)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:36:44.847  3555  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jdj.a(PG:4091)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jdj.a(PG:1125)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jdm.a(PG:77)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	... 15 more
08-30 13:36:44.847  3555  4339 E HttpOperation: Caused by: faj: BadAuthentication
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at fal.a(PG:38)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	at jdj.a(PG:4089)
08-30 13:36:44.847  3555  4339 E HttpOperation: 	... 17 more
08-30 13:36:44.847  3555  4339 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 13:36:44.847  3555  4339 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at hec.a(PG:42)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at hee.a(PG:102)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at czr.a(PG:65)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at kka.a(PG:108)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	... 15 more
08-30 13:36:44.847  3555  4339 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at fal.a(PG:38)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 13:36:44.847  3555  4339 E ExperimentLoader: 	... 17 more
,08-30 13:36:45.016   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 591987, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 13:36:48.053   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=595677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:37:18.347   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=625970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:37:23.813   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=631437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:37:54.080   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=661703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:37:59.613   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=667237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:38:29.920   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=697544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:38:35.547   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=703170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:39:04.951  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:39:04.956  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:39:04.972  4046  4352 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:39:04.997  1502  3090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 13:39:04.997  1502  3090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 13:39:04.997  1502  3090 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 13:39:04.997  1502  3090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 13:39:05.015  4046  4352 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 13:39:05.866   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=733490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:39:11.000   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=738623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:39:24.188   873  1296 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
,08-30 13:39:24.189   873  1296 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,08-30 13:39:41.280   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=768903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:39:46.987   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=774611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:40:17.760   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=805384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:40:22.800   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=810423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:40:53.067   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=840690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:40:58.773   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=846397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:41:21.326   873  1303 I PowerManagerService: Waking up from dozing (uid 1000)...
,08-30 13:41:21.327   873   873 V KeyguardServiceDelegate: onStartedWakingUp()
08-30 13:41:21.329   873   893 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,08-30 13:41:21.331  1889  1889 I Keyboard.Facilitator: onFinishInput()
,08-30 13:41:21.342   873   893 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@ad55dfd)
,08-30 13:41:21.348   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,08-30 13:41:21.348   281   281 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a64000
08-30 13:41:21.348   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-30 13:41:21.351  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 13:41:21.352  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-30 13:41:21.359  1964  2104 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,08-30 13:41:21.359  1964  2104 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
08-30 13:41:21.360  1964  2104 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
08-30 13:41:21.360  1964  2089 D BrcmNfcJni: RoutingManager::commitRouting
08-30 13:41:21.361  1964  2104 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
08-30 13:41:21.361   873  1395 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,08-30 13:41:21.365  1902  1902 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,08-30 13:41:21.375  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 13:41:21.376  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 13:41:21.389   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:41:21.395   873  2136 I ActivityManager: Start proc 4371:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,08-30 13:41:21.401   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:41:21.408   873  1314 E native  : do suspend false
,08-30 13:41:21.416   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 13:41:21.442  4371  4371 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm,
,08-30 13:41:21.459   873  2005 I ActivityManager: Killing 3648:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-30 13:41:21.478   377  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 13:41:21.478   377  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-30 13:41:21.478   873   893 I DisplayPowerController: Unblocked screen on after 149 ms
,08-30 13:41:21.479   873   893 V KeyguardServiceDelegate: onScreenTurnedOn()
08-30 13:41:21.480   873   893 I DreamManagerService: Gently waking up from dream.
08-30 13:41:21.481   873  1695 I DreamManagerService: Leaving dreamland.
,08-30 13:41:21.481   873   888 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 13:41:21.597   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-30 13:41:21.598   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-30 13:41:21.599   873  1340 D SurfaceControl: Excessive delay in setPowerMode(): 251ms
,08-30 13:41:22.105  1964  2345 D NfcService: Discovery configuration equal, not updating.
,08-30 13:41:24.439   873  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-30 13:41:29.120   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=876743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:41:34.747   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=882370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:41:42.629   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:41:45.670   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:42:01.440   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:42:10.587   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=918210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:42:21.332  1889  1935 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 13:42:21.333  1889  1935 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 13:42:21.389  1502  1502 I ConfigService: onCreate
,08-30 13:42:26.485  1502  1502 I ConfigService: onDestroy
,08-30 13:42:27.147   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=934770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:42:36.053   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=943677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:42:52.960   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=960583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:43:01.680   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:43:18.240   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=985863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:43:19.671   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:43:21.407  1902  2655 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 13:43:22.318   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 13:43:22.326  1889  1889 I Keyboard.Facilitator: onFinishInput()
,08-30 13:43:22.442   873   882 I art     : Background partial concurrent mark sweep GC freed 64596(4MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.398ms total 117.450ms
,08-30 13:43:22.708   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 13:43:22.880  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 13:43:22.881  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 13:43:22.917  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9668ef6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@47b4770, 16908290=android.view.AbsSavedState$1@47b4770}, android:focusedViewId=100}]}]
,08-30 13:43:22.917  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 13:43:22.917   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
08-30 13:43:22.918  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 13:43:22.918  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 13:43:22.927   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-30 13:43:22.927   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-30 13:43:22.928   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 13:43:23.153   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 13:43:23.156   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 13:43:23.162   873  1340 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
08-30 13:43:23.165   873   893 I DreamManagerService: Entering dreamland.
,08-30 13:43:23.166   873   893 I PowerManagerService: Dozing...
08-30 13:43:23.167   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 13:43:23.208   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 13:43:23.211   873  1314 E native  : do suspend true
,08-30 13:43:23.337   377  1323 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 13:43:23.338   377  1323 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 13:43:27.427   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=995050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:43:43.947   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1011570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:43:52.694   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1020317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:44:14.307   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1041930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:44:22.367  1889  1935 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 13:44:22.367  1889  1935 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 13:44:22.418  1502  1502 I ConfigService: onCreate
,08-30 13:44:23.013   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1050637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:44:27.453  1502  1502 I ConfigService: onDestroy
,08-30 13:44:39.574   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1067197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:44:48.373   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1075997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:45:04.960   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1092584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:45:13.813   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1101437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:45:30.347   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1117970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:45:39.120   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:45:55.680   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1143304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:46:04.400   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1152024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:46:20.960   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1168584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:46:29.680   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1177304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:46:44.800   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1192424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:46:49.920   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1197543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:47:05.066   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1212690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:47:05.216  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 13:47:05.217  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 13:47:05.231  4046  4414 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 13:47:05.296  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-30 13:47:05.296  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-30 13:47:05.296  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 13:47:05.297  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 13:47:05.309  4046  4414 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 13:47:05.310  4046  4414 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 13:47:10.106   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1217730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:47:10.447   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-30 13:47:25.440   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1233064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:47:30.560   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1238183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:47:45.707   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:47:50.827   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1258450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:48:05.920   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1273544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:48:11.413   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1279037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:48:26.613   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1294237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:48:31.666   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1299290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:48:46.773   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1314397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:48:53.520   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1321143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:49:08.640   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1336264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:49:13.800   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1341423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:49:28.907   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1356530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:49:34.067   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1361690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:49:49.173   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1376797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:49:54.400   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1382023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:50:09.493   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:50:14.666   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1402290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:50:29.760   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1417383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:50:34.880   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:50:49.974   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1437597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:50:55.440   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1443064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:51:10.560   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1458184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:51:15.653   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:51:30.774   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1478397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:51:35.894   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1483517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:51:49.867   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1497490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:51:58.054   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1505677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 13:52:11.680   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1519303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 13:52:18.320   873  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1525943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,TIME-OUT KILL (timeout was 1400000ms),08-30 13:52:24.763  4431  4431 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 13:52:24.768  4431  4431 D AndroidRuntime: CheckJNI is OFF
08-30 13:52:24.804  4431  4431 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 13:52:24.844  4431  4431 I Radio-JNI: register_android_hardware_Radio DONE
08-30 13:52:24.864  4431  4431 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 13:52:24.880   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-30 13:52:24.881   873   886 I ActivityManager: Killing 3799:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-30 13:52:24.979   873   883 D GraphicsStats: Buffer count: 2
08-30 13:52:24.980   873  1694 I WindowState: WIN DEATH: Window{85e08b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 13:52:24.980   873  1315 D WifiService: Client connection lost with reason: 4
08-30 13:52:25.023   873   896 W PackageSettings: Skipping PackageSetting{518928f com.example.hello/10273} due to missing metadata
08-30 13:52:25.050   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-30 13:52:25.050   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 13:52:25.050   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-30 13:52:25.050   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 13:52:25.050   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:52:25.050   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:52:25.050   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 13:52:25.050   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 13:52:25.051   873   886 I ActivityManager:   Force finishing activity ActivityRecord{77291f8 u0 com.test.thalitest/.MainActivity t2}
08-30 13:52:25.057   873   896 I art     : Starting a blocking GC Explicit
08-30 13:52:25.057   873  1695 W ActivityManager: Spurious death for ProcessRecord{2d22a52 0:com.test.thalitest/u0a0}, curProc for 3799: null
08-30 13:52:25.128   873   896 I art     : Explicit concurrent mark sweep GC freed 24822(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 29MB/43MB, paused 1.072ms total 70.262ms
08-30 13:52:25.153   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 13:52:25.157  4431  4431 I art     : System.exit called, status: 0
08-30 13:52:25.157  4431  4431 I AndroidRuntime: VM exiting with result code 0.
08-30 13:52:25.213   873   896 I ActivityManager: Start proc 4444:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-30 13:52:25.213   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-30 13:52:25.226   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-30 13:52:25.240  4182  4182 D BluetoothMapAppObserver: onReceive
08-30 13:52:25.240  4182  4182 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 13:52:25.248   873  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 13:52:25.249  3671  3671 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 13:52:25.258  1902  2261 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 13:52:25.261  1889  1889 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 13:52:25.268  1889  4460 I Keyboard.Facilitator.DecoderInitializer: run()
08-30 13:52:25.272  1889  4460 I Decoder : createOrResetDecoder
08-30 13:52:25.296   873  1695 I ActivityManager: Start proc 4461:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-30 13:52:25.324  1977  1977 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-30 13:52:25.334   873  1312 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-30 13:52:25.337   873  1696 I ActivityManager: Killing 3723:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-30 13:52:25.338  1502  1502 I ConfigService: onCreate
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 13:52:25.350  1502  4473 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 13:52:25.350  1502  4473 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 13:52:25.352   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 13:52:25.352  1502  4473 W SQLiteOpenHelper: Opened config.db in read-only mode
08-30 13:52:25.357   873  2135 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3799 uid 10000
08-30 13:52:25.358  1889  1889 I Keyboard.Facilitator: onFinishInput()
08-30 13:52:25.367  4461  4461 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-30 13:52:25.552   873  1696 E libprocessgroup: failed to kill 1 processes for processgroup 3723
08-30 13:52:25.571   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 13:52:25.574   873   885 E PackageManager: Failed to write settings, restoring backup
08-30 13:52:25.574   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 13:52:25.574   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 13:52:25.574   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 13:52:25.574   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 13:52:25.574   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 13:52:25.574   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 13:52:25.574   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:52:25.574   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 13:52:25.579  1992  2078 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 13:52:25.580   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-30 13:52:25.580   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 13:52:25.580   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:52:25.580   873   886 E DropBoxManagerService: 	... 13 more
08-30 13:52:25.594  1889  4460 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-30 13:52:25.622   873  1395 I ActivityManager: Start proc 4474:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-30 13:52:25.623  1992  2078 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 13:52:25.623  1992  2078 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1992
08-30 13:52:25.623  1992  2078 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 13:52:25.623  1992  2078 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 13:52:25.625   873  1695 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 13:52:25.627   873  4483 E DropBoxManagerService: Can't write: system_app_crash
08-30 13:52:25.627   873  4483 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 13:52:25.627   873  4483 E DropBoxManagerService: 	... 5 more
08-30 13:52:25.631  1992  2078 I Process : Sending signal. PID: 1992 SIG: 9
08-30 13:52:25.647  1889  4460 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 13:52:25.649  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 13:52:25.649  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 13:52:25.651  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 13:52:25.651  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 13:52:25.652  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 13:52:25.652  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 13:52:25.653  1889  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 13:52:25.653  1889  4460 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 13:52:25.653  1889  4460 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 13:52:25.653  1889  4460 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 13:52:25.653  1889  4460 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 13:52:25.653  1889  4460 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon

```
