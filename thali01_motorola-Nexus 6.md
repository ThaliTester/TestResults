#### Test 81418577ad1885e_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-02 12:07:41.643  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:07:41.665  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 12:07:41.671  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 12:07:41.730  1507  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-02 12:07:41.730  1507  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-02 12:07:41.730  1507  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:07:41.730  1507  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-02 12:07:41.762  3501  3501 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-02 12:07:41.762  3501  3501 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-02 12:07:41.763  3501  3501 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-02 12:07:42.292  3770  3770 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-02 12:07:42.297  3770  3770 D AndroidRuntime: CheckJNI is OFF
09-02 12:07:42.334  3770  3770 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-02 12:07:42.377  3770  3770 I Radio-JNI: register_android_hardware_Radio DONE
09-02 12:07:42.400  3770  3770 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-02 12:07:42.410   874  1905 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 12:07:42.469  2042  2052 W SearchService: Abort, client detached.
09-02 12:07:42.473  3770  3770 D AndroidRuntime: Shutting down VM
09-02 12:07:42.485  2042  2347 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@daf67c0
09-02 12:07:42.485  2042  2357 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-02 12:07:42.486  2042  2042 I HotwordDetector: Closing mic
09-02 12:07:42.495   874  2041 I ActivityManager: Start proc 3781:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-02 12:07:42.538   374  2359 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-02 12:07:42.539   374  2359 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-02 12:07:42.544   374  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-02 12:07:42.546  2042  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-02 12:07:42.546  2042  2356 I MicroRecognitionRnrImpl: Detection finished
09-02 12:07:42.591  3781  3781 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-02 12:07:42.620  3781  3781 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-02 12:07:42.632  3781  3781 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9256-9263)
09-02 12:07:42.632  3781  3781 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:07:42.653  3781  3781 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b2229bf}
09-02 12:07:42.653  3781  3781 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 12:07:42.653  3781  3781 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 12:07:42.661  3781  3781 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-02 12:07:42.663  3781  3781 E SysUtils: ApplicationContext is null in ApplicationStatus
09-02 12:07:42.686  3781  3781 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-02 12:07:42.695  3781  3781 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 12:07:42.696  3781  3781 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 12:07:42.696  3781  3781 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 12:07:42.696  3781  3781 I Adreno  : Build Date                       : 10/20/15
09-02 12:07:42.696  3781  3781 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 12:07:42.696  3781  3781 I Adreno  : Local Branch                     : M14
09-02 12:07:42.696  3781  3781 I Adreno  : Remote Branch                    : 
09-02 12:07:42.696  3781  3781 I Adreno  : Remote Branch                    : 
09-02 12:07:42.696  3781  3781 I Adreno  : Reconstruct Branch               : 
,09-02 12:07:42.795   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb7e794:true
,09-02 12:07:42.826  3781  3781 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 12:07:42.840  3781  3781 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-02 12:07:42.896  3781  3820 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-02 12:07:42.906  3781  3806 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-02 12:07:42.977  3781  3820 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 12:07:43.080   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +604ms
,09-02 12:07:43.080  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-02 12:07:43.172  3781  3781 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3781
,09-02 12:07:43.305   874   885 I ActivityManager: Killing 3214:com.google.android.gm/u0a78 (adj 15): empty #17
,09-02 12:07:43.357  3781  3781 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 12:07:43.368   874   885 I ActivityManager: Killing 3126:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-02 12:07:43.511  3781  3824 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1698494160
,09-02 12:07:43.516  3781  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 12:07:43.516  3781  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 12:07:43.516  3781  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 12:07:43.516  3781  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 12:07:43.516  3781  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 12:07:43.517  3781  3824 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7445102 added. We now have 1 listener(s)
,09-02 12:07:43.520  3781  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-02 12:07:43.520  3781  3824 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:07:43.521  3781  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:07:43.521  3781  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-02 12:07:43.525  3781  3824 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c8e649 added. We now have 1 listener(s)
09-02 12:07:43.525  3781  3824 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:43.529   874  1315 D WifiService: New client listening to asynchronous messages
09-02 12:07:43.530  3781  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:07:43.530  3781  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-02 12:07:43.531  3781  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-02 12:07:43.531  3781  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-02 12:07:43.531  3781  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
,09-02 12:07:43.534  3781  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:43.536  3781  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-02 12:07:43.544  3781  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:43.544  3781  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:43.544  3781  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-02 12:07:43.544  3781  3824 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:43.547  3781  3824 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 12:07:43.547  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:43.549  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:43.570  3781  3781 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 12:07:44.387  3781  3832 W jxcore-log: Initializing JXcore engine
,09-02 12:07:44.387  3781  3832 W jxcore-log: JXcore engine is ready
,09-02 12:07:44.423  3832  3832 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-02 12:07:44.423  3832  3832 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10929]" dev="sockfs" ino=10929 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-02 12:07:44.426  3832  3832 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-02 12:07:44.426  3832  3832 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25289]" dev="sockfs" ino=25289 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-02 12:07:44.441  3781  3832 W jxcore-log: Starting JXcore engine
,09-02 12:07:44.523  3781  3832 W jxcore-log: Platform android
09-02 12:07:44.523  3781  3832 W jxcore-log: 
,09-02 12:07:44.523  3781  3832 W jxcore-log: Process ARCH arm
09-02 12:07:44.523  3781  3832 W jxcore-log: 
,09-02 12:07:44.768  3781  3832 I jxcore-log: JXcore Cordova bridge is ready!
09-02 12:07:44.768  3781  3832 I jxcore-log: 
,09-02 12:07:44.768  3781  3832 W jxcore-log: JXcore engine is started
,09-02 12:07:44.773  3781  3824 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 12:07:44.780  3781  3781 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 12:07:46.171   874  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-02 12:07:49.340  3019  3839 V KeepSync: Connecting to GoogleApiClient
09-02 12:07:49.341   874  1477 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-02 12:07:49.385  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:07:49.388  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:07:49.419  1507  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-02 12:07:49.419  1507  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-02 12:07:49.419  1507  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:07:49.419  1507  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:07:49.440  1701  3840 V BaseAuthAsyncOperation: access token request failed
,09-02 12:07:49.440  3019  3839 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-02 12:07:49.501  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-02 12:07:49.501  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-02 12:07:49.501  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 12:07:49.501  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:07:49.527  3019  3839 E KeepSync: IOException
09-02 12:07:49.527  3019  3839 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-02 12:07:49.527  3019  3839 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-02 12:07:49.527  3019  3839 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-02 12:07:49.527  3019  3839 E KeepSync: 	... 10 more
,09-02 12:07:49.527  3019  3839 W KeepSync: Sync result 2
,09-02 12:07:49.534   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125634, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-02 12:07:49.772  1507  3763 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-02 12:07:49.772  1507  3763 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-02 12:07:49.773  1507  3763 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:07:49.773  1507  3763 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:07:49.805  3540  3842 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-02 12:07:49.805  3540  3842 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jdm.a(PG:82)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jcs.o(PG:406)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jcn.a(PG:1379)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jcs.i(PG:143)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at blb.a(PG:3937)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at czp.a(PG:18188)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at czp.a(PG:9081)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at czq.run(PG:1686)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:07:49.805  3540  3842 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jdj.a(PG:4091)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jdj.a(PG:1125)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jdm.a(PG:77)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	... 12 more
09-02 12:07:49.805  3540  3842 E HttpOperation: Caused by: faj: BadAuthentication
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at fal.a(PG:38)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	at jdj.a(PG:4089)
09-02 12:07:49.805  3540  3842 E HttpOperation: 	... 14 more
,09-02 12:07:49.849  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-02 12:07:49.849  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-02 12:07:49.849  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 12:07:49.849  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:07:49.889  3540  3842 E HttpOperation: [getmobileexperiments] Unexpected exception
09-02 12:07:49.889  3540  3842 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jdm.a(PG:82)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jcs.o(PG:406)
09-02 12:07:49.889  3540  3842 E HttpOperation: ,	at jcn.a(PG:1379)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jcs.i(PG:143)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at hec.a(PG:42)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at hee.a(PG:102)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at czr.a(PG:65)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at kka.a(PG:108)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at czp.a(PG:19176)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at czp.a(PG:9081)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at czq.run(PG:1686)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:07:49.889  3540  3842 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jdj.a(PG:4091)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jdj.a(PG:1125)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jdm.a(PG:77)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	... 15 more
09-02 12:07:49.889  3540  3842 E HttpOperation: Caused by: faj: BadAuthentication
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at fal.a(PG:38)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	at jdj.a(PG:4089)
09-02 12:07:49.889  3540  3842 E HttpOperation: 	... 17 more
09-02 12:07:49.889  3540  3842 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-02 12:07:49.889  3540  3842 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jdm.a(PG:82)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jcs.o(PG:406)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jcn.a(PG:1379)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jcs.i(PG:143)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at hec.a(PG:42)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at hee.a(PG:102)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at czr.a(PG:65)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at kka.a(PG:108)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at czp.a(PG:19176)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at czp.a(PG:9081)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at czq.run(PG:1686)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jdj.a(PG:4091)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jdj.a(PG:1125)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jdm.a(PG:77)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	... 15 more
09-02 12:07:49.889  3540  3842 E ExperimentLoader: Caused by: faj: BadAuthentication
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at fal.a(PG:38)
09-02 12:07:49.889  3540  3842 E ExperimentLoader: 	at jdj.a(PG:4089)
09-02 12:07:4,9.889  3540  3842 E ExperimentLoader: 	... 17 more
,09-02 12:07:50.020   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126099, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-02 12:07:54.788  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 12:07:54.788  3781  3832 I jxcore-log: 
,09-02 12:07:54.791  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 12:07:54.791  3781  3832 I jxcore-log: 
,09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:54.801  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:54.809  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:54.817  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 12:07:54.817  3781  3832 I jxcore-log: 
,09-02 12:07:54.825  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 12:07:54.825  3781  3832 I jxcore-log: 
,09-02 12:07:55.369  3781  3832 D executeNativeTests: Running unit tests
,09-02 12:07:55.426  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:07:55.426  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 added. We now have 2 listener(s)
,09-02 12:07:55.428  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:07:55.428  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:07:55.428  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:07:55.430  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:55.430  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 added. We now have 2 listener(s)
09-02 12:07:55.430  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:07:55.431  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:07:55.435  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.454  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:55.458  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:55.458  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:55.460  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 12:07:55.462  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:07:55.462  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 12:07:55.464  3781  3832 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 12:07:55.464  3781  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-02 12:07:55.464  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:07:55.464  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:55.464  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:55.465  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.465  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.465  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.465  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.466  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:07:55.466  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:55.466  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:07:55.466  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 removed from the list
,09-02 12:07:55.466  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:07:55.466  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 removed from the list
,09-02 12:07:55.466  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:55.466  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:07:55.466  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.467  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.467  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.470  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.470  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.470  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:07:55.470  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.475  3781  3832 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 12:07:55.476  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.476  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.476  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.476  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:07:55.476  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.477  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.477  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.477  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:07:55.477  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.478  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.479  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.479  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:07:55.479  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.479  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.479  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.483  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.483  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.483  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.483  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.487  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:07:55.488  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnect,ions: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:07:55.489  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:07:55.489  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.489  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.489  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.489  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.489  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.489  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.489  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.490  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.490  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.490  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.490  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.490  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.490  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.490  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.491  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.491  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.491  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.491  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.492  3781  3832 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:07:55.494  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.507  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:55.511  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.511  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:07:55.511  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:07:55.511  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:07:55.511  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:07:55.511  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:55.511  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:07:55.516  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.519  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:07:55.519  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.520  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:07:55.533  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:07:55.538  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:07:55.539  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:07:55.544  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 12:07:55.551  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 12:07:55.551  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:07:55.552  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:07:55.553  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:07:55.556  3781  3832 D BluetoothAdapter: STATE_ON
09-02 12:07:55.564  2698  2908 D BtGatt.GattService: registerClient() - UUID=129baf02-9684-48ca-a215-ed72401a129f
09-02 12:07:55.565  2698  2755 D BtGatt.GattService: onClientRegistered() - UUID=129baf02-9684-48ca-a215-ed72401a129f, clientIf=5
09-02 12:07:55.567  3781  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:07:55.570  2698  2710 D BtGatt.GattService: start scan with filters
09-02 12:07:55.576  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:07:55.576  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:07:55.576  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 12:07:55.576  2698  2758 D BtGatt.ScanManager: handling starting scan
,09-02 12:07:55.576  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:07:55.595  2698  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:07:55.598  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:55.599  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:55.601  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:07:55.607  2698  2755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:07:55.607  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 12:07:55.607  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:07:55.608  2698  2758 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:07:55.615  3781  3832 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 12:07:55.621  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.621  3781  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:55.621  2698  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 12:07:55.621  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.621  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.621  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:07:55.621  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.621  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:07:55.621  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:55.621  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:55.621  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:55.621  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:55.622  2698  2758 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:07:55.622  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:07:55.622  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:07:55.622  2698  2758 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 12:07:55.625  3781  3832 D BluetoothAdapter: STATE_ON
,09-02 12:07:55.626  2698  2709 D BtGatt.GattService: stopScan() - queue size =1
,09-02 12:07:55.627  2698  2710 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:07:55.627  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:07:55.628  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:07:55.628  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:07:55.628  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 12:07:55.628  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:07:55.631  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.631  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 12:07:55.631  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:07:55.632  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:07:55.633  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:55.634  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:07:55.634  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.634  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:55.634  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.634  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.634  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.634  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.634  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.635  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:07:55.635  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.635  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.635  3781  3832 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:07:55.637  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:55.642  2698  2755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:07:55.642  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.642  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:55.645  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:55.645  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:07:55.645  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:07:55.645  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:07:55.645  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:07:55.645  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:55.645  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:07:55.647  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.648  2698  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 12:07:55.648  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.648  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:07:55.648  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:07:55.649  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:55.651  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:07:55.652  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:07:55.652  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:07:55.654  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:07:55.654  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:07:55.654  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:07:55.655  2698  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:07:55.655  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.655  3781  3832 D BluetoothAdapter: STATE_ON
09-02 12:07:55.655  2698  2758 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:07:55.657  2698  2709 D BtGatt.GattService: registerClient() - UUID=82f723b5-f9f7-4c52-a2a9-37ca12d4f553
,09-02 12:07:55.657  2698  2755 D BtGatt.GattService: onClientRegistered() - UUID=82f723b5-f9f7-4c52-a2a9-37ca12d4f553, clientIf=5
09-02 12:07:55.657  3781  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:07:55.658  2698  2710 D BtGatt.GattService: start scan with filters
,09-02 12:07:55.660  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:07:55.660  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:07:55.660  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 12:07:55.660  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:07:55.662  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:07:55.662  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:07:55.662  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:07:55.662  2698  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:07:55.662  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.662  2698  2758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 12:07:55.663  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:07:55.665  3781  3832 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 12:07:55.666  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:07:55.666  3781  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:55.666  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.666  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:07:55.666  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.666  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:07:55.667  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 12:07:55.667  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:55.667  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:55.667  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:55.667  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:07:55.667  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 12:07:55.667  3781  3832 D BluetoothAdapter: STATE_ON
09-02 12:07:55.668  2698  2709 D BtGatt.GattService: stopScan() - queue size =0
09-02 12:07:55.668  2698  2755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:07:55.668  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.668  2698  2908 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:07:55.669  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:07:55.669  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:07:55.669  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 12:07:55.669  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:07:55.669  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:07:55.669  2698  2758 D BtGatt.ScanManager: handling starting scan
09-02 12:07:55.669  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.669  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:07:55.670  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:07:55.670  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:07:55.670  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:55.670  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.670  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.671  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:55.671  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.671  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.671  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.671  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.671  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.671  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.671  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.671  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.671  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.671  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.673  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.673  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.673  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.673  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
,09-02 12:07:55.673  3781  3832 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 12:07:55.674  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:55.675  2698  2755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 12:07:55.675  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.675  2698  2758 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.677  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:55.679  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:55.679  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:07:55.679  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:07:55.679  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:07:55.679  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:07:55.680  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:55.680  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:07:55.680  2698  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:07:55.680  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.680  2698  2758 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:07:55.680  2698  2758 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 12:07:55.681  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:07:55.681  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:07:55.682  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:55.685  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:07:55.686  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 12:07:55.686  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:07:55.688  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.688  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:07:55.689  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:07:55.689  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:07:55.689  3781  3832 D BluetoothAdapter: STATE_ON
,09-02 12:07:55.690  2698  2709 D BtGatt.GattService: registerClient() - UUID=0b774bae-4a81-4d6e-a98e-5e7018fcc404
,09-02 12:07:55.691  2698  2755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:07:55.691  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:07:55.691  2698  2755 D BtGatt.GattService: onClientRegistered() - UUID=0b774bae-4a81-4d6e-a98e-5e7018fcc404, clientIf=5
09-02 12:07:55.692  3781  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 12:07:55.693  2698  2908 D BtGatt.GattService: start scan with filters
09-02 12:07:55.695  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:07:55.695  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:07:55.695  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:07:55.696  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:07:55.696  2698  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 12:07:55.696  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:07:55.699  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:07:55.699  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:07:55.699  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:55.700  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:07:55.701  2698  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:07:55.702  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.702  2698  2758 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:07:55.702  3781  3832 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:07:55.702  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.703  3781  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:55.703  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:07:55.703  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:07:55.703  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.703  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:07:55.703  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:55.703  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:55.703  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:55.703  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:55.703  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:07:55.704  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:07:55.704  3781  3832 D BluetoothAdapter: STATE_ON
09-02 12:07:55.704  2698  2710 D BtGatt.GattService: stopScan() - queue size =0
,09-02 12:07:55.705  2698  2709 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:07:55.705  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:07:55.705  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:07:55.705  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:07:55.706  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:07:55.706  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:07:55.707  2698  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:07:55.707  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.707  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.707  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:07:55.707  2698  2758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 12:07:55.707  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:07:55.707  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:07:55.709  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:55.710  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.711  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:07:55.711  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.711  2698  2755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:07:55.711  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.711  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:07:55.711  3781  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:55.711  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:07:55.711  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.712  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.712  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.712  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:55.712  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.712  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.712  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.712  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.712  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.713  2698  2758 D BtGatt.ScanManager: handling starting scan
,09-02 12:07:55.713  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.713  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.714  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.714  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:07:55.714  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.714  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.715  3781  3832 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 12:07:55.715  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:07:55.715  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.715  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.716  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.716  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.716  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.716  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.716  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.716  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.716  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.716  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.716  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.717  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.717  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.718  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.718  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:07:55.718  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.718  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.718  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:07:55.718  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:07:55.718  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.719  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.719  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.719  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.719  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.719  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
,09-02 12:07:55.719  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:07:55.719  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
,09-02 12:07:55.719  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:07:55.719  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:07:55.719  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.719  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:07:55.719  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.719  2698  2755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 12:07:55.719  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.720  2698  2758 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:07:55.720  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:07:55.720  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:07:55.720  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.720  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.720  3781  3832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-02 12:07:55.721  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.721  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.721  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:07:55.721  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.721  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.721  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.721  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.721  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.721  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
,09-02 12:07:55.721  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.721  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.721  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.721  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.721  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.722  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.722  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.722  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.722  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.722  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-02 12:07:55.722  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.722  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.722  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.722  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:07:55.723  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.723  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.723  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.723  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.723  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
,09-02 12:07:55.723  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.723  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.723  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:55.723  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:07:55.723  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.724  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:07:55.724  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.724  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:07:55.724  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
,09-02 12:07:55.724  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 12:07:55.724  2698  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:07:55.725  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.725  2698  2758 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:07:55.725  2698  2758 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 12:07:55.725  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:07:55.726  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 12:07:55.726  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:55.726  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 12:07:55.726  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:07:55.727  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.727  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.727  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:07:55.728  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.728  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.728  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.728  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.728  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:07:55.729  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.729  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.729  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.729  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.729  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.729  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.730  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.730  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:07:55.730  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.730  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.731  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:55.731  3781  3832 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:07:55.731  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:07:55.733  2698  2755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 12:07:55.733  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.737  2698  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 12:07:55.737  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.740  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:55.740  3781  3832 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-02 12:07:55.740  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:07:55.741  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:07:55.741  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:07:55.741  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:07:55.742  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:07:55.742  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:07:55.742  2698  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:07:55.742  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.742  2698  2758 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:07:55.742  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:07:55.743  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:07:55.743  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:07:55.743  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:07:55.743  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:07:55.744  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:07:55.744  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:07:55.744  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:07:55.744  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:07:55.744  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:07:55.744  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:07:55.745  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:07:55.745  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:07:55.745  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:07:55.745  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:07:55.745  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:07:55.745  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:07:55.745  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 12:07:55.746  3781  3832 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discover,ed peers, but trying anyway...
09-02 12:07:55.746  2698  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:07:55.746  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.746  3781  3832 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 12:07:55.747  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:55.747  2698  2758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 12:07:55.747  3781  3832 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:07:55.747  3781  3832 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 12:07:55.747  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:55.747  3781  3832 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:07:55.747  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 12:07:55.751  2698  2755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:07:55.751  2698  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:07:55.754  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 12:07:55.755  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 12:07:55.755  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 12:07:55.755  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 12:07:55.755  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 12:07:55.755  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 12:07:55.755  3781  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:55.756  3781  3832 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 12:07:55.756  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.756  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.756  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.756  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.756  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.756  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.756  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 12:07:55.756  3781  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
09-02 12:07:55.757  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject,.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.757  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.757  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.757  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.757  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.757  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.757  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.757  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.758  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.758  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.758  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.759  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.759  3781  3832 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 12:07:55.759  3781  3848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:07:55.759  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.760  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.760  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.760  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.760  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.760  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.760  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.760  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.760  3781  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
09-02 12:07:55.760  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.760  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.760  3781  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
09-02 12:07:55.760  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.760  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.760  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.760  3781  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
09-02 12:07:55.760  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.761  3781  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
09-02 12:07:55.762  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.762  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.762  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.762  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.763  3781  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 12:07:55.763  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.763  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.763  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.763  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.763  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.764  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.764  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.764  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.764  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.764  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.764  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.764  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.764  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.764  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.767  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.767  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.767  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.767  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.768  3781  3832 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 12:07:55.768  3781  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 12:07:55.768  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:07:55.768  3781  3832 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 12:07:55.768  3781  3832 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:07:55.768  3781  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 12:07:55.768  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:07:55.768  3781  3832 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 12:07:55.768  3781  3832 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:07:55.768  3781  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:07:55.768  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:07:55.768  3781  3832 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 12:07:55.769  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.769  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.769  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.769  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.769  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.769  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.769  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.769  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.769  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.769  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.769  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.769  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.769  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.769  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.770  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.770  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.770  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.770  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.770  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.771  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.771  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.771  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.771  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.771  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.771  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.771  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.771  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.771  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.771  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.771  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.771  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.771  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.771  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.771  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.771  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.771  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.771  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.772  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.772  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.772  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.772  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.772  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.772  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.772  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.772  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.772  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.772  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.773  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.773  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.773  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.773  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.774  3781  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 12:07:55.774  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:55.775  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 12:07:55.775  3781  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 12:07:55.775  3781  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:55.776  3781  3781 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 12:07:55.776  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 12:07:55.776  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.776  3781  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 12:07:55.776  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.776  3781  3781 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 12:07:55.776  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:55.776  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:55.776  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:55.776  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.776  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.777  3781  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 12:07:55.777  3781  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 12:07:55.777  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.777  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.777  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.777  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.777  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:55.777  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.777  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.777  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:55.777  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.778  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.778  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.778  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.778  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.778  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.778  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.778  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.778  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.778  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.778  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.778  3781  3781 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 12:07:55.779  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.779  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.779  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.779  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.780  3781  3832 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 12:07:55.780  3781  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:07:55.780  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:07:55.780  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:55.780  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.780  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.780  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.780  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.780  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.780  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.780  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.780  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.780  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.780  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.780  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.780  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.781  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.781  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.781  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.781  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.781  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.781  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.790  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.791  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.791  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.791  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.791  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.791  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.791  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.791  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.791  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.791  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.791  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.791  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.791  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.791  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.792  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.792  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.792  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.792  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.793  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:55.793  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:55.793  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:55.793  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:55.793  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.794  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.794  3781  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f623 not in the list
09-02 12:07:55.794  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.794  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.794  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:55.794  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.794  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.794  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:55.794  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:55.795  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:55.795  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:55.795  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:55.795  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1a720 not in the list
09-02 12:07:55.796  3781  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 12:07:55.796  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:07:55.796  3781  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 12:07:55.796  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:07:55.796  3781  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 12:07:55.796  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:07:55.798  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:07:55.798  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 12:07:55.799  3781  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 12:07:55.799  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:07:55.799  3781  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 12:07:55.799  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:07:55.799  3781  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 12:07:55.799  3781  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 12:07:55.800  3781  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 12:07:55.800  3781  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 12:07:55.800  3781  3832 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 12:07:55.800  3781  3832 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 12:07:55.800  3781  3832 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 12:07:55.800  3781  3832 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 12:07:55.801  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:55.801  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d21c502 added. We now have 2 listener(s)
09-02 12:07:55.801  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:07:55.803  3781  3832 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 12:07:55.803   874  1477 D WifiService: setWifiEnabled: true pid=3781, uid=10000
09-02 12:07:55.803   874  1477 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:07:55.804  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:55.804  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f3ae13 added. We now have 3 listener(s)
09-02 12:07:55.804  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:07:55.808  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:55.809  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67d1850 added. We now have 4 listener(s)
09-02 12:07:55.809  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:55.810  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:55.810  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8bea49 added. We now have 5 listener(s)
09-02 12:07:55.810  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:07:55.813   874  2202 D WifiService: setWifiEnabled: false pid=3781, uid=10000
09-02 12:07:55.813   874  2202 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 12:07:55.816  2698  2751 D BluetoothAdapterState: Current state: ON, message: 23
09-02 12:07:55.816  2698  2751 D BluetoothAdapterProperties: Setting state to 13
09-02 12:07:55.816  2698  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:07:55.816  2698  2751 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:07:55.817  2698  2751 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:07:55.818  2698  2698 D BluetoothMapService: onReceive
09-02 12:07:55.818  2698  2698 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:55.818  2698  2698 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:07:55.818  2698  2698 D BluetoothMapService: MAP Service closeService in
09-02 12:07:55.818  2698  2698 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 12:07:55.818  2698  2698 D ObexServerSockets0: shutdown(block = true)
09-02 12:07:55.819  2698  2698 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 12:07:55.819  2698  2698 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 12:07:55.819  2698  2909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 12:07:55.819  2698  2910 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 12:07:55.820  2698  2888 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 12:07:55.820  2698  2698 I BtOppRfcommListener: stopping Accept Thread
09-02 12:07:55.820  2698  3443 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 12:07:55.820  2698  3443 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 12:07:55.821  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.821  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:55.822  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.822  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.833  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 12:07:55.833   874  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 12:07:55.834   874  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 12:07:55.834   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:07:55.834   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:07:55.839   370   872 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:07:55.842   874  2075 D DhcpClient: Clearing IP address
09-02 12:07:55.843   874   887 I ActivityManager: Start proc 3854:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-02 12:07:55.843   370   872 D CommandListener: Setting iface cfg
,09-02 12:07:55.844  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:55.844  2698  2755 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:07:55.845  2698  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 12:07:55.847  2698  2698 D HeadsetService: Received stop request...Stopping profile...
,09-02 12:07:55.847  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:55.849   874   874 D BluetoothHeadset: Proxy object disconnected
,09-02 12:07:55.849   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:07:55.849  1366  1386 D BluetoothHeadset: Proxy object disconnected
09-02 12:07:55.850  1507  2916 V NativeCrypto: Read error: ssl=0xaec86000: I/O error during system call, Connection timed out
,09-02 12:07:55.850   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:07:55.850  1958  2141 D BluetoothHeadset: Proxy object disconnected
09-02 12:07:55.851  1507  2916 V NativeCrypto: SSL shutdown failed: ssl=0xaec86000: I/O error during system call, Broken pipe
,09-02 12:07:55.851  2698  2698 D A2dpService: Received stop request...Stopping profile...
,09-02 12:07:55.851  2698  2892 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.852  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:55.852  1366  1366 D HeadsetProfile: Bluetooth service disconnected
,09-02 12:07:55.853   874  1908 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-02 12:07:55.853   874  2071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-02 12:07:55.853  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.853  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:55.853  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:55.855  1366  1366 D BluetoothA2dp: Proxy object disconnected
,09-02 12:07:55.855   874   874 D BluetoothA2dp: Proxy object disconnected
09-02 12:07:55.855  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:55.856  2698  2698 D HidService: Received stop request...Stopping profile...
,09-02 12:07:55.856  2698  2698 D HidService: Stopping Bluetooth HidService
09-02 12:07:55.856   874  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
09-02 12:07:55.857   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:07:55.857   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 12:07:55.857   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-02 12:07:55.858   393   393 E Parcel  : Reading a NULL string not supported here.
09-02 12:07:55.860  2698  2698 V BluetoothAdapterState: isTurningOff()=true
09-02 12:07:55.860  2698  2698 V BluetoothAdapterState: isTurningOn()=false
,09-02 12:07:55.860  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:07:55.860  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:07:55.861  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:55.861  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:55.861  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.861  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:07:55.862   874  2079 D DhcpClient: Receive thread stopped
09-02 12:07:55.863  2698  2698 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:07:55.863  2698  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-02 12:07:55.864  2698  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:07:55.864  2698  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:07:55.864  2698  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:07:55.864  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.864  2698  2755 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:55.864  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:55.865  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:55.865   874  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-02 12:07:55.865  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:55.865  2698  2698 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:07:55.867  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:55.867  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:55.870  2698  2698 V BluetoothAdapterState: isTurningOff()=true
09-02 12:07:55.871  2698  2698 V BluetoothAdapterState: isTurningOn()=false
09-02 12:07:55.871  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:07:55.871  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:07:55.872  2698  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 12:07:55.872  2698  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:07:55.872  2698  2881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:55.872  2698  2881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:55.872  2698  2881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:55.872  2698  2881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:55.872  2698  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 12:07:55.873  2698  2698 V BluetoothAdapterState: isTurningOff()=true
09-02 12:07:55.873  2698  2698 V BluetoothAdapterState: isTurningOn()=false
09-02 12:07:55.873  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:07:55.873  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:07:55.873  2698  2698 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:07:55.873  2698  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 12:07:55.874  2698  2698 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:07:55.874  2698  2698 D HealthService: Received stop request...Stopping profile...
09-02 12:07:55.876  2698  2698 D PanService: Received stop request...Stopping profile...
09-02 12:07:55.877   874  2071 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-02 12:07:55.880  2698  2698 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:07:55.880  2698  2698 D BluetoothMapService: stop()
,09-02 12:07:55.880  1366  1366 D BluetoothInputDevice: Proxy object disconnected
09-02 12:07:55.880  1366  1366 D HidProfile: Bluetooth service disconnected
09-02 12:07:55.880  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:07:55.881  1366  1366 D PanProfile: Bluetooth service disconnected
09-02 12:07:55.881  2698  2698 D BluetoothMapAppObserver: deinitObservers()
09-02 12:07:55.881  2698  2698 D BluetoothMapAppObserver: removeReceiver()
09-02 12:07:55.881  1366  1366 D BluetoothMap: Proxy object disconnected
09-02 12:07:55.881  1366  1366 D MapProfile: Bluetooth service disconnected
09-02 12:07:55.882  2698  2698 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:07:55.882  2698  2698 V BluetoothAdapterState: isTurningOn()=false
09-02 12:07:55.882  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:07:55.882  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:07:55.886  2698  2698 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:07:55.886  2698  2755 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 12:07:55.886  2698  2698 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:07:55.886  2698  2698 V BluetoothAdapterState: isTurningOff()=true
09-02 12:07:55.886  2698  2698 V BluetoothAdapterState: isTurningOn()=false
09-02 12:07:55.886  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:07:55.886  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:07:55.887  2698  2698 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:07:55.887  2698  2698 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 12:07:55.887  2698  2698 D BluetoothMapService: MAP Service closeService in
09-02 12:07:55.887  2698  2698 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:07:55.887  2698  2698 V BluetoothAdapterState: isTurningOn()=false
09-02 12:07:55.887  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:07:55.887  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:07:55.888  2698  2698 D BluetoothMapService: cleanup()
09-02 12:07:55.888  2698  2698 D BluetoothMapService: MAP Service closeService in
09-02 12:07:55.888  2698  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 12:07:55.888  2698  2751 D BluetoothAdapterProperties: Setting state to 15
09-02 12:07:55.888  2698  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 12:07:55.889  2698  2751 I BluetoothAdapterState: Entering BleOnState
09-02 12:07:55.890  1366  2077 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 12:07:55.890  1366  1386 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:07:55.890  1366  3780 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:07:55.891  1366  1393 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:07:55.892  1366  2077 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:07:55.892   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:07:55.893  1366  1386 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:07:55.893   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:07:55.893   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:07:55.893  1958  1972 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:07:55.894   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:07:55.894  2698  2751 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 12:07:55.894  2698  2751 D BluetoothAdapterProperties: Setting state to 16
09-02 12:07:55.894  2698  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-02 12:07:55.894  2698  2751 D BluetoothAdapterProperties: onBleDisable
09-02 12:07:55.894  2698  2751 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:07:55.895  2698  2752 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 12:07:55.896  2698  2881 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 12:07:55.896  2698  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:07:55.896  2698  2755 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:07:55.897  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:55.897  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:07:55.898  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:55.898  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:07:55.900  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.901  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:55.907   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 12:07:55.912  3854  3854 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-02 12:07:55.922  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:55.927  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:55.927   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 12:07:55.927   370   872 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:07:55.928   874  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-02 12:07:55.928   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:55.931   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:07:55.933  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.934  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:55.936  3391  3391 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2514a13 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-02 12:07:55.943   874  2202 I ActivityManager: Start proc 3873:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-02 12:07:55.944   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:07:55.946  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:55.946  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:55.947  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.947  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:07:55.948   874  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:07:55.948  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:55.948  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:07:55.949  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:55.949  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:07:55.950  1899  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:07:55.960   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d5af4d:true
,09-02 12:07:55.979  3873  3873 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-02 12:07:55.981  3854  3854 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 12:07:55.983  3854  3854 D BluetoothMap: Create BluetoothMap proxy object
,09-02 12:07:55.986   370   872 E Netd    : netlink response contains error (No such file or directory)
,09-02 12:07:55.987   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 12:07:55.992  3854  3854 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-02 12:07:56.005  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:56.010   874  2202 I ActivityManager: Killing 2977:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-02 12:07:56.101  2698  2755 I bt_hci  : shut_down
,09-02 12:07:56.101  2698  2760 D bt_hwcfg: hw_epilog_process
,09-02 12:07:56.112  2698  2760 I bt_vendor: low_power_mode_cb
,09-02 12:07:56.134  2698  2760 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 12:07:56.134  2698  2760 I bt_vendor: epilog_cb
09-02 12:07:56.135  2698  2760 I bt_hci  : epilog_finished_callback
,09-02 12:07:56.140  2698  2755 I bt_hci_h4: hal_close
,09-02 12:07:56.141  2698  2755 I bt_userial_vendor: device fd = 51 close
,09-02 12:07:56.172  3873  3873 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.172  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:583)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.176  3873  3873 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:07:56.176  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:07:56.197  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:56.207  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:56.217  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:56.225   874   884 I ActivityManager: Killing 3391:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-02 12:07:56.279  3781  3781 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:07:56.291  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 12:07:56.293  2698  2752 D bt_stack_manager: event_shut_down_stack finished.
,09-02 12:07:56.294  2698  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-02 12:07:56.296  2698  2751 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-02 12:07:56.297  2698  2698 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:07:56.298  2698  2698 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:07:56.298  2698  2698 D BtGatt.GattService: stop()
09-02 12:07:56.298  2698  2698 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 12:07:56.300  1701  1701 D SystemUpdateService: onCreate
,09-02 12:07:56.302  2698  2698 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:07:56.303  2698  2698 V BluetoothAdapterState: isTurningOn()=false
,09-02 12:07:56.303  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:07:56.303  2698  2698 V BluetoothAdapterState: isBleTurningOff()=true
,09-02 12:07:56.304  2698  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-02 12:07:56.304  2698  2751 D BluetoothAdapterProperties: Setting state to 10
09-02 12:07:56.304  2698  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 12:07:56.306  2698  2751 I BluetoothAdapterState: Entering OffState
,09-02 12:07:56.307  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-02 12:07:56.307   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-02 12:07:56.321  1701  3907 I SystemUpdateService: active receiver: enabled
,09-02 12:07:56.336  1701  3907 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 12:07:56.341  2698  2698 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-02 12:07:56.341  2698  2698 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 12:07:56.341  2698  2698 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 12:07:56.342  2698  2752 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-02 12:07:56.345  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 12:07:56.348  1701  2516 I iu.UploadsManager: num queued entries: 0
,09-02 12:07:56.354  2698  2752 D bt_stack_manager: event_clean_up_stack finished.
,09-02 12:07:56.354  1701  3907 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 12:07:56.355  1701  3907 I SystemUpdateService: now status is 0 (complete)
09-02 12:07:56.355  1701  3907 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 12:07:56.355  1701  3907 I SystemUpdateService: file has been verified
,09-02 12:07:56.357  2698  2698 I art     : System.exit called, status: 0
,09-02 12:07:56.357  2698  2698 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:07:56.359  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:07:56.361  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 12:07:56.363  1701  3907 I SystemUpdateService: OTA package size = 12249756
,09-02 12:07:56.373  1701  2516 I iu.UploadsManager: num updated entries: 0
,09-02 12:07:56.380   874   885 I ActivityManager: Start proc 3910:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-02 12:07:56.386  1701  2516 I iu.SyncManager: NEXT; no task
,09-02 12:07:56.390  1701  3907 I SystemUpdateService: showing system update notification
,09-02 12:07:56.415   874  2041 I ActivityManager: Process com.android.bluetooth (pid 2698) has died
,09-02 12:07:56.431  1701  1701 D SystemUpdateService: onDestroy
,09-02 12:07:56.436  3910  3910 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-02 12:07:56.438  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:56.452  3910  3910 D SprintDMHelper: simOperator: 
,09-02 12:07:56.452  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 12:07:56.473   874  1477 I ActivityManager: Start proc 3923:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-02 12:07:56.506  3873  3902 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 12:07:56.594   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7370bb0:true
,09-02 12:07:56.610   874  1477 I ActivityManager: Start proc 3939:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
09-02 12:07:56.612  3064  3938 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-02 12:07:56.617   874  1908 I ActivityManager: Killing 3461:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-02 12:07:56.686  3939  3939 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-02 12:07:56.738  3939  3939 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-02 12:07:56.738  3939  3939 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 12:07:56.738  3939  3939 I GAv4    :   adb logcat -s GAv4
,09-02 12:07:56.753  3939  3939 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:07:56.759  3939  3939 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:07:56.786  3939  3956 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:07:56.898  3939  3939 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-02 12:07:56.940  3939  3939 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-02 12:07:56.948  3939  3939 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3576-3579)
,09-02 12:07:56.949  3939  3939 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 12:07:56.958  3939  3939 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f0de03}
,09-02 12:07:56.959  3939  3939 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 12:07:56.959  3939  3939 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:07:56.967  3939  3939 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 12:07:56.969  3939  3939 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 12:07:56.988  3939  3939 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-02 12:07:57.003  3939  3939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 12:07:57.003  3939  3939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 12:07:57.003  3939  3939 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 12:07:57.003  3939  3939 I Adreno  : Build Date                       : 10/20/15
09-02 12:07:57.003  3939  3939 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 12:07:57.003  3939  3939 I Adreno  : Local Branch                     : M14
09-02 12:07:57.003  3939  3939 I Adreno  : Remote Branch                    : 
09-02 12:07:57.003  3939  3939 I Adreno  : Remote Branch                    : 
09-02 12:07:57.003  3939  3939 I Adreno  : Reconstruct Branch               : 
,09-02 12:07:57.064  3939  3939 I NSApplication: Starting up...
,09-02 12:07:57.071  3939  3985 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 12:07:57.113   874  1997 I ActivityManager: Start proc 3990:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-02 12:07:57.117   874  1995 I ActivityManager: Killing 1715:android.process.acore/u0a5 (adj 15): empty #17
,09-02 12:07:57.187  3990  3990 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-02 12:07:57.389   874  1477 I ActivityManager: Killing 3635:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-02 12:07:57.465   874  1904 I ActivityManager: Start proc 4004:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-02 12:07:57.529  4004  4004 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-02 12:07:57.592  4004  4004 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-02 12:07:57.664   874  1995 I ActivityManager: Killing 3652:com.android.musicfx/u0a18 (adj 15): empty #17
,09-02 12:07:58.857   874  1388 D WifiService: setWifiEnabled: true pid=3781, uid=10000
,09-02 12:07:58.858   874  1388 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:07:58.874   874  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-02 12:07:58.884  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:58.884  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:58.884  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:58.885  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:58.888  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:58.888  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:07:58.889  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:58.889  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:58.907   874  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-02 12:07:58.908   874  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 12:07:58.909   874  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-02 12:07:58.910   874  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:07:58.910   874  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 12:07:58.910   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 12:07:58.911   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 12:07:58.923   874  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.75 rxSuccessRate=13.12 delta 1000 -> 994
,09-02 12:07:58.923   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 12:07:58.926   370   872 D CommandListener: Setting iface cfg
,09-02 12:07:58.927   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-02 12:07:58.928   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 12:07:58.932   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 12:07:58.932   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:07:58.934   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 12:07:58.940   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 12:07:58.940   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 12:07:59.013   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 12:07:59.015  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 12:07:59.455  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:07:59.509  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:07:59.509  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 12:07:59.515   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:07:59.526   874  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 12:07:59.526   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 12:07:59.526   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:07:59.552   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:07:59.568   370   872 D CommandListener: Setting iface cfg
,09-02 12:07:59.568   874  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,09-02 12:07:59.581   874  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-02 12:07:59.585   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 12:07:59.596   874  4037 D DhcpClient: Receive thread started
,09-02 12:07:59.679   874  1314 E native  : do suspend false
,09-02 12:07:59.699   874  2075 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 12:07:59.718   874  4037 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,09-02 12:07:59.719   874  2075 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,09-02 12:07:59.723   874  2075 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 12:07:59.755   874  4037 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 12:07:59.756   874  2075 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 12:07:59.761   370   872 D CommandListener: Setting iface cfg
,09-02 12:07:59.772   874  2075 D DhcpClient: Scheduling renewal in 86399s
,09-02 12:07:59.773   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 12:07:59.795   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 12:07:59.799   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 12:07:59.799   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 12:07:59.800   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 12:07:59.802   874  1316 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 12:07:59.815   874  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 12:07:59.862   874  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 12:07:59.862   874  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 12:07:59.864   874  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-02 12:07:59.865   874  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-02 12:07:59.866   874  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-02 12:07:59.878   874  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 12:07:59.883   874  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-02 12:07:59.883   874  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-02 12:07:59.884   874  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-02 12:07:59.884   874  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-02 12:07:59.884   874  1316 D ConnectivityService:    accepting network in place of null
,09-02 12:07:59.884   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:07:59.884   874  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 12:07:59.913   874  4036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 12:07:59.961   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:08:00.030   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:80f::200e
,09-02 12:08:00.030   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:08:00.042   874  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 12:08:00.042   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:00.052   874   891 D Tethering: MasterInitialState.processMessage what=3
09-02 12:08:00.053   874  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 12:08:00.060  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:00.060  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:00.060  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:00.060  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:00.065  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:00.065  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:00.065  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:00.065  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:00.074  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 12:08:00.078  1701  1701 D SystemUpdateService: onCreate
,09-02 12:08:00.081  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 12:08:00.083  1701  4048 I SystemUpdateService: active receiver: enabled
,09-02 12:08:00.086  1701  4048 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 12:08:00.090  1701  4048 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-02 12:08:00.091  1701  4048 I SystemUpdateService: now status is 0 (complete)
09-02 12:08:00.091  1701  4048 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 12:08:00.091  1701  4048 I SystemUpdateService: file has been verified
09-02 12:08:00.092  1701  4048 I SystemUpdateService: OTA package size = 12249756
,09-02 12:08:00.099  1701  4048 I SystemUpdateService: showing system update notification
,09-02 12:08:00.104  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 12:08:00.107  1701  2516 I iu.UploadsManager: num queued entries: 0
,09-02 12:08:00.111  1701  2516 I iu.UploadsManager: num updated entries: 0
,09-02 12:08:00.112  1701  2516 I iu.SyncManager: NEXT; no task
,09-02 12:08:00.113  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:08:00.114  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 12:08:00.116   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 10:08:00 GMT], X-Android-Received-Millis=[1472810880115], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472810880077]}
,09-02 12:08:00.118  1701  4052 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-02 12:08:00.118  1701  4052 W BaseAppContext: Using Auth Proxy for data requests.
,09-02 12:08:00.121  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:00.121   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 12:08:00.121  1701  4052 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 12:08:00.121   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-02 12:08:00.122   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 12:08:00.123   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 12:08:00.126  1701  1701 D SystemUpdateService: onDestroy
,09-02 12:08:00.130  3910  3910 D SprintDMHelper: simOperator: 
,09-02 12:08:00.130  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-02 12:08:00.132  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:08:00.134  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:08:00.172  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 12:08:00.172  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 12:08:00.172  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:08:00.172  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:08:00.186  1701  4052 E MDM     : [172] SitrepService.a: Error sending sitrep.
,09-02 12:08:00.298  3064  4055 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 12:08:01.039   874  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 12:08:01.611   874  1988 I ActivityManager: Killing 2102:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-02 12:08:01.867   874  1905 D WifiService: setWifiEnabled: false pid=3781, uid=10000
,09-02 12:08:01.867   874  1905 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:08:01.888  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 12:08:01.892   874  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 12:08:01.892   874  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-02 12:08:01.893   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:08:01.893   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:08:01.916   874  2075 D DhcpClient: Clearing IP address
,09-02 12:08:01.918   370   872 D CommandListener: Setting iface cfg
,09-02 12:08:01.921   370   872 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:08:01.923  1507  4059 V NativeCrypto: Read error: ssl=0x9a99d800: I/O error during system call, Connection timed out
09-02 12:08:01.925   874  4037 D DhcpClient: Receive thread stopped
09-02 12:08:01.925  1507  4059 V NativeCrypto: SSL shutdown failed: ssl=0x9a99d800: I/O error during system call, Broken pipe
,09-02 12:08:01.933   874  2041 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-02 12:08:01.934   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-02 12:08:01.935   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:80f::200e
09-02 12:08:01.938  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 12:08:01.939   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-02 12:08:01.939   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-02 12:08:01.947   874  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-02 12:08:01.947   393   393 E Parcel  : Reading a NULL string not supported here.
09-02 12:08:01.947   874  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-02 12:08:01.949   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 12:08:01.958   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:80f::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-02 12:08:01.977  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-02 12:08:01.977  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-02 12:08:01.977  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:08:01.978  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:08:01.990  3501  3501 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-02 12:08:01.990  3501  3501 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-02 12:08:01.990  3501  3501 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
09-02 12:08:01.993   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:08:02.017   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 12:08:02.018   370   872 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:08:02.018   874  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-02 12:08:02.018   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:02.020   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:08:02.024  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:02.025  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:02.025  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:08:02.025  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:02.026  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:02.026  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:08:02.026  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:02.026  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:02.029   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
09-02 12:08:02.031  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:02.031  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:08:02.031  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:02.031  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:02.032   874  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:08:02.032  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:02.032  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:08:02.032  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:08:02.032  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:02.033  1899  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 12:08:02.035  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-02 12:08:02.039  1701  1701 D SystemUpdateService: onCreate
09-02 12:08:02.042  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 12:08:02.050  1701  4070 I SystemUpdateService: active receiver: enabled
,09-02 12:08:02.051  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 12:08:02.055  1701  2516 I iu.UploadsManager: num queued entries: 0
,09-02 12:08:02.056  1701  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 12:08:02.058  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:08:02.059  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-02 12:08:02.060  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:02.063  3910  3910 D SprintDMHelper: simOperator: 
09-02 12:08:02.063  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 12:08:02.062  1701  2516 I iu.UploadsManager: num updated entries: 0
,09-02 12:08:02.066  1701  4070 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 12:08:02.066  1701  4070 I SystemUpdateService: now status is 0 (complete)
09-02 12:08:02.066  1701  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 12:08:02.066  1701  4070 I SystemUpdateService: file has been verified
09-02 12:08:02.067  1701  4070 I SystemUpdateService: OTA package size = 12249756
,09-02 12:08:02.084   370   872 E Netd    : netlink response contains error (No such file or directory)
,09-02 12:08:02.084  3064  4074 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-02 12:08:02.085   874  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-02 12:08:02.086   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 12:08:02.091  1701  2516 I iu.SyncManager: NEXT; no task
,09-02 12:08:02.102  1701  4070 I SystemUpdateService: showing system update notification
,09-02 12:08:02.110  1701  1701 D SystemUpdateService: onDestroy
,09-02 12:08:04.923   874   891 I ActivityManager: Start proc 4077:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 12:08:05.070  4077  4077 D AdapterServiceConfig: Adding HeadsetService
,09-02 12:08:05.070  4077  4077 D AdapterServiceConfig: Adding A2dpService
,09-02 12:08:05.070  4077  4077 D AdapterServiceConfig: Adding HidService
09-02 12:08:05.070  4077  4077 D AdapterServiceConfig: Adding HealthService
09-02 12:08:05.071  4077  4077 D AdapterServiceConfig: Adding PanService
09-02 12:08:05.071  4077  4077 D AdapterServiceConfig: Adding GattService
,09-02 12:08:05.071  4077  4077 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 12:08:05.084  4077  4077 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 12:08:05.084   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22dae01:true
,09-02 12:08:05.088  4077  4077 I bt_bluedroid: init
,09-02 12:08:05.089  4077  4089 I BluetoothAdapterState: Entering OffState
,09-02 12:08:05.091  4077  4090 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 12:08:05.092  4077  4090 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:08:05.092  4077  4090 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 12:08:05.092  4077  4090 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 12:08:05.092  4077  4077 I bt_bluedroid: get_profile_interface socket
,09-02 12:08:05.094  4077  4077 I bt_bluedroid: get_profile_interface sdp
,09-02 12:08:05.098  4077  4093 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:08:05.098  4077  4088 I bt_bluedroid: config_hci_snoop_log
,09-02 12:08:05.099  4077  4093 D BluetoothAdapterProperties: Name is: Nexus 6
09-02 12:08:05.100   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 12:08:05.105  4077  4089 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 12:08:05.105  4077  4089 D BluetoothAdapterProperties: Setting state to 14
09-02 12:08:05.106  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 12:08:05.110  4077  4089 D BluetoothBondStateMachine: make
,09-02 12:08:05.113  4077  4094 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 12:08:05.121  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:08:05.123  4077  4077 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 12:08:05.129  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:05.131  4077  4077 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:08:05.132  4077  4077 D BtGatt.GattService: Received start request. Starting profile...
,09-02 12:08:05.132  4077  4077 D BtGatt.GattService: start()
09-02 12:08:05.132  4077  4077 I bt_bluedroid: get_profile_interface gatt
,09-02 12:08:05.134  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
09-02 12:08:05.134  4077  4077 D BtGatt.AdvertiseManager: advertise manager created
,09-02 12:08:05.144  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-02 12:08:05.145  4077  4077 V BluetoothAdapterState: isTurningOn()=false
,09-02 12:08:05.145  4077  4077 V BluetoothAdapterState: isBleTurningOn()=true
,09-02 12:08:05.145  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:05.145  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-02 12:08:05.146  4077  4089 I bt_bluedroid: enable
,09-02 12:08:05.146  4077  4090 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-02 12:08:05.146  4077  4090 I bt_hci  : start_up
,09-02 12:08:05.153  4077  4090 I bt_vendor: alloc value 0xb39fc189
09-02 12:08:05.153  4077  4090 I bt_vendor: init
09-02 12:08:05.153  4077  4090 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-02 12:08:05.153  4077  4090 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 12:08:05.259  4077  4090 D bt_hci  : start_up starting async portion
,09-02 12:08:05.261  4077  4097 I bt_hci  : event_finish_startup
,09-02 12:08:05.262  4077  4097 I bt_hci_h4: hal_open
,09-02 12:08:05.263  4077  4097 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 12:08:05.274  4077  4097 I bt_userial_vendor: device fd = 51 open
,09-02 12:08:05.304  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:08:05.336  4077  4097 D bt_hwcfg: Chipset BCM4354A2
,09-02 12:08:05.336  4077  4097 D bt_hwcfg: Target name = [BCM4354A2]
09-02 12:08:05.337  4077  4097 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 12:08:05.994  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 12:08:05.996  4077  4097 D bt_hwcfg: Settlement delay -- 100 ms
09-02 12:08:05.996  4077  4097 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 12:08:06.113  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:08:06.114  4077  4097 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 12:08:06.143  4077  4097 I bt_hwcfg: vendor lib fwcfg completed
,09-02 12:08:06.144  4077  4097 I bt_vendor: firmware callback
,09-02 12:08:06.144  4077  4097 I bt_hci  : firmware_config_callback
,09-02 12:08:06.155  4077  4099 I bt_btu  : btu_task pending for preload complete event
,09-02 12:08:06.155  4077  4099 I bt_btu_task: Bluetooth chip preload is complete
,09-02 12:08:06.155  4077  4099 I bt_btu  : btu_task received preload complete event
,09-02 12:08:06.165  4077  4099 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 12:08:06.165  4077  4099 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 12:08:06.165  4077  4099 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 12:08:06.166  4077  4099 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:08:06.166  4077  4099 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:08:06.166  4077  4099 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:08:06.167  4077  4099 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:08:06.167  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:08:06.167  4077  4099 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 12:08:06.167  4077  4099 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 12:08:06.168  4077  4099 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:08:06.168  4077  4099 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:08:06.168  4077  4099 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 12:08:06.168  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:08:06.169  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 12:08:06.305  4077  4099 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3979d9d
,09-02 12:08:06.306  4077  4099 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3979d9d 
,09-02 12:08:06.320  4077  4093 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 12:08:06.325  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 12:08:06.326  4077  4093 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:08:06.328  4077  4093 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 12:08:06.331  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:08:06.332  4077  4093 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:08:06.332  4077  4093 D bt_hci  : do_postload posting postload work item
,09-02 12:08:06.333  4077  4097 I bt_hci  : event_postload
,09-02 12:08:06.333  4077  4097 I bt_vendor: sco_config_cb
,09-02 12:08:06.333  4077  4097 I bt_hci  : sco_config_callback postload finished.
,09-02 12:08:06.336  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.336  4077  4093 D bt_bte_conf: Device ID record 1 : primary
,09-02 12:08:06.337  4077  4093 D bt_bte_conf:   vendorId            = 000f
09-02 12:08:06.337  4077  4093 D bt_bte_conf:   vendorIdSource      = 0001
09-02 12:08:06.337  4077  4093 D bt_bte_conf:   product             = 1200
,09-02 12:08:06.337  4077  4093 D bt_bte_conf:   version             = 1436
09-02 12:08:06.337  4077  4093 D bt_bte_conf:   clientExecutableURL = 
09-02 12:08:06.338  4077  4093 D bt_bte_conf:   serviceDescription  = 
,09-02 12:08:06.338  4077  4093 D bt_bte_conf:   documentationURL    = 
09-02 12:08:06.338  4077  4093 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-02 12:08:06.339  4077  4090 D bt_stack_manager: event_start_up_stack finished
,09-02 12:08:06.339  4077  4097 I bt_vendor: low_power_mode_cb
,09-02 12:08:06.340  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-02 12:08:06.340  4077  4089 D BluetoothAdapterProperties: Setting state to 15
,09-02 12:08:06.340  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-02 12:08:06.341  4077  4089 I BluetoothAdapterState: Entering BleOnState
,09-02 12:08:06.342  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:06.347  4077  4089 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-02 12:08:06.347  4077  4089 D BluetoothAdapterProperties: Setting state to 11
,09-02 12:08:06.347  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-02 12:08:06.359  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
09-02 12:08:06.361  4077  4077 D HeadsetService: Received start request. Starting profile...
09-02 12:08:06.364  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:06.364  4077  4077 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:08:06.364  4077  4077 D HeadsetStateMachine: make
09-02 12:08:06.367  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.377  4077  4077 D HeadsetStateMachine: max_hf_connections = 1
09-02 12:08:06.378  4077  4077 I bt_bluedroid: get_profile_interface handsfree
09-02 12:08:06.378  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 12:08:06.378  4077  4093 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-02 12:08:06.381  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:08:06.389  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
09-02 12:08:06.391  4077  4077 D A2dpService: Received start request. Starting profile...
,09-02 12:08:06.392  4077  4077 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 12:08:06.393  4077  4077 I bt_bluedroid: get_profile_interface avrcp
,09-02 12:08:06.406  4077  4077 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 12:08:06.407  4077  4077 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:08:06.407  4077  4077 D A2dpStateMachine: make
,09-02 12:08:06.410  4077  4077 I bt_bluedroid: get_profile_interface a2dp
,09-02 12:08:06.411  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 12:08:06.413  4077  4108 D A2dpStateMachine: Enter Disconnected: -2
,09-02 12:08:06.414  4077  4077 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 12:08:06.414  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:06.416  4077  4077 D HidService: Received start request. Starting profile...
,09-02 12:08:06.416  4077  4077 I bt_bluedroid: get_profile_interface hidhost
09-02 12:08:06.416  4077  4077 D HidService: setHidService(): set to: null
,09-02 12:08:06.416  4077  4093 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb395b3e5
09-02 12:08:06.416  3854  3854 D BluetoothInputDevice: Proxy object connected
09-02 12:08:06.416  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-02 12:08:06.416  3854  3854 D HidProfile: Bluetooth service connected
09-02 12:08:06.417  4077  4077 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:08:06.418  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:06.418  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:08:06.419  4077  4077 D HealthService: Received start request. Starting profile...
,09-02 12:08:06.420  4077  4077 I bt_bluedroid: get_profile_interface health
,09-02 12:08:06.422  4077  4077 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 12:08:06.422  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:06.423  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 12:08:06.424  4077  4077 D PanService: Received start request. Starting profile...
09-02 12:08:06.424  3854  3854 D PanProfile: Bluetooth service connected
09-02 12:08:06.424  4077  4077 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:08:06.424  4077  4077 I bt_bluedroid: get_profile_interface pan
,09-02 12:08:06.425  4077  4093 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 12:08:06.427  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:06.428  3854  3854 D BluetoothMap: Proxy object connected
,09-02 12:08:06.428  4077  4077 D BluetoothMapService: Received start request. Starting profile...
09-02 12:08:06.428  4077  4077 D BluetoothMapService: start()
09-02 12:08:06.428  3854  3854 D MapProfile: Bluetooth service connected
09-02 12:08:06.428  3854  3854 D BluetoothMap: getConnectedDevices()
,09-02 12:08:06.429  3854  3854 D BluetoothMap: Bluetooth is Not enabled
09-02 12:08:06.430  4077  4077 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 12:08:06.430  4077  4077 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-02 12:08:06.430  4077  4077 D BluetoothMapAppObserver: createReceiver()
,09-02 12:08:06.431  4077  4077 D BluetoothMapAppObserver: initObservers()
09-02 12:08:06.431  4077  4077 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 12:08:06.437  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:06.437  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:06.437  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:06.437  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:08:06.438  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:06.438  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:06.439  4077  4106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:06.439  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:08:06.441  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-02 12:08:06.441  4077  4077 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:08:06.441  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:06.441  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:08:06.442  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-02 12:08:06.442  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:06.442  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:06.442  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:08:06.442  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-02 12:08:06.442  4077  4089 D BluetoothAdapterProperties: ScanMode =  20
,09-02 12:08:06.442  4077  4089 D BluetoothAdapterProperties: State =  11
09-02 12:08:06.443  4077  4089 D BluetoothAdapterProperties: Setting state to 12
09-02 12:08:06.443  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 12:08:06.444  1366  2077 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:08:06.445  4077  4093 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:08:06.445  1366  1386 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:08:06.445  4077  4093 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:08:06.445  4077  4089 I BluetoothAdapterState: Entering OnState
,09-02 12:08:06.446  1366  1393 D BluetoothPan: onBluetoothStateChange on: true
,09-02 12:08:06.446  1366  1366 D BluetoothMap: Proxy object connected
09-02 12:08:06.446  1366  1366 D MapProfile: Bluetooth service connected
09-02 12:08:06.446  1366  1366 D BluetoothMap: getConnectedDevices()
,09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:06.448  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:06.448  1366  3780 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 12:08:06.449  3854  3869 D BluetoothMap: onBluetoothStateChange: up=true
09-02 12:08:06.449  1366  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:08:06.450  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 12:08:06.450  1366  1366 D PanProfile: Bluetooth service connected
09-02 12:08:06.450  1366  1366 D BluetoothInputDevice: Proxy object connected
09-02 12:08:06.451  1366  1366 D HidProfile: Bluetooth service connected
,09-02 12:08:06.451  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:06.451  3854  3867 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:08:06.451   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:08:06.451  1366  2077 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:08:06.452   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:08:06.453  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:08:06.453  1366  1366 D BluetoothA2dp: Proxy object connected
09-02 12:08:06.453   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:08:06.454   874   874 D BluetoothA2dp: Proxy object connected
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:06.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:06.454  1958  1976 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:08:06.455  3854  3869 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:08:06.456   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:08:06.456  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:06.456   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 12:08:06.457  4077  4077 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 12:08:06.458  4077  4077 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-02 12:08:06.459  4077  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:08:06.459  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.459  3854  3854 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 12:08:06.461  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.461  4077  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:08:06.462  3854  3854 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 12:08:06.463  4077  4077 D ObexServerSockets: Succeed to create listening sockets 
09-02 12:08:06.463  4077  4077 D ObexServerSockets0: startAccept()
09-02 12:08:06.463  4077  4077 D ObexServerSockets0: prepareForNewConnect()
09-02 12:08:06.465  4077  4077 D BluetoothSdpJni: sdpCreateMapMasRecordNative:,
09-02 12:08:06.465  4077  4077 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 12:08:06.465  4077  4077 D BluetoothMapService: onReceive
09-02 12:08:06.465  4077  4077 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:06.466  4077  4115 D ObexServerSockets0: Accepting socket connection...
09-02 12:08:06.465  4077  4077 D BluetoothMapService: STATE_ON
,09-02 12:08:06.466  4077  4116 D ObexServerSockets0: Accepting socket connection...
09-02 12:08:06.468  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 12:08:06.471  3854  3854 D BluetoothA2dp: Proxy object connected
09-02 12:08:06.473  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:08:06.482  1366  1366 D BluetoothPbap: Proxy object connected
,09-02 12:08:06.482  1366  1366 D PbapServerProfile: Bluetooth service connected
09-02 12:08:06.483  3854  3854 D DockEventReceiver: finishStartingService: stopping service
09-02 12:08:06.483  3854  3854 D BluetoothPbap: Proxy object connected
09-02 12:08:06.483  3854  3854 D PbapServerProfile: Bluetooth service connected
,09-02 12:08:06.490  4077  4120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:06.499  4077  4077 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 12:08:06.499  4077  4077 D ObexServerSockets0: prepareForNewConnect()
,09-02 12:08:06.502  4077  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:06.503  4077  4124 I BtOppRfcommListener: Accept thread started.
,09-02 12:08:06.545   874   874 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.546   874   874 D BluetoothHeadset: Proxy object connected
09-02 12:08:06.546  1366  3780 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.546  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-02 12:08:06.547   874   874 D BluetoothHeadset: Proxy object connected
09-02 12:08:06.548  1958  2141 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.551   874   891 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.553   874   891 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.555  1958  1972 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.556   874   891 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.564  3854  3869 D BluetoothHeadset: Proxy object connected
,09-02 12:08:06.565  3854  3854 D HeadsetProfile: Bluetooth service connected
,09-02 12:08:07.886  4077  4089 D BluetoothAdapterState: Current state: ON, message: 23
09-02 12:08:07.886  4077  4089 D BluetoothAdapterProperties: Setting state to 13
,09-02 12:08:07.887  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 12:08:07.889   874  1316 D ConnectivityService: handlePromptUnvalidated 101
,09-02 12:08:07.890  4077  4089 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 12:08:07.893  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:08:07.895  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:08:07.895  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 12:08:07.899  4077  4077 D BluetoothMapService: onReceive
09-02 12:08:07.899  4077  4077 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:07.899  4077  4077 D BluetoothMapService: STATE_TURNING_OFF
09-02 12:08:07.899  4077  4077 D BluetoothMapService: MAP Service closeService in,
,09-02 12:08:07.899  4077  4077 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 12:08:07.899  4077  4077 D ObexServerSockets0: shutdown(block = true)
09-02 12:08:07.901  4077  4115 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 12:08:07.902  4077  4077 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-02 12:08:07.902  4077  4116 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 12:08:07.903  4077  4077 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 12:08:07.906  4077  4102 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 12:08:07.907  4077  4077 I BtOppRfcommListener: stopping Accept Thread
09-02 12:08:07.908  4077  4124 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
09-02 12:08:07.910  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 12:08:07.913  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:07.913  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:08:07.913  4077  4124 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 12:08:07.914  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:07.914  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:07.917  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:07.917  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:08:07.918  4077  4077 D HeadsetService: Received stop request...Stopping profile...
09-02 12:08:07.919  3781  3781 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:08:07.919  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:07.922  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:07.922   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:08:07.922   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:08:07.922  1366  1386 D BluetoothHeadset: Proxy object disconnected
09-02 12:08:07.923  3854  3865 D BluetoothHeadset: Proxy object disconnected
09-02 12:08:07.923  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:07.923   874   874 D BluetoothHeadset: Proxy object disconnected
09-02 12:08:07.924  1958  2305 D BluetoothHeadset: Proxy object disconnected
09-02 12:08:07.925  3854  3854 D DockEventReceiver: finishStartingService: stopping service
09-02 12:08:07.926  4077  4077 D A2dpService: Received stop request...Stopping profile...
,09-02 12:08:07.926  4077  4108 D A2dpStateMachine: Exit Disconnected: -1
09-02 12:08:07.927  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-02 12:08:07.929   874   874 D BluetoothA2dp: Proxy object disconnected
09-02 12:08:07.929  1366  1366 D BluetoothA2dp: Proxy object disconnected
,09-02 12:08:07.931  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:08:07.932  4077  4077 D HidService: Received stop request...Stopping profile...
09-02 12:08:07.932  4077  4077 D HidService: Stopping Bluetooth HidService
,09-02 12:08:07.933  4077  4077 D HealthService: Received stop request...Stopping profile...
,09-02 12:08:07.933  1366  1366 D BluetoothInputDevice: Proxy object disconnected
,09-02 12:08:07.934  1366  1366 D HidProfile: Bluetooth service disconnected
,09-02 12:08:07.934  3854  3854 D HeadsetProfile: Bluetooth service disconnected
,09-02 12:08:07.934  3854  3854 D BluetoothA2dp: Proxy object disconnected
09-02 12:08:07.934  4077  4077 D PanService: Received stop request...Stopping profile...
09-02 12:08:07.935  3854  3854 D BluetoothInputDevice: Proxy object disconnected
09-02 12:08:07.936  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-02 12:08:07.935  3854  3854 D HidProfile: Bluetooth service disconnected
09-02 12:08:07.936  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:07.936  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:07.936  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:07.936  3854  3854 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:08:07.936  3854  3854 D PanProfile: Bluetooth service disconnected
09-02 12:08:07.936  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:08:07.936  1366  1366 D PanProfile: Bluetooth service disconnected
09-02 12:08:07.937  4077  4077 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 12:08:07.937  4077  4077 D BluetoothMapService: stop()
09-02 12:08:07.937  4077  4077 D BluetoothMapAppObserver: deinitObservers()
09-02 12:08:07.937  4077  4077 D BluetoothMapAppObserver: removeReceiver()
09-02 12:08:07.938  3854  3854 D BluetoothMap: Proxy object disconnected
09-02 12:08:07.938  3854  3854 D MapProfile: Bluetooth service disconnected
09-02 12:08:07.938  1366  1366 D BluetoothMap: Proxy object disconnected
09-02 12:08:07.938  1366  1366 D MapProfile: Bluetooth service disconnected
09-02 12:08:07.939  4077  4077 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:08:07.939  4077  4077 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:08:07.939  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-02 12:08:07.939  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:08:07.939  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:08:07.940  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 12:08:07.940  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-02 12:08:07.940  4077  4093 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
09-02 12:08:07.940  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:07.940  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:07.940  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:07.941  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 12:08:07.941  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:08:07.941  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 12:08:07.941  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 12:08:07.941  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:08:07.941  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:08:07.941  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:08:07.943  3854  3854 D BluetoothPbap: Proxy object disconnected
,09-02 12:08:07.943  3854  3854 D PbapServerProfile: Bluetooth service disconnected
,09-02 12:08:07.943  1366  1366 D BluetoothPbap: Proxy object disconnected
,09-02 12:08:07.943  1366  1366 D PbapServerProfile: Bluetooth service disconnected
09-02 12:08:07.943  4077  4077 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:08:07.943  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:07.943  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:07.943  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:07.944  4077  4077 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:08:07.944  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 12:08:07.944  4077  4077 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:08:07.944  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-02 12:08:07.944  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:07.944  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:08:07.945  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:07.945  4077  4077 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-02 12:08:07.945  4077  4093 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-02 12:08:07.945  4077  4077 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:08:07.946  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-02 12:08:07.946  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:07.946  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:08:07.946  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:07.946  4077  4077 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:08:07.947  4077  4077 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 12:08:07.947  4077  4077 D BluetoothMapService: MAP Service closeService in
09-02 12:08:07.948  4077  4077 V BluetoothAdapterState: isTurningOff()=true
,09-02 12:08:07.948  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:07.948  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:07.948  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:07.949  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 12:08:07.949  4077  4089 D BluetoothAdapterProperties: Setting state to 15
,09-02 12:08:07.949  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-02 12:08:07.949  1366  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 12:08:07.950  4077  4089 I BluetoothAdapterState: Entering BleOnState
09-02 12:08:07.950  1366  2077 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:08:07.950  4077  4077 D BluetoothMapService: cleanup()
09-02 12:08:07.950  4077  4077 D BluetoothMapService: MAP Service closeService in
09-02 12:08:07.950  1366  3780 D BluetoothPan: onBluetoothStateChange on: false
09-02 12:08:07.951  1366  1393 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:08:07.952  3854  3869 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:08:07.953  1366  2077 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 12:08:07.953  3854  3867 D BluetoothPan: onBluetoothStateChange on: false
,09-02 12:08:07.954   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:08:07.954  1366  3780 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:08:07.954   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:08:07.954  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:08:07.955   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:08:07.955  1958  1976 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:08:07.955  3854  3869 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 12:08:07.956  3854  3867 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 12:08:07.957  3854  3865 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:08:07.957   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 12:08:07.957  4077  4089 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 12:08:07.957  4077  4089 D BluetoothAdapterProperties: Setting state to 16
09-02 12:08:07.957  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-02 12:08:07.958  4077  4089 D BluetoothAdapterProperties: onBleDisable
,09-02 12:08:07.958  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:08:07.958  4077  4090 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 12:08:07.959  4077  4099 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 12:08:07.959  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 12:08:07.961  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 12:08:07.962  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:07.962  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:08:07.963  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:07.964  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:07.965  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:07.966  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:08:07.971  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:08:08.159  4077  4093 I bt_hci  : shut_down
,09-02 12:08:08.160  4077  4097 D bt_hwcfg: hw_epilog_process
,09-02 12:08:08.161  4077  4097 I bt_vendor: low_power_mode_cb
,09-02 12:08:08.187  4077  4097 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 12:08:08.187  4077  4097 I bt_vendor: epilog_cb
09-02 12:08:08.187  4077  4097 I bt_hci  : epilog_finished_callback
,09-02 12:08:08.199  4077  4093 I bt_hci_h4: hal_close
,09-02 12:08:08.200  4077  4093 I bt_userial_vendor: device fd = 51 close
,09-02 12:08:08.337  4077  4090 D bt_stack_manager: event_shut_down_stack finished.
,09-02 12:08:08.338  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 12:08:08.344  4077  4089 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 12:08:08.344  4077  4077 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:08:08.346  4077  4077 D BtGatt.GattService: Received stop request...Stopping profile...
,09-02 12:08:08.346  4077  4077 D BtGatt.GattService: stop()
09-02 12:08:08.347  4077  4077 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 12:08:08.351  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:08.352  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:08.352  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 12:08:08.353  4077  4077 V BluetoothAdapterState: isBleTurningOff()=true
09-02 12:08:08.353  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-02 12:08:08.354  4077  4089 D BluetoothAdapterProperties: Setting state to 10
09-02 12:08:08.354  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 12:08:08.356  4077  4089 I BluetoothAdapterState: Entering OffState
,09-02 12:08:08.360   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-02 12:08:08.390  4077  4077 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-02 12:08:08.391  4077  4077 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 12:08:08.391  4077  4090 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-02 12:08:08.400  4077  4090 D bt_stack_manager: event_clean_up_stack finished.
,09-02 12:08:08.401  4077  4077 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 12:08:08.408  4077  4077 I art     : System.exit called, status: 0
,09-02 12:08:08.408  4077  4077 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:08:08.453   874  1904 I ActivityManager: Process com.android.bluetooth (pid 4077) has died
,09-02 12:08:10.883  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:08:10.884  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:13.541   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-02 12:08:13.553  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-02 12:08:13.567   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 12:08:13.567   874   894 I Adreno  : Build Date                       : 10/20/15
09-02 12:08:13.567   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 12:08:13.567   874   894 I Adreno  : Local Branch                     : M14
09-02 12:08:13.567   874   894 I Adreno  : Remote Branch                    : 
09-02 12:08:13.567   874   894 I Adreno  : Remote Branch                    : 
09-02 12:08:13.567   874   894 I Adreno  : Reconstruct Branch               : 
,09-02 12:08:13.624   280   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (325 us)
,09-02 12:08:13.890  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:13.891  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a61186f added. We now have 6 listener(s)
,09-02 12:08:13.891  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:13.894  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:13.894  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a3697c added. We now have 7 listener(s)
09-02 12:08:13.895  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:13.896  3781  3832 I System.out: IsBluetoothEnabled
,09-02 12:08:13.906  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:13.950   874   891 I ActivityManager: Start proc 4137:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 12:08:14.074  4137  4137 D AdapterServiceConfig: Adding HeadsetService
,09-02 12:08:14.075  4137  4137 D AdapterServiceConfig: Adding A2dpService
,09-02 12:08:14.075  4137  4137 D AdapterServiceConfig: Adding HidService
09-02 12:08:14.075  4137  4137 D AdapterServiceConfig: Adding HealthService
,09-02 12:08:14.075  4137  4137 D AdapterServiceConfig: Adding PanService
,09-02 12:08:14.076  4137  4137 D AdapterServiceConfig: Adding GattService
09-02 12:08:14.076  4137  4137 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 12:08:14.093   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc1c3c1:true
,09-02 12:08:14.094  4137  4137 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 12:08:14.098  4137  4137 I bt_bluedroid: init
,09-02 12:08:14.099  4137  4149 I BluetoothAdapterState: Entering OffState
,09-02 12:08:14.108  4137  4150 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 12:08:14.109  4137  4150 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-02 12:08:14.109  4137  4150 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 12:08:14.110  4137  4150 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 12:08:14.111  4137  4137 I bt_bluedroid: get_profile_interface socket
,09-02 12:08:14.117  4137  4137 I bt_bluedroid: get_profile_interface sdp
09-02 12:08:14.119  4137  4153 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-02 12:08:14.122  4137  4148 I bt_bluedroid: config_hci_snoop_log
,09-02 12:08:14.122  4137  4153 D BluetoothAdapterProperties: Name is: Nexus 6
09-02 12:08:14.126   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 12:08:14.136  4137  4149 D BluetoothAdapterState: Current state: OFF, message: 0
09-02 12:08:14.136  4137  4149 D BluetoothAdapterProperties: Setting state to 14
,09-02 12:08:14.136  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-02 12:08:14.138  4137  4149 D BluetoothBondStateMachine: make
,09-02 12:08:14.142  4137  4154 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 12:08:14.146  4137  4149 I BluetoothAdapterState: Entering PendingCommandState
,09-02 12:08:14.148  4137  4137 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 12:08:14.153  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:14.154  4137  4137 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:08:14.155  4137  4137 D BtGatt.GattService: Received start request. Starting profile...
,09-02 12:08:14.155  4137  4137 D BtGatt.GattService: start()
09-02 12:08:14.155  4137  4137 I bt_bluedroid: get_profile_interface gatt
,09-02 12:08:14.156  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
09-02 12:08:14.156  4137  4137 D BtGatt.AdvertiseManager: advertise manager created
,09-02 12:08:14.165  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:14.165  4137  4137 V BluetoothAdapterState: isTurningOn()=false
09-02 12:08:14.165  4137  4137 V BluetoothAdapterState: isBleTurningOn()=true
,09-02 12:08:14.165  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:14.166  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-02 12:08:14.167  4137  4149 I bt_bluedroid: enable
09-02 12:08:14.167  4137  4150 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
09-02 12:08:14.168  4137  4150 I bt_hci  : start_up
,09-02 12:08:14.182  4137  4150 I bt_vendor: alloc value 0xb39fc189
,09-02 12:08:14.183  4137  4150 I bt_vendor: init
09-02 12:08:14.183  4137  4150 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-02 12:08:14.183  4137  4150 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 12:08:14.239  3781  3781 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 12:08:14.239  3781  3781 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-02 12:08:14.275   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-02 12:08:14.276  3781  3781 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@35af08d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@29fe205, 16908290=android.view.AbsSavedState$1@29fe205}, android:focusedViewId=100}]}]
09-02 12:08:14.276  3781  3781 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-02 12:08:14.276  3781  3781 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 12:08:14.277  3781  3781 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-02 12:08:14.282   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-02 12:08:14.286   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-02 12:08:14.288   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-02 12:08:14.289   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-02 12:08:14.289  4137  4150 D bt_hci  : start_up starting async portion
09-02 12:08:14.289  4137  4157 I bt_hci  : event_finish_startup
09-02 12:08:14.289  4137  4157 I bt_hci_h4: hal_open
09-02 12:08:14.289  4137  4157 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 12:08:14.300  4137  4157 I bt_userial_vendor: device fd = 51 open
,09-02 12:08:14.332  4137  4157 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:08:14.332   874   883 I art     : Background partial concurrent mark sweep GC freed 24489(1839KB) AllocSpace objects, 13(412KB) LOS objects, 33% free, 29MB/43MB, paused 1.430ms total 116.454ms
,09-02 12:08:14.364  4137  4157 D bt_hwcfg: Chipset BCM4354A2
,09-02 12:08:14.364  4137  4157 D bt_hwcfg: Target name = [BCM4354A2]
09-02 12:08:14.364  4137  4157 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 12:08:14.549   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-02 12:08:14.553   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-02 12:08:14.554   874  1338 D SurfaceControl: Excessive delay in setPowerMode(): 268ms
,09-02 12:08:14.557   874   894 I DreamManagerService: Entering dreamland.
,09-02 12:08:14.558   874   894 I PowerManagerService: Dozing...
,09-02 12:08:14.560   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-02 12:08:14.603   374  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-02 12:08:14.603   374  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-02 12:08:14.609   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:08:14.612   874  1314 E native  : do suspend false
,09-02 12:08:14.614  1947  4160 D NfcService: Discovery configuration equal, not updating.
,09-02 12:08:14.630   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:08:14.634   874  1314 E native  : do suspend true
,09-02 12:08:14.748   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-02 12:08:14.748   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-02 12:08:14.971  4137  4157 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 12:08:14.972  4137  4157 D bt_hwcfg: Settlement delay -- 100 ms
09-02 12:08:14.973  4137  4157 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 12:08:15.089  4137  4157 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 12:08:15.090  4137  4157 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 12:08:15.120  4137  4157 I bt_hwcfg: vendor lib fwcfg completed
,09-02 12:08:15.120  4137  4157 I bt_vendor: firmware callback
09-02 12:08:15.121  4137  4157 I bt_hci  : firmware_config_callback
,09-02 12:08:15.131  4137  4164 I bt_btu  : btu_task pending for preload complete event
09-02 12:08:15.132  4137  4164 I bt_btu_task: Bluetooth chip preload is complete
,09-02 12:08:15.132  4137  4164 I bt_btu  : btu_task received preload complete event
,09-02 12:08:15.141  4137  4164 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 12:08:15.142  4137  4164 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 12:08:15.142  4137  4164 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:08:15.142  4137  4164 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 12:08:15.143  4137  4164 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:08:15.143  4137  4164 I         : BTE_InitTraceLevels -- TRC_A2D
,09-02 12:08:15.143  4137  4164 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:08:15.143  4137  4164 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 12:08:15.144  4137  4164 I         : BTE_InitTraceLevels -- TRC_GAP
,09-02 12:08:15.144  4137  4164 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:08:15.144  4137  4164 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:08:15.144  4137  4164 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:08:15.145  4137  4164 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 12:08:15.145  4137  4164 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:08:15.145  4137  4164 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 12:08:15.284  4137  4164 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3979d9d
,09-02 12:08:15.285  4137  4164 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3979d9d 
,09-02 12:08:15.310  4137  4153 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 12:08:15.311  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 12:08:15.312  4137  4153 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 12:08:15.314  4137  4153 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 12:08:15.316  4137  4153 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:08:15.317  4137  4153 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:08:15.317  4137  4153 D bt_hci  : do_postload posting postload work item
,09-02 12:08:15.318  4137  4157 I bt_hci  : event_postload
,09-02 12:08:15.318  4137  4157 I bt_vendor: sco_config_cb
09-02 12:08:15.318  4137  4157 I bt_hci  : sco_config_callback postload finished.,
09-02 12:08:15.320  4137  4153 D bt_bte_conf: Device ID record 1 : primary
09-02 12:08:15.320  4137  4153 D bt_bte_conf:   vendorId            = 000f
09-02 12:08:15.320  4137  4153 D bt_bte_conf:   vendorIdSource      = 0001
,09-02 12:08:15.320  4137  4153 D bt_bte_conf:   product             = 1200
09-02 12:08:15.320  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:15.321  4137  4153 D bt_bte_conf:   version             = 1436
09-02 12:08:15.321  4137  4153 D bt_bte_conf:   clientExecutableURL = 
09-02 12:08:15.321  4137  4153 D bt_bte_conf:   serviceDescription  = 
,09-02 12:08:15.321  4137  4153 D bt_bte_conf:   documentationURL    = 
09-02 12:08:15.321  4137  4153 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-02 12:08:15.322  4137  4150 D bt_stack_manager: event_start_up_stack finished
,09-02 12:08:15.323  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-02 12:08:15.323  4137  4149 D BluetoothAdapterProperties: Setting state to 15
09-02 12:08:15.324  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-02 12:08:15.325  4137  4149 I BluetoothAdapterState: Entering BleOnState
09-02 12:08:15.326  4137  4157 I bt_vendor: low_power_mode_cb
,09-02 12:08:15.331  4137  4149 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-02 12:08:15.331  4137  4149 D BluetoothAdapterProperties: Setting state to 11
,09-02 12:08:15.331  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-02 12:08:15.343  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:15.344  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:15.346  4137  4137 D HeadsetService: Received start request. Starting profile...
,09-02 12:08:15.349  4137  4137 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 12:08:15.349  4137  4137 D HeadsetStateMachine: make
,09-02 12:08:15.362  4137  4137 D HeadsetStateMachine: max_hf_connections = 1
,09-02 12:08:15.362  4137  4137 I bt_bluedroid: get_profile_interface handsfree
,09-02 12:08:15.365  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-02 12:08:15.365  4137  4153 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-02 12:08:15.368  4137  4149 I BluetoothAdapterState: Entering PendingCommandState
09-02 12:08:15.370  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:15.371  4137  4137 D A2dpService: Received start request. Starting profile...
09-02 12:08:15.371  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 12:08:15.371  4137  4137 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 12:08:15.372  4137  4137 I bt_bluedroid: get_profile_interface avrcp
,09-02 12:08:15.381  4137  4137 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 12:08:15.381  4137  4137 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-02 12:08:15.381  4137  4137 D A2dpStateMachine: make
,09-02 12:08:15.382  4137  4137 I bt_bluedroid: get_profile_interface a2dp
,09-02 12:08:15.384  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-02 12:08:15.386  4137  4173 D A2dpStateMachine: Enter Disconnected: -2
,09-02 12:08:15.389  4137  4137 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 12:08:15.391  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:15.392  4137  4137 D HidService: Received start request. Starting profile...
,09-02 12:08:15.393  4137  4137 I bt_bluedroid: get_profile_interface hidhost
,09-02 12:08:15.393  4137  4153 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb395b3e5
09-02 12:08:15.393  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-02 12:08:15.393  4137  4137 D HidService: setHidService(): set to: null
,09-02 12:08:15.395  4137  4137 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 12:08:15.396  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:15.397  4137  4137 D HealthService: Received start request. Starting profile...
,09-02 12:08:15.400  4137  4137 I bt_bluedroid: get_profile_interface health
,09-02 12:08:15.401  4137  4137 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 12:08:15.403  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:15.403  4137  4137 D PanService: Received start request. Starting profile...,
,09-02 12:08:15.404  4137  4137 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-02 12:08:15.404  4137  4137 I bt_bluedroid: get_profile_interface pan
,09-02 12:08:15.404  4137  4153 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 12:08:15.407  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:15.407  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:08:15.407  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:15.407  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 12:08:15.412  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:15.413  4137  4137 D BluetoothMapService: Received start request. Starting profile...
,09-02 12:08:15.413  4137  4137 D BluetoothMapService: start()
,09-02 12:08:15.417  4137  4137 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 12:08:15.419  4137  4137 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-02 12:08:15.419  4137  4137 D BluetoothMapAppObserver: createReceiver()
,09-02 12:08:15.420  4137  4137 D BluetoothMapAppObserver: initObservers()
,09-02 12:08:15.421  4137  4137 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 12:08:15.432  4137  4171 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 12:08:15.436  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:15.436  4137  4137 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:15.437  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:15.437  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:15.438  4137  4137 V BluetoothAdapterState: isTurningOff()=false
09-02 12:08:15.438  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,09-02 12:08:15.438  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:15.439  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:15.439  4137  4137 V BluetoothAdapterState: isTurningOff()=false
09-02 12:08:15.440  4137  4137 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:15.440  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:15.440  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:15.441  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,09-02 12:08:15.441  4137  4137 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:15.441  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:15.442  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:15.442  4137  4137 V BluetoothAdapterState: isTurningOff()=false
09-02 12:08:15.442  4137  4137 V BluetoothAdapterState: isTurningOn()=true
09-02 12:08:15.443  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
09-02 12:08:15.443  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
09-02 12:08:15.443  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-02 12:08:15.444  4137  4149 D BluetoothAdapterProperties: ScanMode =  20
09-02 12:08:15.444  4137  4149 D BluetoothAdapterProperties: State =  11
,09-02 12:08:15.444  4137  4149 D BluetoothAdapterProperties: Setting state to 12
,09-02 12:08:15.444  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 12:08:15.446  1366  3780 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:08:15.446  4137  4153 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:08:15.446  4137  4153 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:08:15.447  4137  4149 I BluetoothAdapterState: Entering OnState
,09-02 12:08:15.449  1366  1386 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:08:15.453  4137  4137 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 12:08:15.454  4137  4137 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:15.454  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:15.455  1366  1393 D BluetoothPan: onBluetoothStateChange on: true
09-02 12:08:15.458  4137  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:15.459  1366  2077 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:08:15.459  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:15.462  3854  3867 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:08:15.463  4137  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:15.465  4137  4137 D ObexServerSockets: Succeed to create listening sockets 
,09-02 12:08:15.465  1366  3780 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 12:08:15.465  4137  4137 D ObexServerSockets0: startAccept()
,09-02 12:08:15.465  4137  4137 D ObexServerSockets0: prepareForNewConnect()
,09-02 12:08:15.469  3854  3865 D BluetoothPan: onBluetoothStateChange on: true
,09-02 12:08:15.469  4137  4137 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 12:08:15.469  4137  4137 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-02 12:08:15.471   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:08:15.472  1366  1366 D BluetoothMap: Proxy object connected
09-02 12:08:15.472  3854  3854 D BluetoothMap: Proxy object connected
,09-02 12:08:15.472  3854  3854 D MapProfile: Bluetooth service connected
09-02 12:08:15.472  3854  3854 D BluetoothMap: getConnectedDevices()
09-02 12:08:15.472  1366  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:08:15.472  1366  1366 D MapProfile: Bluetooth service connected
09-02 12:08:15.473  1366  1366 D BluetoothMap: getConnectedDevices()
,09-02 12:08:15.475  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 12:08:15.475   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:08:15.475  3854  3854 D PanProfile: Bluetooth service connected
,09-02 12:08:15.476  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:08:15.476  1366  1366 D PanProfile: Bluetooth service connected
09-02 12:08:15.476  1366  1366 D BluetoothInputDevice: Proxy object connected
,09-02 12:08:15.476  1366  1366 D HidProfile: Bluetooth service connected
09-02 12:08:15.476  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 12:08:15.476  4137  4179 D ObexServerSockets0: Accepting socket connection...
09-02 12:08:15.478  1366  1366 D BluetoothA2dp: Proxy object connected
09-02 12:08:15.478   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:08:15.478  4137  4180 D ObexServerSockets0: Accepting socket connection...
09-02 12:08:15.479  3854  3854 D BluetoothInputDevice: Proxy object connected
,09-02 12:08:15.479  3854  3854 D HidProfile: Bluetooth service connected
09-02 12:08:15.479   874   874 D BluetoothA2dp: Proxy object connected
09-02 12:08:15.479  1958  2305 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 12:08:15.479  3854  3867 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 12:08:15.481  3854  3869 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:08:15.483  3854  3867 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:08:15.483   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 12:08:15.484  3854  3854 D BluetoothA2dp: Proxy object connected
09-02 12:08:15.485   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 12:08:15.486  4137  4137 D BluetoothMapService: onReceive
,09-02 12:08:15.486  4137  4137 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:15.486  4137  4137 D BluetoothMapService: STATE_ON
09-02 12:08:15.488  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:15.495  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:08:15.500  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:08:15.501  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 12:08:15.511  1366  1366 D BluetoothPbap: Proxy object connected
09-02 12:08:15.511  3854  3854 D BluetoothPbap: Proxy object connected
09-02 12:08:15.511  1366  1366 D PbapServerProfile: Bluetooth service connected
09-02 12:08:15.511  3854  3854 D PbapServerProfile: Bluetooth service connected
09-02 12:08:15.511  4137  4137 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 12:08:15.511  4137  4137 D ObexServerSockets0: prepareForNewConnect()
,09-02 12:08:15.521  4137  4185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:15.549   874   874 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.549   874   874 D BluetoothHeadset: Proxy object connected
09-02 12:08:15.549  1366  2077 D BluetoothHeadset: Proxy object connected
09-02 12:08:15.549  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-02 12:08:15.550  3854  3869 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.551   874   874 D BluetoothHeadset: Proxy object connected
09-02 12:08:15.551  3854  3854 D HeadsetProfile: Bluetooth service connected
,09-02 12:08:15.551  1958  1976 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.552  4137  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:15.553  4137  4189 I BtOppRfcommListener: Accept thread started.
,09-02 12:08:15.571   874   891 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.576   874   891 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.579  1958  2141 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.584  3854  3867 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.584  3854  3854 D HeadsetProfile: Bluetooth service connected
09-02 12:08:15.584   874   891 D BluetoothHeadset: Proxy object connected
,09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:15.928  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:15.934  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:15.937  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:15.938  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9cef25a added. We now have 8 listener(s)
09-02 12:08:15.938  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:15.944   874  1477 D WifiService: setWifiEnabled: false pid=3781, uid=10000
,09-02 12:08:15.945   874  1477 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:08:15.957  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:15.958   874   884 D WifiService: setWifiEnabled: true pid=3781, uid=10000
09-02 12:08:15.958   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 12:08:15.977   874  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:15.994  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:15.998  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:16.005   874  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-02 12:08:16.006   874  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-02 12:08:16.007   874  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-02 12:08:16.007   874  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-02 12:08:16.008   874  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 12:08:16.009   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 12:08:16.009   874  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 12:08:16.034   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-02 12:08:16.034   874  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
09-02 12:08:16.034   874  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-02 12:08:16.036   370   872 D CommandListener: Setting iface cfg
,09-02 12:08:16.045   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-02 12:08:16.045   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:08:16.046   874  1314 E native  : do suspend true
,09-02 12:08:16.061   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 12:08:16.061   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:08:16.076   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 12:08:16.141   874  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 12:08:16.143  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 12:08:16.170   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 12:08:16.171   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 12:08:16.594  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 12:08:16.639  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 12:08:16.640  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 12:08:16.650   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 12:08:16.667   874  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 12:08:16.668   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 12:08:16.668   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 12:08:16.693   874  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:08:16.706   370   872 D CommandListener: Setting iface cfg
,09-02 12:08:16.707   874  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,09-02 12:08:16.713   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 12:08:16.732   874  4197 D DhcpClient: Receive thread started
,09-02 12:08:16.816   874  1314 E native  : do suspend false
,09-02 12:08:16.836   874  2075 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 12:08:16.913   874  4197 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,09-02 12:08:16.914   874  2075 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,09-02 12:08:16.919   874  2075 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 12:08:16.941   874  4197 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 12:08:16.942   874  2075 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 12:08:16.949   370   872 D CommandListener: Setting iface cfg
,09-02 12:08:16.962   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-02 12:08:16.964   874  1314 E native  : do suspend true
09-02 12:08:16.964   874  2075 D DhcpClient: Scheduling renewal in 86399s
,09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:16.984  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:16.986   874  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 12:08:16.987   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 12:08:16.988   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 12:08:16.989  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:16.990   874  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 12:08:16.992   874  1316 D ConnectivityService: Adding iface wlan0 to network 102
,09-02 12:08:17.007  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 12:08:17.007  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-02 12:08:17.009  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@35af08d Bundle[{}]
09-02 12:08:17.010  3781  3832 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 12:08:17.010  3781  3832 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 12:08:17.011  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-02 12:08:17.011  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 12:08:17.012  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 12:08:17.012  3781  3832 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 12:08:17.017  3781  3832 I System.out: Running OutgoingSocketThread
09-02 12:08:17.018  3781  4199 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,09-02 12:08:17.019  3781  4199 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48863
09-02 12:08:17.019  3781  4199 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,09-02 12:08:17.038   874  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 12:08:17.039   874  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-02 12:08:17.044   874  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-02 12:08:17.047   874  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-02 12:08:17.050   874  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-02 12:08:17.060   874  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-02 12:08:17.066   874  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-02 12:08:17.066   874  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-02 12:08:17.067   874  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-02 12:08:17.067   874  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-02 12:08:17.067   874  1316 D ConnectivityService:    accepting network in place of null
,09-02 12:08:17.069   874  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 12:08:17.070   874  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 12:08:17.106   874  4196 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153737, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 12:08:17.144   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:08:17.204   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 12:08:17.211   874  4195 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:802::200e
,09-02 12:08:17.214   874  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 12:08:17.215   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:17.223   874  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-02 12:08:17.226   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:17.242  3781  3781 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:08:17.250  3781  3781 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:17.253  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 12:08:17.259  1701  1701 D SystemUpdateService: onCreate
,09-02 12:08:17.264  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 12:08:17.283  1701  4207 I SystemUpdateService: active receiver: enabled
,09-02 12:08:17.288  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 12:08:17.290  1701  2516 I iu.UploadsManager: num queued entries: 0
09-02 12:08:17.291  1701  2516 I iu.UploadsManager: num updated entries: 0
09-02 12:08:17.291  1701  2516 I iu.SyncManager: NEXT; no task
,09-02 12:08:17.310  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 12:08:17.312  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 12:08:17.314  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:17.319  1701  4207 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 12:08:17.319   874  4195 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 10:08:17 GMT], X-Android-Received-Millis=[1472810897318], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472810897279]}
,09-02 12:08:17.322   874  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-02 12:08:17.323   874  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-02 12:08:17.323   874  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 12:08:17.324  1701  4210 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-02 12:08:17.324  1701  4210 W BaseAppContext: Using Auth Proxy for data requests.
09-02 12:08:17.324   874  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 12:08:17.328  3910  3910 D SprintDMHelper: simOperator: 
,09-02 12:08:17.328  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 12:08:17.330  1701  4210 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 12:08:17.331  1701  4207 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 12:08:17.332  1701  4207 I SystemUpdateService: now status is 0 (complete)
09-02 12:08:17.332  1701  4207 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 12:08:17.332  1701  4207 I SystemUpdateService: file has been verified
09-02 12:08:17.332  1701  4207 I SystemUpdateService: OTA package size = 12249756
,09-02 12:08:17.343  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:08:17.347  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 12:08:17.356  1701  4207 I SystemUpdateService: showing system update notification
,09-02 12:08:17.387  1701  1701 D SystemUpdateService: onDestroy
,09-02 12:08:17.394  1507  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 12:08:17.394  1507  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-02 12:08:17.395  1507  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 12:08:17.396  1507  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 12:08:17.408  1701  4210 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-02 12:08:17.455  3064  4213 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 12:08:18.018  3781  3832 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,09-02 12:08:18.019  3781  3832 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,09-02 12:08:18.021  3781  3832 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,09-02 12:08:18.022  3781  3832 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 12:08:18.023  3781  3832 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,09-02 12:08:18.025  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:08:18.025  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690cc8b added. We now have 2 listener(s)
,09-02 12:08:18.027  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.027  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:18.027  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.027  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:18.027  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ba168 added. We now have 9 listener(s)
09-02 12:08:18.027  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:18.028  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:08:18.033  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:18.044  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:08:18.047  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:18.048  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:08:18.048  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:18.048  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179da26 added. We now have 3 listener(s)
,09-02 12:08:18.052  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:18.054  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:08:18.054  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:18.055  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:18.055  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:18.055  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bda667 added. We now have 10 listener(s)
09-02 12:08:18.056  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.056  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:08:18.056  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:18.056  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:18.056  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:08:18.057  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:08:18.057  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.057  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:18.057  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.058  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690cc8b removed from the list
,09-02 12:08:18.058  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.058  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ba168 removed from the list
09-02 12:08:18.058  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:18.059  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.060  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.060  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.061  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.062  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:08:18.062  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.062  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87ba168 not in the list
,09-02 12:08:18.063  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.063  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.063  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:18.063  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.064  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.064  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bda667 removed from the list
,09-02 12:08:18.064  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.064  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.064  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.064  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.064  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179da26 removed from the list
09-02 12:08:18.065  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:08:18.065  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41d6c14 added. We now have 2 listener(s)
09-02 12:08:18.067  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.067  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:18.067  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.067  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:18.067  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed4cbd added. We now have 9 listener(s)
,09-02 12:08:18.067  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.068  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:08:18.070  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:18.077  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:18.079  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:18.079  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:18.079  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:18.079  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f44203 added. We now have 3 listener(s)
,09-02 12:08:18.081  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.081  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:18.081  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:18.082  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:18.082  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3580 added. We now have 10 listener(s)
09-02 12:08:18.082  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.082  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:18.082  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-02 12:08:18.082  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:08:18.082  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:18.082  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:18.082  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:08:18.085  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:18.086  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:08:18.086  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:08:18.090  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:08:18.091  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:08:18.091  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:08:18.094  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:08:18.094  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:08:18.094  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:08:18.095  3781  3832 D BluetoothAdapter: STATE_ON
,09-02 12:08:18.098  4137  4147 D BtGatt.GattService: registerClient() - UUID=fb9e7dda-3bc6-4904-b67d-614c40c268ac
,09-02 12:08:18.099  4137  4153 D BtGatt.GattService: onClientRegistered() - UUID=fb9e7dda-3bc6-4904-b67d-614c40c268ac, clientIf=5
,09-02 12:08:18.100  3781  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 12:08:18.101  4137  4178 D BtGatt.GattService: start scan with filters
,09-02 12:08:18.105  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:08:18.105  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 12:08:18.105  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:08:18.105  4137  4156 D BtGatt.ScanManager: handling starting scan
09-02 12:08:18.105  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:08:18.108  4137  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fada051
,09-02 12:08:18.108  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:08:18.108  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:08:18.108  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:08:18.110  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:08:18.112  4137  4153 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:08:18.112  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.113  4137  4156 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:08:18.113  3781  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 12:08:18.113  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:18.113  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:08:18.113  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.113  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 12:08:18.114  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 12:08:18.114  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:08:18.114  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:08:18.114  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:08:18.114  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:08:18.114  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:08:18.115  3781  3832 D BluetoothAdapter: STATE_ON
,09-02 12:08:18.116  4137  4147 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:08:18.116  4137  4178 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:08:18.117  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:08:18.117  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 12:08:18.117  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:08:18.117  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 12:08:18.117  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:08:18.118  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:08:18.118  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:08:18.118  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 12:08:18.118  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:08:18.119  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:18.120  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:08:18.120  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:18.121  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:08:18.121  4137  4153 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 12:08:18.121  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.122  4137  4156 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:08:18.122  4137  4156 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 12:08:18.124  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-02 12:08:18.124  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:18.124  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:08:18.125  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:08:18.125  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.125  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:08:18.125  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.125  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41d6c14 removed from the list
,09-02 12:08:18.125  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:08:18.125  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed4cbd removed from the list
09-02 12:08:18.125  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:18.126  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.126  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.126  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.127  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.127  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 12:08:18.127  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.127  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed4cbd not in the list
,09-02 12:08:18.127  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.127  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.128  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:18.128  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:08:18.128  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.129  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3580 removed from the list
09-02 12:08:18.129  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.129  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.129  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.129  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.129  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f44203 removed from the list
09-02 12:08:18.130  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:08:18.130  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5229ac added. We now have 2 listener(s)
09-02 12:08:18.132  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.132  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:18.133  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:18.133  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:18.133  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b65675 added. We now have 9 listener(s)
09-02 12:08:18.133  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.133  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:08:18.135  4137  4153 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:08:18.135  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.137  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:18.141  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:18.141  4137  4153 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 12:08:18.142  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.143  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.144  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:18.144  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:18.144  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb1ee7b added. We now have 3 listener(s)
09-02 12:08:18.146  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.146  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:18.146  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.146  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:18.146  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:18.146  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e3498 added. We now have 10 listener(s)
09-02 12:08:18.146  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:18.147  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:18.147  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:18.147  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:08:18.148  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:08:18.148  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:18.148  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:08:18.151  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:18.151  4137  4153 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 12:08:18.151  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.151  4137  4156 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:08:18.154  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:08:18.154  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:08:18.157  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:08:18.158  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 12:08:18.158  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:08:18.158  4137  4153 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:08:18.159  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.159  4137  4156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 12:08:18.161  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:08:18.161  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:08:18.162  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:08:18.162  3781  3832 D BluetoothAdapter: STATE_ON
,09-02 12:08:18.164  4137  4153 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 12:08:18.164  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.164  4137  4178 D BtGatt.GattService: registerClient() - UUID=0d0949ff-30f4-4f21-9070-263123fd69e2
09-02 12:08:18.165  4137  4153 D BtGatt.GattService: onClientRegistered() - UUID=0d0949ff-30f4-4f21-9070-263123fd69e2, clientIf=5
,09-02 12:08:18.165  3781  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:08:18.165  4137  4181 D BtGatt.GattService: start scan with filters
,09-02 12:08:18.168  4137  4156 D BtGatt.ScanManager: handling starting scan
,09-02 12:08:18.168  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:08:18.168  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 12:08:18.169  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 12:08:18.169  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:08:18.174  4137  4153 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:08:18.174  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.174  4137  4156 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:08:18.174  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:08:18.175  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:08:18.175  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:08:18.179  4137  4153 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 12:08:18.179  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.179  4137  4156 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:08:18.179  4137  4156 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 12:08:18.179  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:08:18.183  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 12:08:18.183  3781  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-02 12:08:18.183  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:08:18.183  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:18.183  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:08:18.184  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.184  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.184  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:08:18.184  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.184  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5229ac removed from the list
,09-02 12:08:18.184  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.184  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b65675 removed from the list
09-02 12:08:18.184  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:18.184  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:08:18.185  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.185  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 12:08:18.185  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.185  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:18.186  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.186  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:08:18.186  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.186  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b65675 not in the list
09-02 12:08:18.186  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 12:08:18.186  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:08:18.186  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:08:18.186  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:08:18.186  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-02 12:08:18.187  3781  3832 D BluetoothAdapter: STATE_ON
09-02 12:08:18.188  4137  4181 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:08:18.189  4137  4153 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:08:18.189  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.189  4137  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:08:18.190  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:08:18.190  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:08:18.190  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:08:18.190  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 12:08:18.190  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:08:18.191  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:08:18.191  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 12:08:18.191  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:08:18.191  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:08:18.192  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.193  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:18.193  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:18.193  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:08:18.193  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:18.193  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.193  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:08:18.194  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e3498 removed from the list
09-02 12:08:18.194  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.194  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.194  4137  4153 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 12:08:18.194  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.194  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.194  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.194  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb1ee7b removed from the list
09-02 12:08:18.195  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:18.195  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67e0244 added. We now have 2 listener(s)
,09-02 12:08:18.197  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.197  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:18.197  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.197  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:18.197  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cefdf2d added. We now have 9 listener(s)
09-02 12:08:18.197  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.197  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:08:18.200  4137  4153 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 12:08:18.200  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.200  4137  4156 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:08:18.201  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:18.204  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:08:18.207  4137  4153 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 12:08:18.207  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.207  4137  4156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 12:08:18.207  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.208  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:18.208  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:08:18.208  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9b1f3 added. We now have 3 listener(s)
,09-02 12:08:18.209  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 12:08:18.209  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:18.210  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.210  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:18.210  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7afeb0 added. We now have 10 listener(s)
09-02 12:08:18.210  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:18.210  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:18.210  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:08:18.210  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:08:18.210  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:18.210  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:08:18.211  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:18.212   874  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-02 12:08:18.214  3781  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 12:08:18.214  4137  4153 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:08:18.214  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:08:18.214  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.216  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:18.218  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:08:18.219  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 12:08:18.219  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:08:18.222  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:08:18.222  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:08:18.222  3781  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:08:18.223  3781  3832 D BluetoothAdapter: STATE_ON
,09-02 12:08:18.225  4137  4148 D BtGatt.GattService: registerClient() - UUID=275ed6d8-eda6-4f8a-a4fa-ad2bfea865dc
,09-02 12:08:18.225  4137  4153 D BtGatt.GattService: onClientRegistered() - UUID=275ed6d8-eda6-4f8a-a4fa-ad2bfea865dc, clientIf=5
,09-02 12:08:18.226  3781  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 12:08:18.226  4137  4178 D BtGatt.GattService: start scan with filters
,09-02 12:08:18.229  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:08:18.229  4137  4156 D BtGatt.ScanManager: handling starting scan
,09-02 12:08:18.229  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 12:08:18.229  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:08:18.229  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:08:18.232  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:08:18.232  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:08:18.232  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:08:18.233  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:08:18.237  4137  4153 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 12:08:18.237  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.237  4137  4156 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 12:08:18.239  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:08:18.239  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:18.239  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:08:18.240  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.240  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.240  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:08:18.240  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.240  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67e0244 removed from the list
,09-02 12:08:18.240  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.240  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cefdf2d removed from the list
09-02 12:08:18.240  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:18.241  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:18.241  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.241  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-02 12:08:18.241  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.241  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:08:18.242  4137  4153 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 12:08:18.242  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.242  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.242  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:08:18.242  4137  4156 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:08:18.243  4137  4156 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 12:08:18.243  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.243  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cefdf2d not in the list
09-02 12:08:18.243  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:08:18.243  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:08:18.243  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:08:18.243  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:08:18.243  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:08:18.244  3781  3832 D BluetoothAdapter: STATE_ON
09-02 12:08:18.245  4137  4170 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:08:18.245  4137  4148 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 12:08:18.246  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:08:18.246  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 12:08:18.246  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:08:18.246  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:08:18.246  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:08:18.248  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:08:18.248  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 12:08:18.248  3781  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:08:18.248  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:08:18.249  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.250  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:08:18.251  3781  3781 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:18.251  3781  3781 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:08:18.251  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:18.251  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.251  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:08:18.251  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7afeb0 removed from the list
09-02 12:08:18.251  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.251  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.251  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.252  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:08:18.252  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9b1f3 removed from the list
09-02 12:08:18.252  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:18.253  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80955dc added. We now have 2 listener(s)
,09-02 12:08:18.254  4137  4153 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 12:08:18.254  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.255  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:08:18.255  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:18.255  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.256  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:18.256  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ac6e5 added. We now have 9 listener(s)
09-02 12:08:18.256  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.256  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:08:18.259  4137  4153 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 12:08:18.259  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.261  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:18.265  3781  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:08:18.267  3781  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:18.267  3781  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:08:18.267  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:18.267  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d176c6b added. We now have 3 listener(s)
,09-02 12:08:18.268  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 12:08:18.269  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:18.269  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:18.269  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:18.269  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc3f3c8 added. We now have 10 listener(s)
09-02 12:08:18.269  3781  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:18.269  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:18.270  3781  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-02 12:08:18.270  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:18.270  3781  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:08:18.270  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:08:18.270  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.270  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:18.270  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.270  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80955dc removed from the list,
09-02 12:08:18.270  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.270  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ac6e5 removed from the list
09-02 12:08:18.270  4137  4153 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 12:08:18.270  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.270  4137  4156 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:08:18.272  3781  3781 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:18.272  3781  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:08:18.272  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.272  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.272  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.273  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:18.273  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:08:18.273  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.273  3781  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ac6e5 not in the list
,09-02 12:08:18.273  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:18.273  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:18.274  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:18.274  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:08:18.274  3781  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:18.274  3781  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc3f3c8 removed from the list
,09-02 12:08:18.274  3781  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:18.274  3781  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:18.274  3781  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:18.274  3781  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:18.275  3781  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d176c6b removed from the list
09-02 12:08:18.275  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-02 12:08:18.275  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 12:08:18.275  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 12:08:18.276  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:18.276  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-02 12:08:18.276  3781  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:18.281  4137  4153 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 12:08:18.281  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 12:08:18.281  4137  4156 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 12:08:18.282  3781  4219 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
09-02 12:08:18.282  3781  4219 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
09-02 12:08:18.282  3781  4219 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 12:08:18.285  3781  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,09-02 12:08:18.285  3781  4220 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
09-02 12:08:18.285  3781  4220 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 12:08:18.287  3781  3832 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-02 12:08:18.287  3781  3832 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 12:08:18.287  3781  3832 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 12:08:18.287  3781  3832 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 12:08:18.287  3781  3832 D com.test.thalitest.ThaliTestRunner: Total duration: 22863 ms
,09-02 12:08:18.289  3781  3832 I jxcore-log: *Native tests were executed*
09-02 12:08:18.289  3781  3832 I jxcore-log: 
09-02 12:08:18.289  3781  3832 I jxcore-log: Total number of executed tests:  80
09-02 12:08:18.289  3781  3832 I jxcore-log: 
09-02 12:08:18.289  3781  3832 I jxcore-log: Number of passed tests:  80
09-02 12:08:18.289  3781  3832 I jxcore-log: 
,09-02 12:08:18.289  3781  3832 I jxcore-log: Number of failed tests:  0
09-02 12:08:18.289  3781  3832 I jxcore-log: 
09-02 12:08:18.290  3781  3832 I jxcore-log: Number of ignored tests:  0
09-02 12:08:18.290  3781  3832 I jxcore-log: 
,09-02 12:08:18.291  3781  3832 I jxcore-log: Total duration:  22863
09-02 12:08:18.291  3781  3832 I jxcore-log: 
,09-02 12:08:18.291  3781  3832 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 12:08:18.291  3781  3832 I jxcore-log: 
09-02 12:08:18.291  4137  4153 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 12:08:18.292  4137  4153 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 12:08:18.295  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.295  3781  3832 I jxcore-log: 
09-02 12:08:18.297  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.297  3781  3832 I jxcore-log: 
09-02 12:08:18.298  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.298  3781  3832 I jxcore-log: 
09-02 12:08:18.299  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.299  3781  3832 I jxcore-log: 
09-02 12:08:18.300  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.300  3781  3832 I jxcore-log: 
09-02 12:08:18.302  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.302  3781  3832 I jxcore-log: 
09-02 12:08:18.304  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.304  3781  3832 I jxcore-log: 
09-02 12:08:18.305  3781  3781 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 12:08:18.305  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.305  3781  3832 I jxcore-log: 
09-02 12:08:18.306  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.306  3781  3832 I jxcore-log: 
09-02 12:08:18.307  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.307  3781  3832 I jxcore-log: 
,09-02 12:08:18.308  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.308  3781  3832 I jxcore-log: 
,09-02 12:08:18.310  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:18.310  3781  3832 I jxcore-log: 
,09-02 12:08:18.311  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.311  3781  3832 I jxcore-log: 
,09-02 12:08:18.311  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.311  3781  3832 I jxcore-log: 
,09-02 12:08:18.312  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.312  3781  3832 I jxcore-log: 
09-02 12:08:18.313  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.313  3781  3832 I jxcore-log: 
,09-02 12:08:18.314  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.314  3781  3832 I jxcore-log: 
09-02 12:08:18.314  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.314  3781  3832 I jxcore-log: 
09-02 12:08:18.315  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.315  3781  3832 I jxcore-log: 
09-02 12:08:18.315  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.315  3781  3832 I jxcore-log: 
09-02 12:08:18.316  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.316  3781  3832 I jxcore-log: 
09-02 12:08:18.316  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.316  3781  3832 I jxcore-log: 
09-02 12:08:18.317  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.317  3781  3832 I jxcore-log: 
09-02 12:08:18.317  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.317  3781  3832 I jxcore-log: 
09-02 12:08:18.318  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.318  3781  3832 I jxcore-log: 
09-02 12:08:18.318  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:18.318  3781  3832 I jxcore-log: 
,09-02 12:08:18.319  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.319  3781  3832 I jxcore-log: 
09-02 12:08:18.319  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:18.319  3781  3832 I jxcore-log: 
09-02 12:08:18.319  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.319  3781  3832 I jxcore-log: 
09-02 12:08:18.320  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.320  3781  3832 I jxcore-log: 
09-02 12:08:18.320  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.320  3781  3832 I jxcore-log: 
09-02 12:08:18.322  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.322  3781  3832 I jxcore-log: 
09-02 12:08:18.323  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.323  3781  3832 I jxcore-log: 
09-02 12:08:18.324  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:18.324  3781  3832 I jxcore-log: 
,09-02 12:08:18.622  3781  3781 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:08:18.625  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:18.625  3781  3832 I jxcore-log: 
,09-02 12:08:18.693  3781  3781 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:08:18.696  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:18.696  3781  3832 I jxcore-log: 
,09-02 12:08:18.751  3781  3781 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:08:18.756  3781  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:18.756  3781  3832 I jxcore-log: 
,09-02 12:08:18.958  4221  4221 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-02 12:08:18.963  4221  4221 D AndroidRuntime: CheckJNI is OFF
,09-02 12:08:19.005  4221  4221 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-02 12:08:19.052  4221  4221 I Radio-JNI: register_android_hardware_Radio DONE
,09-02 12:08:19.074  4221  4221 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 12:08:19.085   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-02 12:08:19.086   874   887 I ActivityManager: Killing 3781:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-02 12:08:19.194   874  1904 D GraphicsStats: Buffer count: 2
,09-02 12:08:19.195   874  1315 D WifiService: Client connection lost with reason: 4
,09-02 12:08:19.194   874  2041 I WindowState: WIN DEATH: Window{16e5dc4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 12:08:19.222   874   897 W PackageSettings: Skipping PackageSetting{1a150ba com.example.hello/10273} due to missing metadata
,09-02 12:08:19.269   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-02 12:08:19.270   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-02 12:08:19.272   874   897 I art     : Starting a blocking GC Explicit
,09-02 12:08:19.274   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-02 12:08:19.274   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-02 12:08:19.274   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.274   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.274   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 12:08:19.274   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-02 12:08:19.276   874   887 I ActivityManager:   Force finishing activity ActivityRecord{f46f15 u0 com.test.thalitest/.MainActivity t2}
,09-02 12:08:19.297   874  1905 W ActivityManager: Spurious death for ProcessRecord{6b891a 0:com.test.thalitest/u0a0}, curProc for 3781: null
,09-02 12:08:19.348   874   897 I art     : Explicit concurrent mark sweep GC freed 55725(3MB) AllocSpace objects, 10(296KB) LOS objects, 33% free, 29MB/43MB, paused 1.401ms total 76.384ms
,09-02 12:08:19.348   874   883 I art     : WaitForGcToComplete blocked for 16.906ms for cause HeapTrim
,09-02 12:08:19.401   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-02 12:08:19.404  4221  4221 I art     : System.exit called, status: 0
,09-02 12:08:19.404  4221  4221 I AndroidRuntime: VM exiting with result code 0.
,09-02 12:08:19.408   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-02 12:08:19.424   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-02 12:08:19.428  4137  4137 D BluetoothMapAppObserver: onReceive
,09-02 12:08:19.428  4137  4137 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-02 12:08:19.433   874  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-02 12:08:19.434  1899  2284 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-02 12:08:19.436  3621  3621 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-02 12:08:19.437  1887  1887 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-02 12:08:19.447  1887  4233 I Keyboard.Facilitator.DecoderInitializer: run()
,09-02 12:08:19.454  1958  1958 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-02 12:08:19.461  1887  4233 I Decoder : createOrResetDecoder
,09-02 12:08:19.462   874  1908 I ActivityManager: Start proc 4236:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-02 12:08:19.512  1507  1507 I ConfigService: onCreate
,09-02 12:08:19.515  1507  4248 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at com,.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 12:08:19.515  1507  4248 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-02 12:08:19.521  4236  4236 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 12:08:19.515  1507  4248 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-02 12:08:19.526  1507  4248 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-02 12:08:19.536  1887  4233 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-02 12:08:19.543   874  1905 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3781 uid 10000
,09-02 12:08:19.544   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 12:08:19.545  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-02 12:08:19.559  1899  2646 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-02 12:08:19.575  4236  4236 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-02 12:08:19.586  1977  2073 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-02 12:08:19.587  1887  4233 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-02 12:08:19.587   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-02 12:08:19.588   874   886 E PackageManager: Failed to write settings, restoring backup
09-02 12:08:19.588   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-02 12:08:19.588   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-02 12:08:19.588   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-02 12:08:19.588   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-02 12:08:19.588   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-02 12:08:19.588   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.588   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.588   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:08:19.590  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-02 12:08:19.590  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-02 12:08:19.592   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-02 12:08:19.592   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-02 12:08:19.592   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:08:19.592   874   887 E DropBoxManagerService: 	... 13 more
,09-02 12:08:19.592  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-02 12:08:19.592  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-02 12:08:19.593  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-02 12:08:19.594  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-02 12:08:19.595  1887  4233 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-02 12:08:19.595  1887  4233 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-02 12:08:19.596  1887  4233 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-02 12:08:19.596  1887  4233 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-02 12:08:19.596  1887  4233 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-02 12:08:19.596  1887  4233 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-02 12:08:19.596   874  1388 I ActivityManager: Start proc 4254:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-02 12:08:19.602  4236  4253 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-02 12:08:19.608   874  1908 I ActivityManager: Start proc 4266:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-02 12:08:19.609  1977  2073 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-02 12:08:19.609  1977  2073 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1977
09-02 12:08:19.609  1977  2073 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: ,	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.609  1977  2073 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:08:19.613   874  1905 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 12:08:19.617   874  4276 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:08:19.617   874  4276 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:08:19.617   874  4276 E DropBoxManagerService: 	... 5 more
,09-02 12:08:19.619  1977  2073 I Process : Sending signal. PID: 1977 SIG: 9
,09-02 12:08:19.638  4254  4254 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-02 12:08:19.656  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-02 12:08:19.656  1507  1507 D AndroidRuntime: Shutting down VM
09-02 12:08:19.657  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
09-02 12:08:19.657  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
09-02 12:08:19.657  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-02 12:08:19.657  1507  1507 E AndroidRuntime: 	... 8 more
09-02 12:08:19.659  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
,09-02 12:08:19.662   874  4281 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:08:19.662   874  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:08:19.662   874  4281 E DropBoxManagerService: 	... 5 more
,09-02 12:08:19.698   874  1995 I ActivityManager: Killing 3678:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-02 12:08:19.700  4236  4250 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.700  4236  4250 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.700  4236  4250 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:08:19.710   874  1477 D GraphicsStats: Buffer count: 1
,09-02 12:08:19.710   874  1388 I WindowState: WIN DEATH: Window{5da33c6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-02 12:08:19.712   874  1315 D WifiService: Client connection lost with reason: 4
,09-02 12:08:19.748  4236  4250 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-02 12:08:19.752  4236  4253 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.752  4236  4253 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 12:08:19.753  4236  4253 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 12:08:19.753  4236  4253 E AndroidRuntime: Process: android.process.acore, PID: 4236
09-02 12:08:19.753  4236  4253 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.753  4236  4253 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 12:08:19.753  4236  4250 I Process : Sending signal. PID: 4236 SIG: 9
,09-02 12:08:19.767   874  2041 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1977) has died
,09-02 12:08:19.768   874  2041 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-02 12:08:19.769   874  2041 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-02 12:08:19.772   874  1997 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
,09-02 12:08:19.772   874  1997 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,09-02 12:08:19.772   874  1997 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-02 12:08:19.772   874  1997 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-02 12:08:19.772   874  1997 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,09-02 12:08:19.778  1701  1701 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-02 12:08:19.792   874   887 I ActivityManager: Start proc 4287:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-02 12:08:19.797   874  4292 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:08:19.797   874  4292 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:08:19.797   874  4292 E DropBoxManagerService: 	... 5 more
,09-02 12:08:19.805   874  1904 I ActivityManager: Start proc 4298:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-02 12:08:19.807   874  1908 I ActivityManager: Process android.process.acore (pid 4236) has died
09-02 12:08:19.807   874  1908 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40965ms
,09-02 12:08:19.834  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-02 12:08:19.834  1701  1701 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-02 12:08:19.843  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-02 12:08:19.843  1701  1701 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-02 12:08:19.848  1701  4315 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-02 12:08:19.858  2042  4314 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-02 12:08:19.860  4287  4287 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:08:19.860  4287  4287 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 12:08:19.860  4287  4287 D AndroidRuntime: Shutting down VM
09-02 12:08:19.867   874  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
09-02 12:08:19.867  4298  4298 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-02 12:08:19.878  4287  4287 E AndroidRuntime: FATAL EXCEPTION: main
09-02 12:08:19.878  4287  4287 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4287
09-02 12:08:19.878  4287  4287 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 12:08:19.878  4287  4287 E AndroidRuntime: 	... 10 more
09-02 12:08:19.880   874   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-02 12:08:19.884  4298  4298 I MultiDex: VM with version 2.1.0 has multidex support
09-02 12:08:19.884  4298  4298 I MultiDex: install
09-02 12:08:19.884   874  4317 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:08:19.884   874  4317 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:08:19.884   874  4317 E DropBoxManagerService: 	... 5 more
,09-02 12:08:19.884  4298  4298 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-02 12:08:19.886  1701  4315 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-02 12:08:19.886  1701  4315 E AndroidRuntime: Process: com.google.android.gms, PID: 1701
09-02 12:08:19.886  1701  4315 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 12:08:19.886  1701  4315 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,09-02 12:08:19.892   874   887 I ActivityManager: Start proc 4318:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,09-02 12:08:19.894  4287  4287 I Process : Sending signal. PID: 4287 SIG: 9
,09-02 12:08:19.897  4298  4298 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-02 12:08:19.902  4298  4298 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-02 12:08:19.903   874  4329 E DropBoxManagerService: Can't write: system_app_crash
09-02 12:08:19.903   874  4329 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 12:08:19.903   874  4329 E DropBoxManagerService: 	... 5 more

```
