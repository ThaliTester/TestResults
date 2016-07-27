#### Test 78968685da35147_thali03_LGE-Nexus 5 Logs


```
--------- beginning of main
07-27 08:53:29.029  2987  2987 D CAR.SERVICE: onUnbind
,07-27 08:53:29.029  2987  2987 D CAR.SERVICE: CSB onClientsDisconnected
07-27 08:53:29.029  2987  2987 D CAR.SERVICE: tearDown
07-27 08:53:29.029  2987  2987 D CAR.SERVICE: tearDownCarState
07-27 08:53:29.029  2987  2987 D CAR.SERVICE: Skip, car not connected.
07-27 08:53:29.029  2987  2987 D CAR.SERVICE: tearDownClientState
07-27 08:53:29.030  2987  2987 D CAR.SERVICE: requestStop
07-27 08:53:29.032  2987  2987 D CAR.SERVICE: onDestroy
07-27 08:53:29.033  2987  2987 D CAR.SERVICE: tearDown
07-27 08:53:29.033  2987  2987 D CAR.SERVICE: tearDownCarState
07-27 08:53:29.033  2987  2987 D CAR.SERVICE: Skip, car not connected.
07-27 08:53:29.033  2987  2987 D CAR.SERVICE: tearDownClientState
07-27 08:53:29.033  2987  2987 D CAR.SERVICE: requestStop
--------- beginning of system
07-27 08:53:29.034   789  1162 I ActivityManager: Killing 2375:com.google.android.calendar/u0a28 (adj 15): empty #17
07-27 08:53:29.066  2987  2987 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@e121fff that was originally bound here
07-27 08:53:29.066  2987  2987 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@e121fff that was originally bound here
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at irv.a(:com.google.android.gms:120)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at irv.a(:com.google.android.gms:137)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at com.google.android.gms.car.CarCallService.h(:com.google.android.gms:76)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at com.google.android.gms.car.CarCallService.<init>(:com.google.android.gms:64)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at fgl.i(:com.google.android.gms:551)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:163)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:160)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2904)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.ActivityThread.-wrap2(ActivityThread.java)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1432)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:53:29.066  2987  2987 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:53:29.147   789  1338 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@dbd7a61
07-27 08:53:29.643  3037  3037 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:53:29.648  3037  3037 D AndroidRuntime: CheckJNI is OFF
07-27 08:53:29.694  3037  3037 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:53:29.738  3037  3037 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:53:29.758  3037  3037 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:53:29.768   789  1162 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:53:29.788  1384  1533 W SearchService: Abort, client detached.
07-27 08:53:29.797  1384  1384 I MicroDetector: Keeping mic open: false
07-27 08:53:29.797  1384  1539 I DeviceStateChecker: DeviceStateChecker cancelled
07-27 08:53:29.798  1384  1384 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ai@386baaf
07-27 08:53:29.798  1384  1504 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-27 08:53:29.810  3037  3037 D AndroidRuntime: Shutting down VM
07-27 08:53:29.828   789  1337 I ActivityManager: Start proc 3053:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-27 08:53:29.854   197  1552 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-27 08:53:29.854   197  1552 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-27 08:53:29.860  1384  1550 I MicroRecognitionRunner: Detection finished
07-27 08:53:29.860  1384  1538 I MicroRecognitionRunner: Stopping hotword detection.
07-27 08:53:29.918  3053  3053 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-27 08:53:29.966  3053  3053 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 517-518)
07-27 08:53:29.966  3053  3053 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-27 08:53:29.988  3053  3053 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fffa0f7}
07-27 08:53:29.988  3053  3053 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-27 08:53:29.988  3053  3053 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:53:30.001   789   892 D WifiService: New client listening to asynchronous messages
07-27 08:53:30.007  3053  3053 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-27 08:53:30.017  3053  3053 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-27 08:53:30.017  3053  3053 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-27 08:53:30.028  3053  3053 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-27 08:53:30.080   789   806 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dce9f1a:true
,07-27 08:53:30.097   789  1364 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3053 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:30.107  3053  3053 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-27 08:53:30.115  3053  3053 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:53:30.116  3053  3053 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-27 08:53:30.127  3053  3053 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-27 08:53:30.143  3053  3053 I cr_Ime  : ImeThread is not enabled.
,07-27 08:53:30.153  3053  3086 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 08:53:30.179   789   990 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3053 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:30.207  3053  3086 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 08:53:30.253  3053  3091 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-27 08:53:30.259   789   807 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +450ms
,07-27 08:53:30.287  3053  3091 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 08:53:30.307  3053  3091 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 08:53:30.332  3053  3053 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3053
,07-27 08:53:30.333  3053  3053 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
07-27 08:53:30.333  3053  3053 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,07-27 08:53:30.469  3053  3053 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:53:30.470   789   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:30.604  3053  3103 D jxcore_app_log: JniHelper::setJavaVM(0xb4cbc000), pthread_self() = -1708132048
,07-27 08:53:30.607  3053  3103 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:53:30.607  3053  3103 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:53:30.607  3053  3103 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:53:30.607  3053  3103 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:53:30.607  3053  3103 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-27 08:53:30.607  3053  3103 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cb96f2 added. We now have 1 listener(s)
,07-27 08:53:30.610  3053  3103 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,07-27 08:53:30.612  3053  3103 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,07-27 08:53:30.613  3053  3103 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 08:53:30.613  3053  3103 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 08:53:30.618  3053  3103 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f998f9 added. We now have 1 listener(s)
07-27 08:53:30.618  3053  3103 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 08:53:30.618  3053  3103 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:30.619  3053  3103 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:53:30.620  3053  3103 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:53:30.621  3053  3103 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:53:30.622  3053  3103 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:53:30.622  3053  3103 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:53:30.623  3053  3103 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:53:30.623  3053  3103 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
07-27 08:53:30.625  3053  3103 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:30.625  3053  3103 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:30.625  3053  3103 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:53:30.625  3053  3103 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:53:30.625  3053  3103 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:53:30.629   789  1330 I ActivityManager: Killing 1855:com.google.android.gms.feedback/u0a7 (adj 15): empty #17
,07-27 08:53:30.684  3053  3053 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:53:30.728   789  1324 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
,07-27 08:53:31.327  3053  3108 W jxcore-log: Initializing JXcore engine
,07-27 08:53:31.327  3053  3108 W jxcore-log: JXcore engine is ready
,07-27 08:53:31.348  3108  3108 W Thread-272: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10404]" dev="sockfs" ino=10404 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-27 08:53:31.348  3108  3108 W Thread-272: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-27 08:53:31.348  3108  3108 W Thread-272: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[20846]" dev="sockfs" ino=20846 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 08:53:31.373  3053  3108 W jxcore-log: Starting JXcore engine
,07-27 08:53:31.446  3053  3108 W jxcore-log: Platform android
07-27 08:53:31.446  3053  3108 W jxcore-log: 
,07-27 08:53:31.446  3053  3108 W jxcore-log: Process ARCH arm
07-27 08:53:31.446  3053  3108 W jxcore-log: 
,07-27 08:53:31.602  3053  3108 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:53:31.602  3053  3108 I jxcore-log: 
07-27 08:53:31.602  3053  3108 W jxcore-log: JXcore engine is started
,07-27 08:53:31.609  3053  3103 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:53:31.611  3053  3053 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:53:31.741   789   802 I ActivityManager: Start proc 3123:com.google.android.gms.feedback/u0a7 for service com.google.android.gms/.feedback.FeedbackService
,07-27 08:53:31.806  3123  3123 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:53:31.806  3123  3123 I MultiDex: install
07-27 08:53:31.806  3123  3123 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:53:31.833  3123  3123 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:53:31.848  3123  3123 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-27 08:53:31.848  3123  3123 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:53:31.851  3123  3123 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:53:31.882  3123  3123 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:53:31.896  3123  3123 D ChimeraCfgMgr: Reading stored module config
,07-27 08:53:31.927   789  1338 I ActivityManager: Killing 2020:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,07-27 08:53:31.989  3123  3150 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 08:53:39.893  1596  1664 I Finsky  : [113] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-27 08:53:40.079  1596  1664 I Finsky  : [113] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-27 08:53:40.080  1596  1596 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-27 08:53:41.659  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:53:41.659  3053  3108 I jxcore-log: 
07-27 08:53:41.661  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:53:41.661  3053  3108 I jxcore-log: 
,07-27 08:53:41.662  3053  3108 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:41.662  3053  3108 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:53:41.662  3053  3108 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:53:41.662  3053  3108 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:53:41.663  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:53:41.663  3053  3108 I jxcore-log: 
07-27 08:53:41.665  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:53:41.665  3053  3108 I jxcore-log: 
,07-27 08:53:42.008  3053  3108 I jxcore-log: Unit Test app is loaded
07-27 08:53:42.008  3053  3108 I jxcore-log: 
,07-27 08:53:42.013  3053  3053 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:53:42.017  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:53:42.017  3053  3108 I jxcore-log: 
,07-27 08:53:42.022   789  1330 D WifiService: setWifiEnabled: true pid=3053, uid=10026
,07-27 08:53:42.022   789  1330 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 08:53:42.026   193   785 D SoftapController: Softap fwReload - Ok
,07-27 08:53:42.030  3053  3108 I jxcore-log: My device name is: LGE-Nexus 5
07-27 08:53:42.030  3053  3108 I jxcore-log: 
07-27 08:53:42.031   193   785 D CommandListener: Setting iface cfg
07-27 08:53:42.031   193   785 D CommandListener: Trying to bring down wlan0
07-27 08:53:42.032   193   785 D CommandListener: Clearing all IP addresses on wlan0
07-27 08:53:42.035   789   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-27 08:53:42.047   789   806 I ActivityManager: Start proc 3198:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 08:53:42.169  3198  3198 D AdapterServiceConfig: Adding HeadsetService
,07-27 08:53:42.169  3198  3198 D AdapterServiceConfig: Adding A2dpService
07-27 08:53:42.169  3198  3198 D AdapterServiceConfig: Adding HidService
07-27 08:53:42.170  3198  3198 D AdapterServiceConfig: Adding HealthService
07-27 08:53:42.170  3198  3198 D AdapterServiceConfig: Adding PanService
07-27 08:53:42.170  3198  3198 D AdapterServiceConfig: Adding GattService
,07-27 08:53:42.170  3198  3198 D AdapterServiceConfig: Adding BluetoothMapService
,07-27 08:53:42.185   789   806 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c3b3c9:true
,07-27 08:53:42.186  3198  3198 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 08:53:42.188  3198  3198 I bt_bluedroid: init
07-27 08:53:42.189  3198  3215 I BluetoothAdapterState: Entering OffState
,07-27 08:53:42.199  3198  3216 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 08:53:42.200  3198  3216 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-27 08:53:42.200  3198  3216 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 08:53:42.200  3198  3216 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 08:53:42.201  3198  3198 I bt_bluedroid: get_profile_interface socket
,07-27 08:53:42.205  3198  3198 I bt_bluedroid: get_profile_interface sdp
,07-27 08:53:42.207  3198  3219 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-27 08:53:42.209  3198  3219 D BluetoothAdapterProperties: Name is: Nexus 5
,07-27 08:53:42.209  3198  3208 I bt_bluedroid: config_hci_snoop_log
07-27 08:53:42.210   789   806 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,07-27 08:53:42.213  3198  3215 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 08:53:42.215  3198  3215 D BluetoothAdapterProperties: Setting state to 14
,07-27 08:53:42.215  3198  3215 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 08:53:42.217  3198  3215 D BluetoothBondStateMachine: make
,07-27 08:53:42.222  3198  3220 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 08:53:42.225  3198  3198 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-27 08:53:42.226  3198  3215 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:53:42.227  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
,07-27 08:53:42.228  3198  3198 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 08:53:42.228  3198  3198 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:53:42.228  3198  3198 D BtGatt.GattService: start()
,07-27 08:53:42.233  3198  3198 I bt_bluedroid: get_profile_interface gatt
,07-27 08:53:42.233  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:42.233  3198  3198 D BtGatt.AdvertiseManager: advertise manager created
,07-27 08:53:42.239  3198  3198 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:53:42.239  3198  3198 V BluetoothAdapterState: isTurningOn()=false
07-27 08:53:42.240  3198  3198 V BluetoothAdapterState: isBleTurningOn()=true
,07-27 08:53:42.241  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:53:42.243  3198  3215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-27 08:53:42.243  3198  3215 I bt_bluedroid: enable
07-27 08:53:42.243  3198  3216 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-27 08:53:42.244  3198  3216 I bt_hci  : start_up
,07-27 08:53:42.251  3198  3216 I bt_vendor: alloc value 0xb3967631
,07-27 08:53:42.251  3198  3216 I bt_vendor: init
07-27 08:53:42.251  3198  3216 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:53:42.251  3198  3216 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 08:53:42.287  3198  3216 D bt_hci  : start_up starting async portion
,07-27 08:53:42.287  3198  3223 I bt_hci  : event_finish_startup
07-27 08:53:42.287  3198  3223 I bt_hci_h4: hal_open
,07-27 08:53:42.287  3198  3223 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-27 08:53:42.290  3198  3223 I bt_userial_vendor: device fd = 49 open
,07-27 08:53:42.372  3198  3223 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-27 08:53:42.400  3198  3223 D bt_hwcfg: Chipset BCM4335C0
,07-27 08:53:42.400  3198  3223 D bt_hwcfg: Target name = [BCM4335C0]
07-27 08:53:42.400  3198  3223 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-27 08:53:42.742  3198  3223 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 08:53:42.742  3198  3223 D bt_hwcfg: Settlement delay -- 100 ms
07-27 08:53:42.742  3198  3223 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 08:53:42.838   789   891 D wifi    : set interface wlan0 flags (UP)
,07-27 08:53:42.838   789   891 I WifiHAL : Initializing wifi
07-27 08:53:42.838   789   891 I WifiHAL : Creating socket
,07-27 08:53:42.840   789   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-27 08:53:42.840   789   891 D wifi    : Did set static halHandle = 0x92c207c0
07-27 08:53:42.840   789   891 D wifi    : halHandle = 0x92c207c0, mVM = 0xb4cbc000, mCls = 0x1846
07-27 08:53:42.841   789   891 D wifi    : array field set
07-27 08:53:42.841   789   806 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 08:53:42.841   789   891 I WifiNative-HAL: interface[0] = p2p0
07-27 08:53:42.841   789   891 I WifiNative-HAL: interface[1] = wlan0
07-27 08:53:42.845   789  3228 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1832777792
,07-27 08:53:42.845   789  3228 D wifi    : waitForHalEvents called, vm = 0xb4cbc000, obj = 0x1846, env = 0x92c1cc60
,07-27 08:53:42.857  3198  3223 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-27 08:53:42.858  3198  3223 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-27 08:53:42.888  3198  3223 I bt_hwcfg: vendor lib fwcfg completed
,07-27 08:53:42.889  3198  3223 I bt_vendor: firmware callback
07-27 08:53:42.889  3198  3223 I bt_hci  : firmware_config_callback
,07-27 08:53:42.897  3198  3230 I bt_btu  : btu_task pending for preload complete event
,07-27 08:53:42.897  3198  3230 I bt_btu_task: Bluetooth chip preload is complete
07-27 08:53:42.897  3198  3230 I bt_btu  : btu_task received preload complete event
,07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_SDP
,07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 08:53:42.905  3198  3230 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 08:53:42.922  3229  3229 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 08:53:42.943  3229  3229 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:53:42.944   789   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 08:53:42.948  3053  3053 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:53:42.956   789   802 I ActivityManager: Start proc 3232:com.android.settings/1000 for broadcast com.android.settings/.widget.SettingsAppWidgetProvider
,07-27 08:53:42.982  3232  3232 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-27 08:53:42.993   789   806 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2691500:true
,07-27 08:53:43.001  3232  3232 D LocalBluetoothProfileManager: Adding local MAP profile
,07-27 08:53:43.002  3232  3232 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:53:43.006  3232  3232 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-27 08:53:43.008  3229  3229 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:53:43.029   789  1337 I ActivityManager: Start proc 3245:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,07-27 08:53:43.029   789  1337 I ActivityManager: Killing 1251:com.google.android.gm/u0a41 (adj 15): empty #17
,07-27 08:53:43.118  3198  3230 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e59b5
,07-27 08:53:43.118  3198  3230 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e59b5 
,07-27 08:53:43.167  3198  3219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 08:53:43.167  3198  3219 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-27 08:53:43.175   789   891 D WifiConfigStore: Loading config and enabling all networks 
07-27 08:53:43.177  3198  3219 D BluetoothAdapterProperties: Name is: Nexus 5
07-27 08:53:43.178  3198  3219 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:53:43.178  3198  3219 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:53:43.179  3053  3053 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:43.179  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:43.179  3198  3219 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-27 08:53:43.179  3198  3219 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-27 08:53:43.180  3198  3219 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-27 08:53:43.180  3198  3219 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
07-27 08:53:43.180  3198  3219 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-27 08:53:43.180  3198  3219 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-27 08:53:43.180  3198  3219 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-27 08:53:43.181  3053  3053 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:43.181  3053  3053 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:53:43.182  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-27 08:53:43.182  3053  3053 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:53:43.182   789   891 D WifiConfigStore: loaded 0 passpoint configs
07-27 08:53:43.184  3198  3198 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 08:53:43.184   789   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-27 08:53:43.185   789   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:53:43.185   789   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-27 08:53:43.185   789   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-27 08:53:43.186  3198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.189  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-27 08:53:43.190   789   891 D WifiNative-HAL: Setting external_sim to 1
07-27 08:53:43.190   789   891 D wifi    : setting dfs flag to true, 0x9bb618f0
07-27 08:53:43.191   789   891 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:53:43.191   789   891 D wifi    : setting scan oui 0x9bb618f0
07-27 08:53:43.191   789   891 D WifiHAL : Sending mac address OUI
07-27 08:53:43.192  3,198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.192  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
07-27 08:53:43.193  3198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.195  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
07-27 08:53:43.196  3198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.200  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-27 08:53:43.201  3198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.204  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-27 08:53:43.206  3198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.209  3198  3219 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-27 08:53:43.211   789   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-27 08:53:43.212  3198  3198 D HidService: getHidService(): service is NULL
07-27 08:53:43.213  3198  3219 D bt_hci  : do_postload posting postload work item
07-27 08:53:43.213  3198  3223 I bt_hci  : event_postload
07-27 08:53:43.213  3198  3223 I bt_vendor: sco_config_cb
07-27 08:53:43.213  3198  3223 I bt_hci  : sco_config_callback postload finished.
07-27 08:53:43.214  3198  3223 I bt_vendor: low_power_mode_cb
07-27 08:53:43.214  3198  3219 D bt_bte_conf: Device ID record 1 : primary
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   vendorId            = 000f
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   vendorIdSource      = 0001
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   product             = 1200
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   version             = 1436
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   clientExecutableURL = 
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   serviceDescription  = 
07-27 08:53:43.214  3198  3219 D bt_bte_conf:   documentationURL    = 
07-27 08:53:43.214  3198  3219 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 08:53:43.214  3198  3216 D bt_stack_manager: event_start_up_stack finished
07-27 08:53:43.215   193   785 D CommandListener: Setting iface cfg
07-27 08:53:43.215   193   785 D CommandListener: Trying to bring up p2p0
07-27 08:53:43.215   789   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 08:53:43.215   789   789 D RttService: SCAN_AVAILABLE : 3
07-27 08:53:43.215   789   908 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:53:43.216   789   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-27 08:53:43.216  3198  3215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 08:53:43.216  3198  3215 D BluetoothAdapterProperties: Setting state to 15
07-27 08:53:43.216  3198  3215 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 08:53:43.217  3198  3215 I BluetoothAdapterState: Entering BleOnState
07-27 08:53:43.220  3198  3215 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-27 08:53:43.220  3198  3215 D BluetoothAdapterProperties: Setting state to 11
07-27 08:53:43.220  3198  3215 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-27 08:53:43.222  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:43.224  3198  3198 D HeadsetService: Received start request. Starting profile...
07-27 08:53:43.225  3198  3198 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:53:43.231  3198  3198 D HeadsetStateMachine: make
07-27 08:53:43.234   789   890 D WifiNative-HAL: p2pGetDeviceAddress
07-27 08:53:43.234   789   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
07-27 08:53:43.237  3198  3215 I BluetoothAdapterState: Entering PendingCommandState
07-27 08:53:43.244   789   891 E native  : do suspend false
07-27 08:53:43.248  3198  3198 D HeadsetStateMachine: max_hf_connections = 1
07-27 08:53:43.248  3198  3198 I bt_bluedroid: get_profile_interface handsfree
07-27 08:53:43.248  3198  3219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-27 08:53:43.251  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:43.251  3198  3219 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-27 08:53:43.251   789   789 D BluetoothA2dp: Proxy object connected
07-27 08:53:43.252  3198  3198 D A2dpService: Received start request. Starting profile...
07-27 08:53:43.253  3198  3198 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:53:43.253  3198  3198 I bt_bluedroid: get_profile_interface avrcp
07-27 08:53:43.258  3198  3198 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 08:53:43.258  3198  3198 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:53:43.258  3198  3198 D A2dpStateMachine: make
07-27 08:53:43.259  3198  3198 I bt_bluedroid: get_profile_interface a2dp
07-27 08:53:43.260  3198  3219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-27 08:53:43.261  3198  3275 D A2dpStateMachine: Enter Disconnected: -2
07-27 08:53:43.261  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:43.262  3198  3198 D HidService: Received start request. Starting profile...
07-27 08:53:43.262  3198  3198 I bt_bluedroid: get_profile_interface hidhost
07-27 08:53:43.262  3198  3198 D HidService: setHidService(): set to: null
07-27 08:53:43.263  3198  3198 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:53:43.263  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:43.263  3198  3219 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c7099
07-27 08:53:43.263  3198  3219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 08:53:43.264  3198  3198 D HealthService: Received start request. Starting profile...
07-27 08:53:43.267  3198  3198 I bt_bluedroid: get_profile_interface health
07-27 08:53:43.267   789   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-27 08:53:43.268  3198  3198 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 08:53:43.268   789   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-27 08:53:43.268  3232  3232 D BluetoothInputDevice: Proxy object connected
07-27 08:53:43.271  3232  3232 D HidProfile: Bluetooth service connected
07-27 08:53:43.271   931   931 D BluetoothInputDevice: Proxy object connected
07-27 08:53:43.271   931   931 D HidProfile: Bluetooth service connected
07-27 08:53:43.275  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:43.276   931   931 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:53:43.276  3198  3198 D PanService: Received start request. Starting profile...
,07-27 08:53:43.276  3198  3198 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 08:53:43.276  3198  3198 I bt_bluedroid: get_profile_interface pan
07-27 08:53:43.277   931   931 D PanProfile: Bluetooth service connected
07-27 08:53:43.277  3198  3219 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:53:43.292  3232  3232 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:53:43.292  3232  3232 D PanProfile: Bluetooth service connected
07-27 08:53:43.297  3198  3198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aba9dc9
07-27 08:53:43.298   931   931 D BluetoothMap: Proxy object connected
07-27 08:53:43.298  3198  3198 D BluetoothMapService: Received start request. Starting profile...
07-27 08:53:43.298  3198  3198 D BluetoothMapService: start()
07-27 08:53:43.298   931   931 D MapProfile: Bluetooth service connected
07-27 08:53:43.298   931   931 D BluetoothMap: getConnectedDevices()
07-27 08:53:43.299   931   931 D BluetoothMap: Bluetooth is Not enabled
07-27 08:53:43.299  3232  3232 D BluetoothMap: Proxy object connected
07-27 08:53:43.300  3232  3232 D MapProfile: Bluetooth service connected
07-27 08:53:43.300  3232  3232 D BluetoothMap: getConnectedDevices()
07-27 08:53:43.300  3198  3198 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-27 08:53:43.301  3232  3232 D BluetoothMap: Bluetooth is Not enabled
07-27 08:53:43.301  3198  3198 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-27 08:53:43.301  3198  3198 D BluetoothMapAppObserver: createReceiver()
07-27 08:53:43.301  3198  3198 D BluetoothMapAppObserver: initObservers()
07-27 08:53:43.301  3198  3198 D BluetoothMapAppObserver: getEnabledAccountItems()
07-27 08:53:43.307  3198  3263 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-27 08:53:43.307  3198  3198 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:43.307  3198  3198 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:43.308  3198  3198 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:43.308  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOff()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isTurningOn()=true
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:53:43.309  3198  3198 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:53:43.310  3198  3215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-27 08:53:43.310  3198  3215 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:53:43.310  3198  3215 D BluetoothAdapterProperties: State =  11
07-27 08:53:43.312  3198  3219 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:53:43.312  3198  3219 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:53:43.312  3198  3215 D BluetoothAdapterProperties: Setting state to 12
07-27 08:53:43.313  3198  3215 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:53:43.313   789   806 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:53:43.313  3198  3215 I BluetoothAdapterState: Entering OnState
07-27 08:53:43.313   789   806 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:53:43.315  3232  3244 D BluetoothMap: onBluetoothStateChange: up=true
07-27 08:53:43.315  3053  3053 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 08:53:43.316  1315  1473 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:53:43.317   931   943 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 08:53:43.319   789   806 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:43.319  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:43.319  3232  3243 D BluetoothPan: onBluetoothStateChange on: true
07-27 08:53:43.319   931  1433 D BluetoothMap: onBluetoothStateChange: up=true
07-27 08:53:43.320   931   944 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 08:53:43.320   789   806 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:53:43.320  3232  3242 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 08:53:43.321  3053  3053 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:53:43.321   931   943 D BluetoothPan: onBluetoothStateChange on: true
,07-27 08:53:43.322  3232  3244 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 08:53:43.323   789   789 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 08:53:43.323  3198  3198 D BluetoothMapService: onReceive
07-27 08:53:43.323  3198  3198 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:43.323  3198  3198 D BluetoothMapService: STATE_ON
07-27 08:53:43.326  3232  3232 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 08:53:43.326  3198  3198 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 08:53:43.326  3198  3198 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-27 08:53:43.329  3232  3232 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:53:43.330  3198  3198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:53:43.330   931  1118 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 08:53:43.332  3198  3198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:53:43.333  3198  3198 D ObexServerSockets: Succeed to create listening sockets 
,07-27 08:53:43.333  3198  3198 D ObexServerSockets0: startAccept()
07-27 08:53:43.333  3198  3198 D ObexServerSockets0: prepareForNewConnect()
07-27 08:53:43.335  3198  3198 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-27 08:53:43.335  3198  3198 D BluetoothSdpJni: SDP Create record success - handle: 0
07-27 08:53:43.335  3198  3286 D ObexServerSockets0: Accepting socket connection...
07-27 08:53:43.336  3198  3287 D ObexServerSockets0: Accepting socket connection...
,07-27 08:53:43.340   931   931 D BluetoothA2dp: Proxy object connected
,07-27 08:53:43.341   931  1118 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-27 08:53:43.342  3232  3232 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.343  3232  3232 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-27 08:53:43.344  3198  3198 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 08:53:43.344  3198  3198 D ObexServerSockets0: prepareForNewConnect()
07-27 08:53:43.344  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.355   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.358   931  1118 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-27 08:53:43.360   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.363  3245  3245 W InstanceID/Rpc: Found 10007
,07-27 08:53:43.366  3232  3232 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.367  3232  3232 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-27 08:53:43.368  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.378  3232  3232 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.380  3232  3232 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-27 08:53:43.382  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.393  3232  3232 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.394  3232  3232 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-27 08:53:43.396  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.411   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.413  3232  3232 D BluetoothMap: getConnectedDevices()
07-27 08:53:43.413   931  1118 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-27 08:53:43.414  3232  3232 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-27 08:53:43.416   789   806 D BluetoothHeadset: Proxy object connected
,07-27 08:53:43.417  1315  1463 D BluetoothHeadset: Proxy object connected
,07-27 08:53:43.419   789   806 D BluetoothHeadset: Proxy object connected
,07-27 08:53:43.420  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.420   789   806 D BluetoothHeadset: Proxy object connected
,07-27 08:53:43.424   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.428  3232  3232 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.429  3232  3232 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-27 08:53:43.431  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.432  3232  3242 D BluetoothHeadset: Proxy object connected
,07-27 08:53:43.443  3232  3232 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.444   931  1433 D BluetoothHeadset: Proxy object connected
,07-27 08:53:43.445  3232  3232 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-27 08:53:43.446  3232  3232 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.446  3232  3232 D BluetoothA2dp: Proxy object connected
,07-27 08:53:43.450   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.454   931  1118 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-27 08:53:43.455   789   892 D WifiService: New client listening to asynchronous messages
,07-27 08:53:43.456   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.457   931   931 D HeadsetProfile: Bluetooth service connected,
07-27 08:53:43.458  3232  3232 D HeadsetProfile: Bluetooth service connected
,07-27 08:53:43.467   789   957 I ActivityManager: Killing 2580:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,07-27 08:53:43.690  1275  1275 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-27 08:53:43.700   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.703  1275  1275 I BeaconBle: BLE 'JB+' software access layer enabled
,07-27 08:53:43.704   931  1118 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-27 08:53:43.708   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.719  1275  1275 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 08:53:43.725  1275  1275 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 08:53:43.736   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.738  3232  3232 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 08:53:43.738   931  1118 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-27 08:53:43.752   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.757  1275  3310 D BluetoothAdapter: startLeScan(): null
,07-27 08:53:43.762  1275  3310 D BluetoothAdapter: STATE_ON
,07-27 08:53:43.763   931   931 D BluetoothPbap: Proxy object connected
,07-27 08:53:43.763   931   931 D PbapServerProfile: Bluetooth service connected
,07-27 08:53:43.765  3198  3311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:43.768  3198  3213 D BtGatt.GattService: registerClient() - UUID=f1f69bea-1c78-40bb-b745-d32f4f647b87
,07-27 08:53:43.769  3198  3219 D BtGatt.GattService: onClientRegistered() - UUID=f1f69bea-1c78-40bb-b745-d32f4f647b87, clientIf=5
07-27 08:53:43.769  1275  1304 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-27 08:53:43.770  3198  3295 D BtGatt.GattService: start scan with filters
07-27 08:53:43.772  3232  3232 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:53:43.775  3198  3222 D BtGatt.ScanManager: handling starting scan
,07-27 08:53:43.778  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-27 08:53:43.779  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-27 08:53:43.779  3198  3222 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
,07-27 08:53:43.783  3198  3219 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-27 08:53:43.791  3232  3232 D BluetoothPbap: Proxy object connected
,07-27 08:53:43.791  3232  3232 D PbapServerProfile: Bluetooth service connected
07-27 08:53:43.793   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.800   931  1118 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-27 08:53:43.801   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:43.811  1275  1275 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 08:53:43.818  1275  3317 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 08:53:43.819  1275  1275 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 08:53:43.837  3198  3319 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:43.841  3198  3319 I BtOppRfcommListener: Accept thread started.
,07-27 08:53:43.842  1275  3317 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 08:53:43.856   931  1118 D BluetoothMap: getConnectedDevices()
,07-27 08:53:43.859   931  1118 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-27 08:53:43.860   931  1118 D MapProfile: getConnectionStatus: status is: 0
,07-27 08:53:44.093  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:53:44.114  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Braceli5-4955 len=13 dev_type=2
,07-27 08:53:44.219  1275  3272 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:53:44.221  1275  3272 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: java.io.IOException: Not connected
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:53:44.221  1275  3272 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:44.526  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:53:44.732  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:53:44.898  3229  3229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-27 08:53:44.899  3229  3229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-27 08:53:44.939   789   891 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-27 08:53:44.945   789   891 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-27 08:53:44.945   789   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:53:44.987   789   891 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-27 08:53:45.026   789   891 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-27 08:53:45.027  3229  3229 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-27 08:53:45.264  1275  3272 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:53:45.267  1275  3272 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: java.io.IOException: Not connected
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at reh.run(:com.google.android.gms:75)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:53:45.267  1275  3272 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:45.289  1275  3310 D BluetoothAdapter: stopLeScan()
,07-27 08:53:45.290  1275  3310 D BluetoothAdapter: STATE_ON
,07-27 08:53:45.294  3198  3285 D BtGatt.GattService: stopScan() - queue size =1
,07-27 08:53:45.295  3198  3222 D BtGatt.ScanManager: stop scan
07-27 08:53:45.295  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-27 08:53:45.295  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-27 08:53:45.295  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-27 08:53:45.295  3198  3296 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-27 08:53:45.322  3229  3229 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 08:53:45.362  3229  3229 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-27 08:53:45.362  3229  3229 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-27 08:53:45.369   789   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-27 08:53:45.381   789   891 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:53:45.382   789   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 08:53:45.382   789   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-27 08:53:45.407   789   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:53:45.416   193   785 D CommandListener: Setting iface cfg
,07-27 08:53:45.421   789   891 D WifiStateMachine: Start Dhcp Watchdog 1
,07-27 08:53:45.433   789   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-27 08:53:45.433   789   893 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,07-27 08:53:45.435   789   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-27 08:53:45.459   789  3353 D DhcpClient: Receive thread started
,07-27 08:53:45.469  1275  3310 D BluetoothAdapter: startLeScan(): null
,07-27 08:53:45.471  1275  3310 D BluetoothAdapter: STATE_ON
,07-27 08:53:45.473  3198  3296 D BtGatt.GattService: registerClient() - UUID=037d47e7-80b0-4a2a-a43b-1781915b8097
,07-27 08:53:45.473  3198  3219 D BtGatt.GattService: onClientRegistered() - UUID=037d47e7-80b0-4a2a-a43b-1781915b8097, clientIf=5
07-27 08:53:45.474  1275  1304 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 08:53:45.474  3198  3208 D BtGatt.GattService: start scan with filters
,07-27 08:53:45.476  3198  3222 D BtGatt.ScanManager: handling starting scan
,07-27 08:53:45.478  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-27 08:53:45.478  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-27 08:53:45.478  3198  3222 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-27 08:53:45.478  3198  3219 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-27 08:53:45.543   789   891 E native  : do suspend false
,07-27 08:53:45.551   789  3349 D DhcpClient: Broadcasting DHCPDISCOVER
,07-27 08:53:45.655   789  3353 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 166000, domain null
,07-27 08:53:45.655   789  3349 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 166000 seconds
,07-27 08:53:45.656   789  3349 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-27 08:53:45.685  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:53:45.692   789  3353 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-27 08:53:45.692   789  3349 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-27 08:53:45.693   193   785 D CommandListener: Setting iface cfg
,07-27 08:53:45.697   789   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-27 08:53:45.698   789  3349 D DhcpClient: Scheduling renewal in 86399s
,07-27 08:53:45.702   789   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-27 08:53:45.703   789   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-27 08:53:45.705   789   891 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 08:53:45.705   789   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-27 08:53:45.709   789   893 D ConnectivityService: Adding iface wlan0 to network 100
,07-27 08:53:45.758  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:53:45.759   789   893 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 08:53:45.759   789   893 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-27 08:53:45.761   789   893 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-27 08:53:45.764   789   893 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-27 08:53:45.766   789   893 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-27 08:53:45.774   789   893 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-27 08:53:45.786   789   893 D ConnectivityService: scheduleUnvalidatedPrompt 100
,07-27 08:53:45.786   789   893 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-27 08:53:45.786   789   893 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-27 08:53:45.786   789   893 D ConnectivityService:    accepting network in place of null
07-27 08:53:45.786   789   891 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-27 08:53:45.787   789   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 08:53:45.789   789   893 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -58]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 08:53:45.820   193   785 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:53:45.850   193   785 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-27 08:53:45.851   789   893 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,07-27 08:53:45.854   789   893 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 08:53:45.854   789   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:45.857   789   806 D Tethering: MasterInitialState.processMessage what=3
,07-27 08:53:45.859   789   893 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-27 08:53:45.860  2510  2510 D MusicLifecycle: com.google.android.music.net.SystemNetworkMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@e99dbb8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-27 08:53:45.875   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=106414, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 08:53:45.880   789   789 I ActivityManager: Start proc 3374:com.google.android.apps.photos/u0a83 for service com.google.android.apps.photos/.onboarding.autosignin.AutoSignInAndSyncJobService
,07-27 08:53:45.887  3053  3053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:53:45.898  1384  1384 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:53:45.904  3053  3053 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 08:53:45.906  3053  3053 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 08:53:45.909   789   800 I ActivityManager: Start proc 3391:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-27 08:53:45.908  2502  2502 W ChromiumNet: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21228]" dev="sockfs" ino=21228 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-27 08:53:45.908  2502  2502 W ChromiumNet: type=1400 audit(0.0:10): avc: denied { ioctl } for path="socket:[21239]" dev="sockfs" ino=21239 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-27 08:53:45.924   789  1281 D AlarmManagerService: Setting time of day to sec=1469602426
,07-27 08:53:46.449   789  1281 W AlarmManagerService: Unable to set rtc to 1469602426: Invalid argument
,07-27 08:53:46.462   789  3337 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.84,2a00:1450:400d:802::200e
,07-27 08:53:46.473   789  3337 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 06:53:46 GMT], X-Android-Received-Millis=[1469602426473], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469602426468]}
,07-27 08:53:46.474   789   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-27 08:53:46.474   789   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
,07-27 08:53:46.475   789   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-27 08:53:46.476   789   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 08:53:46.508  3391  3391 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-27 08:53:46.535   789   801 I ActivityManager: Start proc 3408:com.google.android.apps.plus/u0a63 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,07-27 08:53:46.614  1275  1275 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:53:46.626  1567  3427 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:53:46.629  3391  3391 E SetupWizard: tickleCheckinService called after completing user setup
,07-27 08:53:46.633   789  3428 D GpsLocationProvider: NTP server returned: 1469602426449 (Wed Jul 27 08:53:46 GMT+02:00 2016) reference: 106464 certainty: 11 system time offset: -183
,07-27 08:53:46.634  3391  3391 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-27 08:53:46.639   789   801 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 27872, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:53:46.640   789   801 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 139151, reason: UserStart
,07-27 08:53:46.678  3391  3415 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-27 08:53:46.689   789  1324 I ActivityManager: Start proc 3434:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-27 08:53:46.729  3434  3434 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-27 08:53:46.740  1567  3422 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-27 08:53:46.774  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:53:46.775  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:53:46.844  1275  3272 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:53:46.865  1275  3272 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:53:46.866  1275  3272 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-27 08:53:46.873  1275  3272 V BaseAppContext: GmsRequestQueue started.
,07-27 08:53:46.973  1275  3431 I GCM     : GCM config loaded
,07-27 08:53:47.023  3434  3434 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:53:47.023  3434  3434 I MultiDex: install
07-27 08:53:47.023  3434  3434 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:53:47.054   789  1330 I ActivityManager: Killing 2510:com.google.android.music:main/u0a58 (adj 15): empty #17
,07-27 08:53:47.107  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:53:47.107  3053  3108 I jxcore-log: 
,07-27 08:53:47.307  1275  3310 D BluetoothAdapter: stopLeScan()
,07-27 08:53:47.308  1275  3310 D BluetoothAdapter: STATE_ON
,07-27 08:53:47.308  3198  3213 D BtGatt.GattService: stopScan() - queue size =1
,07-27 08:53:47.309  3198  3296 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 08:53:47.309  1275  3310 I BeaconBle: Scan : No clients left, canceling alarm.
,07-27 08:53:47.309  3198  3222 D BtGatt.ScanManager: stop scan
07-27 08:53:47.309  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-27 08:53:47.309  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-27 08:53:47.309  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-27 08:53:47.343  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:53:47.388  3434  3434 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-27 08:53:47.388  3434  3434 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:53:47.388  3434  3434 I GAv4    :   adb logcat -s GAv4
,07-27 08:53:47.417  3434  3434 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:47.443  3434  3502 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:47.612  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:53:47.612  3053  3108 I jxcore-log: 
,07-27 08:53:47.640  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:53:47.640  3053  3108 I jxcore-log: 
,07-27 08:53:47.644  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:53:47.644  3053  3108 I jxcore-log: 
,07-27 08:53:47.663  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:53:47.663  3053  3108 I jxcore-log: 
,07-27 08:53:47.667  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:53:47.667  3053  3108 I jxcore-log: 
,07-27 08:53:47.681  3434  3434 I NSApplication: Starting up...
,07-27 08:53:47.687   789  1162 I ActivityManager: Killing 2625:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-27 08:53:47.821   789   799 I ActivityManager: Start proc 3535:com.qualcomm.timeservice/u0a68 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,07-27 08:53:47.844  1567  1567 V Herrevad: NQAS connected
,07-27 08:53:47.859  3535  3535 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-27 08:53:47.870  3535  3535 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1469602427870
,07-27 08:53:47.870  3535  3535 D         : TimeServiceNative: User Time to be set is 1469602427870
07-27 08:53:47.870  3535  3535 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-27 08:53:47.870  3535  3535 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-27 08:53:47.870  3535  3535 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1469602427870
07-27 08:53:47.871   216   590 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-27 08:53:47.871  3535  3535 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1469602427870
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1469602427870, operation = 0
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/17/71 0:57:17
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:Value read from RTC seconds = 53917037000
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:new time 1469602427870 
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon: delta 1415685390870 genoff 1415685390870 
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685390870 to memory
07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
,07-27 08:53:47.872   216  3551 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:53:47.878   216  3551 D QC-time-services: Updating the TOD offset
07-27 08:53:47.878   216  3551 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685390870 to memory
07-27 08:53:47.878   216  3551 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
,07-27 08:53:47.878   216  3551 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:53:47.884   216  3551 D QC-time-services: Daemon:Update to modem bit set
07-27 08:53:47.884   216  3551 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-27 08:53:47.884   216  3551 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1153637627870
,07-27 08:53:47.884  3535  3535 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-27 08:53:47.885   789  1330 I ActivityManager: Killing 2770:com.google.android.partnersetup/u0a11 (adj 15): empty #17
07-27 08:53:47.885   216   588 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-27 08:53:47.885   216   590 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-27 08:53:48.214   789   990 I ActivityManager: Start proc 3560:com.google.android.deskclock/u0a33 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-27 08:53:48.253  3560  3560 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.deskclock-2/lib/arm
,07-27 08:53:48.253  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.256   789   799 D ConnectivityService: listenForNetwork for Listen from uid/pid:10063/3408 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-27 08:53:48.308  1275  3423 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-27 08:53:48.318  3560  3560 I GAv4    : Google Analytics 8.4.87 is starting up. To enable debug logging on a device run:
07-27 08:53:48.318  3560  3560 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:53:48.318  3560  3560 I GAv4    :   adb logcat -s GAv4
,07-27 08:53:48.323  1275  3423 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-27 08:53:48.336  3560  3560 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:48.342  1567  1625 W Herrevad: Invalid mccmnc 
,07-27 08:53:48.343  1567  1625 W Herrevad: Invalid mccmnc 
,07-27 08:53:48.345  3560  3560 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:48.349  3560  3560 I AlarmClock: AlarmInitReceiver android.intent.action.TIME_SET
,07-27 08:53:48.355  3560  3585 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:53:48.397  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.400   789   990 I ActivityManager: Start proc 3589:com.google.android.calendar/u0a28 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-27 08:53:48.442  3589  3589 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.calendar-1/lib/arm
,07-27 08:53:48.480   789  1324 I ActivityManager: Killing 2798:com.android.musicfx/u0a13 (adj 15): empty #17
,07-27 08:53:48.564  1567  3602 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-27 08:53:48.564  1567  3602 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-27 08:53:48.701   789   799 I ActivityManager: Start proc 3617:com.google.android.talk/u0a51 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.broadcastreceiver.GcmStateReceiver
,07-27 08:53:48.742  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:53:48.762   789  1338 I ActivityManager: Killing 2815:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,07-27 08:53:48.771  3589  3589 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-27 08:53:48.900  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.902  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.961  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.962  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:48.966   789   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-27 08:53:49.032  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:49.033  3408  3558 I art     : Note: end time exceeds epoch: 
,07-27 08:53:49.134  3617  3617 I Babel_telephony: TeleModule.onApplicationCreate
,07-27 08:53:49.137  3617  3641 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-27 08:53:49.137  3617  3641 I Babel_SMS: MmsConfig.loadMmsSettings
,07-27 08:53:49.139  3617  3641 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-27 08:53:49.139  3617  3641 I Babel_SMS: MmsConfig.loadFromDatabase
,07-27 08:53:49.145  3617  3641 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-27 08:53:49.145  3617  3641 I Babel_SMS: MmsConfig.loadFromResources
,07-27 08:53:49.147  3617  3641 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 08:53:49.147  3617  3641 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-27 08:53:49.170  3617  3644 I Babel_SMS: ApnsOta: OTA version -1
,07-27 08:53:49.176  3617  3617 I Babel_Prime: wrapCrashReportingIntoUncaughtExceptionHandler
,07-27 08:53:49.177  3617  3617 I Babel_Prime: isMemoryEnabled=false
,07-27 08:53:49.178  3617  3617 I Babel_Prime: isTimerEnabled=false
,07-27 08:53:49.178  3617  3617 I Babel_Prime: isCrashCounterEnabled=true
,07-27 08:53:49.180  3617  3617 I Babel_Prime: primesPackageConfigurationsProvider=false
,07-27 08:53:49.190  3617  3617 I Babel_App: Startup - clean
,07-27 08:53:49.215  3617  3617 I Babel_Prime: startMemoryMonitor
,07-27 08:53:49.227   789   990 I ActivityManager: Killing 2730:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-27 08:53:49.351   789   990 I ActivityManager: Killing 2886:com.quickoffice.android/u0a65 (adj 15): empty #18
,07-27 08:53:49.898  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:53:49.898  3053  3108 I jxcore-log: 
,07-27 08:53:49.909  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:53:49.909  3053  3108 I jxcore-log: 
,07-27 08:53:49.919  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:53:49.919  3053  3108 I jxcore-log: 
,07-27 08:53:50.073  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:53:50.073  3053  3108 I jxcore-log: 
,07-27 08:53:50.335  1275  3300 I BeaconBle: Scan : No clients left, canceling alarm.
,07-27 08:53:50.889  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:53:50.889  3053  3108 I jxcore-log: 
,07-27 08:53:50.944  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:53:50.944  3053  3108 I jxcore-log: 
,07-27 08:53:50.950  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:53:50.950  3053  3108 I jxcore-log: 
,07-27 08:53:51.151  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:53:51.151  3053  3108 I jxcore-log: 
,07-27 08:53:51.172  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:53:51.172  3053  3108 I jxcore-log: 
,07-27 08:53:51.176  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:53:51.176  3053  3108 I jxcore-log: 
,07-27 08:53:51.181  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:53:51.181  3053  3108 I jxcore-log: 
,07-27 08:53:51.196  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:53:51.196  3053  3108 I jxcore-log: 
,07-27 08:53:51.216  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:53:51.216  3053  3108 I jxcore-log: 
,07-27 08:53:51.303  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:53:51.303  3053  3108 I jxcore-log: 
,07-27 08:53:51.308  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:53:51.308  3053  3108 I jxcore-log: 
,07-27 08:53:51.333  3053  3108 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:53:51.333  3053  3108 I jxcore-log: 
,07-27 08:53:51.342  3053  3108 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-27 08:53:51.343  3053  3108 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 08:53:51.343  3053  3108 I jxcore-log: 
,07-27 08:53:51.389  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 08:53:51.389  3053  3108 I jxcore-log: 
,07-27 08:53:51.390  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:53:51.390  3053  3108 I jxcore-log: 
,07-27 08:53:51.390  3053  3108 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:53:51.390  3053  3108 I jxcore-log: 
,07-27 08:53:51.976   789   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-27 08:53:52.059   789  1338 I ActivityManager: Killing 2957:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,07-27 08:53:53.697  3589  3606 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:53:54.312   789   893 D ConnectivityService: handlePromptUnvalidated 100
,07-27 08:53:54.991   789   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-27 08:53:58.796   789   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,07-27 08:54:00.393  1384  1486 W GmsLocationProvider: Error removing location updates: 16
,07-27 08:54:04.143  3617  3636 W Babel   : bcp TOOK TOO LONG! (15022ms > 10000ms)
,07-27 08:54:04.148  3617  3640 W Babel   : bcp TOOK TOO LONG! (15008ms > 10000ms)
,07-27 08:54:04.246   789   802 I ActivityManager: Start proc 3710:com.google.android.talk:matchstick/u0a51 for broadcast com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,07-27 08:54:04.255  3617  3648 W Babel   : bcp TOOK TOO LONG! (15037ms > 10000ms)
,07-27 08:54:04.264   789  1324 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:54:04.281  3617  3617 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-27 08:54:04.281  3617  3617 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:54:04.282  3617  3617 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:54:04.282  3617  3617 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-27 08:54:04.284   789  1324 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:54:04.669  3710  3743 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService } isPeriodic:false
,07-27 08:54:04.691  3710  3743 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:54:04.703  3710  3743 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-27 08:54:04.703  3710  3743 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:54:04.706  3710  3743 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:54:04.727  3710  3743 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:54:04.728  3710  3743 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,07-27 08:54:04.730   789   799 I ActivityManager: Killing 2987:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-27 08:54:07.928  3229  3229 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-27 08:54:19.496  1567  3764 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:54:19.498   789   801 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 139151, reason: UserStart, SyncResult: databaseError: true stats []
07-27 08:54:19.498   789   801 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 204504, reason: UserStart
,07-27 08:54:19.665   789  1338 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1567 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:54:19.735  1567  3777 W DriveInitializer: Background init thread started
,07-27 08:54:19.815  1567  3777 W DriveInitializer: Background init thread ended
,07-27 08:54:19.824   789   800 I ActivityManager: Start proc 3786:com.google.android.gms.unstable/u0a7 for service com.google.android.gms/.droidguard.DroidGuardService
,07-27 08:54:19.872  3786  3786 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:54:19.872  3786  3786 I MultiDex: install
,07-27 08:54:19.872  3786  3786 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:54:19.900  3786  3786 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:54:19.919  3786  3786 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-27 08:54:19.920  3786  3786 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:54:19.926  3786  3786 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:54:19.930  1275  3807 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:54:19.931  1275  3780 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:54:19.947  1275  3807 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:54:19.947  1275  3780 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:54:19.962  1275  3807 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:54:19.963  1275  3780 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:54:19.963  1275  3780 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
07-27 08:54:19.966  3786  3786 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:54:19.967  1275  3780 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:54:19.976  3786  3786 D ChimeraCfgMgr: Reading stored module config
,07-27 08:54:19.996  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:19.997  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:20.039  3786  3809 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 08:54:20.073   197   829 D WVCdm   : Instantiating CDM.
,07-27 08:54:20.074   197   899 I WVCdm   : CdmEngine::OpenSession
,07-27 08:54:20.074   197   899 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-27 08:54:20.089   197   899 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-27 08:54:20.093   197   899 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-27 08:54:20.095   197   899 D DrmWidevineDash: Service_Initialize: starts!
07-27 08:54:20.095   197   899 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-27 08:54:20.095   197   899 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 08:54:20.115   197   899 D QSEECOMAPI: : Loaded image: APP id = 3
,07-27 08:54:20.115   197   899 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-27 08:54:20.115   197   899 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3326000
07-27 08:54:20.116   197   899 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3326000
,07-27 08:54:20.132   197   899 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-27 08:54:20.132   197   899 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-27 08:54:20.138   197   899 D DrmWidevineDash: hlos api version =  10
,07-27 08:54:20.138   197   899 D DrmWidevineDash: tz api version =  10
07-27 08:54:20.138   197   899 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-27 08:54:20.138   197   899 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-27 08:54:20.148   197   899 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-27 08:54:20.148   197   899 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-27 08:54:20.149   197   899 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb36bd134
,07-27 08:54:20.153   197   899 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-27 08:54:20.153   197   899 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-27 08:54:20.153   197   899 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb46d2238, dataLength=8
,07-27 08:54:20.158   197   899 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-27 08:54:20.166   197   899 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb20d8c00, wrapped_rsa_key_length=1280
,07-27 08:54:20.173   197   899 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-27 08:54:20.173   197   899 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 08:54:20.176   197   900 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-27 08:54:20.176   197   900 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-27 08:54:20.176   197   900 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 08:54:20.176   197   900 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb32c4ba0, idLength=0xb353ef2c
,07-27 08:54:20.189   197   900 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-27 08:54:20.189   197   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-27 08:54:20.194   197   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-27 08:54:20.194   197   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-27 08:54:20.194   197   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-27 08:54:20.194   197   900 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-27 08:54:20.198   197   900 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-27 08:54:20.198   197   900 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-27 08:54:20.203   197   900 D DrmWidevineDash: hlos api version =  10
,07-27 08:54:20.203   197   900 D DrmWidevineDash: tz api version =  10
07-27 08:54:20.203   197   900 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-27 08:54:20.203   197   900 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-27 08:54:20.207   197   900 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-27 08:54:20.207   197   900 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-27 08:54:20.207   197   900 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-27 08:54:20.212   197   900 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-27 08:54:20.212   197   900 D WVCdm   : PrepareKeyRequest: nonce=2408935155
07-27 08:54:20.212   197   900 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb48e4c00
07-27 08:54:20.212   197   900 D DrmWidevineDash: message_length=1639, signature=0xb60f6840, signature_length=3008622596
,07-27 08:54:20.304   197   900 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-27 08:54:20.305   197   829 I WVCdm   : CdmEngine::CloseSession
07-27 08:54:20.305   197   829 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-27 08:54:20.309   197   829 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-27 08:54:20.309   197   829 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-27 08:54:20.316   197   829 D DrmWidevineDash: Service_Uninitialize: starts!
,07-27 08:54:20.317   197   829 D QSEECOMAPI: : QSEECom_dealloc_memory 
,07-27 08:54:20.317   197   829 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,07-27 08:54:20.318   197   829 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-27 08:54:20.318   197   829 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-27 08:54:20.528  3799  3799 W Binder_1: type=1400 audit(0.0:11): avc: denied { read } for name="/" dev="tmpfs" ino=6157 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,07-27 08:54:20.628  3828  3828 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-27 08:54:20.674  3828  3828 I dex2oat : dex2oat took 46.034ms (threads: 4) arena alloc=145KB java alloc=63KB native alloc=1406KB free=1409KB
,07-27 08:54:20.679  3786  3799 W System  : ClassLoader referenced unknown path: 
,07-27 08:54:20.684  3786  3799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-27 08:54:20.750  3786  3799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-27 08:54:20.787  3786  3799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-27 08:54:25.925   789  1337 I ActivityManager: Killing 3123:com.google.android.gms.feedback/u0a7 (adj 15): empty #17
,07-27 08:54:26.235   789   891 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-27 08:54:31.131   789   809 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-27 08:54:31.131   789   809 I PowerManagerService: Sleeping (uid 1000)...
07-27 08:54:31.136   190   232 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (428 us)
,07-27 08:54:31.143   789   809 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-27 08:54:31.160  3053  3053 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 08:54:31.160  3053  3053 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-27 08:54:31.235  3053  3053 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d5d6ea Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3b0b01c, 16908290=android.view.AbsSavedState$1@3b0b01c}, android:focusedViewId=100}]}]
07-27 08:54:31.235  3053  3053 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 08:54:31.235  3053  3053 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 08:54:31.235  3053  3053 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-27 08:54:31.301   789   798 I art     : Background partial concurrent mark sweep GC freed 22901(1397KB) AllocSpace objects, 4(96KB) LOS objects, 33% free, 25MB/38MB, paused 1.774ms total 145.900ms
,07-27 08:54:31.739   789   809 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-27 08:54:31.777   789   809 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-27 08:54:31.780   789   807 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-27 08:54:31.784   190   190 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
07-27 08:54:31.784   190   190 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-27 08:54:32.055   190   190 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-27 08:54:32.056   789   911 D SurfaceControl: Excessive delay in setPowerMode(): 275ms
07-27 08:54:32.057  1789  1808 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-27 08:54:32.077   197   900 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-27 08:54:32.100   789   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:54:32.114   789   891 E native  : do suspend false
07-27 08:54:32.118   789   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-27 08:54:32.141   789   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:54:32.142   789   891 E native  : do suspend true
07-27 08:54:32.144   197   829 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-27 08:54:32.159  1237  1237 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-27 08:54:32.171  1275  1275 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-27 08:54:32.173  1275  1275 I BeaconBle: BLE 'JB+' software access layer enabled
,07-27 08:54:32.182  1275  3906 D BluetoothAdapter: startLeScan(): null
,07-27 08:54:32.183  1275  3906 D BluetoothAdapter: STATE_ON
,07-27 08:54:32.184  3198  3296 D BtGatt.GattService: registerClient() - UUID=f373827a-5bf8-4013-9d9b-205099d42d83
07-27 08:54:32.184  3198  3219 D BtGatt.GattService: onClientRegistered() - UUID=f373827a-5bf8-4013-9d9b-205099d42d83, clientIf=5
07-27 08:54:32.185  1275  1291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 08:54:32.185  3198  3208 D BtGatt.GattService: start scan with filters
,07-27 08:54:32.186  3198  3222 D BtGatt.ScanManager: handling starting scan
,07-27 08:54:32.187  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-27 08:54:32.187  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-27 08:54:32.187  3198  3222 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-27 08:54:32.188  3198  3219 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-27 08:54:32.240  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Braceli5-4955 len=13 dev_type=2
,07-27 08:54:32.297  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:32.344  1275  3272 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:54:32.608   789   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,07-27 08:54:32.815  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:33.523  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:33.544  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:33.575  1275  3272 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:54:33.691  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:33.719  1275  3906 D BluetoothAdapter: stopLeScan()
,07-27 08:54:33.720  1275  3906 D BluetoothAdapter: STATE_ON
,07-27 08:54:33.720  3198  3296 D BtGatt.GattService: stopScan() - queue size =1
07-27 08:54:33.720  3198  3222 D BtGatt.ScanManager: stop scan
07-27 08:54:33.721  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-27 08:54:33.721  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-27 08:54:33.721  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-27 08:54:33.731  3198  3208 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-27 08:54:33.903  1275  3906 D BluetoothAdapter: startLeScan(): null
,07-27 08:54:33.904  1275  3906 D BluetoothAdapter: STATE_ON
07-27 08:54:33.911  3198  3295 D BtGatt.GattService: registerClient() - UUID=f182ac54-1e84-49ae-9658-d92d9c041769
07-27 08:54:33.911  3198  3219 D BtGatt.GattService: onClientRegistered() - UUID=f182ac54-1e84-49ae-9658-d92d9c041769, clientIf=5
07-27 08:54:33.911  1275  1304 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 08:54:33.912  3198  3213 D BtGatt.GattService: start scan with filters
07-27 08:54:33.913  3198  3222 D BtGatt.ScanManager: handling starting scan
07-27 08:54:33.914  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-27 08:54:33.914  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-27 08:54:33.914  3198  3222 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-27 08:54:33.931  3198  3219 D BtGatt.GattService: onScanParamSetupCompleted : 0
07-27 08:54:33.951  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Braceli5-4955 len=13 dev_type=2
,07-27 08:54:34.035  1275  1288 I art     : Background partial concurrent mark sweep GC freed 92350(6MB) AllocSpace objects, 67(1512KB) LOS objects, 40% free, 20MB/34MB, paused 2.668ms total 129.013ms
,07-27 08:54:34.058  1275  1286 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d5b2bf0)
,07-27 08:54:34.123  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:34.299  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:34.623  1275  3272 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:54:34.802  3198  3219 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-27 08:54:35.239  1275  3906 D BluetoothAdapter: stopLeScan()
,07-27 08:54:35.254  1275  3906 D BluetoothAdapter: STATE_ON
07-27 08:54:35.256  3198  3285 D BtGatt.GattService: stopScan() - queue size =1
07-27 08:54:35.257  3198  3222 D BtGatt.ScanManager: stop scan
07-27 08:54:35.257  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-27 08:54:35.257  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-27 08:54:35.258  3198  3222 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-27 08:54:35.274  3198  3295 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 08:54:35.279  1275  3906 I BeaconBle: Scan : No clients left, canceling alarm.
,07-27 08:54:36.729  1275  1676 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 08:54:38.195  1275  3895 I BeaconBle: Scan : No clients left, canceling alarm.
,07-27 08:54:46.238   789   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,07-27 08:55:17.118   191   191 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c8a030
,07-27 08:55:17.118   191   191 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,07-27 08:55:17.118   191   191 I rmt_storage: wakelock acquired: 1, error no: 2
,07-27 08:55:17.119   191   459 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229453008)
,07-27 08:55:17.307   191   459 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,07-27 08:55:17.307   191   459 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-27 08:55:17.307   191   459 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229453008) wakelock released: 1, error no: 0
07-27 08:55:17.307   191   459 I rmt_storage: 
07-27 08:55:17.307   191   191 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c8a030
,07-27 08:55:38.532   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218547, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:55:51.914   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231929, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 08:56:28.131   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:57:26.443  1596  1646 I PlayCommon: [97] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 08:57:26.475  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:26.507  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:57:26.507  1275  1275 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:57:26.530  1596  1646 I PlayCommon: [97] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 08:57:26.783  1596  1646 I PlayCommon: [97] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,07-27 08:57:31.541   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=331557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 08:58:24.851   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384867, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:58:40.162   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=400178, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 08:59:16.452   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=436467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:59:25.242   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=445258, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:00:00.100  3560  3560 I Periodic: Executing periodic callback for HOUR because the period ended
,07-27 09:00:01.572   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=481587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:01:31.984   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=571999, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:02:08.292   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=608308, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:02:31.802   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=631818, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:03:08.131   789  3346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=668147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:07:24.812  1567  3977 I EventLogChimeraService: Aggregate from 1469600776245 (log), 1469600776245 (data)
,07-27 09:07:24.847  1384  3976 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-27 09:07:24.906  1384  3976 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,07-27 09:07:24.906  1384  3976 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-27 09:07:24.914  1384  3976 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,07-27 09:07:24.914  1384  3976 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-27 09:07:24.962  1384  3976 I ContextCompilationHandl: Recognition context unchanged for CONTACT_NAMES en-US
,07-27 09:07:24.962  1384  3976 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-27 09:07:25.013  1567  1641 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.gms start 0 num 1000
,07-27 09:07:25.015  1567  3988 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-27 09:07:25.028  1567  3986 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:07:25.049  1567  3986 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:07:25.508  1384  3976 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-27 09:07:25.542  1567  1641 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-27 09:07:25.560  1567  1641 E Icing   : No scoring data for corpus [21]
,07-27 09:07:25.578  1567  1639 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:07:25.622  1567  1639 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:07:25.659  1567  1641 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:07:25.676  1567  1641 E Icing   : No scoring data for corpus [22]
,07-27 09:07:25.678  1384  3976 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-27 09:12:20.862   789   801 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:12:26.799  1596  1646 I PlayCommon: [97] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:12:26.799  1596  1646 I PlayCommon: [97] com.google.android.play.a.al.e(732): No file ready to send
,TIME-OUT KILL (timeout was 1400000ms),07-27 09:17:01.305  4022  4022 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 09:17:01.313  4022  4022 D AndroidRuntime: CheckJNI is OFF
07-27 09:17:01.362  4022  4022 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 09:17:01.417  4022  4022 I Radio-JNI: register_android_hardware_Radio DONE
07-27 09:17:01.437  4022  4022 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 09:17:01.443   789   802 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
07-27 09:17:01.443   789   802 I ActivityManager: Killing 3053:com.test.thalitest/u0a26 (adj 0): stop com.test.thalitest
07-27 09:17:01.478   789   957 D GraphicsStats: Buffer count: 2
07-27 09:17:01.478   789   957 I WindowState: WIN DEATH: Window{6e17904 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:17:01.478   789   990 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3f0a6b1)
07-27 09:17:01.478   789   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:17:01.479   789   892 D WifiService: Client connection lost with reason: 4
07-27 09:17:01.479   789   893 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:17:01.531   789   813 W PackageSettings: Skipping PackageSetting{2516661 com.example.hello/10116} due to missing metadata
07-27 09:17:01.559   789   802 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-27 09:17:01.559   789   802 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-27 09:17:01.561   789   802 E ActivityManager: Failure starting process com.test.thalitest
07-27 09:17:01.561   789   802 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-27 09:17:01.561   789   802 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:01.561   789   802 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:17:01.561   789   802 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:01.561   789   802 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 09:17:01.561   789   802 I ActivityManager:   Force finishing activity ActivityRecord{cfcd986 u0 com.test.thalitest/.MainActivity t46}
07-27 09:17:01.565   789  1364 W ActivityManager: Spurious death for ProcessRecord{e271796 0:com.test.thalitest/u0a26}, curProc for 3053: null
07-27 09:17:01.569   789   813 I art     : Starting a blocking GC Explicit
07-27 09:17:01.622   789   813 I art     : Explicit concurrent mark sweep GC freed 74439(4MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 25MB/38MB, paused 723us total 45.574ms
07-27 09:17:01.633   789   813 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-27 09:17:01.635  4022  4022 I art     : System.exit called, status: 0
07-27 09:17:01.635  4022  4022 I AndroidRuntime: VM exiting with result code 0.
07-27 09:17:01.647   789   813 I ActivityManager: Start proc 4039:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
07-27 09:17:01.647   789   813 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
07-27 09:17:01.701   789   802 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-27 09:17:01.709  3198  3198 D BluetoothMapAppObserver: onReceive
07-27 09:17:01.709  3198  3198 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-27 09:17:01.711  1275  1587 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 09:17:01.712   789   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 09:17:01.764   789   889 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-27 09:17:01.765  2123  2140 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj0C1692926) - 
07-27 09:17:01.766  2123  4069 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
--------- beginning of crash
07-27 09:17:01.771  2123  2140 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
07-27 09:17:01.771  2123  2140 E AndroidRuntime: Process: android.process.acore, PID: 2123
07-27 09:17:01.771  2123  2140 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:17:01.771  2123  2140 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:01.779  1315  1315 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-27 09:17:01.784   789   990 I ActivityManager: Start proc 4074:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
07-27 09:17:01.792  2123  2140 I Process : Sending signal. PID: 2123 SIG: 9
07-27 09:17:01.797   789  4079 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:17:01.797   789  4079 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:17:01.797   789  4079 E DropBoxManagerService: 	... 5 more
07-27 09:17:01.798   789  1364 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3053 uid 10026
07-27 09:17:01.827  4074  4074 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-27 09:17:01.832   789   789 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED

```
