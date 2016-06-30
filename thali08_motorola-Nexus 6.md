#### Test 757892682551a10_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
06-30 13:52:43.632  3270  3308 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
06-30 13:52:43.692  3270  3308 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
06-30 13:52:43.716  3270  3308 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 13:52:43.791  1896  2144 I Icing   : Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
06-30 13:52:43.856  1896  2144 D Icing   : Loaded CLD2 Version V2.0 - 20141016
06-30 13:52:43.948  1896  2144 I Icing   : Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,06-30 13:52:45.720  3317  3317 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:52:45.725  3317  3317 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:45.767  3317  3317 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:52:45.817  3317  3317 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:52:45.839  3317  3317 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 13:52:45.843   874   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:52:45.886  1811  1829 W SearchService: Abort, client detached.
06-30 13:52:45.905  1811  1811 I HotwordDetector: Closing mic
06-30 13:52:45.906  1811  2116 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c9406cf
06-30 13:52:45.906  1811  2123 E AudioRecord-JNI: Error -4 during AudioRecord native read
06-30 13:52:45.915  3317  3317 D AndroidRuntime: Shutting down VM
06-30 13:52:45.932   874  1853 I ActivityManager: Start proc 3326:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 13:52:45.942  1811  1811 W ErrorReporter: reportError [type: 29, code: 917507]: null
06-30 13:52:45.970   375  2125 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 13:52:45.971   375  2125 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
06-30 13:52:45.981   375  1289 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
06-30 13:52:45.982  1811  2120 I MicroRecognitionRnrImpl: Stopping hotword detection.
06-30 13:52:45.983  1811  2121 I MicroRecognitionRnrImpl: Detection finished
06-30 13:52:46.006  3326  3326 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-30 13:52:46.026  3326  3326 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 13:52:46.033  3326  3326 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7111-7114)
06-30 13:52:46.033  3326  3326 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:46.046  3326  3326 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {926b939}
06-30 13:52:46.046  3326  3326 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:46.048  3326  3326 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:46.055  3326  3326 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:46.056  3326  3326 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:46.085  3326  3341 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 13:52:46.092  3326  3326 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 13:52:46.103  3326  3326 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:46.103  3326  3326 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:46.103  3326  3326 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 13:52:46.103  3326  3326 I Adreno  : Build Date                       : 10/20/15
06-30 13:52:46.103  3326  3326 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 13:52:46.103  3326  3326 I Adreno  : Local Branch                     : M14
06-30 13:52:46.103  3326  3326 I Adreno  : Remote Branch                    : 
06-30 13:52:46.103  3326  3326 I Adreno  : Remote Branch                    : 
06-30 13:52:46.103  3326  3326 I Adreno  : Reconstruct Branch               : 
,06-30 13:52:46.197   874   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6819320:true
,06-30 13:52:46.229  3326  3326 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:52:46.241  3326  3326 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,06-30 13:52:46.327  3326  3363 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:46.341  3326  3350 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 13:52:46.380  3326  3363 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:46.448   874   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +533ms
,06-30 13:52:46.454  1664  1664 I Keyboard.Facilitator: onFinishInput()
,06-30 13:52:46.508  3326  3326 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3326
,06-30 13:52:46.635  3326  3326 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:52:46.733   874  1760 I ActivityManager: Killing 2326:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,06-30 13:52:46.781   874  1760 I ActivityManager: Killing 3004:com.qualcomm.telephony/1001 (adj 15): empty #18
,06-30 13:52:46.860  3326  3365 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1714816720
,06-30 13:52:46.872  3326  3365 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:46.872  3326  3365 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:46.872  3326  3365 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:46.872  3326  3365 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:46.872  3326  3365 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 13:52:46.872  3326  3365 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d08a6d added. We now have 1 listener(s)
06-30 13:52:46.875  3326  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,06-30 13:52:46.876  3326  3365 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
06-30 13:52:46.876  3326  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:46.876  3326  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 13:52:46.879  3326  3365 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5712f0 added. We now have 1 listener(s)
,06-30 13:52:46.880  3326  3365 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:52:46.884  3326  3365 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:46.884   874  1320 D WifiService: New client listening to asynchronous messages
06-30 13:52:46.884  3326  3365 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 13:52:46.885  3326  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:46.885  3326  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 13:52:46.885  3326  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:46.885  3326  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 13:52:46.886  3326  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:52:46.887  3326  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,06-30 13:52:46.888  3326  3365 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:46.888  3326  3365 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:46.888  3326  3365 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-30 13:52:46.888  3326  3365 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:46.889  3326  3365 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:52:47.057  3326  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:52:47.060  3326  3326 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:47.700  1521  1521 I ConfigService: onDestroy
06-30 13:52:47.806  3326  3373 W jxcore-log: Initializing JXcore engine
06-30 13:52:47.806  3326  3373 W jxcore-log: JXcore engine is ready
06-30 13:52:47.850  3373  3373 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
06-30 13:52:47.850  3373  3373 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10638]" dev="sockfs" ino=10638 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 13:52:47.850  3373  3373 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 13:52:47.850  3373  3373 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24275]" dev="sockfs" ino=24275 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 13:52:47.863  3326  3373 W jxcore-log: Starting JXcore engine
06-30 13:52:47.945  3326  3373 W jxcore-log: Platform android
06-30 13:52:47.945  3326  3373 W jxcore-log: 
06-30 13:52:47.945  3326  3373 W jxcore-log: Process ARCH arm
06-30 13:52:47.945  3326  3373 W jxcore-log: 
06-30 13:52:48.155  3326  3373 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:48.155  3326  3373 I jxcore-log: 
06-30 13:52:48.155  3326  3373 W jxcore-log: JXcore engine is started
06-30 13:52:48.166  3326  3365 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 13:52:48.167   874   884 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-30 13:52:48.179  3326  3326 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-30 13:52:48.180  3326  3326 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 13:52:48.186  3326  3365 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 13:52:48.203   874  1743 I ActivityManager: Start proc 3376:com.android.packageinstaller/u0a69 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 13:52:48.276  3376  3376 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 13:52:48.419  3376  3388 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:48.521  3376  3388 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 13:52:48.521  3376  3388 I Adreno  : Build Date                       : 10/20/15
06-30 13:52:48.521  3376  3388 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 13:52:48.521  3376  3388 I Adreno  : Local Branch                     : M14
06-30 13:52:48.521  3376  3388 I Adreno  : Remote Branch                    : 
06-30 13:52:48.521  3376  3388 I Adreno  : Remote Branch                    : 
06-30 13:52:48.521  3376  3388 I Adreno  : Reconstruct Branch               : 
,06-30 13:52:48.531  3376  3388 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:48.556  1664  1664 I Keyboard.Facilitator: onFinishInput()
,06-30 13:52:48.617   874   893 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +432ms
,06-30 13:52:48.788  3326  3326 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7d284d7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@adbe962, 16908290=android.view.AbsSavedState$1@adbe962}, android:focusedViewId=100}]}]
06-30 13:52:48.788  3326  3326 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 13:52:57.011   874   888 I ActivityManager: Waited long enough for: ServiceRecord{4dd4cc4 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,06-30 13:53:02.425  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:02.449  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:02.455  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:02.513  1521  2676 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:53:02.514  1521  2676 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:53:02.514  1521  2676 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:53:02.514  1521  2676 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:53:02.578  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:02.579  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 13:53:02.581  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 13:53:18.833   874   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 13:53:18.844  1664  1664 I Keyboard.Facilitator: onFinishInput()
,06-30 13:53:18.847   874   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 13:53:18.847   874   895 I Adreno  : Build Date                       : 10/20/15
06-30 13:53:18.847   874   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 13:53:18.847   874   895 I Adreno  : Local Branch                     : M14
06-30 13:53:18.847   874   895 I Adreno  : Remote Branch                    : 
06-30 13:53:18.847   874   895 I Adreno  : Remote Branch                    : 
06-30 13:53:18.847   874   895 I Adreno  : Reconstruct Branch               : 
,06-30 13:53:18.906   281  1834 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (626 us)
,06-30 13:53:19.616   874   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 13:53:19.632  3326  3326 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-30 13:53:19.632  3326  3326 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
06-30 13:53:19.640   874   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 13:53:19.643   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,06-30 13:53:19.643   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
06-30 13:53:19.643   874   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,06-30 13:53:19.873   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,06-30 13:53:19.876   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,06-30 13:53:19.881   874  1344 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,06-30 13:53:19.884   874   895 I DreamManagerService: Entering dreamland.
,06-30 13:53:19.885   874   895 I PowerManagerService: Dozing...
06-30 13:53:19.886   874   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,06-30 13:53:19.927   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,06-30 13:53:19.927   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,06-30 13:53:19.935   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 13:53:19.938   874  1318 E native  : do suspend false
,06-30 13:53:20.028  1713  3402 D NfcService: Discovery configuration equal, not updating.
,06-30 13:53:20.079   375  1290 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,06-30 13:53:20.080   375  1290 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,06-30 13:53:20.082   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 13:53:20.092   874  1318 E native  : do suspend true
,06-30 13:53:24.138  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:24.156  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:24.162  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:24.224  1840  2325 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:24.239  1521  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:53:24.239  1521  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:53:24.240  1521  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:53:24.240  1521  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:53:24.295  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:24.297  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 13:53:24.300  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 13:53:50.406  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:50.417  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:50.421  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:50.469  1521  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:53:50.470  1521  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:53:50.470  1521  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 13:53:50.470  1521  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:53:50.519  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:50.519  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:53:50.520  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 13:54:10.721  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:10.727  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:10.730  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:10.770  1521  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:54:10.771  1521  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:54:10.771  1521  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:54:10.771  1521  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:54:10.808  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:54:10.808  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:54:10.808  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 13:54:18.850  1664  1777 I Keyboard.Facilitator.LanguageModelFlusher: run()
,06-30 13:54:18.850  1664  1777 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 13:54:18.887  1521  1521 I ConfigService: onCreate
,06-30 13:54:23.927  1521  1521 I ConfigService: onDestroy
,06-30 13:56:19.908  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:19.916  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:19.918  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:19.964  1521  1971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 13:56:19.965  1521  1971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 13:56:19.966  1521  1971 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:56:19.966  1521  1971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:56:19.995  1521  1971 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:56:19.995  1521  1971 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:56:19.995  1521  1971 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:56:19.995  1521  1971 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:56:19.995  1521  1971 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:56:19.995  1521  1971 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:56:19.995  1521  1971 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:56:20.006  2597  2630 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:56:20.006  2597  2630 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:56:20.006  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:56:20.006  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:56:20.006  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:56:20.006  2597  2630 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:56:20.006  2597  2630 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:20.084  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:20.099  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:20.105  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:20.167  1521  2676 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:01:20.168  1521  2676 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:01:20.168  1521  2676 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:01:20.169  1521  2676 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:01:20.211  1521  2676 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:01:20.211  1521  2676 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:01:20.211  1521  2676 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:01:20.211  1521  2676 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:01:20.211  1521  2676 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:01:20.211  1521  2676 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:01:20.211  1521  2676 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:20.221  2597  2630 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:01:20.221  2597  2630 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:01:20.221  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:01:20.221  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:01:20.221  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:01:20.221  2597  2630 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:01:20.221  2597  2630 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:20.280  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:20.305  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:20.313  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:20.400  1521  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:06:20.400  1521  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 14:06:20.401  1521  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 14:06:20.401  1521  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:06:20.451  1521  1534 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:06:20.451  1521  1534 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:06:20.451  1521  1534 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:06:20.451  1521  1534 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:06:20.451  1521  1534 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:20.451  1521  1534 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:20.451  1521  1534 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:20.467  2597  2630 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:06:20.467  2597  2630 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:06:20.467  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:06:20.467  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:06:20.467  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:06:20.467  2597  2630 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:06:20.467  2597  2630 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:06.898   874   887 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:11:20.616  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:20.632  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:20.637  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:20.701  1521  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:11:20.701  1521  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:11:20.701  1521  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:11:20.702  1521  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:11:20.742  1521  2260 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:11:20.742  1521  2260 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:11:20.742  1521  2260 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:11:20.742  1521  2260 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:11:20.742  1521  2260 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:11:20.742  1521  2260 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:11:20.742  1521  2260 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:20.751  2597  2630 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:11:20.751  2597  2630 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:11:20.751  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:11:20.751  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:11:20.751  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:11:20.751  2597  2630 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:11:20.751  2597  2630 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:16:20.804  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 14:16:20.825  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 14:16:20.828  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 14:16:20.902  1521  1971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 14:16:20.903  1521  1971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:16:20.903  1521  1971 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:16:20.903  1521  1971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-30 14:16:20.943  1521  1971 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:16:20.943  1521  1971 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:16:20.943  1521  1971 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:16:20.943  1521  1971 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:16:20.943  1521  1971 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:16:20.943  1521  1971 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:16:20.943  1521  1971 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
06-30 14:16:20.957  2597  2630 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:16:20.957  2597  2630 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:16:20.957  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:16:20.957  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:16:20.957  2597  2630 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:16:20.957  2597  2630 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:16:20.957  2597  2630 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
06-30 14:16:24.290  3486  3486 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 14:16:24.295  3486  3486 D AndroidRuntime: CheckJNI is OFF
06-30 14:16:24.338  3486  3486 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 14:16:24.386  3486  3486 I Radio-JNI: register_android_hardware_Radio DONE
06-30 14:16:24.408  3486  3486 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 14:16:24.420   874   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
06-30 14:16:24.421   874   888 I ActivityManager: Killing 3326:com.test.thalitest/u0a0 (adj 1): stop com.test.thalitest
06-30 14:16:24.504   874  1320 D WifiService: Client connection lost with reason: 4
06-30 14:16:24.504   874  1729 D GraphicsStats: Buffer count: 3
06-30 14:16:24.505   874  1853 I WindowState: WIN DEATH: Window{3300450 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:16:24.582   874   898 W PackageSettings: Skipping PackageSetting{c11717c com.example.hello/10273} due to missing metadata
06-30 14:16:24.619   874   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
06-30 14:16:24.622   874   888 E ActivityManager: Failure starting process com.test.thalitest
06-30 14:16:24.622   874   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1324)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:3305)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
06-30 14:16:24.622   874   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:24.622   874   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:24.622   874   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:24.622   874   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
06-30 14:16:24.623   874   898 I art     : Starting a blocking GC Explicit
06-30 14:16:24.626   874   888 I ActivityManager:   Force finishing activity ActivityRecord{5271b31 u0 com.test.thalitest/.MainActivity t78}
06-30 14:16:24.631   874   888 I ActivityManager:   Force finishing activity ActivityRecord{e3a7eb2 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t78}
06-30 14:16:24.640   874   888 I ActivityManager: Killing 2683:com.google.android.calendar/u0a37 (adj 15): empty #17
06-30 14:16:24.671   874   898 I art     : Explicit concurrent mark sweep GC freed 42664(3MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 750us total 47.923ms
06-30 14:16:24.721   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
06-30 14:16:24.726   874   884 W ActivityManager: Spurious death for ProcessRecord{1eadf3a 0:com.test.thalitest/u0a0}, curProc for 3326: null
06-30 14:16:24.729  3486  3486 I art     : System.exit called, status: 0
06-30 14:16:24.729  3486  3486 I AndroidRuntime: VM exiting with result code 0.
06-30 14:16:24.745   281   281 W SurfaceFlinger: couldn't log to binary event log: overflow.
06-30 14:16:24.756   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
06-30 14:16:24.771   874   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
06-30 14:16:24.779  1840  2034 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 14:16:24.777  1664  1664 I Keyboard.Facilitator: resetDictionaries() : en_US
06-30 14:16:24.780   874  1309 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 14:16:24.783  3217  3217 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
06-30 14:16:24.800  1664  3502 I Keyboard.Facilitator.DecoderInitializer: run()
06-30 14:16:24.828  1724  1724 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
06-30 14:16:24.808  1664  3502 I Decoder : createOrResetDecoder
06-30 14:16:24.866  2756  2775 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
06-30 14:16:24.866  2756  2775 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj13A8B697B) - 
06-30 14:16:24.872  2756  3505 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-30 14:16:24.884  1521  1521 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
06-30 14:16:24.885  1521  1521 D AndroidRuntime: Shutting down VM
--------- beginning of crash
06-30 14:16:24.886  1521  1521 E AndroidRuntime: FATAL EXCEPTION: main
06-30 14:16:24.886  1521  1521 E AndroidRuntime: Process: com.google.process.gapps, PID: 1521
06-30 14:16:24.886  1521  1521 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
06-30 14:16:24.886  1521  1521 E AndroidRuntime: 	... 8 more
06-30 14:16:24.889   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 14:16:24.892   874  3507 E DropBoxManagerService: Can't write: system_app_crash
06-30 14:16:24.892   874  3507 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-30 14:16:24.892   874  3507 E DropBoxManagerService: 	... 5 more
06-30 14:16:24.892  1521  1521 I Process : Sending signal. PID: 1521 SIG: 9
06-30 14:16:24.899  2756  2775 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
06-30 14:16:24.899  2756  2775 E AndroidRuntime: Process: android.process.acore, PID: 2756
06-30 14:16:24.899  2756  2775 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:24.899  2756  2775 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: Can't write: system_app_crash
06-30 14:16:24.902   874  3508 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-30 14:16:24.902   874  3508 E DropBoxManagerService: 	... 5 more
06-30 14:16:24.905  1741  1837 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
06-30 14:16:24.911  2756  3505 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
06-30 14:16:24.915  2756  3505 I Process : Sending signal. PID: 2756 SIG: 9
06-30 14:16:24.916   874   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
06-30 14:16:24.916   874   887 E PackageManager: Failed to write settings, restoring backup
06-30 14:16:24.916   874   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
06-30 14:16:24.916   874   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
06-30 14:16:24.916   874   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
06-30 14:16:24.916   874   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
06-30 14:16:24.916   874   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
06-30 14:16:24.916   874   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:24.916   874   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:24.916   874   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:24.918   874   888 E DropBoxManagerService: Can't write: system_server_wtf
06-30 14:16:24.918   874   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
06-30 14:16:24.918   874   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-30 14:16:24.918   874   888 E DropBoxManagerService: 	... 13 more
06-30 14:16:24.921   874   884 I ActivityManager: Start proc 3509:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
06-30 14:16:24.921  1741  1837 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
06-30 14:16:24.921  1741  1837 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1741
06-30 14:16:24.921  1741  1837 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:24.921  1741  1837 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:24.923   874  1760 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
06-30 14:16:24.924   874  3514 E DropBoxManagerService: Can't write: system_app_crash
06-30 14:16:24.924   874  3514 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-30 14:16:24.924   874  3514 E DropBoxManagerService: 	... 5 more
06-30 14:16:24.925  1741  1837 I Process : Sending signal. PID: 1741 SIG: 9
06-30 14:16:24.933   874  1320 D WifiService: Client connection lost with reason: 4
06-30 14:16:24.939   874  1729 I ActivityManager: Process com.google.process.gapps (pid 1521) has died
06-30 14:16:24.940   874  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
06-30 14:16:24.940   874  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
06-30 14:16:24.940   874  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
06-30 14:16:24.940   874  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 31000ms
06-30 14:16:24.940   874  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 41000ms
06-30 14:16:24.998   874  1738 I ActivityManager: Start proc 3522:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
06-30 14:16:25.038  1896  1896 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 14:16:25.038  1896  1896 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 14:16:25.040   874  1388 D GraphicsStats: Buffer count: 2
06-30 14:16:25.040   874  1389 I WindowState: WIN DEATH: Window{f2ae7e9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
06-30 14:16:25.045   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1741) has died
06-30 14:16:25.046   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 20894ms
06-30 14:16:25.047   874  1738 I ActivityManager: Process android.process.acore (pid 2756) has died
06-30 14:16:25.048   874  1738 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 20893ms
06-30 14:16:25.057  1896  1896 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 14:16:25.057  1896  1896 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 14:16:25.071  1896  3536 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 14:16:25.087  1896  3536 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
06-30 14:16:25.087  1896  3536 E AndroidRuntime: Process: com.google.android.gms, PID: 1896
06-30 14:16:25.087  1896  3536 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-30 14:16:25.087  1896  3536 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
06-30 14:16:25.087   874   885 I ActivityManager: Start proc 3540:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
06-30 14:16:25.094  3522  3522 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
06-30 14:16:25.097   874  3551 E DropBoxManagerService: Can't write: system_app_crash
06-30 14:16:25.097   874  3551 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-30 14:16:25.097   874  3551 E DropBoxManagerService: 	... 5 more
06-30 14:16:25.104  3522  3522 I MultiDex: VM with version 2.1.0 has multidex support
06-30 14:16:25.105  1811  3537 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 14:16:25.105  1896  3536 I Process : Sending signal. PID: 1896 SIG: 9
06-30 14:16:25.135  3522  3522 I MultiDex: install
06-30 14:16:25.135  3522  3522 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 14:16:25.136  1811  3537 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 14:16:25.148  3522  3522 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
06-30 14:16:25.155  1811  3537 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
06-30 14:16:25.155  1811  3537 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
06-30 14:16:25.155  1811  3537 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1811
06-30 14:16:25.155  1811  3537 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:25.155  1811  3537 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:25.156   874   885 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
06-30 14:16:25.157   874   885 I ActivityManager: Killing 1811:com.google.android.googlequicksearchbox:search/u0a28 (adj 8): crash
06-30 14:16:25.157   874  3554 E DropBoxManagerService: Can't write: system_app_crash
06-30 14:16:25.157   874  3554 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-30 14:16:25.157   874  3554 E DropBoxManagerService: 	... 5 more
06-30 14:16:25.173  3522  3522 I GservicesProvider: Gservices pushing to system: true; secure/global: true
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
06-30 14:16:25.174  3522  3522 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
06-30 14:16:25.175  3522  3522 D AndroidRuntime: Shutting down VM
06-30 14:16:25.183  3522  3522 E AndroidRuntime: FATAL EXCEPTION: main
06-30 14:16:25.183  3522  3522 E AndroidRuntime: Process: com.google.process.gapps, PID: 3522
06-30 14:16:25.183  3522  3522 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
06-30 14:16:25.183  3522  3522 E AndroidRuntime: 	... 10 more
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
06-30 14:16:25.208  3540  3540 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
06-30 14:16:25.208  3540  3540 D AndroidRuntime: Shutting down VM
06-30 14:16:25.240   874  1320 D WifiService: Client connection lost with reason: 4
06-30 14:16:25.243  3509  3539 W GmsClient: service died
06-30 14:16:25.243  3509  3553 W GmsClient: service died
06-30 14:16:25.243   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
06-30 14:16:25.245  3509  3509 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
06-30 14:16:25.245  3509  3509 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
06-30 14:16:25.250   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
