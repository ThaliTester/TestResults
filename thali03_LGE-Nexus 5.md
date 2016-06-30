#### Test 7578926851a8f91_thali03_LGE-Nexus 5 Logs


```
--------- beginning of main
06-30 12:51:08.111  1651  2368 D Icing   : Loaded CLD2 Version V2.0 - 20141016
06-30 12:51:08.115  1651  2368 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
06-30 12:51:08.685  1651  2368 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
06-30 12:51:08.761  1651  2368 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,06-30 12:51:10.254  2934  2934 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 12:51:10.257  2934  2934 D AndroidRuntime: CheckJNI is OFF
06-30 12:51:10.292  2934  2934 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 12:51:10.328  2934  2934 I Radio-JNI: register_android_hardware_Radio DONE
06-30 12:51:10.347  2934  2934 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 12:51:10.350   792   962 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:51:10.378  1422  1437 W SearchService: Abort, client detached.
06-30 12:51:10.381  1422  1422 I MicroDetector: Keeping mic open: false
06-30 12:51:10.382  1422  1422 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@b23bd1d
06-30 12:51:10.382  1422  1483 E AudioRecord-JNI: Error -4 during AudioRecord native read
06-30 12:51:10.382  1422  1563 I DeviceStateChecker: DeviceStateChecker cancelled
06-30 12:51:10.385  2934  2934 D AndroidRuntime: Shutting down VM
06-30 12:51:10.397   792   802 I ActivityManager: Start proc 2950:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
06-30 12:51:10.427   197  1583 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 12:51:10.427   197  1583 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
06-30 12:51:10.431  1422  1581 I MicroRecognitionRunner: Detection finished
06-30 12:51:10.432  1422  1562 I MicroRecognitionRunner: Stopping hotword detection.
06-30 12:51:10.485  2950  2950 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108600)
06-30 12:51:10.511  2950  2950 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 6824-6825)
06-30 12:51:10.512  2950  2950 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-30 12:51:10.525  2950  2950 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f132a91}
06-30 12:51:10.525  2950  2950 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-30 12:51:10.526  2950  2950 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:51:10.543   792   894 D WifiService: New client listening to asynchronous messages
06-30 12:51:10.553  2950  2950 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 12:51:10.563  2950  2950 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
06-30 12:51:10.563  2950  2950 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
06-30 12:51:10.575  2950  2950 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 12:51:10.637   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67c466c:true
,06-30 12:51:10.658   792  1199 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/2950 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:51:10.669  2950  2950 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,06-30 12:51:10.675  2950  2950 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 12:51:10.676  2950  2950 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,06-30 12:51:10.686  2950  2950 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-30 12:51:10.707  2950  2950 I cr_Ime  : ImeThread is not enabled.
,06-30 12:51:10.718  2950  2991 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:51:10.751   792   802 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/2950 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:51:10.787  2950  2991 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:51:10.789  2950  2995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-30 12:51:10.855   792   813 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +470ms
,06-30 12:51:10.926  2950  2950 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2950
,06-30 12:51:10.938  2950  2950 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
06-30 12:51:10.938  2950  2950 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,06-30 12:51:11.040  2950  2950 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 12:51:11.041   792   895 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:51:11.192   792  1394 I ActivityManager: Killing 2431:com.google.android.deskclock/u0a33 (adj 15): empty #17
,06-30 12:51:11.321  2950  3007 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1726219984
,06-30 12:51:11.324  2950  3007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:51:11.324  2950  3007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:51:11.324  2950  3007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:51:11.324  2950  3007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:51:11.324  2950  3007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:51:11.324  2950  3007 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dedc6fd added. We now have 1 listener(s)
,06-30 12:51:11.327  2950  3007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,06-30 12:51:11.329  2950  3007 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,06-30 12:51:11.329  2950  3007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 12:51:11.329  2950  3007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:51:11.333  2950  3007 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cca4c0 added. We now have 1 listener(s)
06-30 12:51:11.333  2950  3007 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 12:51:11.334  2950  3007 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:51:11.334  2950  3007 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 12:51:11.335  2950  3007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 12:51:11.335  2950  3007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 12:51:11.335  2950  3007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:51:11.335  2950  3007 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 12:51:11.336  2950  3007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 12:51:11.336  2950  3007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
06-30 12:51:11.337  2950  3007 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:51:11.337  2950  3007 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:51:11.337  2950  3007 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:51:11.337  2950  3007 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:51:11.338  2950  3007 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 12:51:11.364  2950  2950 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:51:11.580   792   803 I ActivityManager: Killing 2450:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,06-30 12:51:12.067  2950  3023 W jxcore-log: Initializing JXcore engine
,06-30 12:51:12.067  2950  3023 W jxcore-log: JXcore engine is ready
,06-30 12:51:12.089  3023  3023 W Thread-258: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10263]" dev="sockfs" ino=10263 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-30 12:51:12.089  3023  3023 W Thread-258: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-30 12:51:12.089  3023  3023 W Thread-258: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18328]" dev="sockfs" ino=18328 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-30 12:51:12.114  2950  3023 W jxcore-log: Starting JXcore engine
,06-30 12:51:12.190  2950  3023 W jxcore-log: Platform android
06-30 12:51:12.190  2950  3023 W jxcore-log: 
,06-30 12:51:12.190  2950  3023 W jxcore-log: Process ARCH arm
06-30 12:51:12.190  2950  3023 W jxcore-log: 
,06-30 12:51:12.381  2950  3023 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:51:12.381  2950  3023 I jxcore-log: 
,06-30 12:51:12.381  2950  3023 W jxcore-log: JXcore engine is started
,06-30 12:51:12.390  2950  3007 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 12:51:12.392   792  1332 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10026 on display 0
,06-30 12:51:12.406  2950  2950 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-30 12:51:12.406  2950  2950 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 12:51:12.420   792  1199 I ActivityManager: Start proc 3033:com.android.packageinstaller/u0a60 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 12:51:12.465  3033  3033 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 12:51:12.569  3033  3045 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:51:12.610  3033  3045 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 12:51:12.612  3033  3045 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:51:12.680   792   813 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +273ms
,06-30 12:51:12.860  2950  2950 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c459bf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2df62b2, 16908290=android.view.AbsSavedState$1@2df62b2}, android:focusedViewId=100}]}]
,06-30 12:51:12.860  2950  2950 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 12:51:13.497   792   962 I ActivityManager: Killing 1761:com.google.android.apps.fitness/u0a82 (adj 15): empty #17
,06-30 12:51:16.611  1566  1566 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,06-30 12:51:16.660  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:16.663  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:16.663  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:16.690  1566  1566 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 12:51:16.694  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:16.707  1566  1566 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 12:51:16.712  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:16.735  1566  1566 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 12:51:16.866  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:16.910  1566  1566 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 12:51:16.914  1566  1566 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,06-30 12:51:16.923  1566  1566 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,06-30 12:51:16.930  1566  1566 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 32 minutes (failures=2)
,06-30 12:51:16.944  1377  1377 D WearableService: callingUid 10007, callindPid: 1377
,06-30 12:51:16.949  1566  1566 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(2100): Skipping verification because network inactive
,06-30 12:51:16.953  1377  1389 D DeviceConnectionService: client connected with version: 8486000
,06-30 12:51:16.982  1566  3073 I Finsky  : [125] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-30 12:51:16.983  1566  1627 I PlayCommon: [107] com.google.android.play.a.w.a(27551): Starting to flush logs
06-30 12:51:16.983  1566  1566 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,06-30 12:51:16.986  1566  1566 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
,06-30 12:51:17.014  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:17.042  1566  1627 I PlayCommon: [107] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
,06-30 12:51:19.368  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:19.503  2844  2885 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,06-30 12:51:19.516  2844  2885 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,06-30 12:51:19.516  2844  2885 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,06-30 12:51:19.519  2844  2885 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-30 12:51:19.541  2844  2885 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 12:51:31.759  1566  1630 I Finsky  : [110] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,06-30 12:51:31.875  1566  1630 I Finsky  : [110] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,06-30 12:51:31.884  1566  1566 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,06-30 12:52:24.369   792   815 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
06-30 12:52:24.372   792   815 I PowerManagerService: Sleeping (uid 1000)...
,06-30 12:52:24.401   190   828 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (830 us)
06-30 12:52:24.405   792   815 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 12:52:24.484  2950  2950 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 12:52:24.484  2950  2950 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 12:52:24.970   792   815 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 12:52:24.983   792   815 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 12:52:24.986   792   813 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,06-30 12:52:24.995   190   190 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
06-30 12:52:24.995   190   190 D qdhwcomposer: hwc_blank: Blanking display: 0
,06-30 12:52:25.276   190   190 D qdhwcomposer: hwc_blank: Done blanking display: 0
,06-30 12:52:25.277   792   910 D SurfaceControl: Excessive delay in setPowerMode(): 291ms
,06-30 12:52:25.278  1818  1826 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,06-30 12:52:25.298   792   893 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 12:52:25.299   792   893 E WifiStateMachine:  Fail to set up pno, want false now false
06-30 12:52:25.304   197   901 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,06-30 12:52:25.372   792   893 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 12:52:25.372   792   893 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 12:52:25.373   197   827 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,06-30 12:52:25.380  1239  1239 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,06-30 12:52:29.374  1377  1606 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:30.009   792  1394 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1651 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:52:30.077  1651  3171 W DriveInitializer: Background init thread started
,06-30 12:52:30.138  1651  3171 W DriveInitializer: Background init thread ended
,06-30 12:53:00.296  1377  1377 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=d678375b-4541-418f-bb60-3dbb20b06774
,06-30 12:53:00.297  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:00.298  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:00.421  1377  1559 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 12:53:00.424  1651  3181 D UdcContextInitService: registered all accounts: true
,06-30 12:53:00.433  1377  1548 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 12:53:00.490  1377  1548 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 12:53:00.551  1377  1377 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 12:53:00.555  1377  3201 I VacuumService: Vacuum at: now=1467283980555 tag=VacuumService
,06-30 12:54:00.656  1377  1548 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:00.657  1377  1548 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:00.657  1377  1548 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:00.658  1377  1548 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 12:54:00.658  1377  1548 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 12:54:00.680  1377  1548 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 12:55:19.759  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:19.774  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:19.775  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:19.875  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:19.893  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:00:19.894  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:19.978  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:19.995  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:19.995  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:13.783   792   807 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:20.100  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:20.113  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:20.113  1377  1377 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms)
```
