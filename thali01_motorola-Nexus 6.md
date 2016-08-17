#### Test 80807573a62a5c7_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 14:01:10.852   873  1877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 14:01:12.143  3948  3948 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 14:01:12.147  3948  3948 D AndroidRuntime: CheckJNI is OFF
08-17 14:01:12.183  3948  3948 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 14:01:12.225  3948  3948 I Radio-JNI: register_android_hardware_Radio DONE
08-17 14:01:12.246  3948  3948 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 14:01:12.251   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 14:01:12.297  1978  3910 W SearchService: Abort, client detached.
08-17 14:01:12.308  1978  2305 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@712841a
08-17 14:01:12.309  1978  2330 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 14:01:12.309  1978  1978 I HotwordDetector: Closing mic
08-17 14:01:12.311  3948  3948 D AndroidRuntime: Shutting down VM
08-17 14:01:12.336   873  1945 I ActivityManager: Start proc 3957:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 14:01:12.361   377  2334 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 14:01:12.363   377  2334 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 14:01:12.372   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 14:01:12.373  1978  2317 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 14:01:12.374  1978  2329 I MicroRecognitionRnrImpl: Detection finished
08-17 14:01:12.429  3957  3957 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 14:01:12.467  3957  3957 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 14:01:12.480  3957  3957 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 1778-1786)
08-17 14:01:12.480  3957  3957 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:01:12.503  3957  3957 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b358cca}
08-17 14:01:12.504  3957  3957 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:01:12.504  3957  3957 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 14:01:12.512  3957  3957 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 14:01:12.514  3957  3957 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 14:01:12.546  3957  3957 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 14:01:12.560  3957  3957 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 14:01:12.560  3957  3957 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 14:01:12.560  3957  3957 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 14:01:12.560  3957  3957 I Adreno  : Build Date                       : 10/20/15
08-17 14:01:12.560  3957  3957 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 14:01:12.560  3957  3957 I Adreno  : Local Branch                     : M14
08-17 14:01:12.560  3957  3957 I Adreno  : Remote Branch                    : 
08-17 14:01:12.560  3957  3957 I Adreno  : Remote Branch                    : 
08-17 14:01:12.560  3957  3957 I Adreno  : Reconstruct Branch               : 
,08-17 14:01:12.662   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e5d030f:true
,08-17 14:01:12.701  3957  3957 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 14:01:12.720  3957  3957 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 14:01:12.781  3957  3995 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 14:01:12.795  3957  3982 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 14:01:12.824  3957  3995 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 14:01:12.877   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +569ms
,08-17 14:01:12.882  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-17 14:01:12.950  3957  3957 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3957
,08-17 14:01:12.960   873  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-17 14:01:13.073  3957  3957 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 14:01:13.190   873  3151 I ActivityManager: Killing 3662:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-17 14:01:13.232   873  3151 I ActivityManager: Killing 3160:com.google.android.talk/u0a61 (adj 15): empty #18
,08-17 14:01:13.350  3957  3997 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1678837456
,08-17 14:01:13.355  3957  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 14:01:13.355  3957  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 14:01:13.355  3957  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 14:01:13.355  3957  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 14:01:13.355  3957  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 14:01:13.355  3957  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2622e added. We now have 1 listener(s)
,08-17 14:01:13.359  3957  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 14:01:13.361  3957  3997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:01:13.362  3957  3997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:01:13.362  3957  3997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 14:01:13.366  3957  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a35a65 added. We now have 1 listener(s)
,08-17 14:01:13.367  3957  3997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:13.374   873  1308 D WifiService: New client listening to asynchronous messages
,08-17 14:01:13.377  3957  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:01:13.377  3957  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 14:01:13.378  3957  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 14:01:13.378  3957  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 14:01:13.378  3957  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 14:01:13.380  3957  3997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:13.380  3957  3997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 14:01:13.387  3957  3997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:13.387  3957  3997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:13.387  3957  3997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 14:01:13.387  3957  3997 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:01:13.388  3957  3997 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:01:13.463  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:13.465  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:13.467  3957  3957 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 14:01:14.391  3957  4008 W jxcore-log: Initializing JXcore engine
,08-17 14:01:14.391  3957  4008 W jxcore-log: JXcore engine is ready
,08-17 14:01:14.427  4008  4008 W Thread-350: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 14:01:14.430  4008  4008 W Thread-350: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11538]" dev="sockfs" ino=11538 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
,08-17 14:01:14.430  4008  4008 W Thread-350: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 14:01:14.430  4008  4008 W Thread-350: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25239]" dev="sockfs" ino=25239 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 14:01:14.464  3957  4008 W jxcore-log: Starting JXcore engine
,08-17 14:01:14.577  3957  4008 W jxcore-log: Platform android
08-17 14:01:14.577  3957  4008 W jxcore-log: 
,08-17 14:01:14.578  3957  4008 W jxcore-log: Process ARCH arm
08-17 14:01:14.578  3957  4008 W jxcore-log: 
,08-17 14:01:14.883  3957  4008 I jxcore-log: JXcore Cordova bridge is ready!
08-17 14:01:14.883  3957  4008 I jxcore-log: 
,08-17 14:01:14.883  3957  4008 W jxcore-log: JXcore engine is started
,08-17 14:01:14.895  3957  3997 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 14:01:14.900  3957  3957 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 14:01:18.385  3704  4016 V KeepSync: Connecting to GoogleApiClient
,08-17 14:01:18.386   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 14:01:18.420  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:18.422  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:18.439  1545  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 14:01:18.440  1545  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 14:01:18.440  1545  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:01:18.440  1545  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:18.450  1741  4017 V BaseAuthAsyncOperation: access token request failed
08-17 14:01:18.451  3704  4016 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 14:01:18.487  1545  1561 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 14:01:18.487  1545  1561 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 14:01:18.488  1545  1561 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:01:18.488  1545  1561 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:18.508  3704  4016 E KeepSync: IOException
08-17 14:01:18.508  3704  4016 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 14:01:18.508  3704  4016 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 14:01:18.508  3704  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 14:01:18.508  3704  4016 E KeepSync: 	... 10 more
08-17 14:01:18.509  3704  4016 W KeepSync: Sync result 2
,08-17 14:01:18.514   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127537, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 14:01:22.526  3739  4022 V GoogleAuthProtoRequest: [310] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 14:01:22.619  1545  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-17 14:01:22.619  1545  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-17 14:01:22.619  1545  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:22.619  1545  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:22.639  3739  4022 W ExperimentUpdateService: [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-17 14:01:22.640  3739  4022 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-17 14:01:22.645  1545  4024 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-17 14:01:22.647  1545  4024 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 14:01:22.669  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:22.687  1545  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 14:01:22.687  1545  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 14:01:22.687  1545  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:01:22.687  1545  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:22.698  3609  3609 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 14:01:22.698  3609  3609 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 14:01:22.698  3609  3609 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-17 14:01:23.050  1545  4024 W Uploader:  no longer exists, so no auth token.
,08-17 14:01:23.382  1545  4024 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 14:01:23.383  1545  4024 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 14:01:23.383  1545  4024 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:23.384  1545  4024 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:23.406  1545  4024 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 14:01:23.406  1545  4024 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 14:01:23.406  1545  4024 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 14:01:24.057  1545  4024 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 14:01:24.057  1545  4024 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-17 14:01:24.057  1545  4024 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:01:24.057  1545  4024 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:24.080  1545  4024 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 14:01:24.080  1545  4024 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 14:01:24.080  1545  4024 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 14:01:24.442  1545  4024 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 14:01:24.442  1545  4024 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 14:01:24.443  1545  4024 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:24.443  1545  4024 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:24.479  1545  4024 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 14:01:24.479  1545  4024 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 14:01:24.479  1545  4024 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 14:01:25.096  1545  4024 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 14:01:25.096  1545  4024 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 14:01:25.097  1545  4024 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:25.097  1545  4024 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:25.137  1545  4024 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 14:01:25.137  1545  4024 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 14:01:25.137  1545  4024 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 14:01:25.238  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 14:01:25.238  3957  4008 I jxcore-log: 
,08-17 14:01:25.241  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 14:01:25.241  3957  4008 I jxcore-log: 
,08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:25.253  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:25.259  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:25.261  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 14:01:25.261  3957  4008 I jxcore-log: 
,08-17 14:01:25.263  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 14:01:25.263  3957  4008 I jxcore-log: 
,08-17 14:01:25.614  3957  4008 D ExecuteNativeTests: Running unit tests
,08-17 14:01:25.674  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:01:25.674  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c added. We now have 2 listener(s)
08-17 14:01:25.675  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:01:25.675  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:25.675  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:25.676  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:25.676  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 added. We now have 2 listener(s)
08-17 14:01:25.676  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:25.676  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:01:25.691  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:25.705  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:25.711  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:25.712  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:01:25.719  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:01:25.720  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:01:25.720  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:01:25.722  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.726  3957  4008 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 14:01:25.726  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 14:01:25.727  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:01:25.727  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:25.728  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 14:01:25.729  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.732  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:25.735  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:25.735  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:01:25.738  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.738  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.739  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:25.739  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:25.739  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c removed from the list
,08-17 14:01:25.740  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.740  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 removed from the list
08-17 14:01:25.740  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:01:25.740  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.743  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:25.743  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.744  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:25.744  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:25.744  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:25.744  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:25.746  3957  4008 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 14:01:25.747  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:25.747  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:25.748  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:25.748  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.748  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.748  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.748  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:25.748  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.748  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.748  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:25.748  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.748  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.748  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.748  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.751  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:25.751  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:25.751  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.751  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:25.756  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:01:25.757  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:01:25.758  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:01:25.759  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:01:25.759  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:25.759  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:25.759  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:25.759  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.759  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.759  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.759  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:25.759  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.759  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.759  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:25.759  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.759  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.759  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.760  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:25.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:25.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.761  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.761  3957  4008 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:01:25.763  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:25.770  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:25.774  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:25.775  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:25.775  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:25.776  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:25.776  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:25.776  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:25.777  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:25.778  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:25.783  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.786  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:01:25.786  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:01:25.796  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:01:25.800  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:01:25.800  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:25.805  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 14:01:25.811  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 14:01:25.812  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:01:25.813  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:01:25.815  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:01:25.818  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:25.829  2741  2892 D BtGatt.GattService: registerClient() - UUID=7954f2f0-fd8f-405f-b34f-9b0c4426769c
,08-17 14:01:25.831  2741  2775 D BtGatt.GattService: onClientRegistered() - UUID=7954f2f0-fd8f-405f-b34f-9b0c4426769c, clientIf=5
,08-17 14:01:25.833  3957  3969 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:01:25.834  2741  2914 D BtGatt.GattService: start scan with filters
,08-17 14:01:25.840  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:01:25.840  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:01:25.840  2741  2791 D BtGatt.ScanManager: handling starting scan
08-17 14:01:25.841  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:01:25.841  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:01:25.845  2741  2791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:25.846  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:25.847  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:25.849  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:01:25.855  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:01:25.859  3957  4008 I io.jxcore.node.ConnectionHelper: start: OK
08-17 14:01:25.859  2741  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:01:25.859  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.861  2741  2791 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:01:25.863  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:25.863  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:01:25.864  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:25.864  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:01:25.864  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:25.864  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 14:01:25.864  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 14:01:25.864  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:01:25.864  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:01:25.864  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:25.865  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:01:25.865  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:01:25.867  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:25.868  2741  2892 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:01:25.869  2741  2753 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:01:25.869  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:25.869  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:01:25.869  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:01:25.869  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:01:25.869  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:01:25.871  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:25.871  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:01:25.871  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:01:25.872  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:25.873  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:25.874  2741  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:01:25.875  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.875  2741  2791 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:01:25.875  2741  2791 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 14:01:25.876  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.876  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:25.877  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:25.877  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.877  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:25.877  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:25.877  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
,08-17 14:01:25.877  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.878  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:25.878  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:25.878  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:25.881  3957  4008 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:01:25.900  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:25.901  2741  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 14:01:25.902  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:25.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:25.909  2741  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 14:01:25.909  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.911  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:25.912  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:25.912  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:01:25.912  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 14:01:25.912  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 14:01:25.912  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:25.912  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-17 14:01:25.918  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.919  2741  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:01:25.920  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.920  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 14:01:25.920  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:01:25.921  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.923  2741  2791 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:01:25.924  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:01:25.925  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 14:01:25.926  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:25.930  2741  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:01:25.930  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:01:25.930  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:01:25.930  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:01:25.930  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.931  2741  2791 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:01:25.931  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:25.934  2741  2755 D BtGatt.GattService: registerClient() - UUID=033b7b5f-8c54-4977-93c8-ea3064d4e92b
08-17 14:01:25.935  2741  2775 D BtGatt.GattService: onClientRegistered() - UUID=033b7b5f-8c54-4977-93c8-ea3064d4e92b, clientIf=5
,08-17 14:01:25.935  3957  3969 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 14:01:25.935  2741  2892 D BtGatt.GattService: start scan with filters
,08-17 14:01:25.938  2741  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:01:25.938  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.939  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:01:25.939  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:01:25.939  2741  2791 D BtGatt.ScanManager: handling starting scan
,08-17 14:01:25.939  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:01:25.939  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 14:01:25.941  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:25.942  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:25.942  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:01:25.944  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:01:25.945  2741  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:01:25.945  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.946  2741  2791 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 14:01:25.946  3957  4008 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:01:25.949  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:25.949  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:01:25.949  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:25.949  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 14:01:25.949  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:25.949  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 14:01:25.949  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 14:01:25.949  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:01:25.949  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 14:01:25.949  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:25.949  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 14:01:25.949  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:01:25.950  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:25.951  2741  2755 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:01:25.951  2741  2892 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 14:01:25.952  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:01:25.952  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 14:01:25.952  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:01:25.952  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 14:01:25.952  2741  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 14:01:25.952  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:01:25.952  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.952  2741  2791 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:01:25.952  2741  2791 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 14:01:25.953  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:25.953  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-17 14:01:25.953  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 14:01:25.953  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:25.953  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:01:25.954  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:01:25.954  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:25.954  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:01:25.955  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.955  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:25.955  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:01:25.955  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:25.955  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:25.955  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.955  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:01:25.955  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.955  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.955  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:25.956  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:01:25.956  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:25.956  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.956  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.958  3957  4008 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:01:25.959  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:25.962  2741  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 14:01:25.962  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:25.963  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:25.964  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-17 14:01:25.965  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:25.966  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.967  2741  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 14:01:25.968  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.968  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:25.968  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:25.968  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:25.968  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:25.969  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:25.969  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:01:25.971  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 14:01:25.971  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:01:25.974  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:01:25.974  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:01:25.974  2741  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 14:01:25.974  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:25.974  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.975  2741  2791 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:01:25.977  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:01:25.977  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:01:25.977  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:01:25.978  3957  4008 D BluetoothAdapter: STATE_ON
08-17 14:01:25.979  2741  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:01:25.980  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-17 14:01:25.980  2741  2791 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:01:25.980  2741  2892 D BtGatt.GattService: registerClient() - UUID=166a842e-9cf4-4f19-8e5f-ab02f5cafe1d
08-17 14:01:25.980  2741  2775 D BtGatt.GattService: onClientRegistered() - UUID=166a842e-9cf4-4f19-8e5f-ab02f5cafe1d, clientIf=5
,08-17 14:01:25.981  3957  3969 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 14:01:25.981  2741  2755 D BtGatt.GattService: start scan with filters
08-17 14:01:25.983  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:01:25.984  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 14:01:25.984  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:01:25.984  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:01:25.985  2741  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 14:01:25.985  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.986  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:01:25.986  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:01:25.986  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:01:25.986  2741  2791 D BtGatt.ScanManager: handling starting scan
,08-17 14:01:25.987  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:01:25.989  3957  4008 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:01:25.989  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:25.989  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:01:25.989  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:25.989  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:01:25.990  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.990  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 14:01:25.990  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:01:25.990  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:01:25.990  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:01:25.990  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 14:01:25.990  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:01:25.990  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:01:25.990  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:25.991  2741  2755 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:01:25.991  2741  2914 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:01:25.992  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:01:25.992  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:01:25.992  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:01:25.992  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-17 14:01:25.992  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:01:25.992  2741  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:01:25.992  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:25.993  2741  2791 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:01:25.993  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:25.993  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:01:25.993  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:01:25.993  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:25.994  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:25.995  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:25.995  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:01:25.995  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:01:25.995  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:25.995  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 14:01:25.995  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:25.995  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:25.995  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.995  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.996  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:25.996  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
,08-17 14:01:25.996  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.996  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.996  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:25.996  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.996  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:25.996  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.997  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:25.997  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:25.997  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:25.997  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.997  2741  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:01:25.997  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:25.997  2741  2791 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:01:25.997  2741  2791 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 14:01:25.998  3957  4008 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 14:01:25.998  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:25.998  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:25.998  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:01:25.998  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:25.998  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.998  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.998  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
,08-17 14:01:25.998  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.998  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:25.998  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:25.998  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.999  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:25.999  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:25.999  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:25.999  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:01:25.999  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:25.999  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:25.999  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.000  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 14:01:26.000  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.000  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.000  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.002  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.002  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.002  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.002  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.002  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.002  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.002  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.002  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.002  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.002  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.003  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.004  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.004  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.004  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.005  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.005  2741  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 14:01:26.005  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:26.005  3957  4008 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-17 14:01:26.005  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.005  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.005  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.005  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.006  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.006  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.006  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.006  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.006  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.006  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.006  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.006  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.006  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.006  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:26.009  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.009  2741  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 14:01:26.009  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:26.009  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.009  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-17 14:01:26.009  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:26.010  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 14:01:26.010  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.012  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:26.012  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.012  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.012  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.012  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.012  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.012  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.012  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.012  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:01:26.013  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.013  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.013  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.013  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.014  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.014  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:26.014  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.014  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.015  2741  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:01:26.015  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:26.015  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:01:26.015  2741  2791 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:01:26.015  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:01:26.015  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:01:26.016  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:26.016  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 14:01:26.016  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:01:26.016  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:26.016  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.016  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.016  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:01:26.016  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.017  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.017  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.017  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.019  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list,
08-17 14:01:26.019  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.019  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.019  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.021  2741  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:01:26.021  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:26.019  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.021  2741  2791 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:01:26.021  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:26.023  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:01:26.023  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.023  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.023  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.024  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:26.025  3957  4008 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:01:26.025  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:01:26.025  2741  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:01:26.025  2741  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:26.031  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 14:01:26.031  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 14:01:26.031  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:01:26.031  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-17 14:01:26.031  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:01:26.032  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-17 14:01:26.033  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:01:26.033  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 14:01:26.034  3957  4008 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:01:26.034  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-17 14:01:26.034  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:26.034  3957  4008 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:01:26.034  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 14:01:26.034  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:26.034  3957  4008 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:01:26.034  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-17 14:01:26.038  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 14:01:26.039  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 14:01:26.039  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 14:01:26.039  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 14:01:26.039  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 14:01:26.039  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 14:01:26.039  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:26.039  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 14:01:26.040  3957  4033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 414)
,08-17 14:01:26.040  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.040  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.040  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:01:26.041  3957  4033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:26.042  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.042  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.042  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.042  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-17 14:01:26.043  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
,08-17 14:01:26.043  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.043  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:26.043  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.043  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.043  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.044  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.044  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.044  3957  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 414
08-17 14:01:26.044  3957  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 414)
08-17 14:01:26.044  3957  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 414)
08-17 14:01:26.044  2741  2889 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-17 14:01:26.044  3957  4033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 414)
,08-17 14:01:26.045  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.045  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.045  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.045  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.046  3957  4008 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 14:01:26.047  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.047  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.047  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.047  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:01:26.047  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.047  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.047  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.047  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.047  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.047  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.047  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.047  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.047  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.047  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.049  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.049  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.049  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.049  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.049  3957  4008 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 14:01:26.049  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.049  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:26.049  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.050  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.050  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.050  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.050  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.050  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.050  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.050  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.050  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.050  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.050  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.050  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.051  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.051  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.051  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.052  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.052  3957  4008 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 14:01:26.052  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 14:01:26.052  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:01:26.052  3957  4008 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-17 14:01:26.052  3957  4008 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:01:26.052  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 14:01:26.052  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:01:26.052  3957  4008 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 14:01:26.052  3957  4008 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:01:26.052  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:01:26.052  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:01:26.053  3957  4008 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 14:01:26.053  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.053  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.053  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:01:26.053  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.053  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.053  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.053  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.053  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.053  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.053  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.053  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.053  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.053  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.053  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.055  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:01:26.055  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.055  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.055  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.055  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.055  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.055  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.055  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.056  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.056  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.056  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.056  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.056  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.056  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.056  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.056  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:01:26.056  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.056  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.056  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.056  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.056  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.056  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.056  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.056  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.056  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.057  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.057  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.057  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.057  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.057  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.057  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.057  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.057  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:26.057  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.057  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.057  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.058  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.058  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 14:01:26.059  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:26.059  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 14:01:26.059  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 14:01:26.060  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 14:01:26.060  3957  3957 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 14:01:26.060  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 14:01:26.060  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:01:26.060  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:01:26.060  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 14:01:26.060  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 14:01:26.060  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 14:01:26.060  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:26.060  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 14:01:26.061  3957  3957 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 14:01:26.061  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.061  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.061  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:01:26.061  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 14:01:26.061  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:26.061  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.061  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.061  3957  4035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:26.062  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:26.062  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:26.062  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:26.062  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:26.062  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:26.062  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.063  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:26.063  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.063  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.063  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.063  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.063  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
,08-17 14:01:26.063  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.063  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.063  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.063  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.063  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.063  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.063  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:26.064  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.064  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:26.064  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.064  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.064  3957  4035 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-17 14:01:26.064  3957  4035 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 14:01:26.064  3957  4035 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-17 14:01:26.065  3957  3957 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 14:01:26.065  3957  4008 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 14:01:26.065  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 14:01:26.065  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:01:26.066  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:26.066  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:26.066  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.066  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.066  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.066  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.066  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.066  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.066  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:26.066  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.066  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.066  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.066  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:26.066  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.066  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.067  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.067  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:26.067  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.068  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.071  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.071  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:26.071  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:01:26.072  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.072  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.072  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.072  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
,08-17 14:01:26.072  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.072  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.072  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.072  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.072  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.072  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.072  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.073  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:01:26.073  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:26.073  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.073  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
,08-17 14:01:26.074  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:26.074  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:26.074  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:26.074  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:26.074  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.074  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.074  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fa7f1c not in the list
08-17 14:01:26.074  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.074  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list,
08-17 14:01:26.074  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:26.074  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:26.074  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.074  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:26.074  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:26.076  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:26.076  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:26.076  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:26.076  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ad725 not in the list
08-17 14:01:26.076  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-17 14:01:26.077  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:01:26.077  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 14:01:26.077  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:01:26.077  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 14:01:26.077  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 14:01:26.078  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:01:26.078  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 14:01:26.079  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-17 14:01:26.079  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:01:26.079  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 14:01:26.079  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:01:26.079  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-17 14:01:26.079  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 14:01:26.079  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 14:01:26.079  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 14:01:26.080  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 14:01:26.080  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 14:01:26.080  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 14:01:26.080  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 14:01:26.081  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:26.081  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ffeab7f added. We now have 2 listener(s)
08-17 14:01:26.081  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:26.083  3957  4008 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 14:01:26.083   873  1932 D WifiService: setWifiEnabled: true pid=3957, uid=10000
08-17 14:01:26.083   873  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:01:26.084  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:26.084  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae9e74c added. We now have 3 listener(s)
08-17 14:01:26.084  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:26.090  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:26.090  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad8d395 added. We now have 4 listener(s)
08-17 14:01:26.090  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:26.091  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:26.091  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@907acaa added. We now have 5 listener(s)
08-17 14:01:26.091  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:26.101   873  1568 D WifiService: setWifiEnabled: false pid=3957, uid=10000
08-17 14:01:26.101   873  1568 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:26.105  2741  2767 D BluetoothAdapterState: Current state: ON, message: 23
08-17 14:01:26.105  2741  2767 D BluetoothAdapterProperties: Setting state to 13
08-17 14:01:26.105  2741  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 14:01:26.105  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:26.105  2741  2767 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:01:26.106  2741  2767 I BluetoothAdapterState: Entering PendingCommandState
08-17 14:01:26.107  2741  2741 D BluetoothMapService: onReceive
08-17 14:01:26.107  2741  2741 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:26.107  2741  2741 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:01:26.108  2741  2741 D BluetoothMapService: MAP Service closeService in
,08-17 14:01:26.108  2741  2741 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 14:01:26.108  2741  2741 D ObexServerSockets0: shutdown(block = true)
08-17 14:01:26.109  2741  2741 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:01:26.109  2741  2915 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 14:01:26.109  2741  2741 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:01:26.109  2741  2916 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 14:01:26.110  2741  2889 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 14:01:26.110  2741  2741 I BtOppRfcommListener: stopping Accept Thread
,08-17 14:01:26.110  2741  3541 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:26.110  2741  3541 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 14:01:26.112  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:26.112  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:26.116  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.116  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:26.116  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:01:26.119  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:26.122  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:26.123  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 14:01:26.124   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 14:01:26.125   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 14:01:26.125   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 14:01:26.125   873   886 I ActivityManager: Start proc 4038:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-17 14:01:26.125   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:01:26.125  2741  2775 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:26.126  2741  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 14:01:26.127  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:26.127  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:26.128  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:26.128  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:26.129  2741  2741 D HeadsetService: Received stop request...Stopping profile...
08-17 14:01:26.131  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:26.133  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:26.135   873   873 D BluetoothHeadset: Proxy object disconnected
,08-17 14:01:26.135   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:26.135   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:26.136  2741  2741 D A2dpService: Received stop request...Stopping profile...
08-17 14:01:26.136  2741  2895 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:01:26.136  1913  2040 D BluetoothHeadset: Proxy object disconnected
,08-17 14:01:26.137  1360  1376 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:26.138  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:26.140   873   873 D BluetoothA2dp: Proxy object disconnected
,08-17 14:01:26.141  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-17 14:01:26.141  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-17 14:01:26.142  2741  2741 D HidService: Received stop request...Stopping profile...
08-17 14:01:26.142  2741  2741 D HidService: Stopping Bluetooth HidService
08-17 14:01:26.143  2741  2741 D HealthService: Received stop request...Stopping profile...
08-17 14:01:26.144  2741  2741 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:26.144  2741  2741 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:26.144  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:26.144  2741  2741 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:26.145   873  1880 D DhcpClient: Clearing IP address
08-17 14:01:26.145  2741  2741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:01:26.145  2741  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 14:01:26.146  2741  2741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:26.146   373   871 D CommandListener: Setting iface cfg
08-17 14:01:26.146  2741  2741 D PanService: Received stop request...Stopping profile...
08-17 14:01:26.146  2741  2869 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:26.146  2741  2869 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:26.147  2741  2869 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:26.147  2741  2775 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 14:01:26.147  2741  2741 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 14:01:26.147  2741  2741 D BluetoothMapService: stop()
08-17 14:01:26.148  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-17 14:01:26.148  2741  2741 D BluetoothMapAppObserver: deinitObservers()
08-17 14:01:26.148  1360  1360 D HidProfile: Bluetooth service disconnected
08-17 14:01:26.148  2741  2741 D BluetoothMapAppObserver: removeReceiver()
,08-17 14:01:26.148  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 14:01:26.148  1360  1360 D PanProfile: Bluetooth service disconnected
08-17 14:01:26.151  1545  2186 V NativeCrypto: Read error: ssl=0xaec25400: I/O error during system call, Connection timed out
,08-17 14:01:26.152   873  1885 D DhcpClient: Receive thread stopped
08-17 14:01:26.151   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:01:26.154  1545  2186 V NativeCrypto: SSL shutdown failed: ssl=0xaec25400: I/O error during system call, Broken pipe
,08-17 14:01:26.149  2741  2741 V BluetoothAdapterState: isTurningOff()=true
,08-17 14:01:26.155  2741  2741 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:26.156  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:26.156  2741  2741 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:26.156  1360  1360 D BluetoothMap: Proxy object disconnected
,08-17 14:01:26.156  1360  1360 D MapProfile: Bluetooth service disconnected
08-17 14:01:26.156   873  1951 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-17 14:01:26.157   873  1872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-17 14:01:26.157  2741  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 14:01:26.157  2741  2869 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:26.157  2741  2741 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:26.157  2741  2741 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:26.157  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:26.157  2741  2741 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:26.157  2741  2741 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:01:26.157  2741  2741 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:01:26.158  2741  2741 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:26.158  2741  2741 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:26.158  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:26.158  2741  2741 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:26.157  2741  2869 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 14:01:26.159  2741  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 14:01:26.161  2741  2869 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:26.161  2741  2869 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:26.161  2741  2869 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 14:01:26.161  2741  2741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 14:01:26.161  2741  2869 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:26.161  2741  2775 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 14:01:26.161  2741  2741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:01:26.163   873  1872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-17 14:01:26.164  2741  2741 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:26.164  2741  2741 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:26.164  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:26.164  2741  2741 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:26.164  2741  2741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:01:26.164  2741  2741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:01:26.164   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-17 14:01:26.164   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-17 14:01:26.165  2741  2741 D BluetoothMapService: MAP Service closeService in
08-17 14:01:26.165   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 14:01:26.166  2741  2741 V BluetoothAdapterState: isTurningOff()=true
,08-17 14:01:26.166  2741  2741 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:26.166  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:26.166  2741  2741 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:26.166  2741  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 14:01:26.166  2741  2767 D BluetoothAdapterProperties: Setting state to 15
08-17 14:01:26.166  2741  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 14:01:26.166  2741  2741 D BluetoothMapService: cleanup()
08-17 14:01:26.166  2741  2741 D BluetoothMapService: MAP Service closeService in
08-17 14:01:26.167  1913  1925 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 14:01:26.167  1360  1382 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:01:26.167  2741  2767 I BluetoothAdapterState: Entering BleOnState
08-17 14:01:26.168  1360  2005 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:01:26.169   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:26.169  1360  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:01:26.172   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:26.172   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 14:01:26.172   396   396 E Parcel  : Reading a NULL string not supported here.
,08-17 14:01:26.172   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 14:01:26.172   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 14:01:26.173   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 14:01:26.174   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:26.174   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:26.175  1360  2005 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:01:26.175   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:01:26.176  1360  2005 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:26.176  1360  2005 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:26.177  2741  2767 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 14:01:26.177  2741  2767 D BluetoothAdapterProperties: Setting state to 16
08-17 14:01:26.177  2741  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 14:01:26.178  2741  2767 D BluetoothAdapterProperties: onBleDisable
08-17 14:01:26.178  2741  2770 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-17 14:01:26.179  2741  2869 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 14:01:26.179  2741  2869 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:26.179  2741  2767 I BluetoothAdapterState: Entering PendingCommandState
08-17 14:01:26.181  2741  2775 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:26.186   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 14:01:26.186  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:26.186  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:26.183   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:01:26.186  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.187  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:26.189  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:26.189  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:26.189  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.189  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:26.189   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:01:26.191  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:26.192  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:26.195  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:26.196  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:26.199  2190  2293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:01:26.217  4038  4038 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 14:01:26.223   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:01:26.227  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:01:26.232   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7969eaa:true
,08-17 14:01:26.235  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:26.251   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:01:26.251   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-17 14:01:26.252   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:26.258   873   884 I ActivityManager: Start proc 4056:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 14:01:26.261   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:01:26.265  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:26.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:26.268  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:26.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:26.273  3489  3489 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e2622e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 14:01:26.280  4038  4038 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 14:01:26.283  4038  4038 D BluetoothMap: Create BluetoothMap proxy object
,08-17 14:01:26.292  4038  4038 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 14:01:26.298  4056  4056 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 14:01:26.308  4038  4038 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:26.319   873  1932 I ActivityManager: Killing 3489:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 14:01:26.329   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-17 14:01:26.330   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 14:01:26.383  2741  2775 I bt_hci  : shut_down
,08-17 14:01:26.383  2741  2792 D bt_hwcfg: hw_epilog_process
,08-17 14:01:26.395  2741  2792 I bt_vendor: low_power_mode_cb
,08-17 14:01:26.414  2741  2792 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-17 14:01:26.414  2741  2792 I bt_vendor: epilog_cb
08-17 14:01:26.414  2741  2792 I bt_hci  : epilog_finished_callback
,08-17 14:01:26.417  2741  2775 I bt_hci_h4: hal_close
,08-17 14:01:26.418  2741  2775 I bt_userial_vendor: device fd = 51 close
,08-17 14:01:26.524  4056  4056 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 14:01:26.524  4056  4056 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 14:01:26.524  4056  4056 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:26.524  4056  4056 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 14:01:26.524  4,056  4056 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:26.524  4056  4056 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 1,4:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.524  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:26.525  4056  4056 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:26.525  4056  4056 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:26.525  4056  4056 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:26.525  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:26.563  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 14:01:26.565   873  1568 I ActivityManager: Start proc 4090:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-17 14:01:26.566   873  1568 I ActivityManager: Killing 3558:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 14:01:26.614  2741  2770 D bt_stack_manager: event_shut_down_stack finished.
08-17 14:01:26.615  2741  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-17 14:01:26.616  2741  2767 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 14:01:26.616  2741  2741 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:01:26.617  2741  2741 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:01:26.617  2741  2741 D BtGatt.GattService: stop()
08-17 14:01:26.617  2741  2741 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 14:01:26.619  2741  2741 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:26.619  2741  2741 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:26.619  2741  2741 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:01:26.620  2741  2741 V BluetoothAdapterState: isBleTurningOff()=true
08-17 14:01:26.620  2741  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-17 14:01:26.620  2741  2767 D BluetoothAdapterProperties: Setting state to 10
,08-17 14:01:26.620  2741  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 14:01:26.621  2741  2767 I BluetoothAdapterState: Entering OffState
,08-17 14:01:26.622   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 14:01:26.632  4090  4090 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-17 14:01:26.635  2741  2741 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 14:01:26.636  2741  2741 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 14:01:26.636  2741  2741 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 14:01:26.636  2741  2770 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 14:01:26.639  2741  2770 D bt_stack_manager: event_clean_up_stack finished.
,08-17 14:01:26.647  2741  2741 I art     : System.exit called, status: 0
,08-17 14:01:26.647  2741  2741 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 14:01:26.711   873   884 I ActivityManager: Process com.android.bluetooth (pid 2741) has died
,08-17 14:01:26.931  4090  4110 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-17 14:01:26.931  4090  4110 I Babel_SMS: MmsConfig.loadMmsSettings
,08-17 14:01:26.932  4090  4110 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-17 14:01:26.940  4090  4110 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 14:01:26.967  4090  4110 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-17 14:01:26.967  4090  4110 I Babel_SMS: MmsConfig.loadFromResources
,08-17 14:01:26.976  4090  4110 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 14:01:26.977  4090  4110 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-17 14:01:27.003  4090  4090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:01:27.005  4090  4090 I Babel_Crash: startup - clean
08-17 14:01:27.040  4090  4090 I Babel_telephony: TeleModule.launchCompleted
08-17 14:01:27.051   873  3845 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
08-17 14:01:27.065  4090  4090 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
08-17 14:01:27.073  4090  4090 W Babel   : BAM#gBA: invalid account id: -1
,08-17 14:01:27.074  4090  4090 W Babel   : BAM#gBA: invalid account id: -1
08-17 14:01:27.074  4090  4090 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-17 14:01:27.082  4090  4115 I Babel   : deleted: false for 0
,08-17 14:01:27.085   873  3845 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-17 14:01:27.115  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:01:27.141   873  1375 I ActivityManager: Start proc 4119:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-17 14:01:27.152  4038  4038 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:27.172  4056  4079 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 14:01:27.177  4090  4090 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 14:01:27.248  4090  4090 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 14:01:27.265  4090  4090 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 14:01:27.271  4090  4090 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 14:01:27.276  4090  4090 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 14:01:27.292  4119  4119 D AdapterServiceConfig: Adding HeadsetService
08-17 14:01:27.292  4119  4119 D AdapterServiceConfig: Adding A2dpService
08-17 14:01:27.292  4119  4119 D AdapterServiceConfig: Adding HidService
08-17 14:01:27.292  4119  4119 D AdapterServiceConfig: Adding HealthService
,08-17 14:01:27.292  4119  4119 D AdapterServiceConfig: Adding PanService
,08-17 14:01:27.295  4119  4119 D AdapterServiceConfig: Adding GattService
,08-17 14:01:27.295  4119  4119 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 14:01:27.301  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:27.308  4090  4090 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 14:01:27.330   873  1932 I ActivityManager: Killing 3591:android.process.acore/u0a5 (adj 15): empty #17
,08-17 14:01:27.368   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a288062:true
,08-17 14:01:27.379  4090  4090 I vclib   : onServiceConnected
,08-17 14:01:27.388  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:01:27.394  1741  1741 D SystemUpdateService: onCreate
,08-17 14:01:27.400  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 14:01:27.405  1741  4131 I SystemUpdateService: active receiver: enabled
,08-17 14:01:27.420  1741  4131 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 14:01:27.423  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 14:01:27.432  1741  4131 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 14:01:27.432  1741  4131 I SystemUpdateService: now status is 0 (complete)
,08-17 14:01:27.433  1741  4131 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 14:01:27.434  1741  4131 I SystemUpdateService: file has been verified
,08-17 14:01:27.437  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 14:01:27.438  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 14:01:27.442  1741  4131 I SystemUpdateService: OTA package size = 12249756
,08-17 14:01:27.443  1741  2412 I iu.UploadsManager: num queued entries: 0
,08-17 14:01:27.445  1741  2412 I iu.UploadsManager: num updated entries: 0
,08-17 14:01:27.448  1741  2412 I iu.SyncManager: NEXT; no task
,08-17 14:01:27.449  1741  4131 I SystemUpdateService: showing system update notification
,08-17 14:01:27.457   873   883 I ActivityManager: Start proc 4133:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 14:01:27.474  1741  1741 D SystemUpdateService: onDestroy
,08-17 14:01:27.487  4133  4133 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 14:01:27.490  4133  4133 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:27.495  4133  4133 D SprintDMHelper: simOperator: 
,08-17 14:01:27.495  4133  4133 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 14:01:27.511   873  1946 I ActivityManager: Start proc 4145:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 14:01:27.513   873  1946 I ActivityManager: Killing 3813:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 14:01:27.666   873  1688 I ActivityManager: Start proc 4160:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 14:01:27.672  4090  4159 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 14:01:27.676   873   883 I ActivityManager: Killing 3828:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 14:01:27.750  4160  4160 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 14:01:27.810  4160  4160 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 14:01:27.810  4160  4160 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 14:01:27.810  4160  4160 I GAv4    :   adb logcat -s GAv4
,08-17 14:01:27.826  4160  4160 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 14:01:27.833  4160  4160 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 14:01:27.861  4160  4177 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 14:01:27.972  4160  4160 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 14:01:28.009  4160  4160 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 14:01:28.018  4160  4160 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7321-7324)
,08-17 14:01:28.018  4160  4160 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:01:28.033  4160  4160 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {341b2de}
,08-17 14:01:28.033  4160  4160 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:01:28.034  4160  4160 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 14:01:28.046  4160  4160 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 14:01:28.048  4160  4160 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 14:01:28.060  4160  4160 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 14:01:28.073  4160  4160 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 14:01:28.073  4160  4160 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 14:01:28.073  4160  4160 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 14:01:28.073  4160  4160 I Adreno  : Build Date                       : 10/20/15
08-17 14:01:28.073  4160  4160 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 14:01:28.073  4160  4160 I Adreno  : Local Branch                     : M14
08-17 14:01:28.073  4160  4160 I Adreno  : Remote Branch                    : 
08-17 14:01:28.073  4160  4160 I Adreno  : Remote Branch                    : 
08-17 14:01:28.073  4160  4160 I Adreno  : Reconstruct Branch               : 
,08-17 14:01:28.137  4160  4160 I NSApplication: Starting up...
,08-17 14:01:28.146  4160  4206 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 14:01:28.185   873  1952 I ActivityManager: Start proc 4211:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 14:01:28.187   873  1952 I ActivityManager: Killing 3779:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-17 14:01:28.293  4211  4211 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 14:01:28.496   873  1375 I ActivityManager: Killing 2250:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 14:01:29.119   873  1951 D WifiService: setWifiEnabled: true pid=3957, uid=10000
,08-17 14:01:29.119   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:29.131   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 14:01:29.141  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:29.142  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:29.142  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:29.143  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:29.146  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:29.146  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:29.146  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:29.148  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:29.171   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 14:01:29.172   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 14:01:29.173   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 14:01:29.173   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 14:01:29.174   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 14:01:29.174   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 14:01:29.174   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 14:01:29.189   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 14:01:29.190   373   871 D CommandListener: Setting iface cfg
,08-17 14:01:29.190   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=14.00 rxSuccessRate=17.25 delta 1000 -> 994
08-17 14:01:29.191   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 14:01:29.191   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 14:01:29.194   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 14:01:29.195   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 14:01:29.216   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 14:01:29.217   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:01:29.226   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 14:01:29.275   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 14:01:29.278  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 14:01:29.695  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 14:01:29.735  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 14:01:29.738  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 14:01:29.743   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:01:29.760   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:01:29.760   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:01:29.761   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 14:01:29.783   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:01:29.794   373   871 D CommandListener: Setting iface cfg
,08-17 14:01:29.795   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 14:01:29.810   873  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 14:01:29.811   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 14:01:29.820   873  4235 D DhcpClient: Receive thread started
,08-17 14:01:29.901   873  1307 E native  : do suspend false
,08-17 14:01:29.921   873  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 14:01:29.934   873  4235 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172683, domain null
,08-17 14:01:29.936   873  1880 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172683 seconds
,08-17 14:01:29.940   873  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 14:01:29.954   873  4235 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 14:01:29.955   873  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 14:01:29.962   373   871 D CommandListener: Setting iface cfg
,08-17 14:01:29.974   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 14:01:29.974   873  1880 D DhcpClient: Scheduling renewal in 86399s
,08-17 14:01:29.991   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 14:01:29.994   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 14:01:29.994   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:29.996   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 14:01:30.001   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 14:01:30.012   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 14:01:30.095   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 14:01:30.095   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 14:01:30.098   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 14:01:30.100   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 14:01:30.102   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 14:01:30.112   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 14:01:30.118   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 14:01:30.118   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 14:01:30.118   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:30.118   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 14:01:30.118   873  1309 D ConnectivityService:    accepting network in place of null
08-17 14:01:30.119   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:01:30.120   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:01:30.130   873  4234 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139436, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 14:01:30.169   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:01:30.217   873  4233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:80a::200e
,08-17 14:01:30.219   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:01:30.231   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 14:01:30.231   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:30.238   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 14:01:30.240   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:01:30.265  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:30.265  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:30.265  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:30.265  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:30.268  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:30.268  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:30.268  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:30.269  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:30.276  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:01:30.278  1741  1741 D SystemUpdateService: onCreate
,08-17 14:01:30.281  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 14:01:30.283  1741  4246 I SystemUpdateService: active receiver: enabled
,08-17 14:01:30.293   873  4233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:01:30 GMT], X-Android-Received-Millis=[1471435290292], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471435290263]}
,08-17 14:01:30.296   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 14:01:30.296   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-17 14:01:30.296   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 14:01:30.297   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 14:01:30.299  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 14:01:30.304  1741  4246 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 14:01:30.308  1741  2412 I iu.UploadsManager: num queued entries: 0
,08-17 14:01:30.308  1741  4246 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 14:01:30.309  1741  4246 I SystemUpdateService: now status is 0 (complete)
,08-17 14:01:30.309  1741  4246 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 14:01:30.309  1741  4246 I SystemUpdateService: file has been verified
08-17 14:01:30.310  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 14:01:30.310  1741  4246 I SystemUpdateService: OTA package size = 12249756
08-17 14:01:30.310  1741  2412 I iu.UploadsManager: num updated entries: 0
08-17 14:01:30.311  1741  2412 I iu.SyncManager: NEXT; no task
08-17 14:01:30.311  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 14:01:30.314  4133  4133 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:30.315  1741  4251 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 14:01:30.315  1741  4251 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 14:01:30.316  1741  4251 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 14:01:30.321  4133  4133 D SprintDMHelper: simOperator: 
,08-17 14:01:30.321  4133  4133 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-17 14:01:30.321  1741  4246 I SystemUpdateService: showing system update notification
,08-17 14:01:30.329  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:30.334  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:30.355  1741  1741 D SystemUpdateService: onDestroy
,08-17 14:01:30.361  1545  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 14:01:30.361  1545  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 14:01:30.361  1545  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:30.361  1545  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:30.372  1741  4251 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-17 14:01:30.493  4090  4253 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 14:01:30.503  1545  2127 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 14:01:30.503  1545  2127 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 14:01:30.503  1545  2127 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:01:30.503  1545  2127 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:30.521  3647  4257 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 14:01:30.521  3647  4257 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jdm.a(PG:82)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jcs.o(PG:406)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jcn.a(PG:1379)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jcs.i(PG:143)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at blb.a(PG:3937)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at czp.a(PG:18188)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at czp.a(PG:9081)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at czq.run(PG:1686)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:01:30.521  3647  4257 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jdj.a(PG:4091)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jdj.a(PG:1125)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jdm.a(PG:77)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	... 12 more
08-17 14:01:30.521  3647  4257 E HttpOperation: Caused by: faj: BadAuthentication
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at fal.a(PG:38)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	at jdj.a(PG:4089)
08-17 14:01:30.521  3647  4257 E HttpOperation: 	... 14 more
,08-17 14:01:30.563  1545  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 14:01:30.564  1545  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 14:01:30.564  1545  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:30.564  1545  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:30.579  3647  4257 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 14:01:30.579  3647  4257 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jdm.a(PG:82)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jcs.o(PG:406)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jcn.a(PG:1379)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jcs.i(PG:143)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at hec.a(PG:42)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at hee.a(PG:102)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at czr.a(PG:65)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at kka.a(PG:108)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at czp.a(PG:19176)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at czp.a(PG:9081)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at czq.run(PG:1686)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:01:30.579  3647  4257 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jdj.a(PG:4091)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jdj.a(PG:1125)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jdm.a(PG:77)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	... 15 more
08-17 14:01:30.579  3647  4257 E HttpOperation: Caused by: faj: BadAuthentication
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at fal.a(PG:38)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	at jdj.a(PG:4089)
08-17 14:01:30.579  3647  4257 E HttpOperation: 	... 17 more
,08-17 14:01:30.579  3647  4257 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 14:01:30.579  3647  4257 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at hec.a(PG:42)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at hee.a(PG:102)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at czr.a(PG:65)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at kka.a(PG:108)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	... 15 more
08-17 14:01:30.579  3647  4257 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at fal.a(PG:38)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 14:01:30.579  3647  4257 E ExperimentLoader: 	... 17 more
,08-17 14:01:30.698   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 130553, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 14:01:31.231   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 14:01:32.063   873  1952 I ActivityManager: Killing 3852:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-17 14:01:32.125   873  1688 D WifiService: setWifiEnabled: false pid=3957, uid=10000
,08-17 14:01:32.125   873  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:32.159  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 14:01:32.167   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 14:01:32.168   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 14:01:32.169   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:01:32.169   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:01:32.187   873  1880 D DhcpClient: Clearing IP address
,08-17 14:01:32.188   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:01:32.195  1545  4259 V NativeCrypto: Read error: ssl=0xaec25400: I/O error during system call, Connection timed out
,08-17 14:01:32.199  1545  4259 V NativeCrypto: SSL shutdown failed: ssl=0xaec25400: I/O error during system call, Broken pipe
,08-17 14:01:32.204   873  1932 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-17 14:01:32.205   873  4233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-17 14:01:32.205   873  4233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:80a::200e
08-17 14:01:32.206   373   871 D CommandListener: Setting iface cfg
,08-17 14:01:32.208   873  4235 D DhcpClient: Receive thread stopped
,08-17 14:01:32.214   873  4233 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:80a::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-17 14:01:32.214   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-17 14:01:32.215   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:32.216   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-17 14:01:32.227   396   396 E Parcel  : Reading a NULL string not supported here.
,08-17 14:01:32.226   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 14:01:32.230   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:01:32.234   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:01:32.235   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 14:01:32.235   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 14:01:32.242   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:32.245   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 14:01:32.248  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:32.248  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:32.248  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.248  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:32.249  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:32.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:32.249  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.249  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:32.251   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:01:32.251  2190  2293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:01:32.275   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:01:32.315   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:01:32.317   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 14:01:32.318   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:32.321   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:01:32.325  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:32.327  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:32.335  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:01:32.337  1741  1741 D SystemUpdateService: onCreate
,08-17 14:01:32.340  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 14:01:32.343  1741  4271 I SystemUpdateService: active receiver: enabled
,08-17 14:01:32.349  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 14:01:32.354  1741  2412 I iu.UploadsManager: num queued entries: 0
08-17 14:01:32.354  1741  2412 I iu.UploadsManager: num updated entries: 0
08-17 14:01:32.355  1741  2412 I iu.SyncManager: NEXT; no task
,08-17 14:01:32.355  1741  4271 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 14:01:32.358  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 14:01:32.359  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 14:01:32.360  4133  4133 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:32.364  4133  4133 D SprintDMHelper: simOperator: 
,08-17 14:01:32.364  4133  4133 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 14:01:32.375  1741  4271 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 14:01:32.380  1741  4271 I SystemUpdateService: now status is 0 (complete)
,08-17 14:01:32.386  4090  4274 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 14:01:32.384  1741  4271 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 14:01:32.387  1741  4271 I SystemUpdateService: file has been verified
,08-17 14:01:32.392  1741  4271 I SystemUpdateService: OTA package size = 12249756
,08-17 14:01:32.400  1741  4271 I SystemUpdateService: showing system update notification
,08-17 14:01:32.407  1741  1741 D SystemUpdateService: onDestroy
,08-17 14:01:32.441   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-17 14:01:32.442   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 14:01:35.177   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20a4f2c:true
,08-17 14:01:35.177  4119  4119 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 14:01:35.182  4119  4119 I bt_bluedroid: init
,08-17 14:01:35.183  4119  4278 I BluetoothAdapterState: Entering OffState
,08-17 14:01:35.185  4119  4279 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 14:01:35.185  4119  4279 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 14:01:35.185  4119  4279 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:01:35.185  4119  4279 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 14:01:35.186  4119  4119 I bt_bluedroid: get_profile_interface socket
08-17 14:01:35.188  4119  4119 I bt_bluedroid: get_profile_interface sdp
,08-17 14:01:35.192  4119  4130 I bt_bluedroid: config_hci_snoop_log
,08-17 14:01:35.193  4119  4282 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 14:01:35.195  4119  4282 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:01:35.196   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 14:01:35.207  4119  4278 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 14:01:35.208  4119  4278 D BluetoothAdapterProperties: Setting state to 14
08-17 14:01:35.208  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 14:01:35.213  4119  4278 D BluetoothBondStateMachine: make
,08-17 14:01:35.216  4119  4283 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:01:35.224  4119  4278 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:01:35.224  4119  4119 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 14:01:35.227  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:35.228  4119  4119 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 14:01:35.228  4119  4119 D BtGatt.GattService: Received start request. Starting profile...
08-17 14:01:35.229  4119  4119 D BtGatt.GattService: start()
,08-17 14:01:35.229  4119  4119 I bt_bluedroid: get_profile_interface gatt
08-17 14:01:35.230  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
08-17 14:01:35.230  4119  4119 D BtGatt.AdvertiseManager: advertise manager created
,08-17 14:01:35.241  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:35.241  4119  4119 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:35.241  4119  4119 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 14:01:35.242  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:35.242  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 14:01:35.243  4119  4278 I bt_bluedroid: enable,
08-17 14:01:35.244  4119  4279 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 14:01:35.244  4119  4279 I bt_hci  : start_up
,08-17 14:01:35.257  4119  4279 I bt_vendor: alloc value 0xb3939189
,08-17 14:01:35.258  4119  4279 I bt_vendor: init
,08-17 14:01:35.258  4119  4279 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-17 14:01:35.258  4119  4279 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 14:01:35.364  4119  4279 D bt_hci  : start_up starting async portion
,08-17 14:01:35.365  4119  4286 I bt_hci  : event_finish_startup
,08-17 14:01:35.365  4119  4286 I bt_hci_h4: hal_open
08-17 14:01:35.366  4119  4286 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 14:01:35.373  4119  4286 I bt_userial_vendor: device fd = 51 open
,08-17 14:01:35.407  4119  4286 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:01:35.439  4119  4286 D bt_hwcfg: Chipset BCM4354A2
,08-17 14:01:35.440  4119  4286 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 14:01:35.440  4119  4286 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 14:01:36.108  4119  4286 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 14:01:36.109  4119  4286 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 14:01:36.109  4119  4286 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 14:01:36.226  4119  4286 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:01:36.227  4119  4286 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 14:01:36.257  4119  4286 I bt_hwcfg: vendor lib fwcfg completed
,08-17 14:01:36.257  4119  4286 I bt_vendor: firmware callback
08-17 14:01:36.257  4119  4286 I bt_hci  : firmware_config_callback
,08-17 14:01:36.269  4119  4288 I bt_btu  : btu_task pending for preload complete event
,08-17 14:01:36.269  4119  4288 I bt_btu_task: Bluetooth chip preload is complete
,08-17 14:01:36.269  4119  4288 I bt_btu  : btu_task received preload complete event
,08-17 14:01:36.282  4119  4288 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 14:01:36.282  4119  4288 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:01:36.283  4119  4288 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:01:36.283  4119  4288 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:01:36.283  4119  4288 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:01:36.284  4119  4288 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:01:36.284  4119  4288 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:01:36.284  4119  4288 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:01:36.284  4119  4288 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 14:01:36.285  4119  4288 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:01:36.285  4119  4288 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 14:01:36.285  4119  4288 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:01:36.285  4119  4288 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:01:36.286  4119  4288 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:01:36.286  4119  4288 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 14:01:36.420  4119  4288 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-17 14:01:36.421  4119  4288 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-17 14:01:36.432  4119  4282 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 14:01:36.435  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 14:01:36.436  4119  4282 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 14:01:36.443  4119  4282 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:01:36.448  4119  4282 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:01:36.448  4119  4282 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:01:36.448  4119  4282 D bt_hci  : do_postload posting postload work item
,08-17 14:01:36.449  4119  4286 I bt_hci  : event_postload
,08-17 14:01:36.449  4119  4286 I bt_vendor: sco_config_cb
,08-17 14:01:36.449  4119  4286 I bt_hci  : sco_config_callback postload finished.
08-17 14:01:36.450  4119  4282 D bt_bte_conf: Device ID record 1 : primary
,08-17 14:01:36.451  4119  4282 D bt_bte_conf:   vendorId            = 000f
08-17 14:01:36.451  4119  4282 D bt_bte_conf:   vendorIdSource      = 0001
08-17 14:01:36.451  4119  4282 D bt_bte_conf:   product             = 1200
,08-17 14:01:36.451  4119  4282 D bt_bte_conf:   version             = 1436
,08-17 14:01:36.451  4119  4282 D bt_bte_conf:   clientExecutableURL = 
08-17 14:01:36.451  4119  4282 D bt_bte_conf:   serviceDescription  = 
08-17 14:01:36.451  4119  4282 D bt_bte_conf:   documentationURL    = 
08-17 14:01:36.451  4119  4282 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 14:01:36.452  4119  4279 D bt_stack_manager: event_start_up_stack finished
,08-17 14:01:36.452  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 14:01:36.452  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:36.452  4119  4278 D BluetoothAdapterProperties: Setting state to 15
08-17 14:01:36.452  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 14:01:36.453  4119  4278 I BluetoothAdapterState: Entering BleOnState
,08-17 14:01:36.455  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:36.457  4119  4286 I bt_vendor: low_power_mode_cb
08-17 14:01:36.461  4119  4278 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 14:01:36.461  4119  4278 D BluetoothAdapterProperties: Setting state to 11
,08-17 14:01:36.461  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 14:01:36.467  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
08-17 14:01:36.468  4119  4119 D HeadsetService: Received start request. Starting profile...
,08-17 14:01:36.472  4119  4119 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 14:01:36.473  4119  4119 D HeadsetStateMachine: make
,08-17 14:01:36.475  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:36.476  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:36.486  4119  4278 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:01:36.486  4119  4119 D HeadsetStateMachine: max_hf_connections = 1
08-17 14:01:36.486  4119  4119 I bt_bluedroid: get_profile_interface handsfree
08-17 14:01:36.487  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 14:01:36.487  4119  4282 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 14:01:36.490  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:36.491  4119  4119 D A2dpService: Received start request. Starting profile...
,08-17 14:01:36.493  4119  4119 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 14:01:36.493  4119  4119 I bt_bluedroid: get_profile_interface avrcp
,08-17 14:01:36.500  4119  4119 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:01:36.500  4119  4119 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:01:36.501  4119  4119 D A2dpStateMachine: make
,08-17 14:01:36.503  4119  4119 I bt_bluedroid: get_profile_interface a2dp
,08-17 14:01:36.504  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 14:01:36.505  4119  4297 D A2dpStateMachine: Enter Disconnected: -2
08-17 14:01:36.506  4119  4119 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:01:36.507  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:36.509  4119  4119 D HidService: Received start request. Starting profile...
08-17 14:01:36.510  4119  4119 I bt_bluedroid: get_profile_interface hidhost
08-17 14:01:36.510  4119  4282 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-17 14:01:36.510  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-17 14:01:36.510  4119  4119 D HidService: setHidService(): set to: null
08-17 14:01:36.511  4119  4119 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:01:36.512  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
08-17 14:01:36.512  4119  4119 D HealthService: Received start request. Starting profile...
,08-17 14:01:36.513  4038  4038 D BluetoothInputDevice: Proxy object connected
08-17 14:01:36.513  4038  4038 D HidProfile: Bluetooth service connected
08-17 14:01:36.514  4119  4119 I bt_bluedroid: get_profile_interface health
08-17 14:01:36.516  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:36.516  4119  4119 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 14:01:36.518  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:36.519  4119  4119 D PanService: Received start request. Starting profile...
,08-17 14:01:36.519  4038  4038 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:01:36.520  4119  4119 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:01:36.520  4119  4119 I bt_bluedroid: get_profile_interface pan
08-17 14:01:36.520  4038  4038 D PanProfile: Bluetooth service connected
,08-17 14:01:36.520  4119  4282 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 14:01:36.522  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:36.524  4119  4119 D BluetoothMapService: Received start request. Starting profile...
08-17 14:01:36.524  4038  4038 D BluetoothMap: Proxy object connected
,08-17 14:01:36.524  4119  4119 D BluetoothMapService: start()
08-17 14:01:36.524  4038  4038 D MapProfile: Bluetooth service connected
,08-17 14:01:36.524  4038  4038 D BluetoothMap: getConnectedDevices()
08-17 14:01:36.525  4038  4038 D BluetoothMap: Bluetooth is Not enabled
08-17 14:01:36.526  4119  4119 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 14:01:36.527  4119  4119 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-17 14:01:36.527  4119  4119 D BluetoothMapAppObserver: createReceiver()
,08-17 14:01:36.528  4119  4119 D BluetoothMapAppObserver: initObservers()
,08-17 14:01:36.528  4119  4119 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 14:01:36.534  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:36.534  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:36.534  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:36.535  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:36.536  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:36.536  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:36.536  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:36.536  4119  4295 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 14:01:36.536  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:36.537  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:01:36.540  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:36.541  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 14:01:36.541  4119  4278 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:01:36.541  4119  4278 D BluetoothAdapterProperties: State =  11
08-17 14:01:36.541  4119  4278 D BluetoothAdapterProperties: Setting state to 12
,08-17 14:01:36.541  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 14:01:36.542  4119  4278 I BluetoothAdapterState: Entering OnState
08-17 14:01:36.542  1913  1926 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:36.543  4119  4282 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:01:36.544  4119  4282 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:01:36.544  1360  1382 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:36.547  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:36.548  1360  4051 D BluetoothPan: onBluetoothStateChange on: true
,08-17 14:01:36.550  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 14:01:36.550  1360  1360 D PanProfile: Bluetooth service connected
08-17 14:01:36.550  4038  4048 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:01:36.550  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:36.550   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:36.550  1360  2005 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:01:36.552  1360  1360 D BluetoothInputDevice: Proxy object connected
08-17 14:01:36.552  1360  1360 D HidProfile: Bluetooth service connected
,08-17 14:01:36.552   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:01:36.553   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:01:36.553   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:36.553  1360  1376 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:36.555  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:36.556  1360  1360 D BluetoothMap: Proxy object connected
08-17 14:01:36.556  1360  1360 D MapProfile: Bluetooth service connected
,08-17 14:01:36.556  1360  1360 D BluetoothMap: getConnectedDevices()
08-17 14:01:36.556  4038  4049 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:01:36.557   873   873 D BluetoothA2dp: Proxy object connected
08-17 14:01:36.557  4038  4048 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:01:36.558  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:36.559  4119  4119 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 14:01:36.559  4038  4049 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 14:01:36.559  4119  4119 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 14:01:36.559  1360  1382 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:36.560  1360  2005 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:01:36.561  4119  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:36.562  1360  1360 D BluetoothA2dp: Proxy object connected
,08-17 14:01:36.564   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 14:01:36.565  4119  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:36.567  4119  4119 D ObexServerSockets: Succeed to create listening sockets 
08-17 14:01:36.567  4119  4119 D ObexServerSockets0: startAccept()
08-17 14:01:36.567  4038  4038 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 14:01:36.567  4119  4119 D ObexServerSockets0: prepareForNewConnect()
08-17 14:01:36.568  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:36.569  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:36.571  4038  4038 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 14:01:36.571  4119  4119 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 14:01:36.572  4119  4119 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 14:01:36.572  4119  4305 D ObexServerSockets0: Accepting socket connection...
08-17 14:01:36.572  4119  4119 D BluetoothMapService: onReceive
,08-17 14:01:36.572  4119  4119 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:36.572  4119  4119 D BluetoothMapService: STATE_ON
,08-17 14:01:36.574  4119  4306 D ObexServerSockets0: Accepting socket connection...
,08-17 14:01:36.579  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:01:36.583  4038  4038 D BluetoothA2dp: Proxy object connected
,08-17 14:01:36.586  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:36.591  4038  4038 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:36.599  1360  1360 D BluetoothPbap: Proxy object connected
,08-17 14:01:36.599  1360  1360 D PbapServerProfile: Bluetooth service connected
08-17 14:01:36.599  4038  4038 D BluetoothPbap: Proxy object connected
08-17 14:01:36.600  4038  4038 D PbapServerProfile: Bluetooth service connected
,08-17 14:01:36.608  4119  4119 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 14:01:36.608  4119  4119 D ObexServerSockets0: prepareForNewConnect()
,08-17 14:01:36.610  4119  4310 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:36.634  4119  4314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:36.635  4119  4314 I BtOppRfcommListener: Accept thread started.
,08-17 14:01:36.645   873   873 D BluetoothHeadset: Proxy object connected
08-17 14:01:36.645   873   873 D BluetoothHeadset: Proxy object connected
08-17 14:01:36.646   873   873 D BluetoothHeadset: Proxy object connected
,08-17 14:01:36.646  1913  2040 D BluetoothHeadset: Proxy object connected
08-17 14:01:36.647  1360  1382 D BluetoothHeadset: Proxy object connected
08-17 14:01:36.647  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:36.650   873   890 D BluetoothHeadset: Proxy object connected
,08-17 14:01:36.653   873   890 D BluetoothHeadset: Proxy object connected
,08-17 14:01:36.653   873   890 D BluetoothHeadset: Proxy object connected
,08-17 14:01:36.659  1360  4051 D BluetoothHeadset: Proxy object connected
08-17 14:01:36.659  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:36.676  4038  4048 D BluetoothHeadset: Proxy object connected
,08-17 14:01:36.678  4038  4038 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:38.124   873  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-17 14:01:38.141  4119  4278 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 14:01:38.142  4119  4278 D BluetoothAdapterProperties: Setting state to 13
08-17 14:01:38.142  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:01:38.144  4119  4278 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 14:01:38.151  4119  4278 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:01:38.161  4119  4119 D BluetoothMapService: onReceive
,08-17 14:01:38.161  4119  4119 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:38.161  4119  4119 D BluetoothMapService: STATE_TURNING_OFF
,08-17 14:01:38.162  4119  4282 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:38.162  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:01:38.162  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:38.163  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:38.162  4119  4119 D BluetoothMapService: MAP Service closeService in
,08-17 14:01:38.163  4119  4119 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 14:01:38.163  4119  4119 D ObexServerSockets0: shutdown(block = true)
,08-17 14:01:38.165  4119  4305 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 14:01:38.167  4119  4119 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:01:38.166  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.167  4119  4306 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 14:01:38.167  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:38.168  4119  4119 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:01:38.168  4119  4291 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 14:01:38.170  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 14:01:38.169  4119  4119 D HeadsetService: Received stop request...Stopping profile...
08-17 14:01:38.172  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:38.172  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:38.173  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.174  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:38.174   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:38.174   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:38.174  4038  4049 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:38.175   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:38.175  1913  1925 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:38.176  1360  2005 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:38.176  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:38.177  4119  4119 D A2dpService: Received stop request...Stopping profile...
08-17 14:01:38.177  4119  4297 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:01:38.178  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:38.179   873   873 D BluetoothA2dp: Proxy object disconnected
08-17 14:01:38.180  4119  4119 I BtOppRfcommListener: stopping Accept Thread
08-17 14:01:38.180  4119  4314 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, ,read ret: -1
08-17 14:01:38.181  4119  4314 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:01:38.182  4119  4119 D HidService: Received stop request...Stopping profile...
08-17 14:01:38.183  4119  4119 D HidService: Stopping Bluetooth HidService
08-17 14:01:38.184  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-17 14:01:38.184  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-17 14:01:38.185  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-17 14:01:38.186  1360  1360 D HidProfile: Bluetooth service disconnected
08-17 14:01:38.186  4119  4119 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:38.186  4119  4119 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:38.186  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:38.186  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:38.187  4038  4038 D HeadsetProfile: Bluetooth service disconnected
08-17 14:01:38.187  4038  4038 D BluetoothA2dp: Proxy object disconnected
,08-17 14:01:38.188  4119  4119 D HealthService: Received stop request...Stopping profile...
,08-17 14:01:38.190  4038  4038 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:38.192  4038  4038 D BluetoothInputDevice: Proxy object disconnected
,08-17 14:01:38.192  4038  4038 D HidProfile: Bluetooth service disconnected
,08-17 14:01:38.193  4119  4119 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:01:38.193  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-17 14:01:38.193  4119  4288 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:38.194  4119  4288 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:38.194  4119  4288 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 14:01:38.195  4119  4282 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 14:01:38.195  4119  4119 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:38.196  4119  4119 D PanService: Received stop request...Stopping profile...
,08-17 14:01:38.197  4038  4038 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 14:01:38.197  4038  4038 D PanProfile: Bluetooth service disconnected
08-17 14:01:38.197  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:01:38.197  1360  1360 D PanProfile: Bluetooth service disconnected
08-17 14:01:38.197  4119  4119 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:38.197  4119  4119 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:38.197  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:01:38.198  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:38.198  4119  4119 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:01:38.198  4119  4119 D BluetoothMapService: stop()
08-17 14:01:38.199  4119  4119 D BluetoothMapAppObserver: deinitObservers()
08-17 14:01:38.199  4119  4119 D BluetoothMapAppObserver: removeReceiver()
,08-17 14:01:38.200  1360  1360 D BluetoothMap: Proxy object disconnected
08-17 14:01:38.200  1360  1360 D MapProfile: Bluetooth service disconnected
,08-17 14:01:38.201  4038  4038 D BluetoothMap: Proxy object disconnected
08-17 14:01:38.201  4038  4038 D MapProfile: Bluetooth service disconnected
,08-17 14:01:38.201  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 14:01:38.201  4119  4288 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:38.201  4119  4288 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:01:38.202  4119  4288 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:38.202  4119  4288 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:38.202  4119  4288 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:38.202  4119  4288 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:38.205  4119  4119 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:38.205  4119  4119 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:38.205  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:38.205  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:38.206  4119  4119 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:01:38.206  4119  4119 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 14:01:38.206  4119  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 14:01:38.208  4119  4119 V BluetoothAdapterState: isTurningOff()=true
,08-17 14:01:38.208  4119  4119 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:38.208  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:38.208  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:38.208  4119  4119 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:01:38.208  4119  4282 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-17 14:01:38.208  4119  4119 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-17 14:01:38.209  4119  4119 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:38.209  4119  4119 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:38.209  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:38.209  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:38.210  4119  4119 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 14:01:38.210  4119  4119 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:01:38.210  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:38.210  4119  4119 D BluetoothMapService: MAP Service closeService in
08-17 14:01:38.211  4119  4119 V BluetoothAdapterState: isTurningOff()=true
08-17 14:01:38.211  4119  4119 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:38.211  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:38.211  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:38.211  4119  4119 D BluetoothMapService: cleanup()
08-17 14:01:38.211  4119  4119 D BluetoothMapService: MAP Service closeService in
,08-17 14:01:38.211  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 14:01:38.212  4119  4278 D BluetoothAdapterProperties: Setting state to 15
,08-17 14:01:38.212  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 14:01:38.212  4119  4278 I BluetoothAdapterState: Entering BleOnState
08-17 14:01:38.212  1913  1926 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:38.213  1360  1360 D BluetoothPbap: Proxy object disconnected
08-17 14:01:38.213  1360  1360 D PbapServerProfile: Bluetooth service disconnected
08-17 14:01:38.213  4038  4049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:38.214  4038  4038 D BluetoothPbap: Proxy object disconnected
,08-17 14:01:38.214  4038  4038 D PbapServerProfile: Bluetooth service disconnected
,08-17 14:01:38.214  1360  2005 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 14:01:38.215  1360  1376 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:01:38.216  4038  4048 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 14:01:38.216   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:38.216  1360  4051 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 14:01:38.218   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:38.218   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:38.218   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:38.218  1360  1382 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:01:38.219  4038  4049 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:01:38.221  4038  4318 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 14:01:38.222  4038  4048 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:01:38.222  4038  4049 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:38.223  1360  2005 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:38.223  1360  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 14:01:38.224  4119  4278 D BluetoothAdapterState: Current state: BLE ON, message: 20,
08-17 14:01:38.224  4119  4278 D BluetoothAdapterProperties: Setting state to 16
08-17 14:01:38.224  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 14:01:38.224  4119  4278 D BluetoothAdapterProperties: onBleDisable
08-17 14:01:38.225  4119  4278 I BluetoothAdapterState: Entering PendingCommandState
08-17 14:01:38.225  4119  4279 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-17 14:01:38.225  4119  4282 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:38.226  4119  4288 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 14:01:38.226  4119  4288 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 14:01:38.229  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:38.230  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 14:01:38.230  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:38.232  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:38.233  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:38.236  4038  4038 D DockEventReceiver: finishStartingService: stopping service
08-17 14:01:38.236  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:38.426  4119  4282 I bt_hci  : shut_down
,08-17 14:01:38.427  4119  4286 D bt_hwcfg: hw_epilog_process
,08-17 14:01:38.428  4119  4286 I bt_vendor: low_power_mode_cb
,08-17 14:01:38.450  4119  4286 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 14:01:38.450  4119  4286 I bt_vendor: epilog_cb
08-17 14:01:38.450  4119  4286 I bt_hci  : epilog_finished_callback
,08-17 14:01:38.462  4119  4282 I bt_hci_h4: hal_close
,08-17 14:01:38.465  4119  4282 I bt_userial_vendor: device fd = 51 close
,08-17 14:01:38.585  4119  4279 D bt_stack_manager: event_shut_down_stack finished.
,08-17 14:01:38.586  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 14:01:38.592  4119  4119 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:01:38.591  4119  4278 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 14:01:38.593  4119  4119 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:01:38.594  4119  4119 D BtGatt.GattService: stop()
,08-17 14:01:38.594  4119  4119 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 14:01:38.599  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:38.600  4119  4119 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:01:38.600  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:38.600  4119  4119 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 14:01:38.602  4119  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-17 14:01:38.603  4119  4278 D BluetoothAdapterProperties: Setting state to 10
08-17 14:01:38.603  4119  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 14:01:38.605  4119  4278 I BluetoothAdapterState: Entering OffState
,08-17 14:01:38.607   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 14:01:38.630  4119  4119 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 14:01:38.630  4119  4119 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 14:01:38.631  4119  4279 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 14:01:38.635  4119  4279 D bt_stack_manager: event_clean_up_stack finished.
08-17 14:01:38.636  4119  4119 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 14:01:38.639  4119  4119 I art     : System.exit called, status: 0
,08-17 14:01:38.640  4119  4119 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 14:01:38.686   873  1951 I ActivityManager: Process com.android.bluetooth (pid 4119) has died
,08-17 14:01:40.840   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 14:01:40.855  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-17 14:01:40.861   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 14:01:40.861   873   893 I Adreno  : Build Date                       : 10/20/15
08-17 14:01:40.861   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 14:01:40.861   873   893 I Adreno  : Local Branch                     : M14
08-17 14:01:40.861   873   893 I Adreno  : Remote Branch                    : 
08-17 14:01:40.861   873   893 I Adreno  : Remote Branch                    : 
08-17 14:01:40.861   873   893 I Adreno  : Reconstruct Branch               : 
,08-17 14:01:40.914   280   349 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (424 us)
,08-17 14:01:41.138  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:01:41.139  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:41.555  3957  3957 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 14:01:41.555  3957  3957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 14:01:41.607  3957  3957 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@64cfb70 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d742c38, 16908290=android.view.AbsSavedState$1@d742c38}, android:focusedViewId=100}]}],
08-17 14:01:41.607  3957  3957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 14:01:41.607  3957  3957 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 14:01:41.607  3957  3957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 14:01:41.610   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 14:01:41.622   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 14:01:41.626   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 14:01:41.626   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-17 14:01:41.627   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 14:01:41.856   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,08-17 14:01:41.860   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-17 14:01:41.861   873  1332 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,08-17 14:01:41.867   873   893 I DreamManagerService: Entering dreamland.
,08-17 14:01:41.868   873   893 I PowerManagerService: Dozing...
08-17 14:01:41.870   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 14:01:41.912   377  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 14:01:41.912   377  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 14:01:41.916   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:01:41.919   873  1307 E native  : do suspend false
,08-17 14:01:41.925  1900  4327 D NfcService: Discovery configuration equal, not updating.
,08-17 14:01:41.947   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:01:41.951   873  1307 E native  : do suspend true
,08-17 14:01:42.051   377  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 14:01:42.052   377  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 14:01:44.147  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:44.147  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b401411 added. We now have 6 listener(s)
08-17 14:01:44.148  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:44.153  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:44.153  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68be976 added. We now have 7 listener(s)
08-17 14:01:44.153  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:44.155  3957  4008 I System.out: IsBluetoothEnabled
,08-17 14:01:44.167  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:44.206   873   890 I ActivityManager: Start proc 4333:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 14:01:44.341  4333  4333 D AdapterServiceConfig: Adding HeadsetService
,08-17 14:01:44.342  4333  4333 D AdapterServiceConfig: Adding A2dpService
,08-17 14:01:44.342  4333  4333 D AdapterServiceConfig: Adding HidService
08-17 14:01:44.342  4333  4333 D AdapterServiceConfig: Adding HealthService
,08-17 14:01:44.342  4333  4333 D AdapterServiceConfig: Adding PanService
08-17 14:01:44.343  4333  4333 D AdapterServiceConfig: Adding GattService
,08-17 14:01:44.343  4333  4333 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 14:01:44.361   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9a6884:true
,08-17 14:01:44.362  4333  4333 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 14:01:44.367  4333  4333 I bt_bluedroid: init
,08-17 14:01:44.367  4333  4345 I BluetoothAdapterState: Entering OffState
,08-17 14:01:44.369  4333  4346 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 14:01:44.370  4333  4346 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 14:01:44.370  4333  4346 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 14:01:44.370  4333  4346 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 14:01:44.371  4333  4333 I bt_bluedroid: get_profile_interface socket
,08-17 14:01:44.373  4333  4333 I bt_bluedroid: get_profile_interface sdp
,08-17 14:01:44.376  4333  4349 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 14:01:44.378  4333  4344 I bt_bluedroid: config_hci_snoop_log
,08-17 14:01:44.379  4333  4349 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:01:44.379   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 14:01:44.386  4333  4345 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 14:01:44.387  4333  4345 D BluetoothAdapterProperties: Setting state to 14
,08-17 14:01:44.387  4333  4345 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 14:01:44.391  4333  4345 D BluetoothBondStateMachine: make
,08-17 14:01:44.395  4333  4350 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:01:44.402  4333  4345 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:01:44.403  4333  4333 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 14:01:44.408  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:44.409  4333  4333 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:01:44.410  4333  4333 D BtGatt.GattService: Received start request. Starting profile...
,08-17 14:01:44.410  4333  4333 D BtGatt.GattService: start()
08-17 14:01:44.410  4333  4333 I bt_bluedroid: get_profile_interface gatt
,08-17 14:01:44.411  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:44.411  4333  4333 D BtGatt.AdvertiseManager: advertise manager created
,08-17 14:01:44.421  4333  4333 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:44.421  4333  4333 V BluetoothAdapterState: isTurningOn()=false
08-17 14:01:44.421  4333  4333 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 14:01:44.422  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:44.422  4333  4345 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 14:01:44.423  4333  4345 I bt_bluedroid: enable
,08-17 14:01:44.423  4333  4346 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 14:01:44.424  4333  4346 I bt_hci  : start_up
,08-17 14:01:44.435  4333  4346 I bt_vendor: alloc value 0xb39b0189
,08-17 14:01:44.435  4333  4346 I bt_vendor: init
08-17 14:01:44.435  4333  4346 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 14:01:44.435  4333  4346 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 14:01:44.543  4333  4346 D bt_hci  : start_up starting async portion
,08-17 14:01:44.543  4333  4353 I bt_hci  : event_finish_startup
08-17 14:01:44.544  4333  4353 I bt_hci_h4: hal_open
,08-17 14:01:44.544  4333  4353 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 14:01:44.554  4333  4353 I bt_userial_vendor: device fd = 51 open
,08-17 14:01:44.586  4333  4353 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:01:44.616  4333  4353 D bt_hwcfg: Chipset BCM4354A2
,08-17 14:01:44.617  4333  4353 D bt_hwcfg: Target name = [BCM4354A2]
08-17 14:01:44.618  4333  4353 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 14:01:45.183  4333  4353 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-17 14:01:45.185  4333  4353 D bt_hwcfg: Settlement delay -- 100 ms
08-17 14:01:45.185  4333  4353 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 14:01:45.302  4333  4353 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:01:45.303  4333  4353 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 14:01:45.332  4333  4353 I bt_hwcfg: vendor lib fwcfg completed
,08-17 14:01:45.333  4333  4353 I bt_vendor: firmware callback
,08-17 14:01:45.333  4333  4353 I bt_hci  : firmware_config_callback
,08-17 14:01:45.351  4333  4355 I bt_btu  : btu_task pending for preload complete event
08-17 14:01:45.351  4333  4355 I bt_btu_task: Bluetooth chip preload is complete
08-17 14:01:45.351  4333  4355 I bt_btu  : btu_task received preload complete event
,08-17 14:01:45.360  4333  4355 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 14:01:45.360  4333  4355 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:01:45.360  4333  4355 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 14:01:45.361  4333  4355 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:01:45.361  4333  4355 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 14:01:45.362  4333  4355 I         : BTE_InitTraceLevels -- TRC_A2D
,08-17 14:01:45.362  4333  4355 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 14:01:45.363  4333  4355 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:01:45.364  4333  4355 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 14:01:45.365  4333  4355 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:01:45.365  4333  4355 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 14:01:45.366  4333  4355 I         : BTE_InitTraceLevels -- TRC_GATT
,08-17 14:01:45.366  4333  4355 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:01:45.367  4333  4355 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:01:45.368  4333  4355 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 14:01:45.494  4333  4355 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-17 14:01:45.495  4333  4355 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-17 14:01:45.505  4333  4349 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 14:01:45.507  4333  4349 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 14:01:45.508  4333  4349 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 14:01:45.510  4333  4349 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:01:45.515  4333  4349 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:01:45.516  4333  4349 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:01:45.516  4333  4349 D bt_hci  : do_postload posting postload work item
08-17 14:01:45.516  4333  4353 I bt_hci  : event_postload
,08-17 14:01:45.516  4333  4353 I bt_vendor: sco_config_cb
08-17 14:01:45.517  4333  4353 I bt_hci  : sco_config_callback postload finished.
08-17 14:01:45.520  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:45.523  4333  4349 D bt_bte_conf: Device ID record 1 : primary
08-17 14:01:45.524  4333  4349 D bt_bte_conf:   vendorId            = 000f
,08-17 14:01:45.525  4333  4353 I bt_vendor: low_power_mode_cb
08-17 14:01:45.524  4333  4349 D bt_bte_conf:   vendorIdSource      = 0001
,08-17 14:01:45.525  4333  4349 D bt_bte_conf:   product             = 1200
08-17 14:01:45.526  4333  4349 D bt_bte_conf:   version             = 1436
08-17 14:01:45.527  4333  4349 D bt_bte_conf:   clientExecutableURL = 
,08-17 14:01:45.527  4333  4349 D bt_bte_conf:   serviceDescription  = 
,08-17 14:01:45.528  4333  4349 D bt_bte_conf:   documentationURL    = 
,08-17 14:01:45.528  4333  4349 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 14:01:45.529  4333  4346 D bt_stack_manager: event_start_up_stack finished
08-17 14:01:45.530  4333  4345 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 14:01:45.531  4333  4345 D BluetoothAdapterProperties: Setting state to 15
08-17 14:01:45.531  4333  4345 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 14:01:45.534  4333  4345 I BluetoothAdapterState: Entering BleOnState
,08-17 14:01:45.536  4333  4345 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 14:01:45.536  4333  4345 D BluetoothAdapterProperties: Setting state to 11
08-17 14:01:45.536  4333  4345 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 14:01:45.541  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:45.542  4333  4333 D HeadsetService: Received start request. Starting profile...
08-17 14:01:45.545  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:45.548  4333  4333 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:01:45.548  4333  4333 D HeadsetStateMachine: make
,08-17 14:01:45.559  4333  4333 D HeadsetStateMachine: max_hf_connections = 1
08-17 14:01:45.559  4333  4333 I bt_bluedroid: get_profile_interface handsfree
,08-17 14:01:45.559  4333  4349 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 14:01:45.560  4333  4349 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-17 14:01:45.561  4333  4345 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:01:45.564  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:45.564  4333  4333 D A2dpService: Received start request. Starting profile...
,08-17 14:01:45.566  4333  4333 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:01:45.567  4333  4333 I bt_bluedroid: get_profile_interface avrcp
,08-17 14:01:45.574  4333  4333 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:01:45.574  4333  4333 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:01:45.574  4333  4333 D A2dpStateMachine: make
,08-17 14:01:45.576  4333  4333 I bt_bluedroid: get_profile_interface a2dp
,08-17 14:01:45.576  4333  4349 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 14:01:45.581  4333  4364 D A2dpStateMachine: Enter Disconnected: -2
,08-17 14:01:45.583  4333  4333 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:01:45.584  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:45.584  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
08-17 14:01:45.584  4333  4333 D HidService: Received start request. Starting profile...
08-17 14:01:45.585  4333  4333 I bt_bluedroid: get_profile_interface hidhost
08-17 14:01:45.585  4333  4349 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-17 14:01:45.585  4333  4349 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 14:01:45.585  4333  4333 D HidService: setHidService(): set to: null
,08-17 14:01:45.586  4333  4333 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:01:45.586  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:45.587  4333  4333 D HealthService: Received start request. Starting profile...
08-17 14:01:45.590  4333  4333 I bt_bluedroid: get_profile_interface health
,08-17 14:01:45.591  4333  4333 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 14:01:45.592  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:45.593  4333  4333 D PanService: Received start request. Starting profile...
,08-17 14:01:45.593  4333  4333 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 14:01:45.593  4333  4333 I bt_bluedroid: get_profile_interface pan
08-17 14:01:45.593  4333  4349 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 14:01:45.602  4333  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:45.603  4333  4333 D BluetoothMapService: Received start request. Starting profile...
08-17 14:01:45.603  4333  4333 D BluetoothMapService: start()
,08-17 14:01:45.607  4333  4333 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 14:01:45.608  4333  4333 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 14:01:45.608  4333  4333 D BluetoothMapAppObserver: createReceiver()
08-17 14:01:45.609  4333  4333 D BluetoothMapAppObserver: initObservers()
08-17 14:01:45.609  4333  4333 D BluetoothMapAppObserver: getEnabledAccountItems()
08-17 14:01:45.617  4333  4333 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:45.617  4333  4333 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:45.617  4333  4333 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:45.617  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:45.620  4333  4362 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 14:01:45.620  4333  4333 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:01:45.620  4333  4333 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:45.620  4333  4333 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:45.621  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:45.621  4333  4333 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:45.621  4333  4333 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:01:45.621  4333  4333 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:45.621  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:45.623  4333  4333 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:45.623  4333  4333 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:45.623  4333  4333 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:45.623  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:01:45.624  4333  4333 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:45.625  4333  4333 V BluetoothAdapterState: isTurningOn()=true
08-17 14:01:45.625  4333  4333 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:45.625  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:45.625  4333  4333 V BluetoothAdapterState: isTurningOff()=false
08-17 14:01:45.625  4333  4333 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:01:45.626  4333  4333 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:01:45.626  4333  4333 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:01:45.627  4333  4345 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 14:01:45.627  4333  4345 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:01:45.627  4333  4345 D BluetoothAdapterProperties: State =  11
,08-17 14:01:45.631  4333  4349 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:01:45.631  4333  4345 D BluetoothAdapterProperties: Setting state to 12
08-17 14:01:45.631  4333  4349 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:01:45.631  4333  4345 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 14:01:45.632  4333  4345 I BluetoothAdapterState: Entering OnState
08-17 14:01:45.632  1913  2040 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:45.635  4038  4049 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:01:45.638  4333  4333 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 14:01:45.639  1360  1376 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:45.639  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:45.639  4333  4333 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-17 14:01:45.641  4333  4333 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:45.642  1360  1382 D BluetoothPan: onBluetoothStateChange on: true
,08-17 14:01:45.643  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:45.644  4038  4318 D BluetoothInputDevice: onBluetoothStateChange: up=true,
,08-17 14:01:45.645  4333  4333 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:45.646  4333  4333 D ObexServerSockets: Succeed to create listening sockets 
,08-17 14:01:45.646  4333  4333 D ObexServerSockets0: startAccept()
,08-17 14:01:45.647  4333  4333 D ObexServerSockets0: prepareForNewConnect()
,08-17 14:01:45.647   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:01:45.648  1360  2005 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:01:45.649  4333  4333 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 14:01:45.649  4333  4333 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 14:01:45.650   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:01:45.651   873   873 D BluetoothA2dp: Proxy object connected
,08-17 14:01:45.652  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:01:45.652  1360  1360 D PanProfile: Bluetooth service connected
08-17 14:01:45.652  4038  4038 D BluetoothA2dp: Proxy object connected
08-17 14:01:45.653  1360  1360 D BluetoothInputDevice: Proxy object connected
,08-17 14:01:45.653  1360  1360 D HidProfile: Bluetooth service connected
,08-17 14:01:45.653  4333  4370 D ObexServerSockets0: Accepting socket connection...
08-17 14:01:45.654  4333  4369 D ObexServerSockets0: Accepting socket connection...
08-17 14:01:45.651   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:01:45.654   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:45.654  1360  1382 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:01:45.656  4038  4038 D BluetoothInputDevice: Proxy object connected
08-17 14:01:45.657  4038  4038 D HidProfile: Bluetooth service connected
08-17 14:01:45.657  4038  4318 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:01:45.658  1360  1360 D BluetoothMap: Proxy object connected
,08-17 14:01:45.658  1360  1360 D MapProfile: Bluetooth service connected
08-17 14:01:45.658  1360  1360 D BluetoothMap: getConnectedDevices()
08-17 14:01:45.660  4038  4318 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 14:01:45.663  4038  4048 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:01:45.661  4038  4038 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 14:01:45.663  4038  4038 D PanProfile: Bluetooth service connected
,08-17 14:01:45.666  4038  4318 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:01:45.666  4038  4038 D BluetoothMap: Proxy object connected
,08-17 14:01:45.667  1360  4051 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:45.667  4038  4038 D MapProfile: Bluetooth service connected
08-17 14:01:45.667  4038  4038 D BluetoothMap: getConnectedDevices()
,08-17 14:01:45.667  1360  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:01:45.669  1360  1360 D BluetoothA2dp: Proxy object connected
,08-17 14:01:45.673  4333  4333 D BluetoothMapService: onReceive
,08-17 14:01:45.673  4333  4333 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:45.673  4333  4333 D BluetoothMapService: STATE_ON
,08-17 14:01:45.674   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 14:01:45.675  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:45.680  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:01:45.687  4038  4038 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:45.689  1545  1545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:45.698  4038  4038 D BluetoothPbap: Proxy object connected
,08-17 14:01:45.698  4038  4038 D PbapServerProfile: Bluetooth service connected
,08-17 14:01:45.698  4333  4333 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 14:01:45.698  4333  4333 D ObexServerSockets0: prepareForNewConnect()
,08-17 14:01:45.702  1360  1360 D BluetoothPbap: Proxy object connected
,08-17 14:01:45.703  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-17 14:01:45.712  4333  4376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:45.731  4333  4380 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:45.733  4333  4380 I BtOppRfcommListener: Accept thread started.
,08-17 14:01:45.736   873   873 D BluetoothHeadset: Proxy object connected
08-17 14:01:45.736   873   873 D BluetoothHeadset: Proxy object connected
08-17 14:01:45.737  4038  4049 D BluetoothHeadset: Proxy object connected
,08-17 14:01:45.737   873   873 D BluetoothHeadset: Proxy object connected
08-17 14:01:45.737  1913  1925 D BluetoothHeadset: Proxy object connected
08-17 14:01:45.738  4038  4038 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:45.738  1360  4051 D BluetoothHeadset: Proxy object connected
08-17 14:01:45.739  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:45.748   873   890 D BluetoothHeadset: Proxy object connected
,08-17 14:01:45.754   873   890 D BluetoothHeadset: Proxy object connected
,08-17 14:01:45.754   873   890 D BluetoothHeadset: Proxy object connected
,08-17 14:01:45.766  4038  4318 D BluetoothHeadset: Proxy object connected
,08-17 14:01:45.766  4038  4038 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:45.768  1360  2005 D BluetoothHeadset: Proxy object connected
,08-17 14:01:45.768  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-17 14:01:46.099  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:46.112  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:46.118  1545  1545 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:01:46.172  1545  2127 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 14:01:46.172  1545  2127 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 14:01:46.172  1545  2127 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:01:46.172  1545  2127 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:46.188  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:46.194  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:46.197  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:46.198  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f88b77 added. We now have 8 listener(s)
,08-17 14:01:46.198  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:46.205   873  1951 D WifiService: setWifiEnabled: false pid=3957, uid=10000
,08-17 14:01:46.205   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:46.218  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:46.219   873  1951 D WifiService: setWifiEnabled: true pid=3957, uid=10000
08-17 14:01:46.219   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:46.222  3609  3609 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 14:01:46.224  3609  3609 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 14:01:46.225  3609  3609 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-17 14:01:46.229   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:46.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:46.251  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:46.252  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:46.258   873  1307 D WifiConfigStore: loaded 0 passpoint configs
08-17 14:01:46.259   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-17 14:01:46.259   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 14:01:46.260   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 14:01:46.261   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 14:01:46.261   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 14:01:46.261   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-17 14:01:46.261  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:46.261  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-17 14:01:46.262  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 14:01:46.264  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@64cfb70 Bundle[{}],
08-17 14:01:46.266  3957  4008 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 14:01:46.266  3957  4008 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 14:01:46.267  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 14:01:46.267  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 14:01:46.268  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 14:01:46.268  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 14:01:46.273  3957  4008 I System.out: Running OutgoingSocketThread
,08-17 14:01:46.274  3957  4386 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 444)
,08-17 14:01:46.276  3957  4386 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37977
,08-17 14:01:46.276  3957  4386 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 14:01:46.283   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 14:01:46.284   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.28 rxSuccessRate=0.32 delta 1000 -> 1000
08-17 14:01:46.284   373   871 D CommandListener: Setting iface cfg
08-17 14:01:46.284   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 14:01:46.284   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-17 14:01:46.285   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 14:01:46.293   873  1307 E native  : do suspend true
,08-17 14:01:46.300   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 14:01:46.300   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 14:01:46.307   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 14:01:46.308   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:01:46.322   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 14:01:46.368   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 14:01:46.374  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 14:01:46.808  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 14:01:46.855  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 14:01:46.856  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 14:01:46.867   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:01:46.881   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:01:46.882   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 14:01:46.883   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:01:46.905   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:01:46.921   373   871 D CommandListener: Setting iface cfg
,08-17 14:01:46.922   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 14:01:46.929   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 14:01:46.964   873  4390 D DhcpClient: Receive thread started
,08-17 14:01:47.051   873  1307 E native  : do suspend false
,08-17 14:01:47.070   873  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 14:01:47.083   873  4390 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-17 14:01:47.084   873  1880 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-17 14:01:47.088   873  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 14:01:47.102   873  4390 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 14:01:47.103   873  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 14:01:47.108   373   871 D CommandListener: Setting iface cfg
,08-17 14:01:47.118   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 14:01:47.120   873  1880 D DhcpClient: Scheduling renewal in 86399s
,08-17 14:01:47.122   873  1307 E native  : do suspend true
,08-17 14:01:47.150   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 14:01:47.154   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 14:01:47.156   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 14:01:47.159   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 14:01:47.168   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 14:01:47.230   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 14:01:47.230   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102,
,08-17 14:01:47.233   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 14:01:47.236   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 14:01:47.239   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 14:01:47.256   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 14:01:47.267   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 14:01:47.267   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-17 14:01:47.267   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 14:01:47.267   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-17 14:01:47.269   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 14:01:47.268   873  1309 D ConnectivityService:    accepting network in place of null
,08-17 14:01:47.272   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:01:47.274  3957  4008 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 445)
08-17 14:01:47.274  3957  4008 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 445)
,08-17 14:01:47.277  3957  4008 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,08-17 14:01:47.278  3957  4008 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 14:01:47.278  3957  4008 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,08-17 14:01:47.279   873  4389 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 14:01:47.280  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.281  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65bd3e4 added. We now have 2 listener(s)
,08-17 14:01:47.282  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:01:47.283  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.283  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.283  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.283  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600e04d added. We now have 9 listener(s)
,08-17 14:01:47.283  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.284  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:01:47.286  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:47.292  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:47.294  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:47.294  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:47.295  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.295  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be06813 added. We now have 3 listener(s)
,08-17 14:01:47.297  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:01:47.297  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.297  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.297  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.297  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff44a50 added. We now have 10 listener(s)
,08-17 14:01:47.297  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.297  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:47.298  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:47.298  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:47.298  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.298  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.298  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:01:47.298  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.298  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65bd3e4 removed from the list
08-17 14:01:47.298  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.298  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600e04d removed from the list
,08-17 14:01:47.300  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:47.303  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:47.304  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:47.304  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.304  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.304  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:47.305  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.305  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:47.305  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:47.305  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600e04d not in the list
08-17 14:01:47.306  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.306  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.306  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:47.307  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.307  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.307  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff44a50 removed from the list
08-17 14:01:47.307  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.307  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.307  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.307  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.307  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be06813 removed from the list
08-17 14:01:47.308  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.308  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3883449 added. We now have 2 listener(s)
,08-17 14:01:47.310  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:01:47.310  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.310  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.310  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.310  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62b14e added. We now have 9 listener(s)
,08-17 14:01:47.310  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.311  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:01:47.313  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:47.320  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:47.323  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:47.323  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:47.324  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.324  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45bbb7c added. We now have 3 listener(s)
,08-17 14:01:47.325  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:47.328  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:47.328  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:01:47.328  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:01:47.328  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:01:47.328  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.328  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c16cc05 added. We now have 10 listener(s)
08-17 14:01:47.328  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.329  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:47.329  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:47.329  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:47.329  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:47.329  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:47.331   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 14:01:47.332  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:01:47.332  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:01:47.336  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:01:47.337  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:01:47.337  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:01:47.340  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:01:47.340  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:01:47.341  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:01:47.341  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:47.344  4333  4343 D BtGatt.GattService: registerClient() - UUID=24377c27-ad0b-43a8-96ff-3e0f657ef1ce
,08-17 14:01:47.345  4333  4349 D BtGatt.GattService: onClientRegistered() - UUID=24377c27-ad0b-43a8-96ff-3e0f657ef1ce, clientIf=5
08-17 14:01:47.346  3957  4004 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:01:47.347  4333  4344 D BtGatt.GattService: start scan with filters
,08-17 14:01:47.350  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:01:47.350  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 14:01:47.350  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:01:47.350  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:01:47.351  4333  4352 D BtGatt.ScanManager: handling starting scan
,08-17 14:01:47.351   873  4388 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:815::200e
,08-17 14:01:47.354  4333  4352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7a5b304
,08-17 14:01:47.358  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:47.358  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:47.359  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:01:47.360  4333  4349 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 14:01:47.360  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.360  4333  4352 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:01:47.361  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:01:47.365  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 14:01:47.365  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:47.365  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:01:47.365  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.365  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:01:47.365  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:01:47.365  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:01:47.366  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:01:47.366  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:47.366  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:01:47.366  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:01:47.367  4333  4349 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:01:47.367  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.367  4333  4352 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:01:47.367  4333  4352 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 14:01:47.367  3957  4008 D BluetoothAdapter: STATE_ON
08-17 14:01:47.369   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 14:01:47.369  4333  4343 D BtGatt.GattService: stopScan() - queue size =1,
08-17 14:01:47.370  4333  4344 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:01:47.371  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:47.371  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:01:47.371  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:01:47.372  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:01:47.372  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:01:47.373   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-17 14:01:47.373  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:47.373   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:47.373  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:01:47.373  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:01:47.373  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:01:47.376   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 14:01:47.378   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:01:47.383  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:47.385  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:47.385  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:47.385  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:01:47.389  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:47.389  4333  4349 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 14:01:47.389  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:47.389  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.389  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:47.389  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.389  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.389  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:47.389  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:01:47.390  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3883449 removed from the list
08-17 14:01:47.390  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.390  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62b14e removed from the list
08-17 14:01:47.390  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:01:47.390  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.390  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.390  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:47.391  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:47.392  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.392  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:47.392  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.392  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62b14e not in the list
08-17 14:01:47.392  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.392  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:47.393  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:47.393  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.393  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.393  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c16cc05 removed from the list
08-17 14:01:47.393  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.393  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.393  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.393  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.393  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45bbb7c removed from the list
08-17 14:01:47.393  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.394  4333  4349 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 14:01:47.394  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.394  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.394  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d2381 added. We now have 2 listener(s)
,08-17 14:01:47.396  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:01:47.396  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.396  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.396  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.396  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9f9c26 added. We now have 9 listener(s)
08-17 14:01:47.396  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:47.396  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:47.399  4333  4349 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 14:01:47.400  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.400  4333  4352 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:01:47.402  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:47.405  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:47.405  4333  4349 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:01:47.405  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.406  4333  4352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:01:47.406  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.406  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:01:47.406  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.407  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34dfe14 added. We now have 3 listener(s)
,08-17 14:01:47.408  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:01:47.409  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.409  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.409  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.409  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31776bd added. We now have 10 listener(s)
08-17 14:01:47.409  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:47.409  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:47.409  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:47.410  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:01:47.410  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 14:01:47.410  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:47.410  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:47.410  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:47.412  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:47.413  4333  4349 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:01:47.413  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.413  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:01:47.413  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:01:47.416  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:01:47.416  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:01:47.416  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:01:47.418  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:01:47.418  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:01:47.419  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:01:47.419  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:47.419  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:01:47.421  4333  4343 D BtGatt.GattService: registerClient() - UUID=3d70e4e3-d34d-4fb9-a658-0076d9d4275a
,08-17 14:01:47.421  4333  4349 D BtGatt.GattService: onClientRegistered() - UUID=3d70e4e3-d34d-4fb9-a658-0076d9d4275a, clientIf=5
,08-17 14:01:47.421  3957  3968 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:01:47.421  4333  4361 D BtGatt.GattService: start scan with filters
08-17 14:01:47.423  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:01:47.423  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:01:47.423  1741  1741 D SystemUpdateService: onCreate
08-17 14:01:47.423  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:01:47.423  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 14:01:47.424  4333  4352 D BtGatt.ScanManager: handling starting scan
08-17 14:01:47.425   873  4388 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:01:47 GMT], X-Android-Received-Millis=[1471435307425], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471435307395]}
,08-17 14:01:47.426  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:01:47.426   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 14:01:47.426   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 14:01:47.426   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 14:01:47.427   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 14:01:47.428  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:47.428  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:01:47.429  4333  4349 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:01:47.429  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.429  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 14:01:47.429  4333  4352 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 14:01:47.429  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 14:01:47.432  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:47.432  3957  4008 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 14:01:47.432  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:47.432  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:47.432  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:47.432  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.432  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.432  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 14:01:47.432  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:01:47.432  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d2381 removed from the list
08-17 14:01:47.432  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.433  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9f9c26 removed from the list
08-17 14:01:47.433  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:47.433  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:47.433  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.433  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 14:01:47.433  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.433  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:01:47.434  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.434  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:47.434  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.434  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9f9c26 not in the list
08-17 14:01:47.434  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:01:47.434  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:01:47.434  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:47.434  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:01:47.434  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:01:47.435  4333  4349 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:01:47.435  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.435  4333  4352 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:01:47.435  4333  4352 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 14:01:47.435  3957  4008 D BluetoothAdapter: STATE_ON
08-17 14:01:47.436  4333  4344 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:01:47.437  4333  4372 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:01:47.437  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:47.437  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:01:47.437  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 14:01:47.437  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:01:47.437  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:01:47.438  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:47.438  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:01:47.438  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:01:47.438  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:01:47.438  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.439  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:47.439  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:01:47.439  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:47.439  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:47.439  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.439  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.439  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31776bd removed from the list
08-17 14:01:47.439  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.439  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.439  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:47.439  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.439  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34dfe14 removed from the list
08-17 14:01:47.440  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.440  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d49c1b9 added. We now have 2 listener(s)
08-17 14:01:47.441  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:01:47.441  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.441  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:01:47.441  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.441  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8409fe added. We now have 9 listener(s)
08-17 14:01:47.441  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.442  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:47.444  4333  4349 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 14:01:47.445  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.445  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:47.449  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:47.449  4333  4349 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 14:01:47.449  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.451  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.451  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:47.451  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:01:47.452  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2fbac added. We now have 3 listener(s)
08-17 14:01:47.453  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:01:47.453  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.453  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.453  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.453  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bbc075 added. We now have 10 listener(s)
08-17 14:01:47.453  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.453  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:01:47.453  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:47.453  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:47.453  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:47.453  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:01:47.456  4333  4349 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:01:47.456  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:47.456  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.456  4333  4352 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:01:47.457  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:01:47.457  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:01:47.458  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:47.460  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:01:47.460  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:01:47.460  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:01:47.462  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-17 14:01:47.462  4333  4349 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 14:01:47.462  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.462  4333  4352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 14:01:47.463  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:01:47.463  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:01:47.463  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:01:47.463  3957  4008 D BluetoothAdapter: STATE_ON
,08-17 14:01:47.465  4333  4344 D BtGatt.GattService: registerClient() - UUID=67c55fca-eaf9-42cb-8cb6-fff14fee640a
08-17 14:01:47.465  4333  4349 D BtGatt.GattService: onClientRegistered() - UUID=67c55fca-eaf9-42cb-8cb6-fff14fee640a, clientIf=5
08-17 14:01:47.466  3957  3968 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:01:47.466  4333  4372 D BtGatt.GattService: start scan with filters
,08-17 14:01:47.467  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:01:47.468  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:01:47.468  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:01:47.468  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 14:01:47.468  4333  4349 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 14:01:47.468  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.469  4333  4352 D BtGatt.ScanManager: handling starting scan
,08-17 14:01:47.470  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:01:47.470  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:01:47.470  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:01:47.471  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:01:47.475  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:01:47.475  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:47.475  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:47.475  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.475  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.475  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:01:47.475  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.475  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d49c1b9 removed from the list
08-17 14:01:47.471  1741  4400 I SystemUpdateService: active receiver: enabled
,08-17 14:01:47.475  4333  4349 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:01:47.476  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.476  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.476  4333  4352 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 14:01:47.476  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8409fe removed from the list
08-17 14:01:47.476  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:47.476  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:01:47.477  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.477  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 14:01:47.477  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.477  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:47.478  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.478  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:47.478  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.478  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8409fe not in the list
,08-17 14:01:47.478  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:01:47.478  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:01:47.478  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:47.478  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 14:01:47.478  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:01:47.479  3957  4008 D BluetoothAdapter: STATE_ON
08-17 14:01:47.479  4333  4371 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:01:47.480  4333  4344 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:01:47.480  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:47.480  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 14:01:47.480  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:01:47.480  4333  4349 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:01:47.480  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.480  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:01:47.481  4333  4352 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 14:01:47.481  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:01:47.481  4333  4352 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 14:01:47.481  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 14:01:47.482  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:47.482  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:01:47.482  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:01:47.482  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:01:47.482  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.482  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 14:01:47.483  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:47.483  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:47.483  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:01:47.483  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:47.483  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:01:47.483  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.483  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bbc075 removed from the list
08-17 14:01:47.483  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:47.483  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.483  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.484  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.484  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2fbac removed from the list
08-17 14:01:47.484  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:47.484  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@714eef1 added. We now have 2 listener(s)
,08-17 14:01:47.485  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:01:47.485  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:47.485  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:47.485  4133  4133 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:47.485  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:47.486  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41d5ad6 added. We now have 9 listener(s)
,08-17 14:01:47.486  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:47.486  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:47.488  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:47.490  4333  4349 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 14:01:47.490  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:47.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:01:47.493  4133  4133 D SprintDMHelper: simOperator: 
,08-17 14:01:47.493  4133  4133 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 14:01:47.496  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:01:47.496  4333  4349 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 14:01:47.496  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.496  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:47.496  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:01:47.496  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71444 added. We now have 3 listener(s)
08-17 14:01:47.496  1741  2412 I iu.UploadsManager: num queued entries: 0
08-17 14:01:47.497  1741  2412 I iu.UploadsManager: num updated entries: 0
08-17 14:01:47.497  1741  2412 I iu.SyncManager: NEXT; no task
,08-17 14:01:47.498  1741  4403 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 14:01:47.499  1741  4403 W BaseAppContext: Using Auth Proxy for data requests.
08-17 14:01:47.499  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:01:47.499  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:01:47.499  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:01:47.499  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:47.499  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f8892d added. We now have 10 listener(s)
08-17 14:01:47.501  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:47.501  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:47.501  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:47.501  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:01:47.501  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:01:47.501  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.501  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:47.501  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:47.501  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@714eef1 removed from the list
08-17 14:01:47.501  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.501  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41d5ad6 removed from the list
,08-17 14:01:47.502  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:47.504  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:47.505  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:47.505  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.506  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:01:47.506  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.506  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.506  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:47.506  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.506  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41d5ad6 not in the list
,08-17 14:01:47.507  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.507  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.507  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:01:47.507  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:47.507  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:47.507  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f8892d removed from the list
08-17 14:01:47.507  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:01:47.507  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:47.508  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:47.508  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:01:47.508  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71444 removed from the list
,08-17 14:01:47.508  4333  4349 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 14:01:47.508  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.508  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-17 14:01:47.508  4333  4352 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:01:47.508  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 14:01:47.508  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 14:01:47.509  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:01:47.509  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 14:01:47.509  1741  4403 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
08-17 14:01:47.509  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:47.514  4333  4349 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:01:47.514  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:01:47.514  4333  4352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 14:01:47.517  3957  4406 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,08-17 14:01:47.517  3957  4406 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: My test thread name)
08-17 14:01:47.518  3957  4406 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 14:01:47.521  4333  4349 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 14:01:47.521  4333  4349 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:01:47.522  3957  4407 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,08-17 14:01:47.522  3957  4407 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
08-17 14:01:47.523  3957  4407 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 14:01:47.524  3957  4008 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 14:01:47.524  3957  4008 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 14:01:47.525  3957  4008 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 14:01:47.525  3957  4008 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 14:01:47.525  3957  4008 D com.test.thalitest.ThaliTestRunner: Total duration: 21853 ms
,08-17 14:01:47.526  1741  4400 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-17 14:01:47.526  3957  4008 I jxcore-log: Total number of executed tests:  80
08-17 14:01:47.526  3957  4008 I jxcore-log: 
08-17 14:01:47.527  3957  4008 I jxcore-log: Number of passed tests:  80
08-17 14:01:47.527  3957  4008 I jxcore-log: 
08-17 14:01:47.527  3957  4008 I jxcore-log: Number of failed tests:  0
08-17 14:01:47.527  3957  4008 I jxcore-log: 
08-17 14:01:47.527  3957  4008 I jxcore-log: Number of ignored tests:  0
08-17 14:01:47.527  3957  4008 I jxcore-log: 
08-17 14:01:47.527  3957  4008 I jxcore-log: Total duration:  21853
08-17 14:01:47.527  3957  4008 I jxcore-log: 
08-17 14:01:47.527  3957  4008 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 14:01:47.527  3957  4008 I jxcore-log: 
,08-17 14:01:47.531  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.531  3957  4008 I jxcore-log: 
08-17 14:01:47.534  3957  3957 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 14:01:47.535  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.535  3957  4008 I jxcore-log: 
08-17 14:01:47.536  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.536  3957  4008 I jxcore-log: 
08-17 14:01:47.536  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.536  3957  4008 I jxcore-log: 
08-17 14:01:47.538  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.538  3957  4008 I jxcore-log: 
08-17 14:01:47.539  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.539  3957  4008 I jxcore-log: 
08-17 14:01:47.542  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.542  3957  4008 I jxcore-log: 
08-17 14:01:47.543  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.543  3957  4008 I jxcore-log: 
08-17 14:01:47.544  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.544  3957  4008 I jxcore-log: 
08-17 14:01:47.544  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:01:47.544  3957  4008 I jxcore-log: 
08-17 14:01:47.545  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:01:47.545  3957  4008 I jxcore-log: 
08-17 14:01:47.546  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:01:47.546  3957  4008 I jxcore-log: 
08-17 14:01:47.546  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.546  3957  4008 I jxcore-log: 
08-17 14:01:47.547  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.547  3957  4008 I jxcore-log: 
08-17 14:01:47.548  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.548  3957  4008 I jxcore-log: 
08-17 14:01:47.548  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.548  3957  4008 I jxcore-log: 
08-17 14:01:47.549  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.549  3957  4008 I jxcore-log: 
08-17 14:01:47.549  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.549  3957  4008 I jxcore-log: 
08-17 14:01:47.550  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.550  3957  4008 I jxcore-log: 
08-17 14:01:47.550  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.550  3957  4008 I jxcore-log: 
08-17 14:01:47.551  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.551  3957  4008 I jxcore-log: 
08-17 14:01:47.551  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:47.551  3957  4008 I jxcore-log: 
08-17 14:01:47.552  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:01:47.552  3957  4008 I jxcore-log: 
08-17 14:01:47.552  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:01:47.552  3957  4008 I jxcore-log: 
08-17 14:01:47.553  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.553  3957  4008 I jxcore-log: 
08-17 14:01:47.553  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.553  3957  4008 I jxcore-log: 
08-17 14:01:47.554  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.554  3957  4008 I jxcore-log: 
08-17 14:01:47.556  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.556  3957  4008 I jxcore-log: 
08-17 14:01:47.557  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.557  3957  4008 I jxcore-log: 
08-17 14:01:47.558  2190  2666 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
08-17 14:01:47.558  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:47.558  3957  4008 I jxcore-log: 
08-17 14:01:47.563  1545  2274 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-17 14:01:47.563  1545  2274 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 14:01:47.563  1545  2274 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:01:47.564  1545  2274 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 14:01:47.573  1741  4400 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 14:01:47.573  1741  4400 I SystemUpdateService: now status is 0 (complete)
08-17 14:01:47.573  1741  4400 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 14:01:47.573  1741  4400 I SystemUpdateService: file has been verified
08-17 14:01:47.573  1741  4400 I SystemUpdateService: OTA package size = 12249756
08-17 14:01:47.575  1741  4403 E MDM     : [184] SitrepService.a: Error sending sitrep.
08-17 14:01:47.579  1741  4400 I SystemUpdateService: showing system update notification
,08-17 14:01:47.586  1741  1741 D SystemUpdateService: onDestroy
,08-17 14:01:47.640  4090  4405 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 14:01:47.886  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:01:47.888  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:01:47.888  3957  4008 I jxcore-log: 
,08-17 14:01:47.939  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:01:47.941  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:01:47.941  3957  4008 I jxcore-log: 
,08-17 14:01:47.983  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:01:47.985  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:01:47.985  3957  4008 I jxcore-log: 
,08-17 14:01:48.245  4412  4412 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 14:01:48.250  4412  4412 D AndroidRuntime: CheckJNI is OFF
,08-17 14:01:48.292  4412  4412 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 14:01:48.339  4412  4412 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 14:01:48.363  4412  4412 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 14:01:48.373   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 14:01:48.374   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 14:01:48.374   873   886 I ActivityManager: Killing 3957:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 14:01:48.479   873  1946 D GraphicsStats: Buffer count: 2
08-17 14:01:48.479   873  1568 I WindowState: WIN DEATH: Window{a0acdff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:01:48.479   873  1308 D WifiService: Client connection lost with reason: 4
,08-17 14:01:48.501   873   896 W PackageSettings: Skipping PackageSetting{92725c1 com.example.hello/10273} due to missing metadata
,08-17 14:01:48.536   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-17 14:01:48.536   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-17 14:01:48.536   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-17 14:01:48.536   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 14:01:48.536   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:48.536   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.536   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.536   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-17 14:01:48.537   873   886 I ActivityManager:   Force finishing activity ActivityRecord{770bdd4 u0 com.test.thalitest/.MainActivity t2}
,08-17 14:01:48.540   873   896 I art     : Starting a blocking GC Explicit
,08-17 14:01:48.547   873   883 W ActivityManager: Spurious death for ProcessRecord{29d5a22 0:com.test.thalitest/u0a0}, curProc for 3957: null
,08-17 14:01:48.578   873   896 I art     : Explicit concurrent mark sweep GC freed 16131(1084KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 703us total 37.395ms
,08-17 14:01:48.607   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 14:01:48.610  4412  4412 I art     : System.exit called, status: 0
,08-17 14:01:48.610  4412  4412 I AndroidRuntime: VM exiting with result code 0.
,08-17 14:01:48.633   873   896 I ActivityManager: Start proc 4423:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-17 14:01:48.634   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 14:01:48.654   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 14:01:48.657  4333  4333 D BluetoothMapAppObserver: onReceive
,08-17 14:01:48.657  4333  4333 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-17 14:01:48.666   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 14:01:48.672  1853  1853 I Keyboard.Facilitator: resetDictionaries() : en_US
08-17 14:01:48.672  3799  3799 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 14:01:48.684  2190  2237 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 14:01:48.697  1853  4438 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 14:01:48.700  1853  4438 I Decoder : createOrResetDecoder
,08-17 14:01:48.703  1913  1913 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 14:01:48.722   873  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-17 14:01:48.732   873  1945 I ActivityManager: Start proc 4439:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 14:01:48.753  1545  1545 I ConfigService: onCreate
,08-17 14:01:48.755   873   883 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3957 uid 10000
,08-17 14:01:48.760   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 14:01:48.761  1545  4451 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 14:01:48.761  1545  4451 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 14:01:48.761  1545  4451 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:01:48.763  1545  4451 W SQLiteOpenHelper: Opened config.db in read-only mode
08-17 14:01:48.767  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-17 14:01:48.777  1853  4438 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 14:01:48.788  4439  4439 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 14:01:48.815  1853  4438 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 14:01:48.820  1927  2007 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 14:01:48.825  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 14:01:48.825  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 14:01:48.834  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-17 14:01:48.834  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-17 14:01:48.837   873  1932 I ActivityManager: Start proc 4453:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-17 14:01:48.838  1927  2007 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 14:01:48.838  1927  2007 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1927
08-17 14:01:48.838  1927  2007 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.838  1927  2007 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.840   873  1375 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 14:01:48.841   873  4459 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:01:48.841   873  4459 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:01:48.841   873  4459 E DropBoxManagerService: 	... 5 more
08-17 14:01:48.844  1927  2007 I Process : Sending signal. PID: 1927 SIG: 9
,08-17 14:01:48.847   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-17 14:01:48.849  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-17 14:01:48.849  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-17 14:01:48.850  1853  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-17 14:01:48.852  1853  4438 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 14:01:48.852  1853  4438 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-17 14:01:48.853  1853  4438 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-17 14:01:48.853  1853  4438 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-17 14:01:48.853  1853  4438 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 14:01:48.867   873   885 E PackageManager: Failed to write settings, restoring backup
08-17 14:01:48.867   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 14:01:48.867   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 14:01:48.867   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 14:01:48.867   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 14:01:48.867   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 14:01:48.867   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:48.867   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.867   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 14:01:48.869   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-17 14:01:48.869   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 14:01:48.869   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:01:48.869   873   886 E DropBoxManagerService: 	... 13 more
,08-17 14:01:48.889  4439  4439 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 14:01:48.899  4439  4470 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-17 14:01:48.908   873  1945 I ActivityManager: Start proc 4472:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-17 14:01:48.921   873  1375 I WindowState: WIN DEATH: Window{69b33ed u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-17 14:01:48.921   873  3845 D GraphicsStats: Buffer count: 1
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.930  4439  4470 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 14:01:48.930  4439  4470 E AndroidRuntime: Process: android.process.acore, PID: 4439
08-17 14:01:48.930  4439  4470 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.930  4439  4470 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.933   873  3845 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1927) has died
08-17 14:01:48.933   873  3845 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-17 14:01:48.934   873  3845 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-17 14:01:48.951   873  1951 I ActivityManager: Start proc 4485:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.952  4439  4468 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:48.952  4439  4468 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:01:48.956   873  4491 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:01:48.956   873  4491 E DropBoxManagerService: 	... 5 more
08-17 14:01:48.960  4439  4470 I Process : Sending signal. PID: 4439 SIG: 9
,08-17 14:01:48.972   278   278 E lowmemorykiller: Error writing /proc/4439/oom_score_adj; errno=22
,08-17 14:01:48.982   278   278 E lowmemorykiller: Error writing /proc/4439/oom_score_adj; errno=22
,08-17 14:01:48.989  4472  4472 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 14:01:49.002  4485  4485 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:49.002  4485  4485 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:49.002  4485  4485 D AndroidRuntime: Shutting down VM
,08-17 14:01:49.009  1545  1545 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-17 14:01:49.010  1545  1545 D AndroidRuntime: Shutting down VM
08-17 14:01:49.010  4485  4485 E AndroidRuntime: FATAL EXCEPTION: main
08-17 14:01:49.010  4485  4485 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4485
08-17 14:01:49.010  4485  4485 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 14:01:49.010  4485  4485 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 14:01:49.010  4485  4485 E AndroidRuntime: 	... 10 more
08-17 14:01:49.010  1545  1545 E AndroidRuntime: FATAL EXCEPTION: main
08-17 14:01:49.010  1545  1545 E AndroidRuntime: Process: com.google.process.gapps, PID: 1545
08-17 14:01:49.010  1545  1545 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 14:01:49.010  1545  1545 E AndroidRuntime: 	... 8 more
08-17 14:01:49.011  1741  4498 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-17 14:01:49.012  1741  4498 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-17 14:01:49.013   873  1951 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 14:01:49.016   278   278 E lowmemorykiller: Error writing /proc/4439/oom_score_adj; errno=22
,08-17 14:01:49.017   873  4502 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:01:49.017   873  4502 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:01:49.017   873  4502 E DropBoxManagerService: 	... 5 more
08-17 14:01:49.017  1545  1545 I Process : Sending signal. PID: 1545 SIG: 9
08-17 14:01:49.018  4485  4485 I Process : Sending signal. PID: 4485 SIG: 9
,08-17 14:01:49.018   873  4501 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:01:49.018   873  4501 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:01:49.018   873  4501 E DropBoxManagerService: 	... 5 more
08-17 14:01:49.028   278   278 E lowmemorykiller: Error writing /proc/4439/oom_score_adj; errno=22
,08-17 14:01:49.038  1741  4498 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-17 14:01:49.038  1741  4498 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-17 14:01:49.045   873   883 I ActivityManager: Killing 3913:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-17 14:01:49.065   873  1308 D WifiService: Client connection lost with reason: 4
,08-17 14:01:49.076   873  1946 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4485) has died
,08-17 14:01:49.078   873  1946 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 14:01:49.081   873  1932 I ActivityManager: Process com.google.process.gapps (pid 1545) has died
,08-17 14:01:49.081   873  1932 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-17 14:01:49.081   873  1932 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-17 14:01:49.081   873  1932 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-17 14:01:49.082   873  1932 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,08-17 14:01:49.094   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
