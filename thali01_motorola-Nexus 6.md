#### Test 80761374ecfdb04_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 16:37:12.901  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:12.908  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 16:37:12.910  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 16:37:12.948  1498  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 16:37:12.948  1498  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 16:37:12.949  1498  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:37:12.949  1498  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 16:37:12.975  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 16:37:12.975  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 16:37:12.976  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-16 16:37:13.536  3756  3756 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 16:37:13.541  3756  3756 D AndroidRuntime: CheckJNI is OFF
08-16 16:37:13.581   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-16 16:37:13.584  3756  3756 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 16:37:13.634  3756  3756 I Radio-JNI: register_android_hardware_Radio DONE
08-16 16:37:13.657  3756  3756 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 16:37:13.661   873  1991 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 16:37:13.716  2017  2031 W SearchService: Abort, client detached.
08-16 16:37:13.722  3756  3756 D AndroidRuntime: Shutting down VM
08-16 16:37:13.726  2017  2017 I HotwordDetector: Closing mic
08-16 16:37:13.726  2017  2319 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d11de5
08-16 16:37:13.727  2017  2332 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 16:37:13.735   873  1957 I ActivityManager: Start proc 3765:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 16:37:13.776   376  2334 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 16:37:13.777   376  2334 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 16:37:13.782   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 16:37:13.783  2017  2327 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 16:37:13.783  2017  2330 I MicroRecognitionRnrImpl: Detection finished
08-16 16:37:13.828  3765  3765 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 16:37:13.859  3765  3765 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 16:37:13.867  3765  3765 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2974-2978)
08-16 16:37:13.867  3765  3765 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:37:13.884  3765  3765 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ef45447}
08-16 16:37:13.884  3765  3765 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:37:13.885  3765  3765 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 16:37:13.894  3765  3765 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 16:37:13.895  3765  3765 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 16:37:13.928  3765  3765 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 16:37:13.946  3765  3765 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 16:37:13.946  3765  3765 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 16:37:13.946  3765  3765 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 16:37:13.946  3765  3765 I Adreno  : Build Date                       : 10/20/15
08-16 16:37:13.946  3765  3765 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 16:37:13.946  3765  3765 I Adreno  : Local Branch                     : M14
08-16 16:37:13.946  3765  3765 I Adreno  : Remote Branch                    : 
08-16 16:37:13.946  3765  3765 I Adreno  : Remote Branch                    : 
08-16 16:37:13.946  3765  3765 I Adreno  : Reconstruct Branch               : 
,08-16 16:37:14.000   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b41f1:true
,08-16 16:37:14.041  3765  3765 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 16:37:14.055  3765  3765 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 16:37:14.135  3765  3803 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 16:37:14.149  3765  3790 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 16:37:14.197  3765  3803 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 16:37:14.281   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +559ms
,08-16 16:37:14.300  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-16 16:37:14.349  3765  3765 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3765
,08-16 16:37:14.463  3765  3765 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 16:37:14.591   873  1957 I ActivityManager: Killing 3190:com.google.android.gm/u0a78 (adj 15): empty #17
,08-16 16:37:14.643   873  1957 I ActivityManager: Killing 3082:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-16 16:37:14.645  3765  3805 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1678837456
,08-16 16:37:14.652  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 16:37:14.652  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 16:37:14.652  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 16:37:14.652  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 16:37:14.652  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 16:37:14.652  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@baec82a added. We now have 1 listener(s)
,08-16 16:37:14.656  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 16:37:14.656  3765  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 16:37:14.657  3765  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 16:37:14.657  3765  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 16:37:14.661  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1188591 added. We now have 1 listener(s)
08-16 16:37:14.661  3765  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:37:14.665   873  1307 D WifiService: New client listening to asynchronous messages
,08-16 16:37:14.667  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:37:14.667  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 16:37:14.667  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 16:37:14.667  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-16 16:37:14.667  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 16:37:14.704  3765  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:14.705  3765  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 16:37:14.709  3765  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:14.709  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:37:14.709  3765  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 16:37:14.709  3765  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:37:14.710  3765  3805 I io.jxcore.node.LifeCycleMonitor: start: OK,
,08-16 16:37:14.712  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:14.713  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:14.903  3765  3765 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 16:37:15.246  3765  3775 I art     : Background sticky concurrent mark sweep GC freed 76867(7MB) AllocSpace objects, 18(1604KB) LOS objects, 28% free, 23MB/32MB, paused 1.044ms total 115.701ms
,08-16 16:37:15.779  3765  3815 W jxcore-log: Initializing JXcore engine
,08-16 16:37:15.779  3765  3815 W jxcore-log: JXcore engine is ready
,08-16 16:37:15.839  3815  3815 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 16:37:15.839  3815  3815 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10779]" dev="sockfs" ino=10779 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 16:37:15.839  3815  3815 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 16:37:15.839  3815  3815 W Thread-321: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25886]" dev="sockfs" ino=25886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 16:37:15.867  3765  3815 W jxcore-log: Starting JXcore engine
,08-16 16:37:16.009  3765  3815 W jxcore-log: Platform android
08-16 16:37:16.009  3765  3815 W jxcore-log: 
,08-16 16:37:16.009  3765  3815 W jxcore-log: Process ARCH arm
08-16 16:37:16.009  3765  3815 W jxcore-log: 
,08-16 16:37:16.283  3765  3815 I jxcore-log: JXcore Cordova bridge is ready!
08-16 16:37:16.283  3765  3815 I jxcore-log: 
08-16 16:37:16.284  3765  3815 W jxcore-log: JXcore engine is started
,08-16 16:37:16.292  3765  3805 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 16:37:16.297  3765  3765 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 16:37:18.222  3561  3818 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 16:37:18.248  3561  3819 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 16:37:18.259  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:18.261  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-16 16:37:18.284  1498  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 16:37:18.285  1498  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 16:37:18.285  1498  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 16:37:18.285  1498  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:18.301  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:18.302  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:18.316  1498  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 16:37:18.316  1498  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 16:37:18.316  1498  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:37:18.316  1498  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:18.326  3561  3819 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 16:37:18.327  3561  3818 E BooksSync: Soft error
08-16 16:37:18.327  3561  3818 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 16:37:18.327  3561  3818 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 16:37:18.327  3561  3818 E BooksSync: Sync error
08-16 16:37:18.327  3561  3818 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 16:37:18.327  3561  3818 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 16:37:18.327  3561  3818 I BooksSync: Finished books sync
,08-16 16:37:18.330   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127279, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 16:37:32.231  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 16:37:32.231  3765  3815 I jxcore-log: 
,08-16 16:37:32.233  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 16:37:32.233  3765  3815 I jxcore-log: 
,08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:32.241  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:37:32.246  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:37:32.249  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 16:37:32.249  3765  3815 I jxcore-log: 
,08-16 16:37:32.251  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 16:37:32.251  3765  3815 I jxcore-log: 
,08-16 16:37:32.586  3765  3815 I jxcore-log: Running unit tests
08-16 16:37:32.586  3765  3815 I jxcore-log: 
,08-16 16:37:32.587  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:37:32.587  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f62e81d added. We now have 2 listener(s)
,08-16 16:37:32.588  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 16:37:32.588  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 16:37:32.588  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:37:32.589  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:37:32.589  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@343da92 added. We now have 2 listener(s)
,08-16 16:37:32.589  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:37:32.589  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:37:32.592  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:32.598  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:37:32.600  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:37:32.600  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:37:32.601  3765  3815 D ExecuteNativeTests: Running unit tests
,08-16 16:37:32.603  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:32.606  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:32.707  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:37:32.707  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 added. We now have 3 listener(s)
08-16 16:37:32.708  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 16:37:32.708  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 16:37:32.708  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:37:32.708  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 16:37:32.708  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 added. We now have 3 listener(s)
08-16 16:37:32.708  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:37:32.710  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:37:32.716  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:32.730  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:37:32.736  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:37:32.737  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:37:32.741  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 16:37:32.743  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 16:37:32.743  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 16:37:32.744  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:32.745  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 16:37:32.751  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:32.756  3765  3815 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 16:37:32.757  3765  3815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 16:37:32.757  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 16:37:32.758  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:32.758  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:32.758  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:32.760  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:32.761  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:32.761  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:37:32.763  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:32.763  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.763  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:37:32.764  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 16:37:32.764  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 removed from the list
08-16 16:37:32.764  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:32.765  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 removed from the list
08-16 16:37:32.765  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:37:32.765  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:32.767  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:32.767  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:32.769  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:37:32.770  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:32.770  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:32.770  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:32.773  3765  3815 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 16:37:32.774  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:32.774  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:32.774  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:32.775  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:32.775  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.775  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:32.775  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:32.775  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:32.775  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:32.775  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:32.775  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.775  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:32.775  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.775  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:32.777  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:32.777  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:32.777  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:32.777  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:32.782  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 16:37:32.783  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 16:37:32.784  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 16:37:32.785  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 16:37:32.785  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 16:37:32.785  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:32.785  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:32.785  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:32.785  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:32.785  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.785  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:32.785  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:32.785  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:32.786  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:32.786  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:32.786  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.786  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:32.786  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:32.786  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:32.787  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:32.787  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:32.787  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:32.787  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:32.788  3765  3815 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 16:37:32.789  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:32.795  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:37:32.797  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:32.797  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:37:32.798  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:37:32.799  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:37:32.799  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:37:32.799  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:37:32.799  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:37:32.799  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:37:32.801  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:37:32.802  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 16:37:32.802  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 16:37:32.807  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 16:37:32.809  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 16:37:32.809  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 16:37:32.812  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 16:37:32.814  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 16:37:32.815  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 16:37:32.815  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 16:37:32.816  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 16:37:32.817  3765  3815 D BluetoothAdapter: STATE_ON
08-16 16:37:32.824  2687  2891 D BtGatt.GattService: registerClient() - UUID=2055a1b6-a067-49c3-a3c6-2a1393d353c4
08-16 16:37:32.826  2687  2741 D BtGatt.GattService: onClientRegistered() - UUID=2055a1b6-a067-49c3-a3c6-2a1393d353c4, clientIf=5
08-16 16:37:32.826  3765  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 16:37:32.827  2687  2704 D BtGatt.GattService: start scan with filters
08-16 16:37:32.831  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 16:37:32.831  2687  2745 D BtGatt.ScanManager: handling starting scan
08-16 16:37:32.831  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 16:37:32.831  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 16:37:32.831  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 16:37:32.833  2687  2745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:37:32.834  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 16:37:32.835  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 16:37:32.836  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 16:37:32.837  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 16:37:32.840  3765  3815 I io.jxcore.node.ConnectionHelper: start: OK
08-16 16:37:32.841  2687  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 16:37:32.841  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:32.842  2687  2745 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 16:37:32.849  2687  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 16:37:32.849  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:32.849  2687  2745 D BtGatt.ScanManager: Starting BLE batch scan
08-16 16:37:32.849  2687  2745 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 16:37:32.864  2687  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 16:37:32.864  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:32.870  2687  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 16:37:32.870  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:33.337  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 16:37:33.338  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:37:33.338  3765  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 16:37:34.411  2687  2687 D BtGatt.ScanManager: awakened up at time 143523
,08-16 16:37:34.461  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:34.490  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 16:37:34.490  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:34.490  2687  2741 D BtGatt.GattService: current time is 143601770668
08-16 16:37:34.490  2687  2741 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -61, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:37:34.493  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 16:37:34.494  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 16:37:34.494  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 16:37:34.494  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-16 16:37:34.495  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 16:37:34.495  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:37:34.571  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:34.579  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:34.584  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:34.613  1498  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 16:37:34.613  1498  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 16:37:34.613  1498  2007 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-16 16:37:34.613  1498  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:34.648  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 16:37:34.649  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 16:37:34.649  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 16:37:35.996  2687  2687 D BtGatt.ScanManager: awakened up at time 145107
,08-16 16:37:36.000  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:36.009  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 16:37:36.010  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:37.429   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 16:37:37.508  2687  2687 D BtGatt.ScanManager: awakened up at time 146620
,08-16 16:37:37.511  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:37.563  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 16:37:37.564  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:37.564  2687  2741 D BtGatt.GattService: current time is 146675971756
,08-16 16:37:37.565  2687  2741 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -90, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 16:37:37.566  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 16:37:37.568  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 16:37:37.569  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 16:37:37.570  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:37:37.571  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-16 16:37:37.572  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 16:37:37.850  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:37:37.850  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:37.851  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 16:37:37.851  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:37.851  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 16:37:37.852  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:37:37.852  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:37:37.852  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 16:37:37.853  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 16:37:37.855  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 16:37:37.857  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 16:37:37.860  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:37:37.864  2687  2889 D BtGatt.GattService: stopScan() - queue size =1
,08-16 16:37:37.867  2687  2891 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 16:37:37.868  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 16:37:37.869  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 16:37:37.869  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 16:37:37.869  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 16:37:37.870  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 16:37:37.873  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:37:37.875  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 16:37:37.875  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,08-16 16:37:37.876  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:37:37.878  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:37:37.883  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:37:37.883  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:37:37.883  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:37.884  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:37:37.884  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 16:37:37.884  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:37:37.884  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:37.884  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:37.885  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:37.885  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:37.886  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:37.888  2687  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 16:37:37.888  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:37.888  2687  2745 D BtGatt.ScanManager: stopping BLe Batch
,08-16 16:37:37.897  2687  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 16:37:37.897  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:37.898  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:37.905  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 16:37:37.905  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:38.384  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 16:37:40.462   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 16:37:41.037   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 16:37:41.046  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-16 16:37:41.067   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 16:37:41.067   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 16:37:41.067   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 16:37:41.067   873   893 I Adreno  : Local Branch                     : M14
08-16 16:37:41.067   873   893 I Adreno  : Remote Branch                    : 
08-16 16:37:41.067   873   893 I Adreno  : Remote Branch                    : 
08-16 16:37:41.067   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 16:37:41.125   281  1295 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (202 us)
,08-16 16:37:41.765  3765  3765 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 16:37:41.765  3765  3765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 16:37:41.823   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 16:37:41.827  3765  3765 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@951a355 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@66b2acb, 16908290=android.view.AbsSavedState$1@66b2acb}, android:focusedViewId=100}]}]
,08-16 16:37:41.827  3765  3765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-16 16:37:41.828  3765  3765 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 16:37:41.828  3765  3765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 16:37:41.835   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 16:37:41.838   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 16:37:41.838   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-16 16:37:41.838   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 16:37:42.068   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 16:37:42.071   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 16:37:42.077   873  1331 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-16 16:37:42.082   873   893 I DreamManagerService: Entering dreamland.
08-16 16:37:42.084   873   893 I PowerManagerService: Dozing...
,08-16 16:37:42.086   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 16:37:42.125   376  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-16 16:37:42.126   376  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 16:37:42.139   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:37:42.150  1928  3836 D NfcService: Discovery configuration equal, not updating.
,08-16 16:37:42.154   873  1305 E native  : do suspend false
,08-16 16:37:42.168   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 16:37:42.181   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:37:42.184   873  1305 E native  : do suspend true
,08-16 16:37:42.264   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 16:37:42.264   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 16:37:42.646   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 16:37:42.887  3765  3815 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 16:37:42.893  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:42.908  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:37:42.914  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:37:42.915  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:37:42.916  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 16:37:42.916  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 16:37:42.916  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:37:42.917  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:42.917  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 16:37:42.924  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:42.927  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 16:37:42.927  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 16:37:42.933  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:42.941  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 16:37:42.943  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 16:37:42.943  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 16:37:42.954  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 16:37:42.954  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 16:37:42.955  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 16:37:42.957  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:37:42.964  2687  3834 D BtGatt.GattService: registerClient() - UUID=4e76f2b6-6e7c-4814-b8b5-9567a198399a
,08-16 16:37:42.966  2687  2741 D BtGatt.GattService: onClientRegistered() - UUID=4e76f2b6-6e7c-4814-b8b5-9567a198399a, clientIf=5
08-16 16:37:42.967  3765  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 16:37:42.968  2687  2701 D BtGatt.GattService: start scan with filters
,08-16 16:37:42.977  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 16:37:42.977  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 16:37:42.977  2687  2745 D BtGatt.ScanManager: handling starting scan
,08-16 16:37:42.978  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 16:37:42.978  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 16:37:42.990  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 16:37:42.991  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 16:37:42.991  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 16:37:42.994  2687  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 16:37:42.995  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:42.996  2687  2745 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 16:37:42.999  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 16:37:43.009  3765  3815 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 16:37:43.011  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:43.011  3765  3815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 16:37:43.011  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:43.012  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 16:37:43.012  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:43.012  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 16:37:43.012  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:37:43.012  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:37:43.012  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 16:37:43.012  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 16:37:43.012  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 16:37:43.013  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 16:37:43.013  3765  3815 D BluetoothAdapter: STATE_ON
08-16 16:37:43.014  2687  2891 D BtGatt.GattService: stopScan() - queue size =1
,08-16 16:37:43.014  2687  2889 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 16:37:43.014  2687  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 16:37:43.015  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:43.015  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:37:43.015  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 16:37:43.015  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 16:37:43.015  2687  2745 D BtGatt.ScanManager: Starting BLE batch scan
08-16 16:37:43.015  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 16:37:43.015  2687  2745 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 16:37:43.015  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 16:37:43.016  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:37:43.016  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 16:37:43.016  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 16:37:43.016  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:37:43.017  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:37:43.019  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 16:37:43.019  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:37:43.019  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:37:43.019  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:43.019  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:43.019  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:37:43.020  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:43.020  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:43.020  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:43.020  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:43.020  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:43.020  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:43.020  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:43.022  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:43.022  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:43.022  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:43.022  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:43.023  3765  3815 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 16:37:43.025  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:37:43.031  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:37:43.033  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:37:43.033  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:37:43.034  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 16:37:43.034  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 16:37:43.034  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 16:37:43.034  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:37:43.034  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 16:37:43.036  2687  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 16:37:43.036  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:37:43.036  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:43.038  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 16:37:43.038  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 16:37:43.038  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:37:43.044  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 16:37:43.044  2687  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 16:37:43.044  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 16:37:43.044  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:43.045  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 16:37:43.048  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 16:37:43.048  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 16:37:43.048  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 16:37:43.049  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:37:43.052  2687  2704 D BtGatt.GattService: registerClient() - UUID=79573ab2-6f1b-42db-ba91-06f09f7cdcf5
,08-16 16:37:43.053  2687  2741 D BtGatt.GattService: onClientRegistered() - UUID=79573ab2-6f1b-42db-ba91-06f09f7cdcf5, clientIf=5
,08-16 16:37:43.053  3765  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 16:37:43.053  2687  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 16:37:43.053  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:43.053  2687  2889 D BtGatt.GattService: start scan with filters
08-16 16:37:43.054  2687  2745 D BtGatt.ScanManager: stopping BLe Batch,
,08-16 16:37:43.057  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 16:37:43.057  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 16:37:43.058  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 16:37:43.058  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 16:37:43.060  2687  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 16:37:43.060  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:43.061  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:43.063  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 16:37:43.064  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 16:37:43.064  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 16:37:43.066  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 16:37:43.068  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 16:37:43.068  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:43.069  3765  3815 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 16:37:43.071  2687  2745 D BtGatt.ScanManager: handling starting scan
,08-16 16:37:43.077  2687  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 16:37:43.077  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:43.077  2687  2745 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 16:37:43.083  2687  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 16:37:43.083  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:43.084  2687  2745 D BtGatt.ScanManager: Starting BLE batch scan
08-16 16:37:43.084  2687  2745 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 16:37:43.094  2687  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 16:37:43.094  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:43.100  2687  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 16:37:43.100  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:43.565  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 16:37:43.565  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 16:37:43.566  3765  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 16:37:44.607  2687  2687 D BtGatt.ScanManager: awakened up at time 153718
,08-16 16:37:44.610  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:44.660  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-16 16:37:44.661  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:44.663  2687  2741 D BtGatt.GattService: current time is 153774851532
,08-16 16:37:44.664  2687  2741 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -81, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 16:37:44.666  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 16:37:44.667  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 16:37:44.668  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 16:37:44.669  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:37:44.670  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 16:37:44.671  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 16:37:46.163  2687  2687 D BtGatt.ScanManager: awakened up at time 155274
,08-16 16:37:46.169  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:46.199  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-16 16:37:46.199  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:46.200  2687  2741 D BtGatt.GattService: current time is 155311437917
08-16 16:37:46.200  2687  2741 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 16:37:46.201  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 16:37:46.232  1877  2630 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 16:37:47.701  2687  2687 D BtGatt.ScanManager: awakened up at time 156813
,08-16 16:37:47.704  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:37:47.755  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 16:37:47.755  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:47.756  2687  2741 D BtGatt.GattService: current time is 156867252350
,08-16 16:37:47.757  2687  2741 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -90, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 16:37:47.757  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-16 16:37:47.758  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 16:37:47.759  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-16 16:37:47.760  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:37:47.761  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-16 16:37:47.762  2687  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 16:37:48.069  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:37:48.070  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:48.070  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 16:37:48.070  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:48.071  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 16:37:48.071  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:37:48.071  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:37:48.072  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 16:37:48.072  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 16:37:48.073  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 16:37:48.073  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 16:37:48.076  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:37:48.078  2687  2701 D BtGatt.GattService: stopScan() - queue size =1
,08-16 16:37:48.080  2687  2891 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 16:37:48.081  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:37:48.082  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 16:37:48.082  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 16:37:48.082  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 16:37:48.083  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 16:37:48.086  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:37:48.087  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 16:37:48.087  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 16:37:48.087  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:37:48.089  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 16:37:48.091  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:37:48.091  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:37:48.091  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:37:48.095  2687  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 16:37:48.095  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:48.095  2687  2745 D BtGatt.ScanManager: stopping BLe Batch
,08-16 16:37:48.101  2687  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 16:37:48.101  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:37:48.101  2687  2745 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-16 16:37:48.111  2687  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 16:37:48.111  2687  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:37:48.534  3028  3842 V KeepSync: Connecting to GoogleApiClient
08-16 16:37:48.534   873  1991 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 16:37:48.592  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 16:37:48.592  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:48.592  3765  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 16:37:48.613  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:48.618  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:48.659  1498  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 16:37:48.659  1498  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 16:37:48.659  1498  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:37:48.659  1498  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:48.677  1498  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 16:37:48.677  1498  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 16:37:48.677  1498  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:37:48.677  1498  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:48.679  1681  3844 V BaseAuthAsyncOperation: access token request failed
,08-16 16:37:48.681  3028  3842 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 16:37:48.709  2985  3843 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 16:37:48.709  2985  3843 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jdm.a(PG:82)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jcs.o(PG:406)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jcn.a(PG:1379)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jcs.i(PG:143)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at blb.a(PG:3937)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at czp.a(PG:18188)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at czp.a(PG:9081)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at czq.run(PG:1686)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 16:37:48.709  2985  3843 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jdj.a(PG:4091)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jdj.a(PG:1125)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jdm.a(PG:77)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	... 12 more
08-16 16:37:48.709  2985  3843 E HttpOperation: Caused by: faj: BadAuthentication
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at fal.a(PG:38)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	at jdj.a(PG:4089)
08-16 16:37:48.709  2985  3843 E HttpOperation: 	... 14 more
,08-16 16:37:48.788  1498  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 16:37:48.788  1498  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 16:37:48.788  1498  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:37:48.788  1498  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:48.796  1498  1989 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 16:37:48.797  1498  1989 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 16:37:48.797  1498  1989 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 16:37:48.797  1498  1989 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:48.820  3028  3842 E KeepSync: IOException
08-16 16:37:48.820  3028  3842 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 16:37:48.820  3028  3842 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 16:37:48.820  3028  3842 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 16:37:48.820  3028  3842 E KeepSync: 	... 10 more
,08-16 16:37:48.820  3028  3842 W KeepSync: Sync result 2
,08-16 16:37:48.836   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131724, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 16:37:48.838  2985  3843 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 16:37:48.838  2985  3843 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jdm.a(PG:82)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jcs.o(PG:406)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jcn.a(PG:1379)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jcs.i(PG:143)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at hec.a(PG:42)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at hee.a(PG:102)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at czr.a(PG:65)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at kka.a(PG:108)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at czp.a(PG:19176)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at czp.a(PG:9081)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at czq.run(PG:1686)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 16:37:48.838  2985  3843 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jdj.a(PG:4091)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jdj.a(PG:1125)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jdm.a(PG:77)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	... 15 more
08-16 16:37:48.838  2985  3843 E HttpOperation: Caused by: faj: BadAuthentication,
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at fal.a(PG:38)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	at jdj.a(PG:4089)
08-16 16:37:48.838  2985  3843 E HttpOperation: 	... 17 more
08-16 16:37:48.838  2985  3843 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 16:37:48.838  2985  3843 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at hec.a(PG:42)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at hee.a(PG:102)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at czr.a(PG:65)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at kka.a(PG:108)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	... 15 more
08-16 16:37:48.838  2985  3843 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at fal.a(PG:38)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 16:37:48.838  2985  3843 E ExperimentLoader: 	... 17 more
,08-16 16:37:48.947   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131479, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 16:37:53.093  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:37:53.093  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:53.093  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:37:53.094  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:37:53.095  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.095  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 16:37:53.096  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
,08-16 16:37:53.096  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.096  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:53.097  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:37:53.097  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.099  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.099  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.102  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.103  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.103  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.103  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.106  3765  3815 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 16:37:53.108  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.108  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:53.108  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.109  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.109  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.109  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.110  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.110  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.110  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.111  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.111  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.111  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.111  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.113  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.116  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.116  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.116  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.117  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:53.119  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 16:37:53.120  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.120  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:53.120  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.121  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-16 16:37:53.121  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.121  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.121  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.122  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.122  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.122  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.122  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.123  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.123  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.123  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 16:37:53.126  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.126  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:37:53.126  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.126  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:53.128  3765  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 16:37:53.129  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.129  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:53.129  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.130  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:37:53.131  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.131  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.131  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.131  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.132  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.132  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.132  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.132  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.133  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.133  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.135  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 16:37:53.136  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.136  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.136  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:53.138  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 16:37:53.138  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.139  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:53.139  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:37:53.140  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.140  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.140  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 16:37:53.140  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.141  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.141  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.141  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:37:53.141  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.142  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.142  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.142  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.144  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:37:53.145  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.145  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.145  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:53.147  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 16:37:53.147  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:37:53.148  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:37:53.148  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 16:37:53.148  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:53.149  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:53.149  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 16:37:53.149  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:37:53.149  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:37:53.149  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.149  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:53.150  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.151  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.152  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.152  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.152  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.152  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.152  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.152  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.152  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.152  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.152  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.153  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.154  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.154  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.154  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.154  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.155  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 16:37:53.156  3765  3815 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 16:37:53.156  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 16:37:53.163  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 16:37:53.163  3765  3815 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 16:37:53.163  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 16:37:53.164  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 16:37:53.164  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 16:37:53.165  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 16:37:53.166  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 16:37:53.166  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 16:37:53.166  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 16:37:53.167  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 16:37:53.167  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 16:37:53.168  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 16:37:53.168  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 16:37:53.169  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 16:37:53.169  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 16:37:53.170  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 16:37:53.171  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 16:37:53.173  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 16:37:53.173  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 16:37:53.173  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 16:37:53.173  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 16:37:53.174  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-16 16:37:53.174  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 16:37:53.174  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-16 16:37:53.175  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 16:37:53.175  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 16:37:53.175  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-16 16:37:53.175  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 16:37:53.176  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 16:37:53.176  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 16:37:53.176  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-16 16:37:53.176  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 16:37:53.177  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-16 16:37:53.178  3765  3815 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 16:37:53.178  3765  3815 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-16 16:37:53.178  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 16:37:53.179  3765  3815 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 16:37:53.179  3765  3815 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 16:37:53.179  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 16:37:53.180  3765  3815 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 16:37:53.180  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 16:37:53.185  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-16 16:37:53.187  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 16:37:53.187  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-16 16:37:53.189  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 16:37:53.189  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-16 16:37:53.189  3765  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
08-16 16:37:53.189  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-16 16:37:53.190  3765  3815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 16:37:53.190  3765  3815 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 16:37:53.192  3765  3846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:37:53.193  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:37:53.193  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:53.193  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:37:53.194  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:37:53.194  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.194  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.195  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 16:37:53.197  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
,08-16 16:37:53.197  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:53.197  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.197  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:37:53.197  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.197  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.197  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:53.197  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.199  3765  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
,08-16 16:37:53.199  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.199  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.199  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.199  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.199  3765  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
08-16 16:37:53.199  2687  2876 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-16 16:37:53.200  3765  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
08-16 16:37:53.200  3765  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
08-16 16:37:53.200  3765  3815 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 16:37:53.201  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.201  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:53.201  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.201  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.202  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.202  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.202  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.202  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.202  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.202  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.202  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.202  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.202  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.203  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.204  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.204  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.204  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.204  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.205  3765  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising,: true
08-16 16:37:53.205  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.205  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:53.205  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.205  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.206  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.206  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.206  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.206  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.206  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.206  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.206  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.206  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.206  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.206  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.207  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.207  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.207  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.207  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.208  3765  3815 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 16:37:53.208  3765  3815 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 16:37:53.208  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 16:37:53.208  3765  3815 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 16:37:53.209  3765  3815 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 16:37:53.209  3765  3815 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 16:37:53.209  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 16:37:53.209  3765  3815 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 16:37:53.209  3765  3815 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44,:55
08-16 16:37:53.209  3765  3815 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 16:37:53.209  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 16:37:53.209  3765  3815 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 16:37:53.209  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:53.210  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:53.210  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:53.210  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.210  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.210  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.210  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.210  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.210  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.210  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.210  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.211  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.211  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.211  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.212  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:53.212  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:53.212  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.212  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.213  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:53.213  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.213  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:53.213  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:53.213  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:53.213  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:53.213  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:53.213  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:53.213  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:53.595   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 16:37:54.771  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:54.921  1498  3849 I VacuumService: Vacuum at: now=1471358274921 tag=VacuumService
,08-16 16:37:55.043  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:55.053  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:55.055  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:37:55.066  1498  3850 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 16:37:55.068  1498  3850 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 16:37:55.125  1498  3078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 16:37:55.125  1498  3078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 16:37:55.125  1498  3078 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 16:37:55.126  1498  3078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:37:55.151  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 16:37:55.151  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 16:37:55.152  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 16:37:58.018  1498  2074 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 16:37:58.214  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:58.215  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:58.215  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:37:58.215  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.216  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:58.216  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:58.217  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:58.217  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:58.217  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:58.218  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:58.219  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.219  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.219  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:58.220  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:58.220  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:58.220  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:37:58.220  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.221  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.221  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.221  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.226  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:37:58.227  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:58.227  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:58.227  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:58.233  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 16:37:58.233  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:37:58.236  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 16:37:58.238  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 16:37:58.239  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 16:37:58.240  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 16:37:58.240  3765  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 16:37:58.240  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 16:37:58.241  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:58.241  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 16:37:58.241  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-16 16:37:58.242  3765  3858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:37:58.242  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 16:37:58.242  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:58.242  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-16 16:37:58.243  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
,08-16 16:37:58.243  3765  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 16:37:58.243  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:58.243  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:37:58.243  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-16 16:37:58.244  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 16:37:58.244  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.244  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.246  3765  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-16 16:37:58.247  3765  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-16 16:37:58.247  3765  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 16:37:58.247  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:37:58.247  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:58.248  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:37:58.248  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:37:58.248  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:58.248  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 16:37:58.248  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:58.249  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:58.249  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-16 16:37:58.249  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.249  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.249  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
,08-16 16:37:58.250  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:58.250  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:58.250  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:37:58.250  3765  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 16:37:58.250  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.251  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.251  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.251  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.253  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:37:58.253  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:37:58.254  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:58.254  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list,
08-16 16:37:58.256  3765  3815 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 16:37:58.257  3765  3815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-16 16:37:58.257  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 16:37:58.260  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:58.261  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:37:58.261  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:58.261  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:58.262  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:37:58.262  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:58.262  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.262  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:58.262  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
,08-16 16:37:58.263  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:58.263  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list,
08-16 16:37:58.263  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:58.263  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.263  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.264  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.264  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 16:37:58.266  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:58.266  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:37:58.266  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:58.267  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:58.275  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 16:37:58.275  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:37:58.275  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:37:58.275  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:37:58.276  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.276  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.276  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
,08-16 16:37:58.276  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:58.276  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
,08-16 16:37:58.276  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:58.276  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.276  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.276  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.276  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.277  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:37:58.277  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:58.278  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:37:58.278  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list,
08-16 16:37:58.279  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:37:58.279  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:37:58.279  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:37:58.279  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:37:58.279  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.279  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:58.279  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e98d190 not in the list
08-16 16:37:58.279  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:58.280  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:58.280  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:37:58.280  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:37:58.280  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:37:58.280  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:37:58.280  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:37:58.281  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:37:58.282  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:37:58.282  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:37:58.282  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b4a89 not in the list
08-16 16:37:58.283  3765  3815 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 16:37:58.283  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 16:37:58.283  3765  3815 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 16:37:58.283  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 16:37:58.283  3765  3815 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-16 16:37:58.284  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 16:37:58.287  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 16:37:58.287  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 16:37:58.288  3765  3815 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 16:37:58.288  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 16:37:58.288  3765  3815 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-16 16:37:58.288  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 16:37:58.288  3765  3815 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 16:37:58.288  3765  3815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 16:37:58.289  3765  3815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 16:37:58.289  3765  3815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 16:37:58.290  3765  3815 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-16 16:37:58.290  3765  3815 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 16:37:58.290  3765  3815 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 16:37:58.290  3765  3815 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 16:37:58.291  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:37:58.291  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98bbec0 added. We now have 3 listener(s)
08-16 16:37:58.291  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:37:58.293  3765  3815 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 16:37:58.293   873  1382 D WifiService: setWifiEnabled: true pid=3765, uid=10000
08-16 16:37:58.293   873  1382 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:37:58.325  2687  2873 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-16 16:37:58.325  2687  2873 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 16:37:58.750  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-16 16:38:00.140   873  2082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 16:38:01.447  1498  3850 W Uploader:  no longer exists, so no auth token.
,08-16 16:38:02.245  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:02.250  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:02.287  1498  3850 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 16:38:02.287  1498  3850 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 16:38:02.287  1498  3850 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:38:02.288  1498  3850 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:38:02.309  1498  3850 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 16:38:02.309  1498  3850 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 16:38:02.309  1498  3850 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 16:38:02.480  1498  3850 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 16:38:02.480  1498  3850 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 16:38:02.480  1498  3850 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:38:02.480  1498  3850 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:38:02.503  1498  3850 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 16:38:02.503  1498  3850 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 16:38:02.503  1498  3850 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 16:38:03.155  1498  3850 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 16:38:03.155  1498  3850 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 16:38:03.155  1498  3850 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:38:03.155  1498  3850 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:38:03.179  1498  3850 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 16:38:03.179  1498  3850 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 16:38:03.179  1498  3850 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 16:38:03.302  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:38:03.303  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1ee7f9 added. We now have 4 listener(s)
08-16 16:38:03.303  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:38:03.318  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:38:03.319  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1ee7f9 removed from the list
08-16 16:38:03.319  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:38:03.319  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:38:03.319  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:38:03.321  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:38:03.322  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@46cd33e added. We now have 4 listener(s)
08-16 16:38:03.322  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:38:03.325  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:38:03.325  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@46cd33e removed from the list
08-16 16:38:03.325  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:38:03.325  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:38:03.326  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:38:03.328  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 16:38:03.328  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa7059f added. We now have 4 listener(s)
08-16 16:38:03.328  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:38:03.335   873  1991 D WifiService: setWifiEnabled: false pid=3765, uid=10000
,08-16 16:38:03.336   873  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:38:03.343  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:38:03.345  2687  2737 D BluetoothAdapterState: Current state: ON, message: 23
08-16 16:38:03.345  2687  2737 D BluetoothAdapterProperties: Setting state to 13
,08-16 16:38:03.345  2687  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 16:38:03.346  2687  2737 D BluetoothAdapterProperties: onBluetoothDisable(),
08-16 16:38:03.347  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:03.347  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:38:03.348  2687  2737 I BluetoothAdapterState: Entering PendingCommandState
08-16 16:38:03.350  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.350  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:03.350  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:38:03.351  2687  2687 D BluetoothMapService: onReceive
08-16 16:38:03.351  2687  2687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 16:38:03.351  2687  2687 D BluetoothMapService: STATE_TURNING_OFF
,08-16 16:38:03.351  2687  2687 D BluetoothMapService: MAP Service closeService in
,08-16 16:38:03.351  2687  2687 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 16:38:03.351  2687  2687 D ObexServerSockets0: shutdown(block = true)
08-16 16:38:03.352  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 16:38:03.352  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 16:38:03.353  2687  2900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 16:38:03.353  2687  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 16:38:03.353  2687  2876 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 16:38:03.354  2687  2687 I BtOppRfcommListener: stopping Accept Thread
08-16 16:38:03.354  2687  3412 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 16:38:03.354  2687  3412 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 16:38:03.356  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:03.359  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.362  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:03.362  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:38:03.363  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:03.363  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:03.366  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:03.366  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:38:03.367  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:03.367  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:03.367   873   886 I ActivityManager: Start proc 3869:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 16:38:03.368  2687  2741 D BluetoothAdapterProperties: Scan Mode:20
,08-16 16:38:03.369  2687  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 16:38:03.371  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:38:03.372  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.372  2687  2687 D HeadsetService: Received stop request...Stopping profile...
08-16 16:38:03.375  1363  1374 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:03.375  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.375   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 16:38:03.375   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:03.376  1941  1953 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:03.376   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 16:38:03.376   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:03.376   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 16:38:03.376   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 16:38:03.376   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:38:03.377  2687  2687 D A2dpService: Received stop request...Stopping profile...
08-16 16:38:03.377  1498  3850 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 16:38:03.377  1498  3850 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 16:38:03.377  1498  3850 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:38:03.377  1498  3850 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 16:38:03.377  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.377  2687  2895 D A2dpStateMachine: Exit Disconnected: -1
,08-16 16:38:03.379  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.380   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 16:38:03.380  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:03.380  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:03.381  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.381  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:03.383  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 16:38:03.383  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 16:38:03.384  2687  2873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:03.384  2687  2873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:03.384  2687  2873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:03.384  2687  2741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 16:38:03.384  2687  2741 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 16:38:03.384  2687  2687 D HidService: Received stop request...Stopping profile...
,08-16 16:38:03.384  2687  2687 D HidService: Stopping Bluetooth HidService
08-16 16:38:03.387  2687  2687 D HealthService: Received stop request...Stopping profile...
08-16 16:38:03.388   873  1305 E native  : do suspend true
08-16 16:38:03.390  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-16 16:38:03.391  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-16 16:38:03.391  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,08-16 16:38:03.391  1363  1363 D HidProfile: Bluetooth service disconnected
08-16 16:38:03.391  2687  2687 D PanService: Received stop request...Stopping profile...
08-16 16:38:03.392  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:03.392  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:03.392  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.393  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:03.393  2687  2687 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 16:38:03.393  2687  2687 D BluetoothMapService: stop()
,08-16 16:38:03.394  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 16:38:03.394  2687  2687 D BluetoothMapAppObserver: deinitObservers()
08-16 16:38:03.394  1363  1363 D PanProfile: Bluetooth service disconnected
08-16 16:38:03.394  2687  2687 D BluetoothMapAppObserver: removeReceiver()
08-16 16:38:03.396  2687  2741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 16:38:03.396  2687  2873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 16:38:03.397  2687  2873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:03.397   873  2086 D DhcpClient: Clearing IP address
08-16 16:38:03.397  2687  2873 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:38:03.397  2687  2873 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:38:03.397  2687  2873 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:38:03.397  2687  2873 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:38:03.397  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:03.397  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:03.397  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.397  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 16:38:03.397   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 16:38:03.398  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 16:38:03.398  2687  2741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 16:38:03.398  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 16:38:03.399   372   871 D CommandListener: Setting iface cfg
08-16 16:38:03.398  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:03.401  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:03.401  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.401  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:03.396  1363  1363 D BluetoothMap: Proxy object disconnected
,08-16 16:38:03.402  1363  1363 D MapProfile: Bluetooth service disconnected
,08-16 16:38:03.402  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 16:38:03.402  2687  2741 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 16:38:03.402  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 16:38:03.403  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:03.403  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:03.403  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.403  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:03.403  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 16:38:03.403  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 16:38:03.404  2687  2687 D BluetoothMapService: MAP Service closeService in
08-16 16:38:03.404  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:03.404  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-16 16:38:03.404  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.404  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 16:38:03.404  2687  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 16:38:03.405  2687  2737 D BluetoothAdapterProperties: Setting state to 15
08-16 16:38:03.405  2687  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-16 16:38:03.405  2687  2737 I BluetoothAdapterState: Entering BleOnState
08-16 16:38:03.405   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:03.405  1363  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 16:38:03.406  2687  2687 D BluetoothMapService: cleanup()
08-16 16:38:03.406  1363  2046 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:03.406  2687  2687 D BluetoothMapService: MAP Service closeService in
08-16 16:38:03.406  1363  1675 D BluetoothPan: onBluetoothStateChange on: false
08-16 16:38:03.406   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 16:38:03.406   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 16:38:03.406   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 16:38:03.412   395   395 E Parcel  : Reading a NULL string not supported here.
,08-16 16:38:03.412   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 16:38:03.413   873  1305 E native  : do suspend true
08-16 16:38:03.413  1363  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 16:38:03.414   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 16:38:03.414  1941  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:03.414   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:03.415  1363  2046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 16:38:03.416   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 16:38:03.416  1363  1675 D BluetoothMap: onBluetoothStateChange: up=false
08-16 16:38:03.418   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:03.418  2687  2737 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 16:38:03.418  2687  2737 D BluetoothAdapterProperties: Setting state to 16
08-16 16:38:03.418  2687  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 16:38:03.419  2687  2737 D BluetoothAdapterProperties: onBleDisable
08-16 16:38:03.419  2687  2737 I BluetoothAdapterState: Entering PendingCommandState
,08-16 16:38:03.419  2687  2738 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 16:38:03.420  2687  2873 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 16:38:03.420  2687  2873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:03.422  2687  2741 D BluetoothAdapterProperties: Scan Mode:20
08-16 16:38:03.423  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:03.423  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:03.425  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.425  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:03.425   873  2091 D DhcpClient: Receive thread stopped
,08-16 16:38:03.427  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:03.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:03.427  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.427  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:03.429  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:03.429  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:03.430  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.430  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:03.431  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.432  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.432  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:03.437  1498  2536 V NativeCrypto: Read error: ssl=0x9b072600: I/O error during system call, Connection timed out
,08-16 16:38:03.439  1498  2536 V NativeCrypto: SSL shutdown failed: ssl=0x9b072600: I/O error during system call, Broken pipe
,08-16 16:38:03.445  1498  3850 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 16:38:03.445  1498  3850 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 16:38:03.445  1498  3850 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 16:38:03.446   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:03.461   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:03.461   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 16:38:03.462   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 16:38:03.462   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:03.464   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 16:38:03.466   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 16:38:03.467  3384  3384 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@307a459 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-16 16:38:03.470  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.472  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.473  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:03.477  1498  3850 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-16 16:38:03.482   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 16:38:03.483  1877  2263 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 16:38:03.485  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:03.485  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:03.485  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.486  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:03.487  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:03.487  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:03.487   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 16:38:03.487  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.487  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:03.489  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:03.489  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:03.489  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:03.489  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:03.496  3869  3869 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 16:38:03.509   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 16:38:03.520  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 16:38:03.524  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:38:03.526   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@55c8b76:true
,08-16 16:38:03.536   873  1690 I ActivityManager: Start proc 3890:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 16:38:03.544  3869  3869 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 16:38:03.547  3869  3869 D BluetoothMap: Create BluetoothMap proxy object
,08-16 16:38:03.551  3869  3869 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 16:38:03.556  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:38:03.559   873  1955 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 16:38:03.579  3890  3890 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 16:38:03.624  2687  2741 I bt_hci  : shut_down
,08-16 16:38:03.635  2687  2749 D bt_hwcfg: hw_epilog_process
,08-16 16:38:03.636  2687  2749 I bt_vendor: low_power_mode_cb
,08-16 16:38:03.659  2687  2749 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 16:38:03.660  2687  2749 I bt_vendor: epilog_cb
,08-16 16:38:03.660  2687  2749 I bt_hci  : epilog_finished_callback
,08-16 16:38:03.665  2687  2741 I bt_hci_h4: hal_close
,08-16 16:38:03.666  2687  2741 I bt_userial_vendor: device fd = 51 close
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.756  3890  3890 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.756  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.757  3890  3890 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:38:03.757  3890  3890 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:38:03.763  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 16:38:03.771  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:38:03.780  2687  2738 D bt_stack_manager: event_shut_down_stack finished.
08-16 16:38:03.780  2687  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 16:38:03.782  2687  2737 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 16:38:03.783  2687  2687 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 16:38:03.783  2687  2687 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 16:38:03.783  2687  2687 D BtGatt.GattService: stop()
08-16 16:38:03.784  2687  2687 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 16:38:03.785  2687  2687 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:03.785  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:03.785  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:03.786  2687  2687 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 16:38:03.786  2687  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 16:38:03.786  2687  2737 D BluetoothAdapterProperties: Setting state to 10
08-16 16:38:03.786  2687  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 16:38:03.789  2687  2737 I BluetoothAdapterState: Entering OffState
08-16 16:38:03.789   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 16:38:03.802  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:38:03.807  1681  1681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 16:38:03.813  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 16:38:03.813  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 16:38:03.814  2687  2687 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 16:38:03.814  2687  2738 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 16:38:03.817  1681  1681 D SystemUpdateService: onCreate
,08-16 16:38:03.818  2687  2738 D bt_stack_manager: event_clean_up_stack finished.
08-16 16:38:03.820  1681  1681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 16:38:03.830  1681  1681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-16 16:38:03.830  2687  2687 I art     : System.exit called, status: 0
08-16 16:38:03.830  2687  2687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 16:38:03.833  1681  2513 I iu.UploadsManager: num queued entries: 0
,08-16 16:38:03.849  1681  1681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 16:38:03.851  1681  1681 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 16:38:03.854  1681  3921 I SystemUpdateService: active receiver: enabled
,08-16 16:38:03.855  1681  2513 I iu.UploadsManager: num updated entries: 0
,08-16 16:38:03.864  1681  2513 I iu.SyncManager: NEXT; no task
,08-16 16:38:03.868  1681  3921 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 16:38:03.871  1681  3921 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 16:38:03.871  1681  3921 I SystemUpdateService: now status is 0 (complete)
08-16 16:38:03.871  1681  3921 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 16:38:03.871  1681  3921 I SystemUpdateService: file has been verified
08-16 16:38:03.871  1681  3921 I SystemUpdateService: OTA package size = 12249756
,08-16 16:38:03.875   873  1970 I ActivityManager: Start proc 3923:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 16:38:03.905  1681  3921 I SystemUpdateService: showing system update notification
,08-16 16:38:03.905   873  1957 I ActivityManager: Process com.android.bluetooth (pid 2687) has died
,08-16 16:38:03.949  3923  3923 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 16:38:03.952  3923  3923 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:03.955  1681  1681 D SystemUpdateService: onDestroy
,08-16 16:38:03.958   873  1955 I ActivityManager: Killing 3384:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 16:38:03.963  3923  3923 D SprintDMHelper: simOperator: 
08-16 16:38:03.963  3923  3923 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 16:38:04.069  3890  3907 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 16:38:04.076   873  1955 I ActivityManager: Start proc 3937:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 16:38:04.077   873  1955 I ActivityManager: Killing 3437:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 16:38:04.096   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c40a75:true
,08-16 16:38:04.260  2200  3953 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 16:38:04.263   873  1970 I ActivityManager: Start proc 3954:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 16:38:04.306  3954  3954 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 16:38:04.359  3954  3954 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 16:38:04.359  3954  3954 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 16:38:04.359  3954  3954 I GAv4    :   adb logcat -s GAv4
,08-16 16:38:04.373  3954  3954 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 16:38:04.380  3954  3954 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 16:38:04.418  3954  3971 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 16:38:04.521  3954  3954 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 16:38:04.565  3954  3954 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 16:38:04.577  3954  3954 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3682-3688)
08-16 16:38:04.577  3954  3954 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 16:38:04.588  3954  3954 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fbadc0b}
,08-16 16:38:04.588  3954  3954 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 16:38:04.589  3954  3954 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 16:38:04.598  3954  3954 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 16:38:04.600  3954  3954 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 16:38:04.618  3954  3954 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 16:38:04.632  3954  3954 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 16:38:04.632  3954  3954 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 16:38:04.632  3954  3954 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 16:38:04.632  3954  3954 I Adreno  : Build Date                       : 10/20/15
08-16 16:38:04.632  3954  3954 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 16:38:04.632  3954  3954 I Adreno  : Local Branch                     : M14
08-16 16:38:04.632  3954  3954 I Adreno  : Remote Branch                    : 
08-16 16:38:04.632  3954  3954 I Adreno  : Remote Branch                    : 
08-16 16:38:04.632  3954  3954 I Adreno  : Reconstruct Branch               : 
,08-16 16:38:04.682  3954  4000 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 16:38:04.702  3954  3954 I NSApplication: Starting up...
,08-16 16:38:04.737   873  3735 I ActivityManager: Start proc 4005:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-16 16:38:04.738   873  3735 I ActivityManager: Killing 1715:android.process.acore/u0a5 (adj 15): empty #17
,08-16 16:38:04.819  4005  4005 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 16:38:05.023   873  1970 I ActivityManager: Killing 3646:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 16:38:05.116   873   884 I ActivityManager: Start proc 4019:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-16 16:38:05.208  4019  4019 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 16:38:05.262  4019  4019 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 16:38:05.312   873  1687 I ActivityManager: Killing 3661:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 16:38:08.356   873  1991 D WifiService: setWifiEnabled: true pid=3765, uid=10000
,08-16 16:38:08.356   873  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:38:08.367   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-16 16:38:08.379  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:08.380  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:08.380  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:08.380  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:08.383  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:08.383  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:08.383  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:08.383  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:08.386  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:08.386  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:08.386  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:08.386  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:08.390   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-16 16:38:08.391   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 16:38:08.392   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 16:38:08.393   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 16:38:08.393   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 16:38:08.393   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 16:38:08.394   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 16:38:08.413   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-16 16:38:08.414   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 16:38:08.416   372   871 D CommandListener: Setting iface cfg
,08-16 16:38:08.422   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 16:38:08.422   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 16:38:08.424   873  1305 E native  : do suspend true
,08-16 16:38:08.433   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 16:38:08.433   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-16 16:38:08.434   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:38:09.274   873  1690 I ActivityManager: Killing 3460:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 16:38:09.717   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 16:38:09.793   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.88 rxSuccessRate=13.06 delta 1000 -> 994
,08-16 16:38:09.797   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 16:38:09.797   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:38:09.816   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 16:38:09.865   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 16:38:09.867  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 16:38:10.280  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 16:38:10.325  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 16:38:10.325  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 16:38:10.331   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:38:10.347   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 16:38:10.348   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:38:10.348   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 16:38:10.375   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:38:10.389   372   871 D CommandListener: Setting iface cfg
,08-16 16:38:10.390   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 16:38:10.396   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 16:38:10.449   873  4056 D DhcpClient: Receive thread started
,08-16 16:38:10.535   873  1305 E native  : do suspend false
,08-16 16:38:10.553   873  2086 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 16:38:10.567   873  4056 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172643, domain null
,08-16 16:38:10.568   873  2086 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172643 seconds
,08-16 16:38:10.572   873  2086 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 16:38:10.589   873  4056 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 16:38:10.590   873  2086 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 16:38:10.595   372   871 D CommandListener: Setting iface cfg
,08-16 16:38:10.606   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 16:38:10.606   873  2086 D DhcpClient: Scheduling renewal in 86399s
,08-16 16:38:10.609   873  1305 E native  : do suspend true
,08-16 16:38:10.640   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 16:38:10.644   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 16:38:10.646   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 16:38:10.649   873  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 16:38:10.664   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 16:38:10.730   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 16:38:10.730   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 16:38:10.734   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 16:38:10.738   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 16:38:10.743   873  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 16:38:10.757   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 16:38:10.763   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-16 16:38:10.763   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-16 16:38:10.763   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 16:38:10.763   873  1308 D ConnectivityService:    accepting network in place of null
08-16 16:38:10.764   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 16:38:10.765   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 16:38:10.765   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 16:38:10.777   873  4055 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179888, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 16:38:10.797   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,08-16 16:38:10.831   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:10.840   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 16:38:10.840   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:10.845   873  4052 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.110,2a00:1450:4001:80b::200e
,08-16 16:38:10.849   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 16:38:10.852   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 16:38:10.860  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:10.861  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:38:10.861  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:10.861  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:10.865  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:10.865  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:38:10.866  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:10.866  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:10.871  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:10.871  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:38:10.871  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:10.871  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:10.880  1681  1681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 16:38:10.887  1681  1681 D SystemUpdateService: onCreate
,08-16 16:38:10.891  1681  1681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 16:38:10.915  1681  4066 I SystemUpdateService: active receiver: enabled
,08-16 16:38:10.917  1681  1681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 16:38:10.924  1681  2513 I iu.UploadsManager: num queued entries: 0
,08-16 16:38:10.926   873  4052 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 14:38:10 GMT], X-Android-Received-Millis=[1471358290925], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471358290899]}
,08-16 16:38:10.929   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 16:38:10.930   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 16:38:10.930   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 16:38:10.933  1681  1681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 16:38:10.935  1681  1681 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
08-16 16:38:10.935   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 16:38:10.938  3923  3923 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:10.943  1681  4068 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 16:38:10.943  1681  4068 W BaseAppContext: Using Auth Proxy for data requests.,
08-16 16:38:10.945  1681  4068 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 16:38:10.947  3923  3923 D SprintDMHelper: simOperator: 
,08-16 16:38:10.947  3923  3923 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 16:38:10.968  1681  4066 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 16:38:10.975  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:10.976  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:10.979  1681  2513 I iu.UploadsManager: num updated entries: 0
,08-16 16:38:10.989  1681  2513 I iu.SyncManager: NEXT; no task
,08-16 16:38:10.991  1681  4066 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 16:38:10.992  1681  4066 I SystemUpdateService: now status is 0 (complete)
,08-16 16:38:10.993  1681  4066 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 16:38:10.993  1681  4066 I SystemUpdateService: file has been verified
08-16 16:38:10.993  1681  4066 I SystemUpdateService: OTA package size = 12249756
,08-16 16:38:11.026  1681  4066 I SystemUpdateService: showing system update notification
,08-16 16:38:11.061  1498  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 16:38:11.061  1498  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 16:38:11.062  1498  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 16:38:11.062  1498  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:38:11.075  1681  1681 D SystemUpdateService: onDestroy
,08-16 16:38:11.092  2200  4074 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 16:38:11.117  1681  4068 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-16 16:38:11.840   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 16:38:13.364   873  1690 D WifiService: setWifiEnabled: false pid=3765, uid=10000
,08-16 16:38:13.364   873  1690 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:38:13.399  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 16:38:13.410   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 16:38:13.410   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 16:38:13.411   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 16:38:13.411   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:38:13.437   873  1305 E native  : do suspend true
,08-16 16:38:13.457   873  2086 D DhcpClient: Clearing IP address
08-16 16:38:13.458   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 16:38:13.465   372   871 D CommandListener: Setting iface cfg
,08-16 16:38:13.478  1498  4078 V NativeCrypto: Read error: ssl=0x9b005a00: I/O error during system call, Connection timed out
08-16 16:38:13.487   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 16:38:13.488   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-16 16:38:13.494   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 16:38:13.495   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 16:38:13.495   873  1305 E native  : do suspend true
08-16 16:38:13.497  1498  4078 V NativeCrypto: SSL shutdown failed: ssl=0x9b005a00: I/O error during system call, Broken pipe
08-16 16:38:13.497   395   395 E Parcel  : Reading a NULL string not supported here.
08-16 16:38:13.506   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 16:38:13.512   873  4056 D DhcpClient: Receive thread stopped
,08-16 16:38:13.540   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:13.580   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:13.582   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 16:38:13.583   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:13.583   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 16:38:13.587   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 16:38:13.591  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:13.592  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:13.592  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:13.592  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:13.597  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:13.598  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:13.598  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:13.598  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-16 16:38:13.599  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:13.600  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:13.600  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:13.600  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:13.604   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 16:38:13.614  1681  1681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 16:38:13.621  1681  1681 D SystemUpdateService: onCreate
08-16 16:38:13.626   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:38:13.629  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:13.630  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:13.630  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:13.630  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:13.631  1877  2263 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:38:13.631  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:13.631  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:13.631  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:13.631  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:13.632  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:13.632  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:13.632   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 16:38:13.633  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:13.633  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:13.638  1681  1681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 16:38:13.661  1681  1681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 16:38:13.663  1681  2513 I iu.UploadsManager: num queued entries: 0
,08-16 16:38:13.663  1681  2513 I iu.UploadsManager: num updated entries: 0
08-16 16:38:13.664  1681  2513 I iu.SyncManager: NEXT; no task
,08-16 16:38:13.661  1681  4088 I SystemUpdateService: active receiver: enabled
,08-16 16:38:13.670  1681  1681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 16:38:13.671  1681  1681 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 16:38:13.672  1681  4088 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-16 16:38:13.673  3923  3923 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:13.679  3923  3923 D SprintDMHelper: simOperator: 
08-16 16:38:13.679  3923  3923 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 16:38:13.684  1681  4088 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 16:38:13.684  1681  4088 I SystemUpdateService: now status is 0 (complete)
08-16 16:38:13.684  1681  4088 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 16:38:13.685  1681  4088 I SystemUpdateService: file has been verified
08-16 16:38:13.685  1681  4088 I SystemUpdateService: OTA package size = 12249756
,08-16 16:38:13.687   372   871 E Netd    : netlink response contains error (No such file or directory)
08-16 16:38:13.688   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 16:38:13.710  2200  4092 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 16:38:13.716  1681  4088 I SystemUpdateService: showing system update notification
,08-16 16:38:13.732  1681  1681 D SystemUpdateService: onDestroy
,08-16 16:38:18.422   873   890 I ActivityManager: Start proc 4096:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 16:38:18.535  4096  4096 D AdapterServiceConfig: Adding HeadsetService
,08-16 16:38:18.536  4096  4096 D AdapterServiceConfig: Adding A2dpService
08-16 16:38:18.536  4096  4096 D AdapterServiceConfig: Adding HidService
08-16 16:38:18.536  4096  4096 D AdapterServiceConfig: Adding HealthService
,08-16 16:38:18.536  4096  4096 D AdapterServiceConfig: Adding PanService
08-16 16:38:18.536  4096  4096 D AdapterServiceConfig: Adding GattService
08-16 16:38:18.537  4096  4096 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 16:38:18.553   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2df70f6:true
,08-16 16:38:18.553  4096  4096 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 16:38:18.558  4096  4096 I bt_bluedroid: init
,08-16 16:38:18.559  4096  4108 I BluetoothAdapterState: Entering OffState
,08-16 16:38:18.564  4096  4109 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 16:38:18.565  4096  4109 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 16:38:18.565  4096  4109 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 16:38:18.565  4096  4109 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 16:38:18.568  4096  4096 I bt_bluedroid: get_profile_interface socket
,08-16 16:38:18.571  4096  4096 I bt_bluedroid: get_profile_interface sdp
08-16 16:38:18.574  4096  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 16:38:18.576  4096  4107 I bt_bluedroid: config_hci_snoop_log
,08-16 16:38:18.577  4096  4112 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 16:38:18.580   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 16:38:18.588  4096  4108 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 16:38:18.588  4096  4108 D BluetoothAdapterProperties: Setting state to 14
08-16 16:38:18.589  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 16:38:18.593  4096  4108 D BluetoothBondStateMachine: make
,08-16 16:38:18.596  4096  4114 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 16:38:18.605  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
08-16 16:38:18.605  4096  4096 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 16:38:18.610  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:18.611  4096  4096 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 16:38:18.612  4096  4096 D BtGatt.GattService: Received start request. Starting profile...
08-16 16:38:18.612  4096  4096 D BtGatt.GattService: start()
,08-16 16:38:18.613  4096  4096 I bt_bluedroid: get_profile_interface gatt
,08-16 16:38:18.614  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:18.615  4096  4096 D BtGatt.AdvertiseManager: advertise manager created
,08-16 16:38:18.627  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,08-16 16:38:18.627  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:18.628  4096  4096 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 16:38:18.628  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 16:38:18.629  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 16:38:18.629  4096  4108 I bt_bluedroid: enable
,08-16 16:38:18.630  4096  4109 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 16:38:18.631  4096  4109 I bt_hci  : start_up
,08-16 16:38:18.647  4096  4109 I bt_vendor: alloc value 0xb3a5a189
,08-16 16:38:18.648  4096  4109 I bt_vendor: init
08-16 16:38:18.648  4096  4109 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 16:38:18.648  4096  4109 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 16:38:18.757  4096  4109 D bt_hci  : start_up starting async portion
,08-16 16:38:18.757  4096  4117 I bt_hci  : event_finish_startup
08-16 16:38:18.758  4096  4117 I bt_hci_h4: hal_open
08-16 16:38:18.758  4096  4117 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 16:38:18.768   873  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-16 16:38:18.768  4096  4117 I bt_userial_vendor: device fd = 51 open
,08-16 16:38:18.799  4096  4117 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 16:38:18.831  4096  4117 D bt_hwcfg: Chipset BCM4354A2
,08-16 16:38:18.831  4096  4117 D bt_hwcfg: Target name = [BCM4354A2]
08-16 16:38:18.832  4096  4117 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 16:38:19.496  4096  4117 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 16:38:19.498  4096  4117 D bt_hwcfg: Settlement delay -- 100 ms
08-16 16:38:19.498  4096  4117 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 16:38:19.615  4096  4117 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 16:38:19.617  4096  4117 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 16:38:19.645  4096  4117 I bt_hwcfg: vendor lib fwcfg completed
,08-16 16:38:19.646  4096  4117 I bt_vendor: firmware callback
08-16 16:38:19.646  4096  4117 I bt_hci  : firmware_config_callback
,08-16 16:38:19.657  4096  4119 I bt_btu  : btu_task pending for preload complete event
,08-16 16:38:19.657  4096  4119 I bt_btu_task: Bluetooth chip preload is complete
,08-16 16:38:19.658  4096  4119 I bt_btu  : btu_task received preload complete event
,08-16 16:38:19.667  4096  4119 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 16:38:19.668  4096  4119 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 16:38:19.668  4096  4119 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 16:38:19.668  4096  4119 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 16:38:19.669  4096  4119 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 16:38:19.669  4096  4119 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 16:38:19.669  4096  4119 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 16:38:19.669  4096  4119 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 16:38:19.670  4096  4119 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 16:38:19.670  4096  4119 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 16:38:19.670  4096  4119 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 16:38:19.671  4096  4119 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 16:38:19.671  4096  4119 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 16:38:19.672  4096  4119 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 16:38:19.672  4096  4119 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 16:38:19.808  4096  4119 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d7d9d
,08-16 16:38:19.809  4096  4119 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d7d9d 
,08-16 16:38:19.818  4096  4112 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 16:38:19.821  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 16:38:19.822  4096  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 16:38:19.826  4096  4112 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 16:38:19.829  4096  4112 D BluetoothAdapterProperties: Scan Mode:20
,08-16 16:38:19.830  4096  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 16:38:19.830  4096  4112 D bt_hci  : do_postload posting postload work item
,08-16 16:38:19.833  4096  4117 I bt_hci  : event_postload
,08-16 16:38:19.833  4096  4117 I bt_vendor: sco_config_cb
,08-16 16:38:19.833  4096  4117 I bt_hci  : sco_config_callback postload finished.
,08-16 16:38:19.834  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:19.836  4096  4112 D bt_bte_conf: Device ID record 1 : primary
08-16 16:38:19.836  4096  4112 D bt_bte_conf:   vendorId            = 000f
08-16 16:38:19.836  4096  4112 D bt_bte_conf:   vendorIdSource      = 0001
08-16 16:38:19.837  4096  4112 D bt_bte_conf:   product             = 1200
08-16 16:38:19.837  4096  4112 D bt_bte_conf:   version             = 1436
08-16 16:38:19.837  4096  4112 D bt_bte_conf:   clientExecutableURL = 
08-16 16:38:19.837  4096  4112 D bt_bte_conf:   serviceDescription  = 
08-16 16:38:19.837  4096  4112 D bt_bte_conf:   documentationURL    = 
08-16 16:38:19.838  4096  4112 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 16:38:19.838  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:19.839  4096  4109 D bt_stack_manager: event_start_up_stack finished
08-16 16:38:19.839  4096  4117 I bt_vendor: low_power_mode_cb
08-16 16:38:19.841  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 16:38:19.842  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:19.842  4096  4108 D BluetoothAdapterProperties: Setting state to 15
08-16 16:38:19.842  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 16:38:19.845  4096  4108 I BluetoothAdapterState: Entering BleOnState
,08-16 16:38:19.851  4096  4108 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 16:38:19.852  4096  4108 D BluetoothAdapterProperties: Setting state to 11
08-16 16:38:19.852  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 16:38:19.864  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:19.865  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:19.867  4096  4096 D HeadsetService: Received start request. Starting profile...
,08-16 16:38:19.869  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:19.870  4096  4096 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 16:38:19.870  4096  4096 D HeadsetStateMachine: make
08-16 16:38:19.870  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:19.880  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
,08-16 16:38:19.882  4096  4096 D HeadsetStateMachine: max_hf_connections = 1
,08-16 16:38:19.882  4096  4096 I bt_bluedroid: get_profile_interface handsfree
08-16 16:38:19.882  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 16:38:19.882  4096  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 16:38:19.885  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:19.886  4096  4096 D A2dpService: Received start request. Starting profile...
08-16 16:38:19.887  4096  4096 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 16:38:19.887  4096  4096 I bt_bluedroid: get_profile_interface avrcp
,08-16 16:38:19.894  4096  4096 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 16:38:19.894  4096  4096 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 16:38:19.894  4096  4096 D A2dpStateMachine: make
08-16 16:38:19.896  4096  4096 I bt_bluedroid: get_profile_interface a2dp
,08-16 16:38:19.897  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 16:38:19.899  4096  4127 D A2dpStateMachine: Enter Disconnected: -2
,08-16 16:38:19.902  4096  4096 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 16:38:19.903  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:19.919  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:38:19.921  4096  4096 D HidService: Received start request. Starting profile...
,08-16 16:38:19.921  4096  4096 I bt_bluedroid: get_profile_interface hidhost
08-16 16:38:19.921  4096  4112 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b93e5
08-16 16:38:19.921  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 16:38:19.922  4096  4096 D HidService: setHidService(): set to: null
08-16 16:38:19.922  4096  4096 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 16:38:19.923  3869  3869 D BluetoothInputDevice: Proxy object connected
08-16 16:38:19.923  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:19.923  3869  3869 D HidProfile: Bluetooth service connected
,08-16 16:38:19.924  4096  4096 D HealthService: Received start request. Starting profile...
,08-16 16:38:19.926  4096  4096 I bt_bluedroid: get_profile_interface health
,08-16 16:38:19.928  4096  4096 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 16:38:19.929  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:19.930  4096  4096 D PanService: Received start request. Starting profile...
,08-16 16:38:19.930  4096  4096 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 16:38:19.930  4096  4096 I bt_bluedroid: get_profile_interface pan
,08-16 16:38:19.931  4096  4112 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 16:38:19.931  3869  3869 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:38:19.932  3869  3869 D PanProfile: Bluetooth service connected
08-16 16:38:19.933  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:19.934  3869  3869 D BluetoothMap: Proxy object connected
08-16 16:38:19.934  3869  3869 D MapProfile: Bluetooth service connected
08-16 16:38:19.934  3869  3869 D BluetoothMap: getConnectedDevices()
08-16 16:38:19.934  3869  3869 D BluetoothMap: Bluetooth is Not enabled
,08-16 16:38:19.935  4096  4096 D BluetoothMapService: Received start request. Starting profile...
08-16 16:38:19.935  4096  4096 D BluetoothMapService: start()
08-16 16:38:19.937  4096  4096 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-16 16:38:19.938  4096  4096 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 16:38:19.938  4096  4096 D BluetoothMapAppObserver: createReceiver()
08-16 16:38:19.939  4096  4096 D BluetoothMapAppObserver: initObservers()
08-16 16:38:19.939  4096  4096 D BluetoothMapAppObserver: getEnabledAccountItems()
08-16 16:38:19.945  4096  4096 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:19.945  4096  4096 V BluetoothAdapterState: isTurningOn()=true
,08-16 16:38:19.945  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:19.945  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:19.948  4096  4125 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 16:38:19.948  4096  4096 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:19.948  4096  4096 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:19.948  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:19.948  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:19.948  4096  4096 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:19.949  4096  4096 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:19.949  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 16:38:19.949  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:19.951  4096  4096 V BluetoothAdapterState: isTurningOn()=true
,08-16 16:38:19.952  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:19.952  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:19.952  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 16:38:19.952  4096  4108 D BluetoothAdapterProperties: ScanMode =  20
08-16 16:38:19.952  4096  4108 D BluetoothAdapterProperties: State =  11
08-16 16:38:19.953  4096  4108 D BluetoothAdapterProperties: Setting state to 12
,08-16 16:38:19.953  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 16:38:19.953   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:38:19.953  1363  2046 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 16:38:19.955  4096  4112 D BluetoothAdapterProperties: Scan Mode:21
08-16 16:38:19.955  4096  4108 I BluetoothAdapterState: Entering OnState
08-16 16:38:19.955  4096  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 16:38:19.956  3869  3880 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 16:38:19.956  1363  1363 D BluetoothInputDevice: Proxy object connected
08-16 16:38:19.956  1363  1363 D HidProfile: Bluetooth service connected
08-16 16:38:19.957  3869  3879 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:19.959  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:19.959  3869  3880 D BluetoothMap: onBluetoothStateChange: up=true
08-16 16:38:19.959  1363  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:38:19.960  1363  2046 D BluetoothPan: onBluetoothStateChange on: true
08-16 16:38:19.961  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:19.962  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:38:19.963  1363  1363 D PanProfile: Bluetooth service connected
08-16 16:38:19.963  3869  3879 D BluetoothPan: onBluetoothStateChange on: true
08-16 16:38:19.963  1363  1675 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:19.964  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:19.965  1941  1953 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:38:19.965   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:38:19.965  1363  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 16:38:19.965  4096  4096 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 16:38:19.966  4096  4096 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 16:38:19.966  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:19.968   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 16:38:19.968  4096  4096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:38:19.969  1363  1374 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 16:38:19.970  4096  4096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:19.971  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:19.971  4096  4096 D ObexServerSockets: Succeed to create listening sockets 
08-16 16:38:19.972  4096  4096 D ObexServerSockets0: startAccept()
08-16 16:38:19.972  4096  4096 D ObexServerSockets0: prepareForNewConnect()
08-16 16:38:19.972  1363  1363 D BluetoothMap: Proxy object connected
08-16 16:38:19.972  1363  1363 D MapProfile: Bluetooth service connected
08-16 16:38:19.972  1363  1363 D BluetoothMap: getConnectedDevices()
08-16 16:38:19.973   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:38:19.974  4096  4096 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 16:38:19.974  4096  4096 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 16:38:19.975  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:19.975   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 16:38:19.976  4096  4136 D ObexServerSockets0: Accepting socket connection...
,08-16 16:38:19.976  4096  4135 D ObexServerSockets0: Accepting socket connection...
08-16 16:38:19.978   873   873 D BluetoothA2dp: Proxy object connected
08-16 16:38:19.978  4096  4096 D BluetoothMapService: onReceive
08-16 16:38:19.978  1363  1363 D BluetoothA2dp: Proxy object connected
,08-16 16:38:19.978  4096  4096 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:38:19.978  4096  4096 D BluetoothMapService: STATE_ON
08-16 16:38:19.979  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:19.981  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:19.981  3869  3869 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 16:38:19.982  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:19.986  3869  3869 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 16:38:19.991  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 16:38:19.994  3869  3869 D BluetoothA2dp: Proxy object connected
,08-16 16:38:19.997  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:38:20.004  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:38:20.005  4096  4096 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 16:38:20.006  4096  4096 D ObexServerSockets0: prepareForNewConnect()
08-16 16:38:20.007  3869  3869 D BluetoothPbap: Proxy object connected
08-16 16:38:20.007  3869  3869 D PbapServerProfile: Bluetooth service connected
08-16 16:38:20.008  1363  1363 D BluetoothPbap: Proxy object connected
08-16 16:38:20.008  1363  1363 D PbapServerProfile: Bluetooth service connected
,08-16 16:38:20.014  4096  4140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:38:20.029  4096  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:38:20.031  4096  4144 I BtOppRfcommListener: Accept thread started.
,08-16 16:38:20.054  1363  1675 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.054   873   873 D BluetoothHeadset: Proxy object connected,
08-16 16:38:20.054  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-16 16:38:20.054   873   873 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.055  1941  2234 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.055   873   873 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.060  1363  1376 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.060  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-16 16:38:20.065  1941  1951 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.065   873   890 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.073   873   890 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.088  3869  3880 D BluetoothHeadset: Proxy object connected
,08-16 16:38:20.092  3869  3869 D HeadsetProfile: Bluetooth service connected
,08-16 16:38:20.095  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:20.115  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:20.118  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:20.145  1498  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 16:38:20.145  1498  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 16:38:20.145  1498  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:38:20.146  1498  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:38:20.172  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 16:38:20.173  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 16:38:20.173  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 16:38:23.386  4096  4108 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 16:38:23.386  4096  4108 D BluetoothAdapterProperties: Setting state to 13
08-16 16:38:23.386  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 16:38:23.388  4096  4108 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 16:38:23.396  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
,08-16 16:38:23.405  4096  4096 D BluetoothMapService: onReceive
,08-16 16:38:23.405  4096  4096 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:38:23.406  4096  4096 D BluetoothMapService: STATE_TURNING_OFF
08-16 16:38:23.407  4096  4096 D BluetoothMapService: MAP Service closeService in
08-16 16:38:23.407  4096  4096 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 16:38:23.407  4096  4096 D ObexServerSockets0: shutdown(block = true)
,08-16 16:38:23.408  4096  4135 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 16:38:23.413  4096  4096 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 16:38:23.414  4096  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 16:38:23.416  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:23.416  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:23.416  4096  4096 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 16:38:23.417  4096  4096 I BtOppRfcommListener: stopping Accept Thread
08-16 16:38:23.417  4096  4144 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:38:23.417  4096  4144 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 16:38:23.418  4096  4112 D BluetoothAdapterProperties: Scan Mode:20
,08-16 16:38:23.418  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:23.419  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:23.419  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 16:38:23.420  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 16:38:23.416  4096  4122 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 16:38:23.427  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:23.427  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:23.428  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:23.428  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:23.431  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:23.431  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:23.437  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:38:23.433  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:38:23.438  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:23.430  4096  4096 D HeadsetService: Received stop request...Stopping profile...
08-16 16:38:23.441  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:23.441  1363  1376 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:23.441   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:23.441  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-16 16:38:23.441   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:23.442  1941  2073 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:23.442  3869  3880 D BluetoothHeadset: Proxy object disconnected
08-16 16:38:23.442  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:23.442   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 16:38:23.442  3869  3869 D HeadsetProfile: Bluetooth service disconnected
08-16 16:38:23.443  4096  4096 D A2dpService: Received stop request...Stopping profile...
08-16 16:38:23.443  4096  4127 D A2dpStateMachine: Exit Disconnected: -1
08-16 16:38:23.443  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:23.445   873   873 D BluetoothA2dp: Proxy object disconnected
,08-16 16:38:23.446  1363  1363 D BluetoothA2dp: Proxy object disconnected
08-16 16:38:23.446  3869  3869 D BluetoothA2dp: Proxy object disconnected
08-16 16:38:23.446  4096  4096 D HidService: Received stop request...Stopping profile...
08-16 16:38:23.446  4096  4096 D HidService: Stopping Bluetooth HidService
08-16 16:38:23.447  3869  3869 D BluetoothInputDevice: Proxy object disconnected
08-16 16:38:23.447  3869  3869 D HidProfile: Bluetooth service disconnected
,08-16 16:38:23.447  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-16 16:38:23.447  1363  1363 D HidProfile: Bluetooth service disconnected
,08-16 16:38:23.448  4096  4096 D HealthService: Received stop request...Stopping profile...
08-16 16:38:23.449  4096  4096 D PanService: Received stop request...Stopping profile...
08-16 16:38:23.450  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 16:38:23.450  1363  1363 D PanProfile: Bluetooth service disconnected
08-16 16:38:23.450  3869  3869 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 16:38:23.450  3869  3869 D PanProfile: Bluetooth service disconnected
08-16 16:38:23.450  4096  4096 D BluetoothMapService: Received stop request...Stopping profile...
08-16 16:38:23.450  4096  4096 D BluetoothMapService: stop()
08-16 16:38:23.451  4096  4096 D BluetoothMapAppObserver: deinitObservers()
08-16 16:38:23.451  4096  4096 D BluetoothMapAppObserver: removeReceiver()
08-16 16:38:23.452  1363  1363 D BluetoothMap: Proxy object disconnected
08-16 16:38:23.452  1363  1363 D MapProfile: Bluetooth service disconnected
08-16 16:38:23.453  3869  3869 D BluetoothMap: Proxy object disconnected
08-16 16:38:23.453  3869  3869 D MapProfile: Bluetooth service disconnected
08-16 16:38:23.454  4096  4096 V BluetoothAdapterState: isTurningOff()=true
,08-16 16:38:23.454  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:23.454  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.454  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:23.455  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:38:23.456  4096  4096 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 16:38:23.456  4096  4096 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:38:23.456  4096  4119 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:23.456  4096  4119 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:23.456  4096  4119 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:23.457  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 16:38:23.457  4096  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 16:38:23.457  4096  4096 V BluetoothAdapterState: isTurningOff()=true
,08-16 16:38:23.457  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:23.457  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.457  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:23.458  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 16:38:23.459  4096  4096 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:23.459  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:23.459  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.459  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:23.459  4096  4119 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:23.459  4096  4119 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:23.459  4096  4119 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:38:23.459  4096  4119 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:38:23.459  4096  4096 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 16:38:23.459  4096  4119 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:38:23.460  4096  4119 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:38:23.460  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 16:38:23.460  4096  4096 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 16:38:23.460  4096  4096 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:23.460  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:23.460  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.460  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 16:38:23.460  4096  4096 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 16:38:23.460  4096  4112 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 16:38:23.461  4096  4096 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 16:38:23.461  4096  4096 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:23.461  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:23.461  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.461  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:23.462  4096  4096 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 16:38:23.462  4096  4096 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 16:38:23.463  4096  4096 D BluetoothMapService: MAP Service closeService in
08-16 16:38:23.463  4096  4096 V BluetoothAdapterState: isTurningOff()=true
08-16 16:38:23.463  4096  4096 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:23.463  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.463  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:23.463  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 16:38:23.463  4096  4108 D BluetoothAdapterProperties: Setting state to 15
08-16 16:38:23.463  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 16:38:23.464  4096  4108 I BluetoothAdapterState: Entering BleOnState
08-16 16:38:23.464  3869  3879 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 16:38:23.464  4096  4096 D BluetoothMapService: cleanup()
08-16 16:38:23.464  4096  4096 D BluetoothMapService: MAP Service closeService in
,08-16 16:38:23.465   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 16:38:23.465  1363  2046 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 16:38:23.466  1363  1363 D BluetoothPbap: Proxy object disconnected
08-16 16:38:23.466  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-16 16:38:23.467  3869  3879 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 16:38:23.469  3869  3880 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 16:38:23.470  3869  3879 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 16:38:23.471  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:23.471  1363  1675 D BluetoothPan: onBluetoothStateChange on: false
08-16 16:38:23.472  3869  3880 D BluetoothPan: onBluetoothStateChange on: false
,08-16 16:38:23.472  1363  1376 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 16:38:23.468  3869  3869 D BluetoothPbap: Proxy object disconnected
,08-16 16:38:23.473  3869  3869 D PbapServerProfile: Bluetooth service disconnected
,08-16 16:38:23.473  1941  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:23.473   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:23.473  1363  2046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 16:38:23.475   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 16:38:23.475  1363  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-16 16:38:23.476  3869  3879 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:23.476   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:38:23.476  4096  4108 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 16:38:23.476  4096  4108 D BluetoothAdapterProperties: Setting state to 16
08-16 16:38:23.477  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 16:38:23.477  4096  4108 D BluetoothAdapterProperties: onBleDisable
,08-16 16:38:23.477  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
08-16 16:38:23.478  4096  4109 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 16:38:23.479  4096  4119 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 16:38:23.479  4096  4119 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 16:38:23.480  4096  4112 D BluetoothAdapterProperties: Scan Mode:20
,08-16 16:38:23.480  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 16:38:23.481  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:23.482  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:23.485  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:23.486  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:38:23.487  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:23.496  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:23.497  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:23.499  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:38:23.681  4096  4112 I bt_hci  : shut_down
,08-16 16:38:23.682  4096  4117 D bt_hwcfg: hw_epilog_process
,08-16 16:38:23.684  4096  4117 I bt_vendor: low_power_mode_cb
,08-16 16:38:23.714  4096  4117 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 16:38:23.714  4096  4117 I bt_vendor: epilog_cb
08-16 16:38:23.714  4096  4117 I bt_hci  : epilog_finished_callback
,08-16 16:38:23.723  4096  4112 I bt_hci_h4: hal_close
,08-16 16:38:23.725  4096  4112 I bt_userial_vendor: device fd = 51 close
,08-16 16:38:23.846  4096  4109 D bt_stack_manager: event_shut_down_stack finished.
,08-16 16:38:23.848  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 16:38:23.854  4096  4096 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 16:38:23.854  4096  4108 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 16:38:23.856  4096  4096 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 16:38:23.856  4096  4096 D BtGatt.GattService: stop()
,08-16 16:38:23.856  4096  4096 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 16:38:23.861  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,08-16 16:38:23.862  4096  4096 V BluetoothAdapterState: isTurningOn()=false
,08-16 16:38:23.862  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:23.862  4096  4096 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 16:38:23.863  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 16:38:23.864  4096  4108 D BluetoothAdapterProperties: Setting state to 10
,08-16 16:38:23.864  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 16:38:23.869  4096  4108 I BluetoothAdapterState: Entering OffState
,08-16 16:38:23.873   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 16:38:23.899  4096  4096 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 16:38:23.899  4096  4096 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 16:38:23.900  4096  4109 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 16:38:23.907  4096  4109 D bt_stack_manager: event_clean_up_stack finished.
,08-16 16:38:23.908  4096  4096 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 16:38:23.913  4096  4096 I art     : System.exit called, status: 0
,08-16 16:38:23.914  4096  4096 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 16:38:23.973   873   883 I ActivityManager: Process com.android.bluetooth (pid 4096) has died
,08-16 16:38:28.383  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:38:28.383  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:38:28.390  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:38:28.390  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa7059f removed from the list
08-16 16:38:28.390  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:38:28.391  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:38:28.391  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:38:28.398  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 16:38:28.398  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85d0ab5 added. We now have 4 listener(s)
,08-16 16:38:28.399  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:38:28.400  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:38:28.401  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85d0ab5 removed from the list
08-16 16:38:28.401  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:38:28.401  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:38:28.402  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:38:28.405  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:38:28.405  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5dee54a added. We now have 4 listener(s)
08-16 16:38:28.405  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:38:33.416  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:33.465   873   890 I ActivityManager: Start proc 4155:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 16:38:33.589  4155  4155 D AdapterServiceConfig: Adding HeadsetService
08-16 16:38:33.589  4155  4155 D AdapterServiceConfig: Adding A2dpService
08-16 16:38:33.589  4155  4155 D AdapterServiceConfig: Adding HidService
08-16 16:38:33.589  4155  4155 D AdapterServiceConfig: Adding HealthService
08-16 16:38:33.589  4155  4155 D AdapterServiceConfig: Adding PanService
08-16 16:38:33.590  4155  4155 D AdapterServiceConfig: Adding GattService
08-16 16:38:33.590  4155  4155 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 16:38:33.605  4155  4155 D BluetoothAdapterState: make() - Creating AdapterState
08-16 16:38:33.605   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a10345:true
,08-16 16:38:33.612  4155  4155 I bt_bluedroid: init
,08-16 16:38:33.614  4155  4167 I BluetoothAdapterState: Entering OffState
,08-16 16:38:33.618  4155  4168 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 16:38:33.619  4155  4168 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 16:38:33.619  4155  4168 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 16:38:33.619  4155  4168 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 16:38:33.621  4155  4155 I bt_bluedroid: get_profile_interface socket
,08-16 16:38:33.623  4155  4155 I bt_bluedroid: get_profile_interface sdp
,08-16 16:38:33.627  4155  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 16:38:33.628  4155  4166 I bt_bluedroid: config_hci_snoop_log
08-16 16:38:33.629  4155  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 16:38:33.631   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 16:38:33.643  4155  4167 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 16:38:33.643  4155  4167 D BluetoothAdapterProperties: Setting state to 14
,08-16 16:38:33.644  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 16:38:33.647  4155  4167 D BluetoothBondStateMachine: make
,08-16 16:38:33.651  4155  4172 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 16:38:33.654  4155  4167 I BluetoothAdapterState: Entering PendingCommandState
,08-16 16:38:33.656  4155  4155 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 16:38:33.661  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:33.663  4155  4155 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 16:38:33.664  4155  4155 D BtGatt.GattService: Received start request. Starting profile...
,08-16 16:38:33.664  4155  4155 D BtGatt.GattService: start()
08-16 16:38:33.664  4155  4155 I bt_bluedroid: get_profile_interface gatt
08-16 16:38:33.666  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:33.666  4155  4155 D BtGatt.AdvertiseManager: advertise manager created
,08-16 16:38:33.683  4155  4155 V BluetoothAdapterState: isTurningOff()=false
,08-16 16:38:33.684  4155  4155 V BluetoothAdapterState: isTurningOn()=false
08-16 16:38:33.684  4155  4155 V BluetoothAdapterState: isBleTurningOn()=true
08-16 16:38:33.684  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:33.685  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 16:38:33.686  4155  4167 I bt_bluedroid: enable
08-16 16:38:33.686  4155  4168 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 16:38:33.686  4155  4168 I bt_hci  : start_up
,08-16 16:38:33.697  4155  4168 I bt_vendor: alloc value 0xb3a5a189
,08-16 16:38:33.697  4155  4168 I bt_vendor: init
08-16 16:38:33.698  4155  4168 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 16:38:33.698  4155  4168 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 16:38:33.805  4155  4168 D bt_hci  : start_up starting async portion
,08-16 16:38:33.806  4155  4175 I bt_hci  : event_finish_startup
08-16 16:38:33.806  4155  4175 I bt_hci_h4: hal_open
08-16 16:38:33.806  4155  4175 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 16:38:33.817  4155  4175 I bt_userial_vendor: device fd = 51 open
,08-16 16:38:33.847  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 16:38:33.879  4155  4175 D bt_hwcfg: Chipset BCM4354A2
08-16 16:38:33.879  4155  4175 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 16:38:33.880  4155  4175 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 16:38:34.732  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 16:38:34.734  4155  4175 D bt_hwcfg: Settlement delay -- 100 ms
08-16 16:38:34.735  4155  4175 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 16:38:34.853  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 16:38:34.854  4155  4175 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 16:38:34.882  4155  4175 I bt_hwcfg: vendor lib fwcfg completed
,08-16 16:38:34.882  4155  4175 I bt_vendor: firmware callback
08-16 16:38:34.882  4155  4175 I bt_hci  : firmware_config_callback
,08-16 16:38:34.895  4155  4177 I bt_btu  : btu_task pending for preload complete event
,08-16 16:38:34.895  4155  4177 I bt_btu_task: Bluetooth chip preload is complete
08-16 16:38:34.895  4155  4177 I bt_btu  : btu_task received preload complete event
,08-16 16:38:34.905  4155  4177 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 16:38:34.905  4155  4177 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 16:38:34.906  4155  4177 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 16:38:34.906  4155  4177 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 16:38:34.906  4155  4177 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 16:38:34.906  4155  4177 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 16:38:34.907  4155  4177 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 16:38:34.907  4155  4177 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 16:38:34.908  4155  4177 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 16:38:34.909  4155  4177 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 16:38:34.909  4155  4177 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 16:38:34.909  4155  4177 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 16:38:34.911  4155  4177 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 16:38:34.911  4155  4177 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 16:38:34.911  4155  4177 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 16:38:35.061  4155  4177 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d7d9d
,08-16 16:38:35.061  4155  4177 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d7d9d 
,08-16 16:38:35.082  4155  4171 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 16:38:35.084  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 16:38:35.085  4155  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 16:38:35.088  4155  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 16:38:35.092  4155  4171 D BluetoothAdapterProperties: Scan Mode:20
08-16 16:38:35.093  4155  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 16:38:35.093  4155  4171 D bt_hci  : do_postload posting postload work item
08-16 16:38:35.094  4155  4175 I bt_hci  : event_postload
08-16 16:38:35.094  4155  4175 I bt_vendor: sco_config_cb
08-16 16:38:35.094  4155  4175 I bt_hci  : sco_config_callback postload finished.
08-16 16:38:35.097  4155  4171 D bt_bte_conf: Device ID record 1 : primary
08-16 16:38:35.097  4155  4171 D bt_bte_conf:   vendorId            = 000f
08-16 16:38:35.098  4155  4171 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 16:38:35.098  4155  4171 D bt_bte_conf:   product             = 1200
,08-16 16:38:35.098  4155  4171 D bt_bte_conf:   version             = 1436
,08-16 16:38:35.098  4155  4171 D bt_bte_conf:   clientExecutableURL = 
,08-16 16:38:35.099  4155  4171 D bt_bte_conf:   serviceDescription  = 
,08-16 16:38:35.099  4155  4171 D bt_bte_conf:   documentationURL    = 
,08-16 16:38:35.100  4155  4171 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 16:38:35.101  4155  4168 D bt_stack_manager: event_start_up_stack finished
08-16 16:38:35.101  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 16:38:35.102  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:35.103  4155  4175 I bt_vendor: low_power_mode_cb
08-16 16:38:35.103  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 16:38:35.103  4155  4167 D BluetoothAdapterProperties: Setting state to 15
08-16 16:38:35.104  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 16:38:35.105  4155  4167 I BluetoothAdapterState: Entering BleOnState
08-16 16:38:35.109  4155  4167 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 16:38:35.109  4155  4167 D BluetoothAdapterProperties: Setting state to 11
08-16 16:38:35.109  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 16:38:35.116  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:35.119  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:35.121  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:35.124  4155  4155 D HeadsetService: Received start request. Starting profile...
08-16 16:38:35.130  4155  4155 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 16:38:35.130  4155  4155 D HeadsetStateMachine: make
08-16 16:38:35.133  4155  4167 I BluetoothAdapterState: Entering PendingCommandState
,08-16 16:38:35.139  4155  4155 D HeadsetStateMachine: max_hf_connections = 1,
,08-16 16:38:35.139  4155  4155 I bt_bluedroid: get_profile_interface handsfree
08-16 16:38:35.142  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 16:38:35.143  4155  4171 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 16:38:35.146  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:38:35.146  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:35.146  4155  4155 D A2dpService: Received start request. Starting profile...
08-16 16:38:35.147  4155  4155 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 16:38:35.148  4155  4155 I bt_bluedroid: get_profile_interface avrcp
,08-16 16:38:35.156  4155  4155 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 16:38:35.156  4155  4155 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 16:38:35.156  4155  4155 D A2dpStateMachine: make
,08-16 16:38:35.157  4155  4155 I bt_bluedroid: get_profile_interface a2dp
,08-16 16:38:35.159  4155  4186 D A2dpStateMachine: Enter Disconnected: -2
,08-16 16:38:35.160  4155  4155 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 16:38:35.161  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:35.161  4155  4155 D HidService: Received start request. Starting profile...
08-16 16:38:35.161  4155  4155 I bt_bluedroid: get_profile_interface hidhost
08-16 16:38:35.158  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-16 16:38:35.162  4155  4155 D HidService: setHidService(): set to: null
08-16 16:38:35.162  4155  4171 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b93e5
08-16 16:38:35.162  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 16:38:35.162  4155  4155 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 16:38:35.163  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
,08-16 16:38:35.164  4155  4155 D HealthService: Received start request. Starting profile...
,08-16 16:38:35.166  4155  4155 I bt_bluedroid: get_profile_interface health
08-16 16:38:35.167  4155  4155 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 16:38:35.167  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:35.168  4155  4155 D PanService: Received start request. Starting profile...
,08-16 16:38:35.169  4155  4155 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 16:38:35.169  4155  4155 I bt_bluedroid: get_profile_interface pan
,08-16 16:38:35.170  4155  4171 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 16:38:35.173  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:38:35.174  4155  4155 D BluetoothMapService: Received start request. Starting profile...
08-16 16:38:35.174  4155  4155 D BluetoothMapService: start()
,08-16 16:38:35.177  4155  4155 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 16:38:35.177  4155  4155 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 16:38:35.177  4155  4155 D BluetoothMapAppObserver: createReceiver()
08-16 16:38:35.178  4155  4155 D BluetoothMapAppObserver: initObservers()
08-16 16:38:35.179  4155  4155 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 16:38:35.187  4155  4155 V BluetoothAdapterState: isTurningOff()=false
,08-16 16:38:35.188  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:35.188  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:35.188  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:35.188  4155  4184 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:35.191  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isTurningOn()=true
,08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-16 16:38:35.192  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-16 16:38:35.193  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 16:38:35.193  4155  4167 D BluetoothAdapterProperties: ScanMode =  20
08-16 16:38:35.193  4155  4167 D BluetoothAdapterProperties: State =  11
,08-16 16:38:35.196  4155  4171 D BluetoothAdapterProperties: Scan Mode:21
08-16 16:38:35.197  4155  4167 D BluetoothAdapterProperties: Setting state to 12
08-16 16:38:35.197  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 16:38:35.197  4155  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 16:38:35.197  4155  4167 I BluetoothAdapterState: Entering OnState
08-16 16:38:35.197  3869  4148 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 16:38:35.200  3869  3869 D BluetoothA2dp: Proxy object connected
08-16 16:38:35.201   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:38:35.201  1363  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:35.201  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:35.203  3869  3880 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 16:38:35.203  1363  1363 D BluetoothInputDevice: Proxy object connected
08-16 16:38:35.204  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:38:35.204  1363  1363 D HidProfile: Bluetooth service connected
,08-16 16:38:35.206  4155  4155 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 16:38:35.206  3869  4148 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 16:38:35.207  4155  4155 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 16:38:35.208  4155  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:38:35.208  3869  3879 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:35.209  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:35.210  4155  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:38:35.210  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:38:35.211  1363  1675 D BluetoothPan: onBluetoothStateChange on: true
,08-16 16:38:35.213  4155  4155 D ObexServerSockets: Succeed to create listening sockets 
08-16 16:38:35.213  4155  4155 D ObexServerSockets0: startAccept()
08-16 16:38:35.213  4155  4155 D ObexServerSockets0: prepareForNewConnect()
08-16 16:38:35.213  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:35.214  3869  3880 D BluetoothPan: onBluetoothStateChange on: true
08-16 16:38:35.215  4155  4155 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 16:38:35.215  1363  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 16:38:35.215  4155  4155 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 16:38:35.216  1941  1953 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:38:35.217  4155  4193 D ObexServerSockets0: Accepting socket connection...
08-16 16:38:35.217  4155  4192 D ObexServerSockets0: Accepting socket connection...
08-16 16:38:35.217   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:38:35.217  1363  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 16:38:35.217  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:38:35.217  1363  1363 D PanProfile: Bluetooth service connected
08-16 16:38:35.218   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 16:38:35.218  1363  1363 D BluetoothA2dp: Proxy object connected
,08-16 16:38:35.219   873   873 D BluetoothA2dp: Proxy object connected
08-16 16:38:35.219  1363  1376 D BluetoothMap: onBluetoothStateChange: up=true
08-16 16:38:35.221  3869  3869 D BluetoothInputDevice: Proxy object connected
08-16 16:38:35.221  3869  3869 D HidProfile: Bluetooth service connected
08-16 16:38:35.222  3869  3880 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:38:35.222   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:38:35.223   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 16:38:35.224  4155  4155 D BluetoothMapService: onReceive
,08-16 16:38:35.224  4155  4155 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 16:38:35.224  4155  4155 D BluetoothMapService: STATE_ON
,08-16 16:38:35.227  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 16:38:35.229  3869  3869 D BluetoothMap: Proxy object connected
,08-16 16:38:35.229  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:38:35.229  3869  3869 D MapProfile: Bluetooth service connected
08-16 16:38:35.229  3869  3869 D BluetoothMap: getConnectedDevices()
08-16 16:38:35.231  3869  3869 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:38:35.231  3869  3869 D PanProfile: Bluetooth service connected
08-16 16:38:35.232  1363  1363 D BluetoothMap: Proxy object connected
08-16 16:38:35.232  1363  1363 D MapProfile: Bluetooth service connected
08-16 16:38:35.232  1363  1363 D BluetoothMap: getConnectedDevices()
,08-16 16:38:35.237  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 16:38:35.246  1498  1498 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:38:35.247  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:38:35.252  3869  3869 D BluetoothPbap: Proxy object connected
,08-16 16:38:35.252  3869  3869 D PbapServerProfile: Bluetooth service connected
,08-16 16:38:35.254  1363  1363 D BluetoothPbap: Proxy object connected
,08-16 16:38:35.254  1363  1363 D PbapServerProfile: Bluetooth service connected
08-16 16:38:35.255  4155  4155 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 16:38:35.255  4155  4155 D ObexServerSockets0: prepareForNewConnect()
,08-16 16:38:35.262  4155  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:38:35.279  4155  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:38:35.280  4155  4202 I BtOppRfcommListener: Accept thread started.
,08-16 16:38:35.303  1363  2046 D BluetoothHeadset: Proxy object connected
08-16 16:38:35.303  1363  1363 D HeadsetProfile: Bluetooth service connected
08-16 16:38:35.303   873   873 D BluetoothHeadset: Proxy object connected
,08-16 16:38:35.303   873   873 D BluetoothHeadset: Proxy object connected
,08-16 16:38:35.303  1941  2234 D BluetoothHeadset: Proxy object connected
08-16 16:38:35.304  3869  4148 D BluetoothHeadset: Proxy object connected
08-16 16:38:35.304   873   873 D BluetoothHeadset: Proxy object connected
,08-16 16:38:35.304  3869  3869 D HeadsetProfile: Bluetooth service connected
,08-16 16:38:35.310  1363  1376 D BluetoothHeadset: Proxy object connected
,08-16 16:38:35.310  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-16 16:38:35.317  1941  1951 D BluetoothHeadset: Proxy object connected
,08-16 16:38:35.318   873   890 D BluetoothHeadset: Proxy object connected
,08-16 16:38:35.323  3869  3879 D BluetoothHeadset: Proxy object connected
08-16 16:38:35.323  3869  3869 D HeadsetProfile: Bluetooth service connected
,08-16 16:38:35.323   873   890 D BluetoothHeadset: Proxy object connected
,08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:38.437  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:38.444  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:38.445  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:38:38.446  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5dee54a removed from the list
,08-16 16:38:38.446  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:38:38.446  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:38:38.447  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:38:38.449  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 16:38:38.450  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b005cbb added. We now have 4 listener(s)
08-16 16:38:38.450  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:38:38.455   873  1970 D WifiService: setWifiEnabled: false pid=3765, uid=10000
08-16 16:38:38.456   873  1970 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:38:41.087  1865  1913 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 16:38:41.087  1865  1913 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 16:38:41.127  1498  1498 I ConfigService: onCreate
,08-16 16:38:43.471  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:38:43.473   873  1991 D WifiService: setWifiEnabled: true pid=3765, uid=10000
,08-16 16:38:43.473   873  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:38:43.487   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:43.506  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:38:43.513  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:38:43.521  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:38:43.524  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:38:43.531   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-16 16:38:43.532   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 16:38:43.533   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 16:38:43.533   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 16:38:43.534   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 16:38:43.534   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 16:38:43.534   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 16:38:43.550   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 16:38:43.552   372   871 D CommandListener: Setting iface cfg
08-16 16:38:43.552   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 16:38:43.555   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 16:38:43.556   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 16:38:43.607   873  1305 E native  : do suspend true
,08-16 16:38:43.613   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 16:38:43.629   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 16:38:43.645   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:38:44.966   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 16:38:45.113   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.62 rxSuccessRate=14.75 delta 1000 -> 994
,08-16 16:38:45.115   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-16 16:38:45.115   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:38:45.133   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 16:38:45.196   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 16:38:45.202  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 16:38:45.648  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 16:38:45.690  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 16:38:45.691  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 16:38:45.702   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 16:38:45.718   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 16:38:45.719   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:38:45.719   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 16:38:45.745   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:38:45.766   372   871 D CommandListener: Setting iface cfg
,08-16 16:38:45.767   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 16:38:45.787   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 16:38:45.811   873  4211 D DhcpClient: Receive thread started
,08-16 16:38:45.909   873  1305 E native  : do suspend false
,08-16 16:38:45.934   873  2086 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 16:38:45.947   873  4211 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-16 16:38:45.949   873  2086 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-16 16:38:45.953   873  2086 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 16:38:45.977   873  4211 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 16:38:45.978   873  2086 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 16:38:45.984   372   871 D CommandListener: Setting iface cfg
,08-16 16:38:45.994   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 16:38:45.995   873  2086 D DhcpClient: Scheduling renewal in 86399s
08-16 16:38:45.997   873  1305 E native  : do suspend true
,08-16 16:38:46.022   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 16:38:46.024   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 16:38:46.026   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 16:38:46.029   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 16:38:46.034   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 16:38:46.088   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 16:38:46.089   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 16:38:46.095   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 16:38:46.099   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 16:38:46.104   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 16:38:46.115   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 16:38:46.120   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 16:38:46.120   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 16:38:46.120   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 16:38:46.121   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 16:38:46.121   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 16:38:46.121   873  1308 D ConnectivityService:    accepting network in place of null
08-16 16:38:46.123   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 16:38:46.139   873  4210 D NetlinkSocketObserver: NeighborEvent{elapsedMs=215250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 16:38:46.180   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:46.199  1498  1498 I ConfigService: onDestroy
,08-16 16:38:46.226   873  4209 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:80b::200e
,08-16 16:38:46.227   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 16:38:46.235   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 16:38:46.238   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:46.246   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 16:38:46.250   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:46.262  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:38:46.265  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:46.272  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:38:46.276  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:46.286  1681  1681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 16:38:46.291  1681  1681 D SystemUpdateService: onCreate
,08-16 16:38:46.294  1681  1681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 16:38:46.303   873  4209 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 14:38:46 GMT], X-Android-Received-Millis=[1471358326301], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471358326271]}
,08-16 16:38:46.304   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 16:38:46.304   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-16 16:38:46.304   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 16:38:46.306   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 16:38:46.316  1681  4220 I SystemUpdateService: active receiver: enabled
,08-16 16:38:46.321  1681  1681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 16:38:46.326  1681  2513 I iu.UploadsManager: num queued entries: 0
,08-16 16:38:46.326  1681  2513 I iu.UploadsManager: num updated entries: 0
08-16 16:38:46.327  1681  2513 I iu.SyncManager: NEXT; no task
,08-16 16:38:46.333  1681  1681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 16:38:46.334  1681  1681 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 16:38:46.337  3923  3923 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:38:46.341  3923  3923 D SprintDMHelper: simOperator: 
,08-16 16:38:46.341  3923  3923 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 16:38:46.344  1681  4223 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 16:38:46.344  1681  4223 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 16:38:46.349  1681  4223 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 16:38:46.368  1681  4220 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 16:38:46.375  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:46.376  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 16:38:46.386  1681  4220 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 16:38:46.387  1681  4220 I SystemUpdateService: now status is 0 (complete)
08-16 16:38:46.387  1681  4220 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 16:38:46.387  1681  4220 I SystemUpdateService: file has been verified
,08-16 16:38:46.387  1681  4220 I SystemUpdateService: OTA package size = 12249756
,08-16 16:38:46.405  1681  4220 I SystemUpdateService: showing system update notification
,08-16 16:38:46.416  1498  1989 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 16:38:46.416  1498  1989 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 16:38:46.416  1498  1989 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 16:38:46.416  1498  1989 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 16:38:46.440  1681  1681 D SystemUpdateService: onDestroy
,08-16 16:38:46.447  1681  4223 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-16 16:38:46.489  2200  4226 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 16:38:47.235   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:38:48.500  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:38:48.507  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:38:48.508  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:38:48.509  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b005cbb removed from the list
,08-16 16:38:48.509  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:38:48.509  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:38:48.510  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:38:48.522  3765  4233 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-16 16:38:48.522  3765  4233 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 16:38:51.529  3765  4234 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-16 16:38:51.530  3765  4233 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 16:38:51.531  3765  4233 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 16:38:51.531  3765  4234 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 16:38:51.532  3765  4233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:38:51.533  3765  4234 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:38:51.533  3765  4233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:38:51.534  3765  4234 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 16:38:51.537  3765  4236 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: OutgoingSocketThread/Sender)
08-16 16:38:51.538  3765  4233 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 16:38:51.539  3765  4234 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 16:38:51.544  3765  4237 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: IncomingSocketThread/Sender)
,08-16 16:38:51.547  3765  4238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: OutgoingSocketThread/Receiver)
08-16 16:38:51.548  3765  4238 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: OutgoingSocketThread/Receiver)
,08-16 16:38:51.549  3765  4238 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 16:38:51.549  3765  4238 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 16:38:51.550  3765  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: IncomingSocketThread/Receiver)
08-16 16:38:51.552  3765  4239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 420, thread name: IncomingSocketThread/Receiver)
08-16 16:38:51.552  3765  4239 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 16:38:51.552  3765  4239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 16:38:54.127   873  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-16 16:38:54.528  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 16:38:54.530  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 16:38:54.537  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@951a355 Bundle[{}]
,08-16 16:38:54.538  3765  3815 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 16:38:54.538  3765  3815 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 16:38:54.539  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 16:38:54.539  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 16:38:54.540  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 16:38:54.540  3765  3815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 16:38:54.544  3765  3815 I System.out: Running OutgoingSocketThread
08-16 16:38:54.546  3765  4240 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-16 16:38:54.546  3765  4240 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 16:38:57.557  3765  4241 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-16 16:38:57.557  3765  4241 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 16:38:57.558  3765  4241 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:38:57.558  3765  4240 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 16:38:57.559  3765  4240 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 16:38:57.559  3765  4240 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 16:38:57.560  3765  4241 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:38:57.562  3765  4240 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 16:38:57.566  3765  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Sender)
,08-16 16:38:57.567  3765  4241 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 16:38:57.567  3765  4240 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 16:38:57.572  3765  4244 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Sender)
,08-16 16:38:57.575  3765  4245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Receiver)
,08-16 16:38:57.578  3765  4245 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: IncomingSocketThread/Receiver)
08-16 16:38:57.579  3765  4245 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-16 16:38:57.579  3765  4245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 16:38:57.579  3765  4246 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Receiver)
,08-16 16:38:57.580  3765  4246 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: OutgoingSocketThread/Receiver)
08-16 16:38:57.581  3765  4246 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 16:38:57.581  3765  4246 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 16:39:00.560  3765  3815 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-16 16:39:00.563  3765  3815 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 16:39:00.563  3765  3815 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-16 16:39:00.578  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 16:39:00.578  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0aa5d8 added. We now have 3 listener(s)
08-16 16:39:00.586  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 16:39:00.588  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 16:39:00.588  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:39:00.590  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:39:00.591  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3209d31 added. We now have 4 listener(s)
,08-16 16:39:00.594  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:39:00.596  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:39:00.605  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:39:00.616  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:39:00.621  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:39:00.622  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:39:00.623  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:39:00.623  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:39:00.623  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:39:00.624  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:00.624  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:39:00.625  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:39:00.625  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:39:00.625  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0aa5d8 removed from the list
08-16 16:39:00.626  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:00.626  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3209d31 removed from the list
,08-16 16:39:00.628  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:00.630  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:39:00.630  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:39:00.630  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:00.632  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:00.632  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:00.636  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:39:00.636  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:00.637  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:00.638  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3209d31 not in the list
,08-16 16:39:00.638  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:00.639  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:00.642  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:00.642  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 16:39:00.642  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:00.643  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3209d31 not in the list
,08-16 16:39:00.643  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:00.643  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:39:00.643  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:00.643  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0aa5d8 not in the list
,08-16 16:39:00.644  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 16:39:00.644  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ce0997 added. We now have 3 listener(s)
08-16 16:39:00.646  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 16:39:00.646  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:39:00.646  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:39:00.647  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:39:00.647  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1704784 added. We now have 4 listener(s)
08-16 16:39:00.647  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:39:00.647  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:39:00.650  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:39:00.654  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:39:00.657  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:39:00.657  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:39:00.657  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:39:00.657  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:39:00.657  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:39:00.657  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:39:00.657  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 16:39:00.659  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:00.661  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:00.661  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 16:39:00.662  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 16:39:00.666  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 16:39:00.667  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 16:39:00.667  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 16:39:00.671  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 16:39:00.671  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 16:39:00.672  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 16:39:00.673  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:39:00.675  4155  4191 D BtGatt.GattService: registerClient() - UUID=6fecab36-123b-4aeb-b86c-e1313b3d1bce
08-16 16:39:00.676  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=6fecab36-123b-4aeb-b86c-e1313b3d1bce, clientIf=5
,08-16 16:39:00.677  3765  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 16:39:00.678  4155  4183 D BtGatt.GattService: start scan with filters
,08-16 16:39:00.682  4155  4174 D BtGatt.ScanManager: handling starting scan
,08-16 16:39:00.683  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 16:39:00.683  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 16:39:00.683  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 16:39:00.683  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 16:39:00.684  4155  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d3699
08-16 16:39:00.686  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 16:39:00.686  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 16:39:00.686  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 16:39:00.688  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 16:39:00.690  3765  3815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 16:39:00.691  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:39:00.691  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 16:39:00.691  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:00.691  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 16:39:00.691  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:39:00.691  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:39:00.691  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 16:39:00.691  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 16:39:00.692  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 16:39:00.692  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 16:39:00.693  3765  3815 D BluetoothAdapter: STATE_ON
08-16 16:39:00.694  4155  4165 D BtGatt.GattService: stopScan() - queue size =1
08-16 16:39:00.694  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 16:39:00.694  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:00.695  4155  4183 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 16:39:00.695  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 16:39:00.695  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:39:00.695  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 16:39:00.697  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 16:39:00.697  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 16:39:00.697  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 16:39:00.698  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:39:00.699  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 16:39:00.699  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 16:39:00.699  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:39:00.700  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 16:39:00.702  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:39:00.702  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 16:39:00.702  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:39:00.703  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 16:39:00.703  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:00.704  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 16:39:00.704  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 16:39:00.718  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 16:39:00.718  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:00.731  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 16:39:00.731  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:00.746  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 16:39:00.746  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:00.747  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
,08-16 16:39:00.762  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 16:39:00.762  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:00.763  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:39:00.799  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-16 16:39:00.799  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:00.800  4155  4171 D BtGatt.GattService: current time is 229911788982
,08-16 16:39:00.801  4155  4171 D BtGatt.GattService: Batch record : [78, -20, -96, 83, -39, -56, 1, -128, -68, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 118, 39, 0]
,08-16 16:39:00.805  4155  4171 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 118, 39]
,08-16 16:39:01.203  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 16:39:01.204  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:39:01.204  3765  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 16:39:03.702  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:39:03.703  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:39:03.703  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:39:03.703  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:03.704  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:39:03.704  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:39:03.704  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:39:03.705  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ce0997 removed from the list
08-16 16:39:03.705  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:39:03.706  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1704784 removed from the list
08-16 16:39:03.706  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:39:03.707  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:03.708  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:39:03.709  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:03.712  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:03.712  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:03.712  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:03.713  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1704784 not in the list
08-16 16:39:03.713  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:03.713  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:03.717  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:39:03.718  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:03.718  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:03.718  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1704784 not in the list
,08-16 16:39:03.719  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:03.719  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:03.719  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:03.720  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ce0997 not in the list
08-16 16:39:03.723  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:39:03.723  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8cc169 added. We now have 3 listener(s)
,08-16 16:39:03.726  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 16:39:03.726  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 16:39:03.726  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:39:03.726  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:39:03.727  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21287ee added. We now have 4 listener(s)
08-16 16:39:03.727  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:39:03.728  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:39:03.734  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:39:03.745  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:39:03.749  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:39:03.750  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:39:03.750  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 16:39:03.751  3765  3815 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 16:39:03.751  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 16:39:03.751  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 16:39:03.751  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 16:39:03.751  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 16:39:03.752  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:39:03.753  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 16:39:03.755  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 16:39:03.755  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 16:39:03.755  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 16:39:03.756  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 16:39:03.756  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:39:03.756  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:39:03.756  3765  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:39:03.759  3765  4247 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 16:39:03.761  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:03.768  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 16:39:03.768  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 16:39:03.769  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:39:03.770  3765  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 16:39:03.774  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 16:39:03.775  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 16:39:03.775  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 16:39:03.779  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 16:39:03.779  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 16:39:03.780  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-16 16:39:03.781  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 16:39:03.781  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 16:39:03.781  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-16 16:39:03.783  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:39:03.787  4155  4166 D BtGatt.GattService: registerClient() - UUID=dccdd218-8aae-42ba-9eb9-f8fde64d53e3
,08-16 16:39:03.788  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=dccdd218-8aae-42ba-9eb9-f8fde64d53e3, clientIf=5
,08-16 16:39:03.789  3765  3776 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 16:39:03.791  4155  4173 D BtGatt.AdvertiseManager: message : 0
,08-16 16:39:03.795  4155  4173 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 16:39:03.814  4155  4171 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 16:39:03.831  4155  4171 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 16:39:03.834  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 16:39:03.834  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 16:39:03.838  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 16:39:03.843  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 16:39:03.844  3765  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 16:39:03.844  3765  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-16 16:39:03.844  3765  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 16:39:03.845  3765  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-16 16:39:03.845  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 16:39:03.847  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 16:39:03.853  3765  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 16:39:03.853  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 16:39:04.354  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 16:39:04.355  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 16:39:04.355  3765  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 16:39:06.848  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:39:06.849  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-16 16:39:06.849  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 16:39:06.849  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 16:39:06.850  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 16:39:06.850  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 16:39:06.854  3765  4247 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-16 16:39:06.854  3765  4247 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 16:39:06.855  3765  4247 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 16:39:06.856  3765  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 16:39:06.858  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 16:39:06.859  3765  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-16 16:39:06.860  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:39:06.860  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:39:06.861  3765  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 16:39:06.861  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 16:39:06.861  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 16:39:06.861  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 16:39:06.864  3765  3815 D BluetoothAdapter: STATE_ON
08-16 16:39:06.864  3765  3815 D BluetoothLeScanner: could not find callback wrapper
08-16 16:39:06.865  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 16:39:06.865  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-16 16:39:06.867  4155  4173 D BtGatt.AdvertiseManager: message : 1
08-16 16:39:06.867  4155  4173 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 16:39:06.874  4155  4171 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-16 16:39:06.875  4155  4171 D BtGatt.GattService: Client app is not null!
08-16 16:39:06.875  4155  4191 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 16:39:06.876  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 16:39:06.877  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-16 16:39:06.877  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 16:39:06.878  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-16 16:39:06.878  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-16 16:39:06.882  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:39:06.882  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 16:39:06.882  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:39:06.883  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 16:39:06.886  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:06.886  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:06.886  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:39:06.886  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:39:06.886  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8cc169 removed from the list
08-16 16:39:06.886  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:06.887  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21287ee removed from the list
08-16 16:39:06.887  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:39:06.887  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:06.887  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:39:06.887  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:39:06.887  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:06.888  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:06.888  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:39:06.889  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:06.889  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:06.889  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:06.889  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21287ee not in the list
08-16 16:39:06.889  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:06.889  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:06.890  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:39:06.890  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:06.890  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:06.891  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21287ee not in the list
08-16 16:39:06.891  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:06.891  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:06.891  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:06.891  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8cc169 not in the list
08-16 16:39:06.892  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 16:39:06.892  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fdeaab added. We now have 3 listener(s)
08-16 16:39:06.895  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 16:39:06.895  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:39:06.895  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 16:39:06.895  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:39:06.895  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdf3508 added. We now have 4 listener(s)
08-16 16:39:06.895  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:39:06.896  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:39:06.899  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:39:06.904  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:39:06.906  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:39:06.906  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:39:06.906  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:39:06.906  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:39:06.906  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:39:06.906  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:39:06.906  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 16:39:06.908  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:06.910  3765  3815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 16:39:06.910  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 16:39:06.911  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:06.915  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 16:39:06.916  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 16:39:06.916  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 16:39:06.919  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 16:39:06.919  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 16:39:06.919  3765  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 16:39:06.920  3765  3815 D BluetoothAdapter: STATE_ON
,08-16 16:39:06.923  4155  4191 D BtGatt.GattService: registerClient() - UUID=05dde5a0-bd0d-4f9d-a36a-48f1a7e45783
,08-16 16:39:06.923  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=05dde5a0-bd0d-4f9d-a36a-48f1a7e45783, clientIf=5
08-16 16:39:06.924  3765  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 16:39:06.924  4155  4165 D BtGatt.GattService: start scan with filters
,08-16 16:39:06.927  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 16:39:06.927  4155  4174 D BtGatt.ScanManager: handling starting scan
,08-16 16:39:06.927  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 16:39:06.927  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 16:39:06.927  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 16:39:06.931  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 16:39:06.931  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 16:39:06.931  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 16:39:06.934  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 16:39:06.934  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 16:39:06.934  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:06.934  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 16:39:06.941  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 16:39:06.941  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:06.941  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
08-16 16:39:06.942  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 16:39:06.959  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 16:39:06.959  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:06.968  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 16:39:06.968  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:07.389  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 16:39:07.431  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 16:39:07.432  3765  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:39:07.432  3765  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 16:39:08.477  4155  4155 D BtGatt.ScanManager: awakened up at time 237588
,08-16 16:39:08.482  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 16:39:08.531  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,08-16 16:39:08.531  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:08.531  4155  4171 D BtGatt.GattService: current time is 237643173624
,08-16 16:39:08.533  4155  4171 D BtGatt.GattService: Batch record : [-14, -127, 37, 111, 109, 95, 1, -128, -57, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -126, -22, -96, 83, -39, -56, 1, -128, -61, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, -52, 11, 57, -70, 107, -17, 1, 0, -103, 2, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 37, -47, 14, -113, 116, -46, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -90, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:39:08.533  4155  4171 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-16 16:39:08.533  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 16:39:08.533  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 16:39:08.534  4155  4171 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
08-16 16:39:08.534  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
08-16 16:39:08.534  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 16:39:08.534  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 16:39:08.535  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 16:39:08.538  3765  3765 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-16 16:39:08.539  3765  3765 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 2
08-16 16:39:08.539  3765  3765 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
08-16 16:39:08.540  3765  3765 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,08-16 16:39:09.946  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:39:09.946  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 16:39:09.946  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 16:39:09.947  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:09.947  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 16:39:09.947  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:39:09.948  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 16:39:09.948  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 16:39:09.948  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 16:39:09.949  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 16:39:09.950  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 16:39:09.953  3765  3815 D BluetoothAdapter: STATE_ON
08-16 16:39:09.955  4155  4194 D BtGatt.GattService: stopScan() - queue size =1
,08-16 16:39:09.958  4155  4191 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 16:39:09.959  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:39:09.960  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 16:39:09.960  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 16:39:09.961  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 16:39:09.961  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 16:39:09.967  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:39:09.967  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 16:39:09.967  3765  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 16:39:09.968  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:39:09.969  4155  4155 D BtGatt.ScanManager: awakened up at time 239080
08-16 16:39:09.970  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:39:09.971  3765  3815 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-16 16:39:09.978  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:39:09.978  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:09.978  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:39:09.978  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 16:39:09.978  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:09.978  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:39:09.979  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:39:09.979  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fdeaab removed from the list
08-16 16:39:09.979  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:09.979  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdf3508 removed from the list
08-16 16:39:09.980  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 16:39:09.980  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:09.981  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 16:39:09.981  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:09.981  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:09.981  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:09.982  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
,08-16 16:39:09.984  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:09.984  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:09.984  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:09.984  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdf3508 not in the list
08-16 16:39:09.985  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:39:09.985  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:09.988  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:39:09.989  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:09.989  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:09.989  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdf3508 not in the list
08-16 16:39:09.989  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:39:09.990  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:09.990  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:09.990  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fdeaab not in the list
08-16 16:39:09.990  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 16:39:09.990  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 16:39:09.991  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 16:39:09.992  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:39:09.992  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe30423 added. We now have 3 listener(s)
,08-16 16:39:09.999  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 16:39:09.999  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:39:09.999  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:39:09.999  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:39:09.999  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fd9d20 added. We now have 4 listener(s)
08-16 16:39:10.000  3765  3815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:39:10.000  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:39:10.004  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:39:10.005  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-16 16:39:10.005  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 16:39:10.005  4155  4171 D BtGatt.GattService: current time is 239116807769
08-16 16:39:10.005  4155  4171 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -103, 2, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, 71, -122, -77, 84, 69, -12, 1, -128, -89, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 16:39:10.006  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
08-16 16:39:10.006  4155  4171 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:39:10.010  3765  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:39:10.012  3765  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:39:10.013  3765  3815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:39:10.013  3765  3815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:39:10.013  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:39:10.013  3765  3815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:39:10.013  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:10.013  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:10.013  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 16:39:10.013  3765  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:39:10.014  3765  3815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe30423 removed from the list
08-16 16:39:10.014  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:10.014  3765  3815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fd9d20 removed from the list
,08-16 16:39:10.017  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:10.019  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:39:10.019  3765  3815 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:39:10.019  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:10.020  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:10.020  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:10.021  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:10.021  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:10.021  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:10.021  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fd9d20 not in the list
08-16 16:39:10.021  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:10.021  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:39:10.022  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:39:10.022  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:39:10.022  3765  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:39:10.023  3765  3815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fd9d20 not in the list
,08-16 16:39:10.023  3765  3815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:39:10.023  3765  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:39:10.023  3765  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:39:10.023  3765  3815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe30423 not in the list
08-16 16:39:10.024  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 16:39:10.024  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 16:39:10.024  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 16:39:10.024  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:39:10.024  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 16:39:10.024  3765  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 16:39:10.479  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 16:39:12.039  3765  4249 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
,08-16 16:39:14.037  3765  3815 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 451
,08-16 16:39:14.037  3765  3815 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 451, name: My test thread name)
,08-16 16:39:14.043  3765  4250 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
,08-16 16:39:14.044  3765  4250 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: My test thread name)
08-16 16:39:14.044  3765  4250 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 16:39:14.048  3765  3815 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 16:39:14.057  3765  4251 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,08-16 16:39:14.057  3765  4251 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 456, thread name: My test thread name): Test exception.
08-16 16:39:14.058  3765  4251 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 16:39:14.066  3765  3815 I jxcore-log: Total number of executed tests:  82
08-16 16:39:14.066  3765  3815 I jxcore-log: 
,08-16 16:39:14.067  3765  3815 I jxcore-log: Number of passed tests:  82
08-16 16:39:14.067  3765  3815 I jxcore-log: 
08-16 16:39:14.067  3765  3815 I jxcore-log: Number of failed tests:  0
08-16 16:39:14.067  3765  3815 I jxcore-log: 
,08-16 16:39:14.068  3765  3815 I jxcore-log: Number of ignored tests:  0
08-16 16:39:14.068  3765  3815 I jxcore-log: 
08-16 16:39:14.070  3765  3815 I jxcore-log: Total duration:  101356
08-16 16:39:14.070  3765  3815 I jxcore-log: 
,08-16 16:39:14.071  3765  3815 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 16:39:14.071  3765  3815 I jxcore-log: 
,08-16 16:39:14.085  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.085  3765  3815 I jxcore-log: 
,08-16 16:39:14.097  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.097  3765  3815 I jxcore-log: 
,08-16 16:39:14.099  3765  3765 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 16:39:14.099  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.099  3765  3815 I jxcore-log: 
,08-16 16:39:14.104  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.104  3765  3815 I jxcore-log: 
,08-16 16:39:14.108  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 16:39:14.108  3765  3815 I jxcore-log: 
,08-16 16:39:14.109  3765  4249 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-16 16:39:14.113  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:39:14.113  3765  3815 I jxcore-log: 
,08-16 16:39:14.122  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.122  3765  3815 I jxcore-log: 
,08-16 16:39:14.128  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.128  3765  3815 I jxcore-log: 
,08-16 16:39:14.130  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 16:39:14.130  3765  3815 I jxcore-log: 
,08-16 16:39:14.132  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:39:14.132  3765  3815 I jxcore-log: 
,08-16 16:39:14.134  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:39:14.134  3765  3815 I jxcore-log: 
,08-16 16:39:14.136  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.136  3765  3815 I jxcore-log: 
08-16 16:39:14.137  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.137  3765  3815 I jxcore-log: 
08-16 16:39:14.138  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.138  3765  3815 I jxcore-log: 
08-16 16:39:14.139  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.139  3765  3815 I jxcore-log: 
,08-16 16:39:14.140  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.140  3765  3815 I jxcore-log: 
,08-16 16:39:14.141  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.141  3765  3815 I jxcore-log: 
,08-16 16:39:14.143  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.143  3765  3815 I jxcore-log: 
,08-16 16:39:14.145  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.145  3765  3815 I jxcore-log: 
,08-16 16:39:14.147  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.147  3765  3815 I jxcore-log: 
,08-16 16:39:14.149  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.149  3765  3815 I jxcore-log: 
,08-16 16:39:14.151  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.151  3765  3815 I jxcore-log: 
,08-16 16:39:14.153  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.153  3765  3815 I jxcore-log: 
,08-16 16:39:14.154  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.154  3765  3815 I jxcore-log: 
,08-16 16:39:14.156  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.156  3765  3815 I jxcore-log: 
,08-16 16:39:14.158  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.158  3765  3815 I jxcore-log: 
,08-16 16:39:14.159  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.159  3765  3815 I jxcore-log: 
,08-16 16:39:14.161  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.161  3765  3815 I jxcore-log: 
,08-16 16:39:14.163  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.163  3765  3815 I jxcore-log: 
,08-16 16:39:14.164  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.164  3765  3815 I jxcore-log: 
,08-16 16:39:14.165  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.165  3765  3815 I jxcore-log: 
,08-16 16:39:14.165  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.165  3765  3815 I jxcore-log: 
,08-16 16:39:14.167  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.167  3765  3815 I jxcore-log: 
,08-16 16:39:14.167  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.167  3765  3815 I jxcore-log: 
,08-16 16:39:14.168  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.168  3765  3815 I jxcore-log: 
,08-16 16:39:14.169  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.169  3765  3815 I jxcore-log: 
08-16 16:39:14.170  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.170  3765  3815 I jxcore-log: 
,08-16 16:39:14.171  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.171  3765  3815 I jxcore-log: 
,08-16 16:39:14.171  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.171  3765  3815 I jxcore-log: 
08-16 16:39:14.172  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.172  3765  3815 I jxcore-log: 
,08-16 16:39:14.173  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:39:14.173  3765  3815 I jxcore-log: 
,08-16 16:39:14.174  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.174  3765  3815 I jxcore-log: 
,08-16 16:39:14.175  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 16:39:14.175  3765  3815 I jxcore-log: 
,08-16 16:39:14.176  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.176  3765  3815 I jxcore-log: 
08-16 16:39:14.176  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.176  3765  3815 I jxcore-log: 
,08-16 16:39:14.177  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.177  3765  3815 I jxcore-log: 
,08-16 16:39:14.178  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.178  3765  3815 I jxcore-log: 
,08-16 16:39:14.179  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.179  3765  3815 I jxcore-log: 
08-16 16:39:14.180  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:39:14.180  3765  3815 I jxcore-log: 
,08-16 16:39:14.181  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.181  3765  3815 I jxcore-log: 
,08-16 16:39:14.181  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 16:39:14.181  3765  3815 I jxcore-log: 
,08-16 16:39:14.182  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.182  3765  3815 I jxcore-log: 
,08-16 16:39:14.183  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:39:14.183  3765  3815 I jxcore-log: 
,08-16 16:39:14.184  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 16:39:14.184  3765  3815 I jxcore-log: 
,08-16 16:39:14.186  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-16 16:39:14.186  3765  3815 I jxcore-log: 
08-16 16:39:14.187  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-16 16:39:14.187  3765  3815 I jxcore-log: 
08-16 16:39:14.187  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:39:14.187  3765  3815 I jxcore-log: 
,08-16 16:39:14.188  3765  3815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:39:14.188  3765  3815 I jxcore-log: 
,08-16 16:39:14.678  4252  4252 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 16:39:14.683  4252  4252 D AndroidRuntime: CheckJNI is OFF
,08-16 16:39:14.725  4252  4252 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 16:39:14.772  4252  4252 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 16:39:14.794  4252  4252 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 16:39:14.807   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 16:39:14.808   873   886 I ActivityManager: Killing 3765:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 16:39:14.905   873   896 W PackageSettings: Skipping PackageSetting{430d8e2 com.example.hello/10273} due to missing metadata
,08-16 16:39:14.942   873  1382 D GraphicsStats: Buffer count: 2
,08-16 16:39:14.943   873  3735 I WindowState: WIN DEATH: Window{7bf8961 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 16:39:14.943   873  1307 D WifiService: Client connection lost with reason: 4
,08-16 16:39:14.956   873   896 I art     : Starting a blocking GC Explicit
,08-16 16:39:14.976   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 16:39:14.977   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 16:39:14.978   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 16:39:14.978   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 16:39:14.978   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:14.978   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:14.978   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 16:39:14.978   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 16:39:14.979   873   886 I ActivityManager:   Force finishing activity ActivityRecord{53a684e u0 com.test.thalitest/.MainActivity t2}
,08-16 16:39:14.990   873  1382 W ActivityManager: Spurious death for ProcessRecord{ab5330d 0:com.test.thalitest/u0a0}, curProc for 3765: null
,08-16 16:39:15.044   873   896 I art     : Explicit concurrent mark sweep GC freed 53814(3MB) AllocSpace objects, 9(224KB) LOS objects, 33% free, 29MB/43MB, paused 1.159ms total 85.712ms
,08-16 16:39:15.080   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 16:39:15.082  4252  4252 I art     : System.exit called, status: 0
,08-16 16:39:15.082  4252  4252 I AndroidRuntime: VM exiting with result code 0.
08-16 16:39:15.085   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 16:39:15.110   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 16:39:15.115  1865  1865 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 16:39:15.116  4155  4155 D BluetoothMapAppObserver: onReceive
08-16 16:39:15.116  4155  4155 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 16:39:15.117  1877  2224 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 16:39:15.117   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 16:39:15.121  3632  3632 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 16:39:15.128  1865  4263 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 16:39:15.167  1941  1941 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 16:39:15.167   873  1382 I ActivityManager: Start proc 4266:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 16:39:15.170  1865  4263 I Decoder : createOrResetDecoder
,08-16 16:39:15.181  1498  1498 I ConfigService: onCreate
,08-16 16:39:15.191   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 16:39:15.221  4266  4266 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 16:39:15.229  1865  4263 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 16:39:15.239   873  1991 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3765 uid 10000
,08-16 16:39:15.240  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-16 16:39:15.260  1958  2038 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 16:39:15.263   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 16:39:15.266   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 16:39:15.266   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 16:39:15.266   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 16:39:15.266   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 16:39:15.266   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 16:39:15.266   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 16:39:15.266   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:15.266   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.266   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 16:39:15.272   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 16:39:15.272   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 16:39:15.272   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 16:39:15.272   873   886 E DropBoxManagerService: 	... 13 more
,08-16 16:39:15.273   873  1382 I ActivityManager: Start proc 4283:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 16:39:15.274  1958  2038 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 16:39:15.274  1958  2038 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1958
08-16 16:39:15.274  1958  2038 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.274  1958  2038 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 16:39:15.277   873  4288 E DropBoxManagerService: Can't write: system_app_crash
08-16 16:39:15.277   873  4288 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 16:39:15.277   873  4288 E DropBoxManagerService: 	... 5 more
08-16 16:39:15.279   873  3735 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 16:39:15.292  1958  2038 I Process : Sending signal. PID: 1958 SIG: 9
,08-16 16:39:15.313  4266  4266 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 16:39:15.316  1865  4263 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-16 16:39:15.317  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 16:39:15.317  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 16:39:15.319  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 16:39:15.319  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-16 16:39:15.327  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-16 16:39:15.327  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 16:39:15.328  1865  4263 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 16:39:15.328  1865  4263 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 16:39:15.328  1865  4263 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 16:39:15.328  1865  4263 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 16:39:15.328  1865  4263 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 16:39:15.328  1865  4263 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 16:39:15.344   873  1687 I ActivityManager: Start proc 4296:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 16:39:15.354  4266  4302 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 16:39:15.380   873   883 D GraphicsStats: Buffer count: 1
08-16 16:39:15.380   873  3735 I WindowState: WIN DEATH: Window{1aea335 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 16:39:15.391   873  1991 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1958) has died
,08-16 16:39:15.393   873  1991 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 16:39:15.396   873  1991 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 16:39:15.409  4296  4296 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 16:39:15.413   873   886 I ActivityManager: Start proc 4311:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 16:39:15.454  4266  4280 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.454  4266  4280 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.454  4266  4280 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 16:39:15.460  4311  4311 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:39:15.460  4311  4311 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 16:39:15.460  4311  4311 D AndroidRuntime: Shutting down VM
,08-16 16:39:15.461  1498  1498 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 16:39:15.465  1498  1498 D AndroidRuntime: Shutting down VM
,08-16 16:39:15.466  1498  1498 E AndroidRuntime: FATAL EXCEPTION: main
08-16 16:39:15.466  1498  1498 E AndroidRuntime: Process: com.google.process.gapps, PID: 1498
08-16 16:39:15.466  1498  1498 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 16:39:15.466  1498  1498 E AndroidRuntime: 	... 8 more
,08-16 16:39:15.469  4311  4311 E AndroidRuntime: FATAL EXCEPTION: main
08-16 16:39:15.469  4311  4311 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4311
08-16 16:39:15.469  4311  4311 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 16:39:15.469  4311  4311 E AndroidRuntime: 	... 10 more
08-16 16:39:15.472   873  4327 E DropBoxManagerService: Can't write: system_app_crash
08-16 16:39:15.472   873  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 16:39:15.472   873  4327 E DropBoxManagerService: 	... 5 more
,08-16 16:39:15.477  1498  1498 I Process : Sending signal. PID: 1498 SIG: 9
08-16 16:39:15.477   873  3735 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 16:39:15.477  4311  4311 I Process : Sending signal. PID: 4311 SIG: 9
08-16 16:39:15.486   873  4328 E DropBoxManagerService: Can't write: system_app_crash
08-16 16:39:15.486   873  4328 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 16:39:15.486   873  4328 E DropBoxManagerService: 	... 5 more
,08-16 16:39:15.498   873  3735 I ActivityManager: Killing 3685:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 16:39:15.521   873  1307 D WifiService: Client connection lost with reason: 4
08-16 16:39:15.523  1681  4324 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@9cd5a0b
08-16 16:39:15.530   873  1382 I ActivityManager: Process com.google.process.gapps (pid 1498) has died
08-16 16:39:15.531   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-16 16:39:15.531   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-16 16:39:15.531   873  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-16 16:39:15.533   873   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4311) has died
08-16 16:39:15.534   873   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 16:39:15.545  1681  1681 W RocketImpressions: ClearcutLogger connection suspended: 1

```
