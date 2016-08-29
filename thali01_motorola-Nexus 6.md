#### Test 8289468223f5822_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-29 15:11:13.148   873  1850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-29 15:11:13.834  3916  3916 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 15:11:13.839  3916  3916 D AndroidRuntime: CheckJNI is OFF
08-29 15:11:13.877  3916  3916 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 15:11:13.921  3916  3916 I Radio-JNI: register_android_hardware_Radio DONE
08-29 15:11:13.942  3916  3916 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 15:11:13.948   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 15:11:13.983  2042  3160 W SearchService: Abort, client detached.
08-29 15:11:13.997  3916  3916 D AndroidRuntime: Shutting down VM
08-29 15:11:13.997  2042  2042 I HotwordDetector: Closing mic
08-29 15:11:13.998  2042  2323 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@edefb50
08-29 15:11:13.998  2042  2342 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 15:11:14.015   873  1997 I ActivityManager: Start proc 3926:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 15:11:14.054   375  2346 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 15:11:14.055   375  2346 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 15:11:14.062   375  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 15:11:14.065  2042  2341 I MicroRecognitionRnrImpl: Detection finished
08-29 15:11:14.066  2042  2333 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 15:11:14.108  3926  3926 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 15:11:14.137  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 15:11:14.145  3926  3926 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8486-8489)
08-29 15:11:14.145  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:11:14.165  3926  3926 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7cd1720}
08-29 15:11:14.166  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:11:14.167  3926  3926 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 15:11:14.175  3926  3926 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 15:11:14.177  3926  3926 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 15:11:14.198  3926  3926 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 15:11:14.216  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 15:11:14.217  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 15:11:14.217  3926  3926 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 15:11:14.217  3926  3926 I Adreno  : Build Date                       : 10/20/15
08-29 15:11:14.217  3926  3926 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 15:11:14.217  3926  3926 I Adreno  : Local Branch                     : M14
08-29 15:11:14.217  3926  3926 I Adreno  : Remote Branch                    : 
08-29 15:11:14.217  3926  3926 I Adreno  : Remote Branch                    : 
08-29 15:11:14.217  3926  3926 I Adreno  : Reconstruct Branch               : 
08-29 15:11:14.280   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d75677:true
08-29 15:11:14.332  3926  3926 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 15:11:14.347  3926  3926 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-29 15:11:14.412  3926  3966 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-29 15:11:14.423  3926  3952 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-29 15:11:14.462  3926  3966 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 15:11:14.537   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +535ms
08-29 15:11:14.541  1871  1871 I Keyboard.Facilitator: onFinishInput()
08-29 15:11:14.660  3926  3926 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3926
08-29 15:11:14.788  3926  3926 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-29 15:11:14.853   873  2010 I ActivityManager: Killing 3202:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
08-29 15:11:14.891   873  2010 I ActivityManager: Killing 3264:com.google.android.apps.maps/u0a65 (adj 15): empty #18
08-29 15:11:15.025  3926  3968 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1714816720
08-29 15:11:15.053  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 15:11:15.053  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 15:11:15.053  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 15:11:15.053  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 15:11:15.053  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 15:11:15.053  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15062a4 added. We now have 1 listener(s)
08-29 15:11:15.062  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-29 15:11:15.063  3926  3968 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:15.064  3926  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:15.064  3926  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 15:11:15.070  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75e55d3 added. We now have 1 listener(s)
08-29 15:11:15.070  3926  3968 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:15.077   873  1306 D WifiService: New client listening to asynchronous messages
08-29 15:11:15.084  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:11:15.084  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 15:11:15.085  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 15:11:15.085  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 15:11:15.085  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 15:11:15.089  3926  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:15.089  3926  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-29 15:11:15.096  3926  3968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:15.096  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:15.097  3926  3968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 15:11:15.097  3926  3968 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:15.097  3926  3968 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 15:11:15.258  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:15.268  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:15.274  3926  3926 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 15:11:16.178  3926  3977 W jxcore-log: Initializing JXcore engine
,08-29 15:11:16.178  3926  3977 W jxcore-log: JXcore engine is ready
,08-29 15:11:16.281  3977  3977 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8979 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 15:11:16.281  3977  3977 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9661]" dev="sockfs" ino=9661 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 15:11:16.281  3977  3977 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 15:11:16.281  3977  3977 W Thread-357: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26380]" dev="sockfs" ino=26380 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 15:11:16.306  3926  3977 W jxcore-log: Starting JXcore engine
,08-29 15:11:16.398  3926  3977 W jxcore-log: Platform android
08-29 15:11:16.398  3926  3977 W jxcore-log: 
,08-29 15:11:16.398  3926  3977 W jxcore-log: Process ARCH arm
08-29 15:11:16.398  3926  3977 W jxcore-log: 
,08-29 15:11:16.577  3926  3977 I jxcore-log: JXcore Cordova bridge is ready!
08-29 15:11:16.577  3926  3977 I jxcore-log: 
,08-29 15:11:16.578  3926  3977 W jxcore-log: JXcore engine is started
,08-29 15:11:16.596  3926  3968 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 15:11:16.603  3926  3926 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 15:11:17.401   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 15:11:23.283  3326  3983 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 15:11:23.310  3326  3984 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 15:11:23.332  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:23.337  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:23.376  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:11:23.376  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:11:23.377  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:11:23.377  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:23.442  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:23.444  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:23.490  1507  3194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:11:23.491  1507  3194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:11:23.491  1507  3194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:23.491  1507  3194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:23.503  3326  3984 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 15:11:23.504  3326  3983 E BooksSync: Soft error
08-29 15:11:23.504  3326  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:11:23.504  3326  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 15:11:23.504  3326  3983 E BooksSync: Sync error
08-29 15:11:23.504  3326  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:11:23.504  3326  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:11:23.504  3326  3983 I BooksSync: Finished books sync
,08-29 15:11:23.513   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127578, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:11:23.614  3736  3985 V KeepSync: Connecting to GoogleApiClient
,08-29 15:11:23.615   873  2110 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 15:11:23.684  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:23.688  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:23.729  1507  3194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 15:11:23.729  1507  3194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 15:11:23.730  1507  3194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:23.730  1507  3194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:23.759  1704  3986 V BaseAuthAsyncOperation: access token request failed
,08-29 15:11:23.764  3736  3985 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:11:23.855  1507  2300 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 15:11:23.858  1507  2300 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 15:11:23.859  1507  2300 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:23.860  1507  2300 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:23.882  3736  3985 E KeepSync: IOException
08-29 15:11:23.882  3736  3985 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:11:23.882  3736  3985 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:11:23.882  3736  3985 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:11:23.882  3736  3985 E KeepSync: 	... 10 more
,08-29 15:11:23.882  3736  3985 W KeepSync: Sync result 2
,08-29 15:11:23.889   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127704, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:11:24.269  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:24.320  1507  2300 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 15:11:24.320  1507  2300 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 15:11:24.320  1507  2300 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:11:24.320  1507  2300 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:24.347  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 15:11:24.348  3677  3677 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 15:11:24.348  3677  3677 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.,
,08-29 15:11:26.561  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 15:11:26.561  3926  3977 I jxcore-log: 
,08-29 15:11:26.564  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 15:11:26.564  3926  3977 I jxcore-log: 
,08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:26.573  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:26.575  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:26.578  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 15:11:26.578  3926  3977 I jxcore-log: 
,08-29 15:11:26.580  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 15:11:26.580  3926  3977 I jxcore-log: 
,08-29 15:11:27.111  3926  3977 D executeNativeTests: Running unit tests
,08-29 15:11:27.177  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:27.178  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 added. We now have 2 listener(s)
,08-29 15:11:27.179  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:27.179  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:27.179  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:27.179  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:27.179  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d added. We now have 2 listener(s)
08-29 15:11:27.179  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:27.180  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:11:27.187  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:27.195  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:27.197  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:27.197  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:11:27.199  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 15:11:27.201  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 15:11:27.201  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 15:11:27.203  3926  3977 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 15:11:27.203  3926  3977 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 15:11:27.203  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:11:27.203  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.204  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:27.204  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:27.204  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.204  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.204  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.205  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.205  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.205  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:27.205  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:27.205  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 removed from the list
08-29 15:11:27.205  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.205  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d removed from the list
,08-29 15:11:27.212  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.212  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.212  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.212  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.212  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.213  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.213  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.213  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.214  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.215  3926  3977 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 15:11:27.216  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.216  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.216  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:11:27.216  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:27.217  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.217  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.217  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
,08-29 15:11:27.217  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:27.217  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
,08-29 15:11:27.217  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.217  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.217  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.217  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.217  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.218  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.218  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 15:11:27.218  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.218  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.223  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 15:11:27.224  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 15:11:27.225  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 15:11:27.226  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 15:11:27.226  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.226  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.226  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.226  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.227  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.227  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.227  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
,08-29 15:11:27.227  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.227  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.227  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:27.227  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.227  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.227  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.227  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.229  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.230  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.230  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.230  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.230  3926  3977 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 15:11:27.232  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:27.243  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:27.246  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:27.246  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:27.247  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:11:27.247  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 15:11:27.247  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 15:11:27.247  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:27.247  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 15:11:27.250  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.253  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.255  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:11:27.255  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:11:27.268  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:11:27.269  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 15:11:27.270  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:27.272  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 15:11:27.276  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 15:11:27.276  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 15:11:27.276  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:11:27.277  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 15:11:27.277  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:27.282  2745  2863 D BtGatt.GattService: registerClient() - UUID=8946a8d7-dafa-46ba-9825-fce83a8a5f71
08-29 15:11:27.284  2745  2805 D BtGatt.GattService: onClientRegistered() - UUID=8946a8d7-dafa-46ba-9825-fce83a8a5f71, clientIf=5
,08-29 15:11:27.285  3926  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 15:11:27.290  2745  2756 D BtGatt.GattService: start scan with filters
,08-29 15:11:27.294  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 15:11:27.294  2745  2810 D BtGatt.ScanManager: handling starting scan
,08-29 15:11:27.294  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 15:11:27.295  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 15:11:27.295  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:11:27.296  2745  2810 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:27.298  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:27.298  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:27.299  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:11:27.300  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:11:27.302  3926  3977 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 15:11:27.305  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.305  3926  3977 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 15:11:27.305  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:27.305  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 15:11:27.305  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.305  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:11:27.305  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,08-29 15:11:27.305  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 15:11:27.305  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 15:11:27.305  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:27.306  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:11:27.306  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 15:11:27.307  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:27.308  2745  2863 D BtGatt.GattService: stopScan() - queue size =1
,08-29 15:11:27.308  2745  2805 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 15:11:27.308  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.308  2745  2756 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:11:27.309  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:27.309  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 15:11:27.309  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 15:11:27.309  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 15:11:27.309  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:11:27.310  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:27.310  2745  2810 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:11:27.310  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:11:27.310  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 15:11:27.311  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:11:27.311  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:27.312  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.312  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.312  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:11:27.312  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.313  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.313  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.313  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:27.313  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.313  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.313  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.313  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:27.314  3926  3977 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 15:11:27.315  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:27.323  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:27.326  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.327  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:27.327  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:11:27.328  2745  2805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 15:11:27.328  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:27.328  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.328  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:27.328  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:27.328  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:11:27.329  2745  2810 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:11:27.329  2745  2810 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 15:11:27.330  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.335  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.337  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:11:27.337  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:11:27.341  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:11:27.342  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 15:11:27.342  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:27.343  2745  2805 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 15:11:27.343  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.346  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 15:11:27.346  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 15:11:27.347  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 15:11:27.348  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:27.352  2745  2805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:11:27.352  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.354  2745  2872 D BtGatt.GattService: registerClient() - UUID=37e2a640-e37f-46d6-a638-1aa49dfa6d58
,08-29 15:11:27.354  2745  2805 D BtGatt.GattService: onClientRegistered() - UUID=37e2a640-e37f-46d6-a638-1aa49dfa6d58, clientIf=5
,08-29 15:11:27.354  3926  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 15:11:27.355  2745  2757 D BtGatt.GattService: start scan with filters
,08-29 15:11:27.357  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 15:11:27.357  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 15:11:27.358  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:11:27.358  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:11:27.366  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:27.367  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:11:27.367  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:11:27.368  2745  2805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 15:11:27.369  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.369  2745  2810 D BtGatt.ScanManager: stopping BLe Batch
,08-29 15:11:27.372  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:11:27.377  2745  2805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 15:11:27.377  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.377  2745  2810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 15:11:27.378  3926  3977 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 15:11:27.382  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.382  3926  3977 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 15:11:27.382  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:27.382  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:11:27.383  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.383  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:11:27.383  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 15:11:27.383  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:11:27.383  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:11:27.383  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 15:11:27.383  2745  2805 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 15:11:27.383  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.383  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 15:11:27.384  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 15:11:27.384  3926  3977 D BluetoothAdapter: STATE_ON
08-29 15:11:27.385  2745  2872 D BtGatt.GattService: stopScan() - queue size =0,
08-29 15:11:27.385  2745  2757 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:11:27.385  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 15:11:27.385  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 15:11:27.385  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 15:11:27.386  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 15:11:27.386  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:11:27.386  2745  2810 D BtGatt.ScanManager: handling starting scan
,08-29 15:11:27.386  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:27.386  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 15:11:27.387  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 15:11:27.387  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:11:27.387  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:27.388  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.388  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.388  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:27.389  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:27.389  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.389  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:27.389  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.389  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.389  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.389  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.389  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.389  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.390  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.390  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.390  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.390  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.390  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.391  3926  3977 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 15:11:27.392  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:27.396  2745  2805 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 15:11:27.396  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.396  2745  2810 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:27.396  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:27.398  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:27.398  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:27.399  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:11:27.399  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:27.399  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:27.399  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:27.399  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 15:11:27.400  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.401  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.402  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 15:11:27.402  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:11:27.405  2745  2805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 15:11:27.405  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.406  2745  2810 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:11:27.406  2745  2810 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 15:11:27.406  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:11:27.406  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 15:11:27.407  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:27.409  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 15:11:27.409  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:11:27.409  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 15:11:27.410  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:27.411  2745  2872 D BtGatt.GattService: registerClient() - UUID=9421ff90-8f39-457d-9e47-976683b67d4a
08-29 15:11:27.412  2745  2805 D BtGatt.GattService: onClientRegistered() - UUID=9421ff90-8f39-457d-9e47-976683b67d4a, clientIf=5
,08-29 15:11:27.412  3926  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 15:11:27.412  2745  2757 D BtGatt.GattService: start scan with filters
,08-29 15:11:27.414  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 15:11:27.414  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 15:11:27.414  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 15:11:27.414  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:11:27.415  2745  2805 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 15:11:27.415  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.417  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:11:27.417  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 15:11:27.417  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:27.419  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:11:27.420  2745  2805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:11:27.420  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.421  3926  3977 I io.jxcore.node.ConnectionHelper: start: OK
08-29 15:11:27.421  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.421  3926  3977 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 15:11:27.421  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.421  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:11:27.421  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.421  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:11:27.421  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:11:27.421  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 15:11:27.421  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:11:27.421  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:27.422  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:11:27.422  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 15:11:27.422  3926  3977 D BluetoothAdapter: STATE_ON
08-29 15:11:27.422  2745  2757 D BtGatt.GattService: stopScan() - queue size =0
08-29 15:11:27.423  2745  2863 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:11:27.423  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 15:11:27.423  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 15:11:27.423  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 15:11:27.423  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 15:11:27.424  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:11:27.424  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:27.424  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:11:27.425  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:11:27.425  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:11:27.425  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:27.426  2745  2805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 15:11:27.426  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.426  2745  2810 D BtGatt.ScanManager: stopping BLe Batch
08-29 15:11:27.426  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.426  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.426  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.427  3926  3977 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 15:11:27.427  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:27.427  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.427  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.427  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.427  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.427  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:27.427  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.427  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.427  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.427  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:27.427  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.427  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.428  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.428  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.428  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.428  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.429  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.429  3926  3977 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 15:11:27.430  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.430  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.430  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.430  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.430  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.430  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.430  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.430  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.430  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.430  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.430  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.430  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.430  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.430  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.431  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:27.431  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.431  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.431  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.432  2745  2805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 15:11:27.432  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.432  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 15:11:27.432  2745  2810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 15:11:27.432  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.432  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.432  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.432  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.432  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.433  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.433  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.433  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.433  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.433  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.433  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.433  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.433  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.433  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.434  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.434  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.434  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:27.434  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.435  3926  3977 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 15:11:27.435  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.435  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.435  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.435  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.435  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.435  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.435  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.435  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.435  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.435  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.435  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.435  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.436  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.436  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.436  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.436  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.437  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.437  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.437  2745  2805 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 15:11:27.437  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.437  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 15:11:27.437  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.437  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.437  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.437  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.437  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.438  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.438  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.438  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.438  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.438  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.438  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.438  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.438  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.438  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.438  2745  2810 D BtGatt.ScanManager: handling starting scan
,08-29 15:11:27.439  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:27.439  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.439  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:27.439  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
,08-29 15:11:27.440  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 15:11:27.441  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:11:27.441  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:11:27.441  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:27.441  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 15:11:27.441  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 15:11:27.441  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.442  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.442  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:11:27.442  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.442  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.442  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.442  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.442  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.443  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.443  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:27.443  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.443  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.443  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.443  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.444  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.444  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.444  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.444  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
,08-29 15:11:27.445  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:27.445  3926  3977 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 15:11:27.445  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 15:11:27.445  2745  2805 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 15:11:27.445  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.445  2745  2810 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:11:27.450  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:27.450  3926  3977 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 15:11:27.451  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 15:11:27.451  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 15:11:27.451  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 15:11:27.451  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 15:11:27.451  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 15:11:27.451  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 15:11:27.452  2745  2805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 15:11:27.452  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 15:11:27.452  2745  2810 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 15:11:27.452  2745  2810 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 15:11:27.452  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 15:11:27.453  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-29 15:11:27.454  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 15:11:27.454  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 15:11:27.454  3926  3977 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 15:11:27.454  3926  3977 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 15:11:27.454  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:27.454  3926  3977 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:11:27.454  3926  3977 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 15:11:27.455  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:27.455  3926  3977 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:11:27.455  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 15:11:27.459  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 15:11:27.460  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 15:11:27.460  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 15:11:27.460  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 15:11:27.461  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 15:11:27.461  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 15:11:27.461  3926  3977 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:27.461  3926  3995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 421)
08-29 15:11:27.461  3926  3977 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 15:11:27.462  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.462  2745  2805 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 15:11:27.463  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.463  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.462  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.463  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.463  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.463  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.463  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 15:11:27.463  3926  3995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:27.464  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.464  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.464  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
,08-29 15:11:27.464  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.464  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.464  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.464  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.464  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.465  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.465  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.465  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.465  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.466  3926  3996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 421
08-29 15:11:27.466  3926  3996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 421)
08-29 15:11:27.466  3926  3977 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 15:11:27.467  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.467  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.467  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.467  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:27.467  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.467  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.467  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.467  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:27.467  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.467  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:27.467  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.468  2745  2860 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,08-29 15:11:27.468  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.468  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.468  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.468  3926  3995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 421),
08-29 15:11:27.468  3926  3996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 421)
,08-29 15:11:27.469  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.469  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.469  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.469  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.470  3926  3977 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-29 15:11:27.470  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:27.470  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.470  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:11:27.470  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.470  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.470  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.470  2745  2805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:11:27.470  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.470  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.470  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.470  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.470  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.470  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.471  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.471  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.471  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.471  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.471  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.472  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.472  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.472  3926  3977 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 15:11:27.472  3926  3977 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-29 15:11:27.472  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:11:27.472  3926  3977 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 15:11:27.473  3926  3977 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 15:11:27.473  3926  3977 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 15:11:27.473  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:11:27.473  3926  3977 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-29 15:11:27.473  3926  3977 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 15:11:27.473  3926  3977 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 15:11:27.473  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:11:27.473  3926  3977 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 15:11:27.473  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.473  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.473  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.473  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:27.474  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.474  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.474  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.474  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.474  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.474  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.474  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.474  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.474  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.474  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.475  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.475  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.475  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.475  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
,08-29 15:11:27.476  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.476  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.476  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.476  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.476  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.476  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.476  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:27.476  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.476  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.476  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.476  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.476  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.476  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.477  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.477  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.477  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.477  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.477  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.477  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.477  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.477  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.477  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
,08-29 15:11:27.477  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.477  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.477  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.477  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.477  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.477  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.478  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.478  2745  2805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 15:11:27.479  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.479  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.479  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.479  2745  2810 D BtGatt.ScanManager: stopping BLe Batch
08-29 15:11:27.479  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.479  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.480  3926  3977 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 15:11:27.480  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:27.481  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 15:11:27.481  3926  3977 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 15:11:27.482  3926  3977 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 15:11:27.482  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 15:11:27.482  3926  3926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 15:11:27.482  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:11:27.482  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.482  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 15:11:27.482  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 15:11:27.482  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 15:11:27.482  3926  3997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:27.482  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.482  3926  3977 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 15:11:27.483  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.483  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.483  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:11:27.483  3926  3926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 15:11:27.483  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:11:27.483  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:27.483  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.483  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.484  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:27.484  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.484  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.484  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.484  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.484  2745  2805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 15:11:27.484  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.484  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:27.484  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.485  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.485  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.485  2745  2810 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 15:11:27.485  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.485  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.484  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:27.485  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
,08-29 15:11:27.485  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.485  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:27.485  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.485  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.485  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.485  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.486  3926  3997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 15:11:27.486  3926  3997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 15:11:27.486  3926  3997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 15:11:27.486  3926  3926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 15:11:27.486  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.486  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.486  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.487  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.488  3926  3977 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 15:11:27.488  3926  3977 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 15:11:27.488  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:11:27.489  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:27.490  2745  2805 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 15:11:27.490  2745  2805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:27.490  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.491  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.491  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.491  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:27.491  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.491  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.492  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.492  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.492  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.492  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.492  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.492  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.492  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.492  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.493  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.493  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:27.493  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.493  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.496  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.496  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.496  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:11:27.496  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:27.496  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.496  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.496  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.496  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.497  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.497  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.497  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.497  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:27.497  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.497  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.498  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.498  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.498  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.498  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.498  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:27.498  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:27.498  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:27.498  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:27.498  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.499  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.499  3926  3977 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f4874 not in the list
08-29 15:11:27.499  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.499  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.499  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:27.499  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:27.499  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.499  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:27.499  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:27.500  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:27.500  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:27.500  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:27.500  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd619d not in the list
08-29 15:11:27.500  3926  3977 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 15:11:27.500  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:11:27.501  3926  3977 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 15:11:27.501  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 15:11:27.501  3926  3977 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 15:11:27.501  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:11:27.502  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 15:11:27.502  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 15:11:27.503  3926  3977 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 15:11:27.503  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 15:11:27.503  3926  3977 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 15:11:27.503  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 15:11:27.503  3926  3977 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 15:11:27.503  3926  3977 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-29 15:11:27.503  3926  3977 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 15:11:27.503  3926  3977 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 15:11:27.504  3926  3977 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 15:11:27.504  3926  3977 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 15:11:27.504  3926  3977 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 15:11:27.504  3926  3977 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 15:11:27.505  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:27.505  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4474137 added. We now have 2 listener(s)
08-29 15:11:27.505  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:27.506  3926  3977 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 15:11:27.506   873  2110 D WifiService: setWifiEnabled: true pid=3926, uid=10000
08-29 15:11:27.506   873  2110 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 15:11:27.507  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:27.507  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbfb6a4 added. We now have 3 listener(s)
08-29 15:11:27.507  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:27.511  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:27.511  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51eec0d added. We now have 4 listener(s)
08-29 15:11:27.511  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:27.512  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:27.512  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@924a7c2 added. We now have 5 listener(s)
08-29 15:11:27.512  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:27.514   873  1951 D WifiService: setWifiEnabled: false pid=3926, uid=10000
,08-29 15:11:27.514   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:27.518  2745  2800 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 15:11:27.518  2745  2800 D BluetoothAdapterProperties: Setting state to 13
08-29 15:11:27.518  2745  2800 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 15:11:27.519  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:27.519  2745  2800 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 15:11:27.520  2745  2800 I BluetoothAdapterState: Entering PendingCommandState
08-29 15:11:27.520  2745  2805 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:11:27.520  2745  2800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 15:11:27.521  2745  2745 D BluetoothMapService: onReceive
,08-29 15:11:27.524  2745  2745 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 15:11:27.524  2745  2745 D BluetoothMapService: STATE_TURNING_OFF
,08-29 15:11:27.524  2745  2745 D BluetoothMapService: MAP Service closeService in
08-29 15:11:27.524  2745  2745 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 15:11:27.524  2745  2745 D ObexServerSockets0: shutdown(block = true)
,08-29 15:11:27.525  2745  2745 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:11:27.525  2745  2745 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:11:27.525  2745  2860 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 15:11:27.525  2745  2873 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 15:11:27.525  2745  2874 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 15:11:27.526  2745  2745 I BtOppRfcommListener: stopping Accept Thread
08-29 15:11:27.526  2745  3591 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 15:11:27.527  2745  3591 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 15:11:27.527  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:27.527  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:27.528  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.528  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:27.528  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:27.530  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.532  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.534  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 15:11:27.535   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 15:11:27.535   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 15:11:27.535   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:11:27.536   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:27.536  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:27.536  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:27.536  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.537  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:27.539  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.541   873   886 I ActivityManager: Start proc 4000:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 15:11:27.543  2745  2745 D HeadsetService: Received stop request...Stopping profile...
,08-29 15:11:27.544  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:27.545   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:11:27.545   873  1866 D DhcpClient: Clearing IP address
,08-29 15:11:27.546  1945  1959 D BluetoothHeadset: Proxy object disconnected
,08-29 15:11:27.546   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:27.546   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:27.546   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:27.547  1349  1361 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:27.549  2745  2745 D A2dpService: Received stop request...Stopping profile...
08-29 15:11:27.550  2745  2866 D A2dpStateMachine: Exit Disconnected: -1
08-29 15:11:27.550  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-29 15:11:27.551   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 15:11:27.551  1507  2483 V NativeCrypto: Read error: ssl=0x9aa54800: I/O error during system call, Connection timed out
08-29 15:11:27.552  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.552  1507  2483 V NativeCrypto: SSL shutdown failed: ssl=0x9aa54800: I/O error during system call, Broken pipe
08-29 15:11:27.553  2745  2745 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:27.553  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.553  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:27.553  2745  2745 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:27.553   371   871 D CommandListener: Setting iface cfg
08-29 15:11:27.554  2745  2745 D HidService: Received stop request...Stopping profile...
08-29 15:11:27.554   873   883 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 15:11:27.554  2745  2745 D HidService: Stopping Bluetooth HidService
08-29 15:11:27.554   873  1847 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-29 15:11:27.556  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-29 15:11:27.557  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-29 15:11:27.557  1349  1349 D HidProfile: Bluetooth service disconnected
08-29 15:11:27.557  2745  2745 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 15:11:27.557  2745  2805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 15:11:27.557  2745  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:27.557  2745  2745 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:27.557  2745  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:27.557  2745  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:27.557   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 15:11:27.557   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 15:11:27.558  2745  2805 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 15:11:27.559  2745  2745 D HealthService: Received stop request...Stopping profile...
08-29 15:11:27.561   402   402 E Parcel  : Reading a NULL string not supported here.
08-29 15:11:27.563  2745  2745 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:27.563   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 15:11:27.564  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.564  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:27.564  2745  2745 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:27.564   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:11:27.564  2745  2745 D PanService: Received stop request...Stopping profile...
08-29 15:11:27.566  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 15:11:27.566  1349  1349 D PanProfile: Bluetooth service disconnected
08-29 15:11:27.567   873  1847 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostExcepti,on: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 15:11:27.567   873  1882 D DhcpClient: Receive thread stopped
08-29 15:11:27.568   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 15:11:27.568  2745  2805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 15:11:27.568  2745  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:27.568  2745  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:27.568  2745  2841 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:27.568  2745  2841 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:27.569  2745  2841 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:27.569  2745  2841 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:27.569  2745  2745 D BluetoothMapService: Received stop request...Stopping profile...
08-29 15:11:27.569  2745  2745 D BluetoothMapService: stop()
08-29 15:11:27.569   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 15:11:27.569  2745  2745 D BluetoothMapAppObserver: deinitObservers()
08-29 15:11:27.569  2745  2745 D BluetoothMapAppObserver: removeReceiver()
08-29 15:11:27.574  1349  1349 D BluetoothMap: Proxy object disconnected
08-29 15:11:27.574  1349  1349 D MapProfile: Bluetooth service disconnected
08-29 15:11:27.574  2745  2745 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:27.574  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.574  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:27.574  2745  2745 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:27.575  2745  2745 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 15:11:27.575  2745  2805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 15:11:27.575  2745  2745 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 15:11:27.575   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 15:11:27.575  2745  2745 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:27.575  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.575  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:27.575  2745  2745 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:27.576  2745  2745 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 15:11:27.576  2745  2805 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 15:11:27.577  2745  2745 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:11:27.577  2745  2745 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:27.578  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.578  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:27.578  2745  2745 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:27.578  2745  2745 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 15:11:27.578  2745  2745 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 15:11:27.579   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 15:11:27.579  2745  2745 D BluetoothMapService: MAP Service closeService in
08-29 15:11:27.579  2745  2745 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:27.579  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.579  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.580  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:27.580  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:27.580  2745  2745 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:27.580  2745  2800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 15:11:27.580  2745  2800 D BluetoothAdapterProperties: Setting state to 15
08-29 15:11:27.580  2745  2800 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 15:11:27.581  1349  1361 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:11:27.581  1349  2077 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:11:27.581  1349  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:27.582  1349  1361 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:27.582  1349  2077 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 15:11:27.582  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.582  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:27.582   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:27.583   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:27.583   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:27.583  1349  1372 D BluetoothPan: onBluetoothStateChange on: false
08-29 15:11:27.583  1945  1961 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:27.583   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:27.584  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:27.584  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:27.585  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:27.585  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:27.585  2745  2800 I BluetoothAdapterState: Entering BleOnState
08-29 15:11:27.585  2745  2800 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 15:11:27.585  2745  2800 D BluetoothAdapterProperties: Setting state to 16
08-29 15:11:27.585  2745  2800 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 15:11:27.586  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.586  2745  2800 D BluetoothAdapterProperties: onBleDisable
08-29 15:11:27.586  2745  2801 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 15:11:27.587  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.587  2745  2805 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:27.588  2745  2841 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 15:11:27.588  2745  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:27.588  2745  2800 I BluetoothAdapterState: Entering PendingCommandState
08-29 15:11:27.588  2745  2745 D BluetoothMapService: cleanup()
08-29 15:11:27.588  2745  2745 D BluetoothMapService: MAP Service closeService in
08-29 15:11:27.589  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.590  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.594  1885  2293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:27.616   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 15:11:27.628  4000  4000 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-29 15:11:27.635   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 15:11:27.636   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 15:11:27.636   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:27.639   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 15:11:27.642  3579  3579 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@15062a4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 15:11:27.642  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.643  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:27.647  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 15:11:27.651  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:27.654   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12f9293:true
08-29 15:11:27.664   873  2110 I ActivityManager: Start proc 4020:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 15:11:27.690  4000  4000 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 15:11:27.692  4000  4000 D BluetoothMap: Create BluetoothMap proxy object
,08-29 15:11:27.698  4020  4020 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 15:11:27.701  4000  4000 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 15:11:27.705   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 15:11:27.706   873  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 15:11:27.706   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 15:11:27.720  4000  4000 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:27.723   873  2010 I ActivityManager: Killing 3378:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 15:11:27.792  2745  2805 I bt_hci  : shut_down
08-29 15:11:27.792  2745  2812 D bt_hwcfg: hw_epilog_process
,08-29 15:11:27.804  2745  2812 I bt_vendor: low_power_mode_cb
,08-29 15:11:27.822  2745  2812 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 15:11:27.823  2745  2812 I bt_vendor: epilog_cb
08-29 15:11:27.823  2745  2812 I bt_hci  : epilog_finished_callback
,08-29 15:11:27.828  2745  2805 I bt_hci_h4: hal_close
,08-29 15:11:27.829  2745  2805 I bt_userial_vendor: device fd = 51 close
,08-29 15:11:27.955  2745  2801 D bt_stack_manager: event_shut_down_stack finished.
,08-29 15:11:27.956  2745  2800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 15:11:27.960  2745  2800 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 15:11:27.961  2745  2745 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 15:11:27.962  2745  2745 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 15:11:27.962  2745  2745 D BtGatt.GattService: stop()
,08-29 15:11:27.963  2745  2745 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 15:11:27.967  2745  2745 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:27.967  2745  2745 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:27.967  2745  2745 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:11:27.968  2745  2745 V BluetoothAdapterState: isBleTurningOff()=true
08-29 15:11:27.968  2745  2800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 15:11:27.969  2745  2800 D BluetoothAdapterProperties: Setting state to 10
08-29 15:11:27.969  2745  2800 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 15:11:27.970  2745  2800 I BluetoothAdapterState: Entering OffState,
08-29 15:11:27.971   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 15:11:27.978  2745  2745 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 15:11:27.978  2745  2745 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 15:11:27.978  2745  2745 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 15:11:27.981  2745  2801 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 15:11:27.984  2745  2801 D bt_stack_manager: event_clean_up_stack finished.
,08-29 15:11:27.986  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:11:27.987  2745  2745 I art     : System.exit called, status: 0
,08-29 15:11:27.987  2745  2745 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 15:11:28.004  4020  4020 D StrictMode: StrictMode policy violation; ~duration=213 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206),
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:28.004  4020  4020 D StrictMode: StrictMode policy violation; ~duration=212 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.004  4020  4020 D StrictMode: StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.004  4020  4020 D StrictMode: StrictMode policy violation; ~duration=209 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.004  4020  4020 D StrictMode: StrictMode policy violation; ~duration=207 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.004  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.005  4020  4020 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.005  4020  4020 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.005  4020  4020 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:28.005  4020  4020 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:28.063   873  1997 I ActivityManager: Start proc 4055:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 15:11:28.063   873  1997 I ActivityManager: Killing 3579:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 15:11:28.091  4020  4045 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 15:11:28.098   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd3c2c:true
,08-29 15:11:28.108   873  2109 I ActivityManager: Process com.android.bluetooth (pid 2745) has died
,08-29 15:11:28.151  4055  4055 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 15:11:28.199  4055  4055 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 15:11:28.215  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:11:28.228   873  1376 I ActivityManager: Start proc 4082:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 15:11:28.229  4000  4000 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:28.298  4082  4082 D AdapterServiceConfig: Adding HeadsetService
,08-29 15:11:28.298  4082  4082 D AdapterServiceConfig: Adding A2dpService
,08-29 15:11:28.298  4082  4082 D AdapterServiceConfig: Adding HidService
08-29 15:11:28.299  4082  4082 D AdapterServiceConfig: Adding HealthService
,08-29 15:11:28.299  4082  4082 D AdapterServiceConfig: Adding PanService
08-29 15:11:28.299  4082  4082 D AdapterServiceConfig: Adding GattService
08-29 15:11:28.299  4082  4082 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 15:11:28.303   873  1376 I ActivityManager: Killing 2958:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 15:11:28.334  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:28.360  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:11:28.364  1704  1704 D SystemUpdateService: onCreate
,08-29 15:11:28.366  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:11:28.375  1704  4094 I SystemUpdateService: active receiver: enabled
,08-29 15:11:28.382  1704  4094 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:11:28.390  1704  4094 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 15:11:28.390  1704  4094 I SystemUpdateService: now status is 0 (complete)
,08-29 15:11:28.390  1704  4094 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 15:11:28.390  1704  4094 I SystemUpdateService: file has been verified
,08-29 15:11:28.390  1704  4094 I SystemUpdateService: OTA package size = 12249756
,08-29 15:11:28.391  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 15:11:28.395  1704  2448 I iu.UploadsManager: num queued entries: 0
,08-29 15:11:28.396  1704  2448 I iu.UploadsManager: num updated entries: 0
,08-29 15:11:28.397  1704  2448 I iu.SyncManager: NEXT; no task
,08-29 15:11:28.397  1704  4094 I SystemUpdateService: showing system update notification,
,08-29 15:11:28.411  1704  1704 D SystemUpdateService: onDestroy
,08-29 15:11:28.420  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:11:28.421  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:11:28.443   873   883 I ActivityManager: Start proc 4096:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 15:11:28.472  4096  4096 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 15:11:28.475  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:28.481  4096  4096 D SprintDMHelper: simOperator: 
,08-29 15:11:28.481  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:11:28.500   873  4068 I ActivityManager: Start proc 4108:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 15:11:28.502   873  4068 I ActivityManager: Killing 1682:android.process.acore/u0a5 (adj 15): empty #17
,08-29 15:11:28.637   873  1693 I ActivityManager: Start proc 4123:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 15:11:28.650  2847  4122 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 15:11:28.655   873  2109 I ActivityManager: Killing 3812:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 15:11:28.734  4123  4123 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 15:11:28.800  4123  4123 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 15:11:28.800  4123  4123 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 15:11:28.800  4123  4123 I GAv4    :   adb logcat -s GAv4
,08-29 15:11:28.820  4123  4123 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 15:11:28.827  4123  4123 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 15:11:28.847  4123  4140 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,08-29 15:11:28.955  4123  4123 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 15:11:28.991  4123  4123 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 15:11:28.999  4123  4123 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3339-3342)
,08-29 15:11:28.999  4123  4123 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 15:11:29.014  4123  4123 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ae3bcd4}
,08-29 15:11:29.014  4123  4123 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 15:11:29.015  4123  4123 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 15:11:29.025  4123  4123 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 15:11:29.027  4123  4123 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 15:11:29.043  4123  4123 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 15:11:29.074  4123  4123 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 15:11:29.075  4123  4123 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 15:11:29.075  4123  4123 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 15:11:29.075  4123  4123 I Adreno  : Build Date                       : 10/20/15
08-29 15:11:29.075  4123  4123 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 15:11:29.075  4123  4123 I Adreno  : Local Branch                     : M14
08-29 15:11:29.075  4123  4123 I Adreno  : Remote Branch                    : 
08-29 15:11:29.075  4123  4123 I Adreno  : Remote Branch                    : 
08-29 15:11:29.075  4123  4123 I Adreno  : Reconstruct Branch               : 
,08-29 15:11:29.132  4123  4169 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 15:11:29.147  4123  4123 I NSApplication: Starting up...
,08-29 15:11:29.191   873  1378 I ActivityManager: Start proc 4174:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 15:11:29.193   873  1378 I ActivityManager: Killing 3829:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 15:11:29.277  4174  4174 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 15:11:29.495   873  1951 I ActivityManager: Killing 3609:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 15:11:30.531   873  1951 D WifiService: setWifiEnabled: true pid=3926, uid=10000
,08-29 15:11:30.531   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:30.544   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-29 15:11:30.551  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:30.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:30.551  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:30.551  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:30.553  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:30.553  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:30.553  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:30.554  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:30.589   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-29 15:11:30.590   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 15:11:30.591   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 15:11:30.592   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 15:11:30.592   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 15:11:30.592   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 15:11:30.593   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 15:11:30.613   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 15:11:30.613   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.88 rxSuccessRate=8.88 delta 1000 -> 994
,08-29 15:11:30.615   371   871 D CommandListener: Setting iface cfg
,08-29 15:11:30.616   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
08-29 15:11:30.616   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 15:11:30.622   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 15:11:30.622   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:30.624   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 15:11:30.624   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 15:11:30.633   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 15:11:30.707   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 15:11:30.710  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 15:11:31.129  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 15:11:31.172  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 15:11:31.173  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 15:11:31.178   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:11:31.190   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:11:31.190   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:11:31.190   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 15:11:31.211   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:31.223   371   871 D CommandListener: Setting iface cfg
,08-29 15:11:31.223   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 15:11:31.242   873  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 15:11:31.246   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 15:11:31.255   873  4197 D DhcpClient: Receive thread started
,08-29 15:11:31.337   873  1305 E native  : do suspend false
,08-29 15:11:31.356   873  1866 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 15:11:31.372   873  4197 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-29 15:11:31.373   873  1866 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-29 15:11:31.376   873  1866 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 15:11:31.404   873  4197 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 15:11:31.406   873  1866 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 15:11:31.411   371   871 D CommandListener: Setting iface cfg
,08-29 15:11:31.422   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 15:11:31.425   873  1866 D DhcpClient: Scheduling renewal in 86399s
,08-29 15:11:31.432   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 15:11:31.432   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 15:11:31.433   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 15:11:31.433   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 15:11:31.439   873  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 15:11:31.442   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 15:11:31.488   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 15:11:31.488   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 15:11:31.489   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 15:11:31.490   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 15:11:31.491   873  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 15:11:31.502   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 15:11:31.507   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 15:11:31.507   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 15:11:31.507   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-29 15:11:31.507   873  1307 D ConnectivityService:    accepting network in place of null
08-29 15:11:31.507   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 15:11:31.508   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:11:31.508   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:11:31.549   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:11:31.594   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:11:31.606   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 15:11:31.606   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:31.615   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 15:11:31.616   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:11:31.640  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:31.640  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:31.640  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:31.640  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:31.642  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:31.643  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:31.643  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:31.643  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:31.649  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:11:31.655  1704  1704 D SystemUpdateService: onCreate
,08-29 15:11:31.661  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 15:11:31.663  1704  4209 I SystemUpdateService: active receiver: enabled
,08-29 15:11:31.666  1704  4209 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:11:31.669  1704  4209 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 15:11:31.669  1704  4209 I SystemUpdateService: now status is 0 (complete)
08-29 15:11:31.669  1704  4209 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 15:11:31.669  1704  4209 I SystemUpdateService: file has been verified
,08-29 15:11:31.671  1704  4209 I SystemUpdateService: OTA package size = 12249756
,08-29 15:11:31.677  1704  4209 I SystemUpdateService: showing system update notification
,08-29 15:11:31.683  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 15:11:31.685  1704  2448 I iu.UploadsManager: num queued entries: 0
,08-29 15:11:31.685  1704  2448 I iu.UploadsManager: num updated entries: 0
08-29 15:11:31.686  1704  2448 I iu.SyncManager: NEXT; no task
,08-29 15:11:31.691  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:11:31.692  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:11:31.696  1704  1704 D SystemUpdateService: onDestroy
,08-29 15:11:31.699  1704  4213 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 15:11:31.699  1704  4213 W BaseAppContext: Using Auth Proxy for data requests.
08-29 15:11:31.700  1704  4213 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:11:31.699  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:31.706  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:11:31.706  4096  4096 D SprintDMHelper: simOperator: 
08-29 15:11:31.706  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 15:11:31.708  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:31.744  1507  3194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 15:11:31.744  1507  3194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 15:11:31.744  1507  3194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:31.744  1507  3194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:31.759  1704  4213 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-29 15:11:31.789  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:11:31.789  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:11:31.789  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:31.789  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:31.804  3178  4210 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:11:31.804  3178  4210 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:11:31.804  3178  4210 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	... 12 more
08-29 15:11:31.804  3178  4210 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at fal.a(PG:38)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:11:31.804  3178  4210 E HttpOperation: 	... 14 more
,08-29 15:11:31.837  1507  2300 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 15:11:31.837  1507  2300 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:11:31.837  1507  2300 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:11:31.837  1507  2300 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:31.852  3178  4210 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:11:31.852  3178  4210 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at hec.a(PG:42)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at hee.a(PG:102)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at czr.a(PG:65)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at kka.a(PG:108)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:11:31.852  3178  4210 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	... 15 more
08-29 15:11:31.852  3178  4210 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at fal.a(PG:38)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:11:31.852  3178  4210 E HttpOperation: 	... 17 more
08-29 15:11:31.853  3178  4210 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:11:31.853  3178  4210 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at hec.a(PG:42)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	... 15 more
08-29 15:11:31.853  3178  4210 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:11:31.853  3178  4210 E ExperimentLoader: 	... 17 more
,08-29 15:11:31.953   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129909, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:11:32.604   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 15:11:33.539   873  2110 D WifiService: setWifiEnabled: false pid=3926, uid=10000
08-29 15:11:33.539   873  2110 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:33.562  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 15:11:33.565   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 15:11:33.565   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 15:11:33.565   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:11:33.565   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:33.581   873  1866 D DhcpClient: Clearing IP address
,08-29 15:11:33.582   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:11:33.592   371   871 D CommandListener: Setting iface cfg
,08-29 15:11:33.594   873  4197 D DhcpClient: Receive thread stopped
,08-29 15:11:33.602   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 15:11:33.602   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 15:11:33.615   402   402 E Parcel  : Reading a NULL string not supported here.
,08-29 15:11:33.617   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 15:11:33.618   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:11:33.620   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:11:33.626   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 15:11:33.627   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:11:33.629  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:33.629  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:33.629  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:33.629  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:33.630  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:33.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:33.631  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:33.631  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:33.631  1885  2293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:11:33.632   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 15:11:33.662   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:11:33.690   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:11:33.691   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 15:11:33.691   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:33.692   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:11:33.696  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:33.696  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:33.698  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:33.704  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:11:33.707  1704  1704 D SystemUpdateService: onCreate
,08-29 15:11:33.710  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:11:33.719  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 15:11:33.723  1704  2448 I iu.UploadsManager: num queued entries: 0
08-29 15:11:33.724  1704  2448 I iu.UploadsManager: num updated entries: 0
08-29 15:11:33.724  1704  2448 I iu.SyncManager: NEXT; no task
,08-29 15:11:33.725  1704  4228 I SystemUpdateService: active receiver: enabled
,08-29 15:11:33.727  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:11:33.729  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:11:33.731  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:33.734  4096  4096 D SprintDMHelper: simOperator: 
,08-29 15:11:33.734  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:11:33.738  1704  4228 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:11:33.739  1704  4228 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 15:11:33.739  1704  4228 I SystemUpdateService: now status is 0 (complete)
08-29 15:11:33.739  1704  4228 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 15:11:33.739  1704  4228 I SystemUpdateService: file has been verified
08-29 15:11:33.739  1704  4228 I SystemUpdateService: OTA package size = 12249756
,08-29 15:11:33.781  1704  4228 I SystemUpdateService: showing system update notification
,08-29 15:11:33.793   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 15:11:33.795   873  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 15:11:33.822  1704  1704 D SystemUpdateService: onDestroy
,08-29 15:11:36.521   873  4195 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 15:11:36.523   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 15:11:36.596   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a9abb9:true
,08-29 15:11:36.597  4082  4082 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 15:11:36.602  4082  4082 I bt_bluedroid: init
,08-29 15:11:36.602  4082  4235 I BluetoothAdapterState: Entering OffState
,08-29 15:11:36.604  4082  4236 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 15:11:36.604  4082  4236 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 15:11:36.604  4082  4236 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 15:11:36.605  4082  4236 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 15:11:36.606  4082  4082 I bt_bluedroid: get_profile_interface socket
,08-29 15:11:36.608  4082  4239 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:11:36.609  4082  4239 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 15:11:36.612  4082  4082 I bt_bluedroid: get_profile_interface sdp
,08-29 15:11:36.618  4082  4093 I bt_bluedroid: config_hci_snoop_log
,08-29 15:11:36.621   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 15:11:36.630  4082  4235 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 15:11:36.630  4082  4235 D BluetoothAdapterProperties: Setting state to 14
08-29 15:11:36.631  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 15:11:36.632  4082  4235 D BluetoothBondStateMachine: make
,08-29 15:11:36.634  4082  4240 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 15:11:36.636  4082  4235 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:11:36.639  4082  4082 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 15:11:36.646  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:36.648  4082  4082 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 15:11:36.649  4082  4082 D BtGatt.GattService: Received start request. Starting profile...
,08-29 15:11:36.649  4082  4082 D BtGatt.GattService: start()
08-29 15:11:36.650  4082  4082 I bt_bluedroid: get_profile_interface gatt
,08-29 15:11:36.651  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:36.652  4082  4082 D BtGatt.AdvertiseManager: advertise manager created
,08-29 15:11:36.657  4082  4082 V BluetoothAdapterState: isTurningOff()=false,
08-29 15:11:36.657  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:11:36.657  4082  4082 V BluetoothAdapterState: isBleTurningOn()=true
08-29 15:11:36.658  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:36.658  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 15:11:36.658  4082  4235 I bt_bluedroid: enable
08-29 15:11:36.658  4082  4236 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 15:11:36.658  4082  4236 I bt_hci  : start_up
,08-29 15:11:36.664  4082  4236 I bt_vendor: alloc value 0xb39e9189
,08-29 15:11:36.664  4082  4236 I bt_vendor: init
08-29 15:11:36.665  4082  4236 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 15:11:36.665  4082  4236 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 15:11:36.747  2847  4215 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-29 15:11:36.748  2847  4215 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 15:11:36.754  2847  4215 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 15:11:36.771  4082  4236 D bt_hci  : start_up starting async portion
,08-29 15:11:36.772  4082  4243 I bt_hci  : event_finish_startup
08-29 15:11:36.772  4082  4243 I bt_hci_h4: hal_open
08-29 15:11:36.772  4082  4243 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 15:11:36.777  4082  4243 I bt_userial_vendor: device fd = 51 open
,08-29 15:11:36.812  4082  4243 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:11:36.845  4082  4243 D bt_hwcfg: Chipset BCM4354A2
,08-29 15:11:36.846  4082  4243 D bt_hwcfg: Target name = [BCM4354A2]
08-29 15:11:36.847  4082  4243 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 15:11:37.544  4082  4243 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 15:11:37.545  4082  4243 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 15:11:37.546  4082  4243 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 15:11:37.663  4082  4243 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:11:37.664  4082  4243 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 15:11:37.694  4082  4243 I bt_hwcfg: vendor lib fwcfg completed
,08-29 15:11:37.694  4082  4243 I bt_vendor: firmware callback
08-29 15:11:37.695  4082  4243 I bt_hci  : firmware_config_callback
,08-29 15:11:37.708  4082  4246 I bt_btu  : btu_task pending for preload complete event
,08-29 15:11:37.708  4082  4246 I bt_btu_task: Bluetooth chip preload is complete
08-29 15:11:37.708  4082  4246 I bt_btu  : btu_task received preload complete event
,08-29 15:11:37.719  4082  4246 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 15:11:37.719  4082  4246 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 15:11:37.719  4082  4246 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 15:11:37.720  4082  4246 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 15:11:37.720  4082  4246 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 15:11:37.720  4082  4246 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 15:11:37.720  4082  4246 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 15:11:37.721  4082  4246 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 15:11:37.721  4082  4246 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 15:11:37.721  4082  4246 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 15:11:37.721  4082  4246 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 15:11:37.721  4082  4246 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 15:11:37.722  4082  4246 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 15:11:37.723  4082  4246 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 15:11:37.723  4082  4246 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 15:11:37.857  4082  4246 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,08-29 15:11:37.858  4082  4246 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-29 15:11:37.884  4082  4239 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-29 15:11:37.885  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 15:11:37.886  4082  4239 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:11:37.890  4082  4239 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 15:11:37.892  4082  4239 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:11:37.893  4082  4239 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 15:11:37.893  4082  4239 D bt_hci  : do_postload posting postload work item
,08-29 15:11:37.894  4082  4243 I bt_hci  : event_postload,
08-29 15:11:37.894  4082  4243 I bt_vendor: sco_config_cb
08-29 15:11:37.894  4082  4243 I bt_hci  : sco_config_callback postload finished.
,08-29 15:11:37.896  4082  4239 D bt_bte_conf: Device ID record 1 : primary
,08-29 15:11:37.896  4082  4239 D bt_bte_conf:   vendorId            = 000f
,08-29 15:11:37.896  4082  4239 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 15:11:37.897  4082  4239 D bt_bte_conf:   product             = 1200
,08-29 15:11:37.897  4082  4239 D bt_bte_conf:   version             = 1436
,08-29 15:11:37.897  4082  4239 D bt_bte_conf:   clientExecutableURL = 
,08-29 15:11:37.897  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.897  4082  4239 D bt_bte_conf:   serviceDescription  = 
08-29 15:11:37.898  4082  4239 D bt_bte_conf:   documentationURL    = 
,08-29 15:11:37.898  4082  4239 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 15:11:37.898  4082  4236 D bt_stack_manager: event_start_up_stack finished
,08-29 15:11:37.900  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 15:11:37.901  4082  4243 I bt_vendor: low_power_mode_cb,
08-29 15:11:37.901  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.901  4082  4235 D BluetoothAdapterProperties: Setting state to 15
08-29 15:11:37.901  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 15:11:37.902  4082  4235 I BluetoothAdapterState: Entering BleOnState
,08-29 15:11:37.908  4082  4235 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 15:11:37.908  4082  4235 D BluetoothAdapterProperties: Setting state to 11
08-29 15:11:37.908  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 15:11:37.917  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:37.919  4082  4082 D HeadsetService: Received start request. Starting profile...
,08-29 15:11:37.931  4082  4082 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 15:11:37.931  4082  4082 D HeadsetStateMachine: make
,08-29 15:11:37.932  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.934  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:37.945  4082  4235 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:11:37.946  4082  4082 D HeadsetStateMachine: max_hf_connections = 1
,08-29 15:11:37.946  4082  4082 I bt_bluedroid: get_profile_interface handsfree
08-29 15:11:37.946  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 15:11:37.946  4082  4239 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 15:11:37.951  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:37.952  4082  4082 D A2dpService: Received start request. Starting profile...
,08-29 15:11:37.953  4082  4082 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 15:11:37.953  4082  4082 I bt_bluedroid: get_profile_interface avrcp
,08-29 15:11:37.959  4082  4082 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 15:11:37.959  4082  4082 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 15:11:37.959  4082  4082 D A2dpStateMachine: make
,08-29 15:11:37.961  4082  4082 I bt_bluedroid: get_profile_interface a2dp
,08-29 15:11:37.961  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 15:11:37.963  4082  4255 D A2dpStateMachine: Enter Disconnected: -2
,08-29 15:11:37.964  4082  4082 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 15:11:37.965  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:37.967  4000  4000 D BluetoothInputDevice: Proxy object connected
,08-29 15:11:37.967  4082  4082 D HidService: Received start request. Starting profile...
08-29 15:11:37.967  4082  4082 I bt_bluedroid: get_profile_interface hidhost
08-29 15:11:37.968  4082  4239 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-29 15:11:37.968  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 15:11:37.968  4082  4082 D HidService: setHidService(): set to: null
,08-29 15:11:37.968  4082  4082 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 15:11:37.969  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:37.970  4082  4082 D HealthService: Received start request. Starting profile...
08-29 15:11:37.970  4000  4000 D HidProfile: Bluetooth service connected
,08-29 15:11:37.971  4082  4082 I bt_bluedroid: get_profile_interface health
,08-29 15:11:37.973  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:37.974  4082  4082 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 15:11:37.976  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:37.977  4082  4082 D PanService: Received start request. Starting profile...
,08-29 15:11:37.977  4000  4000 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 15:11:37.977  4082  4082 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 15:11:37.977  4082  4082 I bt_bluedroid: get_profile_interface pan,
08-29 15:11:37.978  4082  4239 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 15:11:37.978  4000  4000 D PanProfile: Bluetooth service connected
08-29 15:11:37.981  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa,
08-29 15:11:37.982  4082  4082 D BluetoothMapService: Received start request. Starting profile...
08-29 15:11:37.982  4000  4000 D BluetoothMap: Proxy object connected
,08-29 15:11:37.982  4082  4082 D BluetoothMapService: start()
08-29 15:11:37.982  4000  4000 D MapProfile: Bluetooth service connected
,08-29 15:11:37.983  4000  4000 D BluetoothMap: getConnectedDevices()
08-29 15:11:37.984  4000  4000 D BluetoothMap: Bluetooth is Not enabled
,08-29 15:11:37.984  4082  4082 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 15:11:37.985  4082  4082 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 15:11:37.985  4082  4082 D BluetoothMapAppObserver: createReceiver()
,08-29 15:11:37.993  4082  4082 D BluetoothMapAppObserver: initObservers()
,08-29 15:11:37.993  4082  4082 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 15:11:37.998  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:37.998  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:37.998  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:11:37.998  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:38.000  4082  4252 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 15:11:38.000  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-29 15:11:38.000  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:38.001  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:38.003  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:38.004  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 15:11:38.004  4082  4235 D BluetoothAdapterProperties: ScanMode =  20
08-29 15:11:38.004  4082  4235 D BluetoothAdapterProperties: State =  11
,08-29 15:11:38.006  4082  4239 D BluetoothAdapterProperties: Scan Mode:21
,08-29 15:11:38.006  4082  4239 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:11:38.006  4082  4235 D BluetoothAdapterProperties: Setting state to 12
08-29 15:11:38.006  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 15:11:38.007  4082  4235 I BluetoothAdapterState: Entering OnState
08-29 15:11:38.007  1349  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 15:11:38.008  1349  1349 D BluetoothInputDevice: Proxy object connected
08-29 15:11:38.009  1349  1349 D HidProfile: Bluetooth service connected
08-29 15:11:38.009  1349  1372 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.009  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:38.010  1349  1349 D BluetoothMap: Proxy object connected
08-29 15:11:38.010  1349  1349 D MapProfile: Bluetooth service connected
08-29 15:11:38.010  1349  1349 D BluetoothMap: getConnectedDevices()
08-29 15:11:38.010  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 15:11:38.011  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:38.012  1349  2077 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:38.012  1349  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 15:11:38.013  1349  1349 D BluetoothA2dp: Proxy object connected
08-29 15:11:38.014   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.014  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:38.015  4000  4013 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:11:38.015   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:38.015   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:11:38.016  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:38.017   873   873 D BluetoothA2dp: Proxy object connected
08-29 15:11:38.017  1349  2077 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:11:38.018  4082  4082 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 15:11:38.018  4082  4082 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 15:11:38.019  4082  4082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:38.020  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:11:38.020  1349  1349 D PanProfile: Bluetooth service connected
08-29 15:11:38.020  4000  4014 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 15:11:38.021  1945  1961 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:38.021  4082  4082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:38.022  4000  4011 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 15:11:38.022  4082  4082 D ObexServerSockets: Succeed to create listening sockets 
08-29 15:11:38.022  4082  4082 D ObexServerSockets0: startAccept()
08-29 15:11:38.022  4082  4082 D ObexServerSockets0: prepareForNewConnect()
,08-29 15:11:38.024  4000  4013 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 15:11:38.024   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:38.024  4082  4082 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 15:11:38.024  4082  4082 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 15:11:38.025  4082  4263 D ObexServerSockets0: Accepting socket connection...
08-29 15:11:38.025  4082  4262 D ObexServerSockets0: Accepting socket connection...
08-29 15:11:38.026   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 15:11:38.026  4082  4082 D BluetoothMapService: onReceive
,08-29 15:11:38.026  4082  4082 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.026  4082  4082 D BluetoothMapService: STATE_ON
08-29 15:11:38.028  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:38.028  4000  4000 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 15:11:38.029  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:38.033  4000  4000 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 15:11:38.047  4082  4082 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 15:11:38.047  4082  4082 D ObexServerSockets0: prepareForNewConnect()
,08-29 15:11:38.056  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:11:38.068  4000  4000 D BluetoothA2dp: Proxy object connected
,08-29 15:11:38.074  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:38.079  1349  1349 D BluetoothPbap: Proxy object connected
,08-29 15:11:38.080  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-29 15:11:38.087  4000  4000 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:38.091  4000  4000 D BluetoothPbap: Proxy object connected
,08-29 15:11:38.092  4000  4000 D PbapServerProfile: Bluetooth service connected
08-29 15:11:38.093  4082  4267 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:38.103  4082  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:38.104  4082  4271 I BtOppRfcommListener: Accept thread started.
,08-29 15:11:38.113  1945  2164 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.114   873   873 D BluetoothHeadset: Proxy object connected
08-29 15:11:38.114   873   873 D BluetoothHeadset: Proxy object connected
08-29 15:11:38.114   873   873 D BluetoothHeadset: Proxy object connected
08-29 15:11:38.114  1349  1361 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.114  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-29 15:11:38.115   873   890 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.116   873   890 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.121  1945  1959 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.125   873   890 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.136  4000  4011 D BluetoothHeadset: Proxy object connected
,08-29 15:11:38.137  4000  4000 D HeadsetProfile: Bluetooth service connected
,08-29 15:11:39.510   873  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-29 15:11:39.556  4082  4235 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 15:11:39.557  4082  4235 D BluetoothAdapterProperties: Setting state to 13
08-29 15:11:39.557  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 15:11:39.561  4082  4235 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 15:11:39.566  4082  4082 D BluetoothMapService: onReceive
,08-29 15:11:39.567  4082  4082 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:39.567  4082  4082 D BluetoothMapService: STATE_TURNING_OFF
08-29 15:11:39.568  4082  4082 D BluetoothMapService: MAP Service closeService in
08-29 15:11:39.568  4082  4082 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 15:11:39.568  4082  4082 D ObexServerSockets0: shutdown(block = true)
,08-29 15:11:39.568  4082  4235 I BluetoothAdapterState: Entering PendingCommandState
08-29 15:11:39.569  4082  4262 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 15:11:39.575  4082  4082 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:11:39.575  4082  4263 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 15:11:39.576  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:39.576  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:39.577  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:39.577  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:39.578  4082  4248 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 15:11:39.578  4082  4082 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:11:39.578  4082  4239 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:39.579  4082  4082 I BtOppRfcommListener: stopping Accept Thread
08-29 15:11:39.579  4082  4271 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:39.582  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 15:11:39.583  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:39.583  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:39.583  4082  4271 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 15:11:39.584  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:39.584  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:39.586  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:39.586  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:11:39.588  4082  4082 D HeadsetService: Received stop request...Stopping profile...
08-29 15:11:39.589  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:39.592  1945  1959 D BluetoothHeadset: Proxy object disconnected
,08-29 15:11:39.592   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 15:11:39.592   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 15:11:39.592   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:39.593  1349  1361 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:39.593  4000  4014 D BluetoothHeadset: Proxy object disconnected
,08-29 15:11:39.595  4082  4082 D A2dpService: Received stop request...Stopping profile...
,08-29 15:11:39.595  4082  4255 D A2dpStateMachine: Exit Disconnected: -1
,08-29 15:11:39.597   873   873 D BluetoothA2dp: Proxy object disconnected
,08-29 15:11:39.598  4082  4082 D HidService: Received stop request...Stopping profile...
,08-29 15:11:39.598  4082  4082 D HidService: Stopping Bluetooth HidService
,08-29 15:11:39.600  4082  4082 V BluetoothAdapterState: isTurningOff()=true
,08-29 15:11:39.600  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-29 15:11:39.600  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:39.600  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:39.600  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-29 15:11:39.600  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:39.600  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-29 15:11:39.600  1349  1349 D HidProfile: Bluetooth service disconnected
,08-29 15:11:39.601  4082  4082 D HealthService: Received stop request...Stopping profile...
08-29 15:11:39.602  4000  4000 D DockEventReceiver: finishStartingService: stopping service
08-29 15:11:39.603  4000  4000 D HeadsetProfile: Bluetooth service disconnected
08-29 15:11:39.603  4000  4000 D BluetoothA2dp: Proxy object disconnected
08-29 15:11:39.603  4082  4082 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 15:11:39.603  4082  4082 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:39.603  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 15:11:39.603  4082  4246 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:11:39.603  4082  4246 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:11:39.603  4082  4246 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:11:39.603  4000  4000 D BluetoothInputDevice: Proxy object disconnected
,08-29 15:11:39.604  4082  4239 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-29 15:11:39.604  4000  4000 D HidProfile: Bluetooth service disconnected
,08-29 15:11:39.605  4082  4082 D PanService: Received stop request...Stopping profile...
08-29 15:11:39.606  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 15:11:39.606  1349  1349 D PanProfile: Bluetooth service disconnected
08-29 15:11:39.607  4000  4000 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 15:11:39.607  4000  4000 D PanProfile: Bluetooth service disconnected
08-29 15:11:39.608  4082  4082 D BluetoothMapService: Received stop request...Stopping profile...
08-29 15:11:39.609  4082  4082 D BluetoothMapService: stop()
08-29 15:11:39.610  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:39.610  4082  4082 D BluetoothMapAppObserver: deinitObservers()
08-29 15:11:39.610  4082  4082 D BluetoothMapAppObserver: removeReceiver()
,08-29 15:11:39.612  1349  1349 D BluetoothMap: Proxy object disconnected
08-29 15:11:39.612  1349  1349 D MapProfile: Bluetooth service disconnected
,08-29 15:11:39.612  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:39.612  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:39.612  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:39.612  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:39.614  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 15:11:39.614  4082  4246 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:39.614  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:39.614  4082  4246 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:11:39.614  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:39.614  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:39.614  4082  4246 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:39.614  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:39.614  4082  4246 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 15:11:39.614  4082  4246 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:39.614  4082  4246 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:39.615  4082  4082 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 15:11:39.615  4082  4239 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 15:11:39.615  4082  4082 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 15:11:39.615  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:39.615  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:11:39.615  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:39.615  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:39.615  4082  4082 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 15:11:39.615  4082  4239 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 15:11:39.616  4082  4082 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:11:39.616  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:39.616  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:11:39.616  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:39.616  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:39.617  4082  4082 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 15:11:39.617  4082  4082 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 15:11:39.617  4000  4000 D BluetoothMap: Proxy object disconnected
,08-29 15:11:39.617  4000  4000 D MapProfile: Bluetooth service disconnected
08-29 15:11:39.619  1349  1349 D BluetoothPbap: Proxy object disconnected
08-29 15:11:39.620  1349  1349 D PbapServerProfile: Bluetooth service disconnected
08-29 15:11:39.620  4082  4082 D BluetoothMapService: MAP Service closeService in
08-29 15:11:39.620  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-29 15:11:39.620  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:39.620  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:11:39.620  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:39.621  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 15:11:39.621  4082  4082 D BluetoothMapService: cleanup()
08-29 15:11:39.621  4082  4235 D BluetoothAdapterProperties: Setting state to 15
08-29 15:11:39.621  4082  4082 D BluetoothMapService: MAP Service closeService in
08-29 15:11:39.621  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 15:11:39.622  4082  4235 I BluetoothAdapterState: Entering BleOnState
08-29 15:11:39.622  4000  4000 D BluetoothPbap: Proxy object disconnected
08-29 15:11:39.622  4000  4000 D PbapServerProfile: Bluetooth service disconnected
08-29 15:11:39.623  1349  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 15:11:39.624  1349  2077 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:11:39.624  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:39.626  1349  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.626  1349  2077 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 15:11:39.627  4000  4011 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:39.628  4000  4013 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.628   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.628  4000  4014 D BluetoothPan: onBluetoothStateChange on: false
08-29 15:11:39.628   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:11:39.629   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:39.629  1349  1361 D BluetoothPan: onBluetoothStateChange on: false
,08-29 15:11:39.629  4000  4011 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:11:39.630  1945  1961 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.630  4000  4013 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 15:11:39.631  4000  4014 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:11:39.631   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:11:39.632  4082  4235 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 15:11:39.632  4082  4235 D BluetoothAdapterProperties: Setting state to 16
08-29 15:11:39.632  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 15:11:39.635  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:39.636  4082  4235 D BluetoothAdapterProperties: onBleDisable
08-29 15:11:39.636  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:39.636  4082  4235 I BluetoothAdapterState: Entering PendingCommandState
08-29 15:11:39.636  4082  4236 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 15:11:39.638  4082  4246 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 15:11:39.638  4082  4246 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:11:39.638  4082  4239 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:39.639  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:39.640  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 15:11:39.640  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:39.645  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:39.646  4000  4000 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:39.838  4082  4239 I bt_hci  : shut_down
,08-29 15:11:39.838  4082  4243 D bt_hwcfg: hw_epilog_process
,08-29 15:11:39.850  4082  4243 I bt_vendor: low_power_mode_cb
,08-29 15:11:39.875  4082  4243 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 15:11:39.875  4082  4243 I bt_vendor: epilog_cb
,08-29 15:11:39.875  4082  4243 I bt_hci  : epilog_finished_callback
,08-29 15:11:39.882  4082  4239 I bt_hci_h4: hal_close
,08-29 15:11:39.884  4082  4239 I bt_userial_vendor: device fd = 51 close
,08-29 15:11:40.011  4082  4236 D bt_stack_manager: event_shut_down_stack finished.
,08-29 15:11:40.012  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 15:11:40.018  4082  4235 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 15:11:40.018  4082  4082 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 15:11:40.020  4082  4082 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 15:11:40.020  4082  4082 D BtGatt.GattService: stop()
08-29 15:11:40.021  4082  4082 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 15:11:40.026  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:40.026  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:40.027  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:40.027  4082  4082 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 15:11:40.028  4082  4235 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 15:11:40.028  4082  4235 D BluetoothAdapterProperties: Setting state to 10
,08-29 15:11:40.029  4082  4235 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 15:11:40.031  4082  4235 I BluetoothAdapterState: Entering OffState
,08-29 15:11:40.032   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 15:11:40.060  4082  4082 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 15:11:40.060  4082  4082 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 15:11:40.061  4082  4236 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 15:11:40.061  4082  4082 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 15:11:40.068  4082  4236 D bt_stack_manager: event_clean_up_stack finished.
,08-29 15:11:40.075  4082  4082 I art     : System.exit called, status: 0
,08-29 15:11:40.075  4082  4082 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 15:11:40.118   873  1693 I ActivityManager: Process com.android.bluetooth (pid 4082) has died
,08-29 15:11:42.554  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:42.554  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:45.562  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:11:45.562  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d939910 added. We now have 6 listener(s)
,08-29 15:11:45.562  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:45.567  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:45.568  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2db3c09 added. We now have 7 listener(s)
,08-29 15:11:45.568  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:45.570  3926  3977 I System.out: IsBluetoothEnabled
,08-29 15:11:45.585  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:45.633   873   890 I ActivityManager: Start proc 4283:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 15:11:45.741   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 15:11:45.750  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-29 15:11:45.757   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 15:11:45.757   873   893 I Adreno  : Build Date                       : 10/20/15
08-29 15:11:45.757   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 15:11:45.757   873   893 I Adreno  : Local Branch                     : M14
08-29 15:11:45.757   873   893 I Adreno  : Remote Branch                    : 
08-29 15:11:45.757   873   893 I Adreno  : Remote Branch                    : 
08-29 15:11:45.757   873   893 I Adreno  : Reconstruct Branch               : 
,08-29 15:11:45.788   281  1294 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (179 us)
,08-29 15:11:45.823  4283  4283 D AdapterServiceConfig: Adding HeadsetService
,08-29 15:11:45.825  4283  4283 D AdapterServiceConfig: Adding A2dpService
08-29 15:11:45.825  4283  4283 D AdapterServiceConfig: Adding HidService
,08-29 15:11:45.825  4283  4283 D AdapterServiceConfig: Adding HealthService
,08-29 15:11:45.826  4283  4283 D AdapterServiceConfig: Adding PanService
,08-29 15:11:45.828  4283  4283 D AdapterServiceConfig: Adding GattService
,08-29 15:11:45.829  4283  4283 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 15:11:45.862  4283  4283 D BluetoothAdapterState: make() - Creating AdapterState
08-29 15:11:45.862   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4e3979:true
,08-29 15:11:45.867  4283  4283 I bt_bluedroid: init
,08-29 15:11:45.870  4283  4296 I BluetoothAdapterState: Entering OffState
,08-29 15:11:45.876  4283  4297 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 15:11:45.880  4283  4297 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 15:11:45.880  4283  4297 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 15:11:45.881  4283  4297 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 15:11:45.885  4283  4283 I bt_bluedroid: get_profile_interface socket
,08-29 15:11:45.896  4283  4300 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:11:45.898  4283  4300 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 15:11:45.900  4283  4283 I bt_bluedroid: get_profile_interface sdp
,08-29 15:11:45.908  4283  4294 I bt_bluedroid: config_hci_snoop_log
,08-29 15:11:45.910   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 15:11:45.915  4283  4296 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 15:11:45.915  4283  4296 D BluetoothAdapterProperties: Setting state to 14
08-29 15:11:45.915  4283  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 15:11:45.916  4283  4296 D BluetoothBondStateMachine: make
,08-29 15:11:45.922  4283  4296 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:11:45.920  4283  4301 I BluetoothBondStateMachine: StableState(): Entering Off State,
,08-29 15:11:45.924  4283  4283 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 15:11:45.931  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:45.934  4283  4283 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 15:11:45.935  4283  4283 D BtGatt.GattService: Received start request. Starting profile...
,08-29 15:11:45.936  4283  4283 D BtGatt.GattService: start()
,08-29 15:11:45.936  4283  4283 I bt_bluedroid: get_profile_interface gatt
,08-29 15:11:45.938  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:45.938  4283  4283 D BtGatt.AdvertiseManager: advertise manager created
,08-29 15:11:45.949  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:45.950  4283  4283 V BluetoothAdapterState: isTurningOn()=false
08-29 15:11:45.950  4283  4283 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 15:11:45.951  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:45.951  4283  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 15:11:45.951  4283  4296 I bt_bluedroid: enable
,08-29 15:11:45.951  4283  4297 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 15:11:45.951  4283  4297 I bt_hci  : start_up
,08-29 15:11:45.957  4283  4297 I bt_vendor: alloc value 0xb3a45189
,08-29 15:11:45.957  4283  4297 I bt_vendor: init
08-29 15:11:45.957  4283  4297 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 15:11:45.957  4283  4297 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 15:11:46.065  4283  4297 D bt_hci  : start_up starting async portion
,08-29 15:11:46.068  4283  4305 I bt_hci  : event_finish_startup
08-29 15:11:46.068  4283  4305 I bt_hci_h4: hal_open
,08-29 15:11:46.068  4283  4305 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 15:11:46.080  4283  4305 I bt_userial_vendor: device fd = 51 open
,08-29 15:11:46.112  4283  4305 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:11:46.140  4283  4305 D bt_hwcfg: Chipset BCM4354A2
,08-29 15:11:46.142  4283  4305 D bt_hwcfg: Target name = [BCM4354A2]
08-29 15:11:46.143  4283  4305 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 15:11:46.419  3926  3926 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 15:11:46.419  3926  3926 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 15:11:46.451   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 15:11:46.454  3926  3926 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3999776 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b997e0e, 16908290=android.view.AbsSavedState$1@b997e0e}, android:focusedViewId=100}]}]
,08-29 15:11:46.454  3926  3926 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 15:11:46.455  3926  3926 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 15:11:46.455  3926  3926 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 15:11:46.461   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 15:11:46.464   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 15:11:46.465   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-29 15:11:46.466   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 15:11:46.524   873   882 I art     : Background partial concurrent mark sweep GC freed 12320(1017KB) AllocSpace objects, 8(240KB) LOS objects, 33% free, 28MB/43MB, paused 1.225ms total 128.261ms
,08-29 15:11:46.721   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 15:11:46.724   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 15:11:46.729   873  1330 D SurfaceControl: Excessive delay in setPowerMode(): 260ms
,08-29 15:11:46.733   873   893 I DreamManagerService: Entering dreamland.
08-29 15:11:46.734   873   893 I PowerManagerService: Dozing...
08-29 15:11:46.736   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 15:11:46.789   375  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 15:11:46.789   375  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 15:11:46.795   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:11:46.801   873  1305 E native  : do suspend false
,08-29 15:11:46.808  1932  4308 D NfcService: Discovery configuration equal, not updating.
,08-29 15:11:46.829   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:11:46.834   873  1305 E native  : do suspend true
,08-29 15:11:46.850  4283  4305 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 15:11:46.850  4283  4305 D bt_hwcfg: Settlement delay -- 100 ms
08-29 15:11:46.850  4283  4305 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 15:11:46.932   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 15:11:46.932   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 15:11:46.967  4283  4305 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:11:46.968  4283  4305 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 15:11:47.001  4283  4305 I bt_hwcfg: vendor lib fwcfg completed
,08-29 15:11:47.001  4283  4305 I bt_vendor: firmware callback
08-29 15:11:47.001  4283  4305 I bt_hci  : firmware_config_callback
,08-29 15:11:47.019  4283  4312 I bt_btu  : btu_task pending for preload complete event
,08-29 15:11:47.019  4283  4312 I bt_btu_task: Bluetooth chip preload is complete
,08-29 15:11:47.020  4283  4312 I bt_btu  : btu_task received preload complete event
,08-29 15:11:47.032  4283  4312 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 15:11:47.032  4283  4312 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 15:11:47.032  4283  4312 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 15:11:47.033  4283  4312 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 15:11:47.033  4283  4312 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 15:11:47.033  4283  4312 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 15:11:47.034  4283  4312 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 15:11:47.181  4283  4312 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c2d9d
,08-29 15:11:47.181  4283  4312 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c2d9d 
,08-29 15:11:47.189  4283  4300 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 15:11:47.190  4283  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 15:11:47.191  4283  4300 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:11:47.195  4283  4300 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 15:11:47.201  4283  4300 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:11:47.202  4283  4300 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 15:11:47.203  4283  4300 D bt_hci  : do_postload posting postload work item
08-29 15:11:47.203  4283  4305 I bt_hci  : event_postload
08-29 15:11:47.204  4283  4305 I bt_vendor: sco_config_cb
08-29 15:11:47.204  4283  4305 I bt_hci  : sco_config_callback postload finished.
08-29 15:11:47.206  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:47.211  4283  4300 D bt_bte_conf: Device ID record 1 : primary
08-29 15:11:47.211  4283  4300 D bt_bte_conf:   vendorId            = 000f
08-29 15:11:47.212  4283  4300 D bt_bte_conf:   vendorIdSource      = 0001
08-29 15:11:47.212  4283  4300 D bt_bte_conf:   product             = 1200
,08-29 15:11:47.212  4283  4300 D bt_bte_conf:   version             = 1436
08-29 15:11:47.212  4283  4300 D bt_bte_conf:   clientExecutableURL = 
08-29 15:11:47.212  4283  4300 D bt_bte_conf:   serviceDescription  = 
08-29 15:11:47.213  4283  4300 D bt_bte_conf:   documentationURL    = 
08-29 15:11:47.213  4283  4300 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 15:11:47.213  4283  4297 D bt_stack_manager: event_start_up_stack finished
08-29 15:11:47.215  4283  4305 I bt_vendor: low_power_mode_cb
,08-29 15:11:47.216  4283  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 15:11:47.217  4283  4296 D BluetoothAdapterProperties: Setting state to 15
,08-29 15:11:47.217  4283  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 15:11:47.220  4283  4296 I BluetoothAdapterState: Entering BleOnState
,08-29 15:11:47.225  4283  4296 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 15:11:47.225  4283  4296 D BluetoothAdapterProperties: Setting state to 11
,08-29 15:11:47.226  4283  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 15:11:47.240  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:47.240  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:47.245  4283  4283 D HeadsetService: Received start request. Starting profile...
,08-29 15:11:47.253  4283  4283 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 15:11:47.254  4283  4283 D HeadsetStateMachine: make
,08-29 15:11:47.260  4283  4296 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:11:47.266  4283  4283 D HeadsetStateMachine: max_hf_connections = 1
,08-29 15:11:47.266  4283  4283 I bt_bluedroid: get_profile_interface handsfree
,08-29 15:11:47.266  4283  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 15:11:47.266  4283  4300 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-29 15:11:47.270  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:47.270  4283  4283 D A2dpService: Received start request. Starting profile...
,08-29 15:11:47.271  4283  4283 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 15:11:47.271  4283  4283 I bt_bluedroid: get_profile_interface avrcp
,08-29 15:11:47.279  4283  4283 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 15:11:47.279  4283  4283 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 15:11:47.280  4283  4283 D A2dpStateMachine: make
08-29 15:11:47.281  4283  4283 I bt_bluedroid: get_profile_interface a2dp
,08-29 15:11:47.283  4283  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 15:11:47.285  4283  4283 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 15:11:47.287  4283  4321 D A2dpStateMachine: Enter Disconnected: -2
,08-29 15:11:47.286  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:47.288  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:47.288  4283  4283 D HidService: Received start request. Starting profile...
,08-29 15:11:47.289  4283  4283 I bt_bluedroid: get_profile_interface hidhost
08-29 15:11:47.289  4283  4300 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a43e5
,08-29 15:11:47.289  4283  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 15:11:47.290  4283  4283 D HidService: setHidService(): set to: null
08-29 15:11:47.290  4283  4283 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 15:11:47.292  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:47.292  4283  4283 D HealthService: Received start request. Starting profile...
08-29 15:11:47.294  4283  4283 I bt_bluedroid: get_profile_interface health
,08-29 15:11:47.295  4283  4283 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 15:11:47.296  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
08-29 15:11:47.297  4283  4283 D PanService: Received start request. Starting profile...
08-29 15:11:47.297  4283  4283 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 15:11:47.297  4283  4283 I bt_bluedroid: get_profile_interface pan
08-29 15:11:47.297  4283  4300 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 15:11:47.299  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:47.301  4283  4283 D BluetoothMapService: Received start request. Starting profile...
08-29 15:11:47.301  4283  4283 D BluetoothMapService: start()
,08-29 15:11:47.305  4283  4283 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 15:11:47.306  4283  4283 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 15:11:47.307  4283  4283 D BluetoothMapAppObserver: createReceiver()
,08-29 15:11:47.309  4283  4283 D BluetoothMapAppObserver: initObservers()
,08-29 15:11:47.309  4283  4283 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 15:11:47.319  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:47.319  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:47.319  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:47.319  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:47.322  4283  4319 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 15:11:47.322  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:47.322  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:47.322  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:47.322  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:47.322  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:47.322  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:47.323  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:47.323  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-29 15:11:47.325  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:11:47.326  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:47.326  4283  4283 V BluetoothAdapterState: isTurningOff()=false
08-29 15:11:47.326  4283  4283 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:11:47.326  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:11:47.326  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:11:47.326  4283  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2,
08-29 15:11:47.326  4283  4296 D BluetoothAdapterProperties: ScanMode =  20
08-29 15:11:47.326  4283  4296 D BluetoothAdapterProperties: State =  11
,08-29 15:11:47.328  4283  4296 D BluetoothAdapterProperties: Setting state to 12
08-29 15:11:47.328  4283  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 15:11:47.328  1349  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 15:11:47.329  4283  4300 D BluetoothAdapterProperties: Scan Mode:21
08-29 15:11:47.329  4283  4300 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:11:47.330  4283  4296 I BluetoothAdapterState: Entering OnState
,08-29 15:11:47.332  1349  1361 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:11:47.332  1349  1349 D BluetoothInputDevice: Proxy object connected
08-29 15:11:47.332  1349  1349 D HidProfile: Bluetooth service connected
,08-29 15:11:47.333  1349  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:47.334  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:47.335  1349  2077 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:47.335  1349  1349 D BluetoothMap: Proxy object connected
08-29 15:11:47.335  1349  1349 D MapProfile: Bluetooth service connected
08-29 15:11:47.335  1349  1349 D BluetoothMap: getConnectedDevices(),
08-29 15:11:47.336  1349  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 15:11:47.336  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:47.337  1349  1349 D BluetoothA2dp: Proxy object connected
,08-29 15:11:47.337  4283  4283 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 15:11:47.338  4000  4011 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:11:47.338  4283  4283 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 15:11:47.340  4283  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:47.340  4000  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:47.340   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:47.341  4000  4013 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:11:47.341  4000  4000 D BluetoothA2dp: Proxy object connected
,08-29 15:11:47.342  4283  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:47.343   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:47.343   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:11:47.343   873   873 D BluetoothA2dp: Proxy object connected
08-29 15:11:47.343  1349  1361 D BluetoothPan: onBluetoothStateChange on: true
,08-29 15:11:47.344  4283  4283 D ObexServerSockets: Succeed to create listening sockets 
08-29 15:11:47.344  4283  4283 D ObexServerSockets0: startAccept()
,08-29 15:11:47.344  4283  4283 D ObexServerSockets0: prepareForNewConnect()
08-29 15:11:47.345  4000  4011 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 15:11:47.346  4283  4283 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 15:11:47.346  4283  4283 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 15:11:47.347  4283  4327 D ObexServerSockets0: Accepting socket connection...
08-29 15:11:47.348  1945  2164 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:47.348  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 15:11:47.348  1349  1349 D PanProfile: Bluetooth service connected
08-29 15:11:47.348  4000  4011 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 15:11:47.348  4283  4328 D ObexServerSockets0: Accepting socket connection...
,08-29 15:11:47.350  4000  4013 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:11:47.352   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:47.353  4000  4000 D BluetoothInputDevice: Proxy object connected
08-29 15:11:47.353  4000  4000 D HidProfile: Bluetooth service connected
,08-29 15:11:47.354   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 15:11:47.354  4283  4283 D BluetoothMapService: onReceive
,08-29 15:11:47.354  4283  4283 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:47.355  4283  4283 D BluetoothMapService: STATE_ON
,08-29 15:11:47.357  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:47.358  4000  4000 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:11:47.358  4000  4000 D PanProfile: Bluetooth service connected
,08-29 15:11:47.358  4000  4000 D BluetoothMap: Proxy object connected
08-29 15:11:47.358  4000  4000 D MapProfile: Bluetooth service connected
,08-29 15:11:47.358  4000  4000 D BluetoothMap: getConnectedDevices()
,08-29 15:11:47.365  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:11:47.371  4000  4000 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:47.373  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:47.383  4000  4000 D BluetoothPbap: Proxy object connected
,08-29 15:11:47.383  4000  4000 D PbapServerProfile: Bluetooth service connected
08-29 15:11:47.383  1349  1349 D BluetoothPbap: Proxy object connected
08-29 15:11:47.383  1349  1349 D PbapServerProfile: Bluetooth service connected
08-29 15:11:47.384  4283  4283 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 15:11:47.384  4283  4283 D ObexServerSockets0: prepareForNewConnect()
,08-29 15:11:47.392  4283  4332 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:47.413  4283  4336 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:47.414  4283  4336 I BtOppRfcommListener: Accept thread started.
,08-29 15:11:47.438  1945  1959 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.439   873   873 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.439   873   873 D BluetoothHeadset: Proxy object connected,
,08-29 15:11:47.439   873   873 D BluetoothHeadset: Proxy object connected
08-29 15:11:47.440  1349  1372 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.441  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-29 15:11:47.441  4000  4013 D BluetoothHeadset: Proxy object connected
08-29 15:11:47.442  4000  4014 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.442   873   890 D BluetoothHeadset: Proxy object connected
08-29 15:11:47.442  4000  4000 D HeadsetProfile: Bluetooth service connected
08-29 15:11:47.443   873   890 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.446  4000  4000 D HeadsetProfile: Bluetooth service connected
,08-29 15:11:47.448  1945  1961 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.452   873   890 D BluetoothHeadset: Proxy object connected
,08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:47.612  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:47.620  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:47.624  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:11:47.625  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@197202f added. We now have 8 listener(s)
08-29 15:11:47.625  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:47.631   873  2109 D WifiService: setWifiEnabled: false pid=3926, uid=10000
,08-29 15:11:47.631   873  2109 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:47.645  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:47.646   873  1951 D WifiService: setWifiEnabled: true pid=3926, uid=10000
,08-29 15:11:47.646   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:47.658   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:47.677  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:47.685  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:47.690   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-29 15:11:47.691   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 15:11:47.692   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 15:11:47.693   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 15:11:47.693   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 15:11:47.694   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 15:11:47.694   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 15:11:47.712   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 15:11:47.713   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.04 delta 1000 -> 1000
,08-29 15:11:47.713   371   871 D CommandListener: Setting iface cfg
,08-29 15:11:47.714   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 15:11:47.714   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
08-29 15:11:47.714   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 15:11:47.726   873  1305 E native  : do suspend true
,08-29 15:11:47.726   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
08-29 15:11:47.726   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 15:11:47.763   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 15:11:47.763   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:47.775   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 15:11:47.828   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 15:11:47.830  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 15:11:48.255  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 15:11:48.296  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 15:11:48.296  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 15:11:48.302   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:11:48.315   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:11:48.315   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:48.316   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 15:11:48.336   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:11:48.353   371   871 D CommandListener: Setting iface cfg
08-29 15:11:48.354   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 15:11:48.363   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 15:11:48.405   873  4343 D DhcpClient: Receive thread started
,08-29 15:11:48.494   873  1305 E native  : do suspend false
,08-29 15:11:48.513   873  1866 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 15:11:48.529   873  4343 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
08-29 15:11:48.530   873  1866 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 15:11:48.534   873  1866 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 15:11:48.550   873  4343 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 15:11:48.551   873  1866 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 15:11:48.557   371   871 D CommandListener: Setting iface cfg
,08-29 15:11:48.569   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 15:11:48.570   873  1866 D DhcpClient: Scheduling renewal in 86399s
,08-29 15:11:48.571   873  1305 E native  : do suspend true
,08-29 15:11:48.596   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 15:11:48.599   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 15:11:48.601   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 15:11:48.603   873  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 15:11:48.612   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:48.667  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:48.672  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:48.676  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 15:11:48.676  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,08-29 15:11:48.679  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3999776 Bundle[{}],
,08-29 15:11:48.679  3926  3977 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 15:11:48.680  3926  3977 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 15:11:48.680  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivityStarted,
08-29 15:11:48.681  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 15:11:48.681  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 15:11:48.682  3926  3977 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 15:11:48.684   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 15:11:48.684   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 15:11:48.687   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 15:11:48.688  3926  3977 I System.out: Running OutgoingSocketThread
,08-29 15:11:48.691   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 15:11:48.691  3926  4347 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 451)
,08-29 15:11:48.695  3926  4347 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38300
,08-29 15:11:48.695  3926  4347 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 15:11:48.695   873  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 15:11:48.707   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 15:11:48.711   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 15:11:48.711   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-29 15:11:48.712   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 15:11:48.712   873  1307 D ConnectivityService:    accepting network in place of null,
08-29 15:11:48.712   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 15:11:48.713   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:11:48.713   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:11:48.766   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:11:48.814   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:11:48.823   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 15:11:48.823   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:48.831   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 15:11:48.833   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:48.847  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:48.857  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:48.871  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:11:48.875  1704  1704 D SystemUpdateService: onCreate
,08-29 15:11:48.881  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:11:48.896  1704  4354 I SystemUpdateService: active receiver: enabled
,08-29 15:11:48.907  1704  4354 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:11:48.908  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 15:11:48.918  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:11:48.920  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:11:48.922  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:48.929  4096  4096 D SprintDMHelper: simOperator: 
,08-29 15:11:48.929  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:11:48.934  1704  4357 I MDM     : [188] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 15:11:48.934  1704  4357 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 15:11:48.936  1704  4357 V GoogleAuthProtoRequest: [188] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:11:48.952  1704  2448 I iu.UploadsManager: num queued entries: 0
,08-29 15:11:48.956  1704  4354 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 15:11:48.956  1704  2448 I iu.UploadsManager: num updated entries: 0
08-29 15:11:48.956  1704  4354 I SystemUpdateService: now status is 0 (complete)
,08-29 15:11:48.957  1704  4354 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 15:11:48.959  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:48.962  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:11:48.962  1704  4354 I SystemUpdateService: file has been verified
08-29 15:11:48.963  1704  4354 I SystemUpdateService: OTA package size = 12249756
08-29 15:11:48.970  1704  2448 I iu.SyncManager: NEXT; no task
,08-29 15:11:48.973  1704  4354 I SystemUpdateService: showing system update notification
,08-29 15:11:48.997  1704  1704 D SystemUpdateService: onDestroy
,08-29 15:11:49.020  1507  2300 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 15:11:49.020  1507  2300 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 15:11:49.020  1507  2300 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:49.021  1507  2300 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:49.049  1704  4357 E MDM     : [188] SitrepService.a: Error sending sitrep.
,08-29 15:11:49.692  3926  3977 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 452)
08-29 15:11:49.692  3926  3977 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 452)
,08-29 15:11:49.701  3926  3977 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 457)
,08-29 15:11:49.704  3926  3977 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 15:11:49.704  3926  3977 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 458)
,08-29 15:11:49.711  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:49.712  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c81363c added. We now have 2 listener(s)
,08-29 15:11:49.717  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:11:49.717  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:11:49.717  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 15:11:49.718  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.718  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff28fc5 added. We now have 9 listener(s)
08-29 15:11:49.718  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:49.720  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:11:49.726  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:49.735  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:49.740  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:49.740  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:11:49.742  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:49.743  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7f904b added. We now have 3 listener(s)
,08-29 15:11:49.745  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:49.750  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:49.752  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:11:49.753  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:11:49.753  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 15:11:49.753  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.755  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2497a28 added. We now have 10 listener(s)
,08-29 15:11:49.755  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:49.755  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:49.756  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:49.756  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:49.756  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:49.757  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.757  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:11:49.758  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:49.758  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c81363c removed from the list
08-29 15:11:49.759  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.759  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff28fc5 removed from the list
,08-29 15:11:49.760  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:49.761  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:49.761  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.761  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:49.763  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:49.763  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.763  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.763  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff28fc5 not in the list
08-29 15:11:49.763  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.763  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:49.766  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.767  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:49.767  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.767  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2497a28 removed from the list
08-29 15:11:49.767  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:49.767  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.767  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:49.767  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:49.767  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7f904b removed from the list
08-29 15:11:49.768  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:11:49.768  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f716341 added. We now have 2 listener(s)
08-29 15:11:49.770  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:49.770  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:11:49.770  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:49.770  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.770  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cb40e6 added. We now have 9 listener(s)
08-29 15:11:49.771  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:49.771  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:11:49.774  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:49.779  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:49.782  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:49.782  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:11:49.783  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:49.783  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd010d4 added. We now have 3 listener(s)
,08-29 15:11:49.785  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:49.785  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:49.786  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:49.786  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:49.786  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.786  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaff27d added. We now have 10 listener(s)
08-29 15:11:49.786  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:49.786  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:11:49.787  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:49.787  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:49.787  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:49.787  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:11:49.787  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:49.794  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:11:49.794  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:11:49.799  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:11:49.799  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 15:11:49.799  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:49.803  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 15:11:49.803  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:11:49.803  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 15:11:49.804  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:49.807  4283  4294 D BtGatt.GattService: registerClient() - UUID=1f080464-ba09-49b8-80f6-35004043e565
,08-29 15:11:49.808  4283  4300 D BtGatt.GattService: onClientRegistered() - UUID=1f080464-ba09-49b8-80f6-35004043e565, clientIf=5
,08-29 15:11:49.810  3926  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 15:11:49.811  4283  4293 D BtGatt.GattService: start scan with filters
,08-29 15:11:49.815  4283  4304 D BtGatt.ScanManager: handling starting scan
,08-29 15:11:49.816  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 15:11:49.816  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 15:11:49.816  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:11:49.816  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:11:49.817  4283  4304 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@af67aaa
,08-29 15:11:49.821   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 15:11:49.822  4283  4300 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 15:11:49.822  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:49.823  4283  4304 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:11:49.827  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:49.827  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:11:49.828  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:11:49.831  4283  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 15:11:49.831  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:49.832  4283  4304 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 15:11:49.832  4283  4304 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 15:11:49.837  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:11:49.844  3926  3977 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 15:11:49.845  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:49.845  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 15:11:49.845  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.846  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:11:49.846  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 15:11:49.846  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:11:49.846  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 15:11:49.846  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:49.847  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:11:49.847  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 15:11:49.850  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:49.851  4283  4326 D BtGatt.GattService: stopScan() - queue size =1
,08-29 15:11:49.852  4283  4318 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 15:11:49.853  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 15:11:49.854  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 15:11:49.854  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 15:11:49.854  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 15:11:49.854  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 15:11:49.855  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:49.855  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:11:49.855  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:11:49.855  4283  4300 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 15:11:49.855  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:11:49.855  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.856  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:49.857  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:49.857  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:49.857  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:49.861  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:49.861  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:49.862  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:49.862  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:49.862  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.862  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:49.862  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 15:11:49.862  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f716341 removed from the list
08-29 15:11:49.862  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:49.863  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cb40e6 removed from the list
08-29 15:11:49.863  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:49.863  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:49.863  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.863  4283  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 15:11:49.864  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:49.864  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.865  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:49.865  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.865  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:49.865  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cb40e6 not in the list
08-29 15:11:49.865  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.865  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:49.866  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.866  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:49.866  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:49.866  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaff27d removed from the list
08-29 15:11:49.866  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:49.866  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.867  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:49.867  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 15:11:49.867  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd010d4 removed from the list
08-29 15:11:49.868  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:11:49.868  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4e3979 added. We now have 2 listener(s)
,08-29 15:11:49.869  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:49.870  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:11:49.870  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:49.870  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.870  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96786be added. We now have 9 listener(s)
,08-29 15:11:49.870  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:49.871  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:11:49.875  4283  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 15:11:49.875  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:49.875  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.875  4283  4304 D BtGatt.ScanManager: stopping BLe Batch
,08-29 15:11:49.881  4283  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 15:11:49.882  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:49.882  4283  4304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:49.882  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:49.884  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:49.885  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:11:49.886  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:49.886  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69ca66c added. We now have 3 listener(s)
08-29 15:11:49.887  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 15:11:49.888  4283  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 15:11:49.888  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:49.890  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:49.890  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:11:49.891  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:49.891  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 15:11:49.891  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:11:49.891  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeff435 added. We now have 10 listener(s)
08-29 15:11:49.892  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 15:11:49.892  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:11:49.893  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:11:49.893  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:49.893  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 15:11:49.894  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:49.894  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 15:11:49.897  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:11:49.897  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:11:49.901  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:11:49.901  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 15:11:49.902  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:49.904  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 15:11:49.904  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 15:11:49.904  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 15:11:49.905  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:49.907  4283  4293 D BtGatt.GattService: registerClient() - UUID=a0b34374-2a9d-4ba5-8b69-195f08fc6ef4
,08-29 15:11:49.907  4283  4300 D BtGatt.GattService: onClientRegistered() - UUID=a0b34374-2a9d-4ba5-8b69-195f08fc6ef4, clientIf=5
08-29 15:11:49.908  3926  3937 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 15:11:49.908  4283  4326 D BtGatt.GattService: start scan with filters
,08-29 15:11:49.911  4283  4304 D BtGatt.ScanManager: handling starting scan
,08-29 15:11:49.911  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 15:11:49.911  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 15:11:49.911  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:11:49.911  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:11:49.915  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:49.915  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:11:49.915  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:11:49.917  4283  4300 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 15:11:49.917  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 15:11:49.917  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.918  4283  4304 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:11:49.921  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:11:49.921  3926  3977 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 15:11:49.922  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:49.922  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:49.922  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:11:49.922  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:49.922  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.922  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:11:49.923  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:49.923  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4e3979 removed from the list
08-29 15:11:49.923  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:49.923  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96786be removed from the list
08-29 15:11:49.923  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:49.923  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:11:49.924  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.924  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 15:11:49.924  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.924  4283  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 15:11:49.924  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:49.924  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.925  4283  4304 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:11:49.925  4283  4304 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 15:11:49.926  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:49.926  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.926  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.926  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96786be not in the list
08-29 15:11:49.926  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:11:49.926  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:11:49.926  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:49.927  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:11:49.927  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 15:11:49.927  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:49.928  4283  4294 D BtGatt.GattService: stopScan() - queue size =1
,08-29 15:11:49.929  4283  4293 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:11:49.929  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:49.930  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 15:11:49.930  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 15:11:49.930  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 15:11:49.930  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:11:49.931  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:49.931  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:11:49.931  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:11:49.931  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:11:49.932  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:49.933  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:11:49.933  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:49.933  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:49.934  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.934  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:49.934  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.934  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeff435 removed from the list
08-29 15:11:49.934  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:49.934  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.934  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:49.934  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 15:11:49.934  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69ca66c removed from the list
08-29 15:11:49.935  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:11:49.935  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db89eb1 added. We now have 2 listener(s)
,08-29 15:11:49.936  4283  4300 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 15:11:49.936  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.937  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:49.937  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:49.937  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:49.937  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.938  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dbaf96 added. We now have 9 listener(s)
08-29 15:11:49.938  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:49.938  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:11:49.941  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:49.943  4283  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:11:49.943  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:49.946  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:49.948  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:49.948  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:49.949  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:11:49.949  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b835704 added. We now have 3 listener(s)
,08-29 15:11:49.951  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:49.951  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:11:49.951  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:49.951  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:49.952  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.952  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8774ed added. We now have 10 listener(s)
,08-29 15:11:49.952  4283  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 15:11:49.952  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:49.952  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.952  4283  4304 D BtGatt.ScanManager: stopping BLe Batch
08-29 15:11:49.952  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:11:49.952  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:49.952  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:49.952  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:49.952  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 15:11:49.953  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:49.956  3926  3977 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 15:11:49.956  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:11:49.960  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:11:49.960  4283  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 15:11:49.960  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.960  4283  4304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 15:11:49.961  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 15:11:49.961  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:49.966  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 15:11:49.966  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:11:49.966  4283  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 15:11:49.966  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.966  3926  3977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 15:11:49.967  3926  3977 D BluetoothAdapter: STATE_ON
,08-29 15:11:49.969  4283  4294 D BtGatt.GattService: registerClient() - UUID=4e0db20a-fb15-4c5b-b1c4-6a2080685664
,08-29 15:11:49.969  4283  4300 D BtGatt.GattService: onClientRegistered() - UUID=4e0db20a-fb15-4c5b-b1c4-6a2080685664, clientIf=5
,08-29 15:11:49.969  3926  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 15:11:49.970  4283  4318 D BtGatt.GattService: start scan with filters
,08-29 15:11:49.973  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 15:11:49.973  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 15:11:49.973  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:11:49.973  4283  4304 D BtGatt.ScanManager: handling starting scan
08-29 15:11:49.973  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:11:49.977  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:11:49.977  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:11:49.977  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:11:49.979  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:11:49.980  4283  4300 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 15:11:49.980  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.980  4283  4304 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:11:49.984  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:11:49.984  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:49.984  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:49.984  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:49.984  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.984  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:11:49.984  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:49.984  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db89eb1 removed from the list
08-29 15:11:49.985  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.985  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dbaf96 removed from the list
,08-29 15:11:49.985  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:49.985  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:49.985  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.985  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 15:11:49.985  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:49.985  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:11:49.986  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:49.986  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:49.986  4283  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 15:11:49.986  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.987  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:49.987  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dbaf96 not in the list
08-29 15:11:49.987  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:11:49.987  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:11:49.987  4283  4304 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 15:11:49.987  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:49.987  4283  4304 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 15:11:49.987  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 15:11:49.987  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 15:11:49.988  3926  3977 D BluetoothAdapter: STATE_ON
08-29 15:11:49.988  4283  4326 D BtGatt.GattService: stopScan() - queue size =1
08-29 15:11:49.989  4283  4293 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:11:49.989  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:49.989  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 15:11:49.989  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 15:11:49.990  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 15:11:49.990  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:11:49.990  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:49.991  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:11:49.991  3926  3977 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 15:11:49.991  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:11:49.991  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:49.992  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:11:49.992  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:49.993  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:11:49.993  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:49.993  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:49.993  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:49.993  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8774ed removed from the list
08-29 15:11:49.993  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:49.993  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:49.993  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:49.993  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:49.993  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b835704 removed from the list
08-29 15:11:49.995  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:11:49.995  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f372e9 added. We now have 2 listener(s)
,08-29 15:11:49.997  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:11:49.997  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:11:49.997  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:49.997  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:49.997  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae11b6e added. We now have 9 listener(s)
,08-29 15:11:49.997  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:49.998  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:11:49.999  4283  4300 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 15:11:49.999  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:50.001  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:50.005  4283  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:11:50.005  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:50.006  3926  3977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:50.008  3926  3977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:50.008  3926  3977 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:50.009  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:50.009  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4c829c added. We now have 3 listener(s)
,08-29 15:11:50.010  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:50.011  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:11:50.012  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:11:50.012  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:50.012  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:50.012  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0754a5 added. We now have 10 listener(s)
08-29 15:11:50.012  3926  3977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:50.012  3926  3977 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:50.012  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:50.013  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:50.013  4283  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 15:11:50.013  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:50.013  3926  3977 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:50.014  4283  4304 D BtGatt.ScanManager: stopping BLe Batch
08-29 15:11:50.014  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:50.014  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:50.014  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:50.014  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:50.014  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f372e9 removed from the list
08-29 15:11:50.014  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:50.015  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae11b6e removed from the list
,08-29 15:11:50.015  3926  3977 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:50.015  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:50.016  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:50.016  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:50.019  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:50.019  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:50.019  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:50.019  3926  3977 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae11b6e not in the list
08-29 15:11:50.019  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:50.019  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:50.020  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:50.020  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:50.020  3926  3977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:50.020  3926  3977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0754a5 removed from the list
08-29 15:11:50.020  3926  3977 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:50.020  3926  3977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:50.021  3926  3977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:50.021  3926  3977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:50.021  3926  3977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4c829c removed from the list
08-29 15:11:50.021  4283  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 15:11:50.021  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:11:50.021  4283  4304 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:11:50.022  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 15:11:50.022  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:11:50.022  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 15:11:50.022  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:11:50.022  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 15:11:50.022  3926  3977 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:11:50.027  4283  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 15:11:50.027  4283  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:11:50.030  3926  4363 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,08-29 15:11:50.030  3926  4363 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 465, thread name: My test thread name)
08-29 15:11:50.030  3926  4363 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 15:11:50.032  3926  4364 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: My test thread name)
08-29 15:11:50.032  3926  4364 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 467, thread name: My test thread name)
08-29 15:11:50.032  3926  4364 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 15:11:50.034  3926  3977 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 15:11:50.034  3926  3977 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 15:11:50.034  3926  3977 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 15:11:50.034  3926  3977 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 15:11:50.034  3926  3977 D com.test.thalitest.ThaliTestRunner: Total duration: 22858 ms
,08-29 15:11:50.036  3926  3977 I jxcore-log: *Native tests were executed*
08-29 15:11:50.036  3926  3977 I jxcore-log: 
,08-29 15:11:50.036  3926  3977 I jxcore-log: Total number of executed tests:  80
08-29 15:11:50.036  3926  3977 I jxcore-log: 
08-29 15:11:50.036  3926  3977 I jxcore-log: Number of passed tests:  80
08-29 15:11:50.036  3926  3977 I jxcore-log: 
08-29 15:11:50.036  3926  3977 I jxcore-log: Number of failed tests:  0
08-29 15:11:50.036  3926  3977 I jxcore-log: 
,08-29 15:11:50.037  3926  3977 I jxcore-log: Number of ignored tests:  0
08-29 15:11:50.037  3926  3977 I jxcore-log: 
08-29 15:11:50.037  3926  3977 I jxcore-log: Total duration:  22858
08-29 15:11:50.037  3926  3977 I jxcore-log: 
,08-29 15:11:50.037  3926  3977 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 15:11:50.037  3926  3977 I jxcore-log: 
,08-29 15:11:50.040  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.040  3926  3977 I jxcore-log: 
08-29 15:11:50.043  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.043  3926  3977 I jxcore-log: 
08-29 15:11:50.044  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.044  3926  3977 I jxcore-log: 
08-29 15:11:50.045  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.045  3926  3977 I jxcore-log: 
08-29 15:11:50.046  3926  3926 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 15:11:50.046  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.046  3926  3977 I jxcore-log: 
08-29 15:11:50.048  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.048  3926  3977 I jxcore-log: 
,08-29 15:11:50.051  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.051  3926  3977 I jxcore-log: 
,08-29 15:11:50.052  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.052  3926  3977 I jxcore-log: 
08-29 15:11:50.052  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.052  3926  3977 I jxcore-log: 
08-29 15:11:50.053  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:11:50.053  3926  3977 I jxcore-log: 
08-29 15:11:50.054  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:11:50.054  3926  3977 I jxcore-log: 
08-29 15:11:50.055  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:11:50.055  3926  3977 I jxcore-log: 
08-29 15:11:50.055  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.055  3926  3977 I jxcore-log: 
,08-29 15:11:50.056  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.056  3926  3977 I jxcore-log: 
08-29 15:11:50.057  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.057  3926  3977 I jxcore-log: 
,08-29 15:11:50.057  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.057  3926  3977 I jxcore-log: 
,08-29 15:11:50.058  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.058  3926  3977 I jxcore-log: 
08-29 15:11:50.059  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.059  3926  3977 I jxcore-log: 
,08-29 15:11:50.059  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.059  3926  3977 I jxcore-log: 
08-29 15:11:50.060  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.060  3926  3977 I jxcore-log: 
,08-29 15:11:50.060  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.060  3926  3977 I jxcore-log: 
08-29 15:11:50.061  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:11:50.061  3926  3977 I jxcore-log: 
,08-29 15:11:50.061  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:11:50.061  3926  3977 I jxcore-log: 
,08-29 15:11:50.062  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:11:50.062  3926  3977 I jxcore-log: 
08-29 15:11:50.063  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.063  3926  3977 I jxcore-log: 
,08-29 15:11:50.063  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.063  3926  3977 I jxcore-log: 
08-29 15:11:50.064  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.064  3926  3977 I jxcore-log: 
,08-29 15:11:50.064  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.064  3926  3977 I jxcore-log: 
08-29 15:11:50.065  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.065  3926  3977 I jxcore-log: 
,08-29 15:11:50.065  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:11:50.065  3926  3977 I jxcore-log: 
,08-29 15:11:50.358  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:11:50.361  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:11:50.361  3926  3977 I jxcore-log: 
,08-29 15:11:50.434  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:11:50.437  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:11:50.437  3926  3977 I jxcore-log: 
,08-29 15:11:50.493  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:11:50.496  3926  3977 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:11:50.496  3926  3977 I jxcore-log: 
,08-29 15:11:50.707  4365  4365 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 15:11:50.712  4365  4365 D AndroidRuntime: CheckJNI is OFF
,08-29 15:11:50.754  4365  4365 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 15:11:50.802  4365  4365 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 15:11:50.814   873  4342 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155158, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 15:11:50.824  4365  4365 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 15:11:50.833   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 15:11:50.834   873   886 I ActivityManager: Killing 3926:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 15:11:50.937   873   896 W PackageSettings: Skipping PackageSetting{51d410f com.example.hello/10273} due to missing metadata
,08-29 15:11:50.959   873  1693 I WindowState: WIN DEATH: Window{294cb67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 15:11:50.959   873  1306 D WifiService: Client connection lost with reason: 4
,08-29 15:11:50.962   873  1951 D GraphicsStats: Buffer count: 2
,08-29 15:11:51.005   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 15:11:51.005   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 15:11:51.006   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-29 15:11:51.006   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 15:11:51.006   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.006   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.006   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:11:51.006   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 15:11:50.996   873   896 I art     : Starting a blocking GC Explicit
08-29 15:11:51.006   873   886 I ActivityManager:   Force finishing activity ActivityRecord{a1c4e1c u0 com.test.thalitest/.MainActivity t2}
,08-29 15:11:51.032  3677  3714 W Finsky  : [325] PackageManagerRepository.createPackageState: Package com.test.thalitest not installed
,08-29 15:11:51.034   873  1997 W ActivityManager: Spurious death for ProcessRecord{8ca22f2 0:com.test.thalitest/u0a0}, curProc for 3926: null
,08-29 15:11:51.089   873   896 I art     : Explicit concurrent mark sweep GC freed 55913(3MB) AllocSpace objects, 9(228KB) LOS objects, 33% free, 29MB/43MB, paused 1.302ms total 82.514ms
,08-29 15:11:51.110  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:11:51.119   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 15:11:51.127  4365  4365 I art     : System.exit called, status: 0
,08-29 15:11:51.127  4365  4365 I AndroidRuntime: VM exiting with result code 0.
,08-29 15:11:51.138   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 15:11:51.162   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 15:11:51.166  4283  4283 D BluetoothMapAppObserver: onReceive
08-29 15:11:51.166  4283  4283 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 15:11:51.169  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 15:11:51.170  3798  3798 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 15:11:51.181   873  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 15:11:51.182  1507  3194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 15:11:51.183  1507  3194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 15:11:51.183  1507  3194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:11:51.184  1507  3194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:11:51.183  1885  2264 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 15:11:51.195  1945  1945 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 15:11:51.201   873  2008 I ActivityManager: Start proc 4379:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-29 15:11:51.205  1871  4376 I Keyboard.Facilitator.DecoderInitializer: run()
08-29 15:11:51.207  1871  4376 I Decoder : createOrResetDecoder
,08-29 15:11:51.249  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 15:11:51.249  3677  3677 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 15:11:51.249  3677  3677 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: writeToFile: Got exception:
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: java.io.IOException: write failed: EROFS (Read-only file system)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:193)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:600)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl.-wrap2(SharedPreferencesImpl.java)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:515)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at libcore.io.Posix.writeBytes(Native Method)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at libcore.io.Posix.write(Posix.java:271)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-29 15:11:51.252  3677  3697 W SharedPreferencesImpl: 	... 11 more
,08-29 15:11:51.253  3677  3697 E SharedPreferencesImpl: Couldn't clean up partially-written file /data/user/0/com.android.vending/shared_prefs/finsky.xml
,08-29 15:11:51.262  1507  1507 I ConfigService: onCreate
,08-29 15:11:51.266  1507  4392 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 15:11:51.266  1507  4392 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 15:11:51.267  1507  4392 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:11:51.268  1507  4392 W SQLiteOpenHelper: Opened config.db in read-only mode
08-29 15:11:51.273   873  4068 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3926 uid 10000
,08-29 15:11:51.278  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-29 15:11:51.285  1871  4376 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 15:11:51.301  4379  4379 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 15:11:51.304   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 15:11:51.320  1962  2081 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 15:11:51.320   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 15:11:51.321   873   885 E PackageManager: Failed to write settings, restoring backup
08-29 15:11:51.321   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 15:11:51.321   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 15:11:51.321   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 15:11:51.321   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 15:11:51.321   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 15:11:51.321   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.321   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.321   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 15:11:51.325   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-29 15:11:51.325   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 15:11:51.325   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.325   873   886 E DropBoxManagerService: 	... 13 more
,08-29 15:11:51.331  1871  4376 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 15:11:51.336   873  1376 I ActivityManager: Start proc 4394:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 15:11:51.337  1962  2081 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 15:11:51.337  1962  2081 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1962
08-29 15:11:51.337  1962  2081 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.337  1962  2081 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 15:11:51.340   873  1997 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 15:11:51.343   873  4401 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:11:51.343   873  4401 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.343   873  4401 E DropBoxManagerService: 	... 5 more
,08-29 15:11:51.368  1962  2081 I Process : Sending signal. PID: 1962 SIG: 9
,08-29 15:11:51.370  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 15:11:51.370  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 15:11:51.373  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 15:11:51.373  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 15:11:51.374  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 15:11:51.375  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 15:11:51.380  1871  4376 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 15:11:51.380  1871  4376 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 15:11:51.380  1871  4376 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 15:11:51.381  1871  4376 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-29 15:11:51.381  1871  4376 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 15:11:51.381  1871  4376 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 15:11:51.414  4379  4379 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 15:11:51.433  4379  4413 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 15:11:51.438   873  2109 I ActivityManager: Start proc 4414:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 15:11:51.450   873  1997 D GraphicsStats: Buffer count: 1
,08-29 15:11:51.451   873  2109 I WindowState: WIN DEATH: Window{e2e5136 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL},
,08-29 15:11:51.461   873  1951 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1962) has died
,08-29 15:11:51.462   873  1951 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-29 15:11:51.463   873  1951 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 15:11:51.471  4379  4409 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.471  4379  4409 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
,08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.471  4379  4409 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 15:11:51.478   873  1378 I ActivityManager: Start proc 4427:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 15:11:51.493   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-29 15:11:51.495  1704  4420 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-29 15:11:51.498  1704  4420 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-29 15:11:51.503  4414  4414 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 15:11:51.525  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 15:11:51.525  1507  1507 D AndroidRuntime: Shutting down VM
,08-29 15:11:51.526  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:11:51.526  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
08-29 15:11:51.526  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 15:11:51.526  1507  1507 E AndroidRuntime: 	... 8 more
,08-29 15:11:51.532  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
,08-29 15:11:51.534   873  4442 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:11:51.534   873  4442 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.534   873  4442 E DropBoxManagerService: 	... 5 more
,08-29 15:11:51.544  4379  4409 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-29 15:11:51.546  4427  4427 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.546  4427  4427 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:51.546  4427  4427 D AndroidRuntime: Shutting down VM
,08-29 15:11:51.550  4379  4413 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.550  4379  4413 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 15:11:51.553  4427  4427 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:11:51.553  4427  4427 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4427
08-29 15:11:51.553  4427  4427 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:11:51.553  4427  4427 E AndroidRuntime: 	... 10 more
,08-29 15:11:51.555   873  2010 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:11:51.555  4427  4427 I Process : Sending signal. PID: 4427 SIG: 9
,08-29 15:11:51.556   873  4443 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:11:51.556   873  4443 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.556   873  4443 E DropBoxManagerService: 	... 5 more
,08-29 15:11:51.558   873  1957 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
,08-29 15:11:51.559   873  1957 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-29 15:11:51.559   873  1957 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,08-29 15:11:51.559   873  1957 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-29 15:11:51.559   873  1957 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
08-29 15:11:51.559   873  1306 D WifiService: Client connection lost with reason: 4
,08-29 15:11:51.561  4379  4413 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 15:11:51.561  4379  4413 E AndroidRuntime: Process: android.process.acore, PID: 4379
08-29 15:11:51.561  4379  4413 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.561  4379  4413 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 15:11:51.562  4379  4409 I Process : Sending signal. PID: 4379 SIG: 9
,08-29 15:11:51.562   279   279 E lowmemorykiller: Error writing /proc/4379/oom_score_adj; errno=22
,08-29 15:11:51.566   873  4444 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:11:51.566   873  4444 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.566   873  4444 E DropBoxManagerService: 	... 5 more
,08-29 15:11:51.576  1704  1704 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 15:11:51.597   873  2109 I ActivityManager: Start proc 4446:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-29 15:11:51.599   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4427) has died
,08-29 15:11:51.600   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 15:11:51.604   373   594 E QMI_FW  : xport_send: Sendto failed for port 3328
,08-29 15:11:51.613   873   886 I ActivityManager: Start proc 4458:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 15:11:51.615  1704  4420 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-29 15:11:51.626  1704  4420 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-29 15:11:51.633   873  2110 I ActivityManager: Process android.process.acore (pid 4379) has died
,08-29 15:11:51.633   873  2110 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-29 15:11:51.634  4446  4446 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-29 15:11:51.645  4446  4446 I MultiDex: VM with version 2.1.0 has multidex support
,08-29 15:11:51.645  4446  4446 I MultiDex: install
08-29 15:11:51.645  4446  4446 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-29 15:11:51.645   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 15:11:51.657  4446  4446 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-29 15:11:51.660  4446  4446 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-29 15:11:51.662  4446  4446 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.662  4446  4446 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:11:51.662  4446  4446 D AndroidRuntime: Shutting down VM
08-29 15:11:51.663  4446  4446 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:11:51.663  4446  4446 E AndroidRuntime: Process: com.google.process.gapps, PID: 4446
08-29 15:11:51.663  4446  4446 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15,:11:51.663  4446  4446 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:11:51.663  4446  4446 E AndroidRuntime: 	... 10 more
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.664  4458  4458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:51.665  4458  4458 D AndroidRuntime: Shutting down VM
08-29 15:11:51.666   873  447,2 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:11:51.666   873  4472 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.666   873  4472 E DropBoxManagerService: 	... 5 more
08-29 15:11:51.667  4446  4446 I Process : Sending signal. PID: 4446 SIG: 9
08-29 15:11:51.673  4458  4458 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:11:51.673  4458  4458 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4458
08-29 15:11:51.673  4458  4458 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:11:51.673  4458  4458 E AndroidRuntime: 	... 10 more
08-29 15:11:51.674   873  1378 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:11:51.675  4458  4458 I Process : Sending signal. PID: 4458 SIG: 9
08-29 15:11:51.676   873  4473 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:11:51.676   873  4473 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:11:51.676   873  4473 E DropBoxManagerService: 	... 5 more

```
