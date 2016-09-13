#### Test 83627337ae40023_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 22:54:05.120   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-13 22:54:05.791  3810  3810 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 22:54:05.795  3810  3810 D AndroidRuntime: CheckJNI is OFF
09-13 22:54:05.839  3810  3810 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 22:54:05.889  3810  3810 I Radio-JNI: register_android_hardware_Radio DONE
09-13 22:54:05.911  3810  3810 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 22:54:05.915   874  2196 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 22:54:05.948  1998  2009 W SearchService: Abort, client detached.
09-13 22:54:05.953  1998  2316 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7c0d145
09-13 22:54:05.954  1998  1998 I HotwordDetector: Closing mic
09-13 22:54:05.954  1998  2324 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 22:54:05.955  3810  3810 D AndroidRuntime: Shutting down VM
09-13 22:54:05.971   874  2024 I ActivityManager: Start proc 3819:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 22:54:06.013   375  2326 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 22:54:06.016   375  2326 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 22:54:06.021   375  1284 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 22:54:06.022  1998  2323 I MicroRecognitionRnrImpl: Detection finished
09-13 22:54:06.023  1998  2320 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 22:54:06.072  3819  3819 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 22:54:06.098  3819  3819 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 22:54:06.105  3819  3819 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6894-6896)
09-13 22:54:06.106  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:54:06.128  3819  3819 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8890d19}
09-13 22:54:06.128  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:54:06.129  3819  3819 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 22:54:06.135  3819  3819 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 22:54:06.136  3819  3819 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 22:54:06.159  3819  3819 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 22:54:06.170  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 22:54:06.170  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 22:54:06.170  3819  3819 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 22:54:06.170  3819  3819 I Adreno  : Build Date                       : 10/20/15
09-13 22:54:06.170  3819  3819 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 22:54:06.170  3819  3819 I Adreno  : Local Branch                     : M14
09-13 22:54:06.170  3819  3819 I Adreno  : Remote Branch                    : 
09-13 22:54:06.170  3819  3819 I Adreno  : Remote Branch                    : 
09-13 22:54:06.170  3819  3819 I Adreno  : Reconstruct Branch               : 
,09-13 22:54:06.244   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d999cf:true
,09-13 22:54:06.294  3819  3819 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 22:54:06.309  3819  3819 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 22:54:06.402  3819  3860 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 22:54:06.411  3819  3845 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 22:54:06.438  3819  3860 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 22:54:06.466  1872  1872 I Keyboard.Facilitator: onFinishInput()
,09-13 22:54:06.515   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +557ms
,09-13 22:54:06.585  3819  3819 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3819
,09-13 22:54:06.703  3819  3819 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 22:54:06.802   874  2192 I ActivityManager: Killing 3258:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 22:54:06.834   874  2192 I ActivityManager: Killing 3147:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-13 22:54:06.916  3819  3863 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699022544
,09-13 22:54:06.928  3819  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 22:54:06.928  3819  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 22:54:06.928  3819  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 22:54:06.928  3819  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 22:54:06.928  3819  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 22:54:06.928  3819  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fbcbe4 added. We now have 1 listener(s)
,09-13 22:54:06.931  3819  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 22:54:06.932  3819  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 22:54:06.933  3819  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 22:54:06.933  3819  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 22:54:06.939  3819  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51ac013 added. We now have 1 listener(s)
09-13 22:54:06.940  3819  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 22:54:06.945   874  1313 D WifiService: New client listening to asynchronous messages
,09-13 22:54:06.949  3819  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 22:54:06.949  3819  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 22:54:06.949  3819  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 22:54:06.949  3819  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 22:54:06.949  3819  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 22:54:06.951  3819  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:06.951  3819  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 22:54:06.964  3819  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:06.964  3819  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:54:06.964  3819  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 22:54:06.965  3819  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 22:54:06.967  3819  3863 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 22:54:06.967  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:06.971  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:07.114  3819  3819 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 22:54:07.863  3819  3871 W jxcore-log: Initializing JXcore engine
,09-13 22:54:07.863  3819  3871 W jxcore-log: JXcore engine is ready
,09-13 22:54:07.901  3871  3871 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8794 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 22:54:07.901  3871  3871 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11644]" dev="sockfs" ino=11644 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 22:54:07.901  3871  3871 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 22:54:07.901  3871  3871 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26847]" dev="sockfs" ino=26847 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 22:54:07.912  3819  3871 W jxcore-log: Starting JXcore engine
,09-13 22:54:08.000  3819  3871 W jxcore-log: Platform android
09-13 22:54:08.000  3819  3871 W jxcore-log: 
,09-13 22:54:08.000  3819  3871 W jxcore-log: Process ARCH arm
09-13 22:54:08.000  3819  3871 W jxcore-log: 
,09-13 22:54:08.148   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 22:54:08.289  3819  3871 I jxcore-log: JXcore Cordova bridge is ready!
09-13 22:54:08.289  3819  3871 I jxcore-log: 
09-13 22:54:08.289  3819  3871 W jxcore-log: JXcore engine is started
,09-13 22:54:08.300  3819  3863 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 22:54:08.307  3819  3819 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 22:54:11.498   874  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 22:54:11.872   874  1887 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 22:54:17.724  3046  3881 V KeepSync: Connecting to GoogleApiClient
,09-13 22:54:17.725   874  2191 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 22:54:17.792  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 22:54:17.798  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 22:54:17.857  1579  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 22:54:17.858  1579  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 22:54:17.858  1579  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 22:54:17.858  1579  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:17.911  1759  3882 V BaseAuthAsyncOperation: access token request failed
,09-13 22:54:17.914  3046  3881 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 22:54:17.995  1579  2109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 22:54:17.995  1579  2109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 22:54:17.995  1579  2109 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 22:54:17.995  1579  2109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:18.000  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 22:54:18.000  3819  3871 I jxcore-log: 
,09-13 22:54:18.002  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 22:54:18.002  3819  3871 I jxcore-log: 
,09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:18.008  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:18.011  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 22:54:18.012  3046  3881 E KeepSync: IOException
09-13 22:54:18.012  3046  3881 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
,09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 22:54:18.012  3046  3881 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 22:54:18.012  3046  3881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 22:54:18.012  3046  3881 E KeepSync: 	... 10 more
09-13 22:54:18.012  3046  3881 W KeepSync: Sync result 2
,09-13 22:54:18.013  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 22:54:18.013  3819  3871 I jxcore-log: 
09-13 22:54:18.015  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 22:54:18.015  3819  3871 I jxcore-log: 
,09-13 22:54:18.027   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 128417, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 22:54:18.517  3819  3871 I jxcore-log: Unit Test app is loaded
09-13 22:54:18.517  3819  3871 I jxcore-log: 
,09-13 22:54:18.524  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:18.524  3819  3871 I jxcore-log: 
,09-13 22:54:18.529  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-13 22:54:18.530  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40ee969 added. We now have 2 listener(s)
09-13 22:54:18.531  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:18.531  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:54:18.531  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 22:54:18.531  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:54:18.531  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ad8fee added. We now have 2 listener(s)
09-13 22:54:18.531  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:54:18.532  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 22:54:18.533  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:18.540  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:18.543  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:18.543  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:54:18.544  3819  3871 D ExecuteNativeTests: Running unit tests
,09-13 22:54:18.555  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:18.558  3819  3871 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 22:54:18.559   874  2191 D WifiService: setWifiEnabled: true pid=3819, uid=10000
09-13 22:54:18.559   874  2191 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:18.567  3819  3871 I System.out: Running UT
,09-13 22:54:18.569  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:18.569  3819  3819 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 22:54:28.661  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 22:54:28.661  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c added. We now have 3 listener(s)
,09-13 22:54:28.664  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 22:54:28.664  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:54:28.664  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 22:54:28.664  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:54:28.664  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 added. We now have 3 listener(s)
09-13 22:54:28.664  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 22:54:28.665  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 22:54:28.673  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:28.686  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:28.692  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 22:54:28.693  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 22:54:28.699  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:28.704  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:28.706  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 22:54:28.709  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 22:54:28.709  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 22:54:28.709  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 22:54:28.710  3819  3871 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 22:54:28.711  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 22:54:28.711  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 22:54:28.712  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 22:54:28.712  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:54:28.712  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 22:54:28.713  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:28.713  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:28.713  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:54:28.713  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 22:54:28.714  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c removed from the list
09-13 22:54:28.714  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:28.714  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 removed from the list
,09-13 22:54:28.714  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:28.714  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:28.725  3819  3871 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 22:54:28.727  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:28.728  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:28.728  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:28.729  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:28.729  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:28.731  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
,09-13 22:54:28.731  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:28.731  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:28.732  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 22:54:28.750  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 22:54:28.751  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 22:54:28.752  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 22:54:28.752  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:28.752  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:28.752  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:28.753  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:28.753  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:28.753  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:28.753  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:28.753  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:28.753  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:28.754  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 22:54:28.756  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:28.762  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:54:28.765  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:28.765  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:54:28.766  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 22:54:28.766  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 22:54:28.766  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:28.766  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 22:54:28.767  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 22:54:28.767  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:28.770  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 22:54:28.772  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:28.774  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:54:28.774  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 22:54:28.775  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 22:54:28.775  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:28.775  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 22:54:28.775  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 22:54:28.776  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:28.776  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:54:28.782  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 22:54:28.782  3819  3887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:28.782  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 22:54:28.786  3819  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 22:54:28.790  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 22:54:28.792  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 22:54:28.792  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:54:28.797  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 22:54:28.797  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:28.798  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-13 22:54:28.799  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:28.799  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:28.800  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 22:54:28.800  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:28.808  2696  2709 D BtGatt.GattService: registerClient() - UUID=4b7d1994-404d-4245-b232-f24284821d4c
09-13 22:54:28.809  2696  2716 D BtGatt.GattService: onClientRegistered() - UUID=4b7d1994-404d-4245-b232-f24284821d4c, clientIf=5
09-13 22:54:28.810  3819  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 22:54:28.812  2696  2719 D BtGatt.AdvertiseManager: message : 0
09-13 22:54:28.817  2696  2719 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 22:54:28.839  2696  2716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 22:54:28.850  2696  2716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 22:54:28.852  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 22:54:28.853  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 22:54:28.857  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:28.860  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 22:54:28.861  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 22:54:28.861  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 22:54:28.861  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 22:54:28.861  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 22:54:28.861  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 22:54:28.862  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 22:54:28.866  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:28.867  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:29.369  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 22:54:29.369  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 22:54:29.370  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 22:54:29.370  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 22:54:29.371  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 22:54:29.371  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 22:54:29.372  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 22:54:29.372  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 22:54:29.372  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 22:54:29.373  3819  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 22:54:29.373  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 22:54:29.374  3819  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:54:29.374  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 22:54:29.374  3819  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:54:29.374  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 22:54:29.374  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:54:29.375  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:29.375  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:54:29.375  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:54:29.377  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:54:29.380  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:29.381  3819  3871 D BluetoothLeScanner: could not find callback wrapper
09-13 22:54:29.381  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 22:54:29.381  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 22:54:29.385  2696  2719 D BtGatt.AdvertiseManager: message : 1
09-13 22:54:29.386  2696  2719 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 22:54:29.407  2696  2716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 22:54:29.407  2696  2716 D BtGatt.GattService: Client app is not null!
09-13 22:54:29.410  2696  2902 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:29.411  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 22:54:29.412  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 22:54:29.412  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 22:54:29.413  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 22:54:29.414  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 22:54:29.417  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:29.419  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 22:54:29.422  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:54:29.425  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 22:54:29.430  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 22:54:29.430  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 22:54:29.431  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 22:54:29.431  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:29.432  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 22:54:29.432  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:29.436  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 22:54:29.436  3819  3871 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-13 22:54:29.436  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 22:54:29.436  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 22:54:29.437  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:29.437  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 22:54:29.437  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 22:54:29.437  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:29.439  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 22:54:29.439  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:54:29.439  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 22:54:29.439  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 22:54:29.439  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 22:54:29.439  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:29.439  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:54:29.439  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 22:54:29.441  3819  3890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:29.445  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 22:54:29.445  3819  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 22:54:29.445  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 22:54:29.454  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 22:54:29.455  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 22:54:29.456  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:54:29.458  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 22:54:29.459  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:29.459  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,09-13 22:54:29.459  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:29.459  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:29.459  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 22:54:29.460  3819  3871 D BluetoothAdapter: STATE_ON
,09-13 22:54:29.464  2696  2891 D BtGatt.GattService: registerClient() - UUID=ce29d33e-ead4-4f85-a49e-0ed36d108d3a
,09-13 22:54:29.464  2696  2716 D BtGatt.GattService: onClientRegistered() - UUID=ce29d33e-ead4-4f85-a49e-0ed36d108d3a, clientIf=5
09-13 22:54:29.465  3819  3861 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 22:54:29.466  2696  2719 D BtGatt.AdvertiseManager: message : 0
,09-13 22:54:29.469  2696  2719 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 22:54:29.488  2696  2716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 22:54:29.501  2696  2716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 22:54:29.503  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 22:54:29.504  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 22:54:29.510  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:29.513  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 22:54:29.514  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 22:54:29.514  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 22:54:29.514  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 22:54:29.515  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 22:54:29.516  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 22:54:29.516  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 22:54:29.525  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:29.526  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:30.019  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.019  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 22:54:30.020  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 22:54:30.020  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 22:54:30.021  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 22:54:30.021  3819  3890 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 22:54:30.021  3819  3890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 22:54:30.021  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 22:54:30.021  3819  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 22:54:30.021  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:30.022  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:30.022  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 22:54:30.023  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:30.023  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 22:54:30.023  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:54:30.023  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:54:30.024  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:54:30.026  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:30.026  3819  3871 D BluetoothLeScanner: could not find callback wrapper
09-13 22:54:30.027  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 22:54:30.027  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 22:54:30.030  2696  2719 D BtGatt.AdvertiseManager: message : 1
09-13 22:54:30.031  2696  2719 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 22:54:30.054  2696  2716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 22:54:30.055  2696  2716 D BtGatt.GattService: Client app is not null!
,09-13 22:54:30.056  2696  2892 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:30.057  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 22:54:30.058  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 22:54:30.058  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 22:54:30.058  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 22:54:30.059  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 22:54:30.061  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:30.062  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 22:54:30.062  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:54:30.063  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 22:54:30.066  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:30.066  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:30.066  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.066  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 22:54:30.066  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.066  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 22:54:30.066  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:30.070  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 22:54:30.074  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:30.083  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:30.086  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:30.086  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:54:30.087  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 22:54:30.087  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 22:54:30.087  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:30.087  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 22:54:30.087  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 22:54:30.087  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:30.088  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 22:54:30.089  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 22:54:30.089  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
,09-13 22:54:30.089  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 22:54:30.089  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 22:54:30.090  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:30.090  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-13 22:54:30.091  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:30.093  3819  3892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 22:54:30.094  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 22:54:30.094  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 22:54:30.095  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:30.096  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 22:54:30.100  3819  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 22:54:30.102  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 22:54:30.103  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 22:54:30.104  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:54:30.107  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 22:54:30.107  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:30.107  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-13 22:54:30.107  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:30.108  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:30.108  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 22:54:30.108  3819  3871 D BluetoothAdapter: STATE_ON
,09-13 22:54:30.112  2696  2707 D BtGatt.GattService: registerClient() - UUID=a32abcfa-e503-417b-ab24-f24b6eb44a5a,
,09-13 22:54:30.113  2696  2716 D BtGatt.GattService: onClientRegistered() - UUID=a32abcfa-e503-417b-ab24-f24b6eb44a5a, clientIf=5
,09-13 22:54:30.113  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 22:54:30.122  2696  2719 D BtGatt.AdvertiseManager: message : 0
,09-13 22:54:30.126  2696  2719 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 22:54:30.142  2696  2716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 22:54:30.152  2696  2716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 22:54:30.153  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 22:54:30.153  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 22:54:30.158  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:30.161  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 22:54:30.161  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:30.162  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 22:54:30.162  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 22:54:30.162  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 22:54:30.163  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 22:54:30.163  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 22:54:30.171  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:30.172  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:30.666  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 22:54:30.666  3819  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 22:54:30.666  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 22:54:30.667  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 22:54:30.667  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 22:54:30.667  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 22:54:30.668  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 22:54:30.668  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 22:54:30.668  3819  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 22:54:30.669  3819  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:54:30.669  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 22:54:30.669  3819  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:54:30.669  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 22:54:30.669  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:30.670  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:54:30.670  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:54:30.670  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 22:54:30.670  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:54:30.673  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:30.673  3819  3871 D BluetoothLeScanner: could not find callback wrapper
09-13 22:54:30.673  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 22:54:30.674  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 22:54:30.676  2696  2719 D BtGatt.AdvertiseManager: message : 1
09-13 22:54:30.677  2696  2719 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 22:54:30.694  2696  2716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 22:54:30.694  2696  2716 D BtGatt.GattService: Client app is not null!
,09-13 22:54:30.695  2696  2709 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:30.696  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 22:54:30.696  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 22:54:30.696  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 22:54:30.696  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 22:54:30.696  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 22:54:30.699  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 22:54:30.699  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 22:54:30.699  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:54:30.700  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 22:54:30.704  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 22:54:30.704  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 22:54:30.704  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:54:30.704  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:30.704  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:30.704  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 22:54:30.705  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:30.710  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:30.711  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.711  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 22:54:30.711  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:30.712  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.712  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.712  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:30.713  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:30.715  3819  3871 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 22:54:30.717  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:30.718  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.718  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.718  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:30.719  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.719  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
,09-13 22:54:30.719  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.719  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.720  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:30.722  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 22:54:30.723  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.723  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:30.723  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.723  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:30.724  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:30.724  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.724  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.724  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:30.725  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:30.727  3819  3871 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 22:54:30.727  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.727  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:30.728  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.728  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:30.728  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.729  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.729  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:30.729  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.729  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.730  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 22:54:30.730  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.730  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.730  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.730  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:30.730  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.730  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.730  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.731  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.731  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:30.731  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 22:54:30.731  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:54:30.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:54:30.732  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 22:54:30.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:54:30.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:54:30.732  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 22:54:30.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:54:30.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:54:30.732  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:30.732  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.732  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.733  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:30.733  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:30.733  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.733  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.733  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.733  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.734  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:54:30.734  3819  3871 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 22:54:30.734  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 22:54:30.738  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 22:54:30.738  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 22:54:30.738  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 22:54:30.738  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 22:54:30.738  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 22:54:30.738  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 22:54:30.738  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 22:54:30.739  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 22:54:30.740  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 22:54:30.741  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 22:54:30.741  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 22:54:30.741  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 22:54:30.741  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 22:54:30.741  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 22:54:30.741  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 22:54:30.742  3819  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 22:54:30.742  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 22:54:30.742  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:54:30.742  3819  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 22:54:30.742  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 22:54:30.742  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 22:54:30.742  3819  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 22:54:30.742  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 22:54:30.748  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 22:54:30.749  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 22:54:30.749  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 22:54:30.752  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 22:54:30.752  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 22:54:30.752  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-13 22:54:30.752  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:54:30.753  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 22:54:30.753  3819  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 423)
09-13 22:54:30.754  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.754  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:30.754  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.755  3819  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:30.755  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-13 22:54:30.757  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:30.758  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.758  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
,09-13 22:54:30.758  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.758  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.758  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.759  3819  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 423
09-13 22:54:30.759  3819  3871 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-13 22:54:30.760  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.760  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.760  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.760  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:30.760  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.761  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
,09-13 22:54:30.761  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:30.761  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.761  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.761  3819  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 423)
,09-13 22:54:30.761  2696  2887 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: -1
09-13 22:54:30.761  3819  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 423)
09-13 22:54:30.761  3819  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 423)
,09-13 22:54:30.762  3819  3871 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-13 22:54:30.762  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:30.762  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.762  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.763  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:30.763  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:30.764  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.764  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:30.765  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.765  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.767  3819  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-13 22:54:30.767  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-13 22:54:30.767  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 22:54:30.767  3819  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-13 22:54:30.767  3819  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 22:54:30.767  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-13 22:54:30.768  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 22:54:30.768  3819  3871 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 22:54:30.768  3819  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-13 22:54:30.768  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-13 22:54:30.768  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 22:54:30.768  3819  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 22:54:30.768  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:30.768  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.769  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:30.769  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:30.769  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:30.769  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:30.769  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:30.769  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:30.769  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:30.770  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 22:54:30.772  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:30.778  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:54:30.780  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:30.780  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 22:54:30.780  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 22:54:30.780  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-13 22:54:30.781  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:30.781  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 22:54:30.781  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 22:54:30.781  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:30.782  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 22:54:30.782  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:54:30.783  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 22:54:30.783  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 22:54:30.783  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 22:54:30.783  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:30.783  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:54:30.784  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:30.787  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 22:54:30.787  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 22:54:30.790  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:30.790  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 22:54:30.795  3819  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 22:54:30.797  3819  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 22:54:30.797  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 22:54:30.798  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 22:54:30.799  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:54:30.801  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 22:54:30.801  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:30.801  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-13 22:54:30.801  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:30.802  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:30.802  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 22:54:30.802  3819  3871 D BluetoothAdapter: STATE_ON
,09-13 22:54:30.807  2696  2891 D BtGatt.GattService: registerClient() - UUID=b2ad44b7-56ff-462e-99ef-f6c1060cf890
,09-13 22:54:30.807  2696  2716 D BtGatt.GattService: onClientRegistered() - UUID=b2ad44b7-56ff-462e-99ef-f6c1060cf890, clientIf=5
09-13 22:54:30.807  3819  3861 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 22:54:30.809  2696  2719 D BtGatt.AdvertiseManager: message : 0
,09-13 22:54:30.812  2696  2719 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 22:54:30.835  2696  2716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 22:54:30.846  2696  2716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-13 22:54:30.847  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 22:54:30.848  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 22:54:30.853  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:30.858  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
09-13 22:54:30.858  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:30.859  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 22:54:30.859  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 22:54:30.860  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 22:54:30.860  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 22:54:30.860  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 22:54:30.869  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:30.870  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:31.364  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:31.364  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 22:54:31.364  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 22:54:31.365  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 22:54:31.366  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 22:54:31.366  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 22:54:31.366  3819  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 22:54:31.367  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:54:31.368  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:31.368  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:31.368  3819  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:54:31.368  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 22:54:31.369  3819  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:54:31.369  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:54:31.369  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 22:54:31.369  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 22:54:31.370  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:54:31.372  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 22:54:31.374  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:31.375  3819  3871 D BluetoothLeScanner: could not find callback wrapper
09-13 22:54:31.375  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 22:54:31.375  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 22:54:31.379  2696  2719 D BtGatt.AdvertiseManager: message : 1
09-13 22:54:31.380  2696  2719 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 22:54:31.398  2696  2716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 22:54:31.398  2696  2716 D BtGatt.GattService: Client app is not null!
09-13 22:54:31.399  2696  2707 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:31.399  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 22:54:31.400  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 22:54:31.400  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 22:54:31.400  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
09-13 22:54:31.400  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 22:54:31.401  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:31.402  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 22:54:31.402  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:54:31.404  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 22:54:31.406  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
,09-13 22:54:31.406  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:31.406  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.407  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:31.407  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:31.407  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:31.412  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:31.412  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:31.412  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.412  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:31.412  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:31.412  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:31.413  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:31.413  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.413  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:31.416  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 22:54:31.416  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:31.417  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 22:54:31.418  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 22:54:31.418  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 22:54:31.418  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 22:54:31.418  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 22:54:31.418  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 22:54:31.419  3819  3900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 22:54:31.420  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:31.420  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 22:54:31.420  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 22:54:31.420  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 22:54:31.420  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:31.420  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 22:54:31.420  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 22:54:31.421  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:31.421  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:31.421  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:31.421  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:54:31.421  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:54:31.421  3819  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 22:54:31.421  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.421  3819  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:54:31.421  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.421  3819  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:54:31.423  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 22:54:31.423  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:31.423  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:31.424  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:54:31.424  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:31.424  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
,09-13 22:54:31.424  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:31.424  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.424  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.427  3819  3871 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 22:54:31.428  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 22:54:31.428  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 22:54:31.428  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:54:31.428  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:54:31.429  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:31.429  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.429  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.429  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:31.429  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:31.430  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:31.430  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:31.430  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.430  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.439  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:31.439  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.439  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:31.440  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
09-13 22:54:31.440  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:31.440  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:31.440  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:31.441  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.441  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:31.444  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:31.444  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.444  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.444  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277b34c not in the list
,09-13 22:54:31.445  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:31.445  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e60af95 not in the list
09-13 22:54:31.445  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:31.445  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:31.446  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:31.448  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-13 22:54:31.449  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 22:54:31.451  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-13 22:54:31.451  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 22:54:31.451  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-13 22:54:31.452  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 22:54:31.457  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 22:54:31.457  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 22:54:31.459  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 22:54:31.459  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 22:54:31.460  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 22:54:31.460  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 22:54:31.460  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 22:54:31.461  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-13 22:54:31.462  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-13 22:54:31.463  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 22:54:31.464  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-13 22:54:31.465  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 22:54:31.465  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 22:54:31.465  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 22:54:31.468  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 22:54:31.468  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@620405a added. We now have 3 listener(s)
,09-13 22:54:31.470  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 22:54:31.471  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:54:31.471  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 22:54:31.471  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:54:31.471  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef3028b added. We now have 3 listener(s)
,09-13 22:54:31.471  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:54:31.472  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 22:54:31.475  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:31.479  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:31.481  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 22:54:31.481  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 22:54:31.483  3819  3871 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 22:54:31.483   874  2194 D WifiService: setWifiEnabled: true pid=3819, uid=10000
09-13 22:54:31.484   874  2194 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:54:31.484  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:31.487  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:31.491   874  2191 D WifiService: setWifiEnabled: false pid=3819, uid=10000
09-13 22:54:31.491   874  2191 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:31.511  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 22:54:31.517   874  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 22:54:31.517   874  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 22:54:31.517   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 22:54:31.517   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 22:54:31.530   874  1893 D DhcpClient: Clearing IP address
,09-13 22:54:31.530   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 22:54:31.535   371   872 D CommandListener: Setting iface cfg
,09-13 22:54:31.539  1579  2147 V NativeCrypto: Read error: ssl=0x9b7ffc00: I/O error during system call, Connection timed out
,09-13 22:54:31.542  1579  2147 V NativeCrypto: SSL shutdown failed: ssl=0x9b7ffc00: I/O error during system call, Broken pipe
,09-13 22:54:31.544   874  1904 D DhcpClient: Receive thread stopped
,09-13 22:54:31.547   874  1410 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-13 22:54:31.548   874  1885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-13 22:54:31.548   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 22:54:31.549   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-13 22:54:31.551   874  1885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-13 22:54:31.555   874  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-13 22:54:31.557   457   457 E Parcel  : Reading a NULL string not supported here.
09-13 22:54:31.558   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,09-13 22:54:31.564   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 22:54:31.572   874  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 22:54:31.572   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:31.581  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:31.581  2148  2350 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:54:31.588  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:31.591   874  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:31.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:31.594  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:31.597  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:31.598   874   885 I ActivityManager: Start proc 3905:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-13 22:54:31.599  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:31.616   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 22:54:31.631  3905  3905 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 22:54:31.639   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 22:54:31.639   874  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 22:54:31.640   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:54:31.641   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 22:54:31.644  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:31.644  3433  3433 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dad784d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-13 22:54:31.645  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:31.647  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:31.647  1998  1998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-13 22:54:31.672  3905  3905 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 22:54:31.684  1759  1759 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 22:54:31.688  1759  1759 D SystemUpdateService: onCreate
,09-13 22:54:31.691  1759  1759 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 22:54:31.693  1759  3935 I SystemUpdateService: active receiver: enabled
,09-13 22:54:31.698  1759  1759 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 22:54:31.701  1759  2439 I iu.UploadsManager: num queued entries: 0
,09-13 22:54:31.701  1759  2439 I iu.UploadsManager: num updated entries: 0
,09-13 22:54:31.704  1759  3935 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 22:54:31.707   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 22:54:31.708   874  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 22:54:31.708   874  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 22:54:31.709  1759  1759 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 22:54:31.710  1759  1759 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 22:54:31.712  1759  3935 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 22:54:31.712  1759  3935 I SystemUpdateService: now status is 0 (complete)
,09-13 22:54:31.719  1759  3935 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 22:54:31.719  1759  3935 I SystemUpdateService: file has been verified
09-13 22:54:31.719  1759  3935 I SystemUpdateService: OTA package size = 12249756
09-13 22:54:31.720  1759  2439 I iu.SyncManager: NEXT; no task
,09-13 22:54:31.722   874   884 I ActivityManager: Start proc 3938:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 22:54:31.726  1759  3935 I SystemUpdateService: showing system update notification
,09-13 22:54:31.736  1759  1759 D SystemUpdateService: onDestroy
,09-13 22:54:31.737   874   885 I ActivityManager: Killing 2988:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 22:54:31.784  3938  3938 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 22:54:31.786  3938  3938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:54:31.803  3938  3938 D SprintDMHelper: simOperator: 
,09-13 22:54:31.803  3938  3938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 22:54:31.824   874  1410 I ActivityManager: Start proc 3950:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 22:54:31.827   874  1410 I ActivityManager: Killing 3433:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 22:54:31.924  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 22:54:31.962   874  1934 I ActivityManager: Start proc 3965:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 22:54:31.968  3095  3964 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 22:54:31.971   874   885 I ActivityManager: Killing 3503:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 22:54:32.000  3819  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.007   874  2191 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,09-13 22:54:32.007   874  2191 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:32.013   874  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:32.019  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:32.020  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:32.023  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:32.023   874  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-13 22:54:32.024   874  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 22:54:32.024   874  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 22:54:32.025   874  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory),
09-13 22:54:32.025   874  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 22:54:32.026   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 22:54:32.026   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-13 22:54:32.027  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:32.030  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:32.032  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:32.033   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 22:54:32.034   371   872 D CommandListener: Setting iface cfg
09-13 22:54:32.034   874  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-13 22:54:32.034   874  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 22:54:32.036   874  1311 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 22:54:32.041   874  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 22:54:32.042  3965  3965 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
09-13 22:54:32.042   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:32.060   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:32.094  3965  3965 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 22:54:32.094  3965  3965 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 22:54:32.094  3965  3965 I GAv4    :   adb logcat -s GAv4
,09-13 22:54:32.113  3965  3965 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 22:54:32.121  3965  3965 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 22:54:32.169  3965  3984 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 22:54:32.259  3965  3965 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 22:54:32.302  3965  3965 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 22:54:32.312  3965  3965 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3098-3103)
,09-13 22:54:32.312  3965  3965 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 22:54:32.321  3965  3965 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b1a0ebd}
09-13 22:54:32.321  3965  3965 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:54:32.322  3965  3965 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 22:54:32.331  3965  3965 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 22:54:32.334  3965  3965 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 22:54:32.355  3965  3965 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 22:54:32.377  3965  3965 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 22:54:32.377  3965  3965 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 22:54:32.377  3965  3965 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 22:54:32.377  3965  3965 I Adreno  : Build Date                       : 10/20/15
09-13 22:54:32.377  3965  3965 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 22:54:32.377  3965  3965 I Adreno  : Local Branch                     : M14
09-13 22:54:32.377  3965  3965 I Adreno  : Remote Branch                    : 
09-13 22:54:32.377  3965  3965 I Adreno  : Remote Branch                    : 
09-13 22:54:32.377  3965  3965 I Adreno  : Reconstruct Branch               : 
,09-13 22:54:32.457  3965  3965 I NSApplication: Starting up...
,09-13 22:54:32.469  3965  4013 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 22:54:32.503   874  1979 I ActivityManager: Start proc 4018:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-13 22:54:32.505   874  1979 I ActivityManager: Killing 1691:android.process.acore/u0a5 (adj 15): empty #17
,09-13 22:54:32.511  3819  3977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.587  2696  2712 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 22:54:32.587  2696  2712 D BluetoothAdapterProperties: Setting state to 13
09-13 22:54:32.587  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 22:54:32.588  2696  2712 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 22:54:32.589  2696  2712 I BluetoothAdapterState: Entering PendingCommandState
,09-13 22:54:32.592  2696  2716 D BluetoothAdapterProperties: Scan Mode:20
,09-13 22:54:32.592  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 22:54:32.593  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:32.593  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:32.594  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:54:32.595  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:32.599  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:32.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:32.600  2696  2696 D HeadsetService: Received stop request...Stopping profile...
,09-13 22:54:32.601  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:54:32.601  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:32.607  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:32.607  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:32.610  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:54:32.610  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:32.612   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 22:54:32.612   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 22:54:32.612  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:32.613  1354  1374 D BluetoothHeadset: Proxy object disconnected
,09-13 22:54:32.613  1935  2124 D BluetoothHeadset: Proxy object disconnected
09-13 22:54:32.614  1354  1354 D HeadsetProfile: Bluetooth service disconnected
09-13 22:54:32.614   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 22:54:32.615  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:32.616  2696  2696 D A2dpService: Received stop request...Stopping profile...
09-13 22:54:32.616  2696  2894 D A2dpStateMachine: Exit Disconnected: -1
,09-13 22:54:32.621  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.622   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 22:54:32.623  2696  2696 D BluetoothMapService: onReceive
09-13 22:54:32.623  2696  2696 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:54:32.623  2696  2696 D BluetoothMapService: STATE_TURNING_OFF
09-13 22:54:32.623  2696  2696 D HidService: Received stop request...Stopping profile...
09-13 22:54:32.623  2696  2696 D HidService: Stopping Bluetooth HidService
09-13 22:54:32.624  2696  2696 D HealthService: Received stop request...Stopping profile...
,09-13 22:54:32.629  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:32.629  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:32.629  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:32.629  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:32.629  2696  2696 D PanService: Received stop request...Stopping profile...
,09-13 22:54:32.630  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-13 22:54:32.630  1354  1354 D BluetoothInputDevice: Proxy object disconnected
,09-13 22:54:32.630  1354  1354 D HidProfile: Bluetooth service disconnected
09-13 22:54:32.631  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 22:54:32.631  1354  1354 D PanProfile: Bluetooth service disconnected
09-13 22:54:32.631  2696  2696 D BluetoothMapService: Received stop request...Stopping profile...
09-13 22:54:32.631  2696  2696 D BluetoothMapService: stop()
,09-13 22:54:32.632  2696  2696 D BluetoothMapAppObserver: deinitObservers()
09-13 22:54:32.632  2696  2696 D BluetoothMapAppObserver: removeReceiver()
09-13 22:54:32.634  1354  1354 D BluetoothMap: Proxy object disconnected
09-13 22:54:32.635  1354  1354 D MapProfile: Bluetooth service disconnected
,09-13 22:54:32.635  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 22:54:32.635  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:54:32.635  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 22:54:32.635  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:32.635  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:32.635  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:32.635  2696  2865 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:32.636  2696  2865 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:32.636  2696  2865 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:32.635  2696  2716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 22:54:32.637  2696  2716 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-13 22:54:32.639  2696  2865 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 22:54:32.639  2696  2865 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:32.639  2696  2865 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:54:32.639  2696  2865 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:54:32.639  2696  2865 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:54:32.639  2696  2865 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 22:54:32.639  2696  2716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 22:54:32.640  2696  2696 I BtOppRfcommListener: stopping Accept Thread
09-13 22:54:32.640  2696  3485 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:54:32.640  2696  3485 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 22:54:32.641  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:32.642  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:32.642  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:32.642  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:32.642  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 22:54:32.643  2696  2716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 22:54:32.643  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-13 22:54:32.643  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:32.643  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:32.643  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:32.643  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:32.644  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 22:54:32.644  2696  2716 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 22:54:32.644  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 22:54:32.644  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-13 22:54:32.644  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:32.644  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:32.644  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:32.645  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 22:54:32.645  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 22:54:32.646  2696  2696 D BluetoothMapService: MAP Service closeService in
,09-13 22:54:32.647  2696  2696 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 22:54:32.647  2696  2696 D ObexServerSockets0: shutdown(block = true)
,09-13 22:54:32.647  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 22:54:32.648  2696  2904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 22:54:32.648  2696  2887 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 22:54:32.648  2696  2903 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 22:54:32.648  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 22:54:32.648  4018  4018 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 22:54:32.649  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:32.649  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:32.649  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:32.650  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:32.650  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 22:54:32.650  2696  2712 D BluetoothAdapterProperties: Setting state to 15
09-13 22:54:32.650  2696  2696 D BluetoothMapService: cleanup()
09-13 22:54:32.650  2696  2696 D BluetoothMapService: MAP Service closeService in
,09-13 22:54:32.650  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 22:54:32.651  2696  2712 I BluetoothAdapterState: Entering BleOnState
,09-13 22:54:32.651   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:54:32.651  1354  2016 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 22:54:32.651   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 22:54:32.652  1354  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 22:54:32.652  1354  1367 D BluetoothPan: onBluetoothStateChange on: false
09-13 22:54:32.653   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-13 22:54:32.653  1354  2016 D BluetoothMap: onBluetoothStateChange: up=false
09-13 22:54:32.653   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false,
,09-13 22:54:32.654  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 22:54:32.654  1354  1367 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 22:54:32.655  1935  1951 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 22:54:32.656  2696  2712 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 22:54:32.656  2696  2712 D BluetoothAdapterProperties: Setting state to 16
,09-13 22:54:32.656  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 22:54:32.657  2696  2712 D BluetoothAdapterProperties: onBleDisable
09-13 22:54:32.657  2696  2712 I BluetoothAdapterState: Entering PendingCommandState
09-13 22:54:32.657  2696  2713 D bt_stack_manager: event_shut_down_stack is bringing down the stack.,
,09-13 22:54:32.658  2696  2865 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-13 22:54:32.658  2696  2865 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:32.659  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.659  2696  2716 D BluetoothAdapterProperties: Scan Mode:20
09-13 22:54:32.660  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:32.661  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.662  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:32.664  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.665  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:32.867  2696  2716 I bt_hci  : shut_down
,09-13 22:54:32.868  2696  2722 D bt_hwcfg: hw_epilog_process
,09-13 22:54:32.872  2696  2722 I bt_vendor: low_power_mode_cb
,09-13 22:54:32.875   874  1934 I ActivityManager: Killing 3676:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 22:54:32.892  2696  2722 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 22:54:32.892  2696  2722 I bt_vendor: epilog_cb
,09-13 22:54:32.892  2696  2722 I bt_hci  : epilog_finished_callback
,09-13 22:54:32.929  2696  2716 I bt_hci_h4: hal_close,
,09-13 22:54:32.929  2696  2716 I bt_userial_vendor: device fd = 51 close,
,09-13 22:54:32.992   874  2190 I ActivityManager: Start proc 4036:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-13 22:54:33.041  2696  2713 D bt_stack_manager: event_shut_down_stack finished.
,09-13 22:54:33.042  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 22:54:33.043  2696  2712 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 22:54:33.044  2696  2696 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 22:54:33.045  2696  2696 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 22:54:33.045  2696  2696 D BtGatt.GattService: stop()
,09-13 22:54:33.045  2696  2696 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 22:54:33.049  2696  2696 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:33.049  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,09-13 22:54:33.050  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:33.050  2696  2696 V BluetoothAdapterState: isBleTurningOff()=true
09-13 22:54:33.050  2696  2712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 22:54:33.051  2696  2712 D BluetoothAdapterProperties: Setting state to 10
,09-13 22:54:33.051  2696  2712 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 22:54:33.051  2696  2712 I BluetoothAdapterState: Entering OffState
,09-13 22:54:33.053   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-13 22:54:33.057  4036  4036 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 22:54:33.073  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 22:54:33.073  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 22:54:33.073  2696  2713 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 22:54:33.076  2696  2713 D bt_stack_manager: event_clean_up_stack finished.
,09-13 22:54:33.076  2696  2696 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 22:54:33.079  4036  4036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 22:54:33.083  3819  4023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:33.084  2696  2696 I art     : System.exit called, status: 0
09-13 22:54:33.084  2696  2696 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 22:54:33.084   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@520a90c:true
,09-13 22:54:33.092   278   278 E lowmemorykiller: Error writing /proc/2696/oom_score_adj; errno=22
,09-13 22:54:33.109  4036  4036 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 22:54:33.112  4036  4036 D BluetoothMap: Create BluetoothMap proxy object
,09-13 22:54:33.120  4036  4036 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 22:54:33.125  4036  4036 D DockEventReceiver: finishStartingService: stopping service
,09-13 22:54:33.129  4036  4036 D BluetoothPbap: Proxy object connected
,09-13 22:54:33.129  4036  4036 D PbapServerProfile: Bluetooth service connected
,09-13 22:54:33.132   874   885 I ActivityManager: Killing 3693:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 22:54:33.163  4036  4036 D BluetoothPbap: Proxy object disconnected
09-13 22:54:33.163  4036  4036 D PbapServerProfile: Bluetooth service disconnected
,09-13 22:54:33.186   874  2196 I ActivityManager: Process com.android.bluetooth (pid 2696) has died
,09-13 22:54:33.188   874  2196 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,09-13 22:54:33.189   874  2196 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 22:54:33.195  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 22:54:33.232   874  2191 I ActivityManager: Start proc 4053:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-13 22:54:33.359  4053  4053 D AdapterServiceConfig: Adding HeadsetService
,09-13 22:54:33.359  4053  4053 D AdapterServiceConfig: Adding A2dpService
09-13 22:54:33.359  4053  4053 D AdapterServiceConfig: Adding HidService
,09-13 22:54:33.360  4053  4053 D AdapterServiceConfig: Adding HealthService
09-13 22:54:33.360  4053  4053 D AdapterServiceConfig: Adding PanService
,09-13 22:54:33.360  4053  4053 D AdapterServiceConfig: Adding GattService
09-13 22:54:33.360  4053  4053 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 22:54:33.382   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c3f927:true
09-13 22:54:33.382  4053  4053 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 22:54:33.387  4053  4053 I bt_bluedroid: init
,09-13 22:54:33.388  4053  4065 I BluetoothAdapterState: Entering OffState
,09-13 22:54:33.394  4053  4066 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 22:54:33.394  4053  4066 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 22:54:33.395  4053  4066 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 22:54:33.395  4053  4066 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 22:54:33.400  4053  4053 I bt_bluedroid: get_profile_interface socket
09-13 22:54:33.401   874   884 I ActivityManager: Start proc 4069:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 22:54:33.404  4053  4053 I bt_bluedroid: get_profile_interface sdp
,09-13 22:54:33.409  4053  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
09-13 22:54:33.411  4053  4072 D BluetoothAdapterProperties: Name is: Nexus 6
09-13 22:54:33.410  4053  4063 I bt_bluedroid: config_hci_snoop_log
,09-13 22:54:33.414   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-13 22:54:33.420  4053  4065 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 22:54:33.420  4053  4065 D BluetoothAdapterProperties: Setting state to 14
09-13 22:54:33.421  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 22:54:33.425  4053  4065 D BluetoothBondStateMachine: make
,09-13 22:54:33.429  4053  4083 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 22:54:33.434  4053  4065 I BluetoothAdapterState: Entering PendingCommandState
,09-13 22:54:33.435  4053  4053 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 22:54:33.438  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:33.439  4053  4053 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 22:54:33.440  4053  4053 D BtGatt.GattService: Received start request. Starting profile...
,09-13 22:54:33.440  4053  4053 D BtGatt.GattService: start()
09-13 22:54:33.440  4053  4053 I bt_bluedroid: get_profile_interface gatt
,09-13 22:54:33.442  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:33.442  4053  4053 D BtGatt.AdvertiseManager: advertise manager created
,09-13 22:54:33.449  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:33.449  4053  4053 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:33.449  4053  4053 V BluetoothAdapterState: isBleTurningOn()=true
09-13 22:54:33.450  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:33.451  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 22:54:33.452  4053  4065 I bt_bluedroid: enable
,09-13 22:54:33.452  4053  4066 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 22:54:33.453  4053  4066 I bt_hci  : start_up
,09-13 22:54:33.460  4053  4066 I bt_vendor: alloc value 0xb39ed189
09-13 22:54:33.460  4053  4066 I bt_vendor: init
09-13 22:54:33.460  4053  4066 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 22:54:33.460  4053  4066 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 22:54:33.461  4069  4069 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 22:54:33.566  4053  4066 D bt_hci  : start_up starting async portion
,09-13 22:54:33.566  4053  4086 I bt_hci  : event_finish_startup
,09-13 22:54:33.567  4053  4086 I bt_hci_h4: hal_open
09-13 22:54:33.567  4053  4086 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 22:54:33.573  4053  4086 I bt_userial_vendor: device fd = 51 open
,09-13 22:54:33.599  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 22:54:33.609  4053  4086 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 22:54:33.633  4069  4069 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.633  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:33.634  4069  4069 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:33.634  4069  4069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 22:54:33.640  4036  4036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 22:54:33.641  4053  4086 D bt_hwcfg: Chipset BCM4354A2
09-13 22:54:33.641  4053  4086 D bt_hwcfg: Target name = [BCM4354A2]
09-13 22:54:33.642  4053  4086 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
09-13 22:54:33.650  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:54:33.658  4036  4036 D DockEventReceiver: finishStartingService: stopping service
,09-13 22:54:33.720   874  1934 I ActivityManager: Killing 2252:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 22:54:33.897  4069  4092 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 22:54:33.920   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62b3a6e:true
,09-13 22:54:34.104  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 22:54:34.124  4053  4086 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 22:54:34.125  4053  4086 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 22:54:34.125  4053  4086 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 22:54:34.242  4053  4086 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 22:54:34.243  4053  4086 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 22:54:34.273  4053  4086 I bt_hwcfg: vendor lib fwcfg completed
09-13 22:54:34.273  4053  4086 I bt_vendor: firmware callback
,09-13 22:54:34.273  4053  4086 I bt_hci  : firmware_config_callback
,09-13 22:54:34.285  4053  4110 I bt_btu  : btu_task pending for preload complete event
,09-13 22:54:34.285  4053  4110 I bt_btu_task: Bluetooth chip preload is complete
,09-13 22:54:34.285  4053  4110 I bt_btu  : btu_task received preload complete event
,09-13 22:54:34.295  4053  4110 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 22:54:34.296  4053  4110 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 22:54:34.296  4053  4110 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 22:54:34.296  4053  4110 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 22:54:34.296  4053  4110 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 22:54:34.297  4053  4110 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 22:54:34.297  4053  4110 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 22:54:34.297  4053  4110 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 22:54:34.297  4053  4110 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 22:54:34.298  4053  4110 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 22:54:34.298  4053  4110 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 22:54:34.298  4053  4110 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 22:54:34.299  4053  4110 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 22:54:34.299  4053  4110 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 22:54:34.299  4053  4110 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 22:54:34.436  4053  4110 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ad9d
,09-13 22:54:34.436  4053  4110 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ad9d 
,09-13 22:54:34.444  4053  4072 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 22:54:34.447  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 22:54:34.448  4053  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 22:54:34.454  4053  4072 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 22:54:34.457  4053  4072 D BluetoothAdapterProperties: Scan Mode:20
,09-13 22:54:34.458  4053  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 22:54:34.458  4053  4072 D bt_hci  : do_postload posting postload work item
,09-13 22:54:34.459  4053  4086 I bt_hci  : event_postload
,09-13 22:54:34.459  4053  4086 I bt_vendor: sco_config_cb
,09-13 22:54:34.459  4053  4086 I bt_hci  : sco_config_callback postload finished.
,09-13 22:54:34.463  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.467  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.468  4053  4086 I bt_vendor: low_power_mode_cb,
,09-13 22:54:34.467  4053  4072 D bt_bte_conf: Device ID record 1 : primary
09-13 22:54:34.469  4053  4072 D bt_bte_conf:   vendorId            = 000f
09-13 22:54:34.470  4053  4072 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 22:54:34.470  4053  4072 D bt_bte_conf:   product             = 1200
09-13 22:54:34.470  4053  4072 D bt_bte_conf:   version             = 1436
09-13 22:54:34.471  4053  4072 D bt_bte_conf:   clientExecutableURL = 
09-13 22:54:34.471  4053  4072 D bt_bte_conf:   serviceDescription  = 
,09-13 22:54:34.471  4053  4072 D bt_bte_conf:   documentationURL    = 
09-13 22:54:34.471  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.472  4053  4072 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 22:54:34.473  4053  4066 D bt_stack_manager: event_start_up_stack finished
09-13 22:54:34.473  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 22:54:34.474  4053  4065 D BluetoothAdapterProperties: Setting state to 15
09-13 22:54:34.474  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 22:54:34.477  4053  4065 I BluetoothAdapterState: Entering BleOnState
09-13 22:54:34.478  4053  4065 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 22:54:34.478  4053  4065 D BluetoothAdapterProperties: Setting state to 11
09-13 22:54:34.478  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 22:54:34.482  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:34.488  4053  4053 D HeadsetService: Received start request. Starting profile...
09-13 22:54:34.489  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.491  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.492  4053  4053 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 22:54:34.492  4053  4053 D HeadsetStateMachine: make
,09-13 22:54:34.493  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.501  4053  4065 I BluetoothAdapterState: Entering PendingCommandState
,09-13 22:54:34.503  4053  4053 D HeadsetStateMachine: max_hf_connections = 1
,09-13 22:54:34.503  4053  4053 I bt_bluedroid: get_profile_interface handsfree
09-13 22:54:34.503  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 22:54:34.503  4053  4072 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-13 22:54:34.507  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:34.508  4053  4053 D A2dpService: Received start request. Starting profile...
,09-13 22:54:34.509  4053  4053 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 22:54:34.509  4053  4053 I bt_bluedroid: get_profile_interface avrcp
,09-13 22:54:34.515  4053  4053 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 22:54:34.515  4053  4053 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 22:54:34.515  4053  4053 D A2dpStateMachine: make
,09-13 22:54:34.517  4053  4053 I bt_bluedroid: get_profile_interface a2dp
,09-13 22:54:34.518  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 22:54:34.519  4053  4119 D A2dpStateMachine: Enter Disconnected: -2
,09-13 22:54:34.521  4053  4053 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 22:54:34.521  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:54:34.522  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
09-13 22:54:34.523  4053  4053 D HidService: Received start request. Starting profile...
09-13 22:54:34.524  4053  4053 I bt_bluedroid: get_profile_interface hidhost
09-13 22:54:34.524  4053  4053 D HidService: setHidService(): set to: null
09-13 22:54:34.524  4053  4072 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394c3e5
,09-13 22:54:34.524  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 22:54:34.524  4053  4053 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 22:54:34.525  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
09-13 22:54:34.525  4036  4036 D BluetoothInputDevice: Proxy object connected
,09-13 22:54:34.526  4053  4053 D HealthService: Received start request. Starting profile...
09-13 22:54:34.527  4036  4036 D HidProfile: Bluetooth service connected
,09-13 22:54:34.527  4053  4053 I bt_bluedroid: get_profile_interface health
09-13 22:54:34.528  4053  4053 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 22:54:34.529  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:34.531  4036  4036 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 22:54:34.531  4053  4053 D PanService: Received start request. Starting profile...
,09-13 22:54:34.531  4053  4053 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 22:54:34.531  4053  4053 I bt_bluedroid: get_profile_interface pan
09-13 22:54:34.531  4036  4036 D PanProfile: Bluetooth service connected
09-13 22:54:34.532  4053  4072 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 22:54:34.537  4053  4053 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:34.538  4053  4053 D BluetoothMapService: Received start request. Starting profile...
09-13 22:54:34.538  4053  4053 D BluetoothMapService: start()
09-13 22:54:34.539  4036  4036 D BluetoothMap: Proxy object connected
09-13 22:54:34.539  4036  4036 D MapProfile: Bluetooth service connected
09-13 22:54:34.539  4036  4036 D BluetoothMap: getConnectedDevices()
09-13 22:54:34.540  4036  4036 D BluetoothMap: Bluetooth is Not enabled
,09-13 22:54:34.541  4053  4053 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-13 22:54:34.543  4053  4053 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 22:54:34.543  4053  4053 D BluetoothMapAppObserver: createReceiver()
,09-13 22:54:34.544  4053  4053 D BluetoothMapAppObserver: initObservers()
09-13 22:54:34.544  4053  4053 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 22:54:34.553  4053  4053 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:34.553  4053  4053 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:34.553  4053  4117 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 22:54:34.553  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.553  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.555  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:34.555  4053  4053 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:34.555  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.555  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.557  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:34.557  4053  4053 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:34.558  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.558  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.558  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:34.558  4053  4053 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:34.558  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:34.558  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isTurningOn()=true
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isTurningOn()=true
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:34.559  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.560  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-13 22:54:34.560  4053  4065 D BluetoothAdapterProperties: ScanMode =  20
,09-13 22:54:34.560  4053  4065 D BluetoothAdapterProperties: State =  11
09-13 22:54:34.560  4053  4065 D BluetoothAdapterProperties: Setting state to 12
09-13 22:54:34.560  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 22:54:34.561  4053  4065 I BluetoothAdapterState: Entering OnState
09-13 22:54:34.561   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:34.562  1354  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:34.563  4036  4047 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 22:54:34.563  4053  4072 D BluetoothAdapterProperties: Scan Mode:21
09-13 22:54:34.563   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:34.563  4053  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 22:54:34.564  1354  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 22:54:34.567  1354  2016 D BluetoothPan: onBluetoothStateChange on: true
09-13 22:54:34.567  3819  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 22:54:34.568  1354  1354 D BluetoothA2dp: Proxy object connected
09-13 22:54:34.571  3819  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-13 22:54:34.571   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:34.572  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 22:54:34.572  4036  4046 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 22:54:34.572  1354  1354 D PanProfile: Bluetooth service connected
09-13 22:54:34.573  4053  4053 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 22:54:34.574  4053  4053 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 22:54:34.575  1354  1374 D BluetoothMap: onBluetoothStateChange: up=true
09-13 22:54:34.575  4053  4053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:34.578  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:34.578  1354  1354 D BluetoothMap: Proxy object connected
09-13 22:54:34.578  1354  1354 D MapProfile: Bluetooth service connected
09-13 22:54:34.578  1354  1354 D BluetoothMap: getConnectedDevices()
09-13 22:54:34.580  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:34.581   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 22:54:34.582  4053  4053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:34.582   874   874 D BluetoothA2dp: Proxy object connected
09-13 22:54:34.584  4036  4047 D BluetoothMap: onBluetoothStateChange: up=true
09-13 22:54:34.586  4053  4053 D ObexServerSockets: Succeed to create listening sockets 
09-13 22:54:34.586  4053  4053 D ObexServerSockets0: startAccept()
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:34.586  3819  3819 V io.jxcore.node,.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:34.586  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:34.586  4053  4053 D ObexServerSockets0: prepareForNewConnect()
09-13 22:54:34.586  1354  2016 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 22:54:34.588  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:34.589  4036  4046 D BluetoothPan: onBluetoothStateChange on: true
09-13 22:54:34.589  1354  1367 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 22:54:34.591  1354  1354 D BluetoothInputDevice: Proxy object connected
09-13 22:54:34.591  1354  1354 D HidProfile: Bluetooth service connected
09-13 22:54:34.592  1935  1951 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:34.592  4053  4053 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:34.592  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:34.592  4053  4053 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 22:54:34.593  4053  4124 D ObexServerSockets0: Accepting socket connection...
09-13 22:54:34.594   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 22:54:34.595  4053  4053 D BluetoothMapService: onReceive
09-13 22:54:34.595  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:34.595  4053  4053 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:54:34.595  4053  4053 D BluetoothMapService: STATE_ON
09-13 22:54:34.595  4053  4125 D ObexServerSockets0: Accepting socket connection...
09-13 22:54:34.597  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.599  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.599  4036  4036 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 22:54:34.600  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.606  3819  4049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.606  4036  4036 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 22:54:34.608  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:34.608  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:34.613  4036  4036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 22:54:34.614  4053  4065 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 22:54:34.615  4053  4065 D BluetoothAdapterProperties: Setting state to 13
,09-13 22:54:34.615  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 22:54:34.615  4053  4065 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 22:54:34.616  4053  4065 I BluetoothAdapterState: Entering PendingCommandState
,09-13 22:54:34.618  4053  4072 D BluetoothAdapterProperties: Scan Mode:20
,09-13 22:54:34.618  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 22:54:34.619  4036  4036 D BluetoothA2dp: Proxy object connected
09-13 22:54:34.620  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:34.620  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:34.621  4053  4053 D HeadsetService: Received stop request...Stopping profile...
09-13 22:54:34.622  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:54:34.622  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:54:34.623  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:34.625  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:34.625  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:34.626  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:54:34.626  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:34.626  4053  4053 D A2dpService: Received stop request...Stopping profile...
09-13 22:54:34.627  4053  4119 D A2dpStateMachine: Exit Disconnected: -1
,09-13 22:54:34.628   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 22:54:34.628  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-13 22:54:34.630  4036  4036 D DockEventReceiver: finishStartingService: stopping service
09-13 22:54:34.631  4036  4036 D BluetoothA2dp: Proxy object disconnected
,09-13 22:54:34.639  4036  4036 D BluetoothPbap: Proxy object connected
,09-13 22:54:34.639  4036  4036 D PbapServerProfile: Bluetooth service connected
09-13 22:54:34.639  1354  1354 D BluetoothPbap: Proxy object connected
09-13 22:54:34.639  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-13 22:54:34.640  4053  4053 D HidService: Received stop request...Stopping profile...
,09-13 22:54:34.640  4053  4053 D HidService: Stopping Bluetooth HidService
,09-13 22:54:34.641  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-13 22:54:34.641  4036  4036 D BluetoothInputDevice: Proxy object disconnected
09-13 22:54:34.641  4036  4036 D HidProfile: Bluetooth service disconnected
09-13 22:54:34.641  1354  1354 D HidProfile: Bluetooth service disconnected
09-13 22:54:34.641  4053  4053 V BluetoothAdapterState: isTurningOff()=true
09-13 22:54:34.641  4053  4053 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:34.642  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.642  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.643  4053  4053 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 22:54:34.643  4053  4053 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 22:54:34.643  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 22:54:34.643  4053  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:34.643  4053  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:34.643  4053  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 22:54:34.644  4053  4072 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 22:54:34.644  4053  4053 D HealthService: Received stop request...Stopping profile...
,09-13 22:54:34.651  4053  4053 D PanService: Received stop request...Stopping profile...
,09-13 22:54:34.652  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 22:54:34.652  1354  1354 D PanProfile: Bluetooth service disconnected
,09-13 22:54:34.653  4053  4053 V BluetoothAdapterState: isTurningOff()=true
09-13 22:54:34.653  4053  4053 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:34.653  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.653  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:34.654  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 22:54:34.654  4053  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:34.654  4053  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 22:54:34.654  4053  4110 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 22:54:34.654  4053  4110 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 22:54:34.654  4053  4110 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:54:34.654  4053  4110 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 22:54:34.652  4036  4036 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 22:54:34.655  4036  4036 D PanProfile: Bluetooth service disconnected
,09-13 22:54:34.655  4053  4053 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 22:54:34.656  4053  4053 D BluetoothMapService: stop()
09-13 22:54:34.658  4053  4053 D BluetoothMapAppObserver: deinitObservers()
,09-13 22:54:34.658  4053  4053 D BluetoothMapAppObserver: removeReceiver()
09-13 22:54:34.659  4036  4036 D BluetoothMap: Proxy object disconnected
,09-13 22:54:34.659  4036  4036 D MapProfile: Bluetooth service disconnected
09-13 22:54:34.660  4053  4053 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:34.660  4053  4053 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:34.660  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.660  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.660  4053  4053 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 22:54:34.660  4053  4053 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-13 22:54:34.660  4053  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 22:54:34.660  1354  1354 D BluetoothMap: Proxy object disconnected
,09-13 22:54:34.660  1354  1354 D MapProfile: Bluetooth service disconnected
,09-13 22:54:34.661  4053  4053 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:34.661  4053  4053 V BluetoothAdapterState: isTurningOn()=false
,09-13 22:54:34.661  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:34.661  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:34.661  4053  4053 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 22:54:34.661  4053  4072 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 22:54:34.662  4053  4053 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object,
09-13 22:54:34.669  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.670  4036  4036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 22:54:34.672  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.675  4036  4036 D DockEventReceiver: finishStartingService: stopping service
,09-13 22:54:34.677  4053  4053 V BluetoothAdapterState: isTurningOff()=true
,09-13 22:54:34.677  4053  4053 V BluetoothAdapterState: isTurningOn()=false
09-13 22:54:34.677  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.677  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:34.677  4053  4053 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 22:54:34.677  4053  4053 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 22:54:34.678  4053  4053 D BluetoothMapService: MAP Service closeService in
09-13 22:54:34.678  4053  4053 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 22:54:34.678  4053  4053 D ObexServerSockets0: shutdown(block = true)
,09-13 22:54:34.678  4053  4124 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 22:54:34.680  4053  4053 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 22:54:34.680  4053  4053 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 22:54:34.680  4053  4125 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 22:54:34.681  4053  4113 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 22:54:34.684  4053  4053 V BluetoothAdapterState: isTurningOff()=true
09-13 22:54:34.684  4053  4053 V BluetoothAdapterState: isTurningOn()=false
,09-13 22:54:34.684  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:34.684  4053  4053 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:34.684  4053  4053 D BluetoothMapService: cleanup()
09-13 22:54:34.684  4053  4053 D BluetoothMapService: MAP Service closeService in
09-13 22:54:34.685  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 22:54:34.685  4053  4065 D BluetoothAdapterProperties: Setting state to 15
09-13 22:54:34.685  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 22:54:34.686  4053  4065 I BluetoothAdapterState: Entering BleOnState
,09-13 22:54:34.686   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 22:54:34.687  1354  2016 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 22:54:34.687  4036  4047 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 22:54:34.689  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:54:34.689   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:54:34.689  1354  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 22:54:34.690  1354  1354 D BluetoothPbap: Proxy object disconnected
,09-13 22:54:34.690  1354  1354 D PbapServerProfile: Bluetooth service disconnected
09-13 22:54:34.690  4036  4036 D BluetoothPbap: Proxy object disconnected
09-13 22:54:34.690  4036  4036 D PbapServerProfile: Bluetooth service disconnected
,09-13 22:54:34.692  1354  2016 D BluetoothPan: onBluetoothStateChange on: false
,09-13 22:54:34.692   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:54:34.693  4036  4046 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 22:54:34.696  4036  4047 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:54:34.696  4036  4046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 22:54:34.696  1354  1367 D BluetoothMap: onBluetoothStateChange: up=false
09-13 22:54:34.697   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 22:54:34.699  4036  4047 D BluetoothMap: onBluetoothStateChange: up=false
09-13 22:54:34.700  1354  2016 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 22:54:34.700  4036  4046 D BluetoothPan: onBluetoothStateChange on: false
09-13 22:54:34.701  1354  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 22:54:34.701  1935  2114 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 22:54:34.702  4053  4065 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 22:54:34.702  4053  4065 D BluetoothAdapterProperties: Setting state to 16
09-13 22:54:34.702  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 22:54:34.703  4053  4065 D BluetoothAdapterProperties: onBleDisable
09-13 22:54:34.703  4053  4065 I BluetoothAdapterState: Entering PendingCommandState
09-13 22:54:34.703  4053  4066 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 22:54:34.705  4053  4110 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 22:54:34.705  4053  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 22:54:34.706  4053  4072 D BluetoothAdapterProperties: Scan Mode:20
,09-13 22:54:34.707  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.707  4036  4036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 22:54:34.708  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:34.709  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.711  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:34.712  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 22:54:34.716  4036  4036 D DockEventReceiver: finishStartingService: stopping service
,09-13 22:54:34.906  4053  4072 I bt_hci  : shut_down
,09-13 22:54:34.906  4053  4086 D bt_hwcfg: hw_epilog_process
09-13 22:54:34.908  4053  4086 I bt_vendor: low_power_mode_cb
,09-13 22:54:34.929  4053  4086 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 22:54:34.929  4053  4086 I bt_vendor: epilog_cb
,09-13 22:54:34.929  4053  4086 I bt_hci  : epilog_finished_callback
09-13 22:54:34.931  4053  4072 I bt_hci_h4: hal_close
,09-13 22:54:34.933  4053  4072 I bt_userial_vendor: device fd = 51 close
,09-13 22:54:35.067  4053  4066 D bt_stack_manager: event_shut_down_stack finished.
,09-13 22:54:35.068  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 22:54:35.076  4053  4065 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 22:54:35.076  4053  4053 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 22:54:35.078  4053  4053 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 22:54:35.079  4053  4053 D BtGatt.GattService: stop()
,09-13 22:54:35.079  4053  4053 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 22:54:35.084  4053  4053 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:35.084  4053  4053 V BluetoothAdapterState: isTurningOn()=false
,09-13 22:54:35.085  4053  4053 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:35.085  4053  4053 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 22:54:35.086  4053  4065 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 22:54:35.087  4053  4065 D BluetoothAdapterProperties: Setting state to 10
09-13 22:54:35.087  4053  4065 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 22:54:35.089  4053  4065 I BluetoothAdapterState: Entering OffState
,09-13 22:54:35.091   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 22:54:35.113  4053  4053 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-13 22:54:35.113  4053  4053 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 22:54:35.113  4053  4053 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 22:54:35.116  4053  4066 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 22:54:35.116  3819  4127 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:35.116  3819  4127 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:35.117  3819  4127 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:54:35.117  3819  4127 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:35.123  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:35.125  4053  4066 D bt_stack_manager: event_clean_up_stack finished.
,09-13 22:54:35.129  4053  4053 I art     : System.exit called, status: 0
,09-13 22:54:35.130  4053  4053 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 22:54:35.212   874  2197 I ActivityManager: Process com.android.bluetooth (pid 4053) has died
,09-13 22:54:35.213   874  2197 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 22:54:36.253   874   887 I ActivityManager: Start proc 4139:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 22:54:36.382  4139  4139 D AdapterServiceConfig: Adding HeadsetService
,09-13 22:54:36.382  4139  4139 D AdapterServiceConfig: Adding A2dpService
,09-13 22:54:36.383  4139  4139 D AdapterServiceConfig: Adding HidService
,09-13 22:54:36.383  4139  4139 D AdapterServiceConfig: Adding HealthService
,09-13 22:54:36.383  4139  4139 D AdapterServiceConfig: Adding PanService
09-13 22:54:36.383  4139  4139 D AdapterServiceConfig: Adding GattService
,09-13 22:54:36.384  4139  4139 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 22:54:36.399   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5095d7:true
,09-13 22:54:36.400  4139  4139 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 22:54:36.405  4139  4139 I bt_bluedroid: init
,09-13 22:54:36.406  4139  4151 I BluetoothAdapterState: Entering OffState
,09-13 22:54:36.413  4139  4152 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 22:54:36.413  4139  4152 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 22:54:36.413  4139  4152 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 22:54:36.414  4139  4152 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 22:54:36.417  4139  4139 I bt_bluedroid: get_profile_interface socket
,09-13 22:54:36.421  4139  4139 I bt_bluedroid: get_profile_interface sdp
,09-13 22:54:36.425  4139  4155 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 22:54:36.426  4139  4150 I bt_bluedroid: config_hci_snoop_log
,09-13 22:54:36.428   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 22:54:36.428  4139  4155 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 22:54:36.437  4139  4151 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 22:54:36.438  4139  4151 D BluetoothAdapterProperties: Setting state to 14
,09-13 22:54:36.438  4139  4151 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 22:54:36.443  4139  4151 D BluetoothBondStateMachine: make
,09-13 22:54:36.449  4139  4156 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 22:54:36.459  4139  4139 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 22:54:36.460  4139  4151 I BluetoothAdapterState: Entering PendingCommandState
,09-13 22:54:36.464  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:36.465  4139  4139 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 22:54:36.466  4139  4139 D BtGatt.GattService: Received start request. Starting profile...
,09-13 22:54:36.466  4139  4139 D BtGatt.GattService: start()
,09-13 22:54:36.467  4139  4139 I bt_bluedroid: get_profile_interface gatt
,09-13 22:54:36.468  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:36.468  4139  4139 D BtGatt.AdvertiseManager: advertise manager created
,09-13 22:54:36.482  4139  4139 V BluetoothAdapterState: isTurningOff()=false
,09-13 22:54:36.482  4139  4139 V BluetoothAdapterState: isTurningOn()=false
,09-13 22:54:36.482  4139  4139 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 22:54:36.482  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:36.483  4139  4151 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 22:54:36.485  4139  4151 I bt_bluedroid: enable
,09-13 22:54:36.486  4139  4152 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 22:54:36.488  4139  4152 I bt_hci  : start_up
,09-13 22:54:36.506  4139  4152 I bt_vendor: alloc value 0xb39ed189
09-13 22:54:36.506  4139  4152 I bt_vendor: init
09-13 22:54:36.506  4139  4152 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 22:54:36.506  4139  4152 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 22:54:36.620  4139  4152 D bt_hci  : start_up starting async portion
,09-13 22:54:36.621  4139  4159 I bt_hci  : event_finish_startup
,09-13 22:54:36.621  4139  4159 I bt_hci_h4: hal_open
,09-13 22:54:36.621  4139  4159 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 22:54:36.626  4139  4159 I bt_userial_vendor: device fd = 51 open
,09-13 22:54:36.641  4139  4151 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 22:54:36.655  4139  4159 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 22:54:36.688  4139  4159 D bt_hwcfg: Chipset BCM4354A2
09-13 22:54:36.688  4139  4159 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 22:54:36.689  4139  4159 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 22:54:37.151  4139  4151 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 22:54:37.239  4139  4159 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 22:54:37.239  4139  4159 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 22:54:37.239  4139  4159 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 22:54:37.356  4139  4159 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 22:54:37.357  4139  4159 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 22:54:37.388  4139  4159 I bt_hwcfg: vendor lib fwcfg completed
,09-13 22:54:37.389  4139  4159 I bt_vendor: firmware callback
,09-13 22:54:37.389  4139  4159 I bt_hci  : firmware_config_callback
,09-13 22:54:37.404  4139  4162 I bt_btu  : btu_task pending for preload complete event
,09-13 22:54:37.404  4139  4162 I bt_btu_task: Bluetooth chip preload is complete
09-13 22:54:37.404  4139  4162 I bt_btu  : btu_task received preload complete event
,09-13 22:54:37.414  4139  4162 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 22:54:37.414  4139  4162 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 22:54:37.414  4139  4162 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 22:54:37.415  4139  4162 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 22:54:37.415  4139  4162 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 22:54:37.415  4139  4162 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 22:54:37.416  4139  4162 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 22:54:37.416  4139  4162 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 22:54:37.416  4139  4162 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 22:54:37.417  4139  4162 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 22:54:37.417  4139  4162 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 22:54:37.417  4139  4162 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 22:54:37.418  4139  4162 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 22:54:37.418  4139  4162 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 22:54:37.418  4139  4162 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 22:54:37.554  4139  4162 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ad9d
,09-13 22:54:37.554  4139  4162 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ad9d 
,09-13 22:54:37.582  4139  4155 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 22:54:37.583  4139  4155 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 22:54:37.584  4139  4155 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 22:54:37.586  4139  4155 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 22:54:37.589  4139  4155 D BluetoothAdapterProperties: Scan Mode:20
,09-13 22:54:37.590  4139  4155 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 22:54:37.590  4139  4155 D bt_hci  : do_postload posting postload work item
,09-13 22:54:37.590  4139  4159 I bt_hci  : event_postload
,09-13 22:54:37.591  4139  4159 I bt_vendor: sco_config_cb
,09-13 22:54:37.591  4139  4159 I bt_hci  : sco_config_callback postload finished.
,09-13 22:54:37.594  4139  4155 D bt_bte_conf: Device ID record 1 : primary
09-13 22:54:37.594  4139  4155 D bt_bte_conf:   vendorId            = 000f
09-13 22:54:37.595  4139  4155 D bt_bte_conf:   vendorIdSource      = 0001
09-13 22:54:37.595  4139  4155 D bt_bte_conf:   product             = 1200
,09-13 22:54:37.596  4139  4155 D bt_bte_conf:   version             = 1436
,09-13 22:54:37.597  4139  4155 D bt_bte_conf:   clientExecutableURL = 
,09-13 22:54:37.597  4139  4155 D bt_bte_conf:   serviceDescription  = 
,09-13 22:54:37.597  4139  4155 D bt_bte_conf:   documentationURL    = 
,09-13 22:54:37.597  4139  4155 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 22:54:37.598  4139  4152 D bt_stack_manager: event_start_up_stack finished
,09-13 22:54:37.599  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:37.599  4139  4151 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 22:54:37.600  4139  4151 D BluetoothAdapterProperties: Setting state to 15
,09-13 22:54:37.600  4139  4151 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-13 22:54:37.601  4139  4159 I bt_vendor: low_power_mode_cb
,09-13 22:54:37.603  4139  4151 I BluetoothAdapterState: Entering BleOnState
,09-13 22:54:37.604  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-13 22:54:37.607  4139  4151 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 22:54:37.607  4139  4151 D BluetoothAdapterProperties: Setting state to 11
09-13 22:54:37.608  4139  4151 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 22:54:37.617  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
09-13 22:54:37.626  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:37.627   874   874 D BluetoothHeadset: Proxy object connected
09-13 22:54:37.627   874   874 D BluetoothHeadset: Proxy object connected
09-13 22:54:37.628  1354  1367 D BluetoothHeadset: Proxy object connected
09-13 22:54:37.628  4139  4139 D HeadsetService: Received start request. Starting profile...
09-13 22:54:37.630  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:37.631  4139  4139 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 22:54:37.631  4139  4139 D HeadsetStateMachine: make
09-13 22:54:37.632  1935  1951 D BluetoothHeadset: Proxy object connected
09-13 22:54:37.633  4036  4046 D BluetoothHeadset: Proxy object connected
09-13 22:54:37.635  4036  4036 D HeadsetProfile: Bluetooth service connected
09-13 22:54:37.635   874   874 D BluetoothHeadset: Proxy object connected
,09-13 22:54:37.640  4139  4139 D HeadsetStateMachine: max_hf_connections = 1
09-13 22:54:37.640  4139  4139 I bt_bluedroid: get_profile_interface handsfree
,09-13 22:54:37.640  4139  4155 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-13 22:54:37.640  4139  4155 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-13 22:54:37.644  4139  4151 I BluetoothAdapterState: Entering PendingCommandState
09-13 22:54:37.645  1354  1354 D HeadsetProfile: Bluetooth service connected
09-13 22:54:37.646  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
09-13 22:54:37.646  4139  4139 D A2dpService: Received start request. Starting profile...
09-13 22:54:37.647  4139  4139 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 22:54:37.647  4139  4139 I bt_bluedroid: get_profile_interface avrcp
,09-13 22:54:37.653  4139  4139 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 22:54:37.653  4139  4139 I BluetoothA2dpServiceJni: classInitNative: succeeds,
,09-13 22:54:37.654  4139  4139 D A2dpStateMachine: make
09-13 22:54:37.654  4139  4151 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-13 22:54:37.655  4139  4139 I bt_bluedroid: get_profile_interface a2dp
09-13 22:54:37.656  4139  4155 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-13 22:54:37.659  4139  4172 D A2dpStateMachine: Enter Disconnected: -2
09-13 22:54:37.660  4139  4139 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 22:54:37.661  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:37.661  4139  4139 D HidService: Received start request. Starting profile...
09-13 22:54:37.662  4139  4139 I bt_bluedroid: get_profile_interface hidhost
,09-13 22:54:37.662  4139  4155 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394c3e5
09-13 22:54:37.662  4139  4155 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 22:54:37.662  4139  4139 D HidService: setHidService(): set to: null
,09-13 22:54:37.665  4139  4139 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 22:54:37.666  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:54:37.668  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
09-13 22:54:37.669  4139  4139 D HealthService: Received start request. Starting profile...
,09-13 22:54:37.670  4139  4139 I bt_bluedroid: get_profile_interface health
,09-13 22:54:37.671  4139  4139 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 22:54:37.672  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
,09-13 22:54:37.672  4139  4139 D PanService: Received start request. Starting profile...
,09-13 22:54:37.673  4139  4139 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 22:54:37.673  4139  4139 I bt_bluedroid: get_profile_interface pan
,09-13 22:54:37.673  4139  4155 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 22:54:37.675  4139  4168 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 22:54:37.676  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db
09-13 22:54:37.677  4139  4139 D BluetoothMapService: Received start request. Starting profile...
,09-13 22:54:37.677  4139  4139 D BluetoothMapService: start()
,09-13 22:54:37.679  4139  4139 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 22:54:37.680  4139  4139 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 22:54:37.680  4139  4139 D BluetoothMapAppObserver: createReceiver()
,09-13 22:54:37.681  4139  4139 D BluetoothMapAppObserver: initObservers()
,09-13 22:54:37.681  4139  4139 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 22:54:37.686  4139  4139 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:37.686  4139  4139 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:37.686  4139  4139 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:37.686  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isTurningOn()=true
,09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isTurningOn()=true
,09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:37.688  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:37.690  4139  4139 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:37.690  4139  4139 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:37.690  4139  4139 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 22:54:37.691  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 22:54:37.691  4139  4139 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:37.691  4139  4139 V BluetoothAdapterState: isTurningOn()=true
09-13 22:54:37.691  4139  4139 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:37.691  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:37.691  4139  4139 V BluetoothAdapterState: isTurningOff()=false
09-13 22:54:37.692  4139  4139 V BluetoothAdapterState: isTurningOn()=true
,09-13 22:54:37.692  4139  4139 V BluetoothAdapterState: isBleTurningOn()=false
09-13 22:54:37.692  4139  4139 V BluetoothAdapterState: isBleTurningOff()=false
09-13 22:54:37.692  4139  4151 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 22:54:37.692  4139  4151 D BluetoothAdapterProperties: ScanMode =  20
09-13 22:54:37.692  4139  4151 D BluetoothAdapterProperties: State =  11
09-13 22:54:37.692  4139  4151 D BluetoothAdapterProperties: Setting state to 12
,09-13 22:54:37.692  4139  4151 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 22:54:37.693   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:37.693  4139  4151 I BluetoothAdapterState: Entering OnState
09-13 22:54:37.693  1354  2016 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:37.693  4036  4047 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 22:54:37.694  4139  4155 D BluetoothAdapterProperties: Scan Mode:21
09-13 22:54:37.694  4139  4155 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 22:54:37.695   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:37.696  1354  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 22:54:37.702  4036  4036 D BluetoothInputDevice: Proxy object connected
,09-13 22:54:37.702  4036  4036 D HidProfile: Bluetooth service connected
,09-13 22:54:37.703  1354  1374 D BluetoothPan: onBluetoothStateChange on: true
,09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:37.703  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:37.704  1354  1354 D BluetoothA2dp: Proxy object connected
,09-13 22:54:37.705   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 22:54:37.705  4036  4169 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 22:54:37.706  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 22:54:37.706  1354  1354 D PanProfile: Bluetooth service connected
09-13 22:54:37.706  4036  4047 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:37.706  4036  4046 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 22:54:37.707  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:37.707  4139  4139 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 22:54:37.707  4139  4139 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 22:54:37.708  1354  1367 D BluetoothMap: onBluetoothStateChange: up=true
09-13 22:54:37.709  4139  4139 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:37.711   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 22:54:37.711   874   874 D BluetoothA2dp: Proxy object connected
09-13 22:54:37.711  4139  4139 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:37.711  4036  4046 D BluetoothMap: onBluetoothStateChange: up=true
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:37.712  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:37.713  4139  4139 D ObexServerSockets: Succeed to create listening sockets 
,09-13 22:54:37.713  4139  4139 D ObexServerSockets0: startAccept()
09-13 22:54:37.714  4139  4139 D ObexServerSockets0: prepareForNewConnect()
,09-13 22:54:37.714  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:37.715  4036  4036 D BluetoothA2dp: Proxy object connected
09-13 22:54:37.715  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 22:54:37.718  4036  4047 D BluetoothPan: onBluetoothStateChange on: true
,09-13 22:54:37.719  4036  4036 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 22:54:37.719  1354  2016 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 22:54:37.719  4036  4036 D PanProfile: Bluetooth service connected
09-13 22:54:37.721  4139  4178 D ObexServerSockets0: Accepting socket connection...
09-13 22:54:37.721  1354  1354 D BluetoothInputDevice: Proxy object connected
,09-13 22:54:37.721  1354  1354 D HidProfile: Bluetooth service connected
09-13 22:54:37.722  1935  1955 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:54:37.723   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 22:54:37.723   874   874 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-13 22:54:37.723  4139  4139 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 22:54:37.726  4139  4139 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 22:54:37.727  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:37.728  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:37.728  4036  4036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 22:54:37.730  4139  4179 D ObexServerSockets0: Accepting socket connection...
09-13 22:54:37.730  1354  1354 D BluetoothMap: Proxy object connected
09-13 22:54:37.730  4139  4139 D BluetoothMapService: onReceive
,09-13 22:54:37.732  1354  1354 D MapProfile: Bluetooth service connected
,09-13 22:54:37.732  1354  1354 D BluetoothMap: getConnectedDevices()
09-13 22:54:37.732  4139  4139 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:54:37.732  4139  4139 D BluetoothMapService: STATE_ON
09-13 22:54:37.736  1579  1579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 22:54:37.740  4036  4036 D DockEventReceiver: finishStartingService: stopping service
,09-13 22:54:37.741  4036  4036 D BluetoothMap: Proxy object connected
09-13 22:54:37.741  4036  4036 D MapProfile: Bluetooth service connected
,09-13 22:54:37.741  4036  4036 D BluetoothMap: getConnectedDevices()
,09-13 22:54:37.747  4036  4036 D BluetoothPbap: Proxy object connected
,09-13 22:54:37.747  4036  4036 D PbapServerProfile: Bluetooth service connected
09-13 22:54:37.747  1354  1354 D BluetoothPbap: Proxy object connected
09-13 22:54:37.747  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-13 22:54:37.755  4139  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 22:54:37.763  4139  4139 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 22:54:37.763  4139  4139 D ObexServerSockets0: prepareForNewConnect()
,09-13 22:54:37.767  4139  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 22:54:37.768  4139  4188 I BtOppRfcommListener: Accept thread started.
,09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:38.157  3819  4138 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:38.160  3819  4138 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:38.164  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:38.166   874  2194 D WifiService: setWifiEnabled: false pid=3819, uid=10000
,09-13 22:54:38.167   874  2194 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:38.174   874  1940 D WifiService: setWifiEnabled: false pid=3819, uid=10000
09-13 22:54:38.174   874  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:54:38.176   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 22:54:38.185  2148  2350 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:38.191  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:38.198  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:38.205  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:54:38.208  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:38.688  3819  4193 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:38.696  3819  4193 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:38.705  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:38.706   874  1396 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,09-13 22:54:38.706   874  1396 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:38.718   874  1934 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,09-13 22:54:38.719   874  1934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:38.728   874  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:38.743  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:38.747  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:54:38.750   874  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-13 22:54:38.751   874  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 22:54:38.752   874  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 22:54:38.753   874  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 22:54:38.753   874  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 22:54:38.753   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 22:54:38.753   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:38.754  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:38.758  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:38.769   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 22:54:38.770   371   872 D CommandListener: Setting iface cfg
,09-13 22:54:38.771   874  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
,09-13 22:54:38.771   874  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 22:54:38.774   874  1311 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 22:54:38.774   874  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62,
,09-13 22:54:38.800   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:38.861   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:54:39.231  3819  4196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:54:39.239  3819  4196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:54:39.247  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:39.249  3819  3871 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 22:54:39.250   874  2024 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,09-13 22:54:39.251   874  2024 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:54:39.267  3819  4200 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 22:54:39.267  3819  4200 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 22:54:39.326   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 22:54:39.338  1872  1872 I Keyboard.Facilitator: onFinishInput()
,09-13 22:54:39.345   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 22:54:39.345   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 22:54:39.345   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 22:54:39.345   874   894 I Adreno  : Local Branch                     : M14
09-13 22:54:39.345   874   894 I Adreno  : Remote Branch                    : 
09-13 22:54:39.345   874   894 I Adreno  : Remote Branch                    : 
09-13 22:54:39.345   874   894 I Adreno  : Reconstruct Branch               : 
,09-13 22:54:39.386   280   299 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (198 us)
,09-13 22:54:39.788  3819  4204 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 22:54:39.790  3819  4204 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 22:54:39.791  3819  4204 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:54:39.792  3819  4200 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 22:54:39.793  3819  4204 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:39.793  3819  4200 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 22:54:39.793  3819  4200 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:39.796  3819  4207 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 484, name: IncomingSocketThread/Sender)
,09-13 22:54:39.797  3819  4204 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 22:54:39.800  3819  4208 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 485, name: IncomingSocketThread/Receiver)
09-13 22:54:39.801  3819  4200 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:39.804  3819  4208 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 485, thread name: IncomingSocketThread/Receiver)
,09-13 22:54:39.806  3819  4208 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 22:54:39.806  3819  4200 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 22:54:39.806  3819  4208 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 485, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 22:54:39.810  3819  4209 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: OutgoingSocketThread/Sender)
,09-13 22:54:39.811  3819  4210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: OutgoingSocketThread/Receiver)
,09-13 22:54:39.811  3819  4210 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 487, thread name: OutgoingSocketThread/Receiver)
,09-13 22:54:39.811  3819  4210 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 22:54:39.812  3819  4210 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 22:54:40.034  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 22:54:40.035  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 22:54:40.090   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 22:54:40.093  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@abda7b7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@705bf81, 16908290=android.view.AbsSavedState$1@705bf81}, android:focusedViewId=100}]}]
,09-13 22:54:40.093  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-13 22:54:40.094  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 22:54:40.094  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 22:54:40.099   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 22:54:40.106   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 22:54:40.106   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000,
,09-13 22:54:40.106   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 22:54:40.133   874   883 I art     : Background partial concurrent mark sweep GC freed 15631(911KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/43MB, paused 1.196ms total 120.763ms
,09-13 22:54:40.288  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 22:54:40.290  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 22:54:40.295  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@abda7b7 Bundle[{}]
,09-13 22:54:40.296  3819  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 22:54:40.297  3819  3871 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 22:54:40.299  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 22:54:40.299  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 22:54:40.300  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 22:54:40.300  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 22:54:40.301   874  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.35 rxSuccessRate=0.55 delta 1000 -> 1000
,09-13 22:54:40.307   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 22:54:40.307   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 22:54:40.310  3819  4211 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 22:54:40.310  3819  4211 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 22:54:40.322   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 22:54:40.333   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 22:54:40.335   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 22:54:40.340   874  1336 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
09-13 22:54:40.341   874   894 I DreamManagerService: Entering dreamland.
09-13 22:54:40.342   874   894 I PowerManagerService: Dozing...
,09-13 22:54:40.343   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 22:54:40.380   375  1285 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-13 22:54:40.380   375  1285 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 22:54:40.389   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 22:54:40.390  1485  1485 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 22:54:40.393  1921  4214 D NfcService: Discovery configuration equal, not updating.
,09-13 22:54:40.406   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:40.416   874  1312 E native  : do suspend false
,09-13 22:54:40.425   874  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 22:54:40.443   874  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 22:54:40.444  1485  1485 E wpa_supplicant: PNO: In assoc process
,09-13 22:54:40.445   874  1312 E WifiStateMachine:  Fail to set up pno, want true now false
,09-13 22:54:40.450   874  1312 E native  : do suspend true
,09-13 22:54:40.521   375  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 22:54:40.522   375  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 22:54:40.804  1485  1485 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 22:54:40.830  3819  4211 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 22:54:40.830  3819  4211 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 22:54:40.830  3819  4211 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:40.831  3819  4211 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:54:40.831  3819  4218 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 22:54:40.831  3819  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 498, name: OutgoingSocketThread/Sender)
,09-13 22:54:40.831  3819  4218 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 22:54:40.832  3819  4218 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:40.833  3819  4218 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:40.833  3819  4211 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 22:54:40.834  3819  4221 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: OutgoingSocketThread/Receiver)
,09-13 22:54:40.834  3819  4221 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 499, thread name: OutgoingSocketThread/Receiver),
,09-13 22:54:40.834  3819  4221 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 22:54:40.834  3819  4221 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 22:54:40.834  3819  4218 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 22:54:40.835  3819  4223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: IncomingSocketThread/Receiver)
,09-13 22:54:40.836  3819  4223 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 501, thread name: IncomingSocketThread/Receiver)
09-13 22:54:40.836  3819  4223 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 22:54:40.836  3819  4223 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 501, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 22:54:40.837  3819  4222 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: IncomingSocketThread/Sender)
,09-13 22:54:40.860  1485  1485 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 22:54:40.861  1485  1485 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 22:54:40.862   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 22:54:40.873   874  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 22:54:40.873   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 22:54:40.873   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 22:54:40.889   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 22:54:40.898   371   872 D CommandListener: Setting iface cfg
,09-13 22:54:40.901   874  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 22:54:40.910   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 22:54:40.939   874  4226 D DhcpClient: Receive thread started
,09-13 22:54:41.025   874  1312 E native  : do suspend false
,09-13 22:54:41.049   874  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 22:54:41.073   874  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172670, domain null
,09-13 22:54:41.074   874  1893 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172670 seconds
,09-13 22:54:41.077   874  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 22:54:41.091   874  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 22:54:41.092   874  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 22:54:41.097   371   872 D CommandListener: Setting iface cfg
,09-13 22:54:41.108   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 22:54:41.112   874  1312 E native  : do suspend true
,09-13 22:54:41.113   874  1893 D DhcpClient: Scheduling renewal in 86399s
,09-13 22:54:41.133   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 22:54:41.137   874  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 22:54:41.138   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 22:54:41.140   874  1314 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 22:54:41.144   874  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 22:54:41.187   874  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 22:54:41.188   874  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 22:54:41.190   874  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,09-13 22:54:41.190   874  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 22:54:41.192   874  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 22:54:41.196   874  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 22:54:41.209   874  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 22:54:41.217   874  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 22:54:41.217   874  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 22:54:41.218   874  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 22:54:41.219   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 22:54:41.219   874  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-13 22:54:41.220   874  1314 D ConnectivityService:    accepting network in place of null
,09-13 22:54:41.222   874  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 22:54:41.229   874  4225 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152020, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 22:54:41.258   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 22:54:41.296   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 22:54:41.309   874  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 22:54:41.309   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:54:41.311   874  4224 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 22:54:41.315   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 22:54:41.317   874  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:41.336  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:41.339  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 22:54:41.341  3819  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 510)
,09-13 22:54:41.342  3819  3871 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 22:54:41.342  3819  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 511)
,09-13 22:54:41.344  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 22:54:41.344  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920826 added. We now have 4 listener(s)
,09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:41.345  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:54:41.346  1998  1998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-13 22:54:41.346  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:41.346  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 22:54:41.346  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 22:54:41.346  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 22:54:41.346  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0d3c67 added. We now have 4 listener(s)
09-13 22:54:41.347  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:54:41.347  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 22:54:41.347  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 22:54:41.349  1759  1759 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 22:54:41.349  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:41.353  1759  1759 D SystemUpdateService: onCreate
,09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:54:41.356  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:54:41.357  1759  1759 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-13 22:54:41.358  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 22:54:41.358  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:54:41.361  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:54:41.362  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:41.362  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:41.362  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:54:41.363  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 22:54:41.363  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920826 removed from the list
,09-13 22:54:41.363  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:41.363  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0d3c67 removed from the list
,09-13 22:54:41.365  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:54:41.365  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:41.365  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:41.367  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-13 22:54:41.367  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-13 22:54:41.367  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:41.367  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 22:54:41.367  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 22:54:41.368  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:41.369  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 22:54:41.369  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:54:41.370  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 22:54:41.370  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 22:54:41.371  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 22:54:41.371  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 22:54:41.371  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:41.371  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:54:41.371  3819  4238 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:41.373  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 22:54:41.373  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 22:54:41.374  3819  4238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 22:54:41.375  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 22:54:41.376  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 22:54:41.376  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 22:54:41.378  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 22:54:41.378  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 22:54:41.378  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-13 22:54:41.378  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:41.378  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:41.378  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 22:54:41.379  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:41.382  4139  4177 D BtGatt.GattService: registerClient() - UUID=2173b34a-a920-4af3-bc85-8aa1c0a77659
09-13 22:54:41.382  4139  4155 D BtGatt.GattService: onClientRegistered() - UUID=2173b34a-a920-4af3-bc85-8aa1c0a77659, clientIf=5
09-13 22:54:41.383  3819  3861 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 22:54:41.384  4139  4157 D BtGatt.AdvertiseManager: message : 0
09-13 22:54:41.386  4139  4157 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 22:54:41.393  4139  4155 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 22:54:41.395  1759  1759 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 22:54:41.397  1759  2439 I iu.UploadsManager: num queued entries: 0
,09-13 22:54:41.398  4139  4155 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 22:54:41.399  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 22:54:41.399  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 22:54:41.400  1759  4236 I SystemUpdateService: active receiver: enabled,
09-13 22:54:41.400  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:41.401  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 22:54:41.402  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 22:54:41.402  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 22:54:41.402  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 22:54:41.402  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 22:54:41.402  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 22:54:41.403   874  4224 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 20:54:41 GMT], X-Android-Received-Millis=[1473800081402], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473800081376]}
09-13 22:54:41.403   874  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false,
09-13 22:54:41.403   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 22:54:41.404   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 22:54:41.404  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 22:54:41.404  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 22:54:41.404   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 22:54:41.411  1759  2439 I iu.UploadsManager: num updated entries: 0
,09-13 22:54:41.415  1759  1759 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 22:54:41.416  1759  1759 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 22:54:41.418  3938  3938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:54:41.421  1759  4242 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 22:54:41.421  1759  4242 W BaseAppContext: Using Auth Proxy for data requests.
09-13 22:54:41.422  1759  4242 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 22:54:41.424  3938  3938 D SprintDMHelper: simOperator: 
09-13 22:54:41.424  3938  3938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 22:54:41.425  1759  4236 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 22:54:41.435  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 22:54:41.436  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 22:54:41.450  1759  2439 I iu.SyncManager: NEXT; no task
,09-13 22:54:41.452  1759  4236 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 22:54:41.455  1759  4236 I SystemUpdateService: now status is 0 (complete)
,09-13 22:54:41.455  1759  4236 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 22:54:41.455  1759  4236 I SystemUpdateService: file has been verified
09-13 22:54:41.455  1759  4236 I SystemUpdateService: OTA package size = 12249756
,09-13 22:54:41.469  1579  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 22:54:41.470  1579  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 22:54:41.470  1579  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 22:54:41.470  1579  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:41.489  1759  4242 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-13 22:54:41.495  1759  4236 I SystemUpdateService: showing system update notification
,09-13 22:54:41.526  1759  1759 D SystemUpdateService: onDestroy
,09-13 22:54:41.539  1579  2319 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 22:54:41.539  1579  2319 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 22:54:41.539  1579  2319 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 22:54:41.539  1579  2319 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:41.555  3581  4241 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 22:54:41.555  3581  4241 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jdm.a(PG:82)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jcs.o(PG:406)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jcn.a(PG:1379)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jcs.i(PG:143)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at blb.a(PG:3937)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at czp.a(PG:18188)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at czp.a(PG:9081)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at czq.run(PG:1686)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 22:54:41.555  3581  4241 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jdj.a(PG:4091)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jdj.a(PG:1125)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jdm.a(PG:77)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	... 12 more
09-13 22:54:41.555  3581  4241 E HttpOperation: Caused by: faj: BadAuthentication
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at fal.a(PG:38)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	at jdj.a(PG:4089)
09-13 22:54:41.555  3581  4241 E HttpOperation: 	... 14 more
,09-13 22:54:41.565  3095  4248 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 22:54:41.597  1579  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 22:54:41.597  1579  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 22:54:41.597  1579  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 22:54:41.597  1579  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:41.626  3581  4241 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 22:54:41.626  3581  4241 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jdm.a(PG:82)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jcs.o(PG:406)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jcn.a(PG:1379)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jcs.i(PG:143)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at hec.a(PG:42)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at hee.a(PG:102)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at czr.a(PG:65)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at kka.a(PG:108)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at czp.a(PG:19176)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at czp.a(PG:9081)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at czq.run(PG:1686)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 22:54:41.626  3581  4241 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jdj.a(PG:4091)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jdj.a(PG:1125)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jdm.a(PG:77)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	... 15 more
09-13 22:54:41.626  3581  4241 E HttpOperation: Caused by: faj: BadAuthentication
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at fal.a(PG:38)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	at jdj.a(PG:4089)
09-13 22:54:41.626  3581  4241 E HttpOperation: 	... 17 more
,09-13 22:54:41.626  3581  4241 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 22:54:41.626  3581  4241 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at hec.a(PG:42)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at hee.a(PG:102)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at czr.a(PG:65)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at kka.a(PG:108)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	... 15 more
09-13 22:54:41.626  3581  4241 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at fal.a(PG:38)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 22:54:41.626  3581  4241 E ExperimentLoader: 	... 17 more
,09-13 22:54:41.745   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130144, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 22:54:41.904  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 22:54:41.905  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 22:54:41.905  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 22:54:42.308   874  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 22:54:44.910  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 22:54:44.910  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 22:54:44.910  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 22:54:44.910  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 22:54:44.911  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 22:54:44.912  3819  4238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 22:54:44.912  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:54:44.913  3819  4238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:54:44.913  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 22:54:44.913  3819  4238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:54:44.913  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 22:54:44.913  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:54:44.913  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:44.914  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:54:44.914  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:54:44.914  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:54:44.917  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:44.918  3819  3871 D BluetoothLeScanner: could not find callback wrapper
09-13 22:54:44.918  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 22:54:44.918  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 22:54:44.921  4139  4157 D BtGatt.AdvertiseManager: message : 1
,09-13 22:54:44.924  4139  4157 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 22:54:44.933  4139  4155 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
,09-13 22:54:44.933  4139  4155 D BtGatt.GattService: Client app is not null!
,09-13 22:54:44.935  4139  4149 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:44.936  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 22:54:44.936  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 22:54:44.937  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 22:54:44.937  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 22:54:44.938  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 22:54:44.940  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:44.941  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 22:54:44.941  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:54:44.942  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:44.948  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 22:54:44.948  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 22:54:44.949  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:54:44.950  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-13 22:54:44.950  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:44.950  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:44.951  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:44.951  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:44.951  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920826 not in the list
,09-13 22:54:44.951  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 22:54:44.951  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:44.951  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0d3c67 not in the list
,09-13 22:54:44.951  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:44.951  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:44.952  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:44.953  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:54:44.955  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 22:54:44.955  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 22:54:44.955  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:54:44.955  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:54:44.956  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:54:44.961  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 22:54:44.962  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 22:54:44.969  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 22:54:44.971  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 22:54:44.971  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:54:44.977  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 22:54:44.977  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 22:54:44.979  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 22:54:44.980  3819  3871 D BluetoothAdapter: STATE_ON
,09-13 22:54:44.984  4139  4150 D BtGatt.GattService: registerClient() - UUID=da813209-e6cd-47a0-b310-4f2294e6e41d
,09-13 22:54:44.985  4139  4155 D BtGatt.GattService: onClientRegistered() - UUID=da813209-e6cd-47a0-b310-4f2294e6e41d, clientIf=5
,09-13 22:54:44.985  3819  3861 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 22:54:44.988  4139  4180 D BtGatt.GattService: start scan with filters
,09-13 22:54:44.993  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 22:54:44.993  4139  4158 D BtGatt.ScanManager: handling starting scan
,09-13 22:54:44.994  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 22:54:44.994  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 22:54:44.995  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 22:54:44.996  4139  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5c58db,
,09-13 22:54:45.001  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 22:54:45.001  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 22:54:45.001  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 22:54:45.004  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:45.010  4139  4155 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 22:54:45.010  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:45.011  4139  4158 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 22:54:45.022  4139  4155 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 22:54:45.022  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:45.023  4139  4158 D BtGatt.ScanManager: Starting BLE batch scan
09-13 22:54:45.023  4139  4158 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,09-13 22:54:45.039  4139  4155 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 22:54:45.039  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:45.050  4139  4155 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 22:54:45.050  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:45.501  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 22:54:45.502  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:54:45.502  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 22:54:45.531  2148  2646 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 22:54:46.556  4139  4139 D BtGatt.ScanManager: awakened up at time 157347
,09-13 22:54:46.558  4139  4158 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 22:54:46.607  4139  4155 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-13 22:54:46.607  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:46.608  4139  4155 D BtGatt.GattService: current time is 157399349147
,09-13 22:54:46.609  4139  4155 D BtGatt.GattService: Batch record : [-84, -7, 58, 93, 125, 94, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, 71, -122, -77, 84, 69, -12, 1, -128, -99, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -91, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -126, -22, -96, 83, -39, -56, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65, 0]
,09-13 22:54:46.613  4139  4155 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
,09-13 22:54:46.615  4139  4155 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 22:54:46.616  4139  4155 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 22:54:46.617  4139  4155 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 22:54:46.617  4139  4155 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 22:54:46.618  4139  4155 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 22:54:46.619  4139  4155 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65]
,09-13 22:54:46.627  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 5], added - the peer count is 1
,09-13 22:54:46.628  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 5], added - the peer count is 2
,09-13 22:54:46.629  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 5], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
09-13 22:54:46.630  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 5], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-13 22:54:47.070   874  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 14 -> obsolete
,09-13 22:54:48.008  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:48.009  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:48.009  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:54:48.010  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920826 not in the list
09-13 22:54:48.010  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:48.010  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:48.010  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:54:48.011  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:54:48.012  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:54:48.012  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 22:54:48.015  3819  3871 D BluetoothAdapter: STATE_ON
09-13 22:54:48.017  4139  4180 D BtGatt.GattService: stopScan() - queue size =1
,09-13 22:54:48.020  4139  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:48.021  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 22:54:48.022  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 22:54:48.023  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 22:54:48.023  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 22:54:48.024  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 22:54:48.028  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:48.029  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 22:54:48.029  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 22:54:48.029  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 22:54:48.031  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:48.031  3819  3871 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-13 22:54:48.034  4139  4139 D BtGatt.ScanManager: awakened up at time 158825
,09-13 22:54:48.038  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:48.038  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:48.038  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0d3c67 not in the list
,09-13 22:54:48.038  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:48.038  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop,
,09-13 22:54:48.039  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:48.039  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:48.041  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-13 22:54:48.041  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 22:54:48.042  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 22:54:48.042  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 22:54:48.042  4139  4155 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 22:54:48.042  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:48.043  4139  4158 D BtGatt.ScanManager: stopping BLe Batch
,09-13 22:54:48.042  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 22:54:48.044  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:48.046  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 22:54:48.047  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:54:48.047  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 22:54:48.047  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
09-13 22:54:48.048  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 22:54:48.048  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 22:54:48.048  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:54:48.048  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:54:48.055  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 22:54:48.055  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 22:54:48.057  4139  4155 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 22:54:48.057  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 22:54:48.057  4139  4158 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 22:54:48.059  3819  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:54:48.060  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 22:54:48.063  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 22:54:48.063  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:54:48.065  3819  4260 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 22:54:48.068  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 22:54:48.068  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 22:54:48.068  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-13 22:54:48.068  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 22:54:48.069  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 22:54:48.069  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 22:54:48.069  3819  3871 D BluetoothAdapter: STATE_ON
,09-13 22:54:48.072  4139  4155 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-13 22:54:48.072  4139  4155 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 22:54:48.072  4139  4155 D BtGatt.GattService: current time is 158863794636
09-13 22:54:48.072  4139  4155 D BtGatt.GattService: Batch record : [-84, -7, 58, 93, 125, 94, 1, -128, -55, 29, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, -126, -22, -96, 83, -39, -56, 1, -128, -71, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65, 0, 35, 97, 126, -92, 22, -56, 1, -128, -92, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 22:54:48.072  4139  4155 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
09-13 22:54:48.073  4139  4155 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65]
09-13 22:54:48.073  4139  4155 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 22:54:48.074  4139  4170 D BtGatt.GattService: registerClient() - UUID=0b27f0ef-3a46-4553-bb67-e3572ae2b736
,09-13 22:54:48.074  4139  4155 D BtGatt.GattService: onClientRegistered() - UUID=0b27f0ef-3a46-4553-bb67-e3572ae2b736, clientIf=5
09-13 22:54:48.075  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 22:54:48.075  4139  4157 D BtGatt.AdvertiseManager: message : 0
,09-13 22:54:48.077  4139  4157 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 22:54:48.090  4139  4155 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 22:54:48.096  4139  4155 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 22:54:48.096  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 22:54:48.096  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 22:54:48.097  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 22:54:48.099  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 22:54:48.099  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 22:54:48.099  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 22:54:48.099  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 22:54:48.099  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 22:54:48.099  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING],
09-13 22:54:48.100  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 22:54:48.102  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 22:54:48.102  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 22:54:48.244  1579  4263 I VacuumService: Vacuum at: now=1473800088244 tag=VacuumService
,09-13 22:54:48.395  1579  4264 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 22:54:48.402  1579  4264 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 22:54:48.437  1579  4264 W Uploader:  no longer exists, so no auth token.
,09-13 22:54:48.603  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 22:54:48.603  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 22:54:48.604  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 22:54:49.225   874  1314 D ConnectivityService: handlePromptUnvalidated 101
,09-13 22:54:49.763  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 22:54:49.765  1579  1579 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 22:54:49.806  1579  4264 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 22:54:49.806  1579  4264 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 22:54:49.806  1579  4264 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 22:54:49.806  1579  4264 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:49.832  1579  4264 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 22:54:49.832  1579  4264 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 22:54:49.832  1579  4264 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 22:54:50.134  1579  4264 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 22:54:50.134  1579  4264 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-13 22:54:50.135  1579  4264 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 22:54:50.135  1579  4264 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:50.183  1579  4264 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 22:54:50.183  1579  4264 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 22:54:50.183  1579  4264 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 22:54:50.783  1579  4264 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 22:54:50.784  1579  4264 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-13 22:54:50.784  1579  4264 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 22:54:50.784  1579  4264 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 22:54:50.829  1579  4264 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 22:54:50.829  1579  4264 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 22:54:50.829  1579  4264 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 22:54:51.601  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:54:51.602  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 22:54:51.602  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 22:54:51.602  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 22:54:51.603  3819  4260 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 22:54:51.603  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:54:51.603  3819  4260 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:54:51.604  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 22:54:51.604  3819  4260 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 22:54:51.604  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920826 not in the list
,09-13 22:54:51.604  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:54:51.604  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 22:54:51.605  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:54:51.605  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:54:51.605  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 22:54:51.605  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 22:54:51.606  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:54:51.608  3819  3871 D BluetoothAdapter: STATE_ON
,09-13 22:54:51.609  3819  3871 D BluetoothLeScanner: could not find callback wrapper
09-13 22:54:51.609  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 22:54:51.609  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 22:54:51.611  4139  4157 D BtGatt.AdvertiseManager: message : 1
,09-13 22:54:51.613  4139  4157 D BtGatt.AdvertiseManager: stop advertise for client 5
09-13 22:54:51.623  4139  4155 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 22:54:51.623  4139  4155 D BtGatt.GattService: Client app is not null!
,09-13 22:54:51.626  4139  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 22:54:51.627  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 22:54:51.627  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 22:54:51.627  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 22:54:51.627  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 22:54:51.628  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 22:54:51.630  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:51.630  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 22:54:51.630  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:54:51.632  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:51.635  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0d3c67 not in the list
,09-13 22:54:51.635  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:54:51.635  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 22:54:51.635  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 22:54:51.635  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:54:51.635  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 22:54:51.635  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:54:51.636  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:54:51.636  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:51.636  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:51.636  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920826 not in the list
,09-13 22:54:51.636  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:54:51.636  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0d3c67 not in the list
,09-13 22:54:51.636  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:54:51.636  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:54:51.637  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:54:51.637  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 22:54:51.637  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 22:54:51.638  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 22:54:51.638  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:54:51.638  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
09-13 22:54:51.638  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 22:54:51.648  3819  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 531, name: My test thread name)
,09-13 22:54:52.136  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 22:54:53.647  3819  3871 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 531
,09-13 22:54:53.647  3819  3871 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 531, name: My test thread name)
,09-13 22:54:53.654  3819  4276 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 532, name: My test thread name)
,09-13 22:54:53.655  3819  4276 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 532, thread name: My test thread name)
,09-13 22:54:53.655  3819  4276 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 532, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 22:54:53.660  3819  3871 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:54:53.670  3819  4277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 536, name: My test thread name)
,09-13 22:54:53.671  3819  4277 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 536, thread name: My test thread name): Test exception.
,09-13 22:54:53.672  3819  4277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 536, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 22:54:53.679  3819  3871 I jxcore-log: Total number of executed tests:  82
09-13 22:54:53.679  3819  3871 I jxcore-log: 
09-13 22:54:53.681  3819  3871 I jxcore-log: Number of passed tests:  82
09-13 22:54:53.681  3819  3871 I jxcore-log: 
09-13 22:54:53.682  3819  3871 I jxcore-log: Number of failed tests:  0
09-13 22:54:53.682  3819  3871 I jxcore-log: 
,09-13 22:54:53.685  3819  3871 I jxcore-log: Number of ignored tests:  0
09-13 22:54:53.685  3819  3871 I jxcore-log: 
,09-13 22:54:53.686  3819  3871 I jxcore-log: Total duration:  25015
09-13 22:54:53.686  3819  3871 I jxcore-log: 
,09-13 22:54:53.693  3819  3871 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 22:54:53.693  3819  3871 I jxcore-log: 
,09-13 22:54:53.696  3819  3871 I jxcore-log: My device name is: motorola-Nexus 6
09-13 22:54:53.696  3819  3871 I jxcore-log: 
09-13 22:54:53.705  3819  3871 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 22:54:53.705  3819  3871 I jxcore-log: 
,09-13 22:54:53.714  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.714  3819  3871 I jxcore-log: 
,09-13 22:54:53.718  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.718  3819  3871 I jxcore-log: 
,09-13 22:54:53.723  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.723  3819  3871 I jxcore-log: 
,09-13 22:54:53.727  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 22:54:53.727  3819  3871 I jxcore-log: 
,09-13 22:54:53.730  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 22:54:53.730  3819  3871 I jxcore-log: 
,09-13 22:54:53.731  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.731  3819  3871 I jxcore-log: 
,09-13 22:54:53.732  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 22:54:53.732  3819  3871 I jxcore-log: 
09-13 22:54:53.733  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.733  3819  3871 I jxcore-log: 
09-13 22:54:53.734  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 22:54:53.734  3819  3871 I jxcore-log: 
,09-13 22:54:53.735  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.735  3819  3871 I jxcore-log: 
,09-13 22:54:53.736  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:54:53.736  3819  3871 I jxcore-log: 
,09-13 22:54:53.737  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:54:53.737  3819  3871 I jxcore-log: 
,09-13 22:54:53.738  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:54:53.738  3819  3871 I jxcore-log: 
09-13 22:54:53.740  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 22:54:53.740  3819  3871 I jxcore-log: 
09-13 22:54:53.741  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.741  3819  3871 I jxcore-log: 
09-13 22:54:53.742  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.742  3819  3871 I jxcore-log: 
09-13 22:54:53.743  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.743  3819  3871 I jxcore-log: 
09-13 22:54:53.744  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.744  3819  3871 I jxcore-log: 
09-13 22:54:53.745  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.745  3819  3871 I jxcore-log: 
,09-13 22:54:53.746  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.746  3819  3871 I jxcore-log: 
,09-13 22:54:53.746  3819  4275 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 531, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-13 22:54:53.748  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.748  3819  3871 I jxcore-log: 
,09-13 22:54:53.749  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.749  3819  3871 I jxcore-log: 
,09-13 22:54:53.749  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.749  3819  3871 I jxcore-log: 
,09-13 22:54:53.750  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.750  3819  3871 I jxcore-log: 
09-13 22:54:53.751  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.751  3819  3871 I jxcore-log: 
09-13 22:54:53.752  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.752  3819  3871 I jxcore-log: 
,09-13 22:54:53.753  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.753  3819  3871 I jxcore-log: 
09-13 22:54:53.753  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.753  3819  3871 I jxcore-log: 
,09-13 22:54:53.754  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.754  3819  3871 I jxcore-log: 
,09-13 22:54:53.755  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:54:53.755  3819  3871 I jxcore-log: 
09-13 22:54:53.756  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:54:53.756  3819  3871 I jxcore-log: 
09-13 22:54:53.757  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:54:53.757  3819  3871 I jxcore-log: 
,09-13 22:54:53.757  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.757  3819  3871 I jxcore-log: 
09-13 22:54:53.758  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.758  3819  3871 I jxcore-log: 
09-13 22:54:53.759  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:54:53.759  3819  3871 I jxcore-log: 
09-13 22:54:53.760  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.760  3819  3871 I jxcore-log: 
09-13 22:54:53.761  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.761  3819  3871 I jxcore-log: 
09-13 22:54:53.762  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:54:53.762  3819  3871 I jxcore-log: 
,09-13 22:54:53.763  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 22:54:53.763  3819  3871 I jxcore-log: 
09-13 22:54:53.764  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 22:54:53.764  3819  3871 I jxcore-log: 
09-13 22:54:53.766  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 22:54:53.766  3819  3871 I jxcore-log: 
,09-13 22:54:53.768  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 22:54:53.768  3819  3871 I jxcore-log: 
,09-13 22:54:53.770  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 22:54:53.770  3819  3871 I jxcore-log: 
,09-13 22:54:53.771  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 22:54:53.771  3819  3871 I jxcore-log: 
,09-13 22:54:53.865   874  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-13 22:54:54.328  4278  4278 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 22:54:54.333  4278  4278 D AndroidRuntime: CheckJNI is OFF
,09-13 22:54:54.377  4278  4278 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 22:54:54.424  4278  4278 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 22:54:54.445  4278  4278 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 22:54:54.453   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-13 22:54:54.454   874   887 I ActivityManager: Killing 3819:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 22:54:54.554   874   898 W PackageSettings: Skipping PackageSetting{85366dc com.example.hello/10273} due to missing metadata
,09-13 22:54:54.557   874  1934 D GraphicsStats: Buffer count: 2
09-13 22:54:54.558   874  1958 I WindowState: WIN DEATH: Window{13a94bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 22:54:54.558   874  1313 D WifiService: Client connection lost with reason: 4
,09-13 22:54:54.593   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-13 22:54:54.593   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-13 22:54:54.594   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-13 22:54:54.594   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 22:54:54.594   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:54.594   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:54.594   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 22:54:54.594   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 22:54:54.594   874   887 I ActivityManager:   Force finishing activity ActivityRecord{3fac594 u0 com.test.thalitest/.MainActivity t4}
,09-13 22:54:54.596   874   898 I art     : Starting a blocking GC Explicit
,09-13 22:54:54.603   874  1410 W ActivityManager: Spurious death for ProcessRecord{f1f4ae6 0:com.test.thalitest/u0a0}, curProc for 3819: null
,09-13 22:54:54.645   874   898 I art     : Explicit concurrent mark sweep GC freed 66211(4MB) AllocSpace objects, 12(332KB) LOS objects, 33% free, 29MB/43MB, paused 731us total 47.156ms
,09-13 22:54:54.676   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 22:54:54.679  4278  4278 I art     : System.exit called, status: 0
,09-13 22:54:54.679  4278  4278 I AndroidRuntime: VM exiting with result code 0.
,09-13 22:54:54.693   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 22:54:54.717   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 22:54:54.721  4139  4139 D BluetoothMapAppObserver: onReceive
,09-13 22:54:54.722  4139  4139 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 22:54:54.722  1872  1872 I Keyboard.Facilitator: resetDictionaries() : en_US
09-13 22:54:54.723  2148  2313 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 22:54:54.726  3662  3662 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 22:54:54.728   874  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 22:54:54.744   874  2196 I ActivityManager: Start proc 4291:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 22:54:54.746  1872  4289 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 22:54:54.758  1872  4289 I Decoder : createOrResetDecoder
,09-13 22:54:54.773  1935  1935 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 22:54:54.787  4291  4291 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 22:54:54.791  1579  1579 I ConfigService: onCreate
,09-13 22:54:54.819   874  1410 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3819 uid 10000
,09-13 22:54:54.820  1872  1872 I Keyboard.Facilitator: onFinishInput()
,09-13 22:54:54.821   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 22:54:54.823  1579  4304 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-13 22:54:54.835  1952  2026 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-13 22:54:54.835   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-13 22:54:54.836   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 22:54:54.836   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 22:54:54.836   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 22:54:54.836   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 22:54:54.836   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 22:54:54.836   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 22:54:54.836   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:54.836   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:54.836   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 22:54:54.843  1872  4289 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 22:54:54.847   874  1940 I ActivityManager: Start proc 4306:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-13 22:54:54.847  1952  2026 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 22:54:54.847  1952  2026 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1952
09-13 22:54:54.847  1952  2026 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
,09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:54.847  1952  2026 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 22:54:54.851   874  1979 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 22:54:54.855  1952  2026 I Process : Sending signal. PID: 1952 SIG: 9
,09-13 22:54:54.863   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 22:54:54.863   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 22:54:54.863   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:54.863   874   887 E DropBoxManagerService: 	... 13 more
,09-13 22:54:54.863   874  4311 E DropBoxManagerService: Can't write: system_app_crash
09-13 22:54:54.863   874  4311 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:54.863   874  4311 E DropBoxManagerService: 	... 5 more
,09-13 22:54:54.953  4291  4291 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 22:54:54.964  1872  4289 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 22:54:54.966   874  2196 D GraphicsStats: Buffer count: 1
09-13 22:54:54.966   874  2197 I WindowState: WIN DEATH: Window{9de3742 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-13 22:54:54.976  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-13 22:54:54.976  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-13 22:54:54.978   874  2196 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1952) has died
,09-13 22:54:54.979   874  2196 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-13 22:54:54.980   874  2196 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 22:54:54.994   874   887 I ActivityManager: Start proc 4324:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 22:54:55.008  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-13 22:54:55.008  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 22:54:55.008  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-13 22:54:55.008  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-13 22:54:55.017   874  2197 I ActivityManager: Start proc 4337:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 22:54:55.048  1872  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-13 22:54:55.048  1872  4289 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 22:54:55.048  1872  4289 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-13 22:54:55.048  1872  4289 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 22:54:55.048  1872  4289 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-13 22:54:55.048  1872  4289 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 22:54:55.053  4324  4324 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:55.053  4324  4324 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:55.054  4291  4335 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 22:54:55.054  4324  4324 D AndroidRuntime: Shutting down VM
,09-13 22:54:55.063  4324  4324 E AndroidRuntime: FATAL EXCEPTION: main
09-13 22:54:55.063  4324  4324 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4324
09-13 22:54:55.063  4324  4324 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 22:54:55.063  4324  4324 E AndroidRuntime: 	... 10 more
,09-13 22:54:55.064   874  2196 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 22:54:55.065   874  4350 E DropBoxManagerService: Can't write: system_app_crash
09-13 22:54:55.065   874  4350 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:55.065   874  4350 E DropBoxManagerService: 	... 5 more
,09-13 22:54:55.066  4324  4324 I Process : Sending signal. PID: 4324 SIG: 9
09-13 22:54:55.077  1759  4349 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-13 22:54:55.077  1759  4349 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-13 22:54:55.082  1759  4349 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-13 22:54:55.082  1759  4349 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-13 22:54:55.088  4337  4337 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 22:54:55.089   874  2191 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4324) has died
,09-13 22:54:55.090   874  2191 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 22:54:55.103  4291  4312 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.103  4291  4312 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 22:54:55.103   874   887 I ActivityManager: Start proc 4351:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.103  4291  4312 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 22:54:55.122  1579  1579 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-13 22:54:55.123  1579  1579 D AndroidRuntime: Shutting down VM
09-13 22:54:55.124  1579  1579 E AndroidRuntime: FATAL EXCEPTION: main
09-13 22:54:55.124  1579  1579 E AndroidRuntime: Process: com.google.process.gapps, PID: 1579
09-13 22:54:55.124  1579  1579 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 22:54:55.124  1579  1579 E AndroidRuntime: 	... 8 more
,09-13 22:54:55.130   874  4366 E DropBoxManagerService: Can't write: system_app_crash
09-13 22:54:55.130   874  4366 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:55.130   874  4366 E DropBoxManagerService: 	... 5 more
,09-13 22:54:55.131  1579  1579 I Process : Sending signal. PID: 1579 SIG: 9
09-13 22:54:55.145   874  2191 I ActivityManager: Killing 3715:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 22:54:55.170  4351  4351 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:55.170  4351  4351 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 22:54:55.171  4351  4351 D AndroidRuntime: Shutting down VM
,09-13 22:54:55.186  4291  4312 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-13 22:54:55.191   874  1313 D WifiService: Client connection lost with reason: 4
,09-13 22:54:55.215  4291  4335 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.215  4291  4335 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 22:54:55.215  4291  4335 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 22:54:55.215  4291  4335 E AndroidRuntime: Process: android.process.acore, PID: 4291
09-13 22:54:55.215  4291  4335 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.215  4291  4335 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 22:54:55.216  4291  4312 I Process : Sending signal. PID: 4291 SIG: 9
,09-13 22:54:55.228   874   884 I ActivityManager: Process com.google.process.gapps (pid 1579) has died
09-13 22:54:55.229   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-13 22:54:55.229   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-13 22:54:55.229   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-13 22:54:55.234  1759  1759 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-13 22:54:55.244   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-13 22:54:55.246   874   887 I ActivityManager: Start proc 4371:com.google.process.gapps/u0a11 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
09-13 22:54:55.249   874  4368 I ActivityManager: Process android.process.acore (pid 4291) has died
09-13 22:54:55.249   874  4368 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30979ms
09-13 22:54:55.251   874  4377 E DropBoxManagerService: Can't write: system_app_crash
09-13 22:54:55.251   874  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:55.251   874  4377 E DropBoxManagerService: 	... 5 more
09-13 22:54:55.252  4351  4351 E AndroidRuntime: FATAL EXCEPTION: main
09-13 22:54:55.252  4351  4351 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4351
09-13 22:54:55.252  4351  4351 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 22:54:55.252  4351  4351 E And,roidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 22:54:55.252  4351  4351 E AndroidRuntime: 	... 10 more
,09-13 22:54:55.254   874  2191 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 22:54:55.255  4351  4351 I Process : Sending signal. PID: 4351 SIG: 9
09-13 22:54:55.263   874  4382 E DropBoxManagerService: Can't write: system_app_crash
09-13 22:54:55.263   874  4382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 22:54:55.263   874  4382 E DropBoxManagerService: 	... 5 more
,09-13 22:54:55.267  1759  4349 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-13 22:54:55.268  1759  4349 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory

```
