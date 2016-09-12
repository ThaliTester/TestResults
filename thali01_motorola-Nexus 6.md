#### Test 846390992661b80_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-12 09:34:56.067   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-12 09:34:56.838  3837  3837 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 09:34:56.842  3837  3837 D AndroidRuntime: CheckJNI is OFF
09-12 09:34:56.859  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 09:34:56.868  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 09:34:56.870  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 09:34:56.880  3837  3837 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 09:34:56.912  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 09:34:56.913  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:34:56.913  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:34:56.913  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 09:34:56.916  3837  3837 I Radio-JNI: register_android_hardware_Radio DONE
09-12 09:34:56.934  3837  3837 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 09:34:56.939   873  1980 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 09:34:56.940  3484  3484 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 09:34:56.940  3484  3484 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 09:34:56.940  3484  3484 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 09:34:56.967  3837  3837 D AndroidRuntime: Shutting down VM
09-12 09:34:56.967  2012  2023 W SearchService: Abort, client detached.
09-12 09:34:56.972  2012  2332 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@190cbd1
09-12 09:34:56.972  2012  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 09:34:56.979  2012  2012 I HotwordDetector: Closing mic
09-12 09:34:56.986   873  2339 I ActivityManager: Start proc 3846:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 09:34:57.026   375  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 09:34:57.027   375  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 09:34:57.030   375  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 09:34:57.031  2012  2354 I MicroRecognitionRnrImpl: Detection finished
09-12 09:34:57.032  2012  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 09:34:57.080  3846  3846 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 09:34:57.108  3846  3846 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 09:34:57.114  3846  3846 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9549-9551)
09-12 09:34:57.114  3846  3846 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 09:34:57.126  3846  3846 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8cf7edc}
09-12 09:34:57.127  3846  3846 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 09:34:57.127  3846  3846 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 09:34:57.133  3846  3846 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 09:34:57.134  3846  3846 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 09:34:57.150  3846  3846 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 09:34:57.159  3846  3846 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 09:34:57.159  3846  3846 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 09:34:57.159  3846  3846 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 09:34:57.159  3846  3846 I Adreno  : Build Date                       : 10/20/15
09-12 09:34:57.159  3846  3846 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 09:34:57.159  3846  3846 I Adreno  : Local Branch                     : M14
09-12 09:34:57.159  3846  3846 I Adreno  : Remote Branch                    : 
09-12 09:34:57.159  3846  3846 I Adreno  : Remote Branch                    : 
09-12 09:34:57.159  3846  3846 I Adreno  : Reconstruct Branch               : 
,09-12 09:34:57.215   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@772a89b:true
,09-12 09:34:57.274  3846  3846 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 09:34:57.288  3846  3846 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 09:34:57.363  3846  3884 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 09:34:57.372  3846  3871 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 09:34:57.393  3846  3884 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 09:34:57.486   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +515ms
,09-12 09:34:57.489  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-12 09:34:57.567  3846  3846 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3846
,09-12 09:34:57.769  3846  3846 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 09:34:57.799   873  1981 I ActivityManager: Killing 3541:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 09:34:57.843   873  1981 I ActivityManager: Killing 3212:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,09-12 09:34:57.954  3846  3886 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1682179792
,09-12 09:34:57.959  3846  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 09:34:57.959  3846  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 09:34:57.959  3846  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 09:34:57.959  3846  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 09:34:57.959  3846  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 09:34:57.959  3846  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bed9a0 added. We now have 1 listener(s)
,09-12 09:34:57.962  3846  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 09:34:57.963  3846  3886 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,09-12 09:34:57.964  3846  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:34:57.964  3846  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 09:34:57.968  3846  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e585ff added. We now have 1 listener(s)
,09-12 09:34:57.968  3846  3886 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:34:57.976   873  1305 D WifiService: New client listening to asynchronous messages
,09-12 09:34:57.978  3846  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 09:34:57.979  3846  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 09:34:57.982  3846  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 09:34:57.982  3846  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-12 09:34:57.983  3846  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 09:34:57.987  3846  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:34:57.987  3846  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 09:34:57.994  3846  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:34:57.994  3846  3886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:34:57.994  3846  3886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 09:34:57.994  3846  3886 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 09:34:57.997  3846  3886 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 09:34:58.130  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:34:58.135  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:34:58.137  3846  3846 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 09:34:58.787  3846  3894 W jxcore-log: Initializing JXcore engine
,09-12 09:34:58.787  3846  3894 W jxcore-log: JXcore engine is ready
,09-12 09:34:58.825  3894  3894 W Thread-341: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 09:34:58.825  3894  3894 W Thread-341: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13351]" dev="sockfs" ino=13351 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 09:34:58.825  3894  3894 W Thread-341: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 09:34:58.825  3894  3894 W Thread-341: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25139]" dev="sockfs" ino=25139 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 09:34:58.840  3846  3894 W jxcore-log: Starting JXcore engine
,09-12 09:34:58.918  3846  3894 W jxcore-log: Platform android
09-12 09:34:58.918  3846  3894 W jxcore-log: 
,09-12 09:34:58.918  3846  3894 W jxcore-log: Process ARCH arm
09-12 09:34:58.918  3846  3894 W jxcore-log: 
,09-12 09:34:59.201  3846  3894 I jxcore-log: JXcore Cordova bridge is ready!
09-12 09:34:59.201  3846  3894 I jxcore-log: 
,09-12 09:34:59.204  3846  3894 W jxcore-log: JXcore engine is started
,09-12 09:34:59.213  3846  3886 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 09:34:59.219  3846  3846 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 09:34:59.351   873  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 09:35:03.292  3591  3902 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 09:35:03.325  3591  3903 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 09:35:03.337  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:03.342  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:03.378  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 09:35:03.378  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:35:03.378  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:03.378  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:03.422  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:03.427  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:03.454  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 09:35:03.454  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:35:03.454  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:35:03.454  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:03.481  3591  3903 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:35:03.481  3591  3902 E BooksSync: Soft error
09-12 09:35:03.481  3591  3902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:35:03.481  3591  3902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:35:03.482  3591  3902 E BooksSync: Sync error
09-12 09:35:03.482  3591  3902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:35:03.482  3591  3902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:35:03.482  3591  3902 I BooksSync: Finished books sync
,09-12 09:35:03.489   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:35:09.080  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 09:35:09.080  3846  3894 I jxcore-log: 
,09-12 09:35:09.083  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 09:35:09.083  3846  3894 I jxcore-log: 
,09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:09.095  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:09.103  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:09.109  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 09:35:09.109  3846  3894 I jxcore-log: 
,09-12 09:35:09.116  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 09:35:09.116  3846  3894 I jxcore-log: 
,09-12 09:35:09.631  3846  3894 D executeNativeTests: Running unit tests
,09-12 09:35:09.689  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 09:35:09.689  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 added. We now have 2 listener(s)
09-12 09:35:09.690  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 09:35:09.690  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 09:35:09.690  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:09.690  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:09.690  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 added. We now have 2 listener(s)
09-12 09:35:09.690  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:09.691  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 09:35:09.693  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:09.702  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:09.710  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:09.712  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 09:35:09.718  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.721  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 09:35:09.722  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 09:35:09.722  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 09:35:09.725  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.726  3846  3894 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 09:35:09.726  3846  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 09:35:09.726  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 09:35:09.726  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 09:35:09.726  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 09:35:09.727  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:09.727  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:09.727  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:09.728  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:09.728  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:09.728  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:09.728  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 09:35:09.728  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 removed from the list
,09-12 09:35:09.728  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.728  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 removed from the list
,09-12 09:35:09.728  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:09.728  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 09:35:09.730  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:09.731  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.733  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 09:35:09.734  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:09.734  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:09.734  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:09.741  3846  3894 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 09:35:09.742  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:09.742  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:09.743  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:09.743  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:09.743  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.743  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.743  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:09.743  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.743  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:09.743  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:09.744  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.744  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.744  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:09.744  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.747  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:09.748  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:09.748  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:09.748  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:09.767  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 09:35:09.767  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 09:35:09.768  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 09:35:09.768  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 09:35:09.768  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 09:35:09.768  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 09:35:09.769  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-12 09:35:09.769  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 09:35:09.769  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 09:35:09.769  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 09:35:09.770  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 09:35:09.770  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 09:35:09.770  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 09:35:09.770  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 09:35:09.771  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 09:35:09.771  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 09:35:09.771  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 09:35:09.771  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 09:35:09.772  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 09:35:09.772  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-12 09:35:09.772  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 09:35:09.773  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 09:35:09.773  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-12 09:35:09.773  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 09:35:09.773  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 09:35:09.773  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 09:35:09.774  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 09:35:09.774  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 09:35:09.774  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 09:35:09.774  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 09:35:09.775  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-12 09:35:09.775  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:09.775  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:09.775  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:09.776  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:09.776  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.776  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.776  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:09.776  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.776  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:09.776  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:09.776  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.776  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.777  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.777  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.778  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 09:35:09.778  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:09.778  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.778  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:09.778  3846  3894 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 09:35:09.781  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:09.788  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 09:35:09.793  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.793  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 09:35:09.793  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:09.793  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 09:35:09.794  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 09:35:09.794  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:09.794  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 09:35:09.796  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:09.800  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 09:35:09.800  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 09:35:09.801  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.816  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 09:35:09.821  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 09:35:09.823  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 09:35:09.830  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 09:35:09.835  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 09:35:09.836  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 09:35:09.836  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 09:35:09.837  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 09:35:09.839  3846  3894 D BluetoothAdapter: STATE_ON
09-12 09:35:09.847  2690  2702 D BtGatt.GattService: registerClient() - UUID=44fb4f84-dfe3-477e-b8f2-8b845b441f01
09-12 09:35:09.848  2690  2759 D BtGatt.GattService: onClientRegistered() - UUID=44fb4f84-dfe3-477e-b8f2-8b845b441f01, clientIf=5
09-12 09:35:09.849  3846  3857 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 09:35:09.850  2690  2894 D BtGatt.GattService: start scan with filters
,09-12 09:35:09.857  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 09:35:09.857  2690  2768 D BtGatt.ScanManager: handling starting scan
,09-12 09:35:09.857  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 09:35:09.858  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 09:35:09.858  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 09:35:09.860  2690  2768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:09.865  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 09:35:09.869  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:09.870  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 09:35:09.871  2690  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 09:35:09.871  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:09.872  2690  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 09:35:09.878  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 09:35:09.884  3846  3894 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 09:35:09.888  2690  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 09:35:09.888  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:09.888  3846  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 09:35:09.888  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:09.889  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:09.889  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 09:35:09.889  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.889  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 09:35:09.889  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 09:35:09.889  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 09:35:09.889  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 09:35:09.889  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 09:35:09.889  2690  2768 D BtGatt.ScanManager: Starting BLE batch scan
09-12 09:35:09.890  2690  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 09:35:09.890  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 09:35:09.890  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 09:35:09.891  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:09.892  2690  2702 D BtGatt.GattService: stopScan() - queue size =1
,09-12 09:35:09.893  2690  2894 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 09:35:09.893  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 09:35:09.893  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 09:35:09.894  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 09:35:09.894  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 09:35:09.894  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 09:35:09.895  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 09:35:09.895  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 09:35:09.895  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 09:35:09.896  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 09:35:09.897  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:09.898  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:09.898  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 09:35:09.898  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:09.898  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:09.898  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.898  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:09.899  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:09.899  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.899  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:09.899  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:09.899  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.900  3846  3894 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 09:35:09.902  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:09.913  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 09:35:09.916  2690  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 09:35:09.916  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:09.917  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.918  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 09:35:09.921  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:09.921  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 09:35:09.921  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 09:35:09.922  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:09.921  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.922  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 09:35:09.923  2690  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 09:35:09.923  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:09.925  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 09:35:09.925  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 09:35:09.926  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.930  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 09:35:09.931  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 09:35:09.932  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 09:35:09.935  2690  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 09:35:09.935  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:09.935  2690  2768 D BtGatt.ScanManager: stopping BLe Batch
,09-12 09:35:09.935  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 09:35:09.935  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 09:35:09.936  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 09:35:09.937  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:09.941  2690  2707 D BtGatt.GattService: registerClient() - UUID=61ef6b7f-e750-4bb3-9505-1f8a82d68c10
,09-12 09:35:09.941  2690  2759 D BtGatt.GattService: onClientRegistered() - UUID=61ef6b7f-e750-4bb3-9505-1f8a82d68c10, clientIf=5
,09-12 09:35:09.942  3846  3858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 09:35:09.942  2690  2894 D BtGatt.GattService: start scan with filters
,09-12 09:35:09.945  2690  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 09:35:09.945  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:09.946  2690  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 09:35:09.946  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 09:35:09.946  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 09:35:09.946  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 09:35:09.946  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 09:35:09.949  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:09.950  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 09:35:09.950  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 09:35:09.952  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 09:35:09.956  3846  3894 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 09:35:09.957  2690  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 09:35:09.957  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:09.959  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:09.959  3846  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 09:35:09.959  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:09.959  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 09:35:09.959  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.959  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 09:35:09.959  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 09:35:09.959  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 09:35:09.960  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 09:35:09.960  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 09:35:09.960  2690  2768 D BtGatt.ScanManager: handling starting scan
09-12 09:35:09.960  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 09:35:09.960  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 09:35:09.961  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:09.962  2690  2707 D BtGatt.GattService: stopScan() - queue size =1
,09-12 09:35:09.963  2690  2894 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 09:35:09.964  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 09:35:09.964  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 09:35:09.964  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 09:35:09.964  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 09:35:09.964  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 09:35:09.966  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:09.966  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 09:35:09.966  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 09:35:09.966  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 09:35:09.967  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 09:35:09.968  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:09.968  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 09:35:09.968  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:09.968  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:09.968  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.968  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:09.969  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:09.969  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.969  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:09.969  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:09.969  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:09.969  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:09.970  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:09.970  2690  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 09:35:09.970  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:09.971  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:09.971  2690  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 09:35:09.971  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:09.971  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:09.971  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:09.972  3846  3894 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 09:35:09.975  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:09.980  2690  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 09:35:09.981  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:09.981  2690  2768 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 09:35:09.981  2690  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:09.981  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:09.985  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:09.986  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 09:35:09.987  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 09:35:09.987  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 09:35:09.987  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 09:35:09.987  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:09.987  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 09:35:09.988  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.991  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:09.993  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 09:35:09.993  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 09:35:09.998  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 09:35:10.000  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 09:35:10.000  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 09:35:10.001  2690  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
09-12 09:35:10.001  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:10.005  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 09:35:10.006  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 09:35:10.006  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 09:35:10.006  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:10.009  2690  2702 D BtGatt.GattService: registerClient() - UUID=10a6e990-5d3e-4193-95d6-c9733823a960
,09-12 09:35:10.010  2690  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 09:35:10.010  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.010  2690  2759 D BtGatt.GattService: onClientRegistered() - UUID=10a6e990-5d3e-4193-95d6-c9733823a960, clientIf=5
09-12 09:35:10.010  3846  3858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 09:35:10.011  2690  2894 D BtGatt.GattService: start scan with filters
09-12 09:35:10.014  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 09:35:10.014  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 09:35:10.014  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 09:35:10.014  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 09:35:10.017  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:10.017  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 09:35:10.018  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:10.020  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 09:35:10.022  2690  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 09:35:10.022  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:10.023  2690  2768 D BtGatt.ScanManager: stopping BLe Batch
,09-12 09:35:10.023  3846  3894 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 09:35:10.023  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-12 09:35:10.024  3846  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 09:35:10.024  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.024  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 09:35:10.024  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.024  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 09:35:10.024  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 09:35:10.024  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,09-12 09:35:10.024  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 09:35:10.024  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 09:35:10.024  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 09:35:10.024  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 09:35:10.028  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:10.029  2690  2894 D BtGatt.GattService: stopScan() - queue size =0
,09-12 09:35:10.030  2690  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 09:35:10.030  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 09:35:10.030  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 09:35:10.030  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,09-12 09:35:10.030  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 09:35:10.031  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,09-12 09:35:10.032  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 09:35:10.032  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,09-12 09:35:10.032  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 09:35:10.032  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 09:35:10.033  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:10.034  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:10.034  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.034  3846  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 09:35:10.034  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:10.034  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.034  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:10.034  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 09:35:10.034  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.035  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.035  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 09:35:10.035  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.035  2690  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 09:35:10.035  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.035  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.035  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.035  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.035  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.035  2690  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 09:35:10.036  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.036  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.038  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.038  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.038  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.038  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:10.039  3846  3894 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 09:35:10.040  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.040  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.040  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.041  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.041  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.041  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.041  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.041  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.041  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.041  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.041  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.041  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.042  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.042  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.044  2690  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 09:35:10.045  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:10.045  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.045  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 09:35:10.045  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.045  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:10.047  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 09:35:10.047  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:10.047  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.048  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.050  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:10.050  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.050  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.050  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
,09-12 09:35:10.050  2690  2768 D BtGatt.ScanManager: handling starting scan
09-12 09:35:10.050  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.050  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.050  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.051  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.051  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.051  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.051  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.052  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.053  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 09:35:10.053  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.053  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.053  3846  3894 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 09:35:10.054  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:10.054  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.054  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.054  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.054  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.054  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.054  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
,09-12 09:35:10.054  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.055  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.055  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.055  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.055  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.055  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.055  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.056  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.056  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 09:35:10.056  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.056  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.057  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-12 09:35:10.057  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:10.057  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.057  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:10.057  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.057  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.057  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.058  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.058  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.058  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.058  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.058  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.058  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.058  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.058  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.060  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.060  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.060  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.060  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.060  2690  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 09:35:10.061  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.061  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-12 09:35:10.061  2690  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 09:35:10.061  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 09:35:10.061  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 09:35:10.061  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 09:35:10.061  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 09:35:10.061  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 09:35:10.062  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.062  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 09:35:10.062  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.062  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:10.062  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.062  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.062  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
,09-12 09:35:10.062  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.063  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.063  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.063  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.063  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.063  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.063  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.064  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.064  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-12 09:35:10.064  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.064  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.065  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 09:35:10.065  3846  3894 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 09:35:10.065  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 09:35:10.069  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 09:35:10.069  3846  3894 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 09:35:10.070  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-12 09:35:10.071  2690  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 09:35:10.071  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:10.071  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 09:35:10.072  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-12 09:35:10.072  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 09:35:10.072  2690  2768 D BtGatt.ScanManager: Starting BLE batch scan
09-12 09:35:10.072  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
09-12 09:35:10.072  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 09:35:10.072  2690  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 09:35:10.072  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
09-12 09:35:10.072  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 09:35:10.073  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-12 09:35:10.073  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 09:35:10.073  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 09:35:10.073  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 09:35:10.073  3846  3894 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-12 09:35:10.073  3846  3894 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 09:35:10.073  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 09:35:10.073  3846  3894 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 09:35:10.074  3846  3894 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 09:35:10.074  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 09:35:10.074  3846  3894 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 09:35:10.074  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 09:35:10.077  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 09:35:10.078  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-12 09:35:10.078  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 09:35:10.079  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 09:35:10.079  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-12 09:35:10.079  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 09:35:10.079  3846  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 09:35:10.080  3846  3894 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 09:35:10.080  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:10.081  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.081  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.081  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:10.081  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.081  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.081  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 09:35:10.082  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.082  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.082  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.083  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.083  3846  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 405)
,09-12 09:35:10.083  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.083  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.083  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.083  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.084  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.084  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 09:35:10.084  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.084  3846  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 405
09-12 09:35:10.084  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:10.085  3846  3894 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 09:35:10.085  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.085  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 09:35:10.086  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.086  3846  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 09:35:10.086  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:10.086  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.086  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.086  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
,09-12 09:35:10.086  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.086  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.086  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 09:35:10.086  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.086  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.086  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.086  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.087  2690  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 09:35:10.087  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.087  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.087  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.087  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.088  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.088  3846  3894 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 09:35:10.088  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:10.089  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.089  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.089  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.089  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.089  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.090  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.090  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.090  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.090  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.090  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.090  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.090  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.090  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.091  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 09:35:10.091  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.091  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.091  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.092  3846  3894 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 09:35:10.092  3846  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 09:35:10.092  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 09:35:10.092  3846  3894 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 09:35:10.092  3846  3894 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 09:35:10.092  3846  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 09:35:10.093  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 09:35:10.093  3846  3894 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 09:35:10.093  3846  3894 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 09:35:10.093  3846  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 09:35:10.093  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 09:35:10.093  3846  3894 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 09:35:10.093  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.093  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.093  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:10.094  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.094  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.094  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.094  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.094  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.094  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.094  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.094  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.094  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.094  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.094  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.095  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.095  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.095  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.095  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.096  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.096  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.096  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.096  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.096  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.096  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.097  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.097  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.097  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.097  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.097  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.097  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.097  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.097  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.097  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.097  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.097  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.097  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:10.097  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.098  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.098  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.098  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.098  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.098  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.098  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.098  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.098  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.098  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.098  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.099  2690  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 09:35:10.099  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.099  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.099  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.099  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.100  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.101  3846  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 09:35:10.101  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:10.102  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 09:35:10.103  3846  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 09:35:10.103  3846  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 09:35:10.103  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 09:35:10.103  3846  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 09:35:10.103  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 09:35:10.103  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.104  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 09:35:10.104  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 09:35:10.104  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 09:35:10.104  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.104  3846  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 09:35:10.104  3846  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 09:35:10.104  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
,09-12 09:35:10.104  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.104  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 09:35:10.104  3846  3911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 09:35:10.104  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 09:35:10.104  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 09:35:10.104  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.104  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.105  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:10.105  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 09:35:10.105  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:10.106  2690  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 09:35:10.106  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:10.106  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.106  2690  2768 D BtGatt.ScanManager: stopping BLe Batch
09-12 09:35:10.106  3846  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 09:35:10.106  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:10.106  3846  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 09:35:10.106  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.106  3846  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 09:35:10.106  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.106  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.106  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.106  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.107  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.107  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.107  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.107  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.107  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.107  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.107  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.107  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.107  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.108  3846  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 09:35:10.108  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.108  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.108  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.108  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.109  3846  3894 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 09:35:10.109  3846  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 09:35:10.109  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 09:35:10.111  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 09:35:10.111  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.111  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.111  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.111  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.111  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.111  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.112  2690  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 09:35:10.111  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.112  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.112  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.112  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.112  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.112  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.112  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.112  2690  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 09:35:10.112  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.113  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.114  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.114  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.114  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.114  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.117  2690  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 09:35:10.117  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:10.117  2690  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:10.117  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.118  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.118  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.118  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.118  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.118  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
09-12 09:35:10.118  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.118  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
,09-12 09:35:10.118  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.118  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:10.118  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.118  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.118  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.119  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.119  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:10.119  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.119  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.120  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:10.120  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:10.120  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:10.120  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:10.120  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.120  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.120  3846  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c80870 not in the list
,09-12 09:35:10.120  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:10.121  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.121  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:10.121  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.121  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:10.121  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:10.121  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:10.122  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:10.122  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 09:35:10.122  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:10.122  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95de7e9 not in the list
09-12 09:35:10.123  3846  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 09:35:10.123  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 09:35:10.123  3846  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-12 09:35:10.123  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 09:35:10.123  3846  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 09:35:10.123  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 09:35:10.125  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 09:35:10.125  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 09:35:10.125  3846  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 09:35:10.125  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-12 09:35:10.125  3846  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-12 09:35:10.125  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-12 09:35:10.126  3846  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 09:35:10.126  3846  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 09:35:10.126  3846  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 09:35:10.126  3846  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-12 09:35:10.127  3846  3894 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 09:35:10.127  3846  3894 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 09:35:10.127  3846  3894 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 09:35:10.127  3846  3894 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-12 09:35:10.128  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:10.128  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fa2c6a3 added. We now have 2 listener(s)
09-12 09:35:10.128  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:10.130  3846  3894 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 09:35:10.130   873  1933 D WifiService: setWifiEnabled: true pid=3846, uid=10000
09-12 09:35:10.130   873  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 09:35:10.131  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:10.131  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e66da0 added. We now have 3 listener(s)
09-12 09:35:10.131  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:10.141  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:10.141  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2439d59 added. We now have 4 listener(s)
09-12 09:35:10.141  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:10.145  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:10.146  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c914d1e added. We now have 5 listener(s)
09-12 09:35:10.146  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:10.150   873  1924 D WifiService: setWifiEnabled: false pid=3846, uid=10000
,09-12 09:35:10.150   873  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 09:35:10.159  2690  2749 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 09:35:10.159  2690  2749 D BluetoothAdapterProperties: Setting state to 13
09-12 09:35:10.159  2690  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 09:35:10.160  2690  2749 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 09:35:10.162  2690  2690 D BluetoothMapService: onReceive
,09-12 09:35:10.162  2690  2690 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 09:35:10.162  2690  2749 I BluetoothAdapterState: Entering PendingCommandState
09-12 09:35:10.162  2690  2690 D BluetoothMapService: STATE_TURNING_OFF
09-12 09:35:10.162  2690  2690 D BluetoothMapService: MAP Service closeService in
09-12 09:35:10.162  2690  2690 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 09:35:10.162  2690  2690 D ObexServerSockets0: shutdown(block = true)
09-12 09:35:10.163  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 09:35:10.163  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 09:35:10.163  2690  2883 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 09:35:10.164  2690  2902 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 09:35:10.164  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 09:35:10.165  2690  2903 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 09:35:10.166  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:10.166   873  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 09:35:10.166   873  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 09:35:10.166   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 09:35:10.166  2690  2690 I BtOppRfcommListener: stopping Accept Thread
09-12 09:35:10.166   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 09:35:10.167  2690  3418 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 09:35:10.167  2690  3418 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 09:35:10.172  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:10.172  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:10.173  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:10.173  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:10.173  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 09:35:10.176  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.176   873  1868 D DhcpClient: Clearing IP address
09-12 09:35:10.176   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 09:35:10.179  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.179   371   872 D CommandListener: Setting iface cfg
09-12 09:35:10.181   873  1884 D DhcpClient: Receive thread stopped
09-12 09:35:10.181  1511  2442 V NativeCrypto: Read error: ssl=0xaec58600: I/O error during system call, Connection timed out
09-12 09:35:10.184  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:10.184  1511  2442 V NativeCrypto: SSL shutdown failed: ssl=0xaec58600: I/O error during system call, Broken pipe
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:10.184  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 09:35:10.185  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:10.185  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:10.188   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-12 09:35:10.188  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.188   873  1858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-12 09:35:10.188   873   886 I ActivityManager: Start proc 3914:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 09:35:10.189  2690  2759 D BluetoothAdapterProperties: Scan Mode:20
09-12 09:35:10.190  2690  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 09:35:10.190   873  1858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 09:35:10.191   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-12 09:35:10.191   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-12 09:35:10.192   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 09:35:10.193  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.196  2690  2690 D HeadsetService: Received stop request...Stopping profile...
09-12 09:35:10.198  1941  2059 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:10.198   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 09:35:10.198  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.198   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:10.198   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:10.199  1357  1370 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:10.200  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:10.200  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.201  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.201  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:10.201  2690  2690 D A2dpService: Received stop request...Stopping profile...
09-12 09:35:10.201  2690  2897 D A2dpStateMachine: Exit Disconnected: -1
09-12 09:35:10.203   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 09:35:10.204  2690  2690 D HidService: Received stop request...Stopping profile...
09-12 09:35:10.204  2690  2690 D HidService: Stopping Bluetooth HidService
09-12 09:35:10.205  1357  1357 D HeadsetProfile: Bluetooth service disconnected
09-12 09:35:10.205  1357  1357 D BluetoothA2dp: Proxy object disconnected
,09-12 09:35:10.205  1357  1357 D BluetoothInputDevice: Proxy object disconnected
09-12 09:35:10.205  1357  1357 D HidProfile: Bluetooth service disconnected
09-12 09:35:10.207   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 09:35:10.207   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 09:35:10.209   873  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 09:35:10.210   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 09:35:10.214   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-12 09:35:10.216   371   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 09:35:10.217   394   394 E Parcel  : Reading a NULL string not supported here.
09-12 09:35:10.219  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 09:35:10.219  2690  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 09:35:10.219  2690  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 09:35:10.219  2690  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 09:35:10.219  2690  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:10.220  2690  2759 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 09:35:10.221  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 09:35:10.221  2690  2690 D HealthService: Received stop request...Stopping profile...
09-12 09:35:10.229  2690  2690 D PanService: Received stop request...Stopping profile...
09-12 09:35:10.230   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 09:35:10.230  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 09:35:10.230  1357  1357 D PanProfile: Bluetooth service disconnected
09-12 09:35:10.232  2690  2690 D BluetoothMapService: Received stop request...Stopping profile...
09-12 09:35:10.232  2690  2690 D BluetoothMapService: stop()
09-12 09:35:10.232  2690  2690 D BluetoothMapAppObserver: deinitObservers()
09-12 09:35:10.232  2690  2690 D BluetoothMapAppObserver: removeReceiver()
09-12 09:35:10.234  1357  1357 D BluetoothMap: Proxy object disconnected
,09-12 09:35:10.234  1357  1357 D MapProfile: Bluetooth service disconnected
09-12 09:35:10.234  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:10.234  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.234  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.235  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:10.235  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:10.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:10.235  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:10.235  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:10.236  2690  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 09:35:10.236  2690  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:10.236  2690  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:10.236  2690  2876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 09:35:10.236  2690  2876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 09:35:10.236  2690  2876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 09:35:10.236  2690  2876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 09:35:10.236  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:10.236  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.237  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.237  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:10.237  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 09:35:10.237  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 09:35:10.237  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:10.237  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:10.237  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:10.237  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.237  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.237  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:10.238  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 09:35:10.238  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:10.238  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 09:35:10.238  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 09:35:10.238  2690  2690 V BluetoothAdapterState: isTurningOff()=true
,09-12 09:35:10.238  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.238  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.239  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:10.239  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 09:35:10.238  2690  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 09:35:10.239  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 09:35:10.240  2690  2690 D BluetoothMapService: MAP Service closeService in
09-12 09:35:10.240  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:10.240  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.240  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.240  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:10.240  2690  2759 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 09:35:10.240  2690  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 09:35:10.240  2690  2749 D BluetoothAdapterProperties: Setting state to 15
09-12 09:35:10.240  2690  2690 D BluetoothMapService: cleanup()
09-12 09:35:10.240  2690  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 09:35:10.240  2690  2690 D BluetoothMapService: MAP Service closeService in
09-12 09:35:10.241  2690  2749 I BluetoothAdapterState: Entering BleOnState
09-12 09:35:10.241   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:10.241  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 09:35:10.241   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:10.241  1357  1382 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 09:35:10.242  1357  1971 D BluetoothPan: onBluetoothStateChange on: false
09-12 09:35:10.242   873  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 09:35:10.242  1357  1370 D BluetoothMap: onBluetoothStateChange: up=false
09-12 09:35:10.243  1941  2059 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:10.243   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:10.243   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 09:35:10.243  1357  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:10.244  1357  1971 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 09:35:10.244  2690  2749 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 09:35:10.244  2690  2749 D BluetoothAdapterProperties: Setting state to 16
09-12 09:35:10.244  2690  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 09:35:10.245  2690  2749 D BluetoothAdapterProperties: onBleDisable
09-12 09:35:10.245  2690  2749 I BluetoothAdapterState: Entering PendingCommandState
09-12 09:35:10.245  2690  2751 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 09:35:10.246  2690  2876 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 09:35:10.246  2690  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:10.246  3846  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 405)
09-12 09:35:10.246  2690  2759 D BluetoothAdapterProperties: Scan Mode:20
09-12 09:35:10.247  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.248  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.249  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.250  2096  2349 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 09:35:10.251  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.269   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 09:35:10.281  3914  3914 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-12 09:35:10.290  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 09:35:10.294   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 09:35:10.296  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 09:35:10.296   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 09:35:10.297   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 09:35:10.299   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fd427:true
,09-12 09:35:10.304   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 09:35:10.307  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.308  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:10.317   873  1980 I ActivityManager: Start proc 3933:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 09:35:10.351  3914  3914 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 09:35:10.354  3914  3914 D BluetoothMap: Create BluetoothMap proxy object
,09-12 09:35:10.360  3933  3933 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 09:35:10.360  3914  3914 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 09:35:10.377  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 09:35:10.381   873  1674 I ActivityManager: Killing 3466:android.process.acore/u0a5 (adj 15): empty #17
,09-12 09:35:10.389   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 09:35:10.391   873  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 09:35:10.391   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 09:35:10.448  2690  2759 I bt_hci  : shut_down
,09-12 09:35:10.449  2690  2769 D bt_hwcfg: hw_epilog_process
,09-12 09:35:10.450  2690  2769 I bt_vendor: low_power_mode_cb
,09-12 09:35:10.474  2690  2769 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 09:35:10.475  2690  2769 I bt_vendor: epilog_cb
09-12 09:35:10.475  2690  2769 I bt_hci  : epilog_finished_callback
,09-12 09:35:10.483  2690  2759 I bt_hci_h4: hal_close
,09-12 09:35:10.483  2690  2759 I bt_userial_vendor: device fd = 51 close
,09-12 09:35:10.504  3933  3933 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 09:35:10.504  3933  3933 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 09:35:10.504  3933  3933 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 09:35:10.504  3933  3933 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.504  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 09:35:10.505  3933  3933 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 09:35:10.505  3933  3933 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 09:35:10.505  3933  3933 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.505  3933  3933 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 09:35:10.505  3933  3933 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:35:10.505  3933  3933 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 09:35:10.549   873  1927 I ActivityManager: Start proc 3966:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-12 09:35:10.551   873  1927 I ActivityManager: Killing 3677:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 09:35:10.606  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 09:35:10.638  2690  2751 D bt_stack_manager: event_shut_down_stack finished.
09-12 09:35:10.638  2690  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 09:35:10.643  2690  2749 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 09:35:10.643  2690  2690 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 09:35:10.643  2690  2690 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 09:35:10.643  2690  2690 D BtGatt.GattService: stop()
09-12 09:35:10.643  2690  2690 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 09:35:10.644  2690  2690 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:10.644  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:10.644  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:10.645  2690  2690 V BluetoothAdapterState: isBleTurningOff()=true
09-12 09:35:10.645  2690  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 09:35:10.645  2690  2749 D BluetoothAdapterProperties: Setting state to 10
09-12 09:35:10.645  2690  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 09:35:10.646  2690  2749 I BluetoothAdapterState: Entering OffState
,09-12 09:35:10.650   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 09:35:10.674  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 09:35:10.674  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 09:35:10.674  2690  2690 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 09:35:10.675  2690  2751 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 09:35:10.677  2690  2751 D bt_stack_manager: event_clean_up_stack finished.
,09-12 09:35:10.681  3966  3966 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-12 09:35:10.693  2690  2690 I art     : System.exit called, status: 0
,09-12 09:35:10.693  2690  2690 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 09:35:10.728   873  2339 I ActivityManager: Process com.android.bluetooth (pid 2690) has died
,09-12 09:35:10.823  3933  3955 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 09:35:11.047  3966  3986 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-12 09:35:11.047  3966  3986 I Babel_SMS: MmsConfig.loadMmsSettings
09-12 09:35:11.048  3966  3986 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 09:35:11.048  3966  3986 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 09:35:11.096  3966  3986 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-12 09:35:11.096  3966  3986 I Babel_SMS: MmsConfig.loadFromResources
,09-12 09:35:11.097  3966  3986 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 09:35:11.100  3966  3986 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 09:35:11.115  3966  3966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 09:35:11.118  3966  3966 I Babel_Crash: startup - clean
,09-12 09:35:11.159   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db59aff:true
,09-12 09:35:11.171  3966  3966 I Babel_telephony: TeleModule.launchCompleted
,09-12 09:35:11.190   873  1927 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 09:35:11.200  3966  3966 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-12 09:35:11.207  3966  3966 W Babel   : BAM#gBA: invalid account id: -1
,09-12 09:35:11.207  3966  3966 W Babel   : BAM#gBA: invalid account id: -1
09-12 09:35:11.207  3966  3966 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-12 09:35:11.212   873   884 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 09:35:11.216  3966  3991 I Babel   : deleted: false for 0
,09-12 09:35:11.260   873  1385 I ActivityManager: Start proc 3993:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 09:35:11.260  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 09:35:11.301  3966  3966 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 09:35:11.308  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 09:35:11.310  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 09:35:11.319  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 09:35:11.328  3993  3993 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 09:35:11.331  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 09:35:11.341  3966  3966 I vclib   : onServiceConnected
,09-12 09:35:11.397  3993  3993 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 09:35:11.429   873  1385 I ActivityManager: Killing 3692:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 09:35:11.460  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 09:35:11.499   873  1933 I ActivityManager: Start proc 4018:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-12 09:35:11.501  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,09-12 09:35:11.578  4018  4018 D AdapterServiceConfig: Adding HeadsetService
,09-12 09:35:11.578  4018  4018 D AdapterServiceConfig: Adding A2dpService
09-12 09:35:11.578  4018  4018 D AdapterServiceConfig: Adding HidService
,09-12 09:35:11.578  4018  4018 D AdapterServiceConfig: Adding HealthService
09-12 09:35:11.578  4018  4018 D AdapterServiceConfig: Adding PanService
,09-12 09:35:11.579  4018  4018 D AdapterServiceConfig: Adding GattService
,09-12 09:35:11.579  4018  4018 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 09:35:11.583   873  1924 I ActivityManager: Killing 2250:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 09:35:11.621  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 09:35:11.649  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 09:35:11.654  1725  1725 D SystemUpdateService: onCreate
,09-12 09:35:11.656  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 09:35:11.663  1725  4030 I SystemUpdateService: active receiver: enabled
,09-12 09:35:11.666  1725  4030 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 09:35:11.668  1725  4030 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 09:35:11.668  1725  4030 I SystemUpdateService: now status is 0 (complete)
09-12 09:35:11.669  1725  4030 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 09:35:11.669  1725  4030 I SystemUpdateService: file has been verified
,09-12 09:35:11.669  1725  4030 I SystemUpdateService: OTA package size = 12249756
,09-12 09:35:11.669  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 09:35:11.678  1725  2418 I iu.UploadsManager: num queued entries: 0
09-12 09:35:11.678  1725  2418 I iu.UploadsManager: num updated entries: 0
09-12 09:35:11.679  1725  2418 I iu.SyncManager: NEXT; no task
,09-12 09:35:11.681  1725  4030 I SystemUpdateService: showing system update notification
,09-12 09:35:11.695  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 09:35:11.699  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 09:35:11.699  1725  1725 D SystemUpdateService: onDestroy
,09-12 09:35:11.715   873  1924 I ActivityManager: Start proc 4032:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 09:35:11.767  4032  4032 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 09:35:11.770  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 09:35:11.774  4032  4032 D SprintDMHelper: simOperator: 
09-12 09:35:11.774  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 09:35:11.813   873  1674 I ActivityManager: Start proc 4044:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 09:35:11.814   873  1674 I ActivityManager: Killing 3714:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 09:35:11.978   873   884 I ActivityManager: Start proc 4059:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 09:35:11.982  3966  4058 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 09:35:11.988   873  1385 I ActivityManager: Killing 3638:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-12 09:35:12.080  4059  4059 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 09:35:12.146  4059  4059 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 09:35:12.146  4059  4059 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 09:35:12.146  4059  4059 I GAv4    :   adb logcat -s GAv4
,09-12 09:35:12.161  4059  4059 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 09:35:12.169  4059  4059 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 09:35:12.209  4059  4076 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 09:35:12.316  4059  4059 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 09:35:12.406  4059  4059 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 09:35:12.416  4059  4059 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4851-4854)
,09-12 09:35:12.417  4059  4059 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 09:35:12.428  4059  4059 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {48bead0}
09-12 09:35:12.428  4059  4059 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 09:35:12.429  4059  4059 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 09:35:12.439  4059  4059 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 09:35:12.441  4059  4059 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 09:35:12.457  4059  4059 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 09:35:12.471  4059  4059 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 09:35:12.471  4059  4059 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 09:35:12.471  4059  4059 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 09:35:12.471  4059  4059 I Adreno  : Build Date                       : 10/20/15
09-12 09:35:12.471  4059  4059 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 09:35:12.471  4059  4059 I Adreno  : Local Branch                     : M14
09-12 09:35:12.471  4059  4059 I Adreno  : Remote Branch                    : 
09-12 09:35:12.471  4059  4059 I Adreno  : Remote Branch                    : 
09-12 09:35:12.471  4059  4059 I Adreno  : Reconstruct Branch               : 
,09-12 09:35:12.530  4059  4059 I NSApplication: Starting up...
,09-12 09:35:12.541  4059  4105 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 09:35:12.573   873  1980 I ActivityManager: Start proc 4110:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 09:35:12.577   873  1980 I ActivityManager: Killing 3522:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,09-12 09:35:12.654  4110  4110 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 09:35:12.832   873  1675 I ActivityManager: Start proc 4122:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver
,09-12 09:35:12.834   873  1675 I ActivityManager: Killing 3778:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 09:35:13.094   873  1933 I ActivityManager: Start proc 4137:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,09-12 09:35:13.111   873   883 I ActivityManager: Killing 3796:com.google.android.deskclock/u0a44 (adj 15): empty #17
,09-12 09:35:13.155   873   884 I ActivityManager: Killing 3814:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-12 09:35:13.176   873  2339 D WifiService: setWifiEnabled: true pid=3846, uid=10000
,09-12 09:35:13.176   873  2339 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 09:35:13.187   873  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-12 09:35:13.196  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:13.197  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:13.197  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:13.197  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 09:35:13.209   873  1304 D WifiConfigStore: loaded 0 passpoint configs
09-12 09:35:13.209   873  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 09:35:13.210   873  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 09:35:13.211   873  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 09:35:13.211   873  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 09:35:13.211   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 09:35:13.211   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 09:35:13.213  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:13.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:13.213  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:13.213  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:13.224   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 09:35:13.224   873  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=10.88 delta 1000 -> 994
,09-12 09:35:13.225   371   872 D CommandListener: Setting iface cfg
09-12 09:35:13.225   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-12 09:35:13.226   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 09:35:13.232   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 09:35:13.232   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 09:35:13.232   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 09:35:13.233   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 09:35:13.238   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 09:35:13.248  4137  4137 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 09:35:13.295   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
09-12 09:35:13.296  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 09:35:13.307  4137  4137 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 09:35:13.378  4137  4161 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-12 09:35:13.656  4137  4161 D ContactDirectoryManager: Found com.google.contacts.gal.provider
09-12 09:35:13.656  4137  4161 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-12 09:35:13.696   873  1675 I ActivityManager: Start proc 4163:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-12 09:35:13.744   873  2339 I ActivityManager: Killing 2770:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 09:35:13.745  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 09:35:13.776  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 09:35:13.776  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 09:35:13.839   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 09:35:13.845  4163  4163 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,09-12 09:35:13.854   873  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 09:35:13.855   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 09:35:13.856   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 09:35:13.890   873  1385 I ActivityManager: Start proc 4177:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-12 09:35:13.890   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 09:35:13.897   371   872 D CommandListener: Setting iface cfg
,09-12 09:35:13.898   873  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 09:35:13.909   873  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-12 09:35:13.911   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 09:35:13.927   873  4189 D DhcpClient: Receive thread started
,09-12 09:35:13.928   873  2339 I ActivityManager: Killing 3484:com.android.vending/u0a19 (adj 15): empty #17
,09-12 09:35:14.005   873  1304 E native  : do suspend false
,09-12 09:35:14.005   873  1924 I ActivityManager: Start proc 4190:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-12 09:35:14.014  4177  4177 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,09-12 09:35:14.014   873  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 09:35:14.026   873  4189 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,09-12 09:35:14.027   873  1868 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,09-12 09:35:14.030   873  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 09:35:14.041   873  4189 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 09:35:14.042   873  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 09:35:14.047   371   872 D CommandListener: Setting iface cfg
,09-12 09:35:14.050   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 09:35:14.053   873  1868 D DhcpClient: Scheduling renewal in 86399s
,09-12 09:35:14.062   873   883 I ActivityManager: Killing 3591:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-12 09:35:14.064   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-12 09:35:14.065   873  1304 D WifiConfigStore: No blacklist allowed without epno enabled
09-12 09:35:14.065   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 09:35:14.065   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 09:35:14.067   873  1306 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 09:35:14.102   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 09:35:14.102   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 09:35:14.104  4177  4207 I Gmail   : getAccountsCursor
,09-12 09:35:14.104   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 09:35:14.106   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 09:35:14.108   873  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 09:35:14.115  4177  4208 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-12 09:35:14.115  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:14.117   873  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 09:35:14.136   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 09:35:14.144   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 09:35:14.144   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 09:35:14.145   873  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 09:35:14.145   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-12 09:35:14.145   873  1306 D ConnectivityService:    accepting network in place of null
09-12 09:35:14.145   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 09:35:14.148   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 09:35:14.154   873  4176 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136591, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 09:35:14.164  4190  4190 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm,
,09-12 09:35:14.182   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 09:35:14.198  4190  4190 I GoogleHttpClient: GMS http client unavailable, use old client
,09-12 09:35:14.206  4177  4177 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-12 09:35:14.207   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 09:35:14.210   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 09:35:14.210   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 09:35:14.211   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 09:35:14.213   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 09:35:14.226   873  4175 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 09:35:14.233  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:14.234  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 09:35:14.234  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:14.234  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:14.235  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:14.235  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 09:35:14.235  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:14.236  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:14.237  4137  4161 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-12 09:35:14.270  4137  4161 I ContactDirectoryManager: Discovered 0 contact directories in 838ms
,09-12 09:35:14.305   873  4175 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 07:35:14 GMT], X-Android-Received-Millis=[1473665714304], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473665714273]}
09-12 09:35:14.306   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 09:35:14.306   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-12 09:35:14.306   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 09:35:14.309  4177  4226 E Gmail   : Error finding the version of the Email provider.....
09-12 09:35:14.309  4177  4226 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-12 09:35:14.309  4177  4226 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-12 09:35:14.309  4177  4226 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-12 09:35:14.309  4177  4226 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-12 09:35:14.309  4177  4226 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 09:35:14.309  4177  4226 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:35:14.309  4177  4226 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-12 09:35:14.309  4177  4226 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:35:14.309  4177  4226 W EmailMigration: We do not support migrating this version of the Email provider.
09-12 09:35:14.310   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 09:35:14.358  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 09:35:14.361  1725  1725 D SystemUpdateService: onCreate
,09-12 09:35:14.365  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 09:35:14.369  1725  4237 I SystemUpdateService: active receiver: enabled
,09-12 09:35:14.387  1725  4237 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 09:35:14.389  1725  4237 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 09:35:14.389  1725  4237 I SystemUpdateService: now status is 0 (complete)
09-12 09:35:14.389  1725  4237 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 09:35:14.389  1725  4237 I SystemUpdateService: file has been verified
09-12 09:35:14.389  1725  4237 I SystemUpdateService: OTA package size = 12249756
,09-12 09:35:14.396  1725  4237 I SystemUpdateService: showing system update notification
09-12 09:35:14.396  4177  4234 I Gmail   : getAccountsCursor
,09-12 09:35:14.402  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 09:35:14.403  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:14.410  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 09:35:14.412  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 09:35:14.414  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 09:35:14.414  1725  4240 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 09:35:14.415  1725  4240 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 09:35:14.416  1725  2418 I iu.UploadsManager: num queued entries: 0
,09-12 09:35:14.417  1725  4240 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
09-12 09:35:14.417  1725  2418 I iu.UploadsManager: num updated entries: 0
09-12 09:35:14.418  1725  2418 I iu.SyncManager: NEXT; no task
,09-12 09:35:14.421  4032  4032 D SprintDMHelper: simOperator: 
,09-12 09:35:14.421  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 09:35:14.428  3570  4228 V KeepSync: Connecting to GoogleApiClient
,09-12 09:35:14.430  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 09:35:14.429   873  1980 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 09:35:14.431  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:14.435  1725  1725 D SystemUpdateService: onDestroy
,09-12 09:35:14.464  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 09:35:14.465  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 09:35:14.465  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:14.465  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:14.479  1725  4240 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-12 09:35:14.579  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 09:35:14.579  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 09:35:14.579  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:35:14.579  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:14.604  1725  4246 V BaseAuthAsyncOperation: access token request failed
,09-12 09:35:14.605  3570  4228 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 09:35:14.644  3966  4242 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 09:35:14.663   873  1927 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-12 09:35:14.669  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:14.697  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:35:14.698  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 09:35:14.698  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:35:14.698  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:14.721  4122  4231 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 09:35:14.721  4122  4231 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at blb.a(PG:3937)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at czp.a(PG:18188)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:35:14.721  4122  4231 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	... 12 more
09-12 09:35:14.721  4122  4231 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at fal.a(PG:38)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:35:14.721  4122  4231 E HttpOperation: 	... 14 more
,09-12 09:35:14.741  4163  4163 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-12 09:35:14.769  4177  4253 I Gmail   : Observing account changes for notifications
,09-12 09:35:14.781  4163  4163 I Exchange: EasService.onCreate
,09-12 09:35:14.792  4163  4259 I Exchange: RestartPingTask
,09-12 09:35:14.834  4163  4163 I Exchange: RestartPingsTask did not start any pings.
,09-12 09:35:14.834  4163  4163 I Exchange: PSS stopIfIdle
09-12 09:35:14.834  4163  4163 I Exchange: PSS has no active accounts; stopping service.
,09-12 09:35:14.835  4163  4163 I Exchange: onDestroy
,09-12 09:35:14.850  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:35:14.850  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:35:14.851  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:35:14.851  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:14.869  4177  4258 I Gmail   : notifyAccountChanged
,09-12 09:35:14.879  4177  4224 I Gmail   : getAccountsCursor
,09-12 09:35:14.893  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:14.899  4122  4231 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 09:35:14.899  4122  4231 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at hec.a(PG:42)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at hee.a(PG:102)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at czr.a(PG:65)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at kka.a(PG:108)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at czp.a(PG:19176)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:35:14.899  4122  4231 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	... 15 more
09-12 09:35:14.899  4122  4231 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at fal.a(PG:38)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:35:14.899  4122  4231 E HttpOperation: 	... 17 more
,09-12 09:35:14.900  4122  4231 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 09:35:14.900  4122  4231 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at hec.a(PG:42)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at hee.a(PG:102)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at czr.a(PG:65)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at kka.a(PG:108)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	... 15 more
09-12 09:35:14.900  4122  4231 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at fal.a(PG:38)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 09:35:14.900  4122  4231 E ExperimentLoader: 	... 17 more
,09-12 09:35:14.908  4177  4258 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,09-12 09:35:14.937  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 09:35:14.937  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 09:35:14.937  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:14.937  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:14.944  4177  4258 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-12 09:35:14.967  3570  4228 E KeepSync: IOException
09-12 09:35:14.967  3570  4228 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 09:35:14.967  3570  4228 E KeepSync: ,	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 09:35:14.967  3570  4228 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:35:14.967  3570  4228 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 09:35:14.967  3570  4228 E KeepSync: 	... 10 more
,09-12 09:35:14.967  3570  4228 W KeepSync: Sync result 2
,09-12 09:35:14.975  4177  4258 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-12 09:35:14.977   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127168, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:35:14.983  4177  4258 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-12 09:35:15.016   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126618, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:35:15.071  4177  4208 I Gmail   : getAccountsCursor
,09-12 09:35:15.083  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:15.210   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 09:35:16.071   873  1981 I ActivityManager: Killing 2012:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,09-12 09:35:16.127   873  1305 D WifiService: Client connection lost with reason: 4
,09-12 09:35:16.180   873  1933 D WifiService: setWifiEnabled: false pid=3846, uid=10000
,09-12 09:35:16.180   873  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 09:35:16.219  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 09:35:16.226   873  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 09:35:16.226   873  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 09:35:16.226   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 09:35:16.226   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 09:35:16.242   873  1868 D DhcpClient: Clearing IP address
,09-12 09:35:16.242   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 09:35:16.245   371   872 D CommandListener: Setting iface cfg
,09-12 09:35:16.247   873  4189 D DhcpClient: Receive thread stopped
,09-12 09:35:16.248  1511  4244 V NativeCrypto: Read error: ssl=0x9a87d000: I/O error during system call, Connection timed out
,09-12 09:35:16.250  1511  4244 V NativeCrypto: SSL shutdown failed: ssl=0x9a87d000: I/O error during system call, Broken pipe
,09-12 09:35:16.254   873  1675 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-12 09:35:16.255   873  4175 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-12 09:35:16.264   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 09:35:16.265   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 09:35:16.266   873  4175 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 09:35:16.265   873  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 09:35:16.273   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 09:35:16.274   394   394 E Parcel  : Reading a NULL string not supported here.
,09-12 09:35:16.278   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 09:35:16.287   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 09:35:16.292   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 09:35:16.295  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:16.295  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 09:35:16.295  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:16.296  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:16.297  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:16.297  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:16.297  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:16.297  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 09:35:16.297   873  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 09:35:16.301  2096  2349 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 09:35:16.327   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 09:35:16.350   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 09:35:16.351   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 09:35:16.351   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 09:35:16.353   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 09:35:16.355  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:16.357  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:16.361  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 09:35:16.365  1725  1725 D SystemUpdateService: onCreate
,09-12 09:35:16.367  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 09:35:16.376  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 09:35:16.378  1725  2418 I iu.UploadsManager: num queued entries: 0
,09-12 09:35:16.387  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 09:35:16.388  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-12 09:35:16.390  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-12 09:35:16.394  4032  4032 D SprintDMHelper: simOperator: 
09-12 09:35:16.394  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 09:35:16.410  1725  2418 I iu.UploadsManager: num updated entries: 0
,09-12 09:35:16.411  1725  2418 I iu.SyncManager: NEXT; no task
,09-12 09:35:16.422  1725  4273 I SystemUpdateService: active receiver: enabled
,09-12 09:35:16.425  3966  4277 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 09:35:16.436  1725  4273 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 09:35:16.436   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 09:35:16.438  1725  4273 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 09:35:16.438  1725  4273 I SystemUpdateService: now status is 0 (complete)
09-12 09:35:16.438  1725  4273 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 09:35:16.438  1725  4273 I SystemUpdateService: file has been verified
,09-12 09:35:16.438  1725  4273 I SystemUpdateService: OTA package size = 12249756
,09-12 09:35:16.441   873  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 09:35:16.441   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 09:35:16.445  1725  4273 I SystemUpdateService: showing system update notification
,09-12 09:35:16.455  1725  1725 D SystemUpdateService: onDestroy
,09-12 09:35:18.083   873  1290 I ActivityManager: Start proc 4280:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,09-12 09:35:18.158  4280  4280 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,09-12 09:35:18.260  4280  4280 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-12 09:35:18.342  4280  4280 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,09-12 09:35:18.377  4280  4280 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 09:35:18.379  4280  4280 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 09:35:18.431  4280  4280 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-12 09:35:18.433  4280  4280 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,09-12 09:35:18.439  4280  4313 D Ads     : Skipping gmscore version check
,09-12 09:35:18.458  4280  4280 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-12 09:35:18.485  4280  4313 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-12 09:35:18.497  4280  4280 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-12 09:35:18.631  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:18.670  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:35:18.670  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:35:18.670  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:18.671  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:18.699  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 09:35:18.700  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 09:35:18.700  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 09:35:18.721   873  1927 I ActivityManager: Killing 3914:com.android.settings/1000 (adj 15): empty #17
,09-12 09:35:19.231   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8209d2f:true
,09-12 09:35:19.232  4018  4018 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 09:35:19.237  4018  4018 I bt_bluedroid: init
,09-12 09:35:19.238  4018  4318 I BluetoothAdapterState: Entering OffState
,09-12 09:35:19.243  4018  4319 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 09:35:19.243  4018  4319 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 09:35:19.243  4018  4319 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 09:35:19.243  4018  4319 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 09:35:19.244  4018  4018 I bt_bluedroid: get_profile_interface socket
09-12 09:35:19.246  4018  4018 I bt_bluedroid: get_profile_interface sdp
,09-12 09:35:19.249  4018  4029 I bt_bluedroid: config_hci_snoop_log
,09-12 09:35:19.250  4018  4322 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 09:35:19.250   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-12 09:35:19.262  4018  4322 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 09:35:19.267  4018  4318 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 09:35:19.268  4018  4318 D BluetoothAdapterProperties: Setting state to 14
,09-12 09:35:19.268  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 09:35:19.272  4018  4318 D BluetoothBondStateMachine: make
,09-12 09:35:19.276  4018  4324 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 09:35:19.281  4177  4218 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-12 09:35:19.283  4018  4318 I BluetoothAdapterState: Entering PendingCommandState
,09-12 09:35:19.286  4018  4018 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 09:35:19.293  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:19.294  4018  4018 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 09:35:19.294  4018  4018 D BtGatt.GattService: Received start request. Starting profile...
09-12 09:35:19.294  4018  4018 D BtGatt.GattService: start()
09-12 09:35:19.294  4018  4018 I bt_bluedroid: get_profile_interface gatt
,09-12 09:35:19.295  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:19.296  4018  4018 D BtGatt.AdvertiseManager: advertise manager created
,09-12 09:35:19.301  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:19.302  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:19.302  4018  4018 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 09:35:19.302  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:19.302  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 09:35:19.302  4018  4318 I bt_bluedroid: enable
09-12 09:35:19.303  4018  4319 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 09:35:19.303  4018  4319 I bt_hci  : start_up
,09-12 09:35:19.314  4018  4319 I bt_vendor: alloc value 0xb3969189
,09-12 09:35:19.314  4018  4319 I bt_vendor: init
09-12 09:35:19.314  4018  4319 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 09:35:19.314  4018  4319 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 09:35:19.421  4018  4319 D bt_hci  : start_up starting async portion
,09-12 09:35:19.421  4018  4328 I bt_hci  : event_finish_startup
09-12 09:35:19.422  4018  4328 I bt_hci_h4: hal_open
09-12 09:35:19.422  4018  4328 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 09:35:19.434  4018  4328 I bt_userial_vendor: device fd = 51 open
,09-12 09:35:19.463  4018  4328 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 09:35:19.495  4018  4328 D bt_hwcfg: Chipset BCM4354A2
09-12 09:35:19.495  4018  4328 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 09:35:19.496  4018  4328 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 09:35:19.808  4163  4256 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-12 09:35:20.133  4018  4328 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 09:35:20.135  4018  4328 D bt_hwcfg: Settlement delay -- 100 ms
09-12 09:35:20.135  4018  4328 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 09:35:20.252  4018  4328 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 09:35:20.253  4018  4328 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 09:35:20.283  4018  4328 I bt_hwcfg: vendor lib fwcfg completed
,09-12 09:35:20.283  4018  4328 I bt_vendor: firmware callback
09-12 09:35:20.283  4018  4328 I bt_hci  : firmware_config_callback
,09-12 09:35:20.303  4280  4280 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-12 09:35:20.309  4018  4333 I bt_btu  : btu_task pending for preload complete event
,09-12 09:35:20.310  4018  4333 I bt_btu_task: Bluetooth chip preload is complete
,09-12 09:35:20.310  4018  4333 I bt_btu  : btu_task received preload complete event
,09-12 09:35:20.318  4018  4333 I         : BTE_InitTraceLevels -- TRC_HCI,
09-12 09:35:20.318  4018  4333 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 09:35:20.318  4018  4333 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 09:35:20.318  4018  4333 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 09:35:20.319  4018  4333 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 09:35:20.319  4018  4333 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 09:35:20.319  4018  4333 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 09:35:20.319  4018  4333 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 09:35:20.320  4018  4333 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 09:35:20.320  4018  4333 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 09:35:20.320  4018  4333 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 09:35:20.320  4018  4333 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 09:35:20.322  4018  4333 I         : BTE_InitTraceLevels -- TRC_SMP
,09-12 09:35:20.322  4018  4333 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-12 09:35:20.322  4018  4333 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 09:35:20.328  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:20.377  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-12 09:35:20.377  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:35:20.377  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:20.377  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:20.406  4280  4280 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 09:35:20.422  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:20.457  4018  4333 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,09-12 09:35:20.457  4018  4333 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,09-12 09:35:20.466  4018  4322 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 09:35:20.467  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 09:35:20.468  4018  4322 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 09:35:20.471  4018  4322 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 09:35:20.474  4018  4322 D BluetoothAdapterProperties: Scan Mode:20
09-12 09:35:20.475  4018  4322 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 09:35:20.480  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:20.484  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:20.485  4018  4322 D bt_hci  : do_postload posting postload work item
,09-12 09:35:20.486  4018  4328 I bt_hci  : event_postload
,09-12 09:35:20.486  4018  4328 I bt_vendor: sco_config_cb
,09-12 09:35:20.486  4018  4328 I bt_hci  : sco_config_callback postload finished.
,09-12 09:35:20.489  4018  4322 D bt_bte_conf: Device ID record 1 : primary
,09-12 09:35:20.489  4018  4322 D bt_bte_conf:   vendorId            = 000f
,09-12 09:35:20.489  4018  4322 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 09:35:20.489  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:35:20.489  4018  4322 D bt_bte_conf:   product             = 1200
09-12 09:35:20.489  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 09:35:20.490  4018  4322 D bt_bte_conf:   version             = 1436
,09-12 09:35:20.490  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:20.490  4018  4322 D bt_bte_conf:   clientExecutableURL = 
09-12 09:35:20.490  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 09:35:20.490  4018  4322 D bt_bte_conf:   serviceDescription  = 
,09-12 09:35:20.490  4018  4328 I bt_vendor: low_power_mode_cb
09-12 09:35:20.490  4018  4322 D bt_bte_conf:   documentationURL    = 
,09-12 09:35:20.490  4018  4322 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 09:35:20.491  4018  4319 D bt_stack_manager: event_start_up_stack finished
,09-12 09:35:20.492  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 09:35:20.493  4018  4318 D BluetoothAdapterProperties: Setting state to 15
,09-12 09:35:20.493  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 09:35:20.494  4018  4318 I BluetoothAdapterState: Entering BleOnState
,09-12 09:35:20.499  4018  4318 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 09:35:20.499  4018  4318 D BluetoothAdapterProperties: Setting state to 11
09-12 09:35:20.499  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 09:35:20.505  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:20.507  4018  4018 D HeadsetService: Received start request. Starting profile...
,09-12 09:35:20.511  4018  4018 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 09:35:20.512  4018  4018 D HeadsetStateMachine: make
,09-12 09:35:20.513  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:20.514  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:20.530   873   886 I ActivityManager: Start proc 4341:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 09:35:20.534  4018  4018 D HeadsetStateMachine: max_hf_connections = 1
,09-12 09:35:20.534  4018  4018 I bt_bluedroid: get_profile_interface handsfree,
,09-12 09:35:20.536  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 09:35:20.539  4018  4322 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 09:35:20.545  4018  4318 I BluetoothAdapterState: Entering PendingCommandState
09-12 09:35:20.547  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:20.547  4018  4018 D A2dpService: Received start request. Starting profile...
09-12 09:35:20.548  4018  4018 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 09:35:20.548  4018  4018 I bt_bluedroid: get_profile_interface avrcp
,09-12 09:35:20.554  4018  4018 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 09:35:20.556  4018  4018 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 09:35:20.556  4018  4018 D A2dpStateMachine: make
09-12 09:35:20.557  4018  4018 I bt_bluedroid: get_profile_interface a2dp
,09-12 09:35:20.558  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 09:35:20.562  4018  4018 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 09:35:20.563  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:20.561  4018  4353 D A2dpStateMachine: Enter Disconnected: -2
09-12 09:35:20.564  4018  4018 D HidService: Received start request. Starting profile...
09-12 09:35:20.565  4018  4018 I bt_bluedroid: get_profile_interface hidhost
09-12 09:35:20.565  4018  4322 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
09-12 09:35:20.565  4018  4018 D HidService: setHidService(): set to: null
09-12 09:35:20.565  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 09:35:20.568  4018  4018 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 09:35:20.569  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:20.570  4018  4018 D HealthService: Received start request. Starting profile...
09-12 09:35:20.572  4018  4018 I bt_bluedroid: get_profile_interface health
09-12 09:35:20.574  4018  4018 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 09:35:20.576  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:20.576  4018  4018 D PanService: Received start request. Starting profile...
09-12 09:35:20.576  4018  4018 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 09:35:20.577  4018  4018 I bt_bluedroid: get_profile_interface pan
09-12 09:35:20.577  4018  4322 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 09:35:20.579  4018  4018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:20.580  4018  4018 D BluetoothMapService: Received start request. Starting profile...
09-12 09:35:20.580  4018  4018 D BluetoothMapService: start()
09-12 09:35:20.583  4018  4018 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 09:35:20.583  4018  4018 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 09:35:20.584  4018  4018 D BluetoothMapAppObserver: createReceiver()
,09-12 09:35:20.586  4018  4018 D BluetoothMapAppObserver: initObservers()
09-12 09:35:20.586  4018  4018 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 09:35:20.591  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:20.591  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:20.591  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:20.592  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:20.594  4018  4340 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:20.594  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:20.595  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:20.596  4018  4018 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:20.596  4018  4018 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:20.596  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:20.596  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:20.596  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 09:35:20.596  4018  4318 D BluetoothAdapterProperties: ScanMode =  20
09-12 09:35:20.596  4018  4318 D BluetoothAdapterProperties: State =  11
,09-12 09:35:20.597  4018  4318 D BluetoothAdapterProperties: Setting state to 12
09-12 09:35:20.597  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 09:35:20.597  4018  4318 I BluetoothAdapterState: Entering OnState
09-12 09:35:20.598   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:20.598  1357  1971 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 09:35:20.598  4018  4322 D BluetoothAdapterProperties: Scan Mode:21
09-12 09:35:20.598  4018  4322 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 09:35:20.600   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 09:35:20.600  1357  1382 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 09:35:20.601  1357  1357 D BluetoothA2dp: Proxy object connected
,09-12 09:35:20.602  1357  1971 D BluetoothPan: onBluetoothStateChange on: true
09-12 09:35:20.603  1357  1370 D BluetoothMap: onBluetoothStateChange: up=true
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:20.604  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:20.605  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 09:35:20.605  1357  1357 D PanProfile: Bluetooth service connected
,09-12 09:35:20.605  1941  2059 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:20.606   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:20.606   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 09:35:20.606  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 09:35:20.606   873   873 D BluetoothA2dp: Proxy object connected
09-12 09:35:20.607  1357  1971 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:20.607  4280  4359 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
09-12 09:35:20.607  1357  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 09:35:20.609  4280  4280 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
09-12 09:35:20.610  1357  1357 D BluetoothMap: Proxy object connected
09-12 09:35:20.610  1357  1357 D MapProfile: Bluetooth service connected
09-12 09:35:20.610  1357  1357 D BluetoothMap: getConnectedDevices()
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:20.610  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:20.611   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 09:35:20.612  4018  4018 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 09:35:20.613  4018  4018 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 09:35:20.613  1357  1357 D BluetoothInputDevice: Proxy object connected
09-12 09:35:20.613  1357  1357 D HidProfile: Bluetooth service connected
09-12 09:35:20.613  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:20.614  4018  4018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 09:35:20.614  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 09:35:20.615  4280  4280 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,09-12 09:35:20.616  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:20.616  4018  4018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 09:35:20.618  4018  4018 D ObexServerSockets: Succeed to create listening sockets 
09-12 09:35:20.618  4018  4018 D ObexServerSockets0: startAccept()
09-12 09:35:20.618  4018  4018 D ObexServerSockets0: prepareForNewConnect()
,09-12 09:35:20.618  4341  4341 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-12 09:35:20.622  4018  4018 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 09:35:20.622  4018  4018 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 09:35:20.623  4018  4018 D BluetoothMapService: onReceive
09-12 09:35:20.623  4018  4363 D ObexServerSockets0: Accepting socket connection...
09-12 09:35:20.623  4018  4018 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 09:35:20.623  4018  4362 D ObexServerSockets0: Accepting socket connection...
09-12 09:35:20.623  4018  4018 D BluetoothMapService: STATE_ON
09-12 09:35:20.633  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:20.644  4018  4018 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 09:35:20.644  4018  4018 D ObexServerSockets0: prepareForNewConnect()
,09-12 09:35:20.649  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 09:35:20.659  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 09:35:20.659  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-12 09:35:20.660  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:35:20.660  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:35:20.660  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:20.665   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d56182c:true
,09-12 09:35:20.668  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 09:35:20.672  4341  4341 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-12 09:35:20.676  4341  4341 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 09:35:20.680  4280  4280 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 09:35:20.681  1357  1357 D BluetoothPbap: Proxy object connected
09-12 09:35:20.681  1357  1357 D PbapServerProfile: Bluetooth service connected
,09-12 09:35:20.690  4018  4367 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 09:35:20.717  1941  2201 D BluetoothHeadset: Proxy object connected
,09-12 09:35:20.717   873   873 D BluetoothHeadset: Proxy object connected
,09-12 09:35:20.717   873   873 D BluetoothHeadset: Proxy object connected
09-12 09:35:20.717   873   873 D BluetoothHeadset: Proxy object connected
,09-12 09:35:20.718  1357  1370 D BluetoothHeadset: Proxy object connected
,09-12 09:35:20.718  1357  1357 D HeadsetProfile: Bluetooth service connected
,09-12 09:35:20.723  4341  4341 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 09:35:20.724  4341  4341 D BluetoothMap: Create BluetoothMap proxy object
,09-12 09:35:20.725  4018  4371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 09:35:20.727  4018  4371 I BtOppRfcommListener: Accept thread started.
,09-12 09:35:20.731  4341  4341 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 09:35:20.737  4341  4341 D DockEventReceiver: finishStartingService: stopping service
,09-12 09:35:20.738  4341  4341 D BluetoothA2dp: Proxy object connected
,09-12 09:35:20.741  4341  4341 D BluetoothInputDevice: Proxy object connected
,09-12 09:35:20.741  4341  4341 D HidProfile: Bluetooth service connected
,09-12 09:35:20.743  4341  4341 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 09:35:20.743  4341  4341 D PanProfile: Bluetooth service connected
09-12 09:35:20.743  4341  4341 D BluetoothMap: Proxy object connected
,09-12 09:35:20.743  4341  4341 D MapProfile: Bluetooth service connected
09-12 09:35:20.743  4341  4341 D BluetoothMap: getConnectedDevices()
,09-12 09:35:20.746  4341  4341 D BluetoothPbap: Proxy object connected
,09-12 09:35:20.746  4341  4341 D PbapServerProfile: Bluetooth service connected
,09-12 09:35:20.792  4341  4355 D BluetoothHeadset: Proxy object connected
,09-12 09:35:20.793  4341  4341 D HeadsetProfile: Bluetooth service connected
,09-12 09:35:20.889  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:20.933  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:35:20.933  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:35:20.933  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:20.934  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:20.953  4280  4280 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 09:35:20.954  4280  4280 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-12 09:35:20.957  4280  4280 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-12 09:35:20.962  4280  4280 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,09-12 09:35:20.972  4280  4374 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-12 09:35:22.150   873  1306 D ConnectivityService: handlePromptUnvalidated 101
,09-12 09:35:22.193  4018  4318 D BluetoothAdapterState: Current state: ON, message: 23
09-12 09:35:22.194  4018  4318 D BluetoothAdapterProperties: Setting state to 13
09-12 09:35:22.194  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 09:35:22.195  4018  4318 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 09:35:22.197  4018  4318 I BluetoothAdapterState: Entering PendingCommandState
,09-12 09:35:22.200  4018  4322 D BluetoothAdapterProperties: Scan Mode:20
,09-12 09:35:22.201  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 09:35:22.203  4018  4018 D HeadsetService: Received stop request...Stopping profile...
,09-12 09:35:22.205  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:22.205  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 09:35:22.207  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:22.207  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:22.209  1941  1957 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:22.211  4341  4352 D BluetoothHeadset: Proxy object disconnected
,09-12 09:35:22.212  4018  4018 D A2dpService: Received stop request...Stopping profile...
,09-12 09:35:22.212  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:22.213  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 09:35:22.214   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:22.214   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 09:35:22.214  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 09:35:22.215  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 09:35:22.212  4341  4341 D HeadsetProfile: Bluetooth service disconnected
09-12 09:35:22.216  4018  4353 D A2dpStateMachine: Exit Disconnected: -1
,09-12 09:35:22.214   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 09:35:22.220  1357  1971 D BluetoothHeadset: Proxy object disconnected
,09-12 09:35:22.220  1357  1357 D HeadsetProfile: Bluetooth service disconnected
09-12 09:35:22.223  1357  1357 D BluetoothA2dp: Proxy object disconnected
,09-12 09:35:22.224   873   873 D BluetoothA2dp: Proxy object disconnected
,09-12 09:35:22.225  4341  4341 D BluetoothA2dp: Proxy object disconnected
09-12 09:35:22.225  4018  4018 V BluetoothAdapterState: isTurningOff()=true
,09-12 09:35:22.226  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:22.226  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 09:35:22.226  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:22.227  4018  4018 D HidService: Received stop request...Stopping profile...
09-12 09:35:22.228  4018  4018 D HidService: Stopping Bluetooth HidService
09-12 09:35:22.229  4341  4341 D BluetoothInputDevice: Proxy object disconnected
09-12 09:35:22.229  4341  4341 D HidProfile: Bluetooth service disconnected
,09-12 09:35:22.230  1357  1357 D BluetoothInputDevice: Proxy object disconnected
09-12 09:35:22.230  1357  1357 D HidProfile: Bluetooth service disconnected
,09-12 09:35:22.232  4018  4018 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 09:35:22.232  4018  4018 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 09:35:22.232  4018  4333 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:22.232  4018  4333 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:22.232  4018  4333 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:22.233  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 09:35:22.233  4018  4322 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 09:35:22.233  4018  4018 D HealthService: Received stop request...Stopping profile...
,09-12 09:35:22.235  4018  4018 D PanService: Received stop request...Stopping profile...
,09-12 09:35:22.237  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 09:35:22.237  1357  1357 D PanProfile: Bluetooth service disconnected
,09-12 09:35:22.237  4341  4341 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 09:35:22.237  4341  4341 D PanProfile: Bluetooth service disconnected
09-12 09:35:22.238  4018  4018 D BluetoothMapService: Received stop request...Stopping profile...
09-12 09:35:22.238  4018  4018 D BluetoothMapService: stop()
09-12 09:35:22.238  4018  4018 D BluetoothMapAppObserver: deinitObservers()
,09-12 09:35:22.239  4018  4018 D BluetoothMapAppObserver: removeReceiver()
,09-12 09:35:22.240  1357  1357 D BluetoothMap: Proxy object disconnected
,09-12 09:35:22.241  1357  1357 D MapProfile: Bluetooth service disconnected
,09-12 09:35:22.242  4018  4018 V BluetoothAdapterState: isTurningOff()=true
,09-12 09:35:22.242  4018  4018 V BluetoothAdapterState: isTurningOn()=false
,09-12 09:35:22.243  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 09:35:22.243  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:22.246  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:22.246  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:22.246  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:22.246  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:22.246  4018  4018 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 09:35:22.246  4018  4018 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 09:35:22.247  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:22.247  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:22.248  4018  4333 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:22.248  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:22.248  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:22.248  4018  4333 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 09:35:22.249  4018  4333 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 09:35:22.249  4018  4018 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 09:35:22.249  4018  4333 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 09:35:22.249  4018  4333 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 09:35:22.249  4018  4333 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 09:35:22.249  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 09:35:22.249  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:22.249  4018  4018 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 09:35:22.249  4018  4322 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 09:35:22.249  4018  4322 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 09:35:22.250  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:22.250  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:22.250  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:22.250  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:22.250  4018  4018 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 09:35:22.251  4018  4018 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 09:35:22.251  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:22.251  4018  4018 D BluetoothMapService: MAP Service closeService in
,09-12 09:35:22.251  4018  4018 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 09:35:22.252  4018  4018 D ObexServerSockets0: shutdown(block = true)
09-12 09:35:22.252  4018  4362 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 09:35:22.253  4018  4018 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 09:35:22.253  4018  4335 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 09:35:22.253  4018  4363 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 09:35:22.253  4018  4018 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 09:35:22.254  4018  4018 V BluetoothAdapterState: isTurningOff()=true
09-12 09:35:22.255  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:22.255  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:22.255  4018  4018 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:22.256  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 09:35:22.256  4018  4318 D BluetoothAdapterProperties: Setting state to 15
09-12 09:35:22.257  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 09:35:22.259  4018  4318 I BluetoothAdapterState: Entering BleOnState
09-12 09:35:22.259  4341  4352 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 09:35:22.260   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:22.260  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 09:35:22.260   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:22.261  4018  4018 D BluetoothMapService: cleanup()
09-12 09:35:22.261  4341  4355 D BluetoothMap: onBluetoothStateChange: up=false
09-12 09:35:22.261  4018  4018 D BluetoothMapService: MAP Service closeService in
09-12 09:35:22.261  4018  4018 I BtOppRfcommListener: stopping Accept Thread
09-12 09:35:22.262  1357  1971 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 09:35:22.262  4018  4371 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 09:35:22.262  4018  4371 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 09:35:22.263  1357  1382 D BluetoothPan: onBluetoothStateChange on: false
09-12 09:35:22.264  1357  1370 D BluetoothMap: onBluetoothStateChange: up=false
09-12 09:35:22.267  1941  1960 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:22.267   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:22.268  4341  4352 D BluetoothPan: onBluetoothStateChange on: false
09-12 09:35:22.270  4341  4355 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 09:35:22.254  4341  4341 D BluetoothMap: Proxy object disconnected
09-12 09:35:22.271   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 09:35:22.271  4341  4341 D MapProfile: Bluetooth service disconnected
09-12 09:35:22.271  1357  1971 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:22.271  1357  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 09:35:22.272  4341  4352 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 09:35:22.273  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 09:35:22.273  4341  4355 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 09:35:22.274  4018  4318 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 09:35:22.274  4018  4318 D BluetoothAdapterProperties: Setting state to 16
,09-12 09:35:22.274  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 09:35:22.274  4018  4318 D BluetoothAdapterProperties: onBleDisable
09-12 09:35:22.274  4018  4318 I BluetoothAdapterState: Entering PendingCommandState,
09-12 09:35:22.275  4018  4319 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 09:35:22.276  4018  4333 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 09:35:22.276  4018  4333 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 09:35:22.277  4018  4322 D BluetoothAdapterProperties: Scan Mode:20
,09-12 09:35:22.278  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:22.280  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:22.282  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:22.284  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:22.284  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 09:35:22.289  4341  4341 D DockEventReceiver: finishStartingService: stopping service
,09-12 09:35:22.293  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 09:35:22.301  4341  4341 D DockEventReceiver: finishStartingService: stopping service
,09-12 09:35:22.301  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 09:35:22.477  4018  4322 I bt_hci  : shut_down
,09-12 09:35:22.477  4018  4328 D bt_hwcfg: hw_epilog_process
,09-12 09:35:22.493  4018  4328 I bt_vendor: low_power_mode_cb
,09-12 09:35:22.513  4018  4328 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 09:35:22.514  4018  4328 I bt_vendor: epilog_cb
09-12 09:35:22.514  4018  4328 I bt_hci  : epilog_finished_callback
,09-12 09:35:22.520  4018  4322 I bt_hci_h4: hal_close
,09-12 09:35:22.521  4018  4322 I bt_userial_vendor: device fd = 51 close
,09-12 09:35:22.641  4018  4319 D bt_stack_manager: event_shut_down_stack finished.
,09-12 09:35:22.642  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 09:35:22.648  4018  4018 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 09:35:22.649  4018  4318 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 09:35:22.650  4018  4018 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 09:35:22.650  4018  4018 D BtGatt.GattService: stop()
09-12 09:35:22.651  4018  4018 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 09:35:22.657  4018  4018 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:22.657  4018  4018 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:22.658  4018  4018 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:22.658  4018  4018 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 09:35:22.660  4018  4318 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 09:35:22.661  4018  4318 D BluetoothAdapterProperties: Setting state to 10
09-12 09:35:22.661  4018  4318 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 09:35:22.663  4018  4318 I BluetoothAdapterState: Entering OffState
09-12 09:35:22.664   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 09:35:22.686  4018  4018 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 09:35:22.686  4018  4018 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 09:35:22.687  4018  4319 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-12 09:35:22.688  4018  4018 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 09:35:22.698  4018  4319 D bt_stack_manager: event_clean_up_stack finished.
,09-12 09:35:22.702  4018  4018 I art     : System.exit called, status: 0
,09-12 09:35:22.702  4018  4018 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 09:35:22.757   873   883 I ActivityManager: Process com.android.bluetooth (pid 4018) has died
,09-12 09:35:25.193  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 09:35:25.193  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:27.603   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 09:35:27.613  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-12 09:35:27.622   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 09:35:27.622   873   893 I Adreno  : Build Date                       : 10/20/15
09-12 09:35:27.622   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 09:35:27.622   873   893 I Adreno  : Local Branch                     : M14
09-12 09:35:27.622   873   893 I Adreno  : Remote Branch                    : 
09-12 09:35:27.622   873   893 I Adreno  : Remote Branch                    : 
09-12 09:35:27.622   873   893 I Adreno  : Reconstruct Branch               : 
,09-12 09:35:27.661   281   370 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (199 us)
,09-12 09:35:28.201  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:28.204  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd4c3cc added. We now have 6 listener(s)
,09-12 09:35:28.205  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:28.213  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:28.213  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@607b615 added. We now have 7 listener(s)
,09-12 09:35:28.214  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:28.216  3846  3894 I System.out: IsBluetoothEnabled
,09-12 09:35:28.227  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:28.260   873   890 I ActivityManager: Start proc 4388:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 09:35:28.304  3846  3846 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 09:35:28.304  3846  3846 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 09:35:28.344   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 09:35:28.356   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 09:35:28.356  3846  3846 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c8a2312 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4011d2a, 16908290=android.view.AbsSavedState$1@4011d2a}, android:focusedViewId=100}]}]
,09-12 09:35:28.356  3846  3846 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-12 09:35:28.357  3846  3846 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 09:35:28.357  3846  3846 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 09:35:28.361   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-12 09:35:28.367   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 09:35:28.367   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding HeadsetService
,09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding A2dpService
09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding HidService
09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding HealthService
09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding PanService
,09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding GattService
09-12 09:35:28.396  4388  4388 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 09:35:28.405   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6863b9a:true
,09-12 09:35:28.406  4388  4388 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 09:35:28.409  4388  4388 I bt_bluedroid: init
,09-12 09:35:28.410  4388  4400 I BluetoothAdapterState: Entering OffState
,09-12 09:35:28.411  4388  4401 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 09:35:28.411  4388  4401 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 09:35:28.411  4388  4401 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 09:35:28.411  4388  4401 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 09:35:28.412  4388  4388 I bt_bluedroid: get_profile_interface socket
,09-12 09:35:28.413  4388  4388 I bt_bluedroid: get_profile_interface sdp
,09-12 09:35:28.416  4388  4399 I bt_bluedroid: config_hci_snoop_log
,09-12 09:35:28.416   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 09:35:28.417  4388  4404 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 09:35:28.419  4388  4404 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 09:35:28.422  4388  4400 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 09:35:28.423  4388  4400 D BluetoothAdapterProperties: Setting state to 14
,09-12 09:35:28.423  4388  4400 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 09:35:28.425  4388  4400 D BluetoothBondStateMachine: make
,09-12 09:35:28.427  4388  4405 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 09:35:28.431  4388  4400 I BluetoothAdapterState: Entering PendingCommandState
,09-12 09:35:28.431  4388  4388 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-12 09:35:28.433  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:28.433  4388  4388 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 09:35:28.434  4388  4388 D BtGatt.GattService: Received start request. Starting profile...
,09-12 09:35:28.434  4388  4388 D BtGatt.GattService: start()
09-12 09:35:28.434  4388  4388 I bt_bluedroid: get_profile_interface gatt
09-12 09:35:28.434  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:28.435  4388  4388 D BtGatt.AdvertiseManager: advertise manager created
,09-12 09:35:28.442  4388  4388 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:28.442  4388  4388 V BluetoothAdapterState: isTurningOn()=false
09-12 09:35:28.443  4388  4388 V BluetoothAdapterState: isBleTurningOn()=true
09-12 09:35:28.443  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:28.443  4388  4400 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 09:35:28.444  4388  4400 I bt_bluedroid: enable
09-12 09:35:28.444  4388  4401 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 09:35:28.444  4388  4401 I bt_hci  : start_up
,09-12 09:35:28.449  4388  4401 I bt_vendor: alloc value 0xb39bf189
,09-12 09:35:28.449  4388  4401 I bt_vendor: init
09-12 09:35:28.449  4388  4401 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 09:35:28.449  4388  4401 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 09:35:28.558  4388  4401 D bt_hci  : start_up starting async portion
,09-12 09:35:28.559  4388  4408 I bt_hci  : event_finish_startup
,09-12 09:35:28.559  4388  4408 I bt_hci_h4: hal_open
,09-12 09:35:28.559  4388  4408 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 09:35:28.567  4388  4408 I bt_userial_vendor: device fd = 51 open
,09-12 09:35:28.594   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 09:35:28.598   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 09:35:28.599   873  1327 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-12 09:35:28.600  4388  4408 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 09:35:28.602   873   893 I DreamManagerService: Entering dreamland.
,09-12 09:35:28.604   873   893 I PowerManagerService: Dozing...
,09-12 09:35:28.606   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 09:35:28.631  4388  4408 D bt_hwcfg: Chipset BCM4354A2
,09-12 09:35:28.631  4388  4408 D bt_hwcfg: Target name = [BCM4354A2]
09-12 09:35:28.632  4388  4408 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 09:35:28.663   375  1275 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 09:35:28.663   375  1275 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 09:35:28.666   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 09:35:28.672   873  1304 E native  : do suspend false
,09-12 09:35:28.688  1926  4411 D NfcService: Discovery configuration equal, not updating.
,09-12 09:35:28.716   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 09:35:28.725   873  1304 E native  : do suspend true
,09-12 09:35:28.797   375  1451 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 09:35:28.798   375  1451 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 09:35:29.305  4388  4408 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-12 09:35:29.307  4388  4408 D bt_hwcfg: Settlement delay -- 100 ms
09-12 09:35:29.307  4388  4408 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 09:35:29.424  4388  4408 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 09:35:29.425  4388  4408 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 09:35:29.455  4388  4408 I bt_hwcfg: vendor lib fwcfg completed
,09-12 09:35:29.455  4388  4408 I bt_vendor: firmware callback
09-12 09:35:29.455  4388  4408 I bt_hci  : firmware_config_callback
,09-12 09:35:29.468  4388  4415 I bt_btu  : btu_task pending for preload complete event
,09-12 09:35:29.469  4388  4415 I bt_btu_task: Bluetooth chip preload is complete
,09-12 09:35:29.469  4388  4415 I bt_btu  : btu_task received preload complete event
,09-12 09:35:29.476  4388  4415 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 09:35:29.477  4388  4415 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 09:35:29.478  4388  4415 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 09:35:29.607  4388  4415 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393cd9d
,09-12 09:35:29.607  4388  4415 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393cd9d 
,09-12 09:35:29.619  4388  4404 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 09:35:29.621  4388  4404 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 09:35:29.622  4388  4404 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 09:35:29.625  4388  4404 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 09:35:29.630  4388  4404 D BluetoothAdapterProperties: Scan Mode:20
,09-12 09:35:29.630  4388  4404 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 09:35:29.631  4388  4404 D bt_hci  : do_postload posting postload work item
,09-12 09:35:29.631  4388  4408 I bt_hci  : event_postload
,09-12 09:35:29.631  4388  4408 I bt_vendor: sco_config_cb
,09-12 09:35:29.631  4388  4408 I bt_hci  : sco_config_callback postload finished.
09-12 09:35:29.635  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:29.635  4388  4404 D bt_bte_conf: Device ID record 1 : primary
,09-12 09:35:29.635  4388  4404 D bt_bte_conf:   vendorId            = 000f
09-12 09:35:29.636  4388  4404 D bt_bte_conf:   vendorIdSource      = 0001
09-12 09:35:29.636  4388  4404 D bt_bte_conf:   product             = 1200
09-12 09:35:29.636  4388  4404 D bt_bte_conf:   version             = 1436
09-12 09:35:29.637  4388  4404 D bt_bte_conf:   clientExecutableURL = 
09-12 09:35:29.637  4388  4404 D bt_bte_conf:   serviceDescription  = 
,09-12 09:35:29.637  4388  4404 D bt_bte_conf:   documentationURL    = 
09-12 09:35:29.638  4388  4404 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 09:35:29.638  4388  4401 D bt_stack_manager: event_start_up_stack finished
09-12 09:35:29.639  4388  4400 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 09:35:29.640  4388  4400 D BluetoothAdapterProperties: Setting state to 15
,09-12 09:35:29.641  4388  4400 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 09:35:29.641  4388  4408 I bt_vendor: low_power_mode_cb
09-12 09:35:29.644  4388  4400 I BluetoothAdapterState: Entering BleOnState
,09-12 09:35:29.649  4388  4400 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 09:35:29.649  4388  4400 D BluetoothAdapterProperties: Setting state to 11
09-12 09:35:29.649  4388  4400 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 09:35:29.656  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:29.656  4388  4388 D HeadsetService: Received start request. Starting profile...
09-12 09:35:29.657  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:29.660  4388  4388 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 09:35:29.661  4388  4388 D HeadsetStateMachine: make
,09-12 09:35:29.668  4388  4400 I BluetoothAdapterState: Entering PendingCommandState
09-12 09:35:29.669  4388  4388 D HeadsetStateMachine: max_hf_connections = 1
09-12 09:35:29.669  4388  4388 I bt_bluedroid: get_profile_interface handsfree
09-12 09:35:29.670  4388  4404 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 09:35:29.671  4388  4404 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-12 09:35:29.672  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:29.673  4388  4388 D A2dpService: Received start request. Starting profile...
09-12 09:35:29.674  4388  4388 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 09:35:29.674  4388  4388 I bt_bluedroid: get_profile_interface avrcp
,09-12 09:35:29.680  4388  4388 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 09:35:29.680  4388  4388 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 09:35:29.680  4388  4388 D A2dpStateMachine: make
,09-12 09:35:29.681  4388  4388 I bt_bluedroid: get_profile_interface a2dp
,09-12 09:35:29.682  4388  4404 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-12 09:35:29.684  4388  4424 D A2dpStateMachine: Enter Disconnected: -2
09-12 09:35:29.685  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 09:35:29.685  4388  4388 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 09:35:29.686  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:29.687  4388  4388 D HidService: Received start request. Starting profile...
09-12 09:35:29.687  4388  4388 I bt_bluedroid: get_profile_interface hidhost
,09-12 09:35:29.687  4388  4388 D HidService: setHidService(): set to: null
,09-12 09:35:29.687  4388  4404 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391e3e5
,09-12 09:35:29.687  4388  4404 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 09:35:29.687  4388  4388 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 09:35:29.688  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
09-12 09:35:29.688  4388  4388 D HealthService: Received start request. Starting profile...
,09-12 09:35:29.690  4388  4388 I bt_bluedroid: get_profile_interface health
09-12 09:35:29.691  4388  4388 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 09:35:29.692  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:29.693  4388  4388 D PanService: Received start request. Starting profile...
09-12 09:35:29.693  4388  4388 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 09:35:29.693  4388  4388 I bt_bluedroid: get_profile_interface pan
09-12 09:35:29.693  4388  4404 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
09-12 09:35:29.695  4388  4388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:29.696  4388  4388 D BluetoothMapService: Received start request. Starting profile...
09-12 09:35:29.696  4388  4388 D BluetoothMapService: start()
09-12 09:35:29.698  4388  4388 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 09:35:29.698  4388  4388 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 09:35:29.698  4388  4388 D BluetoothMapAppObserver: createReceiver()
,09-12 09:35:29.699  4388  4388 D BluetoothMapAppObserver: initObservers()
09-12 09:35:29.699  4388  4388 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 09:35:29.706  4388  4422 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 09:35:29.706  4388  4388 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:29.706  4388  4388 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:29.706  4388  4388 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:29.706  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:29.708  4388  4388 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:29.708  4388  4388 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:29.708  4388  4388 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:29.708  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:29.709  4388  4388 V BluetoothAdapterState: isTurningOff()=false
,09-12 09:35:29.709  4388  4388 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:29.709  4388  4388 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:29.709  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isTurningOff()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isTurningOn()=true
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isBleTurningOn()=false
09-12 09:35:29.710  4388  4388 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 09:35:29.711  4388  4400 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 09:35:29.711  4388  4400 D BluetoothAdapterProperties: ScanMode =  20
09-12 09:35:29.711  4388  4400 D BluetoothAdapterProperties: State =  11
,09-12 09:35:29.713  4388  4400 D BluetoothAdapterProperties: Setting state to 12
09-12 09:35:29.713  4388  4400 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 09:35:29.714  4341  4355 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 09:35:29.716  4388  4404 D BluetoothAdapterProperties: Scan Mode:21
09-12 09:35:29.714  4388  4400 I BluetoothAdapterState: Entering OnState
09-12 09:35:29.716  4388  4404 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 09:35:29.717   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:29.717  1357  1971 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 09:35:29.719  4341  4341 D BluetoothA2dp: Proxy object connected
09-12 09:35:29.719  1357  1357 D BluetoothA2dp: Proxy object connected
,09-12 09:35:29.720   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:29.720  4341  4355 D BluetoothMap: onBluetoothStateChange: up=true
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:29.720  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 09:35:29.722  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 09:35:29.725  4388  4388 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 09:35:29.726  4388  4388 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 09:35:29.726  1357  1971 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 09:35:29.727  4388  4388 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 09:35:29.729  4388  4388 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 09:35:29.730  1357  1370 D BluetoothPan: onBluetoothStateChange on: true
,09-12 09:35:29.731  4388  4388 D ObexServerSockets: Succeed to create listening sockets 
,09-12 09:35:29.731  4388  4388 D ObexServerSockets0: startAccept()
09-12 09:35:29.731  4388  4388 D ObexServerSockets0: prepareForNewConnect()
,09-12 09:35:29.731  1357  1382 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 09:35:29.733  1941  1957 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:29.733   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 09:35:29.734  4341  4352 D BluetoothPan: onBluetoothStateChange on: true
09-12 09:35:29.734  4388  4388 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 09:35:29.734  4388  4388 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 09:35:29.736  1357  1357 D BluetoothMap: Proxy object connected
,09-12 09:35:29.736  1357  1357 D MapProfile: Bluetooth service connected
09-12 09:35:29.736  1357  1357 D BluetoothMap: getConnectedDevices()
09-12 09:35:29.736  4341  4341 D BluetoothMap: Proxy object connected
09-12 09:35:29.736  4341  4341 D MapProfile: Bluetooth service connected
09-12 09:35:29.736  4388  4430 D ObexServerSockets0: Accepting socket connection...
,09-12 09:35:29.736  4388  4431 D ObexServerSockets0: Accepting socket connection...
09-12 09:35:29.736  4341  4355 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 09:35:29.737  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 09:35:29.737  1357  1357 D PanProfile: Bluetooth service connected
09-12 09:35:29.738   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 09:35:29.739   873   873 D BluetoothA2dp: Proxy object connected
,09-12 09:35:29.739  1357  1382 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 09:35:29.736  4341  4341 D BluetoothMap: getConnectedDevices()
,09-12 09:35:29.740  1357  1971 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 09:35:29.742  4341  4355 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 09:35:29.742  1357  1357 D BluetoothInputDevice: Proxy object connected
09-12 09:35:29.742  1357  1357 D HidProfile: Bluetooth service connected
,09-12 09:35:29.744  4341  4352 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 09:35:29.745   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 09:35:29.746  4388  4388 D BluetoothMapService: onReceive
,09-12 09:35:29.746  4388  4388 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 09:35:29.747  4388  4388 D BluetoothMapService: STATE_ON
,09-12 09:35:29.748  4341  4341 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 09:35:29.748  4341  4341 D PanProfile: Bluetooth service connected
09-12 09:35:29.748  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:29.749  4341  4341 D BluetoothInputDevice: Proxy object connected
09-12 09:35:29.749  4341  4341 D HidProfile: Bluetooth service connected
,09-12 09:35:29.755  4341  4341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 09:35:29.760  4341  4341 D DockEventReceiver: finishStartingService: stopping service
,09-12 09:35:29.761  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 09:35:29.773  4341  4341 D BluetoothPbap: Proxy object connected
,09-12 09:35:29.773  1357  1357 D BluetoothPbap: Proxy object connected
09-12 09:35:29.773  4341  4341 D PbapServerProfile: Bluetooth service connected
09-12 09:35:29.773  1357  1357 D PbapServerProfile: Bluetooth service connected
,09-12 09:35:29.781  4388  4388 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 09:35:29.782  4388  4388 D ObexServerSockets0: prepareForNewConnect()
,09-12 09:35:29.786  4388  4437 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 09:35:29.804  4388  4441 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 09:35:29.806  4388  4441 I BtOppRfcommListener: Accept thread started.
,09-12 09:35:29.819  1941  1960 D BluetoothHeadset: Proxy object connected
,09-12 09:35:29.820  4341  4355 D BluetoothHeadset: Proxy object connected
09-12 09:35:29.820   873   873 D BluetoothHeadset: Proxy object connected
09-12 09:35:29.820   873   873 D BluetoothHeadset: Proxy object connected
09-12 09:35:29.820   873   873 D BluetoothHeadset: Proxy object connected
,09-12 09:35:29.820   873   890 D BluetoothHeadset: Proxy object connected
09-12 09:35:29.820  1357  1382 D BluetoothHeadset: Proxy object connected
09-12 09:35:29.821  1357  1357 D HeadsetProfile: Bluetooth service connected
,09-12 09:35:29.823  4341  4341 D HeadsetProfile: Bluetooth service connected
,09-12 09:35:29.833  1941  2059 D BluetoothHeadset: Proxy object connected
,09-12 09:35:29.833   873   890 D BluetoothHeadset: Proxy object connected
,09-12 09:35:29.840  1357  1370 D BluetoothHeadset: Proxy object connected
,09-12 09:35:29.840  1357  1357 D HeadsetProfile: Bluetooth service connected
,09-12 09:35:29.843  4341  4352 D BluetoothHeadset: Proxy object connected
,09-12 09:35:29.844  4341  4341 D HeadsetProfile: Bluetooth service connected
,09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:30.248  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 09:35:30.255  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:30.258  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:30.258  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d8671b added. We now have 8 listener(s)
09-12 09:35:30.259  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:30.264   873  1674 D WifiService: setWifiEnabled: false pid=3846, uid=10000
09-12 09:35:30.264   873  1674 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 09:35:30.278  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:30.279   873  1933 D WifiService: setWifiEnabled: true pid=3846, uid=10000
09-12 09:35:30.279   873  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 09:35:30.294   873  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:30.310  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 09:35:30.314   873  1304 D WifiConfigStore: loaded 0 passpoint configs
,09-12 09:35:30.315   873  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 09:35:30.316   873  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 09:35:30.316  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:30.317   873  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 09:35:30.318   873  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 09:35:30.318   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 09:35:30.318   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 09:35:30.339   873  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.05 delta 1000 -> 1000
,09-12 09:35:30.339   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 09:35:30.340   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 09:35:30.342   371   872 D CommandListener: Setting iface cfg
,09-12 09:35:30.346   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 09:35:30.346   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 09:35:30.355   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 09:35:30.355   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 09:35:30.359   873  1304 E native  : do suspend true
,09-12 09:35:30.389   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 09:35:30.389   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 09:35:30.397   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 09:35:30.443   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 09:35:30.449  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 09:35:30.897  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 09:35:30.944  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 09:35:30.945  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 09:35:30.954   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 09:35:30.963   873  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 09:35:30.963   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 09:35:30.964   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 09:35:30.991   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 09:35:31.012   371   872 D CommandListener: Setting iface cfg
09-12 09:35:31.016   873  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 09:35:31.032   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 09:35:31.054   873  4449 D DhcpClient: Receive thread started
,09-12 09:35:31.143   873  1304 E native  : do suspend false
,09-12 09:35:31.165   873  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 09:35:31.178   873  4449 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-12 09:35:31.179   873  1868 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-12 09:35:31.183   873  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 09:35:31.198   873  4449 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 09:35:31.200   873  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 09:35:31.205   371   872 D CommandListener: Setting iface cfg
,09-12 09:35:31.216   873  1868 D DhcpClient: Scheduling renewal in 86399s
09-12 09:35:31.217   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 09:35:31.219   873  1304 E native  : do suspend true
,09-12 09:35:31.248   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 09:35:31.252   873  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 09:35:31.254   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 09:35:31.256   873  1306 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 09:35:31.269   873  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 09:35:31.299  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 09:35:31.304  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 09:35:31.308  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 09:35:31.308  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 09:35:31.310  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c8a2312 Bundle[{}]
,09-12 09:35:31.311  3846  3894 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 09:35:31.312  3846  3894 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 09:35:31.312  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 09:35:31.313  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 09:35:31.313  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 09:35:31.314  3846  3894 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 09:35:31.318  3846  3894 I System.out: Running OutgoingSocketThread
,09-12 09:35:31.320  3846  4454 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 435)
,09-12 09:35:31.321  3846  4454 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37806
,09-12 09:35:31.321  3846  4454 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 09:35:31.330   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 09:35:31.330   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 09:35:31.332   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 09:35:31.334   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 09:35:31.336   873  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 09:35:31.347   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 09:35:31.354   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 09:35:31.355   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-12 09:35:31.355   873  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 09:35:31.356   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 09:35:31.356   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-12 09:35:31.356   873  1306 D ConnectivityService:    accepting network in place of null
,09-12 09:35:31.358   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 09:35:31.378   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153815, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 09:35:31.403   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 09:35:31.439   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 09:35:31.446   873  4447 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 09:35:31.447   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 09:35:31.448   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 09:35:31.456   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 09:35:31.456   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:31.462  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:31.465  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:31.477  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 09:35:31.484  1725  1725 D SystemUpdateService: onCreate
,09-12 09:35:31.488  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 09:35:31.501  1725  4461 I SystemUpdateService: active receiver: enabled
,09-12 09:35:31.507  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 09:35:31.510   873  4447 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 07:35:31 GMT], X-Android-Received-Millis=[1473665731510], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473665731485]}
,09-12 09:35:31.511   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 09:35:31.511   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-12 09:35:31.511   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 09:35:31.512   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 09:35:31.514  1725  4461 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-12 09:35:31.518  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 09:35:31.519  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 09:35:31.521  4032  4032 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 09:35:31.526  1725  4464 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 09:35:31.526  1725  4464 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 09:35:31.528  4032  4032 D SprintDMHelper: simOperator: 
,09-12 09:35:31.528  4032  4032 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 09:35:31.532  1725  4464 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 09:35:31.515  1725  2418 I iu.UploadsManager: num queued entries: 0
,09-12 09:35:31.555  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:31.557  1725  4461 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 09:35:31.557  1725  4461 I SystemUpdateService: now status is 0 (complete)
09-12 09:35:31.557  1725  4461 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 09:35:31.557  1725  4461 I SystemUpdateService: file has been verified
,09-12 09:35:31.557  1725  4461 I SystemUpdateService: OTA package size = 12249756
,09-12 09:35:31.559  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:31.566  1725  2418 I iu.UploadsManager: num updated entries: 0
,09-12 09:35:31.574  1725  2418 I iu.SyncManager: NEXT; no task
,09-12 09:35:31.582  1725  4461 I SystemUpdateService: showing system update notification
,09-12 09:35:31.594  1725  1725 D SystemUpdateService: onDestroy
,09-12 09:35:31.605  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 09:35:31.605  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 09:35:31.605  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:31.606  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:31.623  1725  4464 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-12 09:35:31.706  3966  4467 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 09:35:32.321  3846  3894 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 436)
09-12 09:35:32.322  3846  3894 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 436)
,09-12 09:35:32.331  3846  3894 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,09-12 09:35:32.333  3846  3894 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 09:35:32.334  3846  3894 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,09-12 09:35:32.340  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.341  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7050b8 added. We now have 2 listener(s)
,09-12 09:35:32.342  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 09:35:32.343  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:35:32.343  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:32.343  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:32.343  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aba9e91 added. We now have 9 listener(s)
09-12 09:35:32.343  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.344  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 09:35:32.347  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:32.355  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:32.358  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:32.359  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 09:35:32.359  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 09:35:32.359  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c59f7 added. We now have 3 listener(s)
,09-12 09:35:32.361  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 09:35:32.361  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:35:32.361  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 09:35:32.362  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:32.362  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@635c064 added. We now have 10 listener(s)
,09-12 09:35:32.362  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:32.362  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:32.362  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 09:35:32.362  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:32.362  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.362  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.363  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 09:35:32.363  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.363  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7050b8 removed from the list
,09-12 09:35:32.363  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.363  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aba9e91 removed from the list
,09-12 09:35:32.365  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:32.365  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 09:35:32.365  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.366  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.366  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.369  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 09:35:32.369  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.369  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:32.369  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aba9e91 not in the list
09-12 09:35:32.369  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:32.369  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.380  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.380  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 09:35:32.380  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.380  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@635c064 removed from the list
,09-12 09:35:32.380  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.380  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.380  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.380  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 09:35:32.380  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c59f7 removed from the list
09-12 09:35:32.381  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.381  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d992cd added. We now have 2 listener(s)
09-12 09:35:32.382  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:32.383  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 09:35:32.383  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 09:35:32.383  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:32.383  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:32.384  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec2782 added. We now have 9 listener(s)
09-12 09:35:32.384  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.384  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 09:35:32.387  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:32.391  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:32.394  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:32.394  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 09:35:32.394  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 09:35:32.395  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c07ed0 added. We now have 3 listener(s)
,09-12 09:35:32.397  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:32.398  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 09:35:32.398  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:35:32.398  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:32.399  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:32.399  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1798ec9 added. We now have 10 listener(s)
,09-12 09:35:32.399  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.400  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:32.400  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 09:35:32.400  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 09:35:32.400  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:32.400  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 09:35:32.401  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:32.405  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 09:35:32.405  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 09:35:32.409  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 09:35:32.410  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 09:35:32.410  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 09:35:32.414  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 09:35:32.414  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 09:35:32.414  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 09:35:32.415  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:32.419  4388  4433 D BtGatt.GattService: registerClient() - UUID=d0e60f9d-7a84-4d91-b872-2d077500c7b5
,09-12 09:35:32.420  4388  4404 D BtGatt.GattService: onClientRegistered() - UUID=d0e60f9d-7a84-4d91-b872-2d077500c7b5, clientIf=5
,09-12 09:35:32.421  3846  3857 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 09:35:32.422  4388  4399 D BtGatt.GattService: start scan with filters
,09-12 09:35:32.426  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 09:35:32.426  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 09:35:32.426  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 09:35:32.426  4388  4407 D BtGatt.ScanManager: handling starting scan
09-12 09:35:32.426  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 09:35:32.429  4388  4407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11e4486
,09-12 09:35:32.429  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 09:35:32.430  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 09:35:32.430  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 09:35:32.431  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 09:35:32.433  4388  4404 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 09:35:32.433  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.435  4388  4407 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 09:35:32.435  3846  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
09-12 09:35:32.435  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:32.435  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 09:35:32.435  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.435  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 09:35:32.435  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 09:35:32.435  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 09:35:32.435  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 09:35:32.436  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 09:35:32.436  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 09:35:32.436  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 09:35:32.437  3846  3894 D BluetoothAdapter: STATE_ON
09-12 09:35:32.438  4388  4433 D BtGatt.GattService: stopScan() - queue size =1
,09-12 09:35:32.440  4388  4399 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 09:35:32.440  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 09:35:32.440  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 09:35:32.440  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 09:35:32.441  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 09:35:32.441  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 09:35:32.442  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 09:35:32.443  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 09:35:32.443  4388  4404 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 09:35:32.443  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 09:35:32.443  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 09:35:32.443  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.443  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:32.444  4388  4407 D BtGatt.ScanManager: Starting BLE batch scan
09-12 09:35:32.444  4388  4407 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 09:35:32.445  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 09:35:32.445  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 09:35:32.445  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:32.446   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-12 09:35:32.447  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:32.447  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 09:35:32.447  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:32.448  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.448  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:32.448  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:32.448  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.448  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d992cd removed from the list
,09-12 09:35:32.448  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.448  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec2782 removed from the list
09-12 09:35:32.448  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:32.448  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.449  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.449  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.451  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.451  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.451  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.451  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec2782 not in the list
09-12 09:35:32.451  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.451  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.452  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.452  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.452  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.452  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1798ec9 removed from the list
09-12 09:35:32.452  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:32.452  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.452  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.453  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 09:35:32.453  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c07ed0 removed from the list
09-12 09:35:32.453  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.453  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4034e85 added. We now have 2 listener(s)
09-12 09:35:32.455  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 09:35:32.455  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 09:35:32.456  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 09:35:32.456  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:32.456  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73324da added. We now have 9 listener(s)
09-12 09:35:32.456  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:32.456  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 09:35:32.458  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:32.463  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:32.465  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:32.465  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 09:35:32.465  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.466  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f557e8 added. We now have 3 listener(s)
09-12 09:35:32.466  4388  4404 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 09:35:32.466  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.469  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:32.469  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 09:35:32.469  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:35:32.469  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 09:35:32.469  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:32.469  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@baf4e01 added. We now have 10 listener(s)
09-12 09:35:32.469  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.469  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:32.470  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:32.470  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 09:35:32.470  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 09:35:32.471  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:32.471  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 09:35:32.472  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:32.472  4388  4404 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 09:35:32.472  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.474  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 09:35:32.474  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 09:35:32.477  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 09:35:32.479  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 09:35:32.479  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 09:35:32.480  4388  4404 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 09:35:32.481  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.481  4388  4407 D BtGatt.ScanManager: stopping BLe Batch
,09-12 09:35:32.482  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 09:35:32.482  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 09:35:32.482  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 09:35:32.483  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:32.485  4388  4429 D BtGatt.GattService: registerClient() - UUID=743805bc-728a-46b0-9484-f79a0ba6ef46
09-12 09:35:32.485  4388  4404 D BtGatt.GattService: onClientRegistered() - UUID=743805bc-728a-46b0-9484-f79a0ba6ef46, clientIf=5
,09-12 09:35:32.485  3846  3858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 09:35:32.486  4388  4399 D BtGatt.GattService: start scan with filters
09-12 09:35:32.486  4388  4404 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 09:35:32.486  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.486  4388  4407 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 09:35:32.488  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 09:35:32.488  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 09:35:32.488  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 09:35:32.488  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 09:35:32.490  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:32.490  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 09:35:32.491  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 09:35:32.492  4388  4404 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 09:35:32.492  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.492  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 09:35:32.493  4388  4407 D BtGatt.ScanManager: handling starting scan
,09-12 09:35:32.494  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 09:35:32.494  3846  3894 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 09:35:32.495  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 09:35:32.495  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:32.495  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:32.495  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:32.495  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.495  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 09:35:32.495  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.495  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4034e85 removed from the list
09-12 09:35:32.495  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.496  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73324da removed from the list
09-12 09:35:32.496  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:32.496  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 09:35:32.496  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.496  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 09:35:32.496  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.496  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:32.497  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.497  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.497  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.497  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73324da not in the list
,09-12 09:35:32.497  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 09:35:32.497  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 09:35:32.497  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 09:35:32.498  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 09:35:32.498  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 09:35:32.498  4388  4404 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 09:35:32.498  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.499  3846  3894 D BluetoothAdapter: STATE_ON
09-12 09:35:32.499  4388  4407 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 09:35:32.500  4388  4433 D BtGatt.GattService: stopScan() - queue size =1
,09-12 09:35:32.501  4388  4421 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 09:35:32.501  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 09:35:32.501  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 09:35:32.501  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 09:35:32.501  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 09:35:32.501  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 09:35:32.502  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:32.502  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 09:35:32.502  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 09:35:32.502  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 09:35:32.503  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.504  4388  4404 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 09:35:32.504  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:32.504  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.504  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:32.504  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:32.504  4388  4407 D BtGatt.ScanManager: Starting BLE batch scan
09-12 09:35:32.504  4388  4407 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 09:35:32.504  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.504  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.504  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.505  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@baf4e01 removed from the list
09-12 09:35:32.505  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.505  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.505  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.505  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.505  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f557e8 removed from the list
09-12 09:35:32.505  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.506  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1c93d added. We now have 2 listener(s)
09-12 09:35:32.507  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 09:35:32.507  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:35:32.507  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:32.507  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:32.507  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e017532 added. We now have 9 listener(s)
09-12 09:35:32.507  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.508  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 09:35:32.510  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:32.513  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:32.514  4388  4404 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 09:35:32.514  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.515  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:32.515  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 09:35:32.515  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.516  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@993c00 added. We now have 3 listener(s)
,09-12 09:35:32.517  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:32.518  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 09:35:32.518  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 09:35:32.518  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:32.519  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:32.519  4388  4404 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 09:35:32.519  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.519  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@986bc39 added. We now have 10 listener(s)
09-12 09:35:32.519  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.519  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:32.520  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 09:35:32.520  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 09:35:32.520  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 09:35:32.520  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 09:35:32.520  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 09:35:32.522  3846  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 09:35:32.522  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 09:35:32.525  4388  4404 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 09:35:32.525  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.525  4388  4407 D BtGatt.ScanManager: stopping BLe Batch
09-12 09:35:32.526  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 09:35:32.526  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 09:35:32.526  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 09:35:32.529  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 09:35:32.529  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 09:35:32.529  3846  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 09:35:32.529  3846  3894 D BluetoothAdapter: STATE_ON
,09-12 09:35:32.531  4388  4399 D BtGatt.GattService: registerClient() - UUID=25b472c6-0ce6-45c3-8028-59b550dc5f7b
,09-12 09:35:32.531  4388  4404 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 09:35:32.531  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.531  4388  4404 D BtGatt.GattService: onClientRegistered() - UUID=25b472c6-0ce6-45c3-8028-59b550dc5f7b, clientIf=5
,09-12 09:35:32.532  4388  4407 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 09:35:32.532  3846  3857 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 09:35:32.532  4388  4433 D BtGatt.GattService: start scan with filters
09-12 09:35:32.535  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 09:35:32.535  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 09:35:32.535  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 09:35:32.535  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 09:35:32.537  4388  4404 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 09:35:32.537  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.537  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:32.537  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 09:35:32.537  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 09:35:32.538  4388  4407 D BtGatt.ScanManager: handling starting scan
,09-12 09:35:32.539  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 09:35:32.542  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:32.542  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:32.542  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 09:35:32.542  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.543  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.543  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 09:35:32.543  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.543  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1c93d removed from the list
,09-12 09:35:32.543  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.543  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e017532 removed from the list
09-12 09:35:32.543  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-12 09:35:32.543  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:32.543  4388  4404 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 09:35:32.543  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.543  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.543  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 09:35:32.543  4388  4407 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 09:35:32.543  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.544  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 09:35:32.544  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.544  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.544  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.544  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e017532 not in the list
,09-12 09:35:32.544  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 09:35:32.544  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 09:35:32.545  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 09:35:32.545  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 09:35:32.545  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 09:35:32.545  3846  3894 D BluetoothAdapter: STATE_ON
09-12 09:35:32.546  4388  4399 D BtGatt.GattService: stopScan() - queue size =1
,09-12 09:35:32.546  4388  4433 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 09:35:32.547  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 09:35:32.547  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 09:35:32.547  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 09:35:32.547  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 09:35:32.547  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 09:35:32.548  4388  4404 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 09:35:32.548  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.548  4388  4407 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 09:35:32.548  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:32.548  4388  4407 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 09:35:32.548  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 09:35:32.549  3846  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 09:35:32.549  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 09:35:32.549  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.550  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.550  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.550  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:32.550  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:32.550  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@986bc39 removed from the list
09-12 09:35:32.550  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 09:35:32.550  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.550  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.550  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 09:35:32.550  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.550  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.550  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@993c00 removed from the list
09-12 09:35:32.551  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 09:35:32.551  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70de2f5 added. We now have 2 listener(s)
09-12 09:35:32.552  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 09:35:32.552  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 09:35:32.552  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 09:35:32.553  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 09:35:32.553  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8e788a added. We now have 9 listener(s)
09-12 09:35:32.553  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 09:35:32.553  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 09:35:32.555  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 09:35:32.558  4388  4404 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 09:35:32.558  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 09:35:32.559  3846  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 09:35:32.562  3846  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 09:35:32.563  3846  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 09:35:32.563  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 09:35:32.563  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8228b18 added. We now have 3 listener(s)
,09-12 09:35:32.564  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:32.566  4388  4404 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 09:35:32.567  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.567  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 09:35:32.567  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 09:35:32.568  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 09:35:32.568  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 09:35:32.568  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 09:35:32.568  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a6b971 added. We now have 10 listener(s)
,09-12 09:35:32.570  3846  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 09:35:32.570  3846  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 09:35:32.570  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 09:35:32.571  3846  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 09:35:32.571  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 09:35:32.571  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:32.571  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 09:35:32.571  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 09:35:32.571  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70de2f5 removed from the list
,09-12 09:35:32.571  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 09:35:32.571  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8e788a removed from the list
,09-12 09:35:32.571  3846  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 09:35:32.571  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.572  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 09:35:32.572  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.572  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 09:35:32.573  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 09:35:32.573  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.573  3846  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8e788a not in the list
09-12 09:35:32.573  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.573  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 09:35:32.574  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 09:35:32.574  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 09:35:32.574  3846  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 09:35:32.574  3846  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a6b971 removed from the list
09-12 09:35:32.574  3846  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 09:35:32.574  4388  4404 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 09:35:32.574  3846  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 09:35:32.574  3846  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 09:35:32.574  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 09:35:32.574  3846  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 09:35:32.574  3846  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8228b18 removed from the list
09-12 09:35:32.574  4388  4407 D BtGatt.ScanManager: stopping BLe Batch
09-12 09:35:32.575  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 09:35:32.575  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 09:35:32.575  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 09:35:32.575  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:32.575  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 09:35:32.575  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 09:35:32.580  4388  4404 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 09:35:32.580  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.581  4388  4407 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 09:35:32.581  3846  4473 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: My test thread name)
09-12 09:35:32.581  3846  4473 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 449, thread name: My test thread name)
09-12 09:35:32.581  3846  4473 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 449, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 09:35:32.583  3846  4474 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
09-12 09:35:32.583  3846  4474 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 451, thread name: My test thread name)
,09-12 09:35:32.583  3846  4474 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 09:35:32.585  3846  3894 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 09:35:32.585  3846  3894 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 09:35:32.585  3846  3894 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 09:35:32.585  3846  3894 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 09:35:32.585  3846  3894 D com.test.thalitest.ThaliTestRunner: Total duration: 22898 ms
,09-12 09:35:32.587  4388  4404 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 09:35:32.587  4388  4404 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 09:35:32.587  3846  3894 I jxcore-log: *Native tests were executed*
09-12 09:35:32.587  3846  3894 I jxcore-log: 
09-12 09:35:32.587  3846  3894 I jxcore-log: Total number of executed tests:  80
09-12 09:35:32.587  3846  3894 I jxcore-log: 
,09-12 09:35:32.587  3846  3894 I jxcore-log: Number of passed tests:  80
09-12 09:35:32.587  3846  3894 I jxcore-log: 
09-12 09:35:32.587  3846  3894 I jxcore-log: Number of failed tests:  0
09-12 09:35:32.587  3846  3894 I jxcore-log: 
09-12 09:35:32.587  3846  3894 I jxcore-log: Number of ignored tests:  0
09-12 09:35:32.587  3846  3894 I jxcore-log: 
09-12 09:35:32.588  3846  3894 I jxcore-log: Total duration:  22898
09-12 09:35:32.588  3846  3894 I jxcore-log: 
,09-12 09:35:32.590  3846  3894 I jxcore-log: Unit Test app is loaded
09-12 09:35:32.590  3846  3894 I jxcore-log: 
09-12 09:35:32.596  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.596  3846  3894 I jxcore-log: 
09-12 09:35:32.598  3846  3846 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 09:35:32.600  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.600  3846  3894 I jxcore-log: 
09-12 09:35:32.601  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.601  3846  3894 I jxcore-log: 
09-12 09:35:32.602  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.602  3846  3894 I jxcore-log: 
,09-12 09:35:32.603  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.603  3846  3894 I jxcore-log: 
09-12 09:35:32.604  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.604  3846  3894 I jxcore-log: 
09-12 09:35:32.606  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.606  3846  3894 I jxcore-log: 
09-12 09:35:32.607  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.607  3846  3894 I jxcore-log: 
09-12 09:35:32.608  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.608  3846  3894 I jxcore-log: 
,09-12 09:35:32.609  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 09:35:32.609  3846  3894 I jxcore-log: 
09-12 09:35:32.610  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 09:35:32.610  3846  3894 I jxcore-log: 
09-12 09:35:32.611  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 09:35:32.611  3846  3894 I jxcore-log: 
09-12 09:35:32.612  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.612  3846  3894 I jxcore-log: 
09-12 09:35:32.612  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.612  3846  3894 I jxcore-log: 
09-12 09:35:32.613  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.613  3846  3894 I jxcore-log: 
,09-12 09:35:32.613  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.613  3846  3894 I jxcore-log: 
09-12 09:35:32.614  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.614  3846  3894 I jxcore-log: 
,09-12 09:35:32.614  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.614  3846  3894 I jxcore-log: 
09-12 09:35:32.615  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.615  3846  3894 I jxcore-log: 
,09-12 09:35:32.616  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.616  3846  3894 I jxcore-log: 
,09-12 09:35:32.617  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.617  3846  3894 I jxcore-log: 
09-12 09:35:32.617  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 09:35:32.617  3846  3894 I jxcore-log: 
09-12 09:35:32.618  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 09:35:32.618  3846  3894 I jxcore-log: 
,09-12 09:35:32.618  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 09:35:32.618  3846  3894 I jxcore-log: 
,09-12 09:35:32.618  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.618  3846  3894 I jxcore-log: 
09-12 09:35:32.619  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.619  3846  3894 I jxcore-log: 
,09-12 09:35:32.620  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.620  3846  3894 I jxcore-log: 
09-12 09:35:32.620  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.620  3846  3894 I jxcore-log: 
,09-12 09:35:32.620  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.620  3846  3894 I jxcore-log: 
,09-12 09:35:32.621  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 09:35:32.621  3846  3894 I jxcore-log: 
,09-12 09:35:32.624  3846  3894 I jxcore-log: My device name is: motorola-Nexus 6
09-12 09:35:32.624  3846  3894 I jxcore-log: 
,09-12 09:35:32.946  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 09:35:33.005  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 09:35:33.051  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 09:35:33.148  2096  2634 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 09:35:34.121   873  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-12 09:35:36.601  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-12 09:35:36.601  3846  3894 I jxcore-log: 
,09-12 09:35:37.519  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-12 09:35:37.519  3846  3894 I jxcore-log: 
,09-12 09:35:37.545  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-12 09:35:37.545  3846  3894 I jxcore-log: 
,09-12 09:35:37.550  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-12 09:35:37.550  3846  3894 I jxcore-log: 
,09-12 09:35:37.566  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-12 09:35:37.566  3846  3894 I jxcore-log: 
,09-12 09:35:37.571  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-12 09:35:37.571  3846  3894 I jxcore-log: 
,09-12 09:35:39.361   873  1306 D ConnectivityService: handlePromptUnvalidated 102
,09-12 09:35:40.720  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-12 09:35:40.720  3846  3894 I jxcore-log: 
,09-12 09:35:40.732  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-12 09:35:40.732  3846  3894 I jxcore-log: 
,09-12 09:35:40.740  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-12 09:35:40.740  3846  3894 I jxcore-log: 
,09-12 09:35:40.769  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:40.896  1511  4478 I VacuumService: Vacuum at: now=1473665740896 tag=VacuumService
,09-12 09:35:40.931  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-12 09:35:40.931  3846  3894 I jxcore-log: 
,09-12 09:35:41.021  1511  4479 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 09:35:41.034  1511  4479 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 09:35:41.196  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:41.203  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:41.205  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:35:41.249  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:35:41.250  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:35:41.250  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:41.250  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:41.289  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 09:35:41.290  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 09:35:41.290  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 09:35:41.465  1511  4479 W Uploader:  no longer exists, so no auth token.
,09-12 09:35:41.800  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-12 09:35:41.800  3846  3894 I jxcore-log: 
,09-12 09:35:42.051  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-12 09:35:42.051  3846  3894 I jxcore-log: 
,09-12 09:35:42.058  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-12 09:35:42.058  3846  3894 I jxcore-log: 
,09-12 09:35:42.255  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-12 09:35:42.255  3846  3894 I jxcore-log: 
,09-12 09:35:42.277  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-12 09:35:42.277  3846  3894 I jxcore-log: 
,09-12 09:35:42.281  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-12 09:35:42.281  3846  3894 I jxcore-log: 
,09-12 09:35:42.288  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-12 09:35:42.288  3846  3894 I jxcore-log: 
,09-12 09:35:42.304  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-12 09:35:42.304  3846  3894 I jxcore-log: 
,09-12 09:35:42.324  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-12 09:35:42.324  3846  3894 I jxcore-log: 
,09-12 09:35:42.408  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-12 09:35:42.408  3846  3894 I jxcore-log: 
,09-12 09:35:42.413  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-12 09:35:42.413  3846  3894 I jxcore-log: 
,09-12 09:35:42.429  1511  4479 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 09:35:42.429  1511  4479 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 09:35:42.429  1511  4479 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:42.429  1511  4479 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:42.440  3846  3894 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-12 09:35:42.440  3846  3894 I jxcore-log: 
,09-12 09:35:42.443  1511  4479 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 09:35:42.443  1511  4479 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 09:35:42.443  1511  4479 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 09:35:42.450  3846  3894 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 09:35:42.452  3846  3894 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 09:35:42.452  3846  3894 I jxcore-log: 
09-12 09:35:42.454  3846  3894 I jxcore-log: thaliTape.begin
09-12 09:35:42.454  3846  3894 I jxcore-log: 
,09-12 09:35:42.494  3846  3894 I jxcore-log: thaliTape.testServer created
09-12 09:35:42.494  3846  3894 I jxcore-log: 
,09-12 09:35:42.497  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 09:35:42.497  3846  3894 I jxcore-log: 
,09-12 09:35:42.498  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 09:35:42.498  3846  3894 I jxcore-log: 
,09-12 09:35:42.498  3846  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 09:35:42.498  3846  3894 I jxcore-log: 
09-12 09:35:42.499  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 09:35:42.499  3846  3894 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-12 09:35:42.499  3846  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 09:35:42.499  3846  3894 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-12 09:35:42.968  1511  4479 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 09:35:42.968  1511  4479 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 09:35:42.968  1511  4479 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:35:42.968  1511  4479 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:42.982  1511  4479 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 09:35:42.982  1511  4479 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 09:35:42.982  1511  4479 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 09:35:43.457  1511  4479 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 09:35:43.457  1511  4479 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 09:35:43.457  1511  4479 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:35:43.458  1511  4479 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:35:43.475  1511  4479 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 09:35:43.475  1511  4479 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 09:35:43.475  1511  4479 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 09:36:01.639  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:36:01.641  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:36:01.659  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:36:01.659  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 09:36:01.659  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:36:01.659  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:01.672  4122  4495 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 09:36:01.672  4122  4495 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at blb.a(PG:3937)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at czp.a(PG:18188)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:36:01.672  4122  4495 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	... 12 more
09-12 09:36:01.672  4122  4495 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at fal.a(PG:38)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:36:01.672  4122  4495 E HttpOperation: 	... 14 more
,09-12 09:36:01.696  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:36:01.733  3570  4493 V KeepSync: Connecting to GoogleApiClient
,09-12 09:36:01.740   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 09:36:01.762  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:36:01.763  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:36:01.763  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:36:01.763  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:01.768  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:36:01.768  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:36:01.768  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:36:01.768  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:01.790  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 09:36:01.790  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 09:36:01.790  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 09:36:01.810  4122  4495 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 09:36:01.810  4122  4495 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	,at jcs.o(PG:406)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	,at hec.a(PG:42)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at hee.a(PG:102)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at czr.a(PG:65)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at kka.a(PG:108)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at czp.a(PG:19176)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:36:01.810  4122  4495 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	... 15 more
09-12 09:36:01.810  4122  4495 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at fal.a(PG:38)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:36:01.810  4122  4495 E HttpOperation: 	... 17 more
,09-12 09:36:01.810  4122  4495 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 09:36:01.810  4122  4495 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at hec.a(PG:42)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at hee.a(PG:102)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at czr.a(PG:65)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at kka.a(PG:108)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	... 15 more
09-12 09:36:01.810  4122  4495 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at fal.a(PG:38)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 09:36:01.810  4122  4495 E ExperimentLoader: 	... 17 more
,09-12 09:36:01.849  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 09:36:01.850  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 09:36:01.850  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:36:01.850  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:01.869  1725  4497 V BaseAuthAsyncOperation: access token request failed
09-12 09:36:01.870  3570  4493 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 09:36:01.921  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 09:36:01.922  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 09:36:01.922  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:36:01.922  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:01.943  3570  4493 E KeepSync: IOException
09-12 09:36:01.943  3570  4493 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 09:36:01.943  3570  4493 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:36:01.943  3570  4493 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 09:36:01.943  3570  4493 E KeepSync: 	... 10 more
09-12 09:36:01.943  3570  4493 W KeepSync: Sync result 2
,09-12 09:36:01.959   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 168104, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:36:01.996   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 168166, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:36:08.174   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=190611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:36:27.654  1871  1972 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-12 09:36:27.654  1871  1972 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 09:36:27.701  1511  1511 I ConfigService: onCreate
,09-12 09:36:32.783  1511  1511 I ConfigService: onDestroy
,09-12 09:36:33.898  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:36:33.901  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:36:33.950  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 09:36:33.950  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:36:33.950  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:36:33.950  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:33.977  4122  4502 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 09:36:33.977  4122  4502 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at blb.a(PG:3937)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at czp.a(PG:18188)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:36:33.977  4122  4502 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	... 12 more
09-12 09:36:33.977  4122  4502 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at fal.a(PG:38)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:36:33.977  4122  4502 E HttpOperation: 	... 14 more
,09-12 09:36:34.049  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:36:34.049  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:36:34.049  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:36:34.049  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:34.072  4122  4502 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 09:36:34.072  4122  4502 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at hec.a(PG:42)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at hee.a(PG:102)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at czr.a(PG:65)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at kka.a(PG:108)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at czp.a(PG:19176)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:36:34.072  4122  4502 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	... 15 more
09-12 09:36:34.072  4122  4502 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at fal.a(PG:38)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:36:34.072  4122  4502 E HttpOperation: 	... 17 more
,09-12 09:36:34.072  4122  4502 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 09:36:34.072  4122  4502 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at hec.a(PG:42)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at hee.a(PG:102)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at czr.a(PG:65)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at kka.a(PG:108)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	... 15 more
09-12 09:36:34.072  4122  4502 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at fal.a(PG:38)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 09:36:34.072  4122  4502 E ExperimentLoader: 	... 17 more
,09-12 09:36:34.204   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 216098, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:36:34.294  3570  4504 V KeepSync: Connecting to GoogleApiClient
09-12 09:36:34.294   873  1980 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 09:36:34.363  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 09:36:34.363  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 09:36:34.363  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:36:34.363  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:34.393  1725  4505 V BaseAuthAsyncOperation: access token request failed
,09-12 09:36:34.394  3570  4504 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 09:36:34.434  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 09:36:34.434  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 09:36:34.434  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:36:34.434  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:36:34.449  3570  4504 E KeepSync: IOException
09-12 09:36:34.449  3570  4504 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 09:36:34.449  3570  4504 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:36:34.449  3570  4504 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 09:36:34.449  3570  4504 E KeepSync: 	... 10 more
,09-12 09:36:34.449  3570  4504 W KeepSync: Sync result 2
,09-12 09:36:34.455   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 216435, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:37:03.436  1511  2191 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 09:37:04.628   873   885 I ActivityManager: Start proc 4507:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-12 09:37:04.649  4507  4507 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-12 09:37:04.792  4507  4507 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-12 09:37:04.820  4507  4507 I BooksApp: Created application version: 3.6.9 (30609)
,09-12 09:37:04.969  4507  4524 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 09:37:05.111  4507  4530 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 09:37:05.153  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:05.162  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:05.203  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 09:37:05.204  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:37:05.204  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:37:05.204  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:37:05.250  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:05.256  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:05.297  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 09:37:05.297  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:37:05.297  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:37:05.297  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:37:05.324  4507  4530 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 09:37:05.327  4507  4524 E BooksSync: Soft error
09-12 09:37:05.327  4507  4524 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:37:05.327  4507  4524 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 09:37:05.328  4507  4524 E BooksSync: Sync error
09-12 09:37:05.328  4507  4524 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:37:05.328  4507  4524 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:37:05.328  4507  4524 I BooksSync: Finished books sync
,09-12 09:37:05.338   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246886, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:37:05.340   873  1927 I ActivityManager: Killing 4190:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 09:37:09.818  4507  4522 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-12 09:37:14.926  4280  4290 D Finsky  : [376] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-12 09:37:14.943  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:14.956  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:14.962  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:15.040  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:37:15.040  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 09:37:15.041  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:37:15.042  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:37:15.116  4280  4290 D Finsky  : [376] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-12 09:37:24.587   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:37:36.771  4507  4536 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 09:37:36.808  4507  4537 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 09:37:36.825  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:36.829  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:36.866  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 09:37:36.866  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:37:36.866  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:37:36.866  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:37:36.898  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:36.900  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:37:36.926  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 09:37:36.926  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:37:36.926  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:37:36.926  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:37:36.946  4507  4537 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 09:37:36.947  4507  4536 E BooksSync: Soft error
09-12 09:37:36.947  4507  4536 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:37:36.947  4507  4536 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:37:36.947  4507  4536 E BooksSync: Sync error
09-12 09:37:36.947  4507  4536 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:37:36.947  4507  4536 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:37:36.947  4507  4536 I BooksSync: Finished books sync
,09-12 09:37:36.961   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279158, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:37:49.133   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=291570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:38:07.387  3570  4544 V KeepSync: Connecting to GoogleApiClient
,09-12 09:38:07.388   873  1385 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 09:38:07.440  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:38:07.447  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:38:07.475  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 09:38:07.475  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 09:38:07.475  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:38:07.475  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:38:07.516  1725  4546 V BaseAuthAsyncOperation: access token request failed
,09-12 09:38:07.517  3570  4544 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 09:38:07.534  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:38:07.534  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:38:07.534  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:38:07.535  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:38:07.558  4122  4545 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 09:38:07.558  4122  4545 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at blb.a(PG:3937)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at czp.a(PG:18188)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:38:07.558  4122  4545 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	... 12 more
09-12 09:38:07.558  4122  4545 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at fal.a(PG:38)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:38:07.558  4122  4545 E HttpOperation: 	... 14 more
,09-12 09:38:07.604  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:38:07.604  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:38:07.604  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:38:07.604  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:38:07.631  4122  4545 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 09:38:07.631  4122  4545 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at hec.a(PG:42)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at hee.a(PG:102)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at czr.a(PG:65)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at kka.a(PG:108)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at czp.a(PG:19176)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:38:07.631  4122  4545 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	... 15 more
09-12 09:38:07.631  4122  4545 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at fal.a(PG:38)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:38:07.631  4122  4545 E HttpOperation: 	... 17 more
,09-12 09:38:07.632  4122  4545 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 09:38:07.632  4122  4545 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at hec.a(PG:42)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at hee.a(PG:102)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at czr.a(PG:65)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at kka.a(PG:108)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	... 15 more
09-12 09:38:07.632  4122  4545 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at fal.a(PG:38)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 09:38:07.632  4122  4545 E ExperimentLoader: 	... 17 more
,09-12 09:38:07.751   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 279970, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:38:07.761  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 09:38:07.761  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 09:38:07.761  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:38:07.761  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:38:07.773  3570  4544 E KeepSync: IOException
09-12 09:38:07.773  3570  4544 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 09:38:07.773  3570  4544 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:38:07.773  3570  4544 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 09:38:07.773  3570  4544 E KeepSync: 	... 10 more
09-12 09:38:07.773  3570  4544 W KeepSync: Sync result 2
,09-12 09:38:07.778   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 280970, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:38:22.027   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:38:39.931  4507  4550 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 09:38:39.971  4507  4551 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 09:38:39.994  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:38:40.000  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:38:40.059  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 09:38:40.060  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:38:40.060  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:38:40.060  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:38:40.097  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:38:40.099  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:38:40.136  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 09:38:40.136  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:38:40.136  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:38:40.136  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:38:40.159  4507  4551 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 09:38:40.161  4507  4550 E BooksSync: Soft error
09-12 09:38:40.161  4507  4550 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:38:40.161  4507  4550 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 09:38:40.163  4507  4550 E BooksSync: Sync error
09-12 09:38:40.163  4507  4550 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:38:40.163  4507  4550 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:38:40.163  4507  4550 I BooksSync: Finished books sync
,09-12 09:38:40.176   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 342165, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:38:46.627   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=349064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:39:19.373   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:39:56.333   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:40:14.677  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:40:14.682  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:40:14.733  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 09:40:14.733  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:40:14.733  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:40:14.734  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:40:14.761  4122  4556 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 09:40:14.761  4122  4556 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at blb.a(PG:3937)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at czp.a(PG:18188)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:40:14.761  4122  4556 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	... 12 more
09-12 09:40:14.761  4122  4556 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at fal.a(PG:38)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:40:14.761  4122  4556 E HttpOperation: 	... 14 more
,09-12 09:40:14.812  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 09:40:14.812  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 09:40:14.813  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:40:14.813  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:40:14.828  4122  4556 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 09:40:14.828  4122  4556 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jdm.a(PG:82)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jcs.o(PG:406)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jcn.a(PG:1379)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jcs.i(PG:143)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at hec.a(PG:42)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at hee.a(PG:102)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at czr.a(PG:65)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at kka.a(PG:108)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at czp.a(PG:19176)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at czp.a(PG:9081)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at czq.run(PG:1686)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:40:14.828  4122  4556 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jdj.a(PG:4091)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jdj.a(PG:1125)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jdm.a(PG:77)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	... 15 more
09-12 09:40:14.828  4122  4556 E HttpOperation: Caused by: faj: BadAuthentication
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at fal.a(PG:38)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	at jdj.a(PG:4089)
09-12 09:40:14.828  4122  4556 E HttpOperation: 	... 17 more
,09-12 09:40:14.828  4122  4556 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 09:40:14.828  4122  4556 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at hec.a(PG:42)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at hee.a(PG:102)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at czr.a(PG:65)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at kka.a(PG:108)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	... 15 more
09-12 09:40:14.828  4122  4556 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at fal.a(PG:38)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 09:40:14.828  4122  4556 E ExperimentLoader: 	... 17 more
,09-12 09:40:14.956   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 436845, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:40:18.470  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:40:18.550  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:40:18.551  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:40:18.551  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:40:18.553  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:40:18.605  1511  1525 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 09:40:18.605  1511  1525 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 09:40:18.605  1511  1525 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 09:40:18.605  1511  1525 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 09:40:18.605  1511  1525 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 09:40:18.605  1511  1525 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 09:40:18.605  1511  1525 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 09:40:18.624  4280  4309 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 09:40:18.624  4280  4309 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 09:40:18.624  4280  4309 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 09:40:18.624  4280  4309 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 09:40:18.624  4280  4309 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 09:40:18.624  4280  4309 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 09:40:18.624  4280  4309 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 09:40:23.666   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=446104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 09:40:43.533   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=465970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:40:45.088  3570  4562 V KeepSync: Connecting to GoogleApiClient
09-12 09:40:45.088   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 09:40:45.161  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:40:45.165  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:40:45.204  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 09:40:45.204  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 09:40:45.204  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:40:45.204  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:40:45.232  1725  4563 V BaseAuthAsyncOperation: access token request failed
,09-12 09:40:45.234  3570  4562 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 09:40:45.316  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 09:40:45.316  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 09:40:45.316  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:40:45.317  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-12 09:40:45.361  3570  4562 E KeepSync: IOException
09-12 09:40:45.361  3570  4562 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 09:40:45.361  3570  4562 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 09:40:45.361  3570  4562 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 09:40:45.361  3570  4562 E KeepSync: 	... 10 more
,09-12 09:40:45.361  3570  4562 W KeepSync: Sync result 2
,09-12 09:40:45.385   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 438368, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:40:48.693   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=471130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:41:13.293   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=495730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:41:15.569  4507  4566 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 09:41:15.606  4507  4567 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 09:41:15.623  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:41:15.626  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:41:15.673  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 09:41:15.673  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 09:41:15.673  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:41:15.674  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:41:15.718  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:41:15.722  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:41:15.764  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 09:41:15.765  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 09:41:15.765  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:41:15.765  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:41:15.794  4507  4567 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 09:41:15.797  4507  4566 E BooksSync: Soft error
09-12 09:41:15.797  4507  4566 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:41:15.797  4507  4566 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 09:41:15.797  4507  4566 E BooksSync: Sync error
09-12 09:41:15.797  4507  4566 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 09:41:15.797  4507  4566 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 09:41:15.798  4507  4566 I BooksSync: Finished books sync
,09-12 09:41:15.813   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 468146, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 09:41:36.440   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:42:00.974   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=543411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:42:45.396  1511  2191 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 09:44:24.147   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=686584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:44:48.760   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=711197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:45:23.973   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=746410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 09:45:48.546   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=770983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:50:29.670   873  1933 I ActivityManager: Start proc 4595:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-12 09:50:29.731  4595  4595 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-12 09:50:29.758  4595  4595 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-12 09:50:29.758  4595  4595 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 09:50:29.758  4595  4595 I GAv4    :   adb logcat -s GAv4
,09-12 09:50:29.773  4595  4595 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 09:50:29.777  4595  4595 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 09:50:29.788  4595  4610 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 09:50:29.879   873  1981 I ActivityManager: Killing 4137:android.process.acore/u0a5 (adj 15): empty #17
,09-12 09:50:31.909  4280  4280 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-12 09:50:31.949  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:31.979  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:31.984  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:31.988  1725  4613 I EventLogService: Opted in for usage reporting
,09-12 09:50:31.988  1725  4613 I EventLogService: Aggregate from 1473664268342 (log), 1473664268342 (data)
,09-12 09:50:32.041  1725  4613 W EventLogAggregator: Unknown tag: snet_gcore
,09-12 09:50:32.041  1725  4613 W EventLogAggregator: Unknown tag: snet_launch_service
,09-12 09:50:32.043  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:50:32.044  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:50:32.044  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:50:32.044  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:50:32.080  4280  4280 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 09:50:32.089  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:32.122  1725  4613 I ServiceDumpSys: dumping service [account]
,09-12 09:50:32.131  1511  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:50:32.131  1511  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:50:32.131  1511  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:50:32.132  1511  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:50:32.178  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:32.245  1511  3069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 09:50:32.246  1511  3069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 09:50:32.246  1511  3069 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 09:50:32.247  1511  3069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:50:32.312  4280  4280 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 09:50:32.631  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:32.695  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-12 09:50:32.695  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 09:50:32.696  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:50:32.696  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:50:32.760  4280  4280 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 09:50:32.762  4280  4280 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-12 09:50:32.767  4280  4280 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-12 09:50:32.779  4280  4280 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,09-12 09:50:32.781  4280  4359 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-12 09:50:36.973   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 09:50:43.080   873  4448 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1065517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 09:50:47.660  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:47.674  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:47.679  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:50:47.718  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:50:47.718  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 09:50:47.718  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:50:47.718  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:50:47.753  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 09:50:47.753  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 09:50:47.754  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-12 09:51:07.937  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:07.944  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:07.945  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:07.969  1511  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 09:51:07.969  1511  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:51:07.969  1511  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:51:07.969  1511  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:51:08.003  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 09:51:08.003  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 09:51:08.004  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-12 09:51:28.409  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:28.426  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:28.433  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:28.516  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:51:28.517  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:51:28.518  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:51:28.518  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:51:28.591  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 09:51:28.592  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 09:51:28.593  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-12 09:51:48.956  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:48.972  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:48.977  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:51:49.053  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:51:49.053  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:51:49.054  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:51:49.054  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:51:49.124  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 09:51:49.125  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 09:51:49.127  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 09:52:09.401  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:52:09.411  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:52:09.414  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:52:09.462  1511  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:52:09.462  1511  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 09:52:09.463  1511  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:52:09.463  1511  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:52:09.513  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 09:52:09.514  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 09:52:09.514  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 09:52:29.736  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:52:29.749  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:52:29.754  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 09:52:29.799  1511  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 09:52:29.799  1511  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 09:52:29.799  1511  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 09:52:29.799  1511  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 09:52:29.833  4280  4280 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 09:52:29.834  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 09:52:29.834  4280  4280 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 09:53:15.538   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-12 09:58:27.860  4639  4639 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 09:58:27.865  4639  4639 D AndroidRuntime: CheckJNI is OFF
09-12 09:58:27.901  4639  4639 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 09:58:27.942  4639  4639 I Radio-JNI: register_android_hardware_Radio DONE
09-12 09:58:27.962  4639  4639 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 09:58:27.975   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 09:58:27.976   873   886 I ActivityManager: Killing 3846:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-12 09:58:28.092   873   896 W PackageSettings: Skipping PackageSetting{5fc9dfb com.example.hello/10273} due to missing metadata
09-12 09:58:28.132   873   883 D GraphicsStats: Buffer count: 2
09-12 09:58:28.132   873  1980 I WindowState: WIN DEATH: Window{e0aee8b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 09:58:28.132   873  1305 D WifiService: Client connection lost with reason: 4
09-12 09:58:28.135   873   896 I art     : Starting a blocking GC Explicit
09-12 09:58:28.166   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 09:58:28.167   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 09:58:28.168   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-12 09:58:28.168   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 09:58:28.168   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.168   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.168   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.168   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 09:58:28.169   873   886 I ActivityManager:   Force finishing activity ActivityRecord{6e41bf0 u0 com.test.thalitest/.MainActivity t4}
09-12 09:58:28.183   873   883 W ActivityManager: Spurious death for ProcessRecord{c8ded6e 0:com.test.thalitest/u0a0}, curProc for 3846: null
09-12 09:58:28.197   873   896 I art     : Explicit concurrent mark sweep GC freed 51562(3MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 29MB/44MB, paused 3.307ms total 61.480ms
09-12 09:58:28.218   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 09:58:28.219  4639  4639 I art     : System.exit called, status: 0
09-12 09:58:28.220  4639  4639 I AndroidRuntime: VM exiting with result code 0.
09-12 09:58:28.235   873   896 I ActivityManager: Start proc 4653:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-12 09:58:28.235   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 09:58:28.251   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 09:58:28.258  4388  4388 D BluetoothMapAppObserver: onReceive
09-12 09:58:28.259  4388  4388 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 09:58:28.260   873  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 09:58:28.264  2096  2311 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 09:58:28.273  3661  3661 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 09:58:28.276  1941  1941 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-12 09:58:28.285  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 09:58:28.322   873  1976 I ActivityManager: Start proc 4669:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 09:58:28.323   873  1924 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3846 uid 10000
09-12 09:58:28.331  1871  1871 I Keyboard.Facilitator: onFinishInput()
09-12 09:58:28.353   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 09:58:28.359  1871  4667 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 09:58:28.361  1871  4667 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 09:58:28.361  1871  4667 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 09:58:28.361  1871  4667 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 09:58:28.361  1871  4667 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 09:58:28.364  1871  4667 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 09:58:28.364  1871  4667 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 09:58:28.365  1871  4667 I Decoder : createOrResetDecoder
09-12 09:58:28.375   873   883 I ActivityManager: Killing 4177:com.google.android.gm/u0a78 (adj 15): empty #17
09-12 09:58:28.392  4669  4669 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-12 09:58:28.414  1511  1511 I ConfigService: onCreate
09-12 09:58:28.423  4669  4669 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 09:58:28.438  1511  4684 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 09:58:28.438  1511  4684 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-12 09:58:28.441  1511  4684 W SQLiteOpenHelper: Opened config.db in read-only mode
09-12 09:58:28.447  4669  4685 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.451  4669  4682 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.451  4669  4682 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.468   873   884 I ActivityManager: Start proc 4686:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-12 09:58:28.476  1871  4667 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-12 09:58:28.490  1954  2027 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 09:58:28.491   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 09:58:28.491   873   885 E PackageManager: Failed to write settings, restoring backup
09-12 09:58:28.491   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 09:58:28.491   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 09:58:28.491   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 09:58:28.491   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 09:58:28.491   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 09:58:28.491   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.491   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.491   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.497   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-12 09:58:28.497   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 09:58:28.497   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 09:58:28.497   873   886 E DropBoxManagerService: 	... 13 more
09-12 09:58:28.503  4686  4686 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-12 09:58:28.507   873   883 I ActivityManager: Start proc 4698:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-12 09:58:28.507  1954  2027 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 09:58:28.507  1954  2027 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1954
09-12 09:58:28.507  1954  2027 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.507  1954  2027 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.509   873  1980 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 09:58:28.510   873  4705 E DropBoxManagerService: Can't write: system_app_crash
09-12 09:58:28.510   873  4705 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 09:58:28.510   873  4705 E DropBoxManagerService: 	... 5 more
09-12 09:58:28.529  1954  2027 I Process : Sending signal. PID: 1954 SIG: 9
09-12 09:58:28.545  1871  4667 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 09:58:28.546  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 09:58:28.547  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 09:58:28.548  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 09:58:28.549  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 09:58:28.550  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 09:58:28.550  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 09:58:28.550  1871  4667 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 09:58:28.550  1871  4667 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 09:58:28.550  1871  4667 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 09:58:28.551  1871  4667 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 09:58:28.551  1871  4667 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 09:58:28.551  1871  4667 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 09:58:28.571  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 09:58:28.573  1511  1511 D AndroidRuntime: Shutting down VM
09-12 09:58:28.574  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
09-12 09:58:28.574  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
09-12 09:58:28.574  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 09:58:28.574  1511  1511 E AndroidRuntime: 	... 8 more
09-12 09:58:28.576  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
09-12 09:58:28.576   873  4717 E DropBoxManagerService: Can't write: system_app_crash
09-12 09:58:28.576   873  4717 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 09:58:28.576   873  4717 E DropBoxManagerService: 	... 5 more
09-12 09:58:28.633   873  1924 I ActivityManager: Killing 4163:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
09-12 09:58:28.654   873  1291 W InputDispatcher: channel 'ffaae99 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-12 09:58:28.654   873  1291 E InputDispatcher: channel 'ffaae99 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-12 09:58:28.657   873  1305 D WifiService: Client connection lost with reason: 4
09-12 09:58:28.662   873  1981 D GraphicsStats: Buffer count: 1
09-12 09:58:28.662   873  1981 I WindowState: WIN DEATH: Window{ffaae99 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-12 09:58:28.662   873  1981 W InputDispatcher: Attempted to unregister already unregistered input channel 'ffaae99 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-12 09:58:28.666   873  2339 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1954) has died
09-12 09:58:28.666   873  2339 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 09:58:28.668   873  2339 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 09:58:28.680  4669  4682 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.688  4669  4685 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 09:58:28.688  4669  4685 E AndroidRuntime: Process: android.process.acore, PID: 4669
09-12 09:58:28.688  4669  4685 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 09:58:28.688  4669  4685 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 09:58:28.690  4669  4682 I Process : Sending signal. PID: 4669 SIG: 9
09-12 09:58:28.691   873   886 I ActivityManager: Start proc 4721:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 09:58:28.692   873  1980 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
09-12 09:58:28.693   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-12 09:58:28.693   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
09-12 09:58:28.693   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
09-12 09:58:28.695  1725  4719 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@fe5bac0
09-12 09:58:28.700   873  4727 E DropBoxManagerService: Can't write: system_app_crash
09-12 09:58:28.700   873  4727 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 09:58:28.700   873  4727 E DropBoxManagerService: 	... 5 more
09-12 09:58:28.705  1725  1725 W RocketImpressions: ClearcutLogger connection suspended: 1
09-12 09:58:28.716   873   883 I ActivityManager: Start proc 4734:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider

```
